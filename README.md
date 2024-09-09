<h4>WiFi Bands 📶⚡</h4>
<p>is the frequency ranges used for wireless communication. The two main Wi-Fi bands are 2.4 GHz and 5 GHz. </p>

<p>2.4 GHz has Wider coverage, better at penetrating walls and obstacles. But it has slower speeds and more interference (due to crowding from other devices like microwaves, Bluetooth). </p>
<p>5 GHz has faster speeds and less interference, ideal for high-bandwidth activities like gaming or streaming. But it has shorter range, weaker at penetrating walls.</p>

<br />
__________________________________________________________________________________________________________________________
<br />

<img src="https://github.com/user-attachments/assets/60497d4a-f0fd-4fd2-b23d-cbc324f911f5" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/420483ab-2057-4585-9048-87b5ab574145" height="80%" width="80%" />
<p> Using airodump-ng --band a wlan0 is used to capture and show information about nearby WiFi networks and devices on the 5 GHz "a" band.</p>
  <p>It uses the wlan0 interface in monitor mode to focus specifically on 5 GHz networks, filtering out 2.4 GHz networks.</p>

  
<br />
__________________________________________________________________________________________________________________________
<br />

<img src="https://github.com/user-attachments/assets/ba35bcce-ffdc-48bf-bf42-2b87e0d3d1d6" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/c69fc0d4-14cd-433b-a186-2d8706509d57" height="80%" width="80%" />
   
<p>  airodump-ng --band abg wlan0 captures and shows information about Wi-Fi networks and devices on 2.4 GHz (b/g) and 5 GHz (a). In this case, it targets:</p>
  <p>It uses the wlan0 interface in monitor mode to scan for networks specifically on 2.4 GHz and 5 GHz networks.</p>



