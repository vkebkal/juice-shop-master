# OWASP Juice Shop – Hacking Challenges

This directory contains writeups and walkthroughs for selected hacking challenges from the [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/). These challenges demonstrate common web application vulnerabilities in a safe, educational environment.

---

## 📑 Table of Contents
1. [Project Description](#project-description)  
2. [🚀 Getting Started](#-getting-started)  
3. [📂 Challenges](#-challenges)
4. [⚠️ Disclaimer](#️-disclaimer)  
---

## Project Description

This repository contains solutions to hacking challenges performed on the OWASP Juice Shop, a deliberately insecure web application designed for security training. The purpose of this project is purely educational and aims to demonstrate common web security vulnerabilities and their exploitation methods.


## 🚀 Getting Started

All challenges assume:
- Using Juice Shop locally at `http://localhost:3000`
- Using tools like Burp Suite, a browser with DevTools, and optionally `sqlmap`.

---

## 📂 Challenges

| Challenge | Description | Difficulty | Link |
|----------|-------------|------------|------|
| Extra Language | Discover and access a hidden language file via brute-force and language code analysis. | ⭐⭐⭐⭐⭐ | [View](./challenges/REAMDE-extra-language.md) |
| Christmas Special | Use SQL Injection to find and add a hidden "Christmas Special" product to your basket. | ⭐⭐⭐⭐ | [View](./challenges/REAMDE-christmas-challenge.md) |
| Change Bender’s Password | Reset the password of a user account without SQL Injection or Forgot Password function. | ⭐⭐⭐⭐⭐ | [View](./challenges/REAMDE-change-benders-password.md) |

---
## Disclaimer

This repository and all contained material are for **educational purposes only**. No real persons or data were harmed or used. Do **not** apply these techniques outside of authorized, legal contexts.
