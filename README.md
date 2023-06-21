
# Introduction
A quick read, but somewhat complete guide to being seccure digitaly. Enjoy ...

# Table of Contents
- [Network Level Security](#Network-Level-Security-)
- [Server Level Security](#Server-Level-Security-)
- [Device Level Security](#Device-Level-Security-)
- [Browser Level Security](#Borwser-Level-Security-)
- [Account Level Security](#Account-Level-Security-)
- [Hunting For Possible Threats](#Hunting-For-Possible-Threats-)
- [Other Helpful Resources](#other-helpful-resources-)

# Network Level Security [^](#Table-of-Contents)

### MAC Filters
Use mac whitelists to avoid unwanted devices getting into the network. (Note that this is simply a hurdle and can by bypassed)

### Guest Network
Create a separate guest network, so you can better monitor what goes on in the main network. This also helps putting in place stricter security measurements without annoying guests, or maybe stricter measures for guests.

### Password
Use a strong password, devices have remember network password so you won't have to enter the password often anyway. This in combo with guest network allows for you to have a very strong password for the normal network and one easier to type for the guest network. (Main network password: letters, numbers, symbols, >= 20 digits/ Guest network password: 3-5 word passphrase)

### Only LAN
If you mostly only use LAN maybe think about configuring the router to only use LAN, this makes it nearly impossible for the network to be infiltrated.

### WPA 3 personal vs WPA enterprise
WPA 3 is a protocol used for the user to login to a network. WPA 3 personal makes a network have one password for every user. WPA 3 enterprise uses a radio server to have a separate login password an username for every user.

### Hide Network SSID
Hiding the network SSID will make the network not appear when looking for networks and needs to be added by hand with the SSID. This is a double edges sword however, it make it harder for the average person to find the network but those who know what they're doing will still be able to find networks with hidden SSIDs . What makes this potentially dangerous is that those who find it will be very interested to try to penetrate the network, because it seems like a high value target that is trying to protect something. Not standing out of the crowd is most often the best.
# Server Level Security [^](#Table-of-Contents)
# Device Level Security [^](#Table-of-Contents)
### Updates
Always get newest updates of operation system and try to generally keep everything up to date.

### "On the hunt" Antivirus Software
This type antivirus software is always scanning the computer for threats and there should only be one of these in use at the same time. The Windows built in antivirus great and I recommend using it instead of free antivirus software. However paid antivirus software could be a bit better.

### "On demand" Antivirus Software
This is software the user triggers either because one thinks it's a good time to do it again or because the user notices something is strange. One of the best on demand antivirus software is Malwarebytes. Windows also has an on demand scanner. However probably the best is [Tron](https://www.reddit.com/r/TronScript/wiki/downloads/), which is a combination of all of the best on demand virus scanners covered [here](https://www.youtube.com/watch?v=eVRKYftj-aA).

# Browser Level Security [^](#Table-of-Contents)

# Account Level Security [^](#Table-of-Contents)
### Strong password
Use at least 16 digit password with a variety of symbols, numbers, letters and capitalized letters. Password managers make this allot easier, I recommend Bitwarden. It's also important to know which passwords are the most important. The number one most important password is the email account password followed by the recovery email account password another essential password is that for the password manager. Keep these passwords strong and maybe not digital as well keeping multiple backups of them.

### Use Two-Factor Authentication (2FA)
Or Two factor authentication is essential and makes leaked passwords not that much of a threat. The best 2FA options are 2FA apps followed by email followed by SMS. SMS is the least safe of these three because through social engineering the phone company can be tricked.


### Check URL/ Domain Name
- URL's can have letters flipped and be a complete clone of the real page. As well as different URL's the domain name can also be different.
- Use bookmarks instead of searching sites through google.

### Use Add Blocker
Use add blocker to avoid malicious pop ups and code injections. Maybe also disable java script but this will break some website java script features

# Hunting For Possible Threats [^](#Table-of-Contents)
- Use task manager (Process tab, Performance tab and Details tab)
- Check windows logs
- Use "On demand" Antivirus Software (e.g. Malwarebytes)
- Turn off device network connection, or the router entirely so no other devices get infected
- Restart PC (malicious threats can put things in auto start, so this could do more harm than good)
- Instead of booting normally booting into safe boot is often good (needs windows safe boot option to be enabled prior)
- Booting into another OS on another drive connected to the pc, and from there removing the threat on the windows system

# Other Helpful Resources [^](#Table-of-Contents)
Definitly worth checking out, also has some stuff not covered here relating browsing safely and email clients

- https://www.makeuseof.com/online-browsing-security-advice/
- https://www.makeuseof.com/tag/online-security-tips/

# ⚠️In Progress
# Keeping Your Email Safe
Yes yes, one should have a strong password and 2FA on for ones email account. But bad things can happen even if people can't get into your email account. If anyone get's a hold of your email, has a bit of experience in scripting and some reason to harm you, they can easily create a bot that signs you up for thousands of accounts and news letters every minute, making your email acount unusable.

If this ever happens to you the motive for the attacker can be a couple of things. Firstly they maybe just want to mess with you, perhaps something you said online that they didn't like. Secondly it might be an attempt to discuise their actual plan, if they where to attack your PayPal account, you wouldn't see the warning email from PayPal because it would be buired by all the other emails. So if this attack happens to you, allways assume it's the latter. Time is of essense and you should act as quickly as possible, follow following steps in that order:
   1. Sign into your PayPal account and remove your bank payment method
   2. If it's a good time for calling and you have your bank account information at hand, call you bank. If not, skip this step. Tell them about what's happening. While waiting for them to put your call through continue with the next steps
   3. 
   4. Contact PayPal, Amazon, Your Bank and other important accounts of your's, saying that your email account is under attack. Use a different email account for contacting them
   5. At this point it should be time to figure out if the hacker has access to your email account (password + email). If not, then create yourself a new email account and start migrating your most important accounts to this new email. (This step can also be done earlier)

There is sadly no saving an account that has this attack happen to it, even if it stops for some days it might continue. This is because your email might be on a list that's being sold around by hackers.

To prevent this from happening, there are a couple of precausions you can take.
- Never share your email as plain text around, instead add spaces or do other creative things to your email. The way the bost work is that they serach the internet for strings with an @ symol in them. Another great way of sharing yourt email is via an image of your email, but with image to text AI this is also not to good of an option anymore
- If you recieve an email from a mailing list never subscibed to, simply delete it and don't click unsubscribe
- Use disposable emails for many of your accounts and only use your real email for bigger sites of companies you trust
- Try to stay away from subscribing to mailing lists with your email. If it's sites you trust then it's ok
