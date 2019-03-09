Proof of Concept Linux Ransomware 
=================================

This is a simple ransomware created for [BSides Ljubljana 0x7E3](https://0x7e3.bsidesljubljana.si/reversing-mobile-malware-abdullah-joseph/).

The idea is to prove that writing a blindly destructive piece of software is not only very simple, but can be achieved with less than 200 lines of code.

CTF questions are [here](QUESTIONS.md).

Feel free to post the write-up anywhere 

## Building & Usage (**DO NOT EXECUTE**)

```bash
$ clang randomware.c -o ~/randomware
$ strip --strip-all ~/randomware # Skip this step for easier analysis
$ sudo ~/randomware
```

## Disclaimer
This software was created purely for research purposes. 
