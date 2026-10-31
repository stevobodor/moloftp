# Getting started with MoloFTP

The [official user guide](https://www.moloftp.com/guide.html) contains the full instructions. This page is a short introduction to the website edition.

## Install and activate

1. Purchase Molo through [moloftp.com](https://www.moloftp.com/).
2. Download the DMG using the link shown after payment or in your purchase email.
3. Open the DMG and drag Molo to Applications.
4. Launch Molo and activate it with the license key from your purchase.

Molo requires an Apple Silicon Mac running macOS 14 or later.

## Add a server

Choose **Add Server** and enter a name, protocol, host, username and password. An initial remote path is optional.

Choose the protocol your server supports:

| Protocol | Transport | Usual port |
| --- | --- | --- |
| FTP | Plain FTP | 21 |
| FTPS | FTP over TLS | 21 |
| SFTP | SSH | 22 |

Use the port provided by your server administrator if it differs. Passwords are stored in macOS Keychain. For SFTP, Molo remembers the server's host-key fingerprint and refuses the connection if that key changes.

## Transfer files

Click a saved server to connect. Drag local files onto the remote pane to upload, or drag remote files onto the local pane or Finder to download. You can also use the upload and download buttons.

When a file already exists, choose whether to replace it, keep both copies or skip it. Deleting a remote file is permanent; deleting a local file moves it to the Trash.

## Move from FileZilla

Open the **Import/Export** menu above the server list and choose **Import from FileZilla…**. Select your FileZilla site export. The same menu offers FileZilla export and Molo backup import/export.

The website edition automatically keeps a backup of saved server connections in iCloud Drive. Backup and export files can contain server passwords, so keep them private.

## Updates and help

The website edition checks for updates daily. You can also use **Molo → Check for Updates…**. License holders receive free updates within the 1.x line.

For troubleshooting, consult the [full guide](https://www.moloftp.com/guide.html#help). Send private support requests to **support@moloftp.com**.
