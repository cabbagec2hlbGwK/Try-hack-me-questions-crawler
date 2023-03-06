[![Pylint](https://github.com/cabbagec2hlbGwK/Try-hack-me-questions-crawler/actions/workflows/pylint.yml/badge.svg?branch=main)](https://github.com/cabbagec2hlbGwK/Try-hack-me-questions-crawler/actions/workflows/pylint.yml)
---
# Try-hack-me-questions-crawler
this is a small script for extracting data from try hack me room ,and compile a MD file

### Requirements 
  * selenium
  * bs4
  * Firefox
---

### setup 
 * change the file permission of "geckodriver" and "thmq2md.py"
  ```html
   chmod +x thmq2md.py geckodriver
  ```

### Usage 
```bash
thmq2md.py <url> <output file> [-raw"No color"]

Example
thmq2md.py 'https://www.tryhackme.com/room/vulnversity' './README.md'
```
---

# Sample 
```bash
thmq2md.py "https://www.tryhackme.com/room/linuxprivesc" "./readme.md" -raw
```
**output**
```markdown
#  Linux PrivEsc 

## Task 1  Deploy the Vulnerable Debian VM 
	1. **Deploy the machine and login to the "user" account using SSH.**
		*  answer here  
	2. **Run the "id" command. What is the result?**
		*  answer here  

<br>
## Task 2  Service Exploits 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 3  Weak File Permissions - Readable /etc/shadow 
	1. **What is the root user's password hash?**
		*  answer here  
	2. **What hashing algorithm was used to produce the root user's password hash?**
		*  answer here  
	3. **What is the root user's password?**
		*  answer here  

<br>
## Task 4  Weak File Permissions - Writable /etc/shadow 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 5  Weak File Permissions - Writable /etc/passwd 
	1. **Run the "id" command as the newroot user. What is the result?**
		*  answer here  

<br>
## Task 6  Sudo - Shell Escape Sequences 
	1. **How many programs is "user" allowed to run via sudo?**
		*  answer here  
	2. **One program on the list doesn't have a shell escape sequence on GTFOBins. Which is it?**
		*  answer here  
	3. **Consider how you might use this program with sudo to gain root privileges without a shell escape sequence.**
		*  answer here  

<br>
## Task 7  Sudo - Environment Variables 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 8  Cron Jobs - File Permissions 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 9  Cron Jobs - PATH Environment Variable 
	1. **What is the value of the PATH variable in /etc/crontab?**
		*  answer here  

<br>
## Task 10  Cron Jobs - Wildcards 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 11  SUID / SGID Executables - Known Exploits 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 12  SUID / SGID Executables - Shared Object Injection 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 13  SUID / SGID Executables - Environment Variables 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 14  SUID / SGID Executables - Abusing Shell Features (#1) 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 15  SUID / SGID Executables - Abusing Shell Features (#2) 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 16  Passwords & Keys - History Files 
	1. **What is the full mysql command the user executed?**
		*  answer here  

<br>
## Task 17  Passwords & Keys - Config Files 
	1. **What file did you find the root user's credentials in?**
		*  answer here  

<br>
## Task 18  Passwords & Keys - SSH Keys 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 19  NFS 
	1. **What is the name of the option that disables root squashing?**
		*  answer here  

<br>
## Task 20  Kernel Exploits 
	1. **Read and follow along with the above.**
		*  answer here  

<br>
## Task 21  Privilege Escalation Scripts 
	1. **Experiment with all three tools, running them with different options. Do all of them identify the techniques used in this room?**
		*  answer here  

<br>

```
