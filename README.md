Hi, folks. I'm Paul Ducklin. I've been part of the cybersecurity scene for many years. 

You can find my contact details at <https://pducklin.com/about>.

One of my special skills is explaining in plain English the sort of technological stuff that often gets lost in jargon. 

The `minimalisti-C` repository below is a convenience for readers who need a tiny, free, unencumbered C compiler that's trivial to install, so they can have a go with the Windows C code that I include in some of my posts and articles. For quick experiments or threat-hunts, the sub-half-megabyte download of `minimalisti-C` makes it a lot more convenient than fetching gigabytes' worth of mingw-64 or Visual Studio (which never seems to stop calling home, fetching new files, and filling up your VMs with stuff).

The `onenetd` repository was originally written by Adam Sampson way back in the early 2000s. I have added it here mainly for my own convenience in finding it again, though you may find it useful if you've ever used ncat and the like. (This one passes an ever-increasing environment variable called `CONNCOUNT` to the scripts you call, which helps you collect data for each connection in a series of uniquely and well-ordered files.)

Note that I used the awesome [Fossil SCM](https://fossil-scm.org/) for my own development needs, rather that git, so you won't see much activity here. If you have pull requests, questions, or suggestions, feel free to contact me directly. (See above.)
