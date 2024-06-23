# OSProject Running Containers for Application Development

Group Name: PowerPuff

Section: 1

Team Mates:
1. Ammar Haziq bin Zainal 2217763
2. Arina Batrisyia Sobhan binti Mohd Razali 2217572
3. Adlyn Sofea binti Mohd Ariff Adika 2214042
4. Aisha Humairah binti Ahmad Adzuan 2219130

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)***
   ```bash
   https://github.com/marziq/OSProject
   ```
3. How many files and folders are in this repository. ***(1 mark)***
   ```bash
   7 Files 1 folder
   ```


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** 
```bash
Ubuntu Linux
```

2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 
```bash
2 cores, 8 GB RAM, and 32 GB storage.
32 cores, 64 GB RAM, and 128 GB storage.
```
3. Why must we commit and sync our current work on source control? ***(1 mark)***
```bash
To ensure that all changes are saved and shared with others, allowing collaboration.
```

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
   ```bash
   @marziq ➜ /workspaces/OSProject (main) $ pwd
   /workspaces/OSProject
   ```

2. Run the command **cat /etc/passwd** . ***(1 mark)***
   ```bash
   @marziq ➜ /workspaces/OSProject (main) $ cat /etc/passwd
   root:x:0:0:root:/root:/bin/bash
   daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
   bin:x:2:2:bin:/bin:/usr/sbin/nologin
   sys:x:3:3:sys:/dev:/usr/sbin/nologin
   sync:x:4:65534:sync:/bin:/bin/sync
   games:x:5:60:games:/usr/games:/usr/sbin/nologin
   man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
   lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
   mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
   news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
   uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
   proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
   www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
   backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
   list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
   irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
   gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
   nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
   _apt:x:100:65534::/nonexistent:/usr/sbin/nologin
   systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
   systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
   systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
   messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
   codespace:x:1000:1000::/home/codespace:/bin/bash
   sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
   
   ```

