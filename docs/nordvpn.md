# Nordvpn


***Nordpvn is one big problem on Gnu/Linux***

### Fix on Login issue

To fix the problem on Norvpn not allowing you to login

First go on the link that i gives you
-Login
-Right Click on the continue button and copy link

Then type this command:

`nordvpn login --callback URL` 
  
  The URL is the one you copied
***DONT TYPE URL PASTE LINK THERE***

The link should start with "nordvpn://"


  ### Nordvpn WHOOPS
  ```
sudo systemctl start nordvpnd.socket && sudo systemctl enable nordvpnd.socket
sudo systemctl start nordvpnd.service && sudo systemctl enable nordvpnd.service
```
