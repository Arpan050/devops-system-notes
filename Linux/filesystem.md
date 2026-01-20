Day 1



At first I have install ubuntu in VM. Then started with the basic definitions.



\# Linux Filesystem Structure



This document describes how the Linux filesystem is organized and how it behaves in real usage.



\## Root Directory (/)



The filesystem starts at `/`.



Everything exists under root. There are no drive letters like in Windows.



Breaking `/` breaks the system.



\## /bin and /sbin

\## /etc

\## /tmp

\## /usr

\## /var and /var/log

\## /dev

\## /proc

\## /srv

After that learned about some Commands

> pwd
> ls
> ls -l
> ls -a
> cd /  
> cd ~
> cd ..
> cd .

Then Learned about directory and file creation

> mkdir Directory (i know about this because it is normally used in every OS)
> touch filename

Writing Content Inside File:-

> echo "Content......" >> filename.txt
> echo "content..." > filename.txt
> cat filename.txt
> cp filename.txt file2.txt (copying content from filename.txt to file2.txt)

Move and Rename a file:-

> mv filename.txt dir/  (moving filename.txt to dir/ directory)
> mv filename.txt File1.txt  (Rename the file from filename.txt to File1.txt)

Delete the files and directory:

> rm filename.txt
> rm -r dir
