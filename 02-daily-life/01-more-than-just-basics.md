# More than just basics

Once you start getting comfortable with Emacs, you do not need to go through the basics anymore. The key-bindings that used to be so difficult, now start becoming muscle memory to the fingers.

## A few Emacs references

None of us would be able to learn Emacs entirely. We start with learning only as much as we need and then we keep going back to a few guides to learn more as we go. Fortunately, our fellow-creatures have already created a lot of such reference material for us that we can refer.

### The ergoemacs website

The [ergoemacs website](http://ergoemacs.org), although it looks dated (as mentioned earlier), can form a good reference material to learn more of Emacs.

There they also have training material for [Emacs Lisp](https://www.gnu.org/software/emacs/manual/html_node/elisp), which is a dilect of the beautiful language of [Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language)). Knowing at least a bit of Emacs Lisp (or Elisp) helps customize Emacs better. Who knows, you would end up creating your own Emacs extensions with Elisp!

### The Emacs mini manual and more by tuhdo

This [website](http://tuhdo.github.io) has lot of information about Emacs starting from the 'Why' and 'How' that we covered earlier to advanced topics like programming language specific setups and much more.

### The GNU Emacs Manual

If you like reading detailed, lengthy manuals, you can also go through the [GNU Emacs Manual](https://www.gnu.org/software/emacs/manual/emacs.html) provided by GNU itself.

### Emacs.sexy

This one is [a noteworthy website](http://emacs.sexy) that has quite a lot of references to places where you can find information about Emacs.

## Emacs packages

As GNU describes, Emacs is an extensible self-documenting editor. There are thousands of packages that you can add to your configuration (and later write your own).

The core of Emacs is written in C++ and the runtime is based on Elisp. This makes it very easy to modify its behavior by writing Elisp code. That is exactly what those packages out there are: pieces of nicely written Elisp code that you can 'install' into your Emacs.

Even when installing packages, Emacs offers a wide set of choices. You can either download a script file and load it manually into Emacs's runtime or you can use one of the available package archives.

To start with, there are multiple package management systems, and for those systems they have multiple package archives. The two most popular package management systems are [ELPA](https://www.emacswiki.org/emacs/ELPA) and [el-get](https://github.com/dimitri/el-get). ELPA is the more common one among the two

The major package archives for ELPA are:

1. [gnu ELPA](http://elpa.gnu.org) is the default package repository for Emacs. It comes configured with Emacs.
2. [melpa](http://melpa.org) requires authors to write their own packages and submit them through a strict set of guidelines a quality control. I have three packages on melpa currently.
3. [melpa-stable](https://stable.melpa.org) is a more stable version of melpa and supposedly hosts release versions of packages on melpa that are known to be stable. All packages on melpa-stable are on melpa and not the other way around.
4. [marmalade](https://marmalade-repo.org) follows a relaxed approach of submitting packages to the registry where there is no review before a package is submitted. I make sure all my packages are submitted to marmalade. Current I have [twelve](https://marmalade-repo.org/profile/myTerminal) of them there.

You can follow [https://www.emacswiki.org/emacs/ELPA](https://www.emacswiki.org/emacs/ELPA) for instructions on installing packages to your Emacs.

As there are almost infinite number of Emacs packages out there that reside not only on the registries mentioned above, but some also are hosted on individual GitHub repositories and a few are circulated as '.el' files.

If you are confident that you will not be overwhelmed, you can refer to [this list of a few most popular packages for Emacs](https://github.com/emacs-tw/awesome-emacs) at your own discretion. Remember: You have been warned, you will lose days of your life browsing through these packages.
Let's say you went through the entire list of packages, just realize that it was just one list our of the many that you may find in the future.