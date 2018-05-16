---
title: OSCP Labs - Day 1
layout: single
author_profile: true
read_time: false
comments: null
share: true
related: true
---
_______________________________________________________________________________________________________________________________________

While this technically not the first, it was the first day I actually got to work in the labs. I've gone through the course material before and the exercises, so I had a fair idea of where I needed to start. I picked a couple of low-hanging fruits and off to the races I went. 

I ended up netting two roots within a few hours, Alice and Mike. From there I found another host that seems like the path to exploitation is straightforward, it is just a better of figuring out what to get my shellcode to execute. Alice was fairly trivial, though I struggled for a bit with getting a shell. I even broke down and tried the metasploit module - which failed. After burning a fair bit of my resets, I discovered the issue. Went with a different shell and viola! Manual and metasploit exploitation on this one. 

Mike was a bit of a different story. There is a giveaway for him that you come across in the course material - but I won't give any spoilers. Nikto should give you all that you need to know about good o'le Mike. Directory brute forcing will work as well. There is a great write-up about the vulnerability once you find the avenue. The third host I came across allows the HTTP PUT verb, so I think this will be the path to exploitation. Knowing Offensive Security though, this could be just a rabbit hole. 

Overall a pleasant evening in the labs. Looking forward to hitting them again and getting another root. 

Roots: Alice, Mike. 
