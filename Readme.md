The Red Spider Project
----------------------

[https://github.com/the-xkcd-community/the-red-spider-project]


### Why ###

Because we like to combine our love for the xkcd comic with our love
for coding, and we want to share the experience.


### How ###

For the impatient: fork the project, then

    git clone git@github.com:yourname/the-red-spider-project.git redspider
    cd redspider
    git remote add upstream git://github.com/the-xkcd-community/the-red-spider-project.git
    git config branch.master.remote upstream
    git config branch.master.merge refs/heads/master
    ./setup.py
    rsshell

The project is like a small, self-contained operating system layered
on top of your actual operating system. People can add programs at
will. It's an open-ended process without deadlines or a final goal and
we're very open-minded.


### What ###

run `rshelp` to get a list of available commands!

The following commands are expected to be added soon.

- `spider-life`: A Conway's Game of Life variant with two colors and
  four different topologies for the universe.
- `xkcd-windows-wallpaper`: A Windows app which sets your wallpaper to
  an xkcd comic of your choosing.


### Where ###

- [Home page](http://the-xkcd-community.github.com/the-red-spider-project)
- [Issue tracker](https://github.com/the-xkcd-community/the-red-spider-project/issues)
- [Wiki](https://github.com/the-xkcd-community/the-red-spider-project/wiki)
- [IRC channel: #redspider at foonetic.net](irc://irc.foonetic.net/redspider)
- [xkcd forums thread](http://forums.xkcd.com/viewtopic.php?f=11&t=81969)


### When ###

We started in March 2012. In the first few months we spent most of our
effort on the infrastructure. In July we were treated to some splendid
logo designs and we got a homepage. In December we launched our IRC
channel and in March 2013 the wiki took off. In the meanwhile several
members have been working on various subprojects, mostly in short
bursts of activity.

In the near future we may expect a few big improvements to the
infrastructure.


### Who ###

Julian coined the idea, qubital set up the GitHub repository, Neil
wrote most of the initial infrastructure code and Joey designed the
logo proposals. Please also refer to the copyright notices in the
source files and to the Authors.txt, which lists all the authors who
decided not to add their name to some file they edited.
