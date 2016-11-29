# LazLock Translation

###Language: en
LazLock is a lightweight, portable password manager that runs on both Windows and GNU/Linux.

It also has an option to create strong, random passwords for all of the websites that you visit, you only need to remember one password to unlock them all.

Your data is strongly protected with 128 bit AES encryption.

You can find it [here](https://sourceforge.net/projects/lazlock/).

The author of LazLock is [Christopher Hawkins](https://twitter.com/CyberFilth).

It's built with the [Free Pascal](http://www.freepascal.org) compiler and the [Lazarus](http://www.lazarus-ide.org) IDE.

This is an effort to have it translated and localised.

__maintainer:__ [Christopher Hawkins](https://github.com/cyberfilth)

##Locale Codes

I've started investigating about this.

Since LazLock is a Windows and GNU/Linux application I'll have to dig deep into what codes are supported in each platform.

For the time being, I've found that the supported ones,

 * Under Ubuntu are: `/usr/share/i18n/SUPPORTED`.
 * Under Windows are: [Answer on Stack Overflow](https://stackoverflow.com/a/3191729/8167).
 
Still not sure if we should use the `{2 lowercase letter code}(underscore){2 uppercase letter code}` or the more encompassing `{2 lowercase letter code}`.

Will have to discuss this with Christopher.

Things to take into consideration:

 * Investigate how the default translation process occurs under Lazarus.
 * Investigate a bit more about the `gettext` library.
 * Combine that knowledge with Windows own localization process.
 * Combine that knowledge with Linux own localization process.

##Translation Tools

###poedit

The most widly available tool that this effort has chosen is [poedit](https://poedit.net/).

It has versions for the main platforms: [download page](https://poedit.net/download).

Here's a [quick and dirty guide to `poedit`](https://flossvalley.blogspot.co.uk/2008/07/quick-and-dirty-guide-to-poedit.html).

###Installing `poedit`

####Windows

 1. Download the installer from the [download page](https://poedit.net/download).
 2. Run the installer and follow the instructions.
 3. Find the application on your `Start Menu`.
 
####GNU/Linux Debian/Ubuntu based

 1. You should have a version of it in your local repositories:
 2. `$ sudo apt-get update`
 3. `$ sudo apt-get install poedit`

####GNU/Linux Fedora based

 1. You should have a version of it in your local repositories:
 2. `$ yum install poedit`

###BetterPoEdit (Windows only)

While investigating for alternatives to `poedit` I've found: [Better PoEdit](https://sourceforge.net/projects/betterpoeditor/).

At this moment I'm just listing it here in case someone finds it more useful.

##Testing on Ubuntu
To start the application in a different language, under Ubuntu:

```bash
$ LANG={language} LANGUAGE={language} lazlock
```

An example with Portuguese(Portugal):

```bash
$ LANG=pt_PT.UTF-8 LANGUAGE=pt_PT.UTF-8 lazlock
```

For more information on temporarily changing your language:

 * [Is it possible to change language for user interface temporarily?](https://askubuntu.com/questions/246547/is-it-possible-to-change-language-for-user-interface-temporarily)
 * [Why is overriding the LANG environment variable not changing the language for me?](https://askubuntu.com/questions/311767/why-is-overriding-the-lang-environment-variable-not-changing-the-language-for-me)

##Testing on Windows

At the moment I'm still investigating how we can replicate the procedures that are listed above on 'Testing on Ubuntu' on the Windows platform.

###Language: de
LazLock is a lightweight, portable password manager that runs on both Windows and GNU/Linux.

It also has an option to create strong, random passwords for all of the websites that you visit, you only need to remember one password to unlock them all.

Your data is strongly protected with 128 bit AES encryption.

You can find it [here](https://sourceforge.net/projects/lazlock/).

The author of LazLock is [Christopher Hawkins](https://twitter.com/CyberFilth).

It's built with the [Free Pascal](http://www.freepascal.org) compiler and the [Lazarus](http://www.lazarus-ide.org) IDE.

This is an effort to have it translated and localised.

__maintainer:__ 

###Language: es
LazLock is a lightweight, portable password manager that runs on both Windows and GNU/Linux.

It also has an option to create strong, random passwords for all of the websites that you visit, you only need to remember one password to unlock them all.

Your data is strongly protected with 128 bit AES encryption.

You can find it [here](https://sourceforge.net/projects/lazlock/).

The author of LazLock is [Christopher Hawkins](https://twitter.com/CyberFilth).

It's built with the [Free Pascal](http://www.freepascal.org) compiler and the [Lazarus](http://www.lazarus-ide.org) IDE.

This is an effort to have it translated and localised.

__maintainer:__ 

###Language: fr
LazLock is a lightweight, portable password manager that runs on both Windows and GNU/Linux.

It also has an option to create strong, random passwords for all of the websites that you visit, you only need to remember one password to unlock them all.

Your data is strongly protected with 128 bit AES encryption.

You can find it [here](https://sourceforge.net/projects/lazlock/).

The author of LazLock is [Christopher Hawkins](https://twitter.com/CyberFilth).

It's built with the [Free Pascal](http://www.freepascal.org) compiler and the [Lazarus](http://www.lazarus-ide.org) IDE.

This is an effort to have it translated and localised.

__maintainer:__ 

###Language: pt_PT
Lazlock é uma aplicação leve e portável que gere palavras passe e corre em Windows e GNU/Linux.

Tem também facilidades para criar palavras passe com forte segurança para todos os sítios web que visita.  
Só precisa de se lembrar de uma única palavra passe para aceder às restantes.

Os seus dados estão protegidos com encriptação de 128 bits AES.

Pode encontrar a aplicação [aqui](https://sourceforge.net/projects/lazlock/).

O autor da aplicação LazLock é [Christopher Hawkins](https://twitter.com/CyberFilth).

Esta aplicação foi desenvolvida com o compilador [Free Pascal](http://www.freepascal.org) e o ambiente de desenvolvimento [Lazarus](http://www.lazarus-ide.org).

Este repositório é um esforço para traduzir a aplicação.

__maintainer:__ [Gustavo Carreno](https://github.com/gcarreno)

###Language: pt_BR
Lazlock é uma aplicação leve e portátil que gera senhas e roda em Windows e GNU/Linux.

Também facilita a criação de senhas com forte segurança para todos os sites que visitar.  
Só é preciso se lembrar de uma única senha para ter acesso às restantes.

Os seus dados estão protegidos com encriptação de 128 bits AES.

Pode encontrar a aplicação [aqui](https://sourceforge.net/projects/lazlock/).

O autor da aplicação LazLock é [Christopher Hawkins](https://twitter.com/CyberFilth).

Esta aplicação foi desenvolvida com o compilador [Free Pascal](http://www.freepascal.org) e o ambiente de desenvolvimento [Lazarus](http://www.lazarus-ide.org).

Este repositório é um esforço para traduzir a aplicação.

__maintainer:__ [Alex K.](https://github.com/alexkleinubing)
