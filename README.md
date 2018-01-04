## g0blinXv0rtex - A g0blin & v0rtex remix jailbreak
This is a fork of @Sticktron's g0blin jailbreak merged with @xPreeks's tweaks and offsets.

Fork not working because I deleted my project files, gonna remake them maybe.

## .ipa file (Updated on 01/03/2018 19:45) 

.ipa compiled by me, and working on my iPhone 5s on iOS 10.3.3.

## Q&A

Q: What is this?

A: A semi-working, semi-tethered jailbreak made by Sticktron and modified with xPreek's tweaks.

Q: Does it work?

A: If you don't mind having a buggy and possibly broken phone, then yes.

Q: I got a problem!

A: Sorry, I'm not the developer, can't really help you.



Credits to the original devs, I only merged and compiled the .ipa.


// ORGINAL README STARTS HERE //

# g0blin

An incomplete jailbreak for A7-A9 devices on iOS 10.3.x

Spawns an SSH server listening on port 2222. Remember to change your passwords!

Please reinstall the bootstrap when upgrading.


## what is still broken?

Third-party applications that need root priveledges require an extra entitlement to function correctly.

````
<key>com.apple.private.security.no-container</key>
<true/>
````

I have already added the entitlement to the copy of Cydia included in g0blin.

For other apps (eg. Filza, MTerminal) to work correctly you will have to entitle them yourself.


## credits

Siguza - v0rtex kernel exploit

Luca Todesco - yalu102 kpp bypass

Xerub - patchfinder (extra_recipe)

Saurik - Cydia

thanks: PsychoTea, ARX8x, Abraham Masri, ninjaprawn, coolstar, ... ?
