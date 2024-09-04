
slow ssd using sata to usb adapter problem

https://forums.raspberrypi.com/viewtopic.php?f=28&t=245931


edit `/boot/firmware/cmdline.txt`

add on the first line 

```
usb-storage.quirks=152d:0576:u
```


