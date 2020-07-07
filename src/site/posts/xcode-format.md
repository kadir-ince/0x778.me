---
title: Xcode Code Formatting
date: 2018-03-21
---

Xcode üzerinde default olarak gelen re-indent olarak geçen kod formatlama tekniği verimli olarak çalışmamaktadır (Yalnızca kodları sola yaslar ve aradaki boşluklara dokunmaz). Örnek olarak 👇🏻

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*_ybAnDbDx3xDt_oNCfYMvw.gif" style="width: 100%" alt="how to working gif">
</p>
Bu işi daha verimli hale getirebilmek için bir eklenti kullanıyoruz : SwiftFormat <br>
Eklentinin örnek çalışan hali 👇🏻

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*NqpcicIZzqH7PRhEU-nfGw.gif" style="width: 100%" alt="how to working gif">
</p>

## Nasıl Kurulur?

<br>

1. Adım <br>

Terminal ekranımıza <br>

`brew cask install swiftformat-for-xcode` <br>

kodunu yazıp enter dediğimizde Application klasörüne uygulama olarak SwiftFormat’ı kuruyor.

2. Adım <br>

İlk önce Applications klasörüne gelen “_SwiftFormat for Xcode_” uygulamasını açın ve daha sonra “System Preferences > Extensions > Xcode Source Editor” içerisinde _SwiftFormat for Xcode_ seçeneğini aktif hale getirin

3. Adım <br>

Xcode uygulamasını açıp Preferences > Key Binding içinde _swiftformat_ diye arama yaptığımızda karşımıza 3 seçenek çıkar:

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*cthYX0WxsOzlahRiMiVc-g.png" style="width: 100%" alt="how to working gif">
</p>

Format File → Bulunduğu dosyayı formatlar <br>

Format File seçeneğine bir kısayol atarsanız dosyayı ⌘A ile seçip atadığınız kısayola basarsanız kodunuz formatlanır.

## Bonus

Eğer proje yolunu terminalde açıp

`swiftformat .`

kodunu yazarsanız projedeki tüm dosyaları formatlar.

<p align="center">
  <img src="
https://miro.medium.com/max/1400/1*9QS4uxV75B82frIFzKUUdQ.png" style="width: 100%" alt="how to working gif">
</p>

## Kaynak:

**SwiftFormat** <br>
[![GitHub followers](https://img.shields.io/github/stars/nicklockwood/SwiftFormat?style=social)](https://github.com/nicklockwood/SwiftFormat)
