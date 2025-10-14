## **picoCTF 2025 — Log Reconstruction (Forensics)**


**Category:** Forensics

**Date:** 11 October 2025

**Difficulty:** Beginner

## **Challenge Overview**

A server appears to be leaking pieces of a secret flag within its log files.
These fragments are scattered and sometimes repeated.
The goal is to reconstruct the complete flag by collecting and combining all fragments.


## **Stage 1 — File Verification**

Make sure the log file was downloaded successfully and verify its name and type:

              file server.log  


## **Stage 2 — Initial Inspection**

Check the beginning of the file to understand its format:

              head -n 30 server.log


This helps reveal whether the flag or its fragments appear in plain text, encoded, or hidden within log patterns.

## **Stage 3 — Searching for Fragments**

Search through the log file for text resembling the picoCTF pattern:

                grep -i "picoCTF" server.log


Using -i ensures the search is case-insensitive.
You might find multiple lines containing fragments of the flag.


## **Stage 4 — Reconstructing the Flag**

After identifying all fragments, organize and combine them in sequence to form the complete flag string.

Tip: Some fragments may repeat or appear partially truncated — double-check for missing pieces before finalizing.

                picoCTF{REDACTED}


