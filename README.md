# NETWORKWALKS-MOSES-MAKUNGU-WK3-PM1-CYBERSECURITY-PASSWORD-CRACKING-AND-HASHING

# PASSWORD SECURITY & HASH ANALYSIS LABS
### JOHN THE RIPPER (JTR) • JOHNNY GUI • NETWORKWALKS SECURITY TOOLS

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Cybersecurity-red?style=for-the-badge&logo=hackaday&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tool-John%20the%20Ripper-black?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Interface-Johnny%20GUI-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Platform-Kali%20Linux-orange?style=for-the-badge&logo=kalilinux&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---

## 1. PROJECT OVERVIEW

This repository documents practical exercises in password security assessment, hash extraction, and password recovery using John the Ripper (JTR), Johnny GUI, and Networkwalks online security tools.

The exercises focused on examining password-protected PDF documents, extracting their corresponding password hashes, and performing dictionary-based password attacks to evaluate password security.

The practical sessions provided hands-on exposure to password auditing techniques commonly used in ethical hacking and penetration testing.

**Training Area:** Cybersecurity & Ethical Hacking  
**Training Platform:** Networkwalks  
**Primary Focus:** Password Cracking and Hash Analysis

## 2. LAB ACTIVITIES & TOOLS

The practical work was divided into two main modules, each demonstrating a different approach to password hash extraction and recovery.

| Module | Practical Exercise | Tools / Platforms |
|---|---|---|
| Module 01 | PDF Password Hash Extraction and Cracking | John the Ripper, Johnny GUI, pdf2john |
| Module 02 | Online Hash Analysis and Password Recovery | Networkwalks Hash Calculator, Password Cracker |

## 3. MODULE 01 — JOHN THE RIPPER & JOHNNY GUI

### Objective

To extract password hashes from protected PDF documents and use John the Ripper to perform password recovery through dictionary-based testing.

### Practical Implementation

1. Identified the password-protected PDF sample provided for the exercise.
2. Used `pdf2john` to extract the password hash from the PDF document.
3. Saved the extracted hash in a text file for processing.
4. Imported the hash into Johnny, the graphical interface for John the Ripper.
5. Configured the password-testing process using an available wordlist.
6. Initiated the dictionary attack and monitored the results.
7. Verified the recovered password by opening the protected PDF document.

### Tools Used

- John the Ripper (JTR)
- Johnny GUI
- pdf2john
- Wordlists

## 4. MODULE 02 — NETWORKWALKS HASH ANALYSIS TOOLS

### Objective

To explore browser-based password hash extraction and recovery using the Networkwalks Hash Calculator and Password Cracker tools.

### Practical Implementation

1. Accessed the Networkwalks Hash Calculator.
2. Submitted the protected PDF sample for hash extraction.
3. Obtained the generated PDF password hash.
4. Transferred the extracted hash to the Networkwalks Password Cracker.
5. Initiated a dictionary-based password recovery attempt.
6. Reviewed the output and confirmed the recovered password by unlocking the sample document.

### Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Online wordlist-based password testing

## 5. TECHNICAL CONCEPTS EXPLORED

### Password Cracking

Password cracking involves testing possible password combinations against password hashes to identify a matching password. It is used in authorized security assessments to evaluate password strength.

### Password Hashing

Hashing transforms data into a fixed-length output using a mathematical hash function. In password security, hashes are used to verify passwords without storing the original plaintext password.

### Dictionary Attack

A dictionary attack uses a predefined collection of possible passwords, known as a wordlist, to test against a password hash.

### PDF Hash Extraction

PDF hash extraction involves obtaining the password-verification data from a protected PDF document so that an auditing tool can test candidate passwords against it.

## 6. PRACTICAL SCREENSHOTS & EVIDENCE

The following screenshots document the execution stages and results of the practical exercises.

### 6.1 — Extracting PDF Password Hashes Using Networkwalks

The first stage involved using the Networkwalks online tool to extract the password hash from the protected PDF sample.

![Networkwalks PDF Hash Extraction](https://github.com/user-attachments/assets/ffe3ce8c-9ad8-4612-abcd-523c70c9dbde)

### 6.2 — Alternative PDF Hash Extraction Method

An alternative browser-based tool was also explored to obtain the PDF password hash for further analysis.

![Alternative PDF Hash Extraction](https://github.com/user-attachments/assets/28fbf093-bec3-419f-a0cd-432d73848e12)

### 6.3 — Loading Extracted Hashes into John the Ripper

After extracting the hash, it was saved in a `.txt` file and imported into John the Ripper through Johnny GUI to configure a new password-testing session.

![Loading Hash into John the Ripper](https://github.com/user-attachments/assets/3b394a5e-9f5a-4a20-949f-ccb5b3568f0e)

### 6.4 — Password Recovery and Verification

The password-testing process was executed, and the recovered password was used to access the protected PDF document.

![Password Recovery](https://github.com/user-attachments/assets/c17ffd49-c65c-430b-98ff-bef836583995)

### 6.5 — Final Challenge Result

The final stage demonstrated successful completion of the password-cracking challenge and capture of the associated training flag.

![Successful Flag Capture](https://github.com/user-attachments/assets/9321fa7e-d1cf-4c13-bd83-06e6a72696fc)

## 7. SKILLS & KNOWLEDGE DEVELOPED

Through these practical exercises, I gained exposure to:

- Password security assessment.
- Password hash extraction.
- PDF password protection mechanisms.
- John the Ripper installation and usage.
- Johnny GUI configuration and operation.
- Dictionary-based password attacks.
- Wordlist utilization.
- Browser-based hash analysis tools.
- Password recovery and verification.
- Technical documentation and evidence collection.

## 8. KEY TAKEAWAYS

The exercises demonstrated how password hashes can be extracted from protected documents and assessed using password-auditing tools.

They also highlighted the importance of strong passwords, secure password-storage mechanisms, and the risks associated with weak or predictable password choices.

Practical exposure to both command-line and graphical password-auditing tools strengthened my understanding of password security testing.

## 9. CONCLUSION

These two practical modules provided valuable hands-on experience in password cracking and hash analysis using John the Ripper, Johnny GUI, and Networkwalks security tools.

The exercises strengthened my understanding of password hash extraction, dictionary attacks, and password recovery workflows within an ethical hacking laboratory environment.

This practical work forms part of my continuing cybersecurity training and development in penetration testing.

## 10. DISCLAIMER

All activities documented in this repository were performed for educational purposes using authorized training materials and laboratory exercises.

Password-auditing techniques should only be applied to files, systems, and accounts that you own or have explicit permission to assess.

---

## AUTHOR

**MOSES MAKANGU**  
Cybersecurity Trainee | IT Professional | Aspiring Penetration Tester

**Training Institution:** Networkwalks  
**GitHub:** [mosesmktech-alt](https://github.com/mosesmktech-alt)

<p align="center">
  <b>LEARN • ANALYZE • TEST • SECURE</b>
  <br/>
  <i>Developing practical cybersecurity skills through continuous learning and hands-on experience.</i>
</p>
