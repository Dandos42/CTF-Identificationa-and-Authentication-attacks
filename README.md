# CTF-Identification & Authentication attacks
The project serves as an interactive scenario for the BUTCA platform, with the goal of providing a practical demonstration of vulnerabilities and attacks related to identification and authentication.

## Description
The player takes on the role of an independent security specialist hired by the CEO of the fictional company "Masters of the Skies." Sensitive information about air traffic has been leaked from the company, and suspicion has fallen on one of the employees.
The investigator’s task is to complete a series of eight interconnected missions (in the style of Capture the Flag), examine user accounts, crack passwords, and uncover the identity of the “mole” within the company, including evidence of their activities.

## Educational concept
This scenario provides hands-on practice with authentication attacks and demonstrates the consequences of failing to comply with security standards:
* Brute-force and dictionary attacks on passwords.
* Decoding text and searching for weak passwords (e.g., in the form of unencrypted files or cheat sheets on a desk).
* Exploitation of the password manager in a web browser.
* Information gathering using OSINT and social engineering methods (e.g., exploiting personal photos to reset a forgotten password).
* Intercepting and breaking the WPA2 4-Way Handshake on Wi-Fi networks.
* SQL injection vulnerabilities applied to the login process and user enumeration in the database.

## Tools and Technologies
* Virtualization software: VMware (or equivalent) for running virtual machines.
* Virtual machines: A specially prepared vulnerable PenterepMail server and an attacker machine running Kali Linux.
* Hardware: A physical Wi-Fi router/access point and a USB Wi-Fi network adapter (with monitor mode support) to simulate an attack on a wireless network.
* John the Ripper (+ zip2john), aircrack-ng

## Authors
Daniel Prachař, Dalibor Rada

## Virtual Environment (.ova)
To run this project correctly, you must download and import a custom-built virtual machine.
Due to Git repository limits (size over 2 GB), the file is stored on an external repository.

*   **Download link:** [Download the project .ova file here](https://drive.google.com/file/d/1UTKWSlDcAaoAEVmfiKahDHX9-gL9wlZx/view?usp=sharing)
*   **Instructions:** Open VirtualBox / VMware, select `File -> Import Appliance`, and choose the downloaded file.
