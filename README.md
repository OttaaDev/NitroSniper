[![Github](https://img.shields.io/badge/star_it_on-github-black?style=shield&logo=github)](https://github.com/OttaaDev)
[![BMC](https://img.shields.io/badge/buy_me_a-coffee-FFDD00?style=shield&logo=paypal)](paypal.me/MoneymeYsa)

###### The Nitro Sniper is against the ToS of Discord. I’m not responsible for that if you’re banned from using it.
---


<h3 align="center">Nitro Sniper Method</h3>
<p align="center">A lightweight, fast and efficient discord nitro sniper, giveaway sniper & invite sniper.</p
  
 
---
  
  
  
## Features 
  
- [x] Nitro, Giveaway & Invite Sniper
- [x] Customizable Webhook (Giveaways, Nitro, Invites) with customizable events (Invalid Code, Redeemeed Code, Joined Server)
- [x] Customizable Webhook mentions for fired events (pings @everyone, recommended to run in a private server)
- [x] 3 Modes - `main`, `alts`, `both`. Each mode describes what accounts will be used when the sniper starts.
  [...]
  
--- 
    
  
    
## What do I need for the nitro sniper ?
- A replit account : [Sign Up](https://replit.com/signup?from=landing) or [Log In](https://replit.com/login).
- To create a server on [Discord](https://discord.com/login).


## How to do it ?
- Create a new rpl and import the Github repo with the [link](https://github.com/slow/nitro-sniper)
- Click on the lock "Secrets"
  - In Key put : settings
  - In value put the [Config Code](https://github.com/slow/nitro-sniper/wiki/Default-Configuration)

Don't forget to put your main token between the '. (in the config code)

###### Command for have the console : CTRL + SHIFT + I. 
###### Script for have his [token](https://ghostbin.com/atJ0a)

- Create a server on Discord. 
  - Create a webhook
    - Copy the webhook's link and paste it in your config code between the '. (webhooks'settings)
  

**When all this is finish. Don’t forget to "save" your secret.**

We are good. Now click on "Console" and Run your rpl.

If you dont have the message : "You're bot is alive"

Following that : 
  
```
Open /src/lib/Dashboard.js. The line 12 is commented ( // ). Just remove those two slashes ( "/" ). and run your bot.
Example :  // this.start();  to this.start();
```
  

--- 
  
## Run locally the Nitro Sniper on your PC
  
---
  
## What do I need ?
- Node.js
  - #### [Windows ![windows](https://media.discordapp.net/attachments/810799100940255260/838488668816932965/ezgif-6-ac9683508192.png)](https://nodejs.org/dist/v16.10.0/node-v16.10.0-x64.msi)
  - #### [macOS ![mac](https://media.discordapp.net/attachments/810799100940255260/838489488505307176/ezgif-6-cea52c6e0dcc.png)](https://nodejs.org/dist/v16.10.0/node-v16.10.0.pkg)

- Git
  - #### [Windows ![windows](https://media.discordapp.net/attachments/810799100940255260/838488668816932965/ezgif-6-ac9683508192.png)](https://git-scm.com/download/win)
  - #### [macOS ![mac](https://media.discordapp.net/attachments/810799100940255260/838489488505307176/ezgif-6-cea52c6e0dcc.png)](https://git-scm.com/download/mac)
  
- Python
  - #### [Windows ![windows](https://media.discordapp.net/attachments/810799100940255260/838488668816932965/ezgif-6-ac9683508192.png)](https://www.python.org/downloads/release/python-397/)
  - #### [macOS ![mac](https://media.discordapp.net/attachments/810799100940255260/838489488505307176/ezgif-6-cea52c6e0dcc.png)](https://www.python.org/downloads/release/python-397/)
  

When you finish installing these 3 applications, [download Anon Files](https://anonfiles.com/j7cf33H0uc/Nitro_Sniper_Working_7z) and unzip/unpack it with : 
  - #### [WinRAR ![windows](https://media.discordapp.net/attachments/810799100940255260/838488668816932965/ezgif-6-ac9683508192.png)](https://www.win-rar.com/fileadmin/winrar-versions/winrar/winrar-x64-602.exe)
  - #### [WinRAR ![mac](https://media.discordapp.net/attachments/810799100940255260/838489488505307176/ezgif-6-cea52c6e0dcc.png)](https://www.win-rar.com/fileadmin/winrar-versions/rarlinux-x64-6.0.2.tar.gz)
  
**or :**
  - #### [7zip   ![windows](https://media.discordapp.net/attachments/810799100940255260/838488668816932965/ezgif-6-ac9683508192.png)](https://www.7-zip.org/a/7z1900-x64.msi)

## How to do it ?

When all this is done.
  - Open the "nitro-sniper" folder.
    - Right click in the foler and open the "git bash" terminal.

In the "git bash" terminal
  - Type "npm install"

When that is finish.
  - Right click the .env file and edit it.

Any ide or text editor will work
  
  Look for these :
  
``` 
{
   tokens: {
      // Main Token (ex: Nz...)
      main: 'PLACE TOKEN HERE',
      // Alt Tokens (ex: Nz...)
      alts: [
         'PLACE ALT TOKEN',
      ],
   },
 
AND
 
 webhook: {
      // URL to fire webhook to for notifications (ex: https://discord.com/api/webhooks/.../...)
      url: 'PLACE WEBHOOK HERE',
      enabled: {
```
  
Make replacements if necessary.
  
Go back to the "git bash" terminal. 
###### If closed, reopen in new one in "nitro-sniper" folder.
  
  - Run "node ." and watch it load.


**Do wihout Anon's files**
 
Make sure Node v14+ is installed on your system and open a command prompt/terminal.
  
```
Run "git clone https://github.com/slow/nitro-sniper nitro-sniper"
Run "cd nitro-sniper"
Run "npm install"
Edit the .env file.
Run "node ."
```

---
  
## Tips 

###### Some information to help you have more chance with your [Nitro-Sniper](https://github.com/OttaaDev/NitroSniper).
  
  - Add and Use a lot of alts account.
  - Use a [Outlook adress](https://signup.live.com/signup?mkt=fr-FR&wreply=https%3a%2f%2foffice.live.com%2fstart%2fOutlook.aspx%3fui%3dfr-FR%26s%3d2%26auth%3d1%26nf%3d1&wa=wsignin1.0&lw=1&id=257526&uaid=09530f5421c94f24b634dab024e51b52&lic=1) for create others discord accounts.
  - Join many servers, find in [here](https://disboard.org/search). More servers mean more chances. 
  - Use an [uptimer](https://uptimerobot.com/) for have a [Nitro-Sniper](https://github.com/DirOtta/NitroSniperMethod) 24/7.
  
  
--- 

## Support them 
- You can support [**slow**](https://github.com/slow). He is the author of the [Nitro-Sniper](https://github.com/slow/nitro-sniper).
  - Slow [discord](https://discord.gg/HQ5N7Rcajc).
- You can support **Anon**. He is the author of the [Locally Sniper](https://pastebin.com/J4tuffyE).
- You can suppport [**LAW**](https://lawyt.sellix.io/). He is the author of [the video](https://youtu.be/D64WcTLpzes) about the Nitro-Sniper. 
   - Found **Anon and LAW** [here](https://discord.com/invite/gmtqE4ScJB).
     
---
  
## Still need help, or just want to chat ?
  
[Contact](https://github.com/OttaaDev) me or join [LAW's Discord](https://discord.com/invite/gmtqE4ScJB) server.
