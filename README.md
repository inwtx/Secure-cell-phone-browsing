# Secure-cell-phone-browser
Instructions on how to setup secure browsing on a cell phone with Firefox and ConnectBot.  
  
To prevent Google, your phone company, and any wifi location you use from spying on your web browsing, you need to use a personally owned server, an SSH service, a rented Virtual Private Server service, or a Virtual Private Network service.  Although there are some VPNs in the Google Play Store that are available for use with your phone, it is assumed to they are scraping information from your web browsing. 
  
This spying can be circumvented with the use of the android Firefox client and the SSH ConnectBot client.  As long as you can obtain the remote server's IP address and its web server port (usually 80), then you can use these two apps to securely brows the internet anywhere. Firefox is currently the only browser that allows you to change its proxy settings, whereby you can connect to/through ConnectBot.   
  
  
<b><i>I. Download instructions:</i></b>
    
  
<b>A. Go to the Google Play Store, type Firefox in the search box, and download the Firefox browser and install it.  The one you want is outlined in the red box:</b> 
<p align="left">
  <img src="/images/scene1.png" width="720" height="434">
</p>
<br>
<b>B. Go again to the Google Play Store, type ConnectBot in the search box, and download ConnectBot and install it.</b>
<br><br>
<p align="left">
  <img src="/images/scene2.png" width="720" height="434">
</p>

<b><i>II. Firefox setup instructions:</i></b>
<br><br>
<b>A. Start Firefix and type about:config in the URL box. Then type .proxy. in the search box.</b>
<p align="left">
  <img src="/images/scene3.png" width="720" height="265">
</p>
<br>
<b>A. Go down and find the the various fields and set then to those displayed here.</b>
<p align="left"><br><br>
  <img src="/images/scene4.png" width="720" height="2324">
</p>
<b>B. That is all that is needed for Firefox. Close it for now.</b>
<br><br>
<b><i>III. ConnectBot setup instructions:</i></b>
<br><br>
<b>A. Start ConnectBot and click on the plus sign at the bottom to setup a connection.</b>
<p align="left"><br><br>
  <img src="/images/scene5.png" width="720" height="635">
</p>
<b>B. In the top 'username@hostname:port' box, type in your username for the server, followed by an @ sign, followed by your server's IP address, followed by a semicolon (:), followed by your server's connection port (usually 22).<br>
Example: william@204.45.80.117:80</b>
<p align="left"><br><br>
  <img src="/images/scene7.png" width="600" height="2653">
</p>
