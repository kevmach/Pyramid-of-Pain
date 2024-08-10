# Pyramid-of-Pain

I am a level one security operations center (SOC) analyst at a financial services company. I received an alert about a suspicious file being downloaded on an employee's computer.

Upon investigating the alert, I discovered that the employee had received an email containing an attachment. The attachment was a password-protected spreadsheet file, and the password was provided in the email. The employee downloaded the file and entered the password to open it. Unfortunately, when the file was opened, a malicious payload was executed on their computer.

I retrieved the malicious file and created a SHA256 hash of the file. I recall from a previous course that a hash function is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint.

Now that I have the file hash, I will use VirusTotal to uncover additional Indicators of Compromise (IoCs) associated with the file.
