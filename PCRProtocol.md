# TdT Characterization Experiment
Written by Alan Tomusiak and Amy Dunphy \
*Written:* 4/02/2019 \
*Performed:* 4/09/2019

Procedure Purpose
=================
Perform a PCR to isolate a 300-bp fragment from a pUC19 plasmid while adding restriction sites close to each end. This protocol will also create positive control strands for downstream Sanger sequencing, in which the desired nucleotide to be added is already in the strand.


Overview
========

Materials
----------

-   100 uM "Dev_PCR_Fwd_1" Oligonucleotide (Sequence: 5'- /Phos/ GCAGCCAACTCAGCTTCTGCAGgtatgttgtgtggaattgtgagc- 3')
-   100 uM "Dev_PCR_Fwd_2" Oligonucleotide (Sequence: 5'- /Phos/ GCAGCCAACTCAGCTTCTGCAGctatgaccatgattacgccaag- 3')
-   100 uM "Dev_PCR_Fwd_3" Oligonucleotide (Sequence: 5'- /Phos/ GCAGCCAACTCAGCTTCTGCAGccggatcaagagctaccaac- 3')
-   100 uM "Dev_PCR_Rev_1" Oligonucleotide (Sequence: 5'- AAACAAGCGCTCATGAGCCAGGCTCCTGGtgtgaaataccgcacagatgc- 3')
-   100 uM "Dev_PCR_Rev_2" Oligonucleotide (Sequence: 5'- AAACAAGCGCTCATGAGCCAGGCTCCTGGGCATCAGAGCAGATTGTACTG -3')
-   100 uM "Dev_PCR_Rev_3" Oligonucleotide (Sequence: 5'- AAACAAGCGCTCATGAGCCAGGCTCCTGGTCCGCCTTTCTCCCTTCGG -3')
-   100 uM "Dev_PCRPos_Rev_1" Oligonucleotide (Sequence: 5'- AGCTCCTGGtgtgaaataccgcacagatgc -3')
-   100 uM "Dev_PCRPos_Rev_2" Oligonucleotide (Sequence: 5'- AGCTCCTGGGCATCAGAGCAGATTGTACTG -3')
-   100 uM "Dev_PCRPos_Rev_3" Oligonucleotide (Sequence: 5'- AGCTCCTGGTCCGCCTTTCTCCCTTCGG -3')
-   Phusion DNA Polymerase
-   5X Phusion HF Buffer
-   pUC19 DNA
-   10mM dNTPs
-   10,000X Sybr Green I
-   Water

Dilutions
----------
1. Create a 500X Sybr dilution by diluting 1uL Sybr Green I into 19uL water.

Procedure
=========
Prepare Master Mix
-------------
1. Label a tube 'MM1' for 'Master Mix One' and another tube 'MM2' for 'Master Mix Two.'
2. Pipette 500uL water, 1.5uL 500X Sybr, 7.5uL Phusion DNA polymerase, 150uL Phusion HF Buffer, 15uL 10mM dNTPs, and 3uL pUC19 into MM1.
3. Pipette 500uL water, 1.5uL 500X Sybr, 7.5uL Phusion DNA polymerase, 150uL Phusion HF Buffer, 15uL 10mM dNTPs, and 3uL pUC19 into MM2. 

Prepare Primers
-------------
1. Label six tubes 'PS1,' 'PS2,' 'PS3,' 'POS1,' 'POS2,' and 'POS3.'
2. Pipette 16uL of water, 2 uL of "Dev_PCR_Fwd_1", and 2 uL of "Dev_PCR_Rev_1" into 'PS1.'
3. Pipette 16uL of water, 2 uL of "Dev_PCR_Fwd_2", and 2 uL of "Dev_PCR_Rev_2" into 'PS2.'
4. Pipette 16uL of water, 2 uL of "Dev_PCR_Fwd_3", and 2 uL of "Dev_PCR_Rev_3" into 'PS3.'
5. Pipette 16uL of water, 2 uL of "Dev_PCR_Fwd_1", and 2 uL of "Dev_PCRPos_Rev_1" into 'POS1.'
6. Pipette 16uL of water, 2 uL of "Dev_PCR_Fwd_2", and 2 uL of "Dev_PCRPos_Rev_2" into 'POS2.'
7. Pipette 16uL of water, 2 uL of "Dev_PCR_Fwd_3", and 2 uL of "Dev_PCRPos_Rev_3" into 'POS3.'


Prepare Plate
-------------
1. Obtain a 96-well PCR plate. Align it with the table below.

|   | 1 |  2  |  3  |  4  | 5 |   6  |   7  |   8  | 9 | 10 | 11 | 12 |
|:-:|:-:|:---:|:---:|:---:|:-:|:----:|:----:|:----:|:-:|:--:|:--:|:--:|
| A |   | PS1 | PS2 | PS3 |   | POS1 | POS2 | POS3 |   |    |    |    |
| B |   |     |     |     |   |      |      |      |   |    |    |    |
| C |   |     |     |     |   |      |      |      |   |    |    |    |
| D |   | PS1 | PS2 | PS3 |   | POS1 | POS2 | POS3 |   |    |    |    |
| E |   |     |     |     |   |      |      |      |   |    |    |    |
| F |   | PS1 | PS2 | PS3 |   | POS1 | POS2 | POS3 |   |    |    |    |
| G |   |     |     |     |   |      |      |      |   |    |    |    |
| H |   | PS1 | PS2 | PS3 |   | POS1 | POS2 | POS3 |   |    |    |    |

2. Into all 'PS' wells, pipette 45uL of MM1.
3. Into all 'POS' wells, pipette 45uL of MM2.
4. Into all wells, pipette 5uL of the corresponding diluted primer set.

Thermocycler Setup
-------------
1. On the thermocycler, set-up conditions for a gradient PCR to be the following:
   - One cycle of denaturation at 98C for 30 seconds.
   - Thirty cycles of:
     - Denaturation at 98C for 10 seconds.
     - Annealing temperature GRADIENT between 52C to 60C for 20 seconds.
     - Extension at 72C for 15 seconds.
     - Plate read.
   - Final extension at 72C for 5 minutes.
   - Hold for 4C.
2. View the fluorescence curves. Run the most promising samples on a gel for verification.