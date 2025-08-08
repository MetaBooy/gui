# gui
```
sudo apt update && sudo apt upgrade -y
```
# Install XFCE Desktop Environment
```
sudo apt install xfce4 xfce4-goodies -y
```
# Install xRDP
```
sudo systemctl enable xrdp
sudo systemctl start xrdp
```
# Add xrdp to ssl-cert group
```
sudo adduser xrdp ssl-cert
```

#  Add a new user for GUI login
```
sudo adduser yourusername
```
# Then add the user to sudo group
```
sudo usermod -aG sudo yourusername
```
# Set XFCE as the default desktop for the new user

```
su - yourusername
```

### Create a file to start XFCE in RDP:

```
echo "startxfce4" > ~/.xsession
chmod +x ~/.xsession
````
# Then return to root:
```
exit
```

# Install a Lightweight Browser
```sudo apt install snapd -y
```
```
sudo apt install firefox-esr -y
```




