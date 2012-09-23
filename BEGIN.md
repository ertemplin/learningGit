Before we dive in to using git, we first need to understand why and how we'll be using git.

Git is a distributed revision control and source code management tool. In essence, it allows
multiple people to work on the same codebase at the same time. There are lots of cool
features in git that allow you to do some crazy stuff, but we'll be focusing on a few of the
core commands so we can focus on coding, rather than wrangling the tools.  They are:

1. clone
2. pull
3. add
4. rm
5. commit
6. push

If you've been following along, you should have already run the first one -- clone. 
Before we start discussing these core commands, though, you may still be wondering why we're
using it in the first place.

When working in a software team, a number of issues invariably arise. Here's a few:

1. Multiple people want to edit the same areas of the code at once.
2. Multiple people need access to other people's work quickly and frequently.
3. Your code digresses into a state of utter confusion, and you need to jump back to
   something that worked

To combat these issues, smart people have spent a lot of time writing tools to help alleviate
these, and other, all-too-frequent pains of software development.  Git, for example, was
initially written by Linus Torvalds for his work on the Linux kernel.

The way we'll be using git to solve these problems is as follows. The authoritative version
of the code will be stored on github's servers. That version of the code will stay the same
unless we explicitly change it (through a push command). This is how we keep everyone on the
same page -- everyone syncs up through that authoritative version (hosted on github).  The
way we'll work with the code is through local versions of that authoritative version. We'll
'clone' the authoratitive version onto our local machine and edit the code there.  Once we've
edited the code to our liking - be that to implement some new functionality or fix a quick
bug - we'll bundle up those local changes and send them up to be included in the authoratitive
version. Additionally, our local version is exactly as we described it - a local copy of the
authoritative version.  That means we also need to periodically ask the authoritative version
for any updates anyone else has made (through a pull command).

Hopefully that makes some sense.  Now we'll explain the previously mentioned 6 core commands
we'll be using, and walk through some hands-on uses.

Open up the 1_CLONE file to continue.

