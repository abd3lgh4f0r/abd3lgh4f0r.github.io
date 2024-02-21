---
title: LLMNR POISONING
author: ABDELGHAFOUR BOUHDYD
date: 2024-02-21 22:19:00 +0100
categories: [Active Directory]
tags: [blog]
render_with_liquid: false
---
**LLMNR  POISONING**
  - In this blog  i'm  gonna explain one of the most used attack in active directory hacking.

    LLMNR  or LOCAL LINK MULTICAST NAME RESOLUTION  is a protocol used by windows machine to resolve the names of neighbouring computers without using a domain name system (DNS) server.To achieve this the windows machine sends multicast queries over local networks asking if any specific computers with certain names exist and whether any have responded with their IP addresses when queried by LLMNR.

    LLMNR poisoning is a man-in-the-middle (MITM) attack that exploits this protocol.An attacker send a poisned answer to the victim machine , forcing computers that ask for LLMNR information instead to communicate directly with the attacker instead of their intended targets , Once connected with them, attackers can capture sensitive data.
    
    Here is an example of LLMNR POISONING ATTACK :
    ![Desktop View](/../media/image.png)