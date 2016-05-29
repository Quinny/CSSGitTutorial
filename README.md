# Git tutorial
##### By the [uWindsor CSS](http://css.uwindsor.ca)

## WTF is Git?
Git is the most widely used **version control system** in the world.

## WTF is version control?

Version control is a system which records changes to a set of files over
time.  It creates a collection of snapshots of your files at different states,
and allows you to restore specific versions.  Version control is very commonly
used to manage software development, but really it could be used for any kind
of files.

## Why should I use version control?

Imagine you are working on a school project due the next day.  You manage to
hack something together, but its really messy.  Since you have some time,
you decide to do your T.A. a favour and refactor a bit.  Your codes ends up
even messier than the original and now its totally broken and doesn't even compile.
To add on to that, you closed your editor and went and made a sandwich at some
point, so holding down ctrl-z and praying to Donald Knuth isn't an option.
You probably should have used version control, or more specifically git. Had
you read this tutorial before you started your assignment, your work flow would
have looked something like this:

![Git work flow graph](images/git-workflow.png)

If you were using git you could have "committed" (take a snapshot)
your working code.  This way no matter how bad you botch things during
the refactor you can always revert back to it and get those partial marks
on your assignment.

## Using Git For Collaboration

So Git is great at saving you from breaking your code, but it also works really
well as a collaboration tool.  Instead of having to share code with your teammates
via email like a caveman, you could use a shared repository.  Sites like Github
(you are there as we speak) provide a repository sharing service.  Multiple
users can push code to a single repository and collaborate together in writing
code.  There are a few features that git provides, such as branching, that make
this less of a headache than it may seem.

![Git collaboration](https://git-scm.com/figures/18333fig0501-tn.png)

