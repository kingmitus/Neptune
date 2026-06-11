# Neptune Password Cracker

A dictionary-based password cracking tool built in Rust, designed for CTF competitions and security research.

## Features
- SHA256 and MD5 hash cracking
- Multithreaded cracking powered by Rayon
- Live progress bar
- Clean desktop GUI built with egui

## Usage
1. Paste a hash into the Hash field
2. Enter the path to your wordlist (rockyou.txt recommended)
3. Select the hash algorithm
4. Click Crack

## Download
Download the latest installer from the Releases page.

## Built With
- Rust
- egui / eframe — native GUI
- Rayon — data parallelism
- sha2 / md5 — hashing

## Learning Goals
This project was built as a way to learn Rust through a practical security tool. Key concepts covered:
- Ownership and borrowing
- Multithreading with Arc and Mutex
- GUI development with egui
- File I/O and iterator patterns
- Building and releasing a native Windows application

## Disclaimer
This tool is intended for educational purposes and authorized security testing only. Only use it against hashes you own or have permission to test.
