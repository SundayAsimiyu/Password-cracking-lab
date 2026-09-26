## Week 3 – Password Cracking Labs

### Module 1: Cracking a Locked PDF with John the Ripper (JtR & Johnny)
**Objective:** Recover the password of a password-protected PDF.

**Tools:** John the Ripper (CLI), Johnny (GUI), onlinehashcrack.com PDF hash extractor

**Steps:**
1. Uploaded the locked PDF to onlinehashcrack.com's PDF hash extractor tool to generate the file's hash.
2. Saved the extracted hash as a `.txt` file.
3. Loaded the hash file into Johnny (the GUI front-end for JtR) on Windows.
4. Ran a crack session using JtR's cracking engine against the hash.
5. Successfully recovered the PDF password.

**Result:** Successfully decrypted the PDF — confirmed by the unlocked file's congratulatory message.

---

### Module 2: Cracking a Locked PDF with NetworkWalks Hash Calculator
**Objective:** Recover a PDF password using an alternate hash-cracking tool/workflow.

**Tool:** networkwalks.com hash calculator

**Steps:**
1. Extracted/generated the PDF's hash using the NetworkWalks hash calculator tool.
2. Ran the cracking process against the hash to recover the plaintext password.
3. Compared results and workflow against the JtR/Johnny method from Module 1.

**Result:** Successfully decrypted the PDF — confirmed by the unlocked file's congratulatory message.

**Key takeaway:** Cross-checking two different tools against the same problem reinforced that password cracking is often more about hash extraction and wordlist/method choice than any single "best" tool.