3. Run the command **df** . ***(1 mark)*** 
 ```bash
@marziq ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847728 12706868  18446768  41% /
tmpfs              65536        0     65536   0% /dev
shm                65536        0     65536   0% /dev/shm
/dev/root       30298176 24196376   6085416  80% /vscode
/dev/sdb1       46127956       88  43752292   1% /tmp
/dev/loop3      32847728 12706868  18446768  41% /workspaces
```
4. Run the command **du** . ***(1 mark)*** 
 ```bash
   @marziq ➜ /workspaces/OSProject (main) $ du
16      ./nodejs-app/node_modules/string_decoder/lib
48      ./nodejs-app/node_modules/string_decoder/node_modules/safe-buffer
52      ./nodejs-app/node_modules/string_decoder/node_modules
88      ./nodejs-app/node_modules/string_decoder
40      ./nodejs-app/node_modules/finalhandler
220     ./nodejs-app/node_modules/mime-db
24      ./nodejs-app/node_modules/unpipe
36      ./nodejs-app/node_modules/isarray
24      ./nodejs-app/node_modules/vary
20      ./nodejs-app/node_modules/ee-first
20      ./nodejs-app/node_modules/process-nextick-args
12      ./nodejs-app/node_modules/sqlstring/lib
40      ./nodejs-app/node_modules/sqlstring
12      ./nodejs-app/node_modules/has-symbols/test/shams
24      ./nodejs-app/node_modules/has-symbols/test
8       ./nodejs-app/node_modules/has-symbols/.github
72      ./nodejs-app/node_modules/has-symbols
64      ./nodejs-app/node_modules/safer-buffer
32      ./nodejs-app/node_modules/http-errors
12      ./nodejs-app/node_modules/express/lib/middleware
32      ./nodejs-app/node_modules/express/lib/router
124     ./nodejs-app/node_modules/express/lib
260     ./nodejs-app/node_modules/express
4       ./nodejs-app/node_modules/.bin
28      ./nodejs-app/node_modules/body-parser/lib/types
40      ./nodejs-app/node_modules/body-parser/lib
100     ./nodejs-app/node_modules/body-parser
28      ./nodejs-app/node_modules/etag
8       ./nodejs-app/node_modules/setprototypeof/test
32      ./nodejs-app/node_modules/setprototypeof
8       ./nodejs-app/node_modules/has-property-descriptors/test
8       ./nodejs-app/node_modules/has-property-descriptors/.github
48      ./nodejs-app/node_modules/has-property-descriptors
16      ./nodejs-app/node_modules/define-data-property/test
8       ./nodejs-app/node_modules/define-data-property/.github
72      ./nodejs-app/node_modules/define-data-property
24      ./nodejs-app/node_modules/forwarded
32      ./nodejs-app/node_modules/on-finished
28      ./nodejs-app/node_modules/ipaddr.js/lib
64      ./nodejs-app/node_modules/ipaddr.js
36      ./nodejs-app/node_modules/type-is
12      ./nodejs-app/node_modules/mime/src
80      ./nodejs-app/node_modules/mime
32      ./nodejs-app/node_modules/proxy-addr
28      ./nodejs-app/node_modules/media-typer
28      ./nodejs-app/node_modules/bytes
24      ./nodejs-app/node_modules/inherits
92      ./nodejs-app/node_modules/bignumber.js/doc
420     ./nodejs-app/node_modules/bignumber.js
84      ./nodejs-app/node_modules/qs/test
72      ./nodejs-app/node_modules/qs/dist
8       ./nodejs-app/node_modules/qs/.github
44      ./nodejs-app/node_modules/qs/lib
288     ./nodejs-app/node_modules/qs
20      ./nodejs-app/node_modules/readable-stream/lib/internal/streams
24      ./nodejs-app/node_modules/readable-stream/lib/internal
96      ./nodejs-app/node_modules/readable-stream/lib
48      ./nodejs-app/node_modules/readable-stream/node_modules/safe-buffer
52      ./nodejs-app/node_modules/readable-stream/node_modules
8       ./nodejs-app/node_modules/readable-stream/doc/wg-meetings
12      ./nodejs-app/node_modules/readable-stream/doc
224     ./nodejs-app/node_modules/readable-stream
8       ./nodejs-app/node_modules/es-define-property/test
8       ./nodejs-app/node_modules/es-define-property/.github
56      ./nodejs-app/node_modules/es-define-property
20      ./nodejs-app/node_modules/send/node_modules/ms
24      ./nodejs-app/node_modules/send/node_modules
92      ./nodejs-app/node_modules/send
24      ./nodejs-app/node_modules/range-parser
24      ./nodejs-app/node_modules/destroy
8       ./nodejs-app/node_modules/gopd/test
8       ./nodejs-app/node_modules/gopd/.github
44      ./nodejs-app/node_modules/gopd
36      ./nodejs-app/node_modules/accepts
24      ./nodejs-app/node_modules/methods
44      ./nodejs-app/node_modules/raw-body
12      ./nodejs-app/node_modules/call-bind/test
8       ./nodejs-app/node_modules/call-bind/.github
64      ./nodejs-app/node_modules/call-bind
36      ./nodejs-app/node_modules/content-disposition
8       ./nodejs-app/node_modules/side-channel/test
8       ./nodejs-app/node_modules/side-channel/.github
68      ./nodejs-app/node_modules/side-channel
20      ./nodejs-app/node_modules/function-bind/test
12      ./nodejs-app/node_modules/function-bind/.github
80      ./nodejs-app/node_modules/function-bind
32      ./nodejs-app/node_modules/mime-types
24      ./nodejs-app/node_modules/fresh
24      ./nodejs-app/node_modules/utils-merge
24      ./nodejs-app/node_modules/path-to-regexp
8       ./nodejs-app/node_modules/depd/lib/browser
12      ./nodejs-app/node_modules/depd/lib
52      ./nodejs-app/node_modules/depd
36      ./nodejs-app/node_modules/debug/src
112     ./nodejs-app/node_modules/debug
8       ./nodejs-app/node_modules/set-function-length/.github
60      ./nodejs-app/node_modules/set-function-length
8       ./nodejs-app/node_modules/has-proto/test
8       ./nodejs-app/node_modules/has-proto/.github
52      ./nodejs-app/node_modules/has-proto
40      ./nodejs-app/node_modules/serve-static
24      ./nodejs-app/node_modules/cookie-signature
20      ./nodejs-app/node_modules/array-flatten
24      ./nodejs-app/node_modules/merge-descriptors
36      ./nodejs-app/node_modules/iconv-lite/lib
232     ./nodejs-app/node_modules/iconv-lite/encodings/tables
348     ./nodejs-app/node_modules/iconv-lite/encodings
412     ./nodejs-app/node_modules/iconv-lite
20      ./nodejs-app/node_modules/object-inspect/example
8       ./nodejs-app/node_modules/object-inspect/test/browser
96      ./nodejs-app/node_modules/object-inspect/test
8       ./nodejs-app/node_modules/object-inspect/.github
216     ./nodejs-app/node_modules/object-inspect
48      ./nodejs-app/node_modules/safe-buffer
40      ./nodejs-app/node_modules/cookie
8       ./nodejs-app/node_modules/es-errors/test
8       ./nodejs-app/node_modules/es-errors/.github
100     ./nodejs-app/node_modules/es-errors
24      ./nodejs-app/node_modules/negotiator/lib
52      ./nodejs-app/node_modules/negotiator
8       ./nodejs-app/node_modules/hasown/.github
48      ./nodejs-app/node_modules/hasown
20      ./nodejs-app/node_modules/ms
28      ./nodejs-app/node_modules/content-type
8       ./nodejs-app/node_modules/core-util-is/lib
24      ./nodejs-app/node_modules/core-util-is
100     ./nodejs-app/node_modules/mysql/lib/protocol/packets
288     ./nodejs-app/node_modules/mysql/lib/protocol/constants
40      ./nodejs-app/node_modules/mysql/lib/protocol/sequences
496     ./nodejs-app/node_modules/mysql/lib/protocol
556     ./nodejs-app/node_modules/mysql/lib
48      ./nodejs-app/node_modules/mysql/node_modules/safe-buffer
52      ./nodejs-app/node_modules/mysql/node_modules
712     ./nodejs-app/node_modules/mysql
24      ./nodejs-app/node_modules/encodeurl
24      ./nodejs-app/node_modules/parseurl
20      ./nodejs-app/node_modules/escape-html
28      ./nodejs-app/node_modules/util-deprecate
16      ./nodejs-app/node_modules/get-intrinsic/test
8       ./nodejs-app/node_modules/get-intrinsic/.github
76      ./nodejs-app/node_modules/get-intrinsic
28      ./nodejs-app/node_modules/statuses
24      ./nodejs-app/node_modules/toidentifier
5544    ./nodejs-app/node_modules
5592    ./nodejs-app
4       ./mkdir
1972    ./images
4       ./myroot/.local/share/nano
8       ./myroot/.local/share
12      ./myroot/.local
24      ./myroot
8       ./webpage
4       ./.git/refs/tags
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
8       ./.git/refs/heads
32      ./.git/refs
4       ./.git/branches
20      ./.git/objects/8c
12      ./.git/objects/bd
24      ./.git/objects/60
12      ./.git/objects/76
16      ./.git/objects/0d
20      ./.git/objects/1b
20      ./.git/objects/59
12      ./.git/objects/9a
12      ./.git/objects/95
12      ./.git/objects/a4
12      ./.git/objects/55
24      ./.git/objects/ea
8       ./.git/objects/94
16      ./.git/objects/51
12      ./.git/objects/db
8       ./.git/objects/bc
8       ./.git/objects/e4
28      ./.git/objects/c7
20      ./.git/objects/91
28      ./.git/objects/fd
8       ./.git/objects/a8
24      ./.git/objects/09
24      ./.git/objects/06
16      ./.git/objects/01
16      ./.git/objects/d4
20      ./.git/objects/25
16      ./.git/objects/4d
32      ./.git/objects/64
24      ./.git/objects/27
12      ./.git/objects/ef
56      ./.git/objects/d8
32      ./.git/objects/5e
32      ./.git/objects/37
24      ./.git/objects/e2
8       ./.git/objects/80
12      ./.git/objects/7b
28      ./.git/objects/21
8       ./.git/objects/8b
24      ./.git/objects/df
8       ./.git/objects/9f
16      ./.git/objects/7c
24      ./.git/objects/b9
20      ./.git/objects/16
12      ./.git/objects/c9
28      ./.git/objects/e3
40      ./.git/objects/b7
40      ./.git/objects/f1
28      ./.git/objects/e5
8       ./.git/objects/da
28      ./.git/objects/d3
20      ./.git/objects/a9
24      ./.git/objects/c2
28      ./.git/objects/71
12      ./.git/objects/79
24      ./.git/objects/41
44      ./.git/objects/4f
40      ./.git/objects/ff
24      ./.git/objects/fa
24      ./.git/objects/7e
12      ./.git/objects/f3
20      ./.git/objects/03
36      ./.git/objects/cd
28      ./.git/objects/17
8       ./.git/objects/c1
12      ./.git/objects/cf
12      ./.git/objects/2d
20      ./.git/objects/1a
32      ./.git/objects/cb
16      ./.git/objects/fe
36      ./.git/objects/11
48      ./.git/objects/1c
8       ./.git/objects/9c
44      ./.git/objects/d7
16      ./.git/objects/ca
24      ./.git/objects/07
64      ./.git/objects/ac
68      ./.git/objects/20
16      ./.git/objects/92
16      ./.git/objects/54
20      ./.git/objects/67
20      ./.git/objects/c0
32      ./.git/objects/72
8       ./.git/objects/c8
20      ./.git/objects/af
36      ./.git/objects/bf
44      ./.git/objects/7f
20      ./.git/objects/0b
16      ./.git/objects/02
36      ./.git/objects/0e
28      ./.git/objects/cc
48      ./.git/objects/d5
8       ./.git/objects/5c
20      ./.git/objects/74
44      ./.git/objects/b8
8       ./.git/objects/31
20      ./.git/objects/c6
32      ./.git/objects/2a
20      ./.git/objects/a2
20      ./.git/objects/6e
32      ./.git/objects/57
32      ./.git/objects/f4
24      ./.git/objects/1f
28      ./.git/objects/ab
16      ./.git/objects/18
20      ./.git/objects/3a
20      ./.git/objects/84
8       ./.git/objects/6f
24      ./.git/objects/b2
16      ./.git/objects/65
20      ./.git/objects/35
16      ./.git/objects/05
60      ./.git/objects/eb
28      ./.git/objects/69
20      ./.git/objects/52
16      ./.git/objects/10
24      ./.git/objects/42
12      ./.git/objects/86
20      ./.git/objects/e0
16      ./.git/objects/90
16      ./.git/objects/4a
20      ./.git/objects/8f
24      ./.git/objects/fc
16      ./.git/objects/ee
16      ./.git/objects/50
40      ./.git/objects/6a
12      ./.git/objects/9e
8       ./.git/objects/36
72      ./.git/objects/f2
12      ./.git/objects/d1
1828    ./.git/objects/pack
20      ./.git/objects/0c
16      ./.git/objects/19
20      ./.git/objects/47
28      ./.git/objects/de
16      ./.git/objects/58
48      ./.git/objects/be
24      ./.git/objects/a7
32      ./.git/objects/dd
20      ./.git/objects/29
24      ./.git/objects/04
24      ./.git/objects/0f
32      ./.git/objects/e9
12      ./.git/objects/7d
28      ./.git/objects/83
28      ./.git/objects/34
8       ./.git/objects/6c
28      ./.git/objects/2f
12      ./.git/objects/13
48      ./.git/objects/f6
24      ./.git/objects/3e
16      ./.git/objects/3b
16      ./.git/objects/12
32      ./.git/objects/73
40      ./.git/objects/14
24      ./.git/objects/81
20      ./.git/objects/7a
28      ./.git/objects/82
28      ./.git/objects/62
8       ./.git/objects/30
20      ./.git/objects/08
12      ./.git/objects/ad
16      ./.git/objects/22
16      ./.git/objects/8d
36      ./.git/objects/1e
20      ./.git/objects/26
8       ./.git/objects/ce
60      ./.git/objects/e7
36      ./.git/objects/89
44      ./.git/objects/48
24      ./.git/objects/fb
12      ./.git/objects/dc
12      ./.git/objects/a3
32      ./.git/objects/f5
20      ./.git/objects/a5
24      ./.git/objects/44
24      ./.git/objects/d0
16      ./.git/objects/ba
16      ./.git/objects/70
16      ./.git/objects/32
44      ./.git/objects/61
12      ./.git/objects/2c
8       ./.git/objects/6d
12      ./.git/objects/28
20      ./.git/objects/33
20      ./.git/objects/78
12      ./.git/objects/23
16      ./.git/objects/77
8       ./.git/objects/0a
12      ./.git/objects/88
28      ./.git/objects/24
52      ./.git/objects/49
16      ./.git/objects/f8
24      ./.git/objects/4e
20      ./.git/objects/f0
32      ./.git/objects/b5
28      ./.git/objects/b1
40      ./.git/objects/9d
28      ./.git/objects/87
8       ./.git/objects/b3
24      ./.git/objects/b0
20      ./.git/objects/8e
36      ./.git/objects/5a
12      ./.git/objects/3d
40      ./.git/objects/2e
12      ./.git/objects/63
20      ./.git/objects/d6
16      ./.git/objects/d9
28      ./.git/objects/98
20      ./.git/objects/aa
12      ./.git/objects/15
16      ./.git/objects/f7
12      ./.git/objects/56
24      ./.git/objects/bb
20      ./.git/objects/46
20      ./.git/objects/96
24      ./.git/objects/39
32      ./.git/objects/38
12      ./.git/objects/2b
28      ./.git/objects/85
12      ./.git/objects/4c
8       ./.git/objects/b4
12      ./.git/objects/a0
20      ./.git/objects/43
44      ./.git/objects/ec
32      ./.git/objects/d2
48      ./.git/objects/c5
12      ./.git/objects/00
40      ./.git/objects/ae
8       ./.git/objects/ed
28      ./.git/objects/c3
20      ./.git/objects/97
24      ./.git/objects/40
8       ./.git/objects/53
20      ./.git/objects/5b
16      ./.git/objects/66
16      ./.git/objects/c4
16      ./.git/objects/75
40      ./.git/objects/3c
16      ./.git/objects/a1
24      ./.git/objects/9b
24      ./.git/objects/4b
20      ./.git/objects/93
24      ./.git/objects/6b
24      ./.git/objects/a6
28      ./.git/objects/5d
28      ./.git/objects/8a
4       ./.git/objects/info
8       ./.git/objects/1d
20      ./.git/objects/b6
28      ./.git/objects/3f
24      ./.git/objects/45
40      ./.git/objects/e1
36      ./.git/objects/68
24      ./.git/objects/5f
16      ./.git/objects/99
16      ./.git/objects/f9
12      ./.git/objects/e6
7664    ./.git/objects
68      ./.git/hooks
16      ./.git/logs/refs/remotes/origin
20      ./.git/logs/refs/remotes
12      ./.git/logs/refs/heads
36      ./.git/logs/refs
48      ./.git/logs
4       ./.git/lfs/tmp
8       ./.git/lfs
8       ./.git/info
7948    ./.git
15584   .

```

