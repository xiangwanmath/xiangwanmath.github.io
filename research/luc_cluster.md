---
layout: page
title: "LUC ITS Cluster"
permalink: /luc_cluster
---

There are various computing clusters available to students at Loyola. Take a look first at
[LUC Computational Resources](https://www.luc.edu/its/rcs/computationalresources/)

**Students users need**
If you are a student, beside an account on the server, you will also need a VPN access to connect to the servers (including `mongo1`, `mongo2`, `rock`, `freya`, etc.) You need a faculty to request both the account setup and the VPN access for you.


 - accounts set up on the server(s)
 - to gain authorization from ITS, even though they are on campus

#### 1.  [How to Access Cluster for First Time](https://github.com/xiangwanmath/xiangwanmath.github.io/blob/f6e1bee1e7df99f6d981fa8f5f3a5866a01992f9/research/ClusterAccessInstructions.pdf)

To connect directly, you can open terminal (macOS or Linux) or Powershell / CMD (Windows) and type (replace `mongo1` with the server you are connecting to)

`ssh username@mongo1.luc.edu`, then hit `Enter`. It will prompt you to enter the password.


#### 2. [Linux Command Cheat Sheet](https://www.guru99.com/linux-commands-cheat-sheet.html)

#### 3. Let a job run in the background
1.  After you SSH into the server, just run `screen`. That will take you into a background terminal/session, where one can run a process (without finishing).
2. Then to disconnect, press/type `CTRL+A+D`. That will disconnect you from the current session, but everything still run. 
3. To connect back into the sessions, type `screen -r`. If you have multiple sessions, then when you type in `screen -r`, you will see the list of them. In that case you can type in `screen -r <PID Number>` to connect.
4. Type `exit` to quit the current session.

#### 4. 

