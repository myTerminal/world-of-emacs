# Write Your Own Extensions

After a few months of using Emacs (or may be even earlier than that), you may want to write your own extensions for Emacs.

As mentioned earlier, Emacs extensions are simply '.el' files containing scripts written in the beautiful language of Elisp. 

Elisp is one of the many dialects that are a part of the family of functional programming languages called [Lisp](https://en.wikipedia.org/wiki/Lisp_(programming_language)). Lisp was created by [John McCarthy](https://en.wikipedia.org/wiki/John_McCarthy_(computer_scientist)) way back in 1958 and we still see incarnations of Lisp in form of programming languages like [Clojure](https://en.wikipedia.org/wiki/Clojure) created by [Rich Hickey](https://twitter.com/richhickey) in 2007.

## Learning Elisp

Learning basic Elisp should be simple and as usual, there are quite a lot of resources on the internet, some of which are:

1. [Practical Emacs Lisp - ergoemacs](http://ergoemacs.org/emacs/elisp.html)
2. [An Introduction to Programming in Emacs Lisp - gnu.org](https://www.gnu.org/software/emacs/manual/eintr.html)
3. [GNU Emacs Lisp Reference Manual](https://www.gnu.org/software/emacs/manual/elisp.html)

I always like to learn a few basics and start writing my own code to get glued to the language, start getting comfortable and gain confidence before I progress to relatively advanced topics.

## Writing extensions

Thought writing extensions is easy, one needs to follow a few conventions that the community has agreed upon before we publish our packages out there. The conventions include design practices, coding style and commenting formats including file headers and footers.

Read through the post [Authoring Emacs Packages](https://blog.aaronbieber.com/2015/08/04/authoring-emacs-packages.html) by Aaron Bieber to get an idea.

Also, read through the [Coding Conventions](https://www.gnu.org/software/emacs/manual/html_node/elisp/Coding-Conventions.html) described within the GNU Emacs Lisp Reference Manual that mentions a few basic practices to keep in mind.

There's also an [Emacs Lisp coding checklist](http://www.nongnu.org/emacs-tiny-tools/packages/index-body.html) that you can refer to save you some rework later.

## Publishing Extensions

The steps you need to take in order to publish a package to a repository depends upon the repository itself. You would mostly be publishing your packages to the repositories that we discussed earlier.

The simplest one to go for is marmalade-repo, through melpa and then lastly melpa-stable.

Specific steps for each of the repositories are linked below:

1. [marmalade-repo - How to upload packages](https://marmalade-repo.org/#upload)
2. [Contributing to MELPA](https://github.com/melpa/melpa/blob/master/CONTRIBUTING.md)
3. [Contributing to MELPA stable](https://github.com/melpa/melpa#melpa-stable)