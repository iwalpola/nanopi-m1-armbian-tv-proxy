On SD card,

1) copy modified script.bin to /boot/
2) copy modified modules file to /etc/modules
3) copy all files of /etc (wgetrc, /etc/profile.d,  /etc/apt) to nanopi to set proxy (https://codepoets.co.uk/2014/debian-http_proxy-setting/)
4) set date using command [sudo date --set="2 OCT 2006 18:00:00"]
5) set hardware clock to correct time by typpng [sudo hwclock -w], check using [sudo hwclock -r]
