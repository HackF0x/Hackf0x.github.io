---
title: Root filled weekend
layout: single
author_profile: true
read_time: false
comments: null
share: true
related: true
excerpt_separator: <!--more-->
---
_______________________________________________________________________________________________________________________________________
Quite the busy weekend! I took a couple of nights off since I will be traveling this weekend to Atlanta to visit a client. The downtime gave me a chance to charge my batteries and hit the labs hard over the weekend. I spent the better part of the weekend buried in the labs and it paid off - 5 new roots and another host that I am close to getting a shell on. 
<!--more-->
The weekend left me with several lessons learned. Don't always expect msfvenom to produce the best shell. It is great for a quick shell, but there are better ones out there. The perfect example of this is their PHP reverse shell. I struggled with a machine over the weekend because my shell kept dropping frequently. I had the right path to exploitation but could not escalate due to the shell dropping. I hunted around and found a really good PHP reverse TCP shell from pentestmonkey - https://github.com/pentestmonkey/php-reverse-shell. A stable low priv shell makes all the difference for finding the path to root. 

You will hear everyone keep saying that enumeration is the key to the OSCP. It is the absolute truth. If you can't find a foothold, you have not enumerated enough. Every time I struggle on a machine and then root it, I look back and see the answer was there waiting for me the whole time. I don't think the goal of the OSCP is to teach you specific exploits or techniques. It is to teach you how to find the path you need. To properly research and reason your way through a machine. You will learn new tools and techniques, but the important lesson is how to be sufficient with the unknown. It teaches the mindset that you need to be successful. I have learned more in these labs than I ever could reading form a book. 

This weekend brought me the first machine on my list that required an exploit that wasn't directly exploitable. There may be other ways to escalate but my method seemed to have the best chance of success. Read up on your port forwarding, because you will need it in the labs. I will say though, so far that host has been my favorite. 

My weak spots will continue to be privilege escalation. I will probably schedule my exam for some time near the end of June or early July. That will give me some lab time left over if I fail and need to come back. Buffer overflows and privilege escalation is going to be two subjects I will have to better understand before I stand a chance in the exam.

Roots: Alice, Mike, Ralph, Phoenix, Kraken, Susie, Alpha, Gamma.
