\---

title: "Hack The Box: Trickster Machine Walkthrough"

date: 2026-03-17

tags: \["htb", "ctf", "walkthrough", "linux"]

draft: false

\---



\## Machine Information



Trickster is an easy-difficulty Linux machine on Hack The Box.



\### Reconnaissance



First, let's scan the target with nmap:



```bash

nmap -sC -sV -oA nmap/trickster 10.10.11.34

