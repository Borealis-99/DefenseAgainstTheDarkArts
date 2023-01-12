# Lab: The Fall 2022 Password Cracking Contest

## Instructions and Rules

Crack as many of the password hashes (below) that you can.

For students in the CS 116 Introduction to Security courses at Tufts University, submit your pot of passwords using `username:password` format for each password that you crack on Canvas.  One `username:password` per line.  Be sure to describe your cracking methodology.  You will have unlimited submissions and an entire month to do this lab.  Only inline (cut-and-paste) submissions will be accepted for this lab (e.g., no PDFs, no URLs allowed).

## The Password Hashes

<pre>
jackbear:$1$1PCUCGHC$fQc9fYcA0RHYh6hQdWru.1:1001:1001:,,,:/home/jackbear:/bin/bash
brotherbear:$1$.pDUkCfX$GxHhU/95p8K5kBFxXT.af1:1002:1002:,,,:/home/brotherbear:/bin/bash
fancybear:$1$o16/J6q0$ONpqQ65OCmSVClDVMw9IG.:1003:1003:,,,:/home/fancybear:/bin/bash
barneybear:$1$2Z2Ti73q$HAtV0MFdvtmtG1zoUiPFM0:1004:1004:,,,:/home/barneybear:/bin/bash
pandabear:$1$Pko6Qgvz$t06QJrYj3mXf3rURR6ApG1:1005:1005:,,,:/home/pandabear:/bin/bash
yogibear:$1$owv3ovwW$Wm.i.j6W9Ra6Bduy232Y.1:1006:1006:,,,:/home/yogibear:/bin/bash
papabear:$1$JN9btUA/$Kgpzv46b8qyIXsVlTn5r80:1007:1007:,,,:/home/papabear:/bin/bash
grizzlybear:$1$dg7RXQr2$vnDsFAeTQWpX8IjlRwRwn/:1008:1008:,,,:/home/grizzlybear:/bin/bashsisterbear:$6$Lti1Rz7aG5Gcxu0Y$fk7lAYOj5.20YOP09yYOHj0OLlTmyuzUleQVy4hPBpq5Z6oICK2UGUbP5ivqTIKqJrDLuAygY8qBbcgj.WMfn/:1009:1009:,,,:/home/sisterbear:/bin/bash

teddybear:$6$SbzNgpi0kwc6H5Ef$UiJgTJlbPwwdlXLMQfzk.9bKVQoZn2s2smtk3AaquFSi.NvP.pzYYANMI01MAYlqkhJn5Kz641TcshG.MKInJ1:1010:1010:,,,:/home/teddybear:/bin/bash
polarbear:$6$WSJr4aFmq/9ixL8i$weRpnHG7aJQCuAFamztfuuLC8nP2jwtskHG9lQkKiKV1WRBtefTWTRUiENCdkAQliu9hSD.5omg1XmQ8S9/sI0:1011:1011:,,,:/home/polarbear:/bin/bash
bluebear:$6$BpzsEOCQDs82hNgI$GYsF5y2JBuMgLwLRUP05xfcT6hKEz0KtPbUdWLjLR5P7SSXovsd7WWytwA9wfwIdpa3c5C0ddsHTl/LoULA6T/:1012:1012:,,,:/home/bluebear:/bin/bash
blackbear:$6$RDLDAwDXE63Dl9ZM$/FwOtEyYXFz3x4yUCMLdznUSUS9H4vSCMXM5VmSKW6xQFc/YQTm.t78pZ6Lf38fejGjNGB/ZlbUZqe8c0U9/K0:1013:1013:,,,:/home/blackbear:/bin/bash
mamabear:$6$x698r5uHaGfnqjwh$9qvV9kIUDuLbKWaXTxqXjZcUYZ/SyFQiQcKm/h7P2kVmQplzUIqeKLV8ekfFexfP4/cfOOMcfRX2Kgr1e/rvi.:1014:1014:,,,:/home/mamabear:/bin/bash
carebear:$6$sK1HOgwqf0BAaXkM$80Ui4xUs5MMrmPelNFXyXTtdgopPt1dHPAiv/W3FTmk9BqU1558haEWo5Zc5yjNWmdyNS4zTPsEOyGsyzNo0A/:1015:1015:,,,:/home/carebear:/bin/bash
cozybear:$6$qBsWj2EnnzAcrQDa$04O8mb7L5k2L0mpei0j4E1s/ifqoHX4nHybR/1m4QiG/usO8h18vWBE4fA7gFIZcnTWeLXPUJmLPOibvfdd.I1:1016:1016:,,,:/home/cozybear:/bin/bash
</pre>

* Absolutely no collaboration of any kind. This is an individual lab.
* Please be sure to keep records of your cracked passwords, including password pot, screenshots, and logs in case you are questioned.
* When you provide your cracked passwords, provide a very brief explanation on what you did (e.g., password cracker used, wordlist, etc.)
* You are allowed to use as many password crackers and word lists that you want and that you can find.  That is, you are not limited to using John the Ripper; you can use any other password cracker.
* Do not send the entire `crackme.txt` to a password cracker, it will confuse it because of multiple hash algorithms used.  Separate the list of hashes by hash algorithm; crack each list separately.
* You are allowed to use any infrastructure to crack the passwords (e.g., Amazon Web Services, as many graphic cards that you can afford). Please note that you are responsible for all costs.
* While you have unlimited submissions, be sure to also submit previously submitted passwords.
* You are strongly urged to submit early and often. Only last submission will count.
* The number of passwords to crack in order to get full points on this lab won't be announced until the final week of the competition.
* This contest will end on Friday, November 4th at 11:59 PM PDT.
* One last thing: if you crack all the password hashes (read: good luck with that), you will receive an automatic "A" in the course.