# Git log

Logs can be the summary of all the work.
You would need to see the log very often.

So run this to see the log:
`
    git log
`

You should see something like this:

>commit abb5d6f27100fe0bb487aa996ce39cf5757e0483
>Author: Lirian Su <l9s@qad.com>
>Date:   Mon Sep 15 23:52:59 2014 -0400
>
>    First mission : Git log
>
>commit b4627b2c3faf0e289b8bc21bf9f27ab2323fedd8
>Author: Lirian Su <l9s@qad.com>
>Date:   Tue Sep 16 02:51:05 2014 -0400
>
>    Make the readme more attractive
>
>commit 2e333a8f11f2a43c5742877dbd9d1f2fea172e1d
>Author: Lirian Su <l9s@qad.com>
>Date:   Mon Sep 15 23:36:28 2014 -0400
>
>    This is actually the init with README

The `git log` command shows commit messages from current commit to the first commit.
If you want to see the whole log in a better view,
plz type a longer command:

`
    log --graph --decorate --oneline --abbrev-commit --all
`

This command shows all the commit messages and the relation ship between them.
Maybe you are a little bit confuse about what you see
But put them away, you would learn it quickly by practice

Now, follow the instruction in the graph log
Type it and go to Mission II



--------------------Mission I Complete--------------------
