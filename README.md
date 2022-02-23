# Cryo
A GNOME Shell extension to "stop" (suspend) and "continue" (resume) applications
to prevent them from using unnecessary resources while keeping them "open".
It can prevent random CPU usage form applications on a workspace that is not
currently being used. It also helps the kernel decide which application memory
to swap, stopped applications get swapped before others.

It is useful if you have my kind of workflow, because I usually keep everything
open (even things that I won't be using for a long time) and just switch workspace.
With this extension you can suspend all the applications that you won't use, while
leaving the window open so that you can eventually see it and remember what to do.

Isn't it so cool!?
Especially if you think that this functionality is already included in Linux since
a process can be in a STOPPED state if a STOP signal is sent.
Switching the application to a STOPPED state is exactly what this is all about.
