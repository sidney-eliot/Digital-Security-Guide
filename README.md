
# Introduction
A quick read, but somewhat complete guide to being seccure digitaly. Enjoy ...

# Table of Content
- [Network Level Security](#Network-Level-Security-)
- [Device Level Security](#Device-Level-Security-)
- [Account Level Security](#Account-Level-Security-)
- [Hunting For Possible Threats](#Hunting-For-Possible-Threats-)
- [Other Helpful Resources](#Other-helpful-resources)

# Network Level Security [^](#Table-of-Content)

### MAC Filters
Use mac whitelists to avoid unwanted devices getting into the network. (Note that this is simply a hurdle and can by bypassed)

### Guest Network
Create a separate guest network, so you can better monitor what goes on in the main network. This also helps putting in place stricter security measurements without annoying guests, or maybe stricter measures for guests.

### Password
Use a strong password, devices have remember network password so you won't have to enter the password often anyway. This in combo with guest network allows for you to have a very strong password for the normal network and one easier to type for the guest network. (Main: letter, number, symbol, >= 20 digits/ Guest: 3-5 word passphrase)

### Only LAN
If you mostly only use LAN maybe think about configuring the router to only use LAN, this makes it nearly impossible for the network to be infiltrated.

### WPA 3 personal vs WPA enterprise
WPA 3 is a protocol used for the user to login to a network. WPA 3 personal makes a network have one password for every user. WPA 3 enterprise uses a radio server to have a separate login password an username for every user.

### Hide Network SSID
Hiding the network SSID will make the network not appear when looking for networks and needs to be added by hand with the SSID. This is a double edges sword however, it make it harder for the average person to find the network but those who know what they're doing will still be able to find networks with hidden SSID . What makes this potentially dangerous is that those who find it will be very interested to try to penetrate the network, because it seems like a high value target that is trying to protect something. Not standing out of the crowd is most often the best.

# Device Level Security [^](#Table-of-Content)
### Updates
Always get newest updates of operation system and try to generally keep everything up to date.

### "On the hunt" Antivirus Software
This type antivirus software is always scanning the computer for threats and there should only be one of these in use at the same time. The one windows has built in is great, enough and I recommend it vs free antivirus software. However paid antivirus software could be a bit better.

### "On demand" Antivirus Software
This is software the user triggers either because he thinks its a good time to do it again or because the user notices something is strange. Here one of the best options is Malwarebytes. Windows also has a on demand scanner. However probably the best is [Tron](https://www.reddit.com/r/TronScript/wiki/downloads/) which is a combination of all of the best on demand virus scanner covered [here](https://www.youtube.com/watch?v=eVRKYftj-aA).


# Account Level Security [^](#Table-of-Content)
### Strong password
Use at least 16 digit password with a variety of symbols, numbers, letters and capitalized letters. Password managers make this allot easier, I recommend Bitwarden. It's also important to know which passwords are the most important. The number one most important password is the email account password followed by the recovery email account password another essential password is that for the password manager. Keep these passwords strong and maybe not digital as well keeping multiple backups of them.

### Use Two-Factor Authentication (2FA)
Or Two factor authentication is essential and makes leaked passwords not that much of a threat. The best 2FA options are 2FA apps followed by email followed by SMS. SMS is the least safe of these three because through social engineering the phone company can be tricked.


### Check URL/ Domain Name
- URL's can have letters flipped and be a complete clone of the real page. As well as different URL's the domain name can also be different.
- Use bookmarks instead of searching sites through google.

### Use Add Blocker
Use add blocker to avoid malicious pop ups and code injections. Maybe also disable java script but this will break some website java script features

# Hunting For Possible Threats [^](#Table-of-Content)
- Use task manager (Process tab, Performance tab and Details tab)
- Check windows logs
- Use "On demand" Antivirus Software
- Turn off network
- Restart PC (malicious threats can put things in auto start, so this could do more harm than good)
- Instead of booting normally booting into safe boot is often good (needs windows safe boot options configured correctly)
- Booting into another OS on another drive connected to the pc, and from there removing the threat on the windows system

# Other Helpful Resources [^](#Table-of-Content)
Definitly worth checking out, also has some stuff not covered here relating browsing safely and email clients

- https://www.makeuseof.com/online-browsing-security-advice/
- https://www.makeuseof.com/tag/online-security-tips/
