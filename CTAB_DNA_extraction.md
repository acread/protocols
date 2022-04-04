# Modified CTAB
This is a mix of a Springer Lab protocol and suggestions in a YouTube recording of a HMW extraction protocol presentation

Modified CTAB buffer: \
This is for 10mL
- 1mL 1M TRIS pH 7.5
- 2.8mL 1.5M NaCl *Note, this is higher than 'normal'
- 200uL .01M EDTA
- 200mg CTAB *Note, this is higher than 'normal'
- ddH2O to 10mL


1. Before starting make modified CTAB buffer, turn heating block on to 65c, and add 20uL Betamercaptoethanol per mL CTAB buffer
    - I believe this is a higher amount of betamercapto than 'normal'
    - only add betamercapto to the amount you need to use, leftover CTAB buffer can be stored
3. Grind plant tissue in liquid N2 in pre-cooled mortar and pestle - add more liquid N2 as needed - until a fine powder
    - I'm not exactly sure what the optimum amount of tissue is for each prep, I believe I was somewhere in the 250mg ballpark
4. Transfer ~250mg ground tissue to a 2mL tube, add 700uL CTAB buffer, vortex
5. Incubate at 65c for 60-90 minutes - invert tube every five minutes to mix
### Move to fume Hood
6. Add 400uL Chloroform:IAA (24:1) to each tube and vortex to mix
7. Spin for 5 minutes at 12,500 RPM
8. Transfer the top phase to a new 1.7mL tube
9. Add 400uL Chloroform:IAA (24:1) to each tube and vortex to mix
10. Spin for 5 minutes at 12,500 RPM 
11. Transfer the top phase to a new 1.7mL tube
12. Add 300uL Isopropanol (preferably cold), mix by inversion NOT vortex, and incubate 15 minutes at -20c
13. Spin 5 minutes and pour off supernatant into sink - should have a visible pellet
14. Add 450uL 70% ethanol and vortex (I'm not sure if vortexing is a good idea at this point)
15. Spin 5 minutes and pour off supernatant
16. Quick spin and pipette off any additional ethanol
17. Allow to air dry with caps open about 10 minutes
18. Resuspend in 200-250uL nuclease free H2O or elution buffer

### Quality check
19. Check DNA concentration and contamination with Nanodrop (in my limited experience it looks like there is \
carryover of a contaminant that absorbs at ~230nm so the 260/230 ratio is not good)
    - Note that target 260/230 and 260/280 are both around 2.0

### Bead clean-up
20. Bring SPRI beads to room temp - about 30 minutes.  I'm using AMPure.
21. Add 0.5x volume of resuspended beads to DNA sample (this ratio should get rid of lots of small DNA fragments - less than 600bp)
22. Mix and incubate at RT for 5 minutes
23. Put on magnet rack and aspirate out clear supernatant
24. Gentle wash with 200uL 70% ethanol x2 (I'm not disturbing the pellet here)
25. Add elution buffer (I added 200uL to a 200uL starting DNA sample - can modify to boost concentration)
26. Flick to resuspend and incubate at RT 2 minutes
27. Place on magnet and transfer eluate to new 1.7mL tube

Link to some good info on SPRI beads:
https://diagnostech.co.za/next-generation-sequencing-tips-n-tricks-part-2/

### Quality check
28. Following bead clean-up I see a decrease in total amount of DNA, but the 260/230 is MUCH better
29. Submit 8-10uL to the UMGC for fluoresence quantification and size distribution
30. cross fingers

### UMGC Results
I submitted samples from both the cleaned up and non-bead cleaned preps \
Based on the results I am going to use sample 3 (cleaned) BUT I am going to do a short read eliminator kit to get rid of \
shorter fragments and (mainly) to concentrate the DNA a bit.

<img width="461" alt="image" src="https://user-images.githubusercontent.com/43852873/161580988-3b46dd1e-307a-4424-a699-def794d27ce2.png">

<img width="592" alt="image" src="https://user-images.githubusercontent.com/43852873/161581038-1fe8bfc6-50c3-4619-8cb8-ce2418e00893.png">

### SRE
In retrospect I'm not sure if this was necessary, but I did it
1. 60uL DNA + 60uL BRE Buffer in 1.5mL tube - gently mix
2. Spin 10,000 xG 30 minutes at RT
3. Pipette off supernatant -- avoid where the pellet should be
4. Add 200uL freshly made 70% EtOH - do not vortex - spin 2 minutes and pipette off
5. Repeat wash
6. Allow to dry ~2 minutes
7. Add Elution Buffer and inucabate at RT 20 minutes
### Note: I did not see any evidence of a the pellet and was concerned that I lost the DNA, but QC looked good

