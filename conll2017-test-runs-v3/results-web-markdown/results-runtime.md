---
layout: page
title: CoNLL 2017 Shared Task
---

# Results: System run time

<strong style='color:red'>DISCLAIMER:</strong> This is not a fair comparison.
Some of these numbers may be interesting for the big picture but no conclusions should be drawn from details.
TIRA is not set up as a benchmarking environment.
Not all systems ran on the same hardware: teams that asked for more resources (CPUs, memory, disk) got it.
Even the same system applied to the same data sometimes required significantly more time than previously, depending on the actual traffic.
Furthermore, results of certain teams are taken from several runs combined.
In these cases the table shows the sum of the run times but it does not say much.
Besides the overhead of running the system multiple times, sometimes the system just pretended to run for many hours without
actually producing new output, then it was killed, surviving output files used, and a new run initiated to produce the remaining outputs.

The run time is indicated in hours.

<pre>
  1. fbaml (Palo Alto)                          software1-P     112.58 [combined]
  2. LyS-FASTPARSE (A Coruña)                   software5-P      31.61
  3. IMS (Stuttgart)                            software2-P      26.17
  4. OpenU NLP Lab (Ra'anana)                   software6-P      16.78 [combined]
  5. Stanford (Stanford)                        software1-P      16.27
  6. ECNU (Shanghai)                            software1-P      16.12
  7. LIMSI (Paris)                              software2-P      10.56
  8. CLCL (Genève)                              software2-P       9.67 [combined]
  9. RACAI (București)                          software1-P       8.93 [combined]
 10. HIT-SCIR (Harbin)                          software4-P       8.88
 11. Uppsala (Uppsala)                          software1-P       6.71
 12. LATTICE (Paris)                            software7-P       5.96
 13. C2L2 (Ithaca)                              software5-P       4.64
 14. ParisNLP (Paris)                           software1-P       3.79
 15. NAIST SATO (Nara)                          software1-P       3.30
 16. Orange – Deskiñ (Lannion)                  software1-P       2.99
 17. Koç University (İstanbul)                  software3-P       2.92
 18. UParse (Edinburgh)                         software1-P       2.72
 19. ÚFAL – UDPipe 1.2 (Praha)                  software1-P       2.27
 20. darc (Tübingen)                            software1-P       1.79
 21. MQuni (Sydney)                             software2-P       1.56
 22. Wenba-NLU (Wuhan)                          software1-P       1.50
 23. TurkuNLP (Turku)                           software1-P       1.37
 24. Mengest (Shanghai)                         software1-P       1.21 [combined]
 25. METU (Ankara)                              software2-P       0.95
 26. naistCL (Nara)                             software1-P       0.77
 27. Wanghao-ftd-SJTU (Shanghai)                software2-P       0.59
 28. MetaRomance (Santiago de Compostela)       software1-P       0.50
 29. BASELINE UDPipe 1.1 (Praha)                software2-P       0.48
 30. IIT Kharagpur (Kharagpur)                  software3-P       0.30
 31. UALING (Tucson)                            software1-P       0.17
 32. TRL (Tokyo)                                software1-P       0.17
 33. UT (Tartu)                                 software1-P       0.00 [combined]
</pre>

## Resource Allocation Table

<pre>
    Team                 LAS    CPUs  RAM (GB)
 1. Stanford             76.30     4   16
 2. C2L2                 75.00     2    8
 3. IMS                  74.42    12   64
 4. HIT-SCIR             72.11     1    8
 5. LATTICE              70.93     8   32
 6. NAIST SATO           70.14     1    4
 7. Koc University       69.76     4   32
 8. UFAL                 69.52     1    4
 9. UParse               68.87     4   16
10. Orange               68.61     1   16
11. TurkuNLP             68.59     4   32
12. darc                 68.41     1    4
13. BASELINE UDPipe 1.1  68.35     1    4
14. MQuni                68.05     1    6
15. fbaml                67.87    18  128
16. LyS                  67.81     1   64
17. LIMSI                67.72     4   16
18. RACAI                67.71     4   64
19. IIT Kharagpur        67.61     8  128
20. naistCL              67.59     1    4
21. Wanghao-ftd-SJTU     66.53     1    4
22. UALING               65.24     6   32
23. Uppsala              65.11    10   10
24. METU                 61.98     1    4
25. CLCL                 61.82     4    8
26. Mengest              61.33     1    4
27. ParisNLP             60.02    12   64
28. OpenU                56.56    12   32
29. TRL                  43.07     1    4
30. MetaRomance          34.05     1    4
31. UT                   21.10    10   32
32. ECNU                  3.18    12   65
33. Wenba-NLU             0.58     1    4
</pre>
