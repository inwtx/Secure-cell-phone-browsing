# Secure-cell-phone-browsing
Instructions on how to set up secure browsing on a cell phone with Firefox and ConnectBot.  
  
To prevent Google, your phone company, and any wifi location you use from spying on your web browsing, you need to connect to a personally owned server, an SSH service, a rented Virtual Private Server, or a Virtual Private Network.  Although there are some VPNs in the Google Play Store that are available for use with your phone, it is assumed that they are scraping information from your web browsing. 
  
This spying can be circumvented with the use of the android Firefox client and the ConnectBot SSH client.  As long as you can obtain your remote server's IP address and its SSH port (usually 22), then you can use these two apps to securely browse the internet anywhere. Firefox is currently the only browser that allows you to change its proxy settings, whereby you can connect to/through ConnectBot.   
  
  
<b><i>I. Download instructions:</i></b>
    
  
<b>A. Go to the Google Play Store, type Firefox in the search box, and download the Firefox browser and install it on your phone.  The one you want is outlined in the red box:</b> 
<p align="left">
  <img src="/images/scene1.png" width="360" height="217">
</p>
<br>
<b>B. Go again to the Google Play Store, type ConnectBot in the search box, and download ConnectBot and install it.</b>
<br><br>
<p align="left">
  <img src="/images/scene2.png" width="360" height="217">
</p>
<br>
<b><i>II. Firefox set up instructions:</i></b>
<br><br>
<b>A. Start Firefix and type <i>about:config</i> in the URL box. Then type <i>.proxy.</i> in the search box.</b>
<br><br>
<p align="left">
  <img src="/images/scene3.png" width="360" height="132">
</p>
<br>
<b>B. Go down the list that appears and find the the various fields and set then to those displayed below.</b>
<p align="left"><br><br>
  <img src="/images/scene4.png" width="360" height="1162">
</p>
<b>C. That is all that is needed for Firefox.</b>
<br><br><br>
<b><i>III. ConnectBot set up instructions:</i></b>
<br><br>
<b>A. Start ConnectBot and click on the plus sign at the bottom to set up a Host connection.</b>
<p align="left"><br><br>
  <img src="/images/scene5.png" width="360" height="317">
</p>
<br>
<b>B. In the top 'username@hostname:port' box, type in your username for the server, followed by an @ sign, followed by your server's IP address, followed by a semicolon (:), followed by your server's connection port (usually 22).<br>
Example: william@204.45.80.117:22<br>
You can check the parameters out by clicking the down button in the square orange box.<br>
<br>
Continuing down the 'Edit Host' connection entries page:<br>
Tap on and set 'Nickname' to anything (or to the same as your above 'username@hostname:port' for clarity).<br>
Set 'Use pubkey authentication' to 'Use any unlocked key'.<br>
Set 'DEL Key' to 'Delete'.<br>
Turn on all switches to right ('Start shell session' can be left off).<br>
Ignore 'Post-login automation'.<br>
<br>
Press the plus (+) in the upper right corner of the ConnectBot interface to save.</b><br>
<br>
<p align="left">
  <img src="/images/scene7.png" width="360" height="1326">
</p>
<br>
<b>C. This is what your new server will look like in ConnectBot after it has been created.</b><br>
<br>
<p align="left">
  <img src="/images/scene112.png" width="360" height="243">
</p>
<br>
<b>D. Now you need to set up Port Forwarding for your new Host for ConnectBot to correctly connect.<br>
Tap and hold down on your new server Host line until a menu pops up and tap on 'Edit port forwards'.</b><br>
<br>
<p align="left">
  <img src="/images/scene8.png" width="360" height="473">
</p>
<br>
<b>E. Then click on the round plus (+) button.</b><br>
<br>
<p align="left">
  <img src="/images/scene9.png" width="360" height="269">
</p>
<br>
<b>F. Then enter anything for the Nickname.</b><br>
<b>Click on the down arrow (orange box) and select 'Dynamic (SOCKS)'.</b><br>
<b>For Source port, enter 9500.</b><br>
<b>Click 'CHANGE' and your finished.</b><br>
<br>
<p align="left">
  <img src="/images/scene11.png" width="360" height="537">
</p>
<br>
<b>G. To connect to your server, simply tap on the server name in ConnectBot (as seen in C. above).</b><br>
<b>You should be taken to a page that request your Password.</b><br>
<b>Use Firefox to test that your connection is actually going to your server by using an IP test site:<br>
https://whatismyipaddress.com/<br>
https://ipleak.net/<br><br>
If you are shown any IP address other than the IP address you used in your Host set up, you are not going through your Host. 
Recheck your set up parameters and try again.<br>
