<h1>Configuring a Wireless Network</h1>

<h2>Description</h2>
In order to pass my Comptia A+ exam I had to learn about the Networking Basics such as Wireless Networks. The A+ Exam covers multiple wireless Network topics such as Wireless Frequencies, Wireless Standards, Wireless Security, and etc. Today I will be configuring
a Wireless Network to use the proper secure settings. I am going to be doing things like MAC Filtering, Setting broadcast to disabled, and putting the wireless network at WPA2
<br />


<h2>Tools used </h2>

- <b>Standard  wireless Router, has a wireless access point and a switch built in. 4 ports +WAN connection  </b> 
- <b>Network Preface on MAC OS </b> 

<h2>Environments Used </h2>

- <b>Network Preferances on MAC OS</b> 

<h2>Step 1: Open Network Preferances on MAC settings</h2>
This shows me im connected directly over ethernet, directly to that wireless access point, bc it has 4 switch ports and I am plugged into one of them, my DHCP address was 192.168.1.1, For me to be able to configure this wireless access point im gonna go and type that 
router ip address into a web browser, bc most allow you to have a web navigation.

<h2>Step 2: Configure Wireless Settings</h2>
Disabling SSID Broadcast is such an important thing to do because with it on, your wireless access point is basically say "HEY! HEY! IM OVER HERE CONNECT TO ME MY NAME IS ....." The reason why is because I am using a wirless N router for this example,
Wireless N and wireless AC do support wireless isolation . This allows it to act more as a switch and less like a hub and thats what we'd like. We name the SSID, select the region, auto select the channel or select yourself, mode tell me how fast its gonna operate (150Mbps or 300 Mbps)

<h2>Step 3: Security Options</h2>
AM I going to have no security? Well if this was a Guest Network like we see at Starbucks, The Library, etc, I wouldnt need any. But if im setting this up for my home, im gonna need a password. Bc I dont want people coming in and connecting it and touching my other devices. For this type of connection specifically It only supports WPA and WPA2, why? bc WEP is ez to crack. It gives us an option of encryption from TKIP or AES or even both. Since I am operating in a home enviornment, the best thing for me is the easiest and most secure to use wich is WPA2 with an encryption through AES. I then chose a long and complex password so it lengthens the time it would take for someone to crack into it.

<h2>Step 4: Advanced Settings</h2>
Setup> Wireless> Guest network> Going into here allows me to have 2 types of networks, One for my personal and one for my guests that would come over to my house. I can do this by enabling Guest Network, SSID Broadcast, and Wireless Isolation, giving it name as "Friends-Guest", I'll leave the box "allow guest to accest my Local Network" Disabled. 

<h2>Step 5: MAC Filtering</h2>
Advanced>ADvanced Setup>Wireless Settings> Listed as "Wireless Card Access List". Setting up this access list I would be able to turn it on and only allow certain MAC addresses to be able to connect to this wireless network. The good thing is, this will keep out people that dont know im using that filtering, The Bad Thing, a hacker or attacker takes about 30 seconds to bypass MAC Filtering.

<h2>Step 6: WPS</h2>
WPS was something put on the router to make it easier for people to pair the access point and the router, they would share a pin together then connect each other securley to the network. In theory this is a great thing ,but unforunantly, it was easily hacked, so its something I do want to turn off for best security practices.

<h2>Step 7: Remote Management</h2>
This allows you to connect to the device remotely over the internet through this webbased graphical interface, If I turn Remote Management On, I can set an IP address, and allow anyone to connect to this device and make changes.
WHY WOULD I WANT TO DO THAT???? Well maybe u have to set this up for your mothers house, and shes not very technically savvy. But you would need to configure it to ONLY allow certain computers with CERTAIN IPs to connect to it.

<h2>Summary</h2>

- <b>Use WPA2 with a good, long, andstrong pre-shared key </b> 

- <b>Disable SSID broadcast</b>
  
- <b>Enable Wireless Isolation </b>
  
- <b>Enablke MAC Filtering </b>
 
- <b>Disable WPS Settings </b> 

THANKS FOR READING !! Happy testing !
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
