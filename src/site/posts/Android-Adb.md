---
title: How to Use Adb on Android?
date: 2020-07-09
---

❗️This article will be translate to English <br>

Android Studio üzerinde geliştirdiğimiz uygulamaları gerçek cihazımda test etmek istediğimizde kablo tak çıkar ile uğraşmak istemeyiz Android Studio .apk dosyasını wifi üzerinden telefona iletip kurması işlerimizi çok daha kolaylaştırmaktadır hem telefon gereksiz yere şarj olmaz ve laptop kullanıyorsanız şarjınız gitmez hem kablo ile uğraşmayız. Bunun için bu yazımızda adb komutlarını öğreneceğiz.

**1. Adım** <br>
Telefonumuzu bir kereye mahsus usb ile bilgisayarımıza bağlıyoruz ve terminal ekranını açıp <br>
`adb tcpip 555` <br>
komutunu giriyoruz ve usb kablosunu çıkarabiliriz. <br>
**2. Adım** <br>
Telefonumuzundan Ayarlar — Wifi üzerinden bulunduğumuz ağın detaylarına geliyoruz ve oradaki ip adresimizi alıyoruz örnek olarak 👇🏻

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*Sv_oscOdTqagOiezYg5_PA.jpeg" style="width: 100%" alt="how to working gif">
</p>

3. Adım
   Terminal ekranımıza <br>
   `adb connect 192.168.1.xx:5555` <br>
   komutunu giriyoruz (xx bölümüne kendi ip adresinizi giriyorsunuz. <br>
   Örnek olarak — > (_adb connect 192.168.1.42:5555_)

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*QLsV9LrLBua6WRm7ezLlWg.png
" style="width: 100%" alt="how to working gif">
</p>
connected to şeklinde mesajı aldığınızda başarıyla bağlanmış oluyoruz.
Android Studio üzerinde cihazlar bölümünde cihazımız tanınmış bir şekilde gözükecektir.

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*cCR9kZibOsvPYzZ0Cg7YSw.png" style="width: 100%" alt="how to working gif">
</p>