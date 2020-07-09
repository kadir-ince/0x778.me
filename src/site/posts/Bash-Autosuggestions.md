---
title: Bash Autosuggestions
date: 2020-07-09
---

❗️This article will be translate to English <br>

<p align="center">
  <img src="https://i.ibb.co/2PSYXMW/fish.png" style="width: 100%" alt="how to working gif">
</p>

Kurulumlan için Mac cihazınızda <a href="https://brew.sh">Brew</a>'in kurulu olması gerekmektedir. Kurulum için terminal ekranına aşağıdaki kodu yazınız: <br>
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"` <br>
Terminalinizi kapatıp açtığınızda Brew kurulmuş olacaktır.
Terminalde kod öneri sistemini Fish Shell üstlenecektir bu yüzden Brew üzerinden Fish Shell'i kurmaya geçelim: <br>

**1.adım** <br>
`brew install fish`

**2.adım** <br>
`chsh -s /usr/local/bin/fish`

Sizden bilgisayar şifrenizi soracaktır girdiğinizde default shelli Fish Shell yapacaktır. <br>
Terminalinizi kapatıp açtığınızda Fish Shell kullanıma hazırdır.

### Bonus

Eğer Visual Studio Code üzerindeki terminali de Fish Shell'e geçirmek isterseniz vs code üzerindeki terminalden "Select Default Shell" diyerek kullanabilirsiniz.

<p align="center">
  <img  src="https://i.ibb.co/9s1XGZ0/Screen-Shot-2020-07-09-at-16-36-08.png" style="width: 100%" alt="how to working gif">
</p>

**Kaynak**: <br>
<a href="https://https://fishshell.com">FishShell</a>
