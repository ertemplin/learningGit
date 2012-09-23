4. Push
=======

Now that you have a bundle of local changes, you'll want to add them to the authoritative
version of the code.  That's where the push command comes in.  Before you run it, though,
let's think back to the potential merge problem we described in the 2_PULL section.  In that
scenario, we made some local changes to the same places as a change we tried to download
using the pull command, and it confused git into a merge error. A good way to avoid that is
to first pull before you try to push your local bundle.
```bash
git pull
git push
```

It's good form to always pull before you push.  That way, git will tell you if there's a
merge conflict and you can edit it yourself on the local version.  Otherwise, your push will
fail and you'll quickly start heading down the road to merge hell.

Continue on now to the final section 5_SUMMARY!

