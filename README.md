# NETWORKWALKS-MOSES-MAKUNGU-WK3-PM1-CYBERSECURITY-PASSWORD-CRACKING-AND-HASHING
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Waqas%20Karim%20CCIE-C00000?style=flat-square" />
</p>

## PASSWORD CRACKING, HASHING & JOHN THE RIPPER (JTR)

### 1. Introduction

Password cracking and hashing are important concepts in cybersecurity and penetration testing. This practical exercise explores how passwords are protected through hashing and how security professionals use password-auditing tools to identify weak password practices.

### 2. Understanding Password Cracking

Password cracking is the process of testing possible password combinations to recover a password associated with a particular password hash.

In ethical hacking, password cracking is used to evaluate password strength and identify weaknesses in authentication systems.

**Common Password Cracking Techniques:**

- **Brute Force Attack:** Attempts different character combinations until a match is found.
- **Dictionary Attack:** Uses a predefined wordlist containing possible passwords.
- **Hybrid Attack:** Combines dictionary words with numbers, symbols, or other variations.
- **Rainbow Table Attack:** Uses precomputed tables to look up possible passwords from their hashes.

### 3. Understanding Password Hashing

Hashing is the process of converting input data, such as a password, into a fixed-length output using a mathematical algorithm called a hash function.

Unlike encryption, hashing is designed to be a one-way process, meaning the original password is not directly recoverable through decryption.

**Key Characteristics of Hashing:**

- Converts input data into a hash value.
- Produces a fixed-length output for a given algorithm.
- The same input produces the same hash when the algorithm and settings are unchanged.
- Small changes in input produce significantly different hash values.

**Common Hashing Algorithms:**

| Algorithm | Description |
|---|---|
| MD5 | Older 128-bit hash algorithm. |
| SHA-1 | Older 160-bit hash algorithm. |
| SHA-256 | Member of the SHA-2 family, producing a 256-bit hash. |
| bcrypt | Password-hashing algorithm designed to resist brute-force attacks. |
| Argon2 | Modern password-hashing algorithm designed to resist GPU-based attacks. |

**Note:** Secure password storage should use dedicated password-hashing algorithms such as Argon2id, bcrypt, or scrypt, rather than fast general-purpose hashes such as MD5 or SHA-256.

### 4. Introduction to John the Ripper (JTR)

John the Ripper is an open-source password security auditing and recovery tool used by cybersecurity professionals to identify weak passwords and evaluate password security.

It works by testing candidate passwords against supplied password hashes using different techniques, including dictionary attacks and brute-force methods.

**Key Features:**

- Password hash auditing.
- Dictionary-based password testing.
- Brute-force password testing.
- Wordlist-based password recovery.
- Support for multiple password hash formats.
- Password strength assessment.

### 5. Practical Commands

The following commands demonstrate basic John the Ripper operations in Kali Linux.

**Check John the Ripper version:**

```bash
john --version
```

**Display available options:**

```bash
john --help
```

**Run a dictionary attack against an authorized sample hash file:**

```bash
john --wordlist=/usr/share/wordlists/rockyou.txt hashes.txt
```

**Display recovered passwords:**

```bash
john --show hashes.txt
```

### 6. Practical Workflow

1. Obtain a sample password hash from an authorized laboratory environment.
2. Identify the hash format.
3. Prepare an appropriate wordlist.
4. Execute John the Ripper against the sample hash.
5. Monitor the password-auditing process.
6. Review the results and document findings.

### 7. Skills and Knowledge Acquired

Through this practical exercise, I developed an understanding of:

- Password security and authentication.
- Password hashing mechanisms.
- Differences between hashing and encryption.
- Common password-cracking methodologies.
- Dictionary-based password attacks.
- Wordlist utilization.
- John the Ripper installation and command-line operations.
- Password security auditing.

