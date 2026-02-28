⚠️ **This document contains explicit language** in regards to a list of our blocked words and moderation filters.
We advise against reading this list unless you're prepared for the content within. Read with caution.
This is to be used only for the purposes of understanding our policies and moderation.
No attempts should be made to bypass the filters, as these words, and attempts to bypass the blocks for them, is prohibited.

This wordlist is open-source and may be used by anyone for any server(s) without expectation of credit.
The wordlist is provided AS-IS and should not be used as a sole means of moderation. 

📅 **Last Updated: February 28, 2026**

## 🛡️ Discord Filters
We use Discord's AutoMod filters and have the "Insults & Slurs" and the "Sexual Content" filters activated.
These wordlists change and are controlled by Discord, we have no insight into them. These filters catch a significant majority of our blocked words.

## 🟡 Blocked For New Users
These are words which are specifically blocked for "new" users. Violations of this filter lead to a message being blocked, alongside a 60 second timeout.
We do not make publicly available the specific conditions required for someone to be considered a "new" user and for these filters to apply.

**Wordlist:**
```crypto, disboard.org, download google drive, drive download, *drive.google.com*, free nitro, google drive download, mediafire.com, mega.nz, nft, reddit.com, steam account, top.gg, web3```

Within this filter, we also block the following regex, Which we use to block non-Latin characters and copypasta spam.
```(?-i)([\u0180-\u02AF]|[\u0370-\u13FF]|[\u141D-\u1FFF]|[\u2070-\u214F]|[\u2400-\u245F]|[\u249C-\u24E9]|[\u2500-\u259F]|[\u2800-\u28FF]]|[\u2C00-\u2E7F]|[\u3100-\u31BF]|[\uA000-\uF8FF]|[\uFB00-\uFDFF]|[\u{10000}-\u{1D0FF}]|[\u{1D200}-\u{1EEFF}])```

## 🟠 Main Filter
This is our main wordlist which applies to all members and will result in a message being blocked from being sent in the server.

**Wordlist:**
```🍖🌈, 🎱🎀, 666, ass, asshole, bitch, boob, boobs, breasts, chriscreator, cocaine, comship, comshipper, cum, darkship, darkshipper, dick, dickhead, diddy, *drive.google.com*, drugs, dumbasses, esptein, extacy, extasy, fag, faggot, fuck off, fuck you, fucker, goon, gooned, gooner, gooning, greenflame, hazbin, helluva, heroin, hitler, horny, inbred, incel, incest, jesus fucking christ, jfc, joseph smith, kike, kill myself, kill yourself, loli, lolicon, meth, motherfucker, nga, nibba, nigga, ninjago media project, ouija, pedo, pedophile, pedophilia, pedophiliac, penis, proship, proshipper, pussy, rape, rapist, sexually assaulted, sexually harassed, shithead, stfu, suicide, tanner fishies, tannerfishies, vivziepop, xxx```

We also block specific regex filters which we use for more fine-tuned prevention of specific words.
For security purposes, these filters are private however the 4 filters we use are specifically targeted to preventing speciifc content even when people attempt to obfuscate/hide it. These filters are specifically for:
* Crypto Scams
* Porn Mentions
* R-Slur
* Hawk Tuah

We also block all `discord.com/*`, `discord.gg/*`, `discordapp.com/*`, and `discord.gift/*` URLs from being sent in the server.
Except for the following allowed paths: ```discord.com/blog, discord.com/channels/*, discord.com/invite/ninjago, discord.com/nitro, discord.com/safety, discord.gg/ninjago, *discordapp.com/attachments*, support.discord.com```

---
© 2026 Ancilla
