---
title: iOS 13 apps run on iOS 12
date: 2020-07-08
---

❗️This article will be translate to English <br>
iOS 13 ile birlikte geliştirme ortamına yeni özellikler eklenmiş bulunmaktadır fakat bu özellikler iOS 13 özelindedir ve alt sürümlerinde çalışmamaktadır. Eğer iOS 13 altında çalıştırmak istersek derleme zamanında şu şekilde hatalar almaktayız 👇🏻

<p align="center">
  <img src="https://miro.medium.com/max/1116/1*vdaagcxhELQ4xvVyeKnTWw.png" style="width: 100%" alt="how to working gif">
</p>

Bu hatayı önlemek için iOS 13'e özel işlemlerin bulunduğu classın üstüne: <br>
`@available(iOS 13.0, *)` <br>
satırını eklememiz gerekir.

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*RVQlQQZ3oyghdZpciauLbQ.png" style="width: 100%" alt="how to working gif">
</p>

Böylelikle iOS 13'e özel UI’lar yalnızca iOS 13 bulunan iPhone’lar üzerinde çalıştırılacaktır. <br>
Eğer bu şekilde başlatırsanız uygulama siyah bir ekran ile başlayacaktır çünkü UIWindow iOS 13 ile birlikte SceneDelegate dosyasına taşındı onu AppDelegate dosyasının içine geri alacağız. AppDelegate classının ilk satırına:
`var window: UIWindow?` <br>
satırını ekleyin ve artık iOS 12 cihazda çalıştırabilirsiniz 
