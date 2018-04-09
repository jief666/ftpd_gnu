# ftpd_gnu
Original ftpd from Gnu, pulled from `inetutils-1.9.4.tar.xz`

## Usage
Functionality are untouched. See Gnu documentation.

## Getting Started
- Compile with xcode.
- Copy the sample `gftpd.plist` in `/Library/LaunchDaemons`. Adapt the path in `<Program>`.
- Do `sudo launchctl load -w /Library/LaunchDaemons/gftpd.plist`
-  **That's it !**

## Debug
I modified the server_mode function so it can be debugged under xcode. Program exit at the end of each connection, though.

## "Dropbox" version
If you're looking for a simple ftpd to act like a dropbox (probably for your network scan), see https://github.com/jief666/ftpd4scan

## Credits
Credit to all people who programmed. I didn't do much.
