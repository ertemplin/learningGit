3. Bundling Changes
===================

You can edit the local files any way you'd like, be that through an IDE such as eclipse, a
text editor such as vim, or any other method you can think of. You can even add new files or
delete existing ones.

We'll start by creating some content in our local copy of the repository.
First open up a terminal (if you haven't already), and change directories into the local
copy.
```bash
cd learningGit/
```

Next, create a subdirectory for yourself named after your github username (substitute your
username for mine)
```bash
mkdir cole14/
```

Next, using the editor of your choice, create a file in your newly created subdirectory with
the words Hello, World!
```bash
echo "Hello, World!" > cole14/myFirstFile.txt
```

At this point, you've made some changes to your local copy of the repository.  You've created
a subdirectory and added a file with some content.  However, git doesn't care about new files
unless you tell it to, so next we'll tell git to keep track of our new files using the add
command.
```bash
git add cole14/myFirstFile.txt
```

The add command starts the bundling process.  When you want to bundle up your local changes
in order to send up to the authoritative version, you first tell git which changes you want
to bundle using the add command.  The add command specifically operates on files, so you
specify the files which contain the changes you want to bundle.

Once you've added all the changes to the bundle, you finish up the bundle using the commit
command:
```bash
git commit
```

This command will open up an editor (probably pico or nano) for you to add a
message which describes your bundle of changes.  Once you've written out your description,
simply write the file and quit the editor and your bundle will be complete.

Your bundle may be complete now, but it's still sitting on your local copy.  This is nice
because you can bundle up some intermediate changes that you may not want everyone to get
just yet.  To complete the process and upload your bundle(s) to the authoritative version,
you'll need to run the push command.

Continue on to [4_PUSH](4_PUSH.md).
    
