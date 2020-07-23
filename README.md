## Roblox-Bot-creator
Create roblox.com bots, currently only creates accounts.

### Planning on being added
- Proxy support (To prevent the Captcha)
- Check if username is taken
- Star, Follow, Like (Generally control bots)

### What does it do?
The program opens a script-controlled browser that navigates to the roblox.com page, then it signs up.

### Error sources and bugs
- Captcha Confirmation (Begins popping up after you've tried a couple times with same IP/proxy)
- Username Taken (Not handled currently)


### How to use
Open python interpretter in main directory
```
>>> import BotController as bc
>>> bc.setupUser("kresten123", "password", "Male", "Aug", "7", "2002")
>>> bc.createUser()
```
