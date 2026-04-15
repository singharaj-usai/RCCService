# RCCService
actual working 2016 radical clout calculator system gameserver to make avatars and thumbnails from your favorite block game!!😎😎😎😎🤟🤟🤟🤟

# Whats RCCService?
Its a gameserver service from [roblox](https://www.roblox.com) to let you render avatars and place thumbnails for your revival projects, pretty much that. There is other uses for this but thats the most popular reason for this

# How to use

1. git clone or download this as zip
2. download hxd and search up rblx16.com (my domain that i used) to your revival's domain **MUST BE 10 CHAR DOMAIN**
3. change appsettings.xml baseurl to your domain, then patch it! Now profit!
4. I included the gameserver.txt file that we used, do not modify this file unless you know what you are doing
5. now use git bash or powershell in the RCCService folder and type `rccservice.exe -console -verbose` to start the service on your local computer.
6. also download soapui roblox edition from here, you need this if you want to make an avatar without doing setups: [https://www.mediafire.com/file/us37e18tl30njc9/SoapUI.exe/file](https://www.mediafire.com/file/us37e18tl30njc9/SoapUI.exe/file)
- with soapui downloaded and open, use that headshot render script lua. Change base URL to your 10 character domain. Change SOAP Action to OpenJobEx. Press Load Script and select the headshot.lua. Then press Execute. 
- Now look at your command prompt and wait until very long texts in blue show up, that is your base64. If it shows up, that means your avatar successfully rendered.
- Go to this [link](https://base64.guru/converter/decode/image), copy and paste that base64 string into this website. You can now see your avatar headshot that was generated!

7. To get this to work on a revival website of yours, you're on your own, it's hard to explain. People like to gatekeep information on how to do this stuff. I have found out how to do it but it involves a ton of setting up, my method was to have the RCCService gameserver be hosted on Azure virtual machine, and have the website hosted on render.com. Since RCCService is a Windows service, it cannot run on Linux servers so Azure VPS worked for me. You're gonna have to know actual coding to get this to work on a real revival project, so good luck. Most people you find on Discord and Reddit are not gonna help because they're all 15 year olds who gatekeep knowledge. One day I might do a guide on how to do this because these gatekeeprs are weird.

# Credit

me (mrbobbilly)
Add me on Discord at mrbobbilly if you have questions or would like to collab on a revival project