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
```*<sound:*, 🌽hub, 🍖🌈, 🎱🎀, 666, antiniggers, ass, asshole, bitch, ball gag, ball licking, ball sack, ball sucking, ballgag, balls deep, barelylegal, bdsm, beaner, beat my meat, bestiality, big black, bitch, blacky, blmtard, blonde on blonde, blonde on blonde action, blow your load, blowjob, bondage, boner, boobs, booty call, boyfuck, boypussy, breastman, breasts, butthole, cam boy, cam girl, cam show, camel toe, camslut, camwhore, carpet muncher, childfucker, childrape, childsex, chriscreator, clansmen, clit, clitoris, clitty, cocaine, cock, comship, comshipper, coon, cornhub, cp, cum, cunnilingus, cybersex, darkie, darkship, darkshipper, date rape, ddlg, deep throat, dick, dickhead, diddy, diddy party, dildo, dogfucker, dogfucking, doggie style, dominatrix, dommes, dp, *drive.google.com*, drugs, dry hump, dumbasses, e sex, eatme, ejaculation, erection, esex, esptein, extacy, extasy, face fuck, fag, foot fetish, footjob, fuck off, fuck you, fucker, fucktards, fucktoy, fucktrophy, fuktard, gang bang, gay sex, girl gone wild, girls on top, golden shower, goon, gooned, gooner, gooning, greenflame, hand job, handjob, hazbin, helluva, hentai, hentai haven, hentaihaven, heroin, hitler, holy fuck, holy hell, holy shit, hom0, homobangers, horney, horny, horsefucking, inbred, incel, incest, jerk mate, jerk off, jesus fucking christ, jfc, joseph smith, k!ke, k1ke, kike, kill myself, kill yourself, kinky, libtard, live sex, loli, lolicon, lolita, masturbate, meth, milf, molest, molestation, molested, molester, motherfucker, my naked photos, my sexy photos, n*des, negro, neonazi, nigger, ninjago media project, nsfw images, nsfw videos, nudes, onlyfans, oral sex, orgasm, orgy, ouija, pedo, pedophile, penis, phone sex, playboy, pornhub, proship, proshipper, pussy, r34, rape, s&m, sexually assaulted, sexually harassed, shithead, slut, stfu, suicide, tanner fishies, tits, tranny, *unY8CMLu_3w*, vivziepop, xxx, *YHVSMNbu9eE*```

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
