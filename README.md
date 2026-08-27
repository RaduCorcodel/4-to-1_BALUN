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

It appears that 10 turns of 16AWG on a T240-61 toroid gives the best overall performance. In my practical application I only use 100W of RF power for which this core and wire gauge is way overkill but since it gives a slightly better performance, this is what I used in my field applications.

## *Nota Bene*
The SWR that I'm reading corresponds to the same length of hookup wires from the terminals of the transformer to the SMA connector that goes to the Vector Network Analyzer. Your experiments might vary with different lengths of hookup wire.

## Experimenting with Litz wire
Blast from the past; Litz wire was used in the early days of radio for some assumed performance gains. Litz wire consists of dozens of very thin individually coated copper wires bunched together. Since RF travels only on the surface of the wire, this gives the overall cable much more surface area than monofillar wire. In time, this was disproven and regular single-core enameled copper wire became the norm for RF transformers. Nevertheless, I wanted to see if there are any measurable gains for using Litz wire.

![Toroid size T240-61 with 10 turn per side](img/4TO1-BALUN-LITZFIN.png)
*Toroid size T240-61 with 10 turn Litz per side*

Plot shows a slightly worse performance than single-core 16AWG enameled wire. But we're really splitting hairs here (pardon the pun). For practical reasons they are so close in performance that their practical application would be indistinguishable. Band conditions will be the determining factor, not the slight edge of one transformer over the other.

## In conclusion
We tested a few core sizes, wire size, wire wrapping style and specialized wire to give us an insight into how they might affect the performance of 4:1 BALUN transformers. The comparison can be further improved of course; I didn't have all combinations of cores sizes, materials, winding patterns and wire sizes. Nevertheless, this tests gives us some information about what to expect when winding a 4:1 BALUN. In my test, a T240-61 core and using 16AWG single-core enameled copper wire had a slightly better performance. But slightly! In reality, dare I say, any of these cores would've been undistinguishable, with the band conditions playing a much bigger role. 

It was a fun experiment 
