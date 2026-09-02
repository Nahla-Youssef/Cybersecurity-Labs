---
# Lab: Offensive Security intro
---

## Offensive Security: 
### is about thinking like an attacker to find weaknesses before real hackers do.

---

## First hacking tool, dirbuster:
### DirBuster: A tool used to discover hidden files and directories on a web server by brute-forcing common names from a wordlist.

```bash 
dirb http://fakebank.thm
```
<img width="800" height="600" alt="Screenshot 2026-09-02 at 3 04 24 AM" src="https://github.com/user-attachments/assets/be247804-c54c-4129-92a2-16852691a038" />

### Dirb found two URLs:
1. http://fakebank.thm/bank-transfer
2. http://fakebank.thm/images
   
---

### Add the following: /bank-transfer to the URL in the browser   
1. Use your account number 8881 and deposit $2000
2. After depositing, return to your account page and confirm the balance is now positive.

<img width="800" height="600" alt="Screenshot 2026-09-02 at 3 26 17 AM" src="https://github.com/user-attachments/assets/ce0794d1-e262-4ffe-9527-09e866e5be1b" />

### Press Deposit Money 

<img width="800" height="600" alt="Screenshot 2026-09-02 at 3 27 17 AM" src="https://github.com/user-attachments/assets/e445e244-327c-4f3d-b9a9-943f43db3aa9" />

---
