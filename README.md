# Silly Putty Incident Response Report
 
## Introduction

- Created a Incident Response Report for the facticious company xyz. 
- Malicious executable that was affecting the facticious company xyz was putty.
- The Incident Response Report focuses:
  - Executive Summary
  - Technical Summary
  - Malicious Files
  - Timeline of Attack
  - Static Analysis
  - Dynamic Analysis

## Thought Process

- Hash the malicious document to determine if any Threat Intelligence websites would detect if the hash is malicious or not.
- Perform Static Analysis using Floss to determine potential malicious strings.
- Use Pestudio(.txt code) to look at raw size, and virtual size to determine if the file was packed or not.
- Perform Dynmaic Analysis by running process monitor and wireshark.
- Filtering process monitoring Parent ID you want to determine if there are any child process.
- Wireshark will determine the DNSquereies were the CallBack is.
- Base 64 was determined by looking at powershell script and the encoded string.
- Decode String determine powershell script.

## What I Learned

- Base 64 encoding how to determine what it is.
- Base 64 Decoding.
- Floss to determine any malicious strings.
- pestudio for looking at .txt(raw size and virtual size to see if the malicious file is packed)
- hashing file and using threat intelligence website(Virtus Total).
- Using netcat.

## Mark

- Extra Curricular.
