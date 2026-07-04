# iPod Video 5.5 Gen refurb 🎧

Just a small project where I fixed up an old **iPod Video 5.5 Gen** and made it usable again.

I wanted this thing to be a simple offline music player. No streaming, no apps, no distractions, just music. The iPod was a bit rough when I got into it, so I replaced some parts, fixed some annoying issues, and installed Rockbox so it is nicer to use.

## iPod info

- Apple iPod Video 5.5 Gen
- Model number: `A1136`
- 30 GB thin version
- Serial: `9C7108YBV9M`
- Serial ending: `V9M`
- Original Apple firmware I saw: `1.3`
- Usable storage was around `27.8 GB`
- Original drive is the 1.8-inch ZIF hard drive
- Original battery marking was `616-0229`

## What was wrong with it 🔧

The iPod had definitely been used. The outside was scratched up, the battery was old, and the buttons did not feel right anymore.

The headphone / MP3 jack ribbon cable holder was also broken, so that had to be replaced too. I opened it up thinking I might also change the hard drive, but after checking it, the drive was actually still really good, so I left it in.

## What I changed

- changed the battery
- fixed the buttons so they are clicky again
- replaced the broken headphone jack ribbon cable holder
- checked the hard drive and kept it because it was still good
- changed the front plate
- changed the back plate
- changed the click wheel
- added the new red/black case parts
- put it in a clear case
- installed Rockbox
- set it up so it can still boot the normal Apple firmware too

## Parts I used 🧰

- clear thin protective case
- red front plate and rear housing / shell set
- iFixit iPod Video 30 GB battery
- replacement click wheel
- headphone jack ribbon holder / related small part
- iFlash-Solo and HDD ribbon, bought for a possible storage upgrade later
- 128 GB microSD card, also for a possible future flash mod

I was originally going to do the iFlash storage mod, but I did not end up doing it for now because the original drive was surprisingly healthy.

## Storage 💾

The iPod is still using its original 30 GB hard drive.

I know flash storage would be better long term, and I already looked into the iFlash-Solo route, but it felt unnecessary for this build right now. If the hard drive starts making problems later, then I can still swap it.

## Battery 🔋

I used a normal iPod Video 30 GB replacement battery from iFixit.

I did not go for one of those huge battery mods because this is the thin 30 GB model, and I did not want to mess around with thick backs or weird fitment problems. I just wanted it to close properly and work.

## Case / look ✨

The final look is basically red and black with a clear case over it.

The old back plate is scratched, but it has the original serial number on it, so I am keeping it with the project instead of throwing it away.

## Rockbox 🎵

I installed Rockbox and set up dual boot.

- normal boot goes into Rockbox
- to boot the Apple firmware, turn it on and switch Hold on right away
- force restart is Menu + Center
- disk mode is Menu + Center, then Center + Play/Pause
- shutdown in Rockbox is holding Play/Pause

Rockbox is the main reason I wanted to do this. It makes the iPod feel way more useful, and I can just copy music into folders instead of dealing with iTunes.

## Music folders 📁

I am keeping the music folders simple:

```text
/Music/
  Artist/
    Album/
      01 Track Name.mp3
      02 Track Name.flac
```

Folder browsing is good enough for me. I might use the Rockbox database later, but I do not really need it.

## Current build

```text
iPod Video 5.5 Gen A1136
30 GB thin model
original 30 GB hard drive
new battery
fixed buttons
fixed headphone jack ribbon holder
red/black shell
clear case
Rockbox + Apple firmware dual boot
```

That is basically it. It is not perfect or anything, but it looks much better now, the buttons feel better, and it works as a nice little offline music player.
