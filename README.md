# gui
```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt install xfce4 xfce4-goodies -y
```

```
sudo systemctl enable xrdp
sudo systemctl start xrdp
```

```
sudo adduser xrdp ssl-cert
```

```

```
sudo adduser yourusername
```

```
sudo usermod -aG sudo yourusername
```
STEP 6: Set XFCE as the default desktop for the new user

```
su - yourusername
```

### Create a file to start XFCE in RDP:

```
echo "startxfce4" > ~/.xsession
chmod +x ~/.xsession
````
Then return to root:
```
exit
```

Install a Lightweight Browser
```sudo apt install snapd -y
```
```
sudo apt install firefox-esr -y
```




