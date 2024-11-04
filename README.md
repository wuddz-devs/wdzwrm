<h1 align="center">WDZWRM</h1>

## Description
 - WDZWRM Is A LightWeight, Memory-Efficient & Ultra Fast Performing Cli Windows Remote Management Service Bruteforce App.
 - Upload/Download File To/From Remote Server Providing Local & Remote File Paths
 - Execute Command On Remote Server &OR Save Command Output To File (Default=Prints To Screen)
 - Execute Powershell Script Locally Hosted On Your Device On Remote Server
 - Can Make New Directory On Remote Server For Remote File To Be Transferred
 - Scan Using Password Or Ntlm Hash (32 characters)
 - Scan An Entire Network (e.g 1.1.1.0/24)
 - Check If Credential(s) Are valid (e.g "server:port@domain\\username;password")
 - Scan Using "user;password" | "user;ntlm_hash" combo(s) (e.g "admin;admin123", "dev;ab2d4912fc7132fb7165d79cffbc5db5")
 - Password Generator (e.g all perms, all upper & lower, all no repeat chars)
 - Grab Network Cidr Lists For All Datacenters Or Countries(2 letter cc) (e.g all | microsoft | us)
 - No Viruses, Can Be Run Using Guest Or Admin Account On Any Windows OS
 - Encrypt/Decrypt Hits With A Password (Can Only Be Decrypted With This Program)
 - Clean/Delete All Input Files (Total Stealth)
 - Password Protected Program So Even If Found Can't Be Used Without Password
 - Made By A Pentester For Pentesting &Or Network Administrator Purposes
 - Hit Me Up & Let Me Know, Serious Inquiries Only

## Prerequisites
 - Can Be Distributed As An Executable For Windows/Linux Or As A Package To Install With Python On The System.

### Usage
Scan Servers In 's.txt' For Valid User 'admin' & Password 'admin@123' Using 1000 threads
```
wrm.exe -s s.txt -u admin -p admin@123 -t 1000
```
Scan Servers In 's.txt' For Valid User 'admin' & NTLM_Hash '0bae622ab68138248c66d66882818dfd'
```
wrm.exe -s s.txt -u u.txt -hs 0bae622ab68138248c66d66882818dfd
```
Scan Servers In 's.txt' For Valid 'User;Password' Combos In 'combo.txt' & Type Password To Encrypt Valid Creds.
```
wrm.exe -s s.txt -up combo.txt -e
```
Scan Servers In Network 1.1.1.0/24 For Valid User 'user1' & Generated Password(s), Save Passwords To 'pwd.txt'
```
wrm.exe -nw 1.1.1.0/24 -u user1 -ps user -pt nrc -pe @123 -po pwd.txt
```
Save All CIDR Networks For USA In us.txt
```
wrm.exe -nc US -no us.txt
```
Scan Servers In 's.txt' For Users In 'u.txt' & Passwords In 'p.txt' & Stealthily Delete All 3 Input Files.
```
wrm.exe -s s.txt -u u.txt -p p.txt -clean
```

## Illustration Video:
...Pending....

## Contact Info:
 - Email:     wuddz_devs@protonmail.com
 - Github:    https://github.com/wuddz-devs
 - Telegram:  https://t.me/wuddz_devs
 - Youtube:   https://youtube.com/@wuddz-devs
 - Reddit:    https://reddit.com/user/wuddz-devs

### Buy Me A Coffee!!
![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/eth.png)
 - ERC20:    0xbF4d5309Bc633d95B6a8fe60E6AF490F11ed2Dd1

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/btc.png)
 - BTC:      bc1qa7ssx0e4l6lytqawrnceu6hf5990x4r2uwuead

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/ltc.png)
 - LTC:      LdbcFiQVUMTfc9eJdc5Gw2nZgyo6WjKCj7

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/doge.png)
 - DOGE:     DFwLwtcam7n2JreSpq1r2rtkA48Vos5Hgm

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-devs/main/assets/tron.png)
 - TRON:     TY6e3dWGpqyn2wUgnA5q63c88PJzfDmQAD

#### Enjoy my awesome creativity!!
#### Peace & Love Always!!
