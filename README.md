# Pegasus Ransomware

**Author**: Letda Kes dr. Muhammad Sobri Maulana, S.Kom, CEH, OSCP, OSCE

## Description

Pegasus Ransomware is a sophisticated and highly destructive malware designed to encrypt victims' files and demand a ransom for their decryption. This ransomware employs strong encryption techniques and various security measures to ensure the files remain inaccessible without paying the ransom.

## Features

- **RSA-2048 Encryption**: Utilizes strong RSA-2048 bit encryption to secure files.
- **Self-Signed Certificate**: Generates a self-signed certificate to enhance the security of the encryption process.
- **Base64 Encoding**: Encodes the certificate in Base64 format for easy transmission and storage.
- **Password Generation**: Automatically generates strong passwords for various encryption and compression tasks.
- **File Compression and Encryption**: Compresses and encrypts files using 7-Zip with a robust password.
- **Email Communication**: Sends encrypted files and passwords via email to a specified address.
- **File Stealing and Encryption**: Copies targeted files from specified directories, encrypts them, and prepares them for exfiltration.
- **Google Drive Upload**: Uploads stolen and encrypted files to Google Drive using OAuth2 for secure authentication and file transfer.
- **User Interface and Notification**: Displays a ransom note with instructions for the victim and provides payment details.
- **Background and Wallpaper Changes**: Changes the desktop wallpaper to alert the user about the ransomware attack and displays a countdown timer.

## Ransom Demand

The ransomware demands a payment of 0.10 BTC to a specified Bitcoin address. The ransom note warns the victim not to turn off their computer and provides instructions on how to contact the attacker and make the payment. Failure to pay the ransom within the given time frame results in the permanent loss of the encrypted files.

## Usage

**Note**: This ransomware is intended for educational purposes and cybersecurity research only. Unauthorized use, distribution, or deployment of this ransomware is illegal and punishable by law. Always ensure you have proper authorization before conducting any cybersecurity activities.

### Steps

1. **Generate and Export Certificate**: Generates a self-signed certificate and exports it to the temp folder.
2. **Encode Certificate**: Base64 encodes the certificate for easy transmission.
3. **Generate Passwords**: Automatically generates strong passwords for encryption tasks.
4. **Compress and Encrypt Files**: Uses 7-Zip to compress and encrypt files.
5. **Send Encrypted Files via Email**: Sends the encrypted files and passwords to the specified email address.
6. **Steal and Encrypt Files**: Copies targeted files, encrypts them, and prepares them for exfiltration.
7. **Upload to Google Drive**: Uploads the stolen and encrypted files to Google Drive.
8. **Notify User**: Displays a ransom note and changes the desktop wallpaper.
9. **Delete Temporary Files**: Cleans up temporary files created during the process.

## Disclaimer

Pegasus Ransomware is a harmful and illegal software if used maliciously. It is designed for educational and research purposes only. Unauthorized use, distribution, or deployment of this ransomware is illegal and punishable by law. Always ensure you have proper authorization before conducting any cybersecurity activities.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Warning**: Use of this ransomware for malicious purposes is illegal and punishable by law. Always conduct cybersecurity activities responsibly and with proper authorization.
