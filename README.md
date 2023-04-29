# Clipboard Hijacking Proof of Concept

This page will demonstrate how an attacker can leverage the ClipboardEvent.clipboardData call to replace the text you copied with a string of their choice.

These sort of attacks wouldn't be picked up by security rules or software.

## Cryptowallets

PoC at - https://veeeetzzzz.github.io/clipboard-hijacking/

Attackers can replace a cryptocurrency addresses that you copy with their own wallet adddress. Copy and paste the address you see into any other text field on your machine. Did the addresses match?

This is why you should always double check the address you are sending to. It is not enough just to check the first few characters, you should check the first 6 and the last 6 at the bare minimum.

## Web browsers

Attackers could also get you to visit a phishing site, you would think your safe copying a link but consider if you would notice the difference between lol.com and IoI.com - they look the same on your screen but if you copy and paste them they take you to different sites. Some users will rely on "Paste and Go" which means they may not even realise what they've connected to until it's too late.

![image](https://user-images.githubusercontent.com/40268197/235326190-dd784676-9c86-4633-b448-353e4d4e4002.png)

## Command line

Suppose you're a programmer, you're copying and pasting code from StackOverflow. What happens if someone gets you to execute a malicious command? Credits to Gabriel Friedlander @ Wizer Training for this attack vector and inspiring me to write up this page.

[![YouTube video player](https://img.youtube.com/vi/LFXZqQL4vTY/0.jpg)](https://www.youtube.com/embed/LFXZqQL4vTY)
