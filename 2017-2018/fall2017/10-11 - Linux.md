# Introduction to Linux

## Announcements
* Programming Competition Winners
  * 1st Place - Brandon Wong - 20pts
  * 2nd Place - Justin Maddox - 19pts
  * 3rd Place - Hunter Soliday - 18pts

* Stillwater/Okstate Linux Users Group
  * Contact [Andrew](mailto:andrew.bevelhymer@okstate.edu) for details.

## First of all, what IS Linux?

* What is normally referred to as Linux is a variety of operating systems that use the Linux kernel and GNU utilities (as well as other software, normally).
* What is this **kernel** and **GNU** you speak of?? A bit of history...
	* [History of Linux](https://en.wikipedia.org/wiki/History_of_Linux)

## Server vs. Desktop

* There is, in general, two things you would want to do with your linux system. You either want it to run on a server to run server software for the backend of a web application, or you want to use it to do the things you do on a daily basis.
* As CS students, you'll probably hear that it's valuable to have _Linux Skills_. When companies say this, they _most likely_ mean that they want you to know your way around a server, which probably runs on some distribution of Linux. This means that it's essential for you to have these skills. But, how do you gain them?

## Gaining Linux Skills

* One way is to get a server, install Linux on it, and use it for something useful. i.e. hosting a website.
	* This might be the best way to gain the skills employers are hungry for, and it will teach you a lot about how the web works.
	* As a student, you actually can get a server on [DigitalOcean](https://www.digitalocean.com/) for free for up to 10 months (depending on which options you choose) because you can get $50 credit through the [Github Student Developer Pack](https://education.github.com/pack)
* Another way of gaining these skills is to use Linux as the primary os on your computer. This not only gives you the command line skills you need to know, but also could give you knowledge on several other parts of how operating systems work. Not to mention the countless other benefits, which brings us to our next section...

## Why **YOU** Should Use A Distribution of Linux as Your Primary Operating System

* You can gain the skills mentioned above.
* You will become part of a really awesome community.
* You can contribute code!
	* The Linux kernel is 100% open source and most distributions contain mostly open source software as well, meaning you can test out your programming skills by contributing!
* Package Repositories - More on this later.
* Customizability!
	* Remember, if you install linux and you don't like the way something is (i.e. the UI) you can probably change it without affecting your system and you can always revert back!
* FREE!

## So, What are these Distribution thingys?

* If you consider _Linux_ a class of operating systems. Then _Linux Distributions_ are the operating systems themselves.

### Differences between distros?

* Most Linux Distros are incredibly similar.
* The differences are normally the package managers that they use, as well as other software that is used for various tasks

## Packages
* A major advantage of using Linux is the way you install pieces of software, aka packages.
* Each application (**package**) you might want to install lives on a server somewhere, and your package manager downloads it from that server and installs it! Meaning you don't have to go scouring around the internet (well, most of the time) for packages that you need that could have become corrupted. Every package in the official repositories of your distribution has already been checked for integrity!
* Source based vs binary based packages
* Live Demo of Installing a Package

## Some Common Distribution Choices
* [Ubuntu](https://www.ubuntu.com/)
	* Most popular choice (especially for beginners/average users)
	* Comes with Unity as the default desktop environment, but Unity is actually not going to be supported soon. Because of this, I recommend picking an [Ubuntu Flavor](https://wiki.ubuntu.com/UbuntuFlavors) that you like and installing that.
		* Basically each _flavor_ comes with a different Desktop Environment. Read more on that below
	* For Servers: [Ubuntu Server](https://www.ubuntu.com/server) is one of the most common distributions installed on web servers. And for good reason: **it's stable**
* [Linux Mint](https://linuxmint.com/)
	* Another great options for beginners and experienced users alike!
* [Elementary OS](https://elementary.io/)
	* Designed to look really really good. AKA designed to look like macOS
* [Debian](https://www.debian.org/)
	* Actually what Ubuntu, Linux Mint, Elementary OS, and several other distros are based on
* [Solus](https://solus-project.com/)
	* A relatively new distribution, that is designed with the average user in mind (AKA designed for people who aren't linux wizards)
* More advanced distributions: [Arch Linux](https://www.archlinux.org/) and [Gentoo](https://www.gentoo.org/)
	* Not really recommended for beginners, as you have to manually install both of them, but really great for learning and customizability.

## Quick Note On Desktop Environments
* A **Desktop Environment** is a collection of programs that run on top of your OS that consists of everything that makes up the UI. Icons, Windows, toolbars, widgets, etc. are all normally part of you Desktop Environment
* Several new linux users get the wrong impression about Linux as a whole because they are using a desktop environment that they don't like. What's good about Linux is you can install a different one and change everything about your UI without really affecting your system.
* Some Good Options:
	* [GNOME](https://www.gnome.org/)
		* Really Popular
		* Customizable
		* You can install all kinds of extensions
	* [KDE](https://www.kde.org/)
		* Another really popular choice
		* More configurable than GNOME
	* [XFCE](https://xfce.org/)
		* Really lightweight
		* **Extremely configurable**
	* [Budgie](https://budgie-desktop.org/home/)
		* Made for the Solus OS
		* Like GNOME in a lot of ways, but different in others
	* [Mate](http://mate-desktop.org/)
		* Another lightweight choice
		* Actually a continuation of an older version of GNOME

## Tips/Things I Wish I Knew
* Youtube videos are great, but become outdated quickly
* man pages are actually a realy great thing, if you don't know anything about a command you're using, type:
```bash
man <command>
```
* Get involved in Linux communities online. There are several different subreddits, irc channels, etc. devoted to linux related topics.

## Resources For Learning How To Use Linux:
* [Linux Journey](https://linuxjourney.com/)
	* One of the best for learning anything you need to know about linux. Highly recommended!
* man pages
	* These are actually really useful. See above for how to use
* Books
	* There are several books on linux and they're great for learning!

## Activity
* Go through as much as you can on [Linux Journey](https://linuxjourney.com/). You'll learn a lot from doing this!
* If you are feeling like you might like linux, install a distro on your computer.
* Not wanting to make a huge committment? Install in a VM
