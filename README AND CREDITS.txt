DCvM Public Screenpack
Version: 1.0 (1st public release, 6 January 2008)

Created by the ScruffyDragon team
for the MUGEN DC vs Marvel project
-----------------------------------------------------------------------

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Some simple suggestions regarding this screenpack
- Don't host it on your site unless you ASK first, and give me
    proper credit. Email isn't hard, and I'll probably say yes,
    so don't be afraid to ask. =P
- Don't modify this screenpack and upload it to your own site 
    and claim it's your own work. It's not. =P
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Some notes on how to modify your existing characters to fit this screenpack; 
you'll notice that regular characters won't show up properly on the select or VS
screens. That's because of the tweaks we did to get the face/offs to look right.

If you look in the data\support folder in this archive, you'll notice several images that should help you.
While we're not including portraits for every character on the Phase 1 roster, it's enough to get you started for now.
You'll need to open your character's SFF file in some program like Fighter Factory or MCM, and do a couple of things:
1. Replace image 9000,0 with the one in the support folder, or another one like it. Notice that Marvel characters have 
a frame that slants to the left, and DC characters have one that slants to the right.
2. Change the X and Y coordinates for sprite 9000,0; note that this will be different depending on if they're a 
DC or a Marvel character:
	DC chars: X Axis -63, Y Axis 1
	Marvel chars: X Axis 66, Y Axis 1
3. Replace image 9000,1 with the one provided in the support folder. X and Y axis should both be 0.
4. Add image 9000,100 immediately after the large portrait. This is the character's face to be shown on the main game screen.

5. For MUGEN 1.1 portrait bugs:
- On the fights small portraits don't recognize the palette.
- On the versus screen mugen 1.1 ignores the "facing" parameter, the P2 name shows mirrored.

-----------------------------------------------------------------------
SCREENPACK CREDITS

- Select screen layout devised by TA-Chan (PauTo) and ss5ace
- Inspired by ideas from Magus in the previous private versions of the screenpack
- Hitsparks by Loganir & SethZankuten
- Lifebars by McCready & Buyog
- Minilogos for Characters by Hecbator & PrimeOP
- Title logo by Sei
- Programmed by Magus & Buyog
- DC and Marvel for their awesome characters that give us so much fun.
- Capcom for the Marvel Versus series of games that inspired us all.

CHARACTER CREDITS

- Batman by Alucard & Magus
- Captain America by MysticBlaze
- Carnage by Seth Zankuten
- Crystal by Magus, Smogon & Jeff
- Darkseid by Wucash
- Doctor Doom  by Juan Carlos & Tachan
- Etigran by Wucash
- Ghost Rider by Wucash
- Green Lantern by Buyog, Enzo & Arque
- Ice by Buyog, Smogon & Ghouly Mad Maximoff
- Iron-man by Magus
- Lobo by Buyog
- Lex Luthor by Buyog, Enzo, Smogon, Kal-Elvis, McCready, Tenchimuyo4ever, Kojunho, & Gate 
- Parasite by Buyog & Jet the Phoenix
- Plastic-man by Mambojambo
- Sandman by McCready & Loganir
- Savage Hulk by Buyog & Bob Starsky
- Spider-man by Seth Zankuten
- Superboy by Seth Zankuten
- Superman by Hannibal & Kal Elvis
- Thanos by Alucard
- Thor by Black Dragon and Loganir
- Wolverine by ArielAlexCo 
- Wonder Woman by Loganir

STAGES CREDITS
- Apokolips by Magus
- Alkali Cataracts by Magus
- Asgard Bifrost by Loganir
- Cypress Hill Cementery by Wucash & Doom
- Carnival by Juan Carlos
- Gotham Bayside by Magus
- Jason Blood's Apartment by Wucash
- Latveria Castle by Magus
- Lexcorp by Wucash 
- Lobo's Bar by Magus
- Manhattan Night by Juan Carlos
- Metropolis by Magus
- Nuclear Power Plan by McCready & Wucash
- Oan Moon by McCready & Wucash
- Rykers Island by Wucash
- Sanctuary by Juan Carlos
- STAR Labs by Gate & Wucash
- Stark Industries by Juan Carlos
- Themyscira by Loganir
- Times Square by Seth Zankuten
- Titans Tower by Seth Zankuten
- Watchtower by McCready, Magus & Buyog
- Yancy St by Aphaty and Magus
- Training Stage by Buyog

If we forget to mention someone, it was not intentional, many people work on this for a long time and sometimes some name escapes mind.

LINKAGE
Buyog's email:            buyog2099@yahoo.com
Buyog's webspace:         http://www.buyog.com/MUGEN
DCvsMarvel webspace:      http://www.scruffydragon.com
