---
title: OSCP Write-up
layout: single
author_profile: true
read_time: false
comments: null
share: true
related: true
excerpt_separator: <!--more-->
---
_______________________________________________________________________________________________________________________________________
The OSCP has been the single most difficult challenge of my professional career. It tested my limits time and time again, pushing me further every time I stepped into the labs. "Try Harder" became a mantra and a phrase to live by. There is nothing in the labs that is impossible. The OSCP labs are designed to be difficult but doable, the difference between failure and success is you. The purpose of the course and the exam is not to teach you about any specific vulnerability or exploit technique, it is about developing methodology and mindset. If you cannot succeed in the OSCP because you cannot try harder, how will you ever be successful in the real world where you can't buy more lab time with a client who is expecting a thorough engagement? The OSCP will prepare you for dealing with challenges and digging through to find the way. All-in-all, I managed to compromise 43 hosts in 40 days of labtime, including all of the big baddies. 
<!--more-->
About Me:

Prior to the OSCP I had roughly a years worth of pentesting experience. In my career I have dabbled in a bit of everything from network engineering to analyst work, preferring the "Jack of All, Master of None" approach. Having a diversified background benefited me during the course, having been exposed to different technologies. Academic wise, the only offensive course I have completed before was eLearnSecuritys PTS course. 

The Course:

The training materials provided by Offensive Security are more than sufficient for getting started in the labs. My recommendation is to go through the PDF and videos together, section by section. If you follow each exercise presented, you will finish the training material will enough to compromise a handful of hosts. There is no particular order that is advised, but you will quickly figure out which services are more complicated and which services will be the easiest foothold. There are some mechanics in the lab machines that you may not see on the exam, so don't fret if you can't get those boxes. You will understand more about what that means once you start the lab and run across one of the hosts. I can't spoil all the fun, can I? 

Your lab time is best spent trying to expose yourself to as many boxes as possible. If you struggle more than a day or two on any particular host - move on and come back later. I feel like this is an absolutely critical requirement that I struggled with. The further down the rabbit hole one goes, the harder it becomes to dig yourself out. I spent days on hosts that I later came back to and easily popped. The more time you sink into a particular path, the harder it is to admit you are wrong. No one wants to admit they have wasted hours upon hours going down the opposite side of the highway, but hey - sometimes it happens. Time management is paramount in the course and even more-so in the exam. Set timers for a box and when its up - cycle out to another one. 

Speaking of time management and administrative tasks - notes! I used CherryTree to keep track of all the notes about the lab network. I cannot stress enough that you do this from the start. I failed to keep proper notes when I started and because of this, I had to figure out certain hosts again when I circled back to them. Record everything - not just what works. You will kick yourself in the ass later if you don't. Trust me. My own shoe print is still on my backside. 

The standard recommendation for lab time is 90 days and I cannot disagree with that. You can get by with less time if you have some experience. In hindsight, 60 days of lab time would have been more than enough for me. It's better to be cautious and not have interruptions during your lab. The cost difference is negated by the ROI I think the certification provides. There really isn't anything that competes with this at the price level. SANS has some amazing training but it is bananas expensive. eLearnSecurity has great training as well for a similar price point but the name recognition is not there and the experience is nowhere near as intense as the OSCP is. 

The Exam:

The exam is simply put: a beast. You will sweat and you will curse. Time management is no longer a recommendation but a requirement. You have 24 hours to obtain 70 points (65 points if you did the lab write-up and exercises) and another 24 hours to write the report. One thing that is not often discussed in reviews is the timing. My recommendation is to select a start time in the afternoon. This will give you time to get some rest in between. If you start at 6-9AM, then you don't have the same benefit as someone who started at 3 PM. The person who started at 3 PM will work till the wee hours of the morning then grab some Zs and hit it again refreshed. 

I started my exam at 3 PM and wrapped up with 75 points at 5 AM. One of my mistakes was not taking enough breaks. During the whole time, I only got up a handful of times. I didn't eat and only drank minimal amounts of water. This is not the way to do it. I repeat, do not do this. You may pass but your body will hate you for a few days after. 

In the exam, you will be given five boxes worth a variety of points. You will encounter the following: 25 point box (2), 20 point box (2), 10 point box (1). The order you do them it is entirely up to you. I've seen different folks tackle it differently. One of the 25 point boxes will always be a buffer overflow and the majority of people will go for that one first.  While doing that box, you should have recon running against all the other hosts. By the time you finish your overflow box, the scans should be complete and you will have a base to go from. I went for the 20 point boxes first and then the 10 point box. Some people go straight for the other 25 point box. 

Both of the 20 point boxes fell without too much trouble. I had 65 points within 7 hours and honestly was kicking myself for not having done the lab write-up. I could have walked away right then with enough points if I had. Alas, I didn't so I had to conquer one more box. This is where things got frustrating for me and I spent the next several hours rolling around in the dirt while howling at the moon. Around 5 AM some wizardry happened and I was able to successfully exploit the 10 point box. I can't (and won't) give spoilers to any of the boxes but what kept me from immediately getting this box was a networking issue. I needed something from the box and during the transfer, something kept breaking. I spent over 5 hours banging my head against a bad transfer. On that fateful final transfer, I noticed the size was slightly different than before and behold - what I needed was correct this time. 

Overall the exam does a good job of stepping up the difficulty of the lab. In terms of exploit difficulty, you will not find a significant increase in the level of effort but the time restriction adds a new level of stress. You can spend days poking at a machine in the lab. In the exam, you got 23 hours and 45 minutes to own multiple boxes. This puts an enormous pressure on your that will cause minor mistakes to become big mistakes. The exam is absolutely doable if you have taken the time to hone your skills in the lab. Patience and Practice. That's all that is required.

Conclusion and Whats Next:

Looking back on the experience, I am thankful to have obtained my OSCP certification. It was a humbling experience to see a success where before I had a failure. There is nothing like the feeling of seeing that root prompt after struggling with a box for so long. The mindset I obtained during the course and exam will help me further my studies and career. If the question is Should I do the OSCP? The answer is yes. Always, yes. You don't have to be an infosec wizard to take this course and be successful. It's not about experience or intelligence. It's about drive. If you can drive yourself to never quit, you can become an OSCP. You may require more time than others, but that is OK. Not everyone in the same physics class learns the material at the same rate. 

As for whats next, I think I will spend some time focusing on web applications and start participating in bug bounties to help further my skill set. HackTheBox also seems like an interesting place to spend some time learning new things and keeping everything I learned in the OSCP fresh. I will be starting a new position as a threat hunter soon with a new company, so I will have that to focus on for the next bit as well. Certification wise, I have a PTPv4 elite voucher that I need to use so I may try to take a shot at the eCPPT.

Overall, I cannot recommend the OSCP course enough. This concludes my little write-up of my OSCP experience. I could write a formal prep guide but honestly there isn't anything I could say that someone else hasn't already said better. Good luck guys and always try harder!
