# MicroXfce
Simple repo containing my way of setting up Xfce on openSUSE tumbleweed

## So uh, how do i use it?
On a clean install of MicroOS with barely anything installed, do the following:

1. If you're not in root account right now then run `sudo su` first
2. execute the following:
```js
wget https://github.com/ddodogames/MicroXfce/raw/refs/heads/main/setupMicroOS-xfce.txt && transactional-update pkg in `cat setupMicroOS-xfce.txt`
```
3. type `y` to begin the installation
4. once it's done, run `systemctl set-default graphical.target` and then reboot the system

And voila! You should be greeted with Xfce desktop running!
