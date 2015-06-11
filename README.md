# Linux-technical-article-writer
Notice: Yum is replaced by DNF
DNF replaces Yum
Fedora has traditionally used the yum tool for software management. If you’re familiar with Ubuntu and Debian-based distribution, yum is similar to apt-get. Yum was always criticized for being rather slow, although it’s improved over the years. 

But with Fedora 22, Yum is out and replaced by DNF. DNF is a forked version of Yum that uses the libsolv library via hawkey. But never mind all those details—DNF offers faster software installation and dependency resolution with less memory usage. 
DNF offers some backwards compatibility with Yum. Desktop users using graphical package management tools like the Software application won’t see a difference. If you’re using the yum command in a terminal, you’ll be reminded that yum is deprecated and that you should use the dnf command instead. For most uses, DNF works about the same as Yum. If you need the nitty-gritty details, here are the differences between the DNF and Yum commands. 
