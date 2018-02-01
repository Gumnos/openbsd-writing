# OpenBSD for Writers: Introduction

by Matthew Graybosch <public@matthewgraybosch.com>

Do you want to write? Are you not writing because you aren't sure you have the right equipment? I might be able to help you, but I'm going to level with you: you might not actually need OpenBSD or my help.

## You Might Not Need My Help

Do you have a working computer? If so, then congratulations! You already have everything you need to start writing a first draft. 

Here is what you should do, assuming you're using Windows.

1. Restart your computer.
2. Disable your wifi or unplug your network cable.
3. Open up Notepad, maximize it so it takes up the whole screen, and set the display font to something you can comfortably read.
4. Create a directory named "Writing Project 1" in your Documents folder, unless you already have a working title. If not, you can rename this later.
5. Save a file called "draft-01.txt" inside the folder you just created.
6. Start writing. 

If you're using a Mac, you would use TextEdit instead of Notepad. However, TextEdit does rich text editing by default, and [needs to be configured for plain text editing][tekrevue].

Either way, if you have a working computer all the software you need to start writing is already available. You don't need an expensive word processing application or fancy "distraction-free" software made especially for writing.

## Trust Me. I Do This All The Time.

I know from experience that plain text is all you need. I started writing a little over twenty years ago when I was eighteen, which was also when I got my first computer. It was a used IBM PS/ValuePoint that I bought for a hundred box along with a computer desk and a dot-matrix printer, and the only software it had was its operating system, PC-DOS 6. 

Fortunately, PC-DOS 6 came with [a basic text editor called E.EXE][ibm-dos-e-editor]. E only did plain text, and it felt limited at first because I had already gotten some training on WordPerfect 5.1, but once I got used to it I realized that plain text was all I really needed to just get a story out of my head.

After dropping out of college, I took advantage of having been exposed to UNIX and vi and started using Linux. I wrote a whole lot of crap, none of it finished or publishable, but it wasn't because I was messing around with fonts or styles in a word processor.

Plain text all you need to get started, too, if you're willing to give it a try.

## Ready to Consider a Change?

Are you still reading this instead of writing? I can think of a few reasons for that.

1. You don't actually have a working computer.
2. Your computer works, but you're frustrated with Windows, Office, or both.
3. You want to set up a secondary, dedicated machine for writing.
4. You're a parent who wants to set up a safe working environment for a child or teenager who wants to start writing.

These are all excellent reasons to consider using a Unix-like operating system like [OpenBSD][openbsd], but there are some considerations you should be aware of before we continue.

1. I use and recommend OpenBSD because after almost twenty years of experience with GNU/Linux, I've come to prefer OpenBSD's design sensibility. Because of my preference, these tutorials will focus on OpenBSD.
2. Much of the advice I will offer is applicable to the GNU/Linux distribution of your choice, OSX, and even Windows.
3. Unix systems are designed to handle multiple simultaneous users and to be managed by a knowledgable system administrator. If you don't have any friends or friends of friends who are willing to be your sysadmin in exchange for beer or other considerations, you're going to have to step up and become your own sysadmin.
4. Where applicable, I will link to technical documentation from OpenBSD, such as the [FAQ][openbsd-faq] and [manual pages][openbsd-man-pages]. You really should read these. They'll help you get out of trouble, and often help you avoid trouble in the first place.

## I Want My... I Want My BSD...

Why use OpenBSD? It's not easy, but neither was putting men on the moon or climbing Mount Everest. Sometimes you need to do things because they are hard. 

I use OpenBSD because if I wanted to set up a bare-bones computer for writing, the base installation would give me everything I need. You see, the base OpenBSD system comes with both [classic vi][openbsd-man-pages-vi] and [mg, a small Emacs-style editor][openbsd-man-pages-mg]. Both of these are text editors for programmers; they're more than enough for writers.

Of course, if you aren't familiar with either vi or Emacs, you're going to have to learn at least one of them unless you want to install additional tools. We'll get to that later. First, let's talk about getting a copy of OpenBSD so we can install it.

## Thanks for Reading

If you're reading this text on GitHub and want to help, please file an issue or better yet, [fork the repository][github-openbsd-writing], make your changes, and submit a pull request.

If you're reading this on my website, you're welcome to comment using the form below, or quote relevant passages on your own website.

If you need to reach me directly, [email me][public-email] or [find me on Mastodon][mastodon].

[tekrevue]: https://www.tekrevue.com/tip/textedit-plain-text-mode/
[ibm-dos-e-editor]: https://en.wikipedia.org/wiki/E_(PC_DOS)
[openbsd]: https://openbsd.org
[openbsd-faq]: https://www.openbsd.org/faq/
[openbsd-man-pages]: https://man.openbsd.org/
[openbsd-man-pages-vi]: https://man.openbsd.org/vi
[openbsd-man-pages-mg]: https://man.openbsd.org/mg
[github-openbsd-writing]: https://github.com/matthewgraybosch/openbsd-writing/
[public-email]: mailto://public@matthewgraybosch.com
[mastodon]: https://octodon.social/@starbreaker
