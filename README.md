# Beginner Linux & Digital Forensics CTFs

A collection of introductory Capture The Flag (CTF) challenges designed for beginners. The goal of these challenges is to help players get comfortable with essential Linux terminal commands, file permissions, basic digital forensics, and fundamental algorithmic concepts.

---

##  What You Will Learn

By completing these challenges, players will practice:

* **File Management & Navigation:** `ls`, `cat`, `cd`, `tar -xzvf`
* **File Permissions & Execution:** `chmod +x`, executing binaries/scripts (`./script.sh`)
* **Digital Forensics:** Using `exiftool` to inspect image metadata and find hidden data
* **Basic Algorithms:** Applying **Binary Search** in the terminal to find flags efficiently

---

##  Challenges Overview

### Challenge 1: Digital Forensics — Team Image
* **Category:** Forensics
* **Description:** You are given our team's image file. Inspect the embedded EXIF metadata using command-line forensic tools to uncover the hidden flag.
* **Required Tools:** `exiftool`

### Challenge 2: Binary Search Efficiency
* **Category:** Algorithms / CLI
* **Description:** A challenge focused on searching efficiently using the command line. Instead of guessing sequentially, apply Binary Search logic to narrow down the correct target in as few steps as possible.

---

##  Getting Started

1. **Extract the challenge archive:**
   ```bash
   tar -xzvf myctfs.tar.gz
   cd myctfs
