---
fontsize: 9pt
---
# Welcome to Free Software and Linux Club!

This meeting should be streaming at [https://stream.linux.usu.edu](https://stream.linux.usu.edu/).

```elixir
defmodule IntroMeeting do
  def here(you) do
    you
    |> relax
    |> add_to_inventory(:pizza_slice)
    |> learn_about(:usufslc)
    |> learn_about(:linux)
  end
end
```

---

# Names & People

| Name                   | Discord         | Role                 |
| ---------------------- | --------------- | -------------------- |
| Erik Falor             | @fadein         | Advisor              |
| Richard Snider         | @CodeTriangle   | President            |
| Brigham Campbell       | @xeyler         | Vice President       |
| Ethan Payne            | @phat_sumo      | Legend               |
| Lizzy Hunt             | @Simponic       | Also Legend          |

---

# About the FSLC

We're a group of students enthusiastic about free software enthusiasts; we're very passionate about our machines, and what's on them.

The FSLC has been around since at _least_ 1999, according to the original [club constitution](https://web.archive.org/web/20011120092219/http://fslc.usu.edu/about/constitution.html) (which we found via diving deep into the Wayback Machine and "The Statesman" archives).

It was popular enough at the time to attract Richard Stallman to perform a talk with an "audience of 100s", and stayed strong for about a decade. After, though, there was unfortunately a period for several years in which the FSLC saw little to no activity.

It wasn't until Ethan Payne started it back up in 2017 that the club was brought back from the dead.

---

# Cool Stuff from the FSLC

Not only are we a community of free software and Linux lovers, a lot of us are hackers and tinkerers; we make new stuff, teach old stuff new tricks, and sometimes break stuff (because that can be fun too!). Many of us tinker with both hardware and software.

## FSLC Club Software

We have a github @ [github.com/usufslc](https://github.com/USUFSLC)!

- [linux.usu.edu](https://linux.usu.edu) - A good time to call out the official website! This was our original domain way back in 1999.
- [stream.linux.usu.edu](https://stream.linux.usu.edu/watch/) - Dockerized service to stream FSLC meetings.
- [JoinLater](https://github.com/xeyler/joinlater) - Since eduroam's JoinNow on Linux is so hopelessly jank, @xeyler has created JoinLater!

---

# We Present on Free Software and Learn Together

[https://forms.gle/7xS5avngKivdrA7V8](https://forms.gle/7xS5avngKivdrA7V8) - We want to hear from you! If there's something you'd like to present on, fill out this form!

We recognize that members of the Club have different levels of experience with Linux. During our weekly meetings, we spend time learning about topics of varying levels of complexity. We're excited to learn about the following topics with you:

- Sept 27 - The shell
- Oct 2 - SSH (The "secure" shell)
- Oct 9 - Debian installfest

We want to spend our meetings learning together! Let us know what you'd like to learn about or what topics you find confusing.

---

# Other Things we Do

Have an idea you want to explore, but don't know where to start? Diving into Linux or other free software, but you're feeling a bit stuck or lost? Just want to chat about some cool tech, interesting gadgets, tech news, and more?

Our Discord server is our club's hub for most of our club communication. We always enjoy helping others learn and discover free software and technology, so questions are always welcome. _We even have a dedicated tech support channel if you run into roadblocks or issues while using Linux or other software, and of course, we're all welcome to beginners_.

We've also got a great memes channel :) (and a small handful of "internal" memes).

---

# What is Free Software?

From the [Free Software Foundation](https://www.gnu.org/philosophy/free-sw.en.html):

> "Free software" means software that respects users' freedom and community. Roughly, it means that the _users have the freedom to run, copy, distribute, study, change and improve the software_. Thus, "free software" is a matter of liberty, not price. To understand the concept, you should think of "free" as in "free speech," not as in "free beer." We sometimes call it "libre software," borrowing the French or Spanish word for "free" as in freedom, to show we do not mean the software is gratis.

## Free Software You've Probably Heard of

- [Linux](https://www.kernel.org/)
- [Firefox](https://www.mozilla.org/en-US/firefox/new/)
- [Open Broadcaster Software](https://obsproject.com/)
- [VLC](https://www.videolan.org/vlc/)
- [Blender](https://www.blender.org/)
- [Godot Engine](https://godotengine.org/)

The ethos of free software encourages the hacking culture that was extremely prevalant during the early days of the internet. Free software is now the foundation that underpins most of the modern computing world today!

---

# Why is Free Software a Big Deal?

Other than the fact that most "free software" is actually free of charge (_nice_), free software does all the following:

- Provides the OS for 98.1% of the world's top million servers (96.3% Linux, 1.8% FreeBSD)
  - AWS, Azure, and Google Cloud use Linux as their OS of choice
- Provides the core for the world's most popular mobile phone OS (Android)
  - Android is a Linux-based OS, developed and maintained by Google
- Powers space vehicles, like Inginuity (Inginuity is powered by Linux - first powered, controlled flight on another planet)
- Runs almost all supercomputers and many robots
- Provides the core backbone of the world-wide web

---

# Why is Free Software a Big Deal?

## Cool Things You Can Do With Free Software

- Run your own web server
- Host a game server for your friends
- Breathe new life into an old computer
- Access your computer from anywhere in the world
- Become a master at the OS used to run most software written and used by engineers
  - Not only does most of what a software engineer write end up deployed to Linux, but many other engineering fields use Linux extensively.
- Make your computer do what you wish it always did
  - That includes making it look and work however you want if you're super into customization

## Crazier Things You Can Do With Free Software

- Make it so you can run a python interpreter on your phone (Termux on Android)
- Make things do stuff that it was never intended to do
  - Like make a [Wii](https://www.youtube.com/watch?v=mrdR43-sqKs) or an [OG iPod](http://www.ipodlinux.org/) run Linux
  - Trick your car into believing that a [raspberry pi is an ipod](https://github.com/Kytech/ipod) to add bluetooth
- Look like a "real hacker"
- And so much more

---

# A Little Bit of Terminology

In addition to the term "free software", there's a few other terms that you'll often hear. Just to make sure everyone knows what we are talking about, here's some common terns:

## What is a "Terminal"?

A terminal is a text-based interface to the computer. It is used to run commands and programs, and is the fastest way to interact with the computer when using Linux. Make a folder? Easy. Install a program? Easy (most of the time). Run a program? Easy. No double clicking or clicking through menus.

## What is a "Package Manager"?

Package managers are programs that allow you to install, update, and remove software. They are the easiest way to install software on Linux. Some insane people love to patiently wait halves of hours to compile their software.

## What is a "Desktop Environment"?

A desktop environment is a collection of programs that provide a graphical user interface (GUI) for the user. Some popular desktop environments include GNOME, KDE, and XFCE.

---

## Additional Terminology

- Software License - Determines who can use a piece of software and how. Good ones give you permission to do things that you wouldn't be able to do before.
- Open Source - Code that makes its source code available to the public. (Think stuff on GitHub)
- FOSS - Free and Open Source Software. Software that is both "free software" meaning the sense that it grants you lots of freedom in what it permits you to do and is open source.
  - Not all open source code is "free software" because it may not allow you to have certain freedoms in how the code is used (ex. can't redistribute it to someone else). Think free as in freedom, not free as in no money.
- Proprietary software - Software where you can't do anything other than use it as it is given to you. Opposite of free software and is very typical for paid software.
- Distro - A distribution of Linux (more on Linux in a moment)
- Terminal/Shell/Command-Line - Typically, when someone says this, they're referring to the text-based command-line interface on a computer. There are slight differences between each of these, but we'll spare you the details.

---

# What is Linux?

Linux is a free and open source operating system kernel - the core of the operating system, responsible for process scheduling, memory management, managing which code runs in user space vs kernel space, among other ridiculously hard tasks. Linux, in combination with GNU (or alternative) tools, is the basis for many operating systems including Android, Chrome OS, and Ubuntu.

## Distributions

Linux distributions are full operating systems built on top of the Linux kernel, often bundled with free software. Some popular distributions include:

- [Ubuntu](https://ubuntu.com/)
- [Debian](https://www.debian.org/)
- [Fedora](https://getfedora.org/)
- [Arch Linux](https://www.archlinux.org/)
- [EndeavourOS](https://endeavouros.com/)

Distributions can be built on top of other distributions, and are often referred to as "derivatives". For example, Ubuntu is a derivative of Debian, and EndeavourOS is a derivative of Arch Linux.

---

[tree](https://upload.wikimedia.org/wikipedia/commons/1/1b/Linux_Distribution_Timeline.svg)
![distro tree](https://upload.wikimedia.org/wikipedia/commons/1/1b/Linux_Distribution_Timeline.svg)

---

# Pros for Linux

- It's **Easy**: Linux, at most points, is only as hard as you make it. There are many distributions that are designed to be easy to use, and many distributions that are designed to be easy to customize, with a bit of work.
  Anecdotally, many people switching from Windows find that beginner-friendly distros are just plain easier to use than Windows for a lot of their day to day activities.

* It's **Secure**: When it comes to proprietary software, companies have to make a bet that the work they do is better than the work the entire volunteer community can reverse engineer and sidestep. This is a bet that is often lost, especially in C-land where just creating a variable length string may open an entire can of worms.

* It's **Private**: It's easy to audit the code, and you can almost be certain that your software is not sending your data to a third party without permission.

* It's **Flexible**: Can be extremely easy to use, or very power-user focused. Runs on anything from embedded devices to supercomputers.

* It's **In-Demand**: Linux skills are one of the most sought-after in the industry right now.

---

# Cons for Linux

* It's **Too Beautiful**:  Linux users love to make their desktops as pretty as possible, in a mating ritual known as "ricing".
  [r/unixporn](https://www.reddit.com/r/unixporn/) is a subreddit dedicated to showcasing the beauty of Linux desktops.

* It's **Just Too Blazingly Fast**:  You can configure Linux to be incredibly lightweight and run on any hardware, no matter its power level. And with hardware with a power level over 9000, it uses every single piece).

* It's **Too Cheap**:  Students are debt ridden and poor. Linux can be installed at no cost.

* It's **Too Powerful**:  Linux lets you make your computer or server do pretty much whatever you want it to do. No artificial barriers thrown up in your face for no reason!

It's simple. Make the switch today.

---

# The End

How are you using Linux? What's your favorite free software?
