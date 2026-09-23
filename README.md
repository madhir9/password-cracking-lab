# 🔐 Password Cracking Lab

This is my **Week 3 project** for the Cybersecurity Program at **Networkwalks (Batch B083)**.

In this project, I learned the basics of password cracking using a password-protected PDF file in a controlled cybersecurity lab. I used Networkwalks tools and John the Ripper to extract a PDF hash and recover the password.

## 🎯 Objectives

The main objectives of this project were to:

* Understand how password cracking works
* Extract a hash from a protected PDF
* Use password-cracking tools
* Recover the PDF password
* Understand the importance of strong passwords

## 🛠️ Tools Used

* Networkwalks Hash Calculator
* Networkwalks Password Cracker
* John the Ripper
* Johnny GUI
* Windows 10

## ⚙️ Lab Process

### 1. Extracting the PDF Hash

I extracted the password hash from the protected PDF and loaded it into **Johnny**, the graphical interface for John the Ripper.

**Result:** Johnny recognized the hash as a PDF hash and displayed it in the password list, ready for the password-cracking process.

📸 **Screenshot:**

images/<img width="1366" height="733" alt="password 1" src="https://github.com/user-attachments/assets/18ea24d6-68bb-43d6-8fa9-639843b69bde" />

images/<img width="1366" height="731" alt="password 2" src="https://github.com/user-attachments/assets/1683c04d-473e-4ff8-93c5-e95b6f3fa662" />


---

### 2. Cracking the Password

I entered the extracted PDF hash into the **Networkwalks Password Cracker** and started the attack.

**Result:** The tool successfully recovered the PDF password:

```text
password1
```
The password was recovered after 91 attempts.

📸 Screenshot:

images/<img width="1364" height="702" alt="hash c" src="https://github.com/user-attachments/assets/45caf81a-74d7-4e90-9418-e6378010e9ca" />

images/<img width="1364" height="691" alt="hash 1" src="https://github.com/user-attachments/assets/17cfe0de-4dea-415a-8f4d-4272dcee171b" />

images/<img width="1366" height="768" alt="hash 2" src="https://github.com/user-attachments/assets/0291a513-74f3-480a-a994-cd02b7e32fd5" />
)

3. Opening the Protected PDF

I entered the recovered password into the protected PDF.

Result: The PDF opened successfully and displayed the Networkwalks Cyber Security Academy flag, confirming that the recovered password was correct and the lab was completed.

📸 Screenshot:

images/<img width="1362" height="768" alt="lock 1" src="https://github.com/user-attachments/assets/a54a66c3-d7ae-4064-b526-6bc9ade245f6" />

images/<img width="1355" height="733" alt="lock 2" src="https://github.com/user-attachments/assets/f5f15c54-221e-4a0b-974b-d9d9d6a1a01e" />

images/<img width="1329" height="730" alt="lock 3" src="https://github.com/user-attachments/assets/ac77fc1d-9135-4cfd-b345-47c1eb86bf99" />

## 🐞 Problems I Encountered & How I Solved Them

One problem I encountered was making sure the complete PDF hash was copied correctly.

I solved this by checking that the hash was in the correct `$pdf$` format before loading it into the password-cracking tools.

