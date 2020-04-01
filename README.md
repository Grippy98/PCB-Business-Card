# PCB-Buisiness-Card
---

Business Cards are always something that I’ve found to be sort of a nuisance. On one hand, they’re something that very few people ever have on hand, and on the other, when you do get one, you’re very likely to misplace or throw it away. That being said, they are a good way of sharing your contact details, and while I have made my own nicely designed ones on paper, I couldn’t help but think that I could make something better. My goal here was to make something that not only could I be proud to give out to possible recruiters or people I’d want to contact in the future, but I wanted to make something they’d actually WANT to keep with them or in their wallet.

Therefore I set out to design what you see before you, my very own extremely functional PCB business card. I credit it for a good number of job interviews I've gotten this past summer. It's a constant work in progress, but I'm very pleased with how it's turned out. 

###### A huge shoutout to Loann Boudin for his NFC design and for documenting it on Instructables: https://www.instructables.com/id/PCB-Business-Card-With-NFC/

### As far as the card’s functionality goes: 

1. 1S Lithium Battery Charger 
2. NFC Enabled - Have it setup to link to my Website/Resume (also demonstrates power harvesting to LED)
3. Simple logic probe that will tell you if a signal is high/low, oscillating or floating (the last two perhaps are especially useful)
4. Basic flash light (because why not) 
5. Metric/imperial Ruler
6. AWG Gauge 
7. References for trace widths in Mils 
8. Reference for PCB Font Sizes 
9. Reference for some standard component footprints

![alt text](https://github.com/Grippy98/PCB-Buisiness-Card/blob/master/images/front.jpg "PCB Front")
![alt text](https://github.com/Grippy98/PCB-Buisiness-Card/blob/master/images/back.jpg "PCB Back")
---

### Ordering Your Own

The Boards you see were made by JLC PCB with an ENIG finnish, regular LEAD free also works. I do very much recommend you don't hand out leaded PCBs for people to handle and keep in their wallets, but that's just my two cents.

I have experimented with 0.6mm Thick Boards and above, but I recommend 0.8mm as it's thin enough while also being a bit more rigid. 

### BOM:
(TODO - fill out when I have some more time, consult schematic otherwise)
1x BRCL4054BME Power Management IC


### Notes on Soldering:

It's all rather easy to solder by hand, save for the QFN8 Package of the NFC IC, which is tough to get right, especially with Lead-free solder paste. I was able to make over 30 of these boards without defect and minor fixes by using solder masks and plenty of flux, but this is very much not beginner friendly. 

![alt text](https://github.com/Grippy98/PCB-Buisiness-Card/blob/master/images/microscope.jpg "Under the Microscope")