5. Run the command **ls** . ***(1 mark)*** 

```bash
  @marziq ➜ /workspaces/OSProject (main) $ ls
  README.md  images  mkdir  myroot  nodejs-app  webpage
```
6. Run the command **ls -asl** . ***(1 mark)*** 

```bash
@marziq ➜ /workspaces/OSProject (main) $ ls -asl
total 108
 4 drwxrwxrwx+ 8 codespace root       4096 Jun 22 14:40 .
 4 drwxr-xrwx+ 5 codespace root       4096 Jun 15 14:28 ..
 4 drwxrwxrwx+ 9 codespace root       4096 Jun 22 15:33 .git
76 -rw-rw-rw-  1 codespace codespace 76104 Jun 22 15:33 README.md
 4 drwxrwxrwx+ 2 codespace root       4096 Jun 15 14:28 images
 4 drwxrwxrwx+ 2 codespace codespace  4096 Jun 15 14:28 mkdir
 4 drwxrwxrwx+ 3 codespace codespace  4096 Jun 22 14:09 myroot
 4 drwxrwxrwx+ 3 codespace codespace  4096 Jun 22 14:48 nodejs-app
 4 drwxrwxrwx+ 2 codespace codespace  4096 Jun 22 14:12 webpage
```
7. Run the command **free -h** . ***(1 mark)***
```bash
@marziq ➜ /workspaces/OSProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.3Gi       311Mi        61Mi       6.2Gi       6.1Gi
Swap:            0B          0B          0B
```

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@marziq ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3244.283
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.903
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.85
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```
9. Run the command **top** and type **q** to quit. ***(1 mark)***
```bash
top - 12:56:21 up 37 min,  0 users,  load average: 0.17, 0.19, 0.27
Tasks:  17 total,   1 running,  16 sleeping,   0 stopped,   0 zombie
%Cpu(s):  2.0 us,  2.7 sy,  0.0 ni, 95.1 id,  0.2 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    150.1 free,   1509.8 used,   6269.7 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6103.8 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                             
   1233 codespa+  20   0   21.1g 349184  46336 S   1.3   4.3   0:45.60 node                                                                
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.04 docker-init                                                         
      7 codespa+  20   0    7236   1664   1664 S   0.0   0.0   0:00.01 sleep  
