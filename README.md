# Experiments with 4:1 BALUNs for Ham Radio


## Experimenting with wiring style
### Core size T114
![Parallel turns](img/4TO1_BALUN_114-43T.png) ![Twisted turns](img/4T1_BALUN_114-43TT.png)

### Core size T140
![Parallel turns](img/4TO1_BALUN_F140-61.png) ![Twisted turns](img/4TO1_BALUN_140-61T.png)

### Core size T240
Because of the large wire size, it is impractical to twist the wires so we only ran the test for parallel turns
![Parallel turns](img/4TO1_BALUN_240-61T.png)

In this test the plots show that a twisted pair of wires have a slight better performance. Although for the T240 core I used 16AWG which is impractical to twist so I couldn't test that combination.


## Experimenting with toroid material
### Material 43
![Toroid size T114-43](img/4T1_BALUN_114-43TT.png)
![Toroid size T140-43](img/4TO1_BALUN_F140-43.png)

### Material 61
![Toroid size T140-61](img/4TO1_BALUN_140-61T.png)
![Toroid size T240-61](img/4TO1_BALUN_240-61T.png)

In this experiment the plots show that the #61 material is slightly better than #43 in the 40m - 10m ham radio bands.

## Experimenting with different number of turns
So far it appears that the T240-61 core has the better performance so for the next couple tests I only used this core. I used enameled copper wire with the thickness of 16AWG for all experiments.
![Toroid size T240-61 with 10 turn per side](img/41_BAL_240-61_10T.png)
*Toroid size T240-61 with 10 turn per side*

![Toroid size T240-61 with 11 turn per side](img/41_BAL_240-61_11T.png)
*Toroid size T240-61 with 11 turn per side*

![Toroid size T240-61 with 12 turn per side](img/41_BAL_240-61_12T.png)
*Toroid size T240-61 with 12 turn per side*

It appears that 10 turns of 

## *Nota Bene*
The SWR that I'm reading corresponds to the same length of hookup wires from the terminals of the transformer to the SMA connector that goes to the Vector Network Analyzer. Your experiments might vary with different length of hookup wire
