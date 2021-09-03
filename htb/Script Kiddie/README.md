# ScriptKiddie

By using NMAP, it was observed that ports 22 (SHH) and 5000 (were open).

On browsing 10.10.10.226:5000, a hacking website was presented. 

The vulnerability was found by exploiting a reverse webshell using an uploaded android APK. 

By gaining access into kid@ we we're able to find another user. 

We used another reverse shell to gain access. 

By seeing sudo access in the new user, it was found that msfconconsole had root access without a password.

once sudo in msfconsole, we could get the root.txt 

