# HTP DNA extraction from mouse fecal pellets using ZymoBIOMICS 96 MagBead DNA Kit


The following protocol is adapted from the manual for the [ZymoBIOMICS 96 MagBead DNA Kit (D4302)](https://www.zymoresearch.com/media/amasty/amfile/attach/_D4303_D4307_D4309_ZymoBIOMICS_96_DNA_Kit_1.4.0.pdf) and the [SOP from Jordan Bisanz](https://github.com/jbisanz/LabProtocols/blob/master/16S_SOP_2017.md) for 16S rRNA gene analysis.

### Equipment and supplies

- [ ] 96-well microfuge tube rack
- [ ] 65°C aluminum bead dry bath
- [ ] BioSpec Mini-Beadbeater-96
- [ ] centrifuge with appropriate rotor/adapters for plates
- [ ] IKA MS 3 Digital Shaker, or other 96-well plate/block shaker
- [ ] tweezers with smooth tips, for easy cleaning
- [ ] magnetic rack compatible with deep-well plates (Sigma Z740158)
- [ ] aspiration vaccuum flask with multichannel adapter
- [ ] electronic or manual multichannel pipettes for 25 ul to 900 ul volumes



### Reagents and consumables

- [ ] ZymoBIOMICS MagBead-96 DNA kit (D4302)
- [ ] 750 ul beta-mercaptoethanol for adding to lysis buffer
- [ ] 2 ml deep-well 96-well mag-compatible plate (OX1275-S)
- [ ] laboratory DNA extraction standards
- [ ] pipette tips compatible with electronic or multichannel pipettes
- [ ] 0.2 ml PCR plate
- [ ] adhesive aluminum sealing foil
- [ ] 96-well microplate and paper freezer box


### Prep

- Check solutions from Zymo kit; prepare lysis buffer by adding beta-mercaptoethanol.
- If using an electronic pipette, make sure it is charged.


### Weigh pellets

This is a tedious part of the protocol and makes for a long day when done together with the DNA extraction; therefore, I like to separate the two procedures into two days. Weighing fecal pellets will take approximately 1 hour per plate. If you have multiple plates, I highly recommend this separation.

1. Include a few wells as negative DNA extraction controls. For DNA extractions for 16S rRNA gene sequencing, include laboratory DNA extraction standards. Consider that ZymoBIOMICS strip tubes allow extraction in multiples of 8, so the total number of samples should be a multiple of 8.
2. Randomize samples and controls for DNA extraction.\
*Exercise: Use tidyverse/dplyr function sample_n() to accomplish this.*
3. Place sample tubes in a microfuge tube rack in the randomized order, for more efficient and less error-prone sample transfer to the Zymo strip tubes. Double check that samples are in their correct position.
4. Label the first tube of each strip of tubes in the lysis rack with the column number and "A", e.g. "1A", "2A", etc.
5. Using tweezers, loosen caps on strip stubes in the lysis rack. 
6. Keeping samples on dry ice to prevent thawing, weigh fecal pellets on weigh paper, and transfer to Zymo strip tubes. Clean tweezers with water and/or 70% ethanol as necessary.\
*Tip: Aggressively shaking the tube will separate individual fecal pellets that have frozen together.*
7. Record weights so that you may use them later for normalization.
8. Use tape to secure the lid of the lysis rack; label with your initials and store at -20°C until ready for DNA extraction.


### Extract DNA

10. Add 650 ul lysis buffer to samples.
11. Secure lids well.
12. Heat 65°C for 10 min.
13. Place folded Kimwipes against the top of lids to absorb leaked fluids, and place lid securely on top.\
*Tip: these tubes are prone to leaking; unfortunately, I have not found a good solution for this.*
14. Secure in bead beater and disrupt for 5 min.
15. Remove Kimwipes and wipe tubes dry. Moisten a Kimwipe with 70% ethanol and wipe down the tops of the tubes.
16. Centrifuge 3250 rpm (~2000g) 10 min at RT in Beckman Coulter Allegra 6R.
17. Transfer 200 ul to 2-ml 96-well deep-well block; label the lysis rack and store remainder -20°C.
18. Add 600 ul binding buffer.
19. Vortex magnetic beads for 5-10 s to thoroughly resuspend; add 25 ul beads.
20. Pipette with P100/200 to mix well; cover with adhesive foil; vortex 10 min, 750 rpm; capture beads on magnetic stand; discard supernatant by aspiration.
21. Remove from magnetic stand; add 900 ul Wash 1 and pipette once to mix; cover with adhesive foil; vortex 5 min, 750 rpm; capture beads on magnetic stand; discard supernatant by aspiration.
22. Remove from magnetic stand; add 900 ul Wash 2 and pipette once to mix; cover with adhesive foil; vortex 5 min, 750 rpm; capture beads on magnetic stand; discard supernatant by aspiration.
23. Repeat previous step.
24. Pop centrifuge 1000 rpm to draw remaining liquid and beads to bottom of the well.\
*Note: residual liquid on well sides is more difficult to evaporate in the next step.*
25. Dry well at 65°C 15-30 min in aluminum bead dry bath, with a loose fitting cover to allow evaporation.
26. Elute DNA by adding 100 ul water and pipetting well to mix; cover with adhesive foil, vortex 10 min, 1000 rpm.
27. Capture beads on magnetic stand; carefully rescue DNA in supernatant and transfer to PCR plate.
28. Label PCR plate with date and description; place PCR plate in microplate, and label microplate lid with more detailed information. Place microplate in freezer box and store DNA at -20°C.



















