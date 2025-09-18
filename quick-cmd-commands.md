# ⚡ Quick CMD Commands

Core command-line tools for Windows IT troubleshooting.

## 🔍 Network
```cmd
ipconfig /all
ipconfig /flushdns                :: Clear DNS cache
ping 8.8.8.8
tracert google.com
netstat -an
route print
```

## ⚡ System
```cmd
systeminfo
tasklist
taskkill /PID 1234 /F
sfc /scannow                      :: Scan system files
chkdsk C: /f                      :: Disk check and repair
whoami
```

## 📝 Logs & Diagnostics
```cmd
eventvwr.msc                      :: Open Event Viewer GUI
wevtutil qe System /c:20 /f:text  :: Show last 20 System log events
```

## ⚡ Power Management
```cmd
shutdown /r /t 0                  :: Restart immediately
shutdown /s /t 0                  :: Shut down immediately
shutdown /l                       :: Log off current user
```
