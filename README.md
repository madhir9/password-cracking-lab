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

I uploaded the password-protected PDF to the **Networkwalks Hash Calculator**. The tool processed the file and generated a PDF hash beginning with `$pdf$`.

📸 **Screenshot:**

![PDF Hash](images/pdf-hash.png)

---

### 2. Cracking the Password

I copied the extracted hash and entered it into the **Networkwalks Password Cracker**. The tool attempted to recover the password from the hash.

📸 **Screenshot:**

![Password Cracker](images/password-cracker.png)

---

### 3. Using John the Ripper

I also used **John the Ripper** with **Johnny GUI** to perform the same password-recovery exercise. I saved the PDF hash in a text file and loaded it into Johnny before starting the attack.

📸 **Screenshot:**

![John the Ripper](images/johnny.png)

---

### 4. Opening the PDF

After the password was recovered, I entered it into the protected PDF and successfully opened the file.

📸 **Screenshot:**

![Unlocked PDF](images/unlocked-pdf.png)

