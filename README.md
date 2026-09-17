# streamQ.tv for Windows

**[Download the latest version](https://github.com/strongesim05-prog/streamq-tv-app/releases/latest)**

Windows 10 or later, 64-bit. Download the setup, double-click it, and it installs. There is
nothing else to install first, and it does not ask for an administrator password.

### If Windows shows a blue warning

Windows may say **"Windows protected your PC"** the first time you run the installer. Click
**More info**, then **Run anyway**.

This happens because the app is new, not because there is anything wrong with it. Windows
shows it for any application it has not seen many times before.

### Is this app signed?

Not yet. A code signing certificate proves who published a file and that it has not been
altered since, and streamQ.tv does not have one yet. That is why Windows shows the warning
above.

It does not mean anything has been found wrong with the app. Windows shows that warning for
any application it has not seen many times before.

Until a certificate is in place, every release publishes the **SHA-256** of its installer on
its release page. That covers the tampering half: if the number your computer calculates
matches the one published, the file you have is exactly the file that was built.

```powershell
Get-FileHash .\streamQ-Setup-7.1.3.exe -Algorithm SHA256
```

### Signing in

Use the username and password from your provider.

Trouble signing in? [streamq.tv](https://streamq.tv/)