```
10. Run the command **uname -a**. ***(1 mark)*** __Fill answer here__.
```bash
@marziq ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-48772a 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
11. What is the available free memory in the system. ***(1 mark)***
```bash
311Mi
```
12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
```bash
Filesystem      Size  Used Avail Use% Mounted on
overlay          32G   13G   18G  41% /
tmpfs            64M     0   64M   0% /dev
shm              64M     0   64M   0% /dev/shm
/dev/root        29G   24G  5.9G  80% /vscode
/dev/sdb1        44G   88K   42G   1% /tmp
/dev/loop3       32G   13G   18G  41% /workspaces

Answer: 18G
```
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
```bash
Linux codespaces-48772a 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
```bash
ls : List only the visible files. Provides a list of files and directories in the current directory without giving any additional details. 

ls -asl : List all of the files including the hidden ones . - a (all) , -s (size) and -l (long format) files. ls -asl command lists all entries, including hidden files and directories.
```
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 
```bash
Processor 0 :  2560 4K pages
Processor 1 :  2560 4K pages
```
16. What is the CPU speed of the Virtual CPU. ***(1 mark)***
```bash
Processor 0 : 3244.283 Mhz
Processor 1 : 3243.903 Mhz
```
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
```bash
 1233 codespa+  20   0   21.1g 349184  46336 S   1.3   4.3   0:45.60 node  
```

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```

OUTPUT
```bash
@marziq ➜ /workspaces/OSProject (main) $ docker pull debian
Using default tag: latest
latest: Pulling from library/debian
Digest: sha256:a92ed51e0996d8e9de041ca05ce623d2c491444df6a535a566dabd5cb8336946
Status: Image is up to date for debian:latest
docker.io/library/debian:latest
@marziq ➜ /workspaces/OSProject (main) $ docker run --detach -it debian
]\317b3827581f02c2956ab5fc8aca3e73d8c19c12b6772ce76b61d8cdf861b29d
@marziq ➜ /workspaces/OSProject (main) $ ]
```


2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

OUTPUT
```bash
@marziq ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE          COMMAND                  CREATED         STATUS                        PORTS                                       NAMES
317b3827581f   debian         "bash"                   2 minutes ago   Up 2 minutes                                                              festive_moore
b1552e1b322e   debian         "bash"                   3 hours ago     Exited (255) 11 minutes ago                                               dreamy_merkle
f067465b6d76   debian         "bash"                   3 hours ago     Exited (255) 11 minutes ago                                               stoic_nash
4f6c811eabec   debian         "bash"                   3 days ago      Exited (137) 3 days ago                                                   elegant_carver
16faa38612d5   nodejs-app     "docker-entrypoint.s…"   2 weeks ago     Exited (255) 2 weeks ago      0.0.0.0:3000->3000/tcp, :::3000->3000/tcp   nodejs-container
670e22c744a8   mysql:latest   "docker-entrypoint.s…"   2 weeks ago     Exited (255) 2 weeks ago      3306/tcp, 33060/tcp                         mysql-container
8aa85d830151   busybox        "sh"                     2 weeks ago     Exited (255) 2 weeks ago                                                  c2
b463472d6366   busybox        "sh"                     2 weeks ago     Exited (255) 2 weeks ago                                                  c1
bbc5a9f2ac5e   httpd          "httpd-foreground"       2 weeks ago     Exited (255) 2 weeks ago      0.0.0.0:8080->80/tcp, :::8080->80/tcp       nice_jang
0a33c583825a   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   jovial_haibt
458aa3171848   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    sad_wright
8be598e57a98   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    festive_snyder
044aad6b3c49   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    affectionate_goldstine
8489dbee198e   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   great_brown
f941d503da96   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   charming_snyder
9db3aa412d77   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   recursing_carver
a0c6afd8fdcf   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    relaxed_lederberg
be68176069a7   5027089adc4c   "bash"                   2 weeks ago     Exited (255) 2 weeks ago                                                  kind_austin
4e4a5125e92a   5027089adc4c   "bash"                   3 weeks ago     Exited (255) 2 weeks ago                                                  vibrant_villani
```


