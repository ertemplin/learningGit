2. Pull
=======

Once you have your local copy set up using the clone command, you'll want to periodically ask
the authoritative version for any new changes - maybe someone else fixed an annoying bug
after you got your local copy set up.  The way you download those changes is through the pull
command:
```bash
git pull
```

It's as simple as that.  If the authoritative version has changes you don't yet have, then
they are downloaded and automatically merged into your local copy.  Sometimes this can cause
problems -- if you happened to edit the same content locally then git won't know what to do
with the downloaded changes and tell you to manually resolve the merge failure.  That doesn't
usually happen too often, though, and it's better to worry about that when it happens.

Once you have a local copy and know how to get other peolpe's changes, you'll probably want
to edit the files yourself and send your local edits back up to the authoratitive version so
that everyone else can have them as well.

Continue on to [3_BUNDLING_CHANGES](3_BUNDLING_CHANGES.md).
