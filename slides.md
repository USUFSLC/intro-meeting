# Welcome to Free Software and Linux Club!

This meeting should be streaming at [https://linux.usu.edu/streams](https://linux.usu.edu/streams).

```elixir
defmodule IntroMeeting do
  def here(you) do
    you
    |> relax
    |> learn_about(:what_fslc_does)
    |> learn_about(:free_software)
    |> learn_about(:linux)
  end
end
```

---

# Names & People

| Name           | Discord       | Role               |
|----------------|---------------|--------------------|
| Erik Falor     | @fadein       | Advisor            |
|----------------|---------------|--------------------|
| Elizabeth Hunt | @simponic     | President          |
|----------------|---------------|--------------------|
| Kyler Nelson   | @kytech       | Vice President     |
|----------------|---------------|--------------------|
| Richard Snider | @CodeTriangle | Secretary          |
|----------------|---------------|--------------------|

---

# Cool Stuff from the FSLC Club

Not only are we a community of free software and linux lovers, a lot of us are hackers and tinkerers who make new stuff, teach old stuff new tricks, and sometimes break stuff (because that can be fun too!). Many of us tinker with both hardware and software. Here's a small sample of some of what we have built using free software (and/or our own hacking on things).

## FSLC Club Software

* USUPrintCL - Because printing on campus should support Linux and ChromeOS, dang it!
* [linux.usu.edu](https://linux.usu.edu) - Club website
* Trongleposting - World's best chat message full of glorious easter-eggs, perfect for memeing

## Projects from Club Members

* CheSSH | Lizzy Hunt - Multiplayer chess on the command-line (more on this in our SSH night meeting!)
* JoinLater - Since eduroam's JoinNow on Linux is so hopelessly broken, we have JoinLater!

## Other Things we Do

Have an idea you want to explore, but don't know where to start? Diving into Linux or other free software, but you're feeling a bit stuck or lost? Just want to chat about some cool tech, interesting gadgets, tech news, and more? Our Discord server is our club's hub for most of our club communication. We always enjoy helping others learn and discover free software and technology, so questions are always welcome. We even have a dedicated tech support channel if you run into roadblocks or issues while using Linux or other software. We've also got a great memes channel :)

---

# What is Free Software?

From the [Free Software Foundation](https://www.gnu.org/philosophy/free-sw.en.html):

> "Free software" means software that respects users' freedom and community. Roughly, it means that the *users have the freedom to run, copy, distribute, study, change and improve the software*. Thus, "free software" is a matter of liberty, not price. To understand the concept, you should think of "free" as in "free speech," not as in "free beer." We sometimes call it "libre software," borrowing the French or Spanish word for "free" as in freedom, to show we do not mean the software is gratis.

## Free Software You've Probably Heard of

* [Linux](https://www.kernel.org/)
* [Firefox](https://www.mozilla.org/en-US/firefox/new/)
* [Open Broadcaster Software](https://obsproject.com/)
* [VLC](https://www.videolan.org/vlc/)
* [Audacity](https://www.audacityteam.org/)
* [GIMP](https://www.gimp.org/)
* [Inkscape](https://inkscape.org/)
* [Blender](https://www.blender.org/)

The ethos of free software encourages the hacking culture that was extremely prevalant during the early days of the internet. Free software is now the foundation that underpins most of the modern computing world today!

---

# Why is Free Software a Big Deal?

Other than the fact that most "free software" is actually free of charge (*nice*), free software does all the following:

* Provides the OS for 98.1% of the world's top million servers (96.3% Linux, 1.8% FreeBSD)
  * AWS, Azure, and Google Cloud use Linux as their OS of choice
* Provides the core for the world's most popular mobile phone OS (Android)
  * Android is a Linux-based OS, developed and maintained by Google
* Powers space vehicles, like Inginuity (Inginuity is powered by Linux - first powered, controlled flight on another planet)
* Runs almost all supercomputers and many robots
* Provides the core backbone of the world-wide web

## Cool Things You Can Do With Free Software

* Run your own web server
* Host a game server for your friends
* Breathe new life into an old computer
* Access your computer from anywhere in the world
* Become a master at the OS used to run most software written and used by engineers
  * Not only does most of what a software engineer write end up deployed to Linux, but many other engineering fields use Linux extensively.
* Make your computer do what you wish it always did
  * That includes making it look and work however you want if you're super into customization

## Crazier Things You Can Do With Free Software

* Make it so you can run a python interpreter on your phone (Termux on Android)
* Make things do stuff that it was never intended to do
  * Like make a [Wii](https://www.youtube.com/watch?v=mrdR43-sqKs) or an [OG iPod](http://www.ipodlinux.org/) run Linux
  * Trick your car into believing that a [raspberry pi is an ipod](https://github.com/Kytech/ipod) to add bluetooth
* Look like a "real hacker"
* And so much more


---

# A Little Bit of Terminology

In addition to the term "free software", there's a few other terms that you'll often hear. Just to make sure everyone knows what we are talking about, here's some common terns:


## What is a "Terminal"?

A terminal is a text-based interface to the computer. It is used to run commands and programs, and is the fastest way to interact with the computer when using Linux. Make a folder? Easy. Install a program? Easy (most of the time). Run a program? Easy. No double clicking or clicking through menus.

## What is a "Package Manager"?

Package managers are programs that allow you to install, update, and remove software. They are the easiest way to install software on Linux. Some insane people love to patiently wait halves of hours to compile their software.

## What is a "Desktop Environment"?

A desktop environment is a collection of programs that provide a graphical user interface (GUI) for the user. Some popular desktop environments include GNOME, KDE, and XFCE.

## Additional Terminology

* Software License - Determines who can use a piece of software and how. Good ones give you permission to do things that you wouldn't be able to do before.
* Open Source - Code that makes its source code available to the public. (Think stuff on GitHub)
* FOSS - Free and Open Source Software. Software that is both "free software" meaning the sense that it grants you lots of freedom in what it permits you to do and is open source.
  * Not all open source code is "free software" because it may not allow you to have certain freedoms in how the code is used (ex. can't redistribute it to someone else). Think free as in freedom, not free as in no money.
* Proprietary software - Software where you can't do anything other than use it as it is given to you. Opposite of free software and is very typical for paid software.
* Distro - A distribution of Linux (more on Linux in a moment)
* Terminal/Shell/Command-Line - Typically, when someone says this, they're referring to the text-based command-line interface on a computer. There are slight differences between each of these, but we'll spare you the details.

---

# Free Software and Linux - A Brief History

## 1950s - 1970s : Computers as an Area of Research Drives Collaboration

Software was often shared freely between universities and research labs. Some universities even placed restrictions on the usage of non-free software, requiring published source code in used programs. A prime example of collaboration in this time period is the creation of [MULTICS](https://en.wikipedia.org/wiki/Multics) (Multiplexed Information and Computing Service), which was a joint effort between MIT, Bell Labs (now AT&T), and General Electric started in 1964 to create a multi-user operating system.

## 1970s - 1980s : Growth of Proprietary Software and UNIX

Building software primarily for market sale gave system developers incentive to keep their software proprietary - normally providing binary distributions that are hard to analyze and study. UNIX, the most widely used multitasking multiuser operating system in academic circles, and eventually the corporate world, at the time was released as proprietary software by Bell Labs.

In the late 1970's, a group of programmers at the University of California, Berkeley, began work on a free clone of UNIX, aptly named Berkeley Software Distribution (BSD). Unfortunately it eventually came under legal trouble from AT&T in 1992 during the "UNIX wars".

An interesting milestone: in 1980, copyright law was amended to protect software.

---

# Free Software and Linux - A Brief History (cont.)

## 1980s - 1990s : The GNU Project, POSIX as a Standard

Richard Stallman, tired of the new trends of constraints on software, starts the GNU ("GNU's Not Unix") project in 1983 to shift the software development world back to "hacking culture". He creates GNU, aiming to create a complete operating system entirely built with free software. In 1985, Stallman also creates the Free Software Foundation (FSF) to promote the use of free software.

The GNU project introduced the idea of copyleft, which would allow usage of the software under any purpose, even commercially, so long as the source code was made available with the software.

In 1988 the POSIX release was standardized to allow for compatibility between all UNIX-like operating systems. This was a major milestone for the free software movement, as it allowed for the creation of free UNIX-like operating systems that could run standard software.

## 1990s - Present : Linux and the Free Software Movement

In 1991 Linus Torvalds releases his "hobby project" - the Linux kernel, built with the the GNU tools. Initially released under a proprietary license, Linus later moves to the GNU General Public License (GPL) in 1992.

Today, the FSF and the GNU project are still very active, and the Linux kernel is arguably the most used piece of free software in the world.

---

# What is Linux?

Linux is a free and open source operating system kernel - the core of the operating system, responsible for process scheduling, memory management, managing which code runs in user space vs kernel space, among other ridiculously hard tasks. Linux, in combination with GNU (or alternative) tools, is the basis for many operating systems including Android, Chrome OS, and Ubuntu.

## Distributions

Linux distributions are full operating systems built on top of the Linux kernel, often bundled with free software. Some popular distributions include:

* [Ubuntu](https://ubuntu.com/)
* [Debian](https://www.debian.org/)
* [Fedora](https://getfedora.org/)
* [Arch Linux](https://www.archlinux.org/)
* [EndeavourOS](https://endeavouros.com/)

Distributions can be built on top of other distributions, and are often referred to as "derivatives". For example, Ubuntu is a derivative of Debian, and EndeavourOS is a derivative of Arch Linux.

![distro tree](https://upload.wikimedia.org/wikipedia/commons/b/b5/Linux_Distribution_Timeline_21_10_2021.svg)

---

# Pros for Linux

# It's Easy

Linux, at most points, is only as hard as you make it. There are many distributions that are designed to be easy to use, and many distributions that are designed to be easy to customize, with a bit of work.

Anecdotally, many people switching from Windows find that beginner-friendly distros are just plain easier to use than Windows for a lot of their day to day activities.

# It's Secure

When it comes to proprietary software, companies have to make a bet that the work they do is better than the work the entire volunteer community can reverse engineer and sidestep. This is a bet that is often lost, especially in C-land where just creating a variable length string may open an entire can of worms.

# It's Private

It's easy to audit the code, and you can almost be certain that your software is not sending your data to a third party without permission.

# It's Flexible

Can be extremely easy to use, or very power-user focused. Runs on anything from embedded devices to supercomputers.

# It's In-Demand

Linux skills are one of the most sought-after in the industry right now
* Critical knowledge for those interested in Dev-Ops or Cloud Infrastructure
* Stand-out skills to have for software engineering - Provides a strong differentiating skill

---

# Cons for Linux

# It's Too Beautiful

Linux users love to make their desktops as pretty as possible, in a mating ritual known as "ricing".

[r/unixporn](https://www.reddit.com/r/unixporn/) is a subreddit dedicated to showcasing the beauty of Linux desktops.

# It's Just Too Blazingly Fast

You can configure Linux to be incredibly lightweight and run on any hardware, no matter its power level. And with hardware with a power level over 9000, it uses every single piece).

# It's Too Cheap

Students are debt ridden and poor.

Linux can be installed at no cost.

# It's Too Powerful!

Linux lets you make your computer or server do pretty much whatever you want it to do. No artificial barriers thrown up in your face for no reason!

It's simple. Make the switch today.

---

# Other Stuff

## What is a "Text Editor"?

This is a topic that comes up regularly in this club, so we thought you should know :)

Saved the most heated topic for last :).

A text editor is a program that allows you to edit source code and other text files.

The best is obviously Vim (or neovim), and everyone who disagrees can face ASCII MAN:  ̿̿ ̿̿ ̿̿ ̿'̿'\̵͇̿̿\з=(•̀益•́)=ε/̵͇̿̿/’̿’̿ ̿ ̿̿ ̿̿.

However, some utterly deranged people swear by Emacs as if their lives depended on it.

And then there are the people who use actual IDEs. They are the ones who actually get stuff done.

---

# The End

Go out and seek your FOSS and Linux adventure - it's calling to you!

