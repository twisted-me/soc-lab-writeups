# Day 1: Home Lab Setup (VirtualBox + Kali Linux)

**Date:** 01 October 2026
**Time spent:** 2 hours
**Goal:** Build a safe, isolated lab environment for practicing cybersecurity skills.

## Scenario
Before doing any hands-on security work, I needed a lab where I can practice and break things without risking my main computer.

## Tools Used
- Oracle VirtualBox
- Kali Linux 
- Host machine: Windows 11

## What I Did
1. Installed VirtualBox on my host machine.
2. Downloaded the official Kali Linux VM image from kali.org.
3. Created and configured the VM (allocated 2 GB RAM, 2 CPU cores, and standard disk size).
4. Booted Kali and confirmed it runs correctly.
5. Took a **clean snapshot** named `Day-1-Baseline` so I can restore the lab if something breaks.
6. Created this GitHub repository to document my learning.

## Challenges and Fixes
- No major issues. Setup was smooth.

## Key Takeaways
- A snapshot lets me roll back to a known-good state after any experiment.
- Isolating my practice environment in a VM protects my main system.
- 
## Lab Screenshot
- <img width="1920" height="1080" alt="Screenshot (1315)" src="https://github.com/user-attachments/assets/57de0e48-60ef-40af-b6da-c8e85f0311ce" />

## Next Steps
- Day 2: TryHackMe Linux Fundamentals (Parts 1-3) and OverTheWire Bandit levels 0-5.
