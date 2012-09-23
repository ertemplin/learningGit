5. Summary
==========

You now know how to set up your local copy of the repository, add and edit the local copy,
bundle up your changes, and send your local bundle of changes up to be included in the
authoritative version of the code.  That's the basics of git, and will compose the majority
of our usage of the tool.

To summarize:
-------------

To set up the initial local copy of the repository (replace learningGit with your desired
repo):
```bash
    git clone https://github.com/cole14/learningGit.git
```

To download any new changes to the repository you don't yet have in your local copy:
```bash
    git pull
```

To bundle up any local changes you've made:
```bash
    git add <file(s)>
    git commit
```

To add your bundle of changes to the authoritative version of the code:
```bash
    git pull (to avoid merge hell)
    git push
```

I highly recommend you to now play around with git here in this learning repository.
Feel free to add/edit/remove files in the directory you added (please leave these tutorial
files alone). The best way to learn git is to use it, and the best way to start using it is
just to mess around and figure out how it works.

Also, if you want another (probably better written and more in-depth) tutorial, check out:
   http://git-scm.com/book
It has lots of information and will explain a lot of the cooler and more complex aspects of
git we left out.

Woo!

