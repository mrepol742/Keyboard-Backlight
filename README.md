# Automatically turn on keyboard backlight on startup in linux

## Steps

**First**
```
Copy the backligh.sh to /home/user/
```

**Second**
```
Make the backlight.sh executabble by opening the terminal and typing this:
chmod +x backlight.sh
```

**Third**
```
Open and edit the backlight.desktop, on line 4 'Exec=/home/mrepol742/backlight.sh' replace 'mrepol742' with your username.
```

**Forth**
```
Copy the backlight.desktop to /etc/xdg/autostart/
```

**DONE**

# Note
> it wont gonna work again if the keyboard is disconnected consider executing the backlight.sh or xmodmap -e 'add mod3 = Scroll_Lock' in terminal.  <br> 
> i will update this if i found a way to execute the backlight.sh whenever a new device attach <br>
> im also a linux whos also facing this kind of issue