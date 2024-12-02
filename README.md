# suictl
Server Usage Information Contol


### Upload server

### Grant execution permission
```
[mitw@d2 sw] chmod +x ./suictl
```

### Run suictl 
```
[mitw@d2 sw]# ./suictl

───────────────────────────────────────────────────────────────
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                  Server Usage Information                   ┃
┖─────────────────────────────────────────────────────────────┚
  [Memory]
  - Memory Usage : (26230M/48101M) 54.5%
  [CPU]
  - CPU Usage : 2.0%
  [DISK]
  - /dev/sda3 Usage : (615G/921G) 67% (Mounted On : /)
  - /dev/sda1 Usage : (249M/2.0G) 13% (Mounted On : /boot)
───────────────────────────────────────────────────────────────
     Dear Server, don't collapse! Hang in there bravely!

```

### Help suictl 
```
[mitw@d2 sw]# suictl -h
Usage: suictl [options]
Options:
  -s <seconds>   Refresh interval in seconds (default: 1)
  -t <seconds>   Total runtime in seconds (default: run once)
  -h             Show this help message
Comment:
  CC0 License, By mitw.tistory.com.
```

Good Luck!