3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```
OUTPUT
```bash
@marziq ➜ /workspaces/OSProject (main) $ docker exec -i -t festive_moore /bin/bash
root@317b3827581f:/# 
```
4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

OUTPUT
```bash
root@317b3827581f:/# apt-get update
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [55.4 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8786 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [13.8 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [160 kB]
Fetched 9214 kB in 1s (7623 kB/s)
Reading package lists... Done
root@317b3827581f:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (18.8 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...
root@317b3827581f:/# cd /root
root@317b3827581f:~# nano hellworld.txt
root@317b3827581f:~# 
```
5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

OUTPUT
```bash
root@317b3827581f:~# cat helloworld.txt
Hello world this is my docker

root@317b3827581f:~# pwd
/root
root@317b3827581f:~# find / -name helloworld.txt
/root/helloworld.txt
root@317b3827581f:~# ls
helloorld.txt  helloworld.txt
root@317b3827581f:~# exit
exit
```
6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

ANSWER : Yes, the file in the container still available.

OUTPUT

```bash
@marziq ➜ /workspaces/OSProject (main) $ docker stop festive_moore
festive_moore
@marziq ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE          COMMAND                  CREATED         STATUS                        PORTS                                       NAMES
317b3827581f   debian         "bash"                   8 minutes ago   Exited (137) 15 seconds ago                                               festive_moore
b1552e1b322e   debian         "bash"                   3 hours ago     Exited (255) 18 minutes ago                                               dreamy_merkle
f067465b6d76   debian         "bash"                   3 hours ago     Exited (255) 18 minutes ago                                               stoic_nash
4f6c811eabec   debian         "bash"                   4 days ago      Exited (137) 4 days ago                                                   elegant_carver
16faa38612d5   nodejs-app     "docker-entrypoint.s…"   2 weeks ago     Exited (255) 2 weeks ago      0.0.0.0:3000->3000/tcp, :::3000->3000/tcp   nodejs-container
670e22c744a8   mysql:latest   "docker-entrypoint.s…"   2 weeks ago     Exited (255) 2 weeks ago      3306/tcp, 33060/tcp                         mysql-container
8aa85d830151   busybox        "sh"                     2 weeks ago     Exited (255) 2 weeks ago                                                  c2
b463472d6366   busybox        "sh"                     2 weeks ago     Exited (255) 2 weeks ago                                                  c1
bbc5a9f2ac5e   httpd          "httpd-foreground"       2 weeks ago     Exited (255) 2 weeks ago      0.0.0.0:8080->80/tcp, :::8080->80/tcp       nice_jang
0a33c583825a   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   jovial_haibt
458aa3171848   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    sad_wright
8be598e57a98   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    festive_snyder
044aad6b3c49   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    affectionate_goldstine
8489dbee198e   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   great_brown
f941d503da96   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   charming_snyder
9db3aa412d77   httpd          "httpd-foreground"       2 weeks ago     Created                                                                   recursing_carver
a0c6afd8fdcf   httpd          "httpd-foreground"       2 weeks ago     Exited (0) 2 weeks ago                                                    relaxed_lederberg
be68176069a7   5027089adc4c   "bash"                   2 weeks ago     Exited (255) 2 weeks ago                                                  kind_austin
4e4a5125e92a   5027089adc4c   "bash"                   3 weeks ago     Exited (255) 2 weeks ago                                                  vibrant_villani
@marziq ➜ /workspaces/OSProject (main) $ docker restart festive_moore
festive_moore

@marziq ➜ /workspaces/OSProject (main) $ cat /root/helloworld.txt
cat: /root/helloworld.txt: Permission denied
@marziq ➜ /workspaces/OSProject (main) $ docker exec -i -t festive_moore /bin/bash
root@317b3827581f:/# cd /root
root@317b3827581f:~# ls
helloorld.txt  helloworld.txt
root@317b3827581f:~# cat helloworld.txt
Hello world this is my docker

root@317b3827581f:~# exit
exit
@marziq ➜ /workspaces/OSProject (main) $ docker stop festive_moore
festive_moore
@marziq ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE          COMMAND                  CREATED          STATUS                        PORTS                                       NAMES
317b3827581f   debian         "bash"                   12 minutes ago   Exited (137) 23 seconds ago                                               festive_moore
b1552e1b322e   debian         "bash"                   3 hours ago      Exited (255) 22 minutes ago                                               dreamy_merkle
f067465b6d76   debian         "bash"                   3 hours ago      Exited (255) 22 minutes ago                                               stoic_nash
4f6c811eabec   debian         "bash"                   4 days ago       Exited (137) 4 days ago                                                   elegant_carver
16faa38612d5   nodejs-app     "docker-entrypoint.s…"   2 weeks ago      Exited (255) 2 weeks ago      0.0.0.0:3000->3000/tcp, :::3000->3000/tcp   nodejs-container
670e22c744a8   mysql:latest   "docker-entrypoint.s…"   2 weeks ago      Exited (255) 2 weeks ago      3306/tcp, 33060/tcp                         mysql-container
8aa85d830151   busybox        "sh"                     2 weeks ago      Exited (255) 2 weeks ago                                                  c2
b463472d6366   busybox        "sh"                     2 weeks ago      Exited (255) 2 weeks ago                                                  c1
bbc5a9f2ac5e   httpd          "httpd-foreground"       2 weeks ago      Exited (255) 2 weeks ago      0.0.0.0:8080->80/tcp, :::8080->80/tcp       nice_jang
0a33c583825a   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   jovial_haibt
458aa3171848   httpd          "httpd-foreground"       2 weeks ago      Exited (0) 2 weeks ago                                                    sad_wright
8be598e57a98   httpd          "httpd-foreground"       2 weeks ago      Exited (0) 2 weeks ago                                                    festive_snyder
044aad6b3c49   httpd          "httpd-foreground"       2 weeks ago      Exited (0) 2 weeks ago                                                    affectionate_goldstine
8489dbee198e   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   great_brown
f941d503da96   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   charming_snyder
9db3aa412d77   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   recursing_carver
a0c6afd8fdcf   httpd          "httpd-foreground"       2 weeks ago      Exited (0) 2 weeks ago                                                    relaxed_lederberg
be68176069a7   5027089adc4c   "bash"                   2 weeks ago      Exited (255) 2 weeks ago                                                  kind_austin
4e4a5125e92a   5027089adc4c   "bash"                   3 weeks ago      Exited (255) 2 weeks ago                                                  vibrant_villani
@marziq ➜ /workspaces/OSProject (main) $ 
```


7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```


ANSWER : The modifications done inside the container including the generation of helloworld.txt will be erased once the container being stop and deleted.

OUTPUT
```bash
@marziq ➜ /workspaces/OSProject (main) $ docker rm festive_moore
festive_moore
@marziq ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE          COMMAND                  CREATED       STATUS                        PORTS                                       NAMES
b1552e1b322e   debian         "bash"                   3 hours ago   Exited (255) 23 minutes ago                                               dreamy_merkle
f067465b6d76   debian         "bash"                   3 hours ago   Exited (255) 23 minutes ago                                               stoic_nash
4f6c811eabec   debian         "bash"                   4 days ago    Exited (137) 4 days ago                                                   elegant_carver
16faa38612d5   nodejs-app     "docker-entrypoint.s…"   2 weeks ago   Exited (255) 2 weeks ago      0.0.0.0:3000->3000/tcp, :::3000->3000/tcp   nodejs-container
670e22c744a8   mysql:latest   "docker-entrypoint.s…"   2 weeks ago   Exited (255) 2 weeks ago      3306/tcp, 33060/tcp                         mysql-container
8aa85d830151   busybox        "sh"                     2 weeks ago   Exited (255) 2 weeks ago                                                  c2
b463472d6366   busybox        "sh"                     2 weeks ago   Exited (255) 2 weeks ago                                                  c1
bbc5a9f2ac5e   httpd          "httpd-foreground"       2 weeks ago   Exited (255) 2 weeks ago      0.0.0.0:8080->80/tcp, :::8080->80/tcp       nice_jang
0a33c583825a   httpd          "httpd-foreground"       2 weeks ago   Created                                                                   jovial_haibt
458aa3171848   httpd          "httpd-foreground"       2 weeks ago   Exited (0) 2 weeks ago                                                    sad_wright
8be598e57a98   httpd          "httpd-foreground"       2 weeks ago   Exited (0) 2 weeks ago                                                    festive_snyder
044aad6b3c49   httpd          "httpd-foreground"       2 weeks ago   Exited (0) 2 weeks ago                                                    affectionate_goldstine
8489dbee198e   httpd          "httpd-foreground"       2 weeks ago   Created                                                                   great_brown
f941d503da96   httpd          "httpd-foreground"       2 weeks ago   Created                                                                   charming_snyder
9db3aa412d77   httpd          "httpd-foreground"       2 weeks ago   Created                                                                   recursing_carver
a0c6afd8fdcf   httpd          "httpd-foreground"       2 weeks ago   Exited (0) 2 weeks ago                                                    relaxed_lederberg
be68176069a7   5027089adc4c   "bash"                   2 weeks ago   Exited (255) 2 weeks ago                                                  kind_austin
4e4a5125e92a   5027089adc4c   "bash"                   3 weeks ago   Exited (255) 3 weeks ago                                                  vibrant_villani
@marziq ➜ /workspaces/OSProject (main) $ 
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** 
```bash
No, files in a container are not persistent because containers reset every time they run.
 
```
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** 
```bash
Yes. Every container has its own file system, processes and operates independently. Based on the Debian image, many containers can be construct, each will run a separate instance of Debian Linux.
```

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

OUTPUT
```bash
@marziq ➜ /workspaces/OSProject (main) $ mkdir myroot
@marziq ➜ /workspaces/OSProject (main) $ cd myroot/
@marziq ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot
@marziq ➜ /workspaces/OSProject/myroot (main) $ --detach -it -v /workspaces/OSProject/myroot:/root debian
bash: --detach: command not found
@marziq ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
c58712141ff3782e72064c18db07c0088992c749591a06c46853d736bb7f13ea
@marziq ➜ /workspaces/OSProject/myroot (main) $ 
```

```bash
@marziq ➜ /workspaces/OSProject/myroot (main) $ docker ps -a
CONTAINER ID   IMAGE          COMMAND                  CREATED          STATUS                        PORTS                                       NAMES
c58712141ff3   debian         "bash"                   40 seconds ago   Up 39 seconds                                                             flamboyant_sanderson
b1552e1b322e   debian         "bash"                   3 hours ago      Exited (255) 34 minutes ago                                               dreamy_merkle
f067465b6d76   debian         "bash"                   3 hours ago      Exited (255) 34 minutes ago                                               stoic_nash
4f6c811eabec   debian         "bash"                   4 days ago       Exited (137) 4 days ago                                                   elegant_carver
16faa38612d5   nodejs-app     "docker-entrypoint.s…"   2 weeks ago      Exited (255) 2 weeks ago      0.0.0.0:3000->3000/tcp, :::3000->3000/tcp   nodejs-container
670e22c744a8   mysql:latest   "docker-entrypoint.s…"   2 weeks ago      Exited (255) 2 weeks ago      3306/tcp, 33060/tcp                         mysql-container
8aa85d830151   busybox        "sh"                     2 weeks ago      Exited (255) 2 weeks ago                                                  c2
b463472d6366   busybox        "sh"                     2 weeks ago      Exited (255) 2 weeks ago                                                  c1
bbc5a9f2ac5e   httpd          "httpd-foreground"       2 weeks ago      Exited (255) 2 weeks ago      0.0.0.0:8080->80/tcp, :::8080->80/tcp       nice_jang
0a33c583825a   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   jovial_haibt
458aa3171848   httpd          "httpd-foreground"       2 weeks ago      Exited (0) 2 weeks ago                                                    sad_wright
8be598e57a98   httpd          "httpd-foreground"       2 weeks ago      Exited (0) 2 weeks ago                                                    festive_snyder
044aad6b3c49   httpd          "httpd-foreground"       2 weeks ago      Exited (0) 2 weeks ago                                                    affectionate_goldstine
8489dbee198e   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   great_brown
f941d503da96   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   charming_snyder
9db3aa412d77   httpd          "httpd-foreground"       2 weeks ago      Created                                                                   recursing_carver
a0c6afd8fdcf   httpd          "httpd-foreground"       3 weeks ago      Exited (0) 2 weeks ago                                                    relaxed_lederberg
be68176069a7   5027089adc4c   "bash"                   3 weeks ago      Exited (255) 2 weeks ago                                                  kind_austin
4e4a5125e92a   5027089adc4c   "bash"                   3 weeks ago      Exited (255) 3 weeks ago                                                  vibrant_villani
@marziq ➜ /workspaces/OSProject/myroot (main) $ docker exec -i -t flamboyant_sanderson /bin/bash
root@c58712141ff3:/# 
```
***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** 

OUTPUT
```bash
root@c58712141ff3:~# cd /root
root@c58712141ff3:~# nano helloNice.txt 
root@c58712141ff3:~# cat helloNice.txt 
Hello Niceeeee
root@c58712141ff3:~# ls -l /root/helloNice.txt
-rw-rw-rw- 1 root root 15 Jun 22 13:49 /root/helloNice.txt
root@c58712141ff3:~# 
```

```bash
ANSWER : The output -rw-rw-rw- 1 root root 15 Jun 22 13:49 /root/helloNice.txt can be broken down as follows:
-rw-rw-rw- : These are the permissions for the file. In this case, it indicates that the file is readable and writeable for all users (owner, group and others)
1 : This indicates the number of hard links to the file
root : The first occurrence of root indicates the user who owns the file. In this case, it's owned by the root user.
root : The second occurrence of root indicates the group to which the file belongs. In this case, it's assigned to the root group
15 : This represents the file size in bytes.
Jun 22 13:49 : This indicates the date and time when the file was last modified.
/root/helloNice.txt : This is the path to the file.
Therefore, based on the provided information:
User : root
Group : root
The file helloNice.txt is owned by the root user and belongs to the root group within the Docker container.
```

2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash

//use sudo and chown
sudo chown -R codespace:codespace myroot

```

ANSWER : Yes, we can change the permission of the files to user codespace.

```bash
root@c58712141ff3:~# adduser codespace
Adding user `codespace' ...
Adding new group `codespace' (1000) ...
Adding new user `codespace' (1000) with group `codespace (1000)' ...
Creating home directory `/home/codespace' ...
Copying files from `/etc/skel' ...
New password: 
Retype new password: 
passwd: password updated successfully
Changing the user information for codespace
Enter the new value, or press ENTER for the default
        Full Name []: Ammar
        Room Number []: G31
        Work Phone []: 0198389538
        Home Phone []: 
        Other []: 
Is the information correct? [Y/n] Y
Adding new user `codespace' to supplemental / extra groups `users' ...
Adding user `codespace' to group `users' ...
root@c58712141ff3:~# chown -R codespace:codespace /root
```

```bash
root@c58712141ff3:~# ls -l /root
total 4
-rw-rw-rw- 1 codespace codespace 15 Jun 22 13:49 helloNice.txt
root@c58712141ff3:~# 
```

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

URL LINK FOR INDEX.HTML : https://upgraded-fiesta-p476wq75jv4364r-8080.app.github.dev/

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 
```bash
drwxrwxrwx+ 2 1000 1000 4096 Jun 22 14:12 /usr/local/apache2/htdocs

Permissions (drwxr-xr-x) :

d : Indicates it's a directory.
rwx : Owner (root) has read, write, and execute permissions.
r-x : Group (root) has read and execute permissions.
r-x : Others have read and execute permissions.
Owner and Group:

Owner : root
Group : root
```

2. What port is the apache web server running. ***(1 mark)*** 
```bash
Container Port 80, Host Port 8080
```
3. What port is open for http protocol on the host machine? ***(1 mark)*** 
```bash
tcp        0      0 0.0.0.0:8080            0.0.0.0:*               LISTEN     
tcp6       0      0 :::8080                 :::*                    LISTEN  

```

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** 
```bash
BusyBox : BusyBox is a single binary that provides simplified versions of many standard UNIX utilities. It is commonly used in Docker containers due to its small size and ability to provide a functional Linux environment in a minimal footprint.

--name : This command switch in Docker is used to assign a name to a container. It allows you to specify a custom, human-readable name instead of relying on Docker's default naming convention, which uses random words or number
```

2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)*** 
```bash
@marziq ➜ /workspaces/OSProject (main) $ docker network ls
NETWORK ID     NAME        DRIVER    SCOPE
a43ab620e1cb   bluenet     bridge    local
7468fd238c7a   bridge      bridge    local
8c1bec473dcb   bridgenet   bridge    local
6750144f8721   host        host      local
2c5233b24c0e   mysqlnet    bridge    local
74b18fbb5a7b   nodejsnet   bridge    local
08b6a5c9336c   none        null      local
55e8149ecd12   rednet      bridge    local
```

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)*** 
```bash
Bluenet gateway : 172.18.0.1
Rednet gateway  : 172.19.0.1
```

4. What is the network address for the running container c1 and c2? ***(1 mark)*** 
```bash
C1 : 172.18.0.2
C2 : 172.19.0.2
```

5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** 
```bash
ANSWER : No, I cannot ping C1 to C2

OUTPUT : 
@marziq ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
ping: bad address 'c2'

```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```
OUTPUT

```bash
@marziq ➜ /workspaces/OSProject (main) $ docker network create bridgenet
2ac5a077371e789db9db28e863de3f25b37248444d9f6c4d7e01213600503ae8
@marziq ➜ /workspaces/OSProject (main) $ docker network connect bridgenet c1
@marziq ➜ /workspaces/OSProject (main) $ docker network connect bridgenet c2
@marziq ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
```

***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** 

```bash
ANSWER : Yes, I can ping. 

OUTPUT : 
@marziq ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.159 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.070 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.059 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=6 ttl=64 time=0.069 ms
64 bytes from 172.20.0.3: seq=7 ttl=64 time=0.085 ms
64 bytes from 172.20.0.3: seq=8 ttl=64 time=0.062 ms
64 bytes from 172.20.0.3: seq=9 ttl=64 time=0.065 ms
...
```

2. What is different from the previous ping in the section above? ***(1 mark)*** 
```bash
In previous ping, we could not ping because we have not yet bridge the network.
```
## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

OUTPUT
```bash
@marziq ➜ /workspaces/OSProject (main) $ docker network create nodejsnet
9379a8631fca0dbec61895292abe5e377fd8e1dc18b15f5e5badb4eebc80edf2
@marziq ➜ /workspaces/OSProject (main) $ docker network create mysqlnet
70656e7d2a3a0f3472448722b75f66342d3031b27f295cd9440e858caa1b8952
```
#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

    ```sh
    mkdir nodejs-app
    cd nodejs-app
    npm init -y
    npm install express mysql
    ```

    OUTPUT
```bash
    @marziq ➜ /workspaces/OSProject (main) $ mkdir nodejs-app
tall express mysql
@marziq ➜ /workspaces/OSProject (main) $ cd nodejs-app
@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ npm init -y

Wrote to /workspaces/OSProject/nodejs-app/package.json:

{
  "name": "nodejs-app",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": ""
}


@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ npm install express mysql

added 76 packages, and audited 77 packages in 11s

12 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```
OUTPUT
```bash
@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ nano Dockerfile
```
#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
    docker build -t nodejs-app .
    ```
OUTPUT
```bash
@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ docker build -t nodejs-app .
[+] Building 15.1s (11/11) FINISHED                                                                                         docker:default
 => [internal] load build definition from Dockerfile                                                                                  0.1s
 => => transferring dockerfile: 407B                                                                                                  0.0s
 => [internal] load metadata for docker.io/library/node:14                                                                            1.8s
 => [auth] library/node:pull token for registry-1.docker.io                                                                           0.0s
 => [internal] load .dockerignore                                                                                                     0.0s
 => => transferring context: 2B                                                                                                       0.0s
 => [1/5] FROM docker.io/library/node:14@sha256:a158d3b9b4e3fa813fa6c8c590b8f0a860e015ad4e59bbce5744d2f6fd8461aa                      0.0s
 => [internal] load build context                                                                                                     0.2s
 => => transferring context: 3.36MB                                                                                                   0.2s
 => CACHED [2/5] WORKDIR /usr/src/app                                                                                                 0.0s
 => [3/5] COPY package*.json ./                                                                                                       0.4s
 => [4/5] RUN npm install                                                                                                             7.2s
 => [5/5] COPY . .                                                                                                                    0.4s
 => exporting to image                                                                                                                4.5s
 => => exporting layers                                                                                                               4.4s
 => => writing image sha256:0bfc9759f2ca459d0b8e075a9556751380526cdadf92bb494a4631c0afc762cf                                          0.0s
 => => naming to docker.io/library/nodejs-app     
```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
    docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
    ```
    OUTPUT
```bash
@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
f95ceedeaf22d7b5a08f087f0d979a28eb50e6e89f7c18673b80bcbb0f234cdc
```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
curl http://localhost:3000/random
```

OUTPUT

```bash
@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ curl http://localhost:3000/random
Server Error@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ 
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
CREATE TABLE mytable (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  value VARCHAR(255) NOT NULL
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

OUTPUT

```bash
bash-5.1# mysql -uroot -p
Enter password: 
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 10
Server version: 8.4.0 MySQL Community Server - GPL

Copyright (c) 2000, 2024, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> CREATE TABLE mytable (
    ->   id INT AUTO_INCREMENT PRIMARY KEY,
    ->   name VARCHAR(255) NOT NULL,
    ->   value VARCHAR(255) NOT NULL
    -> );
ERROR 1046 (3D000): No database selected
mysql> USE mydatabase;
Database changed
mysql> CREATE TABLE mytable (
    ->   id INT AUTO_INCREMENT PRIMARY KEY,
    ->   name VARCHAR(255) NOT NULL,
    ->   value VARCHAR(255) NOT NULL
    -> );
Query OK, 0 rows affected (0.09 sec)

mysql> SHOW TABLES;
+----------------------+
| Tables_in_mydatabase |
+----------------------+
| mytable              |
+----------------------+
1 row in set (0.00 sec)

mysql> INSERT INTO mytable (name, value) VALUES
    ->   ('example1', 'value1'),
    ->   ('example2', 'value2'),
    ->   ('example3', 'value3');
Query OK, 3 rows affected (0.04 sec)
Records: 3  Duplicates: 0  Warnings: 0

mysql> SELECT * FROM mytable;
+----+----------+--------+
| id | name     | value  |
+----+----------+--------+
|  1 | example1 | value1 |
|  2 | example2 | value2 |
|  3 | example3 | value3 |
+----+----------+--------+
3 rows in set (0.00 sec)
```
### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)***
```bash
@marziq ➜ /workspaces/OSProject/nodejs-app (main) $ curl http://localhost:3000/random
Server Error@marziq ➜ /workspaces/OSProject/nodejs-app (main) $

The output Server Error from the curl command when accessing http://localhost:3000/random indicates that there was an error while processing the request in your Node.js application

Connection Error with MySQL:

The Node.js application (index.js) connects to the MySQL database (mysql-container) to retrieve a random row from the mytable.
If the MySQL container (mysql-container) is not running or if there is a network connectivity issue between the Node.js container (nodejs-container) and the MySQL container, the connection attempt will fail.
This failure could result in an error being thrown when attempting to execute the MySQL query, causing a Server Error response.
MySQL Container Status:

Ensure that the MySQL container (mysql-container) is running and accessible from the Node.js container (nodejs-container).
We can check the status of Docker containers using docker ps to see if both containers are up and running.
Error Handling in Node.js Application:

If there's an error during the MySQL query execution in index.js, the application might respond with a generic Server Error message.
Review the error handling in Node.js application to log detailed error messages (console.error) and return appropriate HTTP status codes (res.status(500) for server errors.
Check Node.js Application Logs:

Inspect the logs of Node.js application (nodejs-container) to see if there are any specific error messages that can provide more insight into what went wrong.
Use docker logs nodejs-container to view logs from the Node.js container.
```

2. Show the instruction needed to make this work. ***(1 mark)***


The Troubleshooting Steps

1. Check MySQL Container Status:

First, verify that MySQL container (mysql-container) is running and accessible. Use the following command to check its status:

```bash
docker ps -a
Ensure that mysql-container is listed and has the status Up (not Exited).
```

2. Verify Docker Networks:

Confirm that both mysql-container and nodejs-container are connected to the correct Docker networks (mysqlnet and nodejsnet). We can list Docker networks with:

```bash
docker network ls

--Check if both mysqlnet and nodejsnet exist and confirm that containers are attached to these networks.
```

3. Access MySQL Container Logs:

Review the logs of MySQL container (mysql-container) to check for any startup errors or issues:

```bash

docker logs mysql-container
--Look for any errors related to MySQL initialization or connectivity issues.
```

4. Node.js Application Configuration:

Ensure that Node.js application (index.js) has the correct MySQL connection settings. Double-check the following in index.js:

Hostname should be mysql-container.
Username (myuser) and password (mypassword) should match the credentials set up in MySQL container.
Database name (mydatabase) should match the name of MySQL database.
Here is example of how MySQL connection setup in index.js should look:

```bash
javascript

const connection = mysql.createConnection({
  host: 'mysql-container',
  user: 'myuser',
  password: 'mypassword',
  database: 'mydatabase'
});
```

5. Restart Node.js Container:
If any changes made to index.js or if suspect issues with the Node.js container (nodejs-container), restart it:

```bash
docker restart nodejs-container
```

6. Test Endpoint:
After ensuring all configurations are correct and containers are running, test Node.js application endpoint again using curl:

```bash
curl http://localhost:3000/random
```

If everything is set up correctly, we should receive a JSON response with a random row from mytable table.




## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
