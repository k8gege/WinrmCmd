# WinrmCmd
WinrmCmd For Golang  (Winrm Remote Shell)
<br>
wiki: http://k8gege.org/Ladon/WinrmScan.html


### WinrmScan (Brute-Force 5985 Port)
```Bash
Ladon 192.168.1.8 WinrmScan
Ladon 192.168.1.8/24 WinrmScan
```

### Ladon WinrmExec
```Bash
Usage:
Ladon WinrmExec <Target> [Port] [Domain] [Username] [Password] <Command>
Default Port is 5985
Example:
Ladon WinrmExec 192.168.1.116 . k8gege K8test520!@# calc.exe
Ladon WinrmExec 192.168.1.116 80 . k8gege K8test520!@# calc.exe
Ladon WinrmExec 192.168.1.116 5985 . k8gege K8test520!@# calc.exe
```

### LadonGo WinrmCmd

```Bash
Ladon SshCmd host port user pass cmd
Ladon WinrmCmd host port user pass cmd
```

![image](http://k8gege.org/k8img/LadonGo/LnxSshWinrm.PNG)
