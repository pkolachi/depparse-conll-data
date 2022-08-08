---
layout: page
title: CoNLL 2017 Shared Task
---

# Results: Labeled Attachment Score (LAS)

## All treebanks

This is the main ranking of the systems by their macro-averaged LAS F1 score.

<pre>
 1. Stanford (Stanford)                         software1-P     76.30 [OK]
 2. C2L2 (Ithaca)                               software5-P     75.00 [OK]
 3. IMS (Stuttgart)                             software2-P     74.42 [OK]
 4. HIT-SCIR (Harbin)                           software4-P     72.11 [OK]
 5. LATTICE (Paris)                             software7-P     70.93 [OK]
 6. NAIST SATO (Nara)                           software1-P     70.14 [OK]
 7. Koç University (İstanbul)                   software3-P     69.76 [OK]
 8. ÚFAL – UDPipe 1.2 (Praha)                   software1-P     69.52 [OK]
 9. UParse (Edinburgh)                          software1-P     68.87 [OK]
10. Orange – Deskiñ (Lannion)                   software1-P     68.61 [OK]
11. TurkuNLP (Turku)                            software1-P     68.59 [OK]
12. darc (Tübingen)                             software1-P     68.41 [OK]
13. BASELINE UDPipe 1.1 (Praha)                 software2-P     68.35 [OK]
14. MQuni (Sydney)                              software2-P     68.05 [OK]
15. fbaml (Palo Alto)                           software1-P     67.87 [OK]
16. LyS-FASTPARSE (A Coruña)                    software5-P     67.81 [OK]
17. LIMSI-LIPN (Paris)                          software2-P     67.72 [OK]
18. RACAI (București)                           software1-P     67.71 [OK]
19. IIT Kharagpur (Kharagpur)                   software3-P     67.61 [OK]
20. naistCL (Nara)                              software1-P     67.59 [OK]
21. Wanghao-ftd-SJTU (Shanghai)                 software2-P     66.53 [OK]
22. UALING (Tucson)                             software1-P     65.24 [OK]
23. Uppsala (Uppsala)                           software1-P     65.11 [OK]
24. METU (Ankara)                               software2-P     61.98 [OK]
25. CLCL (Genève)                               software2-P     61.82 [OK]
26. Mengest (Shanghai)                          software1-P     61.33 [79]
27. ParisNLP (Paris)                            software1-P     60.02 [OK]
28. OpenU NLP Lab (Ra'anana)                    software6-P     56.56 [OK]
29. TRL (Tokyo)                                 software1-P     43.07 [OK]
30. MetaRomance (Santiago de Compostela)        software1-P     34.05 [78]
31. UT (Tartu)                                  software1-P     21.10 [27]
32. ECNU (Shanghai)                             software1-P      3.18 [36]
33. Wenba-NLU (Wuhan)                           software1-P      0.58 [46]
</pre>



## Big treebanks only

Macro-average LAS of the 55 big treebanks: ar, bg, ca, cs, cs_cac, cs_cltt, cu, da, de, el, en, en_lines, en_partut, es, es_ancora, et, eu, fa, fi, fi_ftb, fr, fr_sequoia, gl, got, grc, grc_proiel, he, hi, hr, hu, id, it, ja, ko, la_ittb, la_proiel, lv, nl, nl_lassysmall, no_bokmaal, no_nynorsk, pl, pt, pt_br, ro, ru, ru_syntagrus, sk, sl, sv, sv_lines, tr, ur, vi, zh.
These are the treebanks that have development data available,
hence these results should be comparable to the performance of the systems on the development data.

<pre>
 1. Stanford (Stanford)                         software1       81.77
 2. C2L2 (Ithaca)                               software5       79.85
 3. IMS (Stuttgart)                             software2       79.60
 4. HIT-SCIR (Harbin)                           software4       77.45
 5. LATTICE (Paris)                             software7       75.79
 6. NAIST SATO (Nara)                           software1       75.64
 7. LyS-FASTPARSE (A Coruña)                    software5       74.55
 8. Koç University (İstanbul)                   software3       74.39
 9. ÚFAL – UDPipe 1.2 (Praha)                   software1       74.38
10. TurkuNLP (Turku)                            software1       74.19
11. Orange – Deskiñ (Lannion)                   software1       74.13
12. MQuni (Sydney)                              software2       74.03
13. LIMSI-LIPN (Paris)                          software2       73.64
14. UParse (Edinburgh)                          software1       73.56
15. darc (Tübingen)                             software1       73.31
16. fbaml (Palo Alto)                           software1       73.11
17. BASELINE UDPipe 1.1 (Praha)                 software2       73.04
18. IIT Kharagpur (Kharagpur)                   software3       72.68
19. RACAI (București)                           software1       72.64
20. naistCL (Nara)                              software1       72.60
21. Wanghao-ftd-SJTU (Shanghai)                 software2       71.20
22. CLCL (Genève)                               software2       71.00
23. Uppsala (Uppsala)                           software1       70.96
24. UALING (Tucson)                             software1       69.59
25. METU (Ankara)                               software2       68.77
26. Mengest (Shanghai)                          software1       68.37
27. ParisNLP (Paris)                            software1       62.42
28. OpenU NLP Lab (Ra'anana)                    software6       60.95
29. TRL (Tokyo)                                 software1       45.75
30. MetaRomance (Santiago de Compostela)        software1       34.55
31. UT (Tartu)                                  software1       25.87
32. ECNU (Shanghai)                             software1        3.10
33. Wenba-NLU (Wuhan)                           software1        0.85
</pre>



## PUD treebanks only

Macro-average LAS of the 14 PUD treebanks (additional parallel test sets): ar_pud, cs_pud, de_pud, en_pud, es_pud, fi_pud, fr_pud, hi_pud, it_pud, ja_pud, pt_pud, ru_pud, sv_pud, tr_pud.
These are languages for which there exists at least one big training treebank.
However, these test sets have been produced separately and their domain may differ.

<pre>
 1. Stanford (Stanford)                         software1       73.73
 2. C2L2 (Ithaca)                               software5       71.49
 3. IMS (Stuttgart)                             software2       71.31
 4. LATTICE (Paris)                             software7       70.77
 5. NAIST SATO (Nara)                           software1       69.83
 6. Koç University (İstanbul)                   software3       69.76
 7. HIT-SCIR (Harbin)                           software4       69.51
 8. MQuni (Sydney)                              software2       69.28
 9. ÚFAL – UDPipe 1.2 (Praha)                   software1       69.00
10. UParse (Edinburgh)                          software1       68.91
11. Orange – Deskiñ (Lannion)                   software1       68.64
12. TurkuNLP (Turku)                            software1       68.56
13. BASELINE UDPipe 1.1 (Praha)                 software2       68.33
14. naistCL (Nara)                              software1       68.25
15. fbaml (Palo Alto)                           software1       68.21
16. darc (Tübingen)                             software1       67.96
17. IIT Kharagpur (Kharagpur)                   software3       67.42
18. RACAI (București)                           software1       67.12
19. CLCL (Genève)                               software2       66.60
20. Uppsala (Uppsala)                           software1       66.37
21. Wanghao-ftd-SJTU (Shanghai)                 software2       65.55
22. METU (Ankara)                               software2       65.30
23. UALING (Tucson)                             software1       64.29
24. Mengest (Shanghai)                          software1       63.68
25. ParisNLP (Paris)                            software1       63.17
26. LIMSI-LIPN (Paris)                          software2       62.24
27. LyS-FASTPARSE (A Coruña)                    software5       60.93
28. OpenU NLP Lab (Ra'anana)                    software6       55.83
29. TRL (Tokyo)                                 software1       46.82
30. MetaRomance (Santiago de Compostela)        software1       38.47
31. UT (Tartu)                                  software1       17.69
32. ECNU (Shanghai)                             software1        4.42
33. Wenba-NLU (Wuhan)                           software1        0.00
</pre>



## Small treebanks only

Macro-average LAS of the 8 small treebanks: fr_partut, ga, gl_treegal, kk, la, sl_sst, ug, uk.
These treebanks lack development data and some of them have very little training data (especially Uyghur and Kazakh).

<pre>
 1. C2L2 (Ithaca)                               software5       61.49
 2. Stanford (Stanford)                         software1       61.02
 3. IMS (Stuttgart)                             software2       58.76
 4. LATTICE (Paris)                             software7       54.78
 5. HIT-SCIR (Harbin)                           software4       54.77
 6. fbaml (Palo Alto)                           software1       54.64
 7. RACAI (București)                           software1       54.25
 8. TurkuNLP (Turku)                            software1       54.18
 9. ÚFAL – UDPipe 1.2 (Praha)                   software1       53.75
10. NAIST SATO (Nara)                           software1       53.52
11. Koç University (İstanbul)                   software3       53.36
12. darc (Tübingen)                             software1       52.46
13. UALING (Tucson)                             software1       52.27
14. Wanghao-ftd-SJTU (Shanghai)                 software2       52.13
15. BASELINE UDPipe 1.1 (Praha)                 software2       51.80
16. LIMSI-LIPN (Paris)                          software2       51.71
17. MQuni (Sydney)                              software2       51.58
18. UParse (Edinburgh)                          software1       51.34
19. naistCL (Nara)                              software1       49.81
20. LyS-FASTPARSE (A Coruña)                    software5       49.20
21. ParisNLP (Paris)                            software1       48.43
22. IIT Kharagpur (Kharagpur)                   software3       48.33
23. Orange – Deskiñ (Lannion)                   software1       45.51
24. Uppsala (Uppsala)                           software1       43.53
25. OpenU NLP Lab (Ra'anana)                    software6       38.53
26. Mengest (Shanghai)                          software1       33.88
27. TRL (Tokyo)                                 software1       33.69
28. METU (Ankara)                               software2       30.84
29. MetaRomance (Santiago de Compostela)        software1       29.43
30. CLCL (Genève)                               software2        6.64
31. UT (Tartu)                                  software1        4.82
32. ECNU (Shanghai)                             software1        1.17
33. Wenba-NLU (Wuhan)                           software1        0.00
</pre>



## Surprise languages only

Macro-average LAS of the 4 surprise language treebanks: bxr, hsb, kmr, sme.

<pre>
 1. C2L2 (Ithaca)                               software5       47.54
 2. IMS (Stuttgart)                             software2       45.32
 3. HIT-SCIR (Harbin)                           software4       42.64
 4. Stanford (Stanford)                         software1       40.57
 5. ParisNLP (Paris)                            software1       39.22
 6. UParse (Edinburgh)                          software1       39.17
 7. Koç University (İstanbul)                   software3       38.81
 8. Orange – Deskiñ (Lannion)                   software1       38.72
 9. LIMSI-LIPN (Paris)                          software2       37.57
10. IIT Kharagpur (Kharagpur)                   software3       37.16
11. BASELINE UDPipe 1.1 (Praha)                 software2       37.07
12. LATTICE (Paris)                             software7       36.93
13. LyS-FASTPARSE (A Coruña)                    software5       36.45
14. ÚFAL – UDPipe 1.2 (Praha)                   software1       35.96
15. OpenU NLP Lab (Ra'anana)                    software6       34.68
16. UALING (Tucson)                             software1       34.57
17. Wanghao-ftd-SJTU (Shanghai)                 software2       34.49
18. darc (Tübingen)                             software1       34.47
19. naistCL (Nara)                              software1       32.01
20. CLCL (Genève)                               software2       29.32
21. RACAI (București)                           software1       28.90
22. NAIST SATO (Nara)                           software1       28.81
23. Uppsala (Uppsala)                           software1       23.46
24. fbaml (Palo Alto)                           software1       21.15
25. MetaRomance (Santiago de Compostela)        software1       21.06
26. TurkuNLP (Turku)                            software1       20.52
27. METU (Ankara)                               software2       19.39
28. MQuni (Sydney)                              software2       14.48
29. TRL (Tokyo)                                 software1       11.77
30. Mengest (Shanghai)                          software1       11.31
31. ECNU (Shanghai)                             software1        3.90
32. Wenba-NLU (Wuhan)                           software1        0.00
33. UT (Tartu)                                  software1        0.00
</pre>



## Per treebank LAS



### ar

<pre>
 1. IMS (Stuttgart)                         	software2	72.90
 2. Stanford (Stanford)                     	software1	71.96
 3. C2L2 (Ithaca)                           	software5	70.70
 4. RACAI (București)                       	software1	69.32
 5. HIT-SCIR (Harbin)                       	software4	69.12
 6. LATTICE (Paris)                         	software7	68.54
 7. MQuni (Sydney)                          	software2	68.46
 8. NAIST SATO (Nara)                       	software1	67.78
 9. Orange – Deskiñ (Lannion)               	software1	67.26
10. LyS-FASTPARSE (A Coruña)                	software5	66.54
11. UParse (Edinburgh)                      	software1	66.35
12. naistCL (Nara)                          	software1	66.15
13. Koç University (İstanbul)               	software3	66.14
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	66.06
15. Uppsala (Uppsala)                       	software1	65.96
16. LIMSI-LIPN (Paris)                      	software2	65.86
17. TurkuNLP (Turku)                        	software1	65.74
18. Mengest (Shanghai)                      	software1	65.65
19. darc (Tübingen)                         	software1	65.49
20. BASELINE UDPipe 1.1 (Praha)             	software2	65.30
21. fbaml (Palo Alto)                       	software1	64.89
22. IIT Kharagpur (Kharagpur)               	software3	64.37
23. CLCL (Genève)                           	software1	64.17
24. METU (Ankara)                           	software2	63.81
25. Wanghao-ftd-SJTU (Shanghai)             	software2	62.29
26. UALING (Tucson)                         	software1	61.86
27. ParisNLP (Paris)                        	software1	56.72
28. OpenU NLP Lab (Ra'anana)                	software6	45.01
29. TRL (Tokyo)                             	software1	39.98
30. MetaRomance (Santiago de Compostela)    	software1	29.58
31. Wenba-NLU (Wuhan)                       	software1	 0.14
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ar_pud

<pre>
 1. IMS (Stuttgart)                         	software2	49.94
 2. Stanford (Stanford)                     	software1	49.50
 3. C2L2 (Ithaca)                           	software5	49.03
 4. RACAI (București)                       	software1	48.73
 5. HIT-SCIR (Harbin)                       	software4	48.01
 6. Uppsala (Uppsala)                       	software1	47.34
 7. LATTICE (Paris)                         	software7	47.13
 8. MQuni (Sydney)                          	software2	46.89
 9. NAIST SATO (Nara)                       	software1	45.56
10. UParse (Edinburgh)                      	software1	45.30
11. LyS-FASTPARSE (A Coruña)                	software5	45.12
12. Koç University (İstanbul)               	software3	44.97
13. Orange – Deskiñ (Lannion)               	software1	44.77
14. naistCL (Nara)                          	software1	44.51
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	44.34
16. fbaml (Palo Alto)                       	software1	44.31
17. darc (Tübingen)                         	software1	44.10
18. LIMSI-LIPN (Paris)                      	software2	43.91
19. Mengest (Shanghai)                      	software1	43.70
20. IIT Kharagpur (Kharagpur)               	software3	43.37
21. BASELINE UDPipe 1.1 (Praha)             	software2	43.14
22. TRL (Tokyo)                             	software1	42.76
23. ParisNLP (Paris)                        	software1	42.73
24. METU (Ankara)                           	software2	42.68
25. CLCL (Genève)                           	software1	42.61
26. UALING (Tucson)                         	software1	42.57
27. TurkuNLP (Turku)                        	software1	42.34
28. Wanghao-ftd-SJTU (Shanghai)             	software2	40.81
29. OpenU NLP Lab (Ra'anana)                	software6	31.84
30. MetaRomance (Santiago de Compostela)    	software1	28.32
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### bg

<pre>
 1. Stanford (Stanford)                     	software1	89.81
 2. C2L2 (Ithaca)                           	software5	88.39
 3. IMS (Stuttgart)                         	software2	87.65
 4. HIT-SCIR (Harbin)                       	software4	86.73
 5. NAIST SATO (Nara)                       	software1	85.97
 6. LyS-FASTPARSE (A Coruña)                	software5	85.76
 7. LATTICE (Paris)                         	software7	85.60
 8. Orange – Deskiñ (Lannion)               	software1	85.06
 9. Koç University (İstanbul)               	software3	84.95
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	84.92
11. TurkuNLP (Turku)                        	software1	84.85
12. darc (Tübingen)                         	software1	84.51
13. Mengest (Shanghai)                      	software1	84.28
14. fbaml (Palo Alto)                       	software1	83.89
15. UParse (Edinburgh)                      	software1	83.64
16. BASELINE UDPipe 1.1 (Praha)             	software2	83.64
17. IIT Kharagpur (Kharagpur)               	software3	83.50
18. CLCL (Genève)                           	software1	83.50
19. LIMSI-LIPN (Paris)                      	software2	83.22
20. naistCL (Nara)                          	software1	83.19
21. MQuni (Sydney)                          	software2	83.16
22. Wanghao-ftd-SJTU (Shanghai)             	software2	82.82
23. RACAI (București)                       	software1	82.47
24. UALING (Tucson)                         	software1	82.43
25. UT (Tartu)                              	software1	82.36
26. METU (Ankara)                           	software2	82.07
27. Uppsala (Uppsala)                       	software1	81.25
28. OpenU NLP Lab (Ra'anana)                	software6	74.23
29. ParisNLP (Paris)                        	software1	74.15
30. TRL (Tokyo)                             	software1	53.39
31. MetaRomance (Santiago de Compostela)    	software1	44.45
32. Wenba-NLU (Wuhan)                       	software1	 1.98
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### bxr

<pre>
 1. IMS (Stuttgart)                         	software2	32.24
 2. C2L2 (Ithaca)                           	software5	31.98
 3. BASELINE UDPipe 1.1 (Praha)             	software2	31.50
 4. Stanford (Stanford)                     	software1	30.00
 5. LyS-FASTPARSE (A Coruña)                	software5	28.65
 6. ParisNLP (Paris)                        	software1	28.55
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	28.11
 8. HIT-SCIR (Harbin)                       	software4	27.66
 9. NAIST SATO (Nara)                       	software1	27.20
10. LATTICE (Paris)                         	software7	27.08
11. IIT Kharagpur (Kharagpur)               	software3	26.60
12. LIMSI-LIPN (Paris)                      	software2	25.86
13. Orange – Deskiñ (Lannion)               	software1	25.25
14. Koç University (İstanbul)               	software3	24.96
15. naistCL (Nara)                          	software1	24.08
16. CLCL (Genève)                           	software2	22.59
17. OpenU NLP Lab (Ra'anana)                	software6	22.32
18. RACAI (București)                       	software1	21.66
19. UParse (Edinburgh)                      	software1	21.63
20. ÚFAL – UDPipe 1.2 (Praha)               	software1	21.58
21. UALING (Tucson)                         	software1	19.15
22. METU (Ankara)                           	software2	18.18
23. Uppsala (Uppsala)                       	software1	17.14
24. fbaml (Palo Alto)                       	software1	17.08
25. darc (Tübingen)                         	software1	15.61
26. TurkuNLP (Turku)                        	software1	14.22
27. TRL (Tokyo)                             	software1	14.02
28. MQuni (Sydney)                          	software2	13.71
29. Mengest (Shanghai)                      	software1	12.44
30. ECNU (Shanghai)                         	software1	 5.78
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ca

<pre>
 1. Stanford (Stanford)                     	software1	90.70
 2. HIT-SCIR (Harbin)                       	software4	88.27
 3. C2L2 (Ithaca)                           	software5	88.09
 4. IMS (Stuttgart)                         	software2	87.74
 5. NAIST SATO (Nara)                       	software1	87.47
 6. LATTICE (Paris)                         	software7	86.83
 7. UParse (Edinburgh)                      	software1	86.80
 8. Mengest (Shanghai)                      	software1	86.26
 9. Orange – Deskiñ (Lannion)               	software1	86.24
10. Koç University (İstanbul)               	software3	86.09
11. TurkuNLP (Turku)                        	software1	85.64
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	85.53
13. MQuni (Sydney)                          	software2	85.50
14. Uppsala (Uppsala)                       	software1	85.42
15. darc (Tübingen)                         	software1	85.39
16. LIMSI-LIPN (Paris)                      	software2	85.39
17. BASELINE UDPipe 1.1 (Praha)             	software2	85.39
18. LyS-FASTPARSE (A Coruña)                	software5	85.37
19. fbaml (Palo Alto)                       	software1	85.02
20. naistCL (Nara)                          	software1	84.93
21. IIT Kharagpur (Kharagpur)               	software3	84.01
22. RACAI (București)                       	software1	83.94
23. Wanghao-ftd-SJTU (Shanghai)             	software2	83.42
24. CLCL (Genève)                           	software2	82.83
25. METU (Ankara)                           	software2	82.43
26. ParisNLP (Paris)                        	software1	81.94
27. UALING (Tucson)                         	software1	81.93
28. OpenU NLP Lab (Ra'anana)                	software6	74.53
29. MetaRomance (Santiago de Compostela)    	software1	57.71
30. TRL (Tokyo)                             	software1	51.43
31. Wenba-NLU (Wuhan)                       	software1	 0.06
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs

<pre>
 1. Stanford (Stanford)                     	software1	90.17
 2. HIT-SCIR (Harbin)                       	software4	86.52
 3. NAIST SATO (Nara)                       	software1	86.50
 4. C2L2 (Ithaca)                           	software5	86.46
 5. IMS (Stuttgart)                         	software2	86.39
 6. Uppsala (Uppsala)                       	software1	85.88
 7. UParse (Edinburgh)                      	software1	85.24
 8. fbaml (Palo Alto)                       	software1	84.43
 9. Orange – Deskiñ (Lannion)               	software1	84.33
10. Mengest (Shanghai)                      	software1	83.85
11. LyS-FASTPARSE (A Coruña)                	software5	83.77
12. LATTICE (Paris)                         	software7	83.68
13. TurkuNLP (Turku)                        	software1	83.48
14. MQuni (Sydney)                          	software2	83.37
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	83.19
16. LIMSI-LIPN (Paris)                      	software2	82.87
17. BASELINE UDPipe 1.1 (Praha)             	software2	82.87
18. CLCL (Genève)                           	software1	82.52
19. darc (Tübingen)                         	software1	81.92
20. Koç University (İstanbul)               	software3	81.55
21. RACAI (București)                       	software1	81.14
22. IIT Kharagpur (Kharagpur)               	software3	80.19
23. naistCL (Nara)                          	software1	80.05
24. METU (Ankara)                           	software2	79.89
25. Wanghao-ftd-SJTU (Shanghai)             	software2	79.25
26. UALING (Tucson)                         	software1	78.04
27. OpenU NLP Lab (Ra'anana)                	software6	71.70
28. ParisNLP (Paris)                        	software1	71.30
29. TRL (Tokyo)                             	software1	54.81
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cac

<pre>
 1. Stanford (Stanford)                     	software1	90.43
 2. C2L2 (Ithaca)                           	software5	87.17
 3. IMS (Stuttgart)                         	software2	86.99
 4. NAIST SATO (Nara)                       	software1	86.41
 5. UParse (Edinburgh)                      	software1	85.57
 6. LATTICE (Paris)                         	software7	84.77
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	84.40
 8. TurkuNLP (Turku)                        	software1	84.28
 9. Orange – Deskiñ (Lannion)               	software1	83.98
10. HIT-SCIR (Harbin)                       	software4	83.87
11. Uppsala (Uppsala)                       	software1	83.66
12. MQuni (Sydney)                          	software2	83.45
13. fbaml (Palo Alto)                       	software1	83.27
14. Mengest (Shanghai)                      	software1	83.22
15. Koç University (İstanbul)               	software3	82.91
16. LyS-FASTPARSE (A Coruña)                	software5	82.71
17. LIMSI-LIPN (Paris)                      	software2	82.46
18. BASELINE UDPipe 1.1 (Praha)             	software2	82.46
19. RACAI (București)                       	software1	81.95
20. naistCL (Nara)                          	software1	81.81
21. darc (Tübingen)                         	software1	81.78
22. Wanghao-ftd-SJTU (Shanghai)             	software2	81.35
23. CLCL (Genève)                           	software1	81.35
24. IIT Kharagpur (Kharagpur)               	software3	81.01
25. UALING (Tucson)                         	software1	79.59
26. METU (Ankara)                           	software2	79.52
27. OpenU NLP Lab (Ra'anana)                	software6	74.33
28. ParisNLP (Paris)                        	software1	73.62
29. TRL (Tokyo)                             	software1	57.59
30. MetaRomance (Santiago de Compostela)    	software1	42.41
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cltt

<pre>
 1. C2L2 (Ithaca)                           	software5	85.82
 2. Stanford (Stanford)                     	software1	82.56
 3. HIT-SCIR (Harbin)                       	software4	81.89
 4. IMS (Stuttgart)                         	software2	80.67
 5. NAIST SATO (Nara)                       	software1	77.14
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.69
 7. fbaml (Palo Alto)                       	software1	76.08
 8. LATTICE (Paris)                         	software7	75.45
 9. MQuni (Sydney)                          	software2	73.92
10. Koç University (İstanbul)               	software3	73.88
11. TurkuNLP (Turku)                        	software1	73.83
12. darc (Tübingen)                         	software1	73.57
13. LIMSI-LIPN (Paris)                      	software2	73.49
14. Orange – Deskiñ (Lannion)               	software1	72.99
15. IIT Kharagpur (Kharagpur)               	software3	72.67
16. UALING (Tucson)                         	software1	71.86
17. OpenU NLP Lab (Ra'anana)                	software6	71.68
18. UParse (Edinburgh)                      	software1	71.64
19. BASELINE UDPipe 1.1 (Praha)             	software2	71.64
20. Wanghao-ftd-SJTU (Shanghai)             	software2	71.60
21. naistCL (Nara)                          	software1	69.59
22. CLCL (Genève)                           	software1	69.16
23. LyS-FASTPARSE (A Coruña)                	software5	68.92
24. METU (Ankara)                           	software2	68.71
25. Mengest (Shanghai)                      	software1	68.42
26. RACAI (București)                       	software1	68.36
27. Uppsala (Uppsala)                       	software1	59.84
28. ParisNLP (Paris)                        	software1	58.65
29. TRL (Tokyo)                             	software1	48.38
30. MetaRomance (Santiago de Compostela)    	software1	37.99
31. Wenba-NLU (Wuhan)                       	software1	 0.60
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_pud

<pre>
 1. Stanford (Stanford)                     	software1	84.42
 2. NAIST SATO (Nara)                       	software1	82.30
 3. C2L2 (Ithaca)                           	software5	82.23
 4. UParse (Edinburgh)                      	software1	81.06
 5. IMS (Stuttgart)                         	software2	81.00
 6. LATTICE (Paris)                         	software7	80.86
 7. HIT-SCIR (Harbin)                       	software4	80.75
 8. Mengest (Shanghai)                      	software1	80.44
 9. Uppsala (Uppsala)                       	software1	80.21
10. LyS-FASTPARSE (A Coruña)                	software5	80.13
11. TurkuNLP (Turku)                        	software1	80.02
12. LIMSI-LIPN (Paris)                      	software2	79.80
13. BASELINE UDPipe 1.1 (Praha)             	software2	79.80
14. fbaml (Palo Alto)                       	software1	79.76
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.67
16. darc (Tübingen)                         	software1	79.54
17. Orange – Deskiñ (Lannion)               	software1	79.49
18. CLCL (Genève)                           	software1	79.17
19. MQuni (Sydney)                          	software2	79.08
20. Koç University (İstanbul)               	software3	78.57
21. Wanghao-ftd-SJTU (Shanghai)             	software2	78.48
22. naistCL (Nara)                          	software1	77.98
23. IIT Kharagpur (Kharagpur)               	software3	77.96
24. RACAI (București)                       	software1	77.71
25. METU (Ankara)                           	software2	77.06
26. UALING (Tucson)                         	software1	76.75
27. ParisNLP (Paris)                        	software1	72.05
28. OpenU NLP Lab (Ra'anana)                	software6	71.19
29. TRL (Tokyo)                             	software1	58.02
30. MetaRomance (Santiago de Compostela)    	software1	38.93
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cu

<pre>
 1. IMS (Stuttgart)                         	software2	76.84
 2. C2L2 (Ithaca)                           	software5	72.35
 3. Stanford (Stanford)                     	software1	71.84
 4. LyS-FASTPARSE (A Coruña)                	software5	67.21
 5. RACAI (București)                       	software1	67.12
 6. fbaml (Palo Alto)                       	software1	66.91
 7. darc (Tübingen)                         	software1	66.37
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	66.29
 9. HIT-SCIR (Harbin)                       	software4	65.80
10. LIMSI-LIPN (Paris)                      	software2	65.64
11. TurkuNLP (Turku)                        	software1	65.43
12. NAIST SATO (Nara)                       	software1	65.13
13. IIT Kharagpur (Kharagpur)               	software3	64.42
14. Orange – Deskiñ (Lannion)               	software1	64.26
15. ParisNLP (Paris)                        	software1	63.64
16. UT (Tartu)                              	software1	62.95
17. UParse (Edinburgh)                      	software1	62.76
18. BASELINE UDPipe 1.1 (Praha)             	software2	62.76
19. Wanghao-ftd-SJTU (Shanghai)             	software2	62.75
20. CLCL (Genève)                           	software1	62.45
21. MQuni (Sydney)                          	software2	62.20
22. UALING (Tucson)                         	software1	61.35
23. LATTICE (Paris)                         	software7	60.81
24. METU (Ankara)                           	software2	60.33
25. naistCL (Nara)                          	software1	58.83
26. Koç University (İstanbul)               	software3	58.63
27. Uppsala (Uppsala)                       	software1	57.88
28. OpenU NLP Lab (Ra'anana)                	software6	56.13
29. Mengest (Shanghai)                      	software1	48.95
30. TRL (Tokyo)                             	software1	35.00
31. MetaRomance (Santiago de Compostela)    	software1	29.43
32. ECNU (Shanghai)                         	software1	 6.41
33. Wenba-NLU (Wuhan)                       	software1	 1.70
</pre>



### da

<pre>
 1. Stanford (Stanford)                     	software1	82.97
 2. C2L2 (Ithaca)                           	software5	81.55
 3. IMS (Stuttgart)                         	software2	79.52
 4. HIT-SCIR (Harbin)                       	software4	78.03
 5. NAIST SATO (Nara)                       	software1	77.08
 6. LATTICE (Paris)                         	software7	76.47
 7. Koç University (İstanbul)               	software3	76.39
 8. fbaml (Palo Alto)                       	software1	75.59
 9. MQuni (Sydney)                          	software2	75.29
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.28
11. LyS-FASTPARSE (A Coruña)                	software5	75.27
12. TurkuNLP (Turku)                        	software1	74.61
13. LIMSI-LIPN (Paris)                      	software2	73.85
14. ParisNLP (Paris)                        	software1	73.83
15. Wanghao-ftd-SJTU (Shanghai)             	software2	73.82
16. IIT Kharagpur (Kharagpur)               	software3	73.79
17. darc (Tübingen)                         	software1	73.67
18. Orange – Deskiñ (Lannion)               	software1	73.54
19. UParse (Edinburgh)                      	software1	73.46
20. BASELINE UDPipe 1.1 (Praha)             	software2	73.38
21. naistCL (Nara)                          	software1	73.33
22. Mengest (Shanghai)                      	software1	72.78
23. UALING (Tucson)                         	software1	72.61
24. RACAI (București)                       	software1	72.29
25. Uppsala (Uppsala)                       	software1	70.63
26. UT (Tartu)                              	software1	70.48
27. CLCL (Genève)                           	software1	69.43
28. METU (Ankara)                           	software2	68.09
29. OpenU NLP Lab (Ra'anana)                	software6	65.30
30. TRL (Tokyo)                             	software1	41.01
31. MetaRomance (Santiago de Compostela)    	software1	40.06
32. ECNU (Shanghai)                         	software1	 5.74
33. Wenba-NLU (Wuhan)                       	software1	 0.28
</pre>



### de

<pre>
 1. Stanford (Stanford)                     	software1	80.71
 2. C2L2 (Ithaca)                           	software5	77.17
 3. IMS (Stuttgart)                         	software2	75.47
 4. LATTICE (Paris)                         	software7	75.09
 5. HIT-SCIR (Harbin)                       	software4	74.79
 6. fbaml (Palo Alto)                       	software1	74.26
 7. NAIST SATO (Nara)                       	software1	74.04
 8. MQuni (Sydney)                          	software2	73.41
 9. Orange – Deskiñ (Lannion)               	software1	73.38
10. Uppsala (Uppsala)                       	software1	72.61
11. Koç University (İstanbul)               	software3	72.44
12. Mengest (Shanghai)                      	software1	71.49
13. naistCL (Nara)                          	software1	71.07
14. LIMSI-LIPN (Paris)                      	software2	70.89
15. UParse (Edinburgh)                      	software1	70.09
16. CLCL (Genève)                           	software1	69.59
17. TurkuNLP (Turku)                        	software1	69.32
18. RACAI (București)                       	software1	69.14
19. BASELINE UDPipe 1.1 (Praha)             	software2	69.11
20. ÚFAL – UDPipe 1.2 (Praha)               	software1	68.61
21. ParisNLP (Paris)                        	software1	68.45
22. LyS-FASTPARSE (A Coruña)                	software5	68.35
23. darc (Tübingen)                         	software1	68.02
24. METU (Ankara)                           	software2	67.97
25. IIT Kharagpur (Kharagpur)               	software3	67.80
26. Wanghao-ftd-SJTU (Shanghai)             	software2	66.18
27. UALING (Tucson)                         	software1	66.00
28. OpenU NLP Lab (Ra'anana)                	software6	48.05
29. TRL (Tokyo)                             	software1	43.23
30. MetaRomance (Santiago de Compostela)    	software1	36.09
31. Wenba-NLU (Wuhan)                       	software1	 0.39
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### de_pud

<pre>
 1. Stanford (Stanford)                     	software1	74.86
 2. C2L2 (Ithaca)                           	software5	73.92
 3. IMS (Stuttgart)                         	software2	71.88
 4. LATTICE (Paris)                         	software7	71.45
 5. HIT-SCIR (Harbin)                       	software4	71.11
 6. Koç University (İstanbul)               	software3	70.96
 7. NAIST SATO (Nara)                       	software1	70.74
 8. Orange – Deskiñ (Lannion)               	software1	69.75
 9. MQuni (Sydney)                          	software2	69.52
10. fbaml (Palo Alto)                       	software1	69.19
11. Mengest (Shanghai)                      	software1	69.13
12. naistCL (Nara)                          	software1	68.73
13. LIMSI-LIPN (Paris)                      	software2	68.62
14. Uppsala (Uppsala)                       	software1	68.04
15. CLCL (Genève)                           	software1	67.76
16. UParse (Edinburgh)                      	software1	67.36
17. TurkuNLP (Turku)                        	software1	66.78
18. BASELINE UDPipe 1.1 (Praha)             	software2	66.53
19. LyS-FASTPARSE (A Coruña)                	software5	66.29
20. ÚFAL – UDPipe 1.2 (Praha)               	software1	66.05
21. METU (Ankara)                           	software2	65.94
22. IIT Kharagpur (Kharagpur)               	software3	65.27
23. RACAI (București)                       	software1	65.24
24. ParisNLP (Paris)                        	software1	65.16
25. darc (Tübingen)                         	software1	65.09
26. Wanghao-ftd-SJTU (Shanghai)             	software2	64.26
27. UALING (Tucson)                         	software1	63.65
28. OpenU NLP Lab (Ra'anana)                	software6	44.05
29. TRL (Tokyo)                             	software1	43.44
30. MetaRomance (Santiago de Compostela)    	software1	35.58
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### el

<pre>
 1. Stanford (Stanford)                     	software1	87.38
 2. C2L2 (Ithaca)                           	software5	86.90
 3. IMS (Stuttgart)                         	software2	84.96
 4. HIT-SCIR (Harbin)                       	software4	82.82
 5. NAIST SATO (Nara)                       	software1	81.79
 6. LyS-FASTPARSE (A Coruña)                	software5	81.43
 7. Koç University (İstanbul)               	software3	81.35
 8. LATTICE (Paris)                         	software7	81.13
 9. MQuni (Sydney)                          	software2	80.90
10. fbaml (Palo Alto)                       	software1	80.79
11. Orange – Deskiñ (Lannion)               	software1	80.69
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.67
13. TurkuNLP (Turku)                        	software1	79.93
14. IIT Kharagpur (Kharagpur)               	software3	79.52
15. LIMSI-LIPN (Paris)                      	software2	79.38
16. UParse (Edinburgh)                      	software1	79.26
17. BASELINE UDPipe 1.1 (Praha)             	software2	79.26
18. RACAI (București)                       	software1	79.08
19. darc (Tübingen)                         	software1	79.05
20. naistCL (Nara)                          	software1	78.76
21. Mengest (Shanghai)                      	software1	78.72
22. UALING (Tucson)                         	software1	78.43
23. CLCL (Genève)                           	software1	77.80
24. ParisNLP (Paris)                        	software1	77.00
25. METU (Ankara)                           	software2	76.71
26. Wanghao-ftd-SJTU (Shanghai)             	software2	76.65
27. OpenU NLP Lab (Ra'anana)                	software6	73.41
28. UT (Tartu)                              	software1	73.31
29. Uppsala (Uppsala)                       	software1	72.77
30. TRL (Tokyo)                             	software1	52.44
31. MetaRomance (Santiago de Compostela)    	software1	46.73
32. ECNU (Shanghai)                         	software1	 1.32
33. Wenba-NLU (Wuhan)                       	software1	 0.19
</pre>



### en

<pre>
 1. Stanford (Stanford)                     	software1	82.23
 2. HIT-SCIR (Harbin)                       	software4	79.94
 3. C2L2 (Ithaca)                           	software5	79.64
 4. LATTICE (Paris)                         	software7	78.91
 5. IMS (Stuttgart)                         	software2	78.71
 6. NAIST SATO (Nara)                       	software1	77.93
 7. fbaml (Palo Alto)                       	software1	77.57
 8. Orange – Deskiñ (Lannion)               	software1	77.51
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.25
10. MQuni (Sydney)                          	software2	76.81
11. TurkuNLP (Turku)                        	software1	76.68
12. UParse (Edinburgh)                      	software1	76.42
13. Mengest (Shanghai)                      	software1	76.42
14. LyS-FASTPARSE (A Coruña)                	software5	76.00
15. Koç University (İstanbul)               	software3	75.96
16. Uppsala (Uppsala)                       	software1	75.88
17. LIMSI-LIPN (Paris)                      	software2	75.84
18. BASELINE UDPipe 1.1 (Praha)             	software2	75.84
19. darc (Tübingen)                         	software1	75.83
20. IIT Kharagpur (Kharagpur)               	software3	75.59
21. naistCL (Nara)                          	software1	75.27
22. CLCL (Genève)                           	software1	75.09
23. Wanghao-ftd-SJTU (Shanghai)             	software2	74.60
24. RACAI (București)                       	software1	74.44
25. METU (Ankara)                           	software2	73.40
26. UALING (Tucson)                         	software1	72.84
27. ParisNLP (Paris)                        	software1	70.20
28. OpenU NLP Lab (Ra'anana)                	software6	69.53
29. TRL (Tokyo)                             	software1	49.56
30. MetaRomance (Santiago de Compostela)    	software1	36.56
31. Wenba-NLU (Wuhan)                       	software1	 0.75
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_lines

<pre>
 1. Stanford (Stanford)                     	software1	82.09
 2. C2L2 (Ithaca)                           	software5	80.65
 3. HIT-SCIR (Harbin)                       	software4	78.73
 4. IMS (Stuttgart)                         	software2	78.25
 5. NAIST SATO (Nara)                       	software1	77.53
 6. LATTICE (Paris)                         	software7	76.17
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.92
 8. TurkuNLP (Turku)                        	software1	74.77
 9. fbaml (Palo Alto)                       	software1	74.67
10. Koç University (İstanbul)               	software3	74.39
11. IIT Kharagpur (Kharagpur)               	software3	73.98
12. MQuni (Sydney)                          	software2	73.77
13. LyS-FASTPARSE (A Coruña)                	software5	73.47
14. Orange – Deskiñ (Lannion)               	software1	73.36
15. UParse (Edinburgh)                      	software1	73.28
16. darc (Tübingen)                         	software1	72.98
17. LIMSI-LIPN (Paris)                      	software2	72.94
18. BASELINE UDPipe 1.1 (Praha)             	software2	72.94
19. naistCL (Nara)                          	software1	72.83
20. Wanghao-ftd-SJTU (Shanghai)             	software2	72.78
21. CLCL (Genève)                           	software1	72.68
22. Mengest (Shanghai)                      	software1	72.66
23. UALING (Tucson)                         	software1	72.55
24. RACAI (București)                       	software1	70.97
25. METU (Ankara)                           	software2	70.36
26. OpenU NLP Lab (Ra'anana)                	software6	68.09
27. UT (Tartu)                              	software1	67.97
28. Uppsala (Uppsala)                       	software1	67.52
29. ParisNLP (Paris)                        	software1	64.77
30. TRL (Tokyo)                             	software1	52.49
31. ECNU (Shanghai)                         	software1	38.68
32. MetaRomance (Santiago de Compostela)    	software1	34.87
33. Wenba-NLU (Wuhan)                       	software1	 0.47
</pre>



### en_partut

<pre>
 1. C2L2 (Ithaca)                           	software5	84.46
 2. Stanford (Stanford)                     	software1	82.54
 3. HIT-SCIR (Harbin)                       	software4	81.98
 4. LATTICE (Paris)                         	software7	80.45
 5. IMS (Stuttgart)                         	software2	79.37
 6. NAIST SATO (Nara)                       	software1	79.10
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.89
 8. fbaml (Palo Alto)                       	software1	76.68
 9. MQuni (Sydney)                          	software2	76.02
10. Orange – Deskiñ (Lannion)               	software1	75.78
11. Koç University (İstanbul)               	software3	75.71
12. LyS-FASTPARSE (A Coruña)                	software5	74.50
13. TurkuNLP (Turku)                        	software1	74.48
14. IIT Kharagpur (Kharagpur)               	software3	74.47
15. darc (Tübingen)                         	software1	74.39
16. Wanghao-ftd-SJTU (Shanghai)             	software2	73.98
17. Mengest (Shanghai)                      	software1	73.74
18. UParse (Edinburgh)                      	software1	73.64
19. BASELINE UDPipe 1.1 (Praha)             	software2	73.64
20. LIMSI-LIPN (Paris)                      	software2	73.60
21. UALING (Tucson)                         	software1	73.59
22. naistCL (Nara)                          	software1	73.00
23. RACAI (București)                       	software1	72.69
24. METU (Ankara)                           	software2	72.38
25. CLCL (Genève)                           	software1	71.78
26. ParisNLP (Paris)                        	software1	69.29
27. OpenU NLP Lab (Ra'anana)                	software6	68.15
28. Uppsala (Uppsala)                       	software1	63.55
29. TRL (Tokyo)                             	software1	54.50
30. MetaRomance (Santiago de Compostela)    	software1	45.13
31. Wenba-NLU (Wuhan)                       	software1	 0.10
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_pud

<pre>
 1. Stanford (Stanford)                     	software1	85.51
 2. LATTICE (Paris)                         	software7	82.38
 3. HIT-SCIR (Harbin)                       	software4	81.86
 4. IMS (Stuttgart)                         	software2	81.55
 5. NAIST SATO (Nara)                       	software1	81.18
 6. MQuni (Sydney)                          	software2	81.01
 7. fbaml (Palo Alto)                       	software1	79.88
 8. Orange – Deskiñ (Lannion)               	software1	79.67
 9. TurkuNLP (Turku)                        	software1	79.61
10. UParse (Edinburgh)                      	software1	79.54
11. Koç University (İstanbul)               	software3	79.51
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.21
13. Mengest (Shanghai)                      	software1	79.02
14. LIMSI-LIPN (Paris)                      	software2	78.95
15. BASELINE UDPipe 1.1 (Praha)             	software2	78.95
16. LyS-FASTPARSE (A Coruña)                	software5	78.79
17. naistCL (Nara)                          	software1	78.57
18. CLCL (Genève)                           	software1	78.22
19. IIT Kharagpur (Kharagpur)               	software3	78.21
20. Wanghao-ftd-SJTU (Shanghai)             	software2	77.82
21. RACAI (București)                       	software1	77.79
22. darc (Tübingen)                         	software1	77.67
23. C2L2 (Ithaca)                           	software5	76.56
24. UALING (Tucson)                         	software1	76.42
25. UT (Tartu)                              	software1	76.07
26. METU (Ankara)                           	software2	75.97
27. ParisNLP (Paris)                        	software1	75.87
28. Uppsala (Uppsala)                       	software1	75.61
29. OpenU NLP Lab (Ra'anana)                	software6	73.47
30. TRL (Tokyo)                             	software1	53.94
31. MetaRomance (Santiago de Compostela)    	software1	44.46
32. ECNU (Shanghai)                         	software1	34.20
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### es

<pre>
 1. Stanford (Stanford)                     	software1	87.29
 2. LATTICE (Paris)                         	software7	85.22
 3. C2L2 (Ithaca)                           	software5	85.16
 4. NAIST SATO (Nara)                       	software1	84.25
 5. HIT-SCIR (Harbin)                       	software4	84.22
 6. MQuni (Sydney)                          	software2	83.37
 7. Koç University (İstanbul)               	software3	83.34
 8. LyS-FASTPARSE (A Coruña)                	software5	83.24
 9. IMS (Stuttgart)                         	software2	83.15
10. Orange – Deskiñ (Lannion)               	software1	83.03
11. UParse (Edinburgh)                      	software1	83.02
12. Uppsala (Uppsala)                       	software1	82.17
13. naistCL (Nara)                          	software1	81.99
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	81.95
15. TurkuNLP (Turku)                        	software1	81.79
16. fbaml (Palo Alto)                       	software1	81.53
17. LIMSI-LIPN (Paris)                      	software2	81.47
18. BASELINE UDPipe 1.1 (Praha)             	software2	81.47
19. darc (Tübingen)                         	software1	81.27
20. IIT Kharagpur (Kharagpur)               	software3	80.21
21. RACAI (București)                       	software1	79.97
22. CLCL (Genève)                           	software2	79.96
23. Wanghao-ftd-SJTU (Shanghai)             	software2	79.83
24. UALING (Tucson)                         	software1	78.73
25. ParisNLP (Paris)                        	software1	77.94
26. METU (Ankara)                           	software2	77.54
27. Mengest (Shanghai)                      	software1	75.41
28. OpenU NLP Lab (Ra'anana)                	software6	67.89
29. MetaRomance (Santiago de Compostela)    	software1	59.80
30. TRL (Tokyo)                             	software1	57.01
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_ancora

<pre>
 1. Stanford (Stanford)                     	software1	89.99
 2. C2L2 (Ithaca)                           	software5	87.42
 3. HIT-SCIR (Harbin)                       	software4	87.39
 4. NAIST SATO (Nara)                       	software1	87.27
 5. IMS (Stuttgart)                         	software2	87.12
 6. LATTICE (Paris)                         	software7	86.87
 7. LyS-FASTPARSE (A Coruña)                	software5	86.83
 8. UParse (Edinburgh)                      	software1	86.01
 9. Koç University (İstanbul)               	software3	85.63
10. Orange – Deskiñ (Lannion)               	software1	85.57
11. MQuni (Sydney)                          	software2	85.26
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	84.95
13. Uppsala (Uppsala)                       	software1	84.60
14. naistCL (Nara)                          	software1	84.43
15. TurkuNLP (Turku)                        	software1	84.15
16. darc (Tübingen)                         	software1	84.06
17. fbaml (Palo Alto)                       	software1	83.81
18. LIMSI-LIPN (Paris)                      	software2	83.78
19. BASELINE UDPipe 1.1 (Praha)             	software2	83.78
20. IIT Kharagpur (Kharagpur)               	software3	82.63
21. Wanghao-ftd-SJTU (Shanghai)             	software2	82.23
22. RACAI (București)                       	software1	82.07
23. CLCL (Genève)                           	software2	81.26
24. UALING (Tucson)                         	software1	80.90
25. METU (Ankara)                           	software2	80.89
26. Mengest (Shanghai)                      	software1	78.64
27. ParisNLP (Paris)                        	software1	76.61
28. OpenU NLP Lab (Ra'anana)                	software6	71.34
29. MetaRomance (Santiago de Compostela)    	software1	60.99
30. TRL (Tokyo)                             	software1	55.52
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_pud

<pre>
 1. Stanford (Stanford)                     	software1	81.05
 2. C2L2 (Ithaca)                           	software5	80.50
 3. LATTICE (Paris)                         	software7	79.87
 4. NAIST SATO (Nara)                       	software1	79.66
 5. MQuni (Sydney)                          	software2	79.49
 6. UParse (Edinburgh)                      	software1	79.20
 7. Orange – Deskiñ (Lannion)               	software1	78.78
 8. Koç University (İstanbul)               	software3	78.74
 9. IMS (Stuttgart)                         	software2	78.63
10. Uppsala (Uppsala)                       	software1	78.16
11. naistCL (Nara)                          	software1	78.13
12. TurkuNLP (Turku)                        	software1	78.02
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.99
14. BASELINE UDPipe 1.1 (Praha)             	software2	77.65
15. darc (Tübingen)                         	software1	77.49
16. fbaml (Palo Alto)                       	software1	77.09
17. Wanghao-ftd-SJTU (Shanghai)             	software2	77.06
18. RACAI (București)                       	software1	76.64
19. IIT Kharagpur (Kharagpur)               	software3	76.62
20. ParisNLP (Paris)                        	software1	76.57
21. UALING (Tucson)                         	software1	76.31
22. CLCL (Genève)                           	software1	75.90
23. METU (Ankara)                           	software2	75.26
24. HIT-SCIR (Harbin)                       	software4	72.67
25. Mengest (Shanghai)                      	software1	72.61
26. LIMSI-LIPN (Paris)                      	software2	68.40
27. OpenU NLP Lab (Ra'anana)                	software6	67.15
28. MetaRomance (Santiago de Compostela)    	software1	65.49
29. TRL (Tokyo)                             	software1	58.40
30. LyS-FASTPARSE (A Coruña)                	software5	53.73
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### et

<pre>
 1. Stanford (Stanford)                     	software1	71.65
 2. C2L2 (Ithaca)                           	software5	69.71
 3. IMS (Stuttgart)                         	software2	67.60
 4. HIT-SCIR (Harbin)                       	software4	65.10
 5. LATTICE (Paris)                         	software7	62.93
 6. Koç University (İstanbul)               	software3	62.04
 7. LyS-FASTPARSE (A Coruña)                	software5	61.79
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	60.01
 9. LIMSI-LIPN (Paris)                      	software2	59.80
10. TurkuNLP (Turku)                        	software1	59.79
11. darc (Tübingen)                         	software1	59.75
12. IIT Kharagpur (Kharagpur)               	software3	59.24
13. Orange – Deskiñ (Lannion)               	software1	58.98
14. UALING (Tucson)                         	software1	58.85
15. BASELINE UDPipe 1.1 (Praha)             	software2	58.79
16. UParse (Edinburgh)                      	software1	58.78
17. RACAI (București)                       	software1	58.74
18. fbaml (Palo Alto)                       	software1	58.48
19. Wanghao-ftd-SJTU (Shanghai)             	software2	57.99
20. MQuni (Sydney)                          	software2	57.85
21. NAIST SATO (Nara)                       	software1	57.72
22. ParisNLP (Paris)                        	software1	56.00
23. naistCL (Nara)                          	software1	55.59
24. Mengest (Shanghai)                      	software1	55.40
25. UT (Tartu)                              	software1	54.13
26. CLCL (Genève)                           	software1	52.67
27. METU (Ankara)                           	software2	52.08
28. Uppsala (Uppsala)                       	software1	49.01
29. OpenU NLP Lab (Ra'anana)                	software6	45.05
30. TRL (Tokyo)                             	software1	34.05
31. MetaRomance (Santiago de Compostela)    	software1	23.41
32. ECNU (Shanghai)                         	software1	 3.42
33. Wenba-NLU (Wuhan)                       	software1	 1.62
</pre>



### eu

<pre>
 1. Stanford (Stanford)                     	software1	81.44
 2. C2L2 (Ithaca)                           	software5	79.61
 3. IMS (Stuttgart)                         	software2	77.97
 4. HIT-SCIR (Harbin)                       	software4	73.85
 5. LyS-FASTPARSE (A Coruña)                	software5	73.27
 6. MQuni (Sydney)                          	software2	72.49
 7. LATTICE (Paris)                         	software7	72.13
 8. Koç University (İstanbul)               	software3	71.47
 9. fbaml (Palo Alto)                       	software1	70.74
10. NAIST SATO (Nara)                       	software1	70.71
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.45
12. RACAI (București)                       	software1	70.40
13. TurkuNLP (Turku)                        	software1	70.22
14. naistCL (Nara)                          	software1	69.96
15. UParse (Edinburgh)                      	software1	69.85
16. Uppsala (Uppsala)                       	software1	69.84
17. LIMSI-LIPN (Paris)                      	software2	69.21
18. BASELINE UDPipe 1.1 (Praha)             	software2	69.15
19. IIT Kharagpur (Kharagpur)               	software3	68.85
20. darc (Tübingen)                         	software1	68.08
21. UALING (Tucson)                         	software1	66.77
22. Wanghao-ftd-SJTU (Shanghai)             	software2	66.22
23. UT (Tartu)                              	software1	65.42
24. Orange – Deskiñ (Lannion)               	software1	65.29
25. Mengest (Shanghai)                      	software1	62.89
26. CLCL (Genève)                           	software2	62.47
27. METU (Ankara)                           	software2	59.01
28. OpenU NLP Lab (Ra'anana)                	software6	56.37
29. ParisNLP (Paris)                        	software1	50.67
30. TRL (Tokyo)                             	software1	41.80
31. MetaRomance (Santiago de Compostela)    	software1	10.06
32. ECNU (Shanghai)                         	software1	 2.36
33. Wenba-NLU (Wuhan)                       	software1	 0.64
</pre>



### fa

<pre>
 1. Stanford (Stanford)                     	software1	86.31
 2. C2L2 (Ithaca)                           	software5	84.90
 3. IMS (Stuttgart)                         	software2	83.34
 4. LATTICE (Paris)                         	software7	82.63
 5. HIT-SCIR (Harbin)                       	software4	82.08
 6. NAIST SATO (Nara)                       	software1	82.01
 7. MQuni (Sydney)                          	software2	81.40
 8. Orange – Deskiñ (Lannion)               	software1	80.87
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.33
10. UParse (Edinburgh)                      	software1	79.97
11. naistCL (Nara)                          	software1	79.76
12. Koç University (İstanbul)               	software3	79.56
13. LIMSI-LIPN (Paris)                      	software2	79.24
14. BASELINE UDPipe 1.1 (Praha)             	software2	79.24
15. IIT Kharagpur (Kharagpur)               	software3	79.01
16. fbaml (Palo Alto)                       	software1	77.74
17. LyS-FASTPARSE (A Coruña)                	software5	77.68
18. darc (Tübingen)                         	software1	77.59
19. RACAI (București)                       	software1	77.45
20. TurkuNLP (Turku)                        	software1	76.54
21. UALING (Tucson)                         	software1	76.23
22. Uppsala (Uppsala)                       	software1	76.13
23. CLCL (Genève)                           	software2	75.86
24. METU (Ankara)                           	software2	75.73
25. Wanghao-ftd-SJTU (Shanghai)             	software2	75.21
26. OpenU NLP Lab (Ra'anana)                	software6	62.89
27. ParisNLP (Paris)                        	software1	61.93
28. Mengest (Shanghai)                      	software1	61.43
29. TRL (Tokyo)                             	software1	48.40
30. MetaRomance (Santiago de Compostela)    	software1	29.07
31. Wenba-NLU (Wuhan)                       	software1	 0.76
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi

<pre>
 1. Stanford (Stanford)                     	software1	85.64
 2. C2L2 (Ithaca)                           	software5	82.38
 3. IMS (Stuttgart)                         	software2	81.21
 4. HIT-SCIR (Harbin)                       	software4	77.73
 5. Koç University (İstanbul)               	software3	77.72
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.26
 7. LATTICE (Paris)                         	software7	77.11
 8. LyS-FASTPARSE (A Coruña)                	software5	76.11
 9. TurkuNLP (Turku)                        	software1	75.82
10. MQuni (Sydney)                          	software2	75.47
11. UParse (Edinburgh)                      	software1	75.35
12. naistCL (Nara)                          	software1	75.10
13. darc (Tübingen)                         	software1	74.93
14. NAIST SATO (Nara)                       	software1	74.84
15. IIT Kharagpur (Kharagpur)               	software3	74.71
16. Uppsala (Uppsala)                       	software1	74.59
17. fbaml (Palo Alto)                       	software1	74.51
18. Orange – Deskiñ (Lannion)               	software1	73.97
19. LIMSI-LIPN (Paris)                      	software2	73.75
20. BASELINE UDPipe 1.1 (Praha)             	software2	73.75
21. Wanghao-ftd-SJTU (Shanghai)             	software2	73.27
22. UALING (Tucson)                         	software1	73.06
23. RACAI (București)                       	software1	72.59
24. UT (Tartu)                              	software1	71.00
25. Mengest (Shanghai)                      	software1	69.86
26. METU (Ankara)                           	software2	66.46
27. CLCL (Genève)                           	software2	63.93
28. ParisNLP (Paris)                        	software1	60.19
29. OpenU NLP Lab (Ra'anana)                	software6	45.98
30. TRL (Tokyo)                             	software1	31.51
31. MetaRomance (Santiago de Compostela)    	software1	24.65
32. Wenba-NLU (Wuhan)                       	software1	 0.75
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### fi_ftb

<pre>
 1. Stanford (Stanford)                     	software1	86.81
 2. C2L2 (Ithaca)                           	software5	82.55
 3. IMS (Stuttgart)                         	software2	81.33
 4. LATTICE (Paris)                         	software7	79.44
 5. Orange – Deskiñ (Lannion)               	software1	78.64
 6. HIT-SCIR (Harbin)                       	software4	78.08
 7. LyS-FASTPARSE (A Coruña)                	software5	76.80
 8. CLCL (Genève)                           	software2	76.26
 9. TurkuNLP (Turku)                        	software1	75.59
10. darc (Tübingen)                         	software1	75.43
11. Koç University (İstanbul)               	software3	75.37
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.31
13. Mengest (Shanghai)                      	software1	75.13
14. NAIST SATO (Nara)                       	software1	74.42
15. MQuni (Sydney)                          	software2	74.34
16. IIT Kharagpur (Kharagpur)               	software3	74.24
17. UParse (Edinburgh)                      	software1	74.04
18. LIMSI-LIPN (Paris)                      	software2	74.04
19. BASELINE UDPipe 1.1 (Praha)             	software2	74.03
20. naistCL (Nara)                          	software1	73.04
21. UALING (Tucson)                         	software1	72.60
22. METU (Ankara)                           	software2	72.13
23. RACAI (București)                       	software1	72.09
24. Wanghao-ftd-SJTU (Shanghai)             	software2	72.08
25. fbaml (Palo Alto)                       	software1	72.08
26. Uppsala (Uppsala)                       	software1	71.85
27. OpenU NLP Lab (Ra'anana)                	software6	52.73
28. TRL (Tokyo)                             	software1	44.55
29. ParisNLP (Paris)                        	software1	40.21
30. MetaRomance (Santiago de Compostela)    	software1	23.09
31. Wenba-NLU (Wuhan)                       	software1	 2.11
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi_pud

<pre>
 1. Stanford (Stanford)                     	software1	88.47
 2. C2L2 (Ithaca)                           	software5	85.42
 3. IMS (Stuttgart)                         	software2	85.21
 4. Koç University (İstanbul)               	software3	82.37
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.86
 6. LATTICE (Paris)                         	software7	80.82
 7. UParse (Edinburgh)                      	software1	79.66
 8. TurkuNLP (Turku)                        	software1	79.61
 9. MQuni (Sydney)                          	software2	79.20
10. HIT-SCIR (Harbin)                       	software4	78.99
11. naistCL (Nara)                          	software1	78.92
12. BASELINE UDPipe 1.1 (Praha)             	software2	78.65
13. darc (Tübingen)                         	software1	78.49
14. Orange – Deskiñ (Lannion)               	software1	77.52
15. fbaml (Palo Alto)                       	software1	77.39
16. UALING (Tucson)                         	software1	77.22
17. NAIST SATO (Nara)                       	software1	77.11
18. Wanghao-ftd-SJTU (Shanghai)             	software2	76.67
19. Uppsala (Uppsala)                       	software1	76.22
20. IIT Kharagpur (Kharagpur)               	software3	76.03
21. RACAI (București)                       	software1	75.44
22. Mengest (Shanghai)                      	software1	71.77
23. METU (Ankara)                           	software2	69.47
24. CLCL (Genève)                           	software1	64.91
25. ParisNLP (Paris)                        	software1	62.41
26. OpenU NLP Lab (Ra'anana)                	software6	45.17
27. LIMSI-LIPN (Paris)                      	software2	44.99
28. LyS-FASTPARSE (A Coruña)                	software5	40.66
29. TRL (Tokyo)                             	software1	32.55
30. MetaRomance (Santiago de Compostela)    	software1	28.10
31. ECNU (Shanghai)                         	software1	 3.54
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr

<pre>
 1. Stanford (Stanford)                     	software1	85.51
 2. C2L2 (Ithaca)                           	software5	84.36
 3. IMS (Stuttgart)                         	software2	83.82
 4. LATTICE (Paris)                         	software7	82.83
 5. MQuni (Sydney)                          	software2	82.79
 6. HIT-SCIR (Harbin)                       	software4	82.67
 7. NAIST SATO (Nara)                       	software1	82.43
 8. UParse (Edinburgh)                      	software1	81.58
 9. Koç University (İstanbul)               	software3	81.30
10. LIMSI-LIPN (Paris)                      	software2	80.75
11. BASELINE UDPipe 1.1 (Praha)             	software2	80.75
12. TurkuNLP (Turku)                        	software1	80.61
13. Orange – Deskiñ (Lannion)               	software1	80.58
14. darc (Tübingen)                         	software1	80.50
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.50
16. fbaml (Palo Alto)                       	software1	80.38
17. Uppsala (Uppsala)                       	software1	80.36
18. Mengest (Shanghai)                      	software1	80.07
19. naistCL (Nara)                          	software1	79.89
20. LyS-FASTPARSE (A Coruña)                	software5	79.86
21. CLCL (Genève)                           	software2	79.85
22. IIT Kharagpur (Kharagpur)               	software3	79.21
23. Wanghao-ftd-SJTU (Shanghai)             	software2	78.88
24. RACAI (București)                       	software1	78.38
25. METU (Ankara)                           	software2	77.48
26. UALING (Tucson)                         	software1	77.30
27. ParisNLP (Paris)                        	software1	76.79
28. OpenU NLP Lab (Ra'anana)                	software6	72.10
29. TRL (Tokyo)                             	software1	54.59
30. MetaRomance (Santiago de Compostela)    	software1	54.10
31. Wenba-NLU (Wuhan)                       	software1	 0.29
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_partut

<pre>
 1. C2L2 (Ithaca)                           	software5	88.13
 2. Stanford (Stanford)                     	software1	85.05
 3. HIT-SCIR (Harbin)                       	software4	84.86
 4. IMS (Stuttgart)                         	software2	83.82
 5. LATTICE (Paris)                         	software7	83.26
 6. NAIST SATO (Nara)                       	software1	80.31
 7. Koç University (İstanbul)               	software3	80.22
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.17
 9. fbaml (Palo Alto)                       	software1	80.06
10. MQuni (Sydney)                          	software2	79.20
11. darc (Tübingen)                         	software1	78.84
12. TurkuNLP (Turku)                        	software1	78.83
13. Wanghao-ftd-SJTU (Shanghai)             	software2	78.80
14. LIMSI-LIPN (Paris)                      	software2	78.30
15. UALING (Tucson)                         	software1	78.29
16. UParse (Edinburgh)                      	software1	77.38
17. BASELINE UDPipe 1.1 (Praha)             	software2	77.38
18. naistCL (Nara)                          	software1	77.27
19. Orange – Deskiñ (Lannion)               	software1	77.26
20. RACAI (București)                       	software1	76.75
21. IIT Kharagpur (Kharagpur)               	software3	75.33
22. ParisNLP (Paris)                        	software1	75.15
23. OpenU NLP Lab (Ra'anana)                	software6	73.11
24. Mengest (Shanghai)                      	software1	72.40
25. LyS-FASTPARSE (A Coruña)                	software5	72.09
26. METU (Ankara)                           	software2	71.50
27. Uppsala (Uppsala)                       	software1	69.17
28. TRL (Tokyo)                             	software1	57.18
29. MetaRomance (Santiago de Compostela)    	software1	56.17
30. CLCL (Genève)                           	software2	17.85
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_pud

<pre>
 1. Stanford (Stanford)                     	software1	78.81
 2. C2L2 (Ithaca)                           	software5	78.25
 3. IMS (Stuttgart)                         	software2	77.60
 4. HIT-SCIR (Harbin)                       	software4	77.51
 5. LATTICE (Paris)                         	software7	76.55
 6. Koç University (İstanbul)               	software3	76.04
 7. MQuni (Sydney)                          	software2	75.69
 8. NAIST SATO (Nara)                       	software1	75.20
 9. CLCL (Genève)                           	software1	74.93
10. ParisNLP (Paris)                        	software1	74.70
11. Orange – Deskiñ (Lannion)               	software1	74.63
12. UParse (Edinburgh)                      	software1	74.44
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.19
14. TurkuNLP (Turku)                        	software1	74.17
15. Mengest (Shanghai)                      	software1	73.92
16. fbaml (Palo Alto)                       	software1	73.67
17. LIMSI-LIPN (Paris)                      	software2	73.63
18. BASELINE UDPipe 1.1 (Praha)             	software2	73.63
19. Uppsala (Uppsala)                       	software1	73.51
20. naistCL (Nara)                          	software1	73.48
21. IIT Kharagpur (Kharagpur)               	software3	73.32
22. Wanghao-ftd-SJTU (Shanghai)             	software2	73.17
23. LyS-FASTPARSE (A Coruña)                	software5	73.15
24. darc (Tübingen)                         	software1	73.06
25. RACAI (București)                       	software1	72.18
26. UALING (Tucson)                         	software1	72.03
27. METU (Ankara)                           	software2	71.15
28. OpenU NLP Lab (Ra'anana)                	software6	67.77
29. MetaRomance (Santiago de Compostela)    	software1	58.67
30. TRL (Tokyo)                             	software1	56.96
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_sequoia

<pre>
 1. C2L2 (Ithaca)                           	software5	87.31
 2. Stanford (Stanford)                     	software1	86.53
 3. IMS (Stuttgart)                         	software2	85.40
 4. HIT-SCIR (Harbin)                       	software4	85.09
 5. LATTICE (Paris)                         	software7	83.70
 6. NAIST SATO (Nara)                       	software1	83.10
 7. Koç University (İstanbul)               	software3	81.97
 8. Orange – Deskiñ (Lannion)               	software1	81.54
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	81.35
10. TurkuNLP (Turku)                        	software1	81.12
11. MQuni (Sydney)                          	software2	80.79
12. LIMSI-LIPN (Paris)                      	software2	80.55
13. fbaml (Palo Alto)                       	software1	80.30
14. IIT Kharagpur (Kharagpur)               	software3	80.26
15. BASELINE UDPipe 1.1 (Praha)             	software2	79.98
16. darc (Tübingen)                         	software1	79.44
17. UALING (Tucson)                         	software1	79.12
18. Mengest (Shanghai)                      	software1	79.00
19. Wanghao-ftd-SJTU (Shanghai)             	software2	78.93
20. OpenU NLP Lab (Ra'anana)                	software6	78.92
21. naistCL (Nara)                          	software1	78.85
22. UParse (Edinburgh)                      	software1	78.57
23. LyS-FASTPARSE (A Coruña)                	software5	77.77
24. RACAI (București)                       	software1	77.64
25. CLCL (Genève)                           	software2	76.36
26. METU (Ankara)                           	software2	75.96
27. Uppsala (Uppsala)                       	software1	74.96
28. ParisNLP (Paris)                        	software1	73.55
29. MetaRomance (Santiago de Compostela)    	software1	55.16
30. TRL (Tokyo)                             	software1	52.75
31. Wenba-NLU (Wuhan)                       	software1	 0.54
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ga

<pre>
 1. Stanford (Stanford)                     	software1	70.06
 2. C2L2 (Ithaca)                           	software5	69.26
 3. IMS (Stuttgart)                         	software2	69.22
 4. fbaml (Palo Alto)                       	software1	66.49
 5. RACAI (București)                       	software1	65.65
 6. LATTICE (Paris)                         	software7	64.39
 7. TurkuNLP (Turku)                        	software1	64.25
 8. Koç University (İstanbul)               	software3	63.22
 9. Orange – Deskiñ (Lannion)               	software1	63.10
10. darc (Tübingen)                         	software1	62.97
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	62.87
12. NAIST SATO (Nara)                       	software1	62.25
13. UALING (Tucson)                         	software1	62.20
14. LIMSI-LIPN (Paris)                      	software2	61.94
15. HIT-SCIR (Harbin)                       	software4	61.62
16. UParse (Edinburgh)                      	software1	61.52
17. MQuni (Sydney)                          	software2	61.52
18. BASELINE UDPipe 1.1 (Praha)             	software2	61.52
19. naistCL (Nara)                          	software1	61.48
20. Wanghao-ftd-SJTU (Shanghai)             	software2	61.43
21. IIT Kharagpur (Kharagpur)               	software3	58.45
22. LyS-FASTPARSE (A Coruña)                	software5	58.05
23. ParisNLP (Paris)                        	software1	56.35
24. Mengest (Shanghai)                      	software1	55.07
25. OpenU NLP Lab (Ra'anana)                	software6	54.58
26. Uppsala (Uppsala)                       	software1	52.81
27. TRL (Tokyo)                             	software1	43.80
28. MetaRomance (Santiago de Compostela)    	software1	26.71
29. METU (Ankara)                           	software2	13.26
30. CLCL (Genève)                           	software2	 4.30
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### gl

<pre>
 1. Stanford (Stanford)                     	software1	83.23
 2. C2L2 (Ithaca)                           	software5	83.22
 3. IMS (Stuttgart)                         	software2	81.60
 4. LATTICE (Paris)                         	software7	80.68
 5. Koç University (İstanbul)               	software3	80.27
 6. HIT-SCIR (Harbin)                       	software4	80.23
 7. MQuni (Sydney)                          	software2	80.16
 8. NAIST SATO (Nara)                       	software1	80.13
 9. fbaml (Palo Alto)                       	software1	79.79
10. Orange – Deskiñ (Lannion)               	software1	79.66
11. Mengest (Shanghai)                      	software1	79.28
12. LyS-FASTPARSE (A Coruña)                	software5	79.24
13. naistCL (Nara)                          	software1	78.58
14. RACAI (București)                       	software1	78.34
15. UParse (Edinburgh)                      	software1	78.08
16. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.73
17. TurkuNLP (Turku)                        	software1	77.66
18. LIMSI-LIPN (Paris)                      	software2	77.31
19. BASELINE UDPipe 1.1 (Praha)             	software2	77.31
20. darc (Tübingen)                         	software1	77.17
21. ParisNLP (Paris)                        	software1	76.81
22. IIT Kharagpur (Kharagpur)               	software3	75.97
23. CLCL (Genève)                           	software2	75.93
24. METU (Ankara)                           	software2	75.25
25. OpenU NLP Lab (Ra'anana)                	software6	74.81
26. Wanghao-ftd-SJTU (Shanghai)             	software2	74.70
27. UT (Tartu)                              	software1	74.26
28. Uppsala (Uppsala)                       	software1	74.09
29. UALING (Tucson)                         	software1	74.02
30. TRL (Tokyo)                             	software1	55.70
31. MetaRomance (Santiago de Compostela)    	software1	54.87
32. ECNU (Shanghai)                         	software1	12.45
33. Wenba-NLU (Wuhan)                       	software1	 0.10
</pre>



### gl_treegal

<pre>
 1. C2L2 (Ithaca)                           	software5	74.34
 2. Stanford (Stanford)                     	software1	73.39
 3. IMS (Stuttgart)                         	software2	71.30
 4. Koç University (İstanbul)               	software3	69.13
 5. LATTICE (Paris)                         	software7	68.01
 6. fbaml (Palo Alto)                       	software1	67.97
 7. NAIST SATO (Nara)                       	software1	66.84
 8. HIT-SCIR (Harbin)                       	software4	66.51
 9. TurkuNLP (Turku)                        	software1	66.47
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	66.31
11. UALING (Tucson)                         	software1	66.12
12. ParisNLP (Paris)                        	software1	65.95
13. Wanghao-ftd-SJTU (Shanghai)             	software2	65.92
14. LIMSI-LIPN (Paris)                      	software2	65.85
15. BASELINE UDPipe 1.1 (Praha)             	software2	65.82
16. MQuni (Sydney)                          	software2	65.64
17. LyS-FASTPARSE (A Coruña)                	software5	65.42
18. RACAI (București)                       	software1	65.22
19. darc (Tübingen)                         	software1	65.19
20. naistCL (Nara)                          	software1	64.79
21. UParse (Edinburgh)                      	software1	64.18
22. IIT Kharagpur (Kharagpur)               	software3	63.86
23. Mengest (Shanghai)                      	software1	61.17
24. OpenU NLP Lab (Ra'anana)                	software6	59.85
25. MetaRomance (Santiago de Compostela)    	software1	57.20
26. Uppsala (Uppsala)                       	software1	56.79
27. METU (Ankara)                           	software2	42.91
28. TRL (Tokyo)                             	software1	33.25
29. Orange – Deskiñ (Lannion)               	software1	22.46
30. CLCL (Genève)                           	software2	 2.76
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### got

<pre>
 1. IMS (Stuttgart)                         	software2	71.36
 2. C2L2 (Ithaca)                           	software5	68.34
 3. Stanford (Stanford)                     	software1	66.82
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	62.80
 5. fbaml (Palo Alto)                       	software1	62.64
 6. RACAI (București)                       	software1	62.30
 7. LyS-FASTPARSE (A Coruña)                	software5	62.07
 8. darc (Tübingen)                         	software1	61.92
 9. TurkuNLP (Turku)                        	software1	61.52
10. LIMSI-LIPN (Paris)                      	software2	60.94
11. UParse (Edinburgh)                      	software1	60.71
12. LATTICE (Paris)                         	software7	60.55
13. HIT-SCIR (Harbin)                       	software4	60.52
14. IIT Kharagpur (Kharagpur)               	software3	60.28
15. NAIST SATO (Nara)                       	software1	60.20
16. BASELINE UDPipe 1.1 (Praha)             	software2	59.81
17. MQuni (Sydney)                          	software2	59.28
18. Wanghao-ftd-SJTU (Shanghai)             	software2	59.26
19. ParisNLP (Paris)                        	software1	58.66
20. Orange – Deskiñ (Lannion)               	software1	57.97
21. CLCL (Genève)                           	software2	57.72
22. UALING (Tucson)                         	software1	57.62
23. Mengest (Shanghai)                      	software1	57.02
24. Koç University (İstanbul)               	software3	56.81
25. Uppsala (Uppsala)                       	software1	56.69
26. naistCL (Nara)                          	software1	55.28
27. UT (Tartu)                              	software1	53.09
28. OpenU NLP Lab (Ra'anana)                	software6	50.06
29. TRL (Tokyo)                             	software1	36.92
30. MetaRomance (Santiago de Compostela)    	software1	32.44
31. METU (Ankara)                           	software2	20.05
32. Wenba-NLU (Wuhan)                       	software1	 1.85
33. ECNU (Shanghai)                         	software1	 1.56
</pre>



### grc

<pre>
 1. Stanford (Stanford)                     	software1	73.19
 2. IMS (Stuttgart)                         	software2	68.23
 3. C2L2 (Ithaca)                           	software5	64.94
 4. NAIST SATO (Nara)                       	software1	61.28
 5. RACAI (București)                       	software1	60.48
 6. LyS-FASTPARSE (A Coruña)                	software5	59.93
 7. HIT-SCIR (Harbin)                       	software4	59.84
 8. TurkuNLP (Turku)                        	software1	59.83
 9. fbaml (Palo Alto)                       	software1	58.42
10. darc (Tübingen)                         	software1	58.20
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	57.39
12. UParse (Edinburgh)                      	software1	57.22
13. LIMSI-LIPN (Paris)                      	software2	56.04
14. BASELINE UDPipe 1.1 (Praha)             	software2	56.04
15. CLCL (Genève)                           	software2	54.56
16. Orange – Deskiñ (Lannion)               	software1	54.10
17. IIT Kharagpur (Kharagpur)               	software3	53.59
18. UALING (Tucson)                         	software1	52.56
19. Wanghao-ftd-SJTU (Shanghai)             	software2	51.78
20. LATTICE (Paris)                         	software7	51.50
21. Uppsala (Uppsala)                       	software1	50.94
22. naistCL (Nara)                          	software1	49.48
23. Koç University (İstanbul)               	software3	49.31
24. Mengest (Shanghai)                      	software1	49.30
25. METU (Ankara)                           	software2	49.11
26. MQuni (Sydney)                          	software2	47.40
27. ParisNLP (Paris)                        	software1	47.37
28. UT (Tartu)                              	software1	42.16
29. OpenU NLP Lab (Ra'anana)                	software6	32.43
30. TRL (Tokyo)                             	software1	28.63
31. MetaRomance (Santiago de Compostela)    	software1	21.71
32. Wenba-NLU (Wuhan)                       	software1	 1.33
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### grc_proiel

<pre>
 1. IMS (Stuttgart)                         	software2	75.28
 2. Stanford (Stanford)                     	software1	74.25
 3. C2L2 (Ithaca)                           	software5	70.47
 4. RACAI (București)                       	software1	69.47
 5. HIT-SCIR (Harbin)                       	software4	69.39
 6. NAIST SATO (Nara)                       	software1	69.23
 7. TurkuNLP (Turku)                        	software1	68.04
 8. LyS-FASTPARSE (A Coruña)                	software5	67.85
 9. fbaml (Palo Alto)                       	software1	67.56
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	66.51
11. darc (Tübingen)                         	software1	66.21
12. Orange – Deskiñ (Lannion)               	software1	65.50
13. LIMSI-LIPN (Paris)                      	software2	65.22
14. BASELINE UDPipe 1.1 (Praha)             	software2	65.22
15. UParse (Edinburgh)                      	software1	64.48
16. IIT Kharagpur (Kharagpur)               	software3	64.19
17. Uppsala (Uppsala)                       	software1	63.86
18. CLCL (Genève)                           	software2	62.83
19. Wanghao-ftd-SJTU (Shanghai)             	software2	62.64
20. UALING (Tucson)                         	software1	62.07
21. naistCL (Nara)                          	software1	62.05
22. Koç University (İstanbul)               	software3	61.70
23. Mengest (Shanghai)                      	software1	60.61
24. LATTICE (Paris)                         	software7	60.58
25. METU (Ankara)                           	software2	60.08
26. MQuni (Sydney)                          	software2	60.06
27. OpenU NLP Lab (Ra'anana)                	software6	51.05
28. ParisNLP (Paris)                        	software1	49.41
29. TRL (Tokyo)                             	software1	38.88
30. MetaRomance (Santiago de Compostela)    	software1	31.73
31. Wenba-NLU (Wuhan)                       	software1	 0.77
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### he

<pre>
 1. IMS (Stuttgart)                         	software2	68.16
 2. Stanford (Stanford)                     	software1	63.94
 3. Uppsala (Uppsala)                       	software1	63.72
 4. C2L2 (Ithaca)                           	software5	62.33
 5. LATTICE (Paris)                         	software7	61.24
 6. RACAI (București)                       	software1	60.72
 7. HIT-SCIR (Harbin)                       	software4	60.07
 8. NAIST SATO (Nara)                       	software1	59.56
 9. LyS-FASTPARSE (A Coruña)                	software5	59.28
10. Koç University (İstanbul)               	software3	58.98
11. MQuni (Sydney)                          	software2	58.74
12. Mengest (Shanghai)                      	software1	58.10
13. Orange – Deskiñ (Lannion)               	software1	58.07
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	57.86
15. UParse (Edinburgh)                      	software1	57.60
16. TurkuNLP (Turku)                        	software1	57.50
17. naistCL (Nara)                          	software1	57.30
18. LIMSI-LIPN (Paris)                      	software2	57.23
19. BASELINE UDPipe 1.1 (Praha)             	software2	57.23
20. darc (Tübingen)                         	software1	57.13
21. IIT Kharagpur (Kharagpur)               	software3	56.74
22. Wanghao-ftd-SJTU (Shanghai)             	software2	56.02
23. UALING (Tucson)                         	software1	55.79
24. CLCL (Genève)                           	software2	55.36
25. METU (Ankara)                           	software2	55.32
26. fbaml (Palo Alto)                       	software1	54.25
27. ParisNLP (Paris)                        	software1	44.49
28. OpenU NLP Lab (Ra'anana)                	software6	41.49
29. TRL (Tokyo)                             	software1	37.10
30. MetaRomance (Santiago de Compostela)    	software1	30.07
31. Wenba-NLU (Wuhan)                       	software1	 0.13
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hi

<pre>
 1. Stanford (Stanford)                     	software1	91.59
 2. IMS (Stuttgart)                         	software2	90.41
 3. C2L2 (Ithaca)                           	software5	90.40
 4. HIT-SCIR (Harbin)                       	software4	89.48
 5. NAIST SATO (Nara)                       	software1	88.70
 6. fbaml (Palo Alto)                       	software1	88.15
 7. TurkuNLP (Turku)                        	software1	87.75
 8. darc (Tübingen)                         	software1	87.50
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	87.28
10. Koç University (İstanbul)               	software3	87.23
11. UParse (Edinburgh)                      	software1	87.20
12. Orange – Deskiñ (Lannion)               	software1	87.09
13. LATTICE (Paris)                         	software7	86.99
14. naistCL (Nara)                          	software1	86.95
15. LyS-FASTPARSE (A Coruña)                	software5	86.88
16. LIMSI-LIPN (Paris)                      	software2	86.82
17. CLCL (Genève)                           	software2	86.80
18. BASELINE UDPipe 1.1 (Praha)             	software2	86.77
19. Mengest (Shanghai)                      	software1	86.76
20. IIT Kharagpur (Kharagpur)               	software3	86.69
21. MQuni (Sydney)                          	software2	86.60
22. Wanghao-ftd-SJTU (Shanghai)             	software2	85.79
23. UALING (Tucson)                         	software1	85.56
24. RACAI (București)                       	software1	85.33
25. UT (Tartu)                              	software1	85.31
26. METU (Ankara)                           	software2	84.54
27. Uppsala (Uppsala)                       	software1	74.34
28. OpenU NLP Lab (Ra'anana)                	software6	69.36
29. TRL (Tokyo)                             	software1	55.15
30. ParisNLP (Paris)                        	software1	45.72
31. MetaRomance (Santiago de Compostela)    	software1	 7.63
32. Wenba-NLU (Wuhan)                       	software1	 0.42
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### hi_pud

<pre>
 1. Stanford (Stanford)                     	software1	54.49
 2. HIT-SCIR (Harbin)                       	software4	54.14
 3. C2L2 (Ithaca)                           	software5	54.12
 4. IMS (Stuttgart)                         	software2	53.57
 5. NAIST SATO (Nara)                       	software1	52.81
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	52.53
 7. UParse (Edinburgh)                      	software1	51.89
 8. TurkuNLP (Turku)                        	software1	51.87
 9. Koç University (İstanbul)               	software3	51.49
10. CLCL (Genève)                           	software1	51.31
11. IIT Kharagpur (Kharagpur)               	software3	51.29
12. Wanghao-ftd-SJTU (Shanghai)             	software2	51.27
13. LyS-FASTPARSE (A Coruña)                	software5	51.15
14. Mengest (Shanghai)                      	software1	51.07
15. naistCL (Nara)                          	software1	51.03
16. Orange – Deskiñ (Lannion)               	software1	51.02
17. darc (Tübingen)                         	software1	50.98
18. LATTICE (Paris)                         	software7	50.94
19. LIMSI-LIPN (Paris)                      	software2	50.91
20. BASELINE UDPipe 1.1 (Praha)             	software2	50.85
21. UALING (Tucson)                         	software1	50.83
22. MQuni (Sydney)                          	software2	50.03
23. UT (Tartu)                              	software1	49.67
24. METU (Ankara)                           	software2	49.63
25. RACAI (București)                       	software1	45.57
26. Uppsala (Uppsala)                       	software1	45.15
27. fbaml (Palo Alto)                       	software1	43.46
28. OpenU NLP Lab (Ra'anana)                	software6	43.06
29. TRL (Tokyo)                             	software1	36.80
30. ParisNLP (Paris)                        	software1	32.39
31. MetaRomance (Santiago de Compostela)    	software1	 9.01
32. ECNU (Shanghai)                         	software1	 0.59
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### hr

<pre>
 1. Stanford (Stanford)                     	software1	85.25
 2. C2L2 (Ithaca)                           	software5	83.15
 3. IMS (Stuttgart)                         	software2	82.51
 4. HIT-SCIR (Harbin)                       	software4	81.30
 5. LATTICE (Paris)                         	software7	80.96
 6. NAIST SATO (Nara)                       	software1	79.32
 7. Koç University (İstanbul)               	software3	79.22
 8. MQuni (Sydney)                          	software2	79.09
 9. TurkuNLP (Turku)                        	software1	78.57
10. LIMSI-LIPN (Paris)                      	software2	78.02
11. LyS-FASTPARSE (A Coruña)                	software5	77.91
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.73
13. UParse (Edinburgh)                      	software1	77.18
14. BASELINE UDPipe 1.1 (Praha)             	software2	77.18
15. Orange – Deskiñ (Lannion)               	software1	77.11
16. RACAI (București)                       	software1	77.03
17. darc (Tübingen)                         	software1	76.96
18. naistCL (Nara)                          	software1	76.78
19. fbaml (Palo Alto)                       	software1	76.63
20. Mengest (Shanghai)                      	software1	76.59
21. IIT Kharagpur (Kharagpur)               	software3	76.36
22. UT (Tartu)                              	software1	75.77
23. Uppsala (Uppsala)                       	software1	75.43
24. Wanghao-ftd-SJTU (Shanghai)             	software2	74.84
25. ParisNLP (Paris)                        	software1	74.81
26. UALING (Tucson)                         	software1	74.59
27. CLCL (Genève)                           	software1	73.78
28. METU (Ankara)                           	software2	71.39
29. OpenU NLP Lab (Ra'anana)                	software6	59.94
30. TRL (Tokyo)                             	software1	45.82
31. MetaRomance (Santiago de Compostela)    	software1	42.03
32. ECNU (Shanghai)                         	software1	 1.80
33. Wenba-NLU (Wuhan)                       	software1	 0.18
</pre>



### hsb

<pre>
 1. C2L2 (Ithaca)                           	software5	61.70
 2. IMS (Stuttgart)                         	software2	61.67
 3. Stanford (Stanford)                     	software1	60.01
 4. HIT-SCIR (Harbin)                       	software4	59.27
 5. UParse (Edinburgh)                      	software1	59.24
 6. Orange – Deskiñ (Lannion)               	software1	58.25
 7. LIMSI-LIPN (Paris)                      	software2	57.79
 8. Wanghao-ftd-SJTU (Shanghai)             	software2	56.60
 9. ParisNLP (Paris)                        	software1	56.22
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	55.76
11. IIT Kharagpur (Kharagpur)               	software3	54.78
12. darc (Tübingen)                         	software1	54.30
13. BASELINE UDPipe 1.1 (Praha)             	software2	53.83
14. OpenU NLP Lab (Ra'anana)                	software6	53.09
15. LyS-FASTPARSE (A Coruña)                	software5	52.50
16. LATTICE (Paris)                         	software7	50.54
17. Koç University (İstanbul)               	software3	50.25
18. CLCL (Genève)                           	software2	48.50
19. naistCL (Nara)                          	software1	47.64
20. UALING (Tucson)                         	software1	46.78
21. Uppsala (Uppsala)                       	software1	45.63
22. RACAI (București)                       	software1	43.74
23. NAIST SATO (Nara)                       	software1	41.32
24. MetaRomance (Santiago de Compostela)    	software1	38.47
25. TurkuNLP (Turku)                        	software1	34.67
26. fbaml (Palo Alto)                       	software1	24.58
27. TRL (Tokyo)                             	software1	22.15
28. METU (Ankara)                           	software2	19.59
29. MQuni (Sydney)                          	software2	18.01
30. Mengest (Shanghai)                      	software1	14.19
31. ECNU (Shanghai)                         	software1	 6.91
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hu

<pre>
 1. Stanford (Stanford)                     	software1	77.56
 2. C2L2 (Ithaca)                           	software5	76.55
 3. IMS (Stuttgart)                         	software2	73.55
 4. Koç University (İstanbul)               	software3	69.55
 5. LATTICE (Paris)                         	software7	68.49
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	66.54
 7. MQuni (Sydney)                          	software2	66.45
 8. HIT-SCIR (Harbin)                       	software4	66.29
 9. LyS-FASTPARSE (A Coruña)                	software5	66.00
10. TurkuNLP (Turku)                        	software1	65.61
11. LIMSI-LIPN (Paris)                      	software2	65.18
12. darc (Tübingen)                         	software1	65.17
13. IIT Kharagpur (Kharagpur)               	software3	65.14
14. RACAI (București)                       	software1	64.76
15. Orange – Deskiñ (Lannion)               	software1	64.59
16. fbaml (Palo Alto)                       	software1	64.37
17. Wanghao-ftd-SJTU (Shanghai)             	software2	64.36
18. UParse (Edinburgh)                      	software1	64.30
19. BASELINE UDPipe 1.1 (Praha)             	software2	64.30
20. UALING (Tucson)                         	software1	64.18
21. naistCL (Nara)                          	software1	62.42
22. NAIST SATO (Nara)                       	software1	60.30
23. Mengest (Shanghai)                      	software1	57.85
24. UT (Tartu)                              	software1	57.50
25. Uppsala (Uppsala)                       	software1	54.55
26. METU (Ankara)                           	software2	52.40
27. CLCL (Genève)                           	software1	50.95
28. ParisNLP (Paris)                        	software1	49.82
29. OpenU NLP Lab (Ra'anana)                	software6	40.29
30. TRL (Tokyo)                             	software1	33.75
31. MetaRomance (Santiago de Compostela)    	software1	33.63
32. ECNU (Shanghai)                         	software1	 9.07
33. Wenba-NLU (Wuhan)                       	software1	 0.06
</pre>



### id

<pre>
 1. Stanford (Stanford)                     	software1	79.19
 2. C2L2 (Ithaca)                           	software5	78.55
 3. IMS (Stuttgart)                         	software2	77.70
 4. HIT-SCIR (Harbin)                       	software4	76.66
 5. LATTICE (Paris)                         	software7	76.60
 6. NAIST SATO (Nara)                       	software1	76.50
 7. MQuni (Sydney)                          	software2	76.50
 8. fbaml (Palo Alto)                       	software1	75.74
 9. Koç University (İstanbul)               	software3	75.54
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.47
11. UParse (Edinburgh)                      	software1	75.01
12. TurkuNLP (Turku)                        	software1	74.87
13. LIMSI-LIPN (Paris)                      	software2	74.78
14. naistCL (Nara)                          	software1	74.73
15. BASELINE UDPipe 1.1 (Praha)             	software2	74.61
16. Mengest (Shanghai)                      	software1	74.40
17. IIT Kharagpur (Kharagpur)               	software3	74.23
18. RACAI (București)                       	software1	73.86
19. Orange – Deskiñ (Lannion)               	software1	73.64
20. darc (Tübingen)                         	software1	73.58
21. Wanghao-ftd-SJTU (Shanghai)             	software2	73.52
22. UT (Tartu)                              	software1	72.99
23. LyS-FASTPARSE (A Coruña)                	software5	72.94
24. UALING (Tucson)                         	software1	72.59
25. Uppsala (Uppsala)                       	software1	72.11
26. CLCL (Genève)                           	software2	69.45
27. METU (Ankara)                           	software2	68.83
28. OpenU NLP Lab (Ra'anana)                	software6	68.49
29. ParisNLP (Paris)                        	software1	64.84
30. TRL (Tokyo)                             	software1	54.97
31. MetaRomance (Santiago de Compostela)    	software1	38.95
32. ECNU (Shanghai)                         	software1	 3.76
33. Wenba-NLU (Wuhan)                       	software1	 2.46
</pre>



### it

<pre>
 1. Stanford (Stanford)                     	software1	90.68
 2. C2L2 (Ithaca)                           	software5	89.08
 3. IMS (Stuttgart)                         	software2	87.85
 4. HIT-SCIR (Harbin)                       	software4	87.77
 5. LATTICE (Paris)                         	software7	87.75
 6. NAIST SATO (Nara)                       	software1	87.39
 7. MQuni (Sydney)                          	software2	86.71
 8. Orange – Deskiñ (Lannion)               	software1	86.65
 9. UParse (Edinburgh)                      	software1	86.62
10. Koç University (İstanbul)               	software3	86.45
11. Mengest (Shanghai)                      	software1	86.14
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	86.11
13. fbaml (Palo Alto)                       	software1	86.01
14. naistCL (Nara)                          	software1	85.74
15. TurkuNLP (Turku)                        	software1	85.66
16. LyS-FASTPARSE (A Coruña)                	software5	85.60
17. BASELINE UDPipe 1.1 (Praha)             	software2	85.28
18. LIMSI-LIPN (Paris)                      	software2	85.27
19. CLCL (Genève)                           	software2	85.05
20. darc (Tübingen)                         	software1	85.04
21. Uppsala (Uppsala)                       	software1	84.84
22. Wanghao-ftd-SJTU (Shanghai)             	software2	84.66
23. IIT Kharagpur (Kharagpur)               	software3	84.66
24. RACAI (București)                       	software1	84.45
25. UALING (Tucson)                         	software1	84.01
26. METU (Ankara)                           	software2	83.01
27. ParisNLP (Paris)                        	software1	81.20
28. OpenU NLP Lab (Ra'anana)                	software6	77.96
29. MetaRomance (Santiago de Compostela)    	software1	62.96
30. TRL (Tokyo)                             	software1	49.67
31. Wenba-NLU (Wuhan)                       	software1	 0.25
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### it_pud

<pre>
 1. Stanford (Stanford)                     	software1	88.14
 2. C2L2 (Ithaca)                           	software5	86.74
 3. LATTICE (Paris)                         	software7	86.49
 4. IMS (Stuttgart)                         	software2	86.16
 5. HIT-SCIR (Harbin)                       	software4	85.51
 6. NAIST SATO (Nara)                       	software1	85.30
 7. UParse (Edinburgh)                      	software1	85.13
 8. MQuni (Sydney)                          	software2	85.04
 9. Orange – Deskiñ (Lannion)               	software1	84.89
10. Koç University (İstanbul)               	software3	84.52
11. fbaml (Palo Alto)                       	software1	84.41
12. TurkuNLP (Turku)                        	software1	84.18
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	84.03
14. naistCL (Nara)                          	software1	83.85
15. LyS-FASTPARSE (A Coruña)                	software5	83.84
16. darc (Tübingen)                         	software1	83.79
17. Mengest (Shanghai)                      	software1	83.79
18. BASELINE UDPipe 1.1 (Praha)             	software2	83.70
19. LIMSI-LIPN (Paris)                      	software2	83.69
20. Uppsala (Uppsala)                       	software1	83.28
21. CLCL (Genève)                           	software1	83.20
22. IIT Kharagpur (Kharagpur)               	software3	83.08
23. Wanghao-ftd-SJTU (Shanghai)             	software2	82.67
24. RACAI (București)                       	software1	82.48
25. UALING (Tucson)                         	software1	82.31
26. ParisNLP (Paris)                        	software1	81.81
27. METU (Ankara)                           	software2	80.99
28. OpenU NLP Lab (Ra'anana)                	software6	75.11
29. MetaRomance (Santiago de Compostela)    	software1	65.49
30. TRL (Tokyo)                             	software1	50.34
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ja

<pre>
 1. TRL (Tokyo)                             	software1	91.13
 2. HIT-SCIR (Harbin)                       	software4	80.85
 3. LIMSI-LIPN (Paris)                      	software2	80.01
 4. fbaml (Palo Alto)                       	software1	79.25
 5. IMS (Stuttgart)                         	software2	78.21
 6. Stanford (Stanford)                     	software1	74.72
 7. C2L2 (Ithaca)                           	software5	74.51
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.49
 9. LATTICE (Paris)                         	software7	73.98
10. Orange – Deskiñ (Lannion)               	software1	73.37
11. NAIST SATO (Nara)                       	software1	73.27
12. MQuni (Sydney)                          	software2	73.04
13. Mengest (Shanghai)                      	software1	73.00
14. darc (Tübingen)                         	software1	72.88
15. TurkuNLP (Turku)                        	software1	72.81
16. UT (Tartu)                              	software1	72.78
17. LyS-FASTPARSE (A Coruña)                	software5	72.68
18. Koç University (İstanbul)               	software3	72.67
19. IIT Kharagpur (Kharagpur)               	software3	72.35
20. UParse (Edinburgh)                      	software1	72.21
21. BASELINE UDPipe 1.1 (Praha)             	software2	72.21
22. Wanghao-ftd-SJTU (Shanghai)             	software2	72.12
23. CLCL (Genève)                           	software2	71.85
24. UALING (Tucson)                         	software1	71.75
25. naistCL (Nara)                          	software1	71.64
26. METU (Ankara)                           	software2	70.62
27. OpenU NLP Lab (Ra'anana)                	software6	68.68
28. RACAI (București)                       	software1	67.64
29. Uppsala (Uppsala)                       	software1	65.71
30. ParisNLP (Paris)                        	software1	65.15
31. MetaRomance (Santiago de Compostela)    	software1	 2.98
32. ECNU (Shanghai)                         	software1	 1.00
33. Wenba-NLU (Wuhan)                       	software1	 0.03
</pre>



### ja_pud

<pre>
 1. HIT-SCIR (Harbin)                       	software4	83.75
 2. LIMSI-LIPN (Paris)                      	software2	82.99
 3. IMS (Stuttgart)                         	software2	81.98
 4. fbaml (Palo Alto)                       	software1	81.25
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	78.36
 6. C2L2 (Ithaca)                           	software5	78.22
 7. Stanford (Stanford)                     	software1	77.92
 8. LATTICE (Paris)                         	software7	77.41
 9. MQuni (Sydney)                          	software2	76.93
10. NAIST SATO (Nara)                       	software1	76.78
11. Orange – Deskiñ (Lannion)               	software1	76.74
12. Mengest (Shanghai)                      	software1	76.66
13. UT (Tartu)                              	software1	76.31
14. BASELINE UDPipe 1.1 (Praha)             	software2	76.28
15. Koç University (İstanbul)               	software3	76.27
16. CLCL (Genève)                           	software1	76.21
17. IIT Kharagpur (Kharagpur)               	software3	76.15
18. LyS-FASTPARSE (A Coruña)                	software5	76.09
19. TurkuNLP (Turku)                        	software1	76.09
20. Wanghao-ftd-SJTU (Shanghai)             	software2	75.69
21. darc (Tübingen)                         	software1	75.69
22. UALING (Tucson)                         	software1	75.61
23. METU (Ankara)                           	software2	74.69
24. UParse (Edinburgh)                      	software1	74.64
25. naistCL (Nara)                          	software1	74.47
26. RACAI (București)                       	software1	74.06
27. Uppsala (Uppsala)                       	software1	71.80
28. OpenU NLP Lab (Ra'anana)                	software6	71.45
29. TRL (Tokyo)                             	software1	64.45
30. ParisNLP (Paris)                        	software1	62.91
31. MetaRomance (Santiago de Compostela)    	software1	 2.02
32. ECNU (Shanghai)                         	software1	 0.65
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### kk

<pre>
 1. RACAI (București)                       	software1	29.22
 2. TurkuNLP (Turku)                        	software1	28.31
 3. C2L2 (Ithaca)                           	software5	27.66
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	25.43
 5. IMS (Stuttgart)                         	software2	25.29
 6. Stanford (Stanford)                     	software1	25.13
 7. HIT-SCIR (Harbin)                       	software4	24.76
 8. UALING (Tucson)                         	software1	24.75
 9. ParisNLP (Paris)                        	software1	24.73
10. IIT Kharagpur (Kharagpur)               	software3	24.54
11. BASELINE UDPipe 1.1 (Praha)             	software2	24.51
12. TRL (Tokyo)                             	software1	24.14
13. fbaml (Palo Alto)                       	software1	23.99
14. darc (Tübingen)                         	software1	23.68
15. naistCL (Nara)                          	software1	22.55
16. NAIST SATO (Nara)                       	software1	22.49
17. Koç University (İstanbul)               	software3	22.34
18. Wanghao-ftd-SJTU (Shanghai)             	software2	22.27
19. LATTICE (Paris)                         	software7	22.11
20. UParse (Edinburgh)                      	software1	21.96
21. Orange – Deskiñ (Lannion)               	software1	21.31
22. LIMSI-LIPN (Paris)                      	software2	20.94
23. MQuni (Sydney)                          	software2	20.40
24. Uppsala (Uppsala)                       	software1	18.24
25. METU (Ankara)                           	software2	16.48
26. LyS-FASTPARSE (A Coruña)                	software5	16.20
27. OpenU NLP Lab (Ra'anana)                	software6	 9.26
28. MetaRomance (Santiago de Compostela)    	software1	 8.23
29. CLCL (Genève)                           	software2	 1.00
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. Mengest (Shanghai)                      	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### kmr

<pre>
 1. C2L2 (Ithaca)                           	software5	47.53
 2. IMS (Stuttgart)                         	software2	46.70
 3. HIT-SCIR (Harbin)                       	software4	44.70
 4. Koç University (İstanbul)               	software3	42.11
 5. LATTICE (Paris)                         	software7	41.71
 6. UALING (Tucson)                         	software1	40.57
 7. UParse (Edinburgh)                      	software1	39.76
 8. Orange – Deskiñ (Lannion)               	software1	38.31
 9. LIMSI-LIPN (Paris)                      	software2	35.59
10. Stanford (Stanford)                     	software1	35.05
11. OpenU NLP Lab (Ra'anana)                	software6	34.94
12. ParisNLP (Paris)                        	software1	34.80
13. darc (Tübingen)                         	software1	33.06
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	32.89
15. BASELINE UDPipe 1.1 (Praha)             	software2	32.35
16. LyS-FASTPARSE (A Coruña)                	software5	32.08
17. IIT Kharagpur (Kharagpur)               	software3	32.03
18. naistCL (Nara)                          	software1	29.15
19. fbaml (Palo Alto)                       	software1	25.85
20. MetaRomance (Santiago de Compostela)    	software1	23.53
21. NAIST SATO (Nara)                       	software1	23.18
22. CLCL (Genève)                           	software2	22.20
23. TurkuNLP (Turku)                        	software1	22.19
24. Wanghao-ftd-SJTU (Shanghai)             	software2	19.85
25. Uppsala (Uppsala)                       	software1	19.37
26. MQuni (Sydney)                          	software2	17.88
27. METU (Ankara)                           	software2	15.86
28. RACAI (București)                       	software1	14.73
29. Mengest (Shanghai)                      	software1	 8.62
30. TRL (Tokyo)                             	software1	 3.44
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ko

<pre>
 1. Stanford (Stanford)                     	software1	82.49
 2. C2L2 (Ithaca)                           	software5	81.10
 3. IMS (Stuttgart)                         	software2	79.51
 4. naistCL (Nara)                          	software1	74.56
 5. MQuni (Sydney)                          	software2	73.70
 6. LATTICE (Paris)                         	software7	72.35
 7. HIT-SCIR (Harbin)                       	software4	71.82
 8. Koç University (İstanbul)               	software3	71.70
 9. Uppsala (Uppsala)                       	software1	69.87
10. Orange – Deskiñ (Lannion)               	software1	67.76
11. TurkuNLP (Turku)                        	software1	66.93
12. NAIST SATO (Nara)                       	software1	64.46
13. METU (Ankara)                           	software2	64.25
14. LyS-FASTPARSE (A Coruña)                	software5	63.85
15. Mengest (Shanghai)                      	software1	63.21
16. RACAI (București)                       	software1	62.79
17. fbaml (Palo Alto)                       	software1	61.14
18. CLCL (Genève)                           	software2	61.08
19. UT (Tartu)                              	software1	60.51
20. ÚFAL – UDPipe 1.2 (Praha)               	software1	60.30
21. UParse (Edinburgh)                      	software1	59.09
22. LIMSI-LIPN (Paris)                      	software2	59.09
23. BASELINE UDPipe 1.1 (Praha)             	software2	59.09
24. IIT Kharagpur (Kharagpur)               	software3	58.33
25. darc (Tübingen)                         	software1	58.30
26. Wanghao-ftd-SJTU (Shanghai)             	software2	54.07
27. UALING (Tucson)                         	software1	52.61
28. OpenU NLP Lab (Ra'anana)                	software6	52.37
29. TRL (Tokyo)                             	software1	45.83
30. ParisNLP (Paris)                        	software1	40.71
31. ECNU (Shanghai)                         	software1	12.78
32. MetaRomance (Santiago de Compostela)    	software1	12.60
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la

<pre>
 1. Stanford (Stanford)                     	software1	63.37
 2. C2L2 (Ithaca)                           	software5	59.48
 3. NAIST SATO (Nara)                       	software1	52.19
 4. LATTICE (Paris)                         	software7	51.95
 5. IMS (Stuttgart)                         	software2	51.82
 6. fbaml (Palo Alto)                       	software1	49.32
 7. LyS-FASTPARSE (A Coruña)                	software5	48.92
 8. HIT-SCIR (Harbin)                       	software4	48.75
 9. TurkuNLP (Turku)                        	software1	47.91
10. Koç University (İstanbul)               	software3	47.08
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	47.02
12. RACAI (București)                       	software1	46.77
13. darc (Tübingen)                         	software1	45.29
14. UALING (Tucson)                         	software1	44.62
15. MQuni (Sydney)                          	software2	44.52
16. Wanghao-ftd-SJTU (Shanghai)             	software2	44.01
17. IIT Kharagpur (Kharagpur)               	software3	43.80
18. UParse (Edinburgh)                      	software1	43.77
19. BASELINE UDPipe 1.1 (Praha)             	software2	43.77
20. LIMSI-LIPN (Paris)                      	software2	43.55
21. Orange – Deskiñ (Lannion)               	software1	43.16
22. ParisNLP (Paris)                        	software1	39.91
23. Uppsala (Uppsala)                       	software1	38.93
24. UT (Tartu)                              	software1	38.57
25. Mengest (Shanghai)                      	software1	38.00
26. naistCL (Nara)                          	software1	36.50
27. OpenU NLP Lab (Ra'anana)                	software6	24.21
28. TRL (Tokyo)                             	software1	23.48
29. MetaRomance (Santiago de Compostela)    	software1	21.22
30. METU (Ankara)                           	software2	17.21
31. CLCL (Genève)                           	software2	 5.72
32. ECNU (Shanghai)                         	software1	 5.50
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_ittb

<pre>
 1. Stanford (Stanford)                     	software1	87.02
 2. IMS (Stuttgart)                         	software2	84.09
 3. C2L2 (Ithaca)                           	software5	82.75
 4. NAIST SATO (Nara)                       	software1	82.20
 5. HIT-SCIR (Harbin)                       	software4	81.03
 6. Uppsala (Uppsala)                       	software1	80.04
 7. LyS-FASTPARSE (A Coruña)                	software5	79.58
 8. UParse (Edinburgh)                      	software1	79.35
 9. TurkuNLP (Turku)                        	software1	78.99
10. fbaml (Palo Alto)                       	software1	77.62
11. LIMSI-LIPN (Paris)                      	software2	76.98
12. BASELINE UDPipe 1.1 (Praha)             	software2	76.98
13. Orange – Deskiñ (Lannion)               	software1	76.42
14. IIT Kharagpur (Kharagpur)               	software3	76.27
15. darc (Tübingen)                         	software1	76.22
16. Koç University (İstanbul)               	software3	76.15
17. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.84
18. CLCL (Genève)                           	software1	75.81
19. naistCL (Nara)                          	software1	75.08
20. Wanghao-ftd-SJTU (Shanghai)             	software2	75.05
21. RACAI (București)                       	software1	74.45
22. Mengest (Shanghai)                      	software1	74.37
23. LATTICE (Paris)                         	software7	74.33
24. MQuni (Sydney)                          	software2	73.91
25. UALING (Tucson)                         	software1	73.29
26. METU (Ankara)                           	software2	70.90
27. ParisNLP (Paris)                        	software1	52.38
28. OpenU NLP Lab (Ra'anana)                	software6	50.65
29. TRL (Tokyo)                             	software1	37.59
30. UT (Tartu)                              	software1	28.59
31. MetaRomance (Santiago de Compostela)    	software1	28.50
32. ECNU (Shanghai)                         	software1	 8.16
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_proiel

<pre>
 1. IMS (Stuttgart)                         	software2	71.55
 2. Stanford (Stanford)                     	software1	69.35
 3. C2L2 (Ithaca)                           	software5	63.68
 4. HIT-SCIR (Harbin)                       	software4	63.48
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	61.55
 6. fbaml (Palo Alto)                       	software1	61.53
 7. LyS-FASTPARSE (A Coruña)                	software5	61.45
 8. NAIST SATO (Nara)                       	software1	61.34
 9. RACAI (București)                       	software1	60.80
10. Orange – Deskiñ (Lannion)               	software1	60.44
11. TurkuNLP (Turku)                        	software1	59.86
12. darc (Tübingen)                         	software1	59.52
13. Koç University (İstanbul)               	software3	59.36
14. Uppsala (Uppsala)                       	software1	58.74
15. BASELINE UDPipe 1.1 (Praha)             	software2	57.54
16. LIMSI-LIPN (Paris)                      	software2	57.51
17. IIT Kharagpur (Kharagpur)               	software3	57.06
18. UParse (Edinburgh)                      	software1	56.93
19. Wanghao-ftd-SJTU (Shanghai)             	software2	55.49
20. LATTICE (Paris)                         	software7	55.04
21. UALING (Tucson)                         	software1	54.53
22. CLCL (Genève)                           	software1	54.07
23. Mengest (Shanghai)                      	software1	54.07
24. naistCL (Nara)                          	software1	53.43
25. MQuni (Sydney)                          	software2	52.54
26. METU (Ankara)                           	software2	52.23
27. ParisNLP (Paris)                        	software1	42.68
28. OpenU NLP Lab (Ra'anana)                	software6	37.12
29. TRL (Tokyo)                             	software1	27.97
30. MetaRomance (Santiago de Compostela)    	software1	23.22
31. Wenba-NLU (Wuhan)                       	software1	 0.67
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### lv

<pre>
 1. Stanford (Stanford)                     	software1	74.01
 2. C2L2 (Ithaca)                           	software5	71.35
 3. IMS (Stuttgart)                         	software2	68.03
 4. HIT-SCIR (Harbin)                       	software4	64.97
 5. LATTICE (Paris)                         	software7	64.49
 6. Koç University (İstanbul)               	software3	63.63
 7. LyS-FASTPARSE (A Coruña)                	software5	63.05
 8. TurkuNLP (Turku)                        	software1	62.13
 9. darc (Tübingen)                         	software1	62.03
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	61.80
11. Orange – Deskiñ (Lannion)               	software1	61.52
12. IIT Kharagpur (Kharagpur)               	software3	61.38
13. fbaml (Palo Alto)                       	software1	60.94
14. MQuni (Sydney)                          	software2	60.47
15. NAIST SATO (Nara)                       	software1	60.20
16. RACAI (București)                       	software1	60.08
17. UParse (Edinburgh)                      	software1	59.95
18. BASELINE UDPipe 1.1 (Praha)             	software2	59.95
19. LIMSI-LIPN (Paris)                      	software2	59.81
20. UALING (Tucson)                         	software1	59.73
21. Mengest (Shanghai)                      	software1	59.50
22. CLCL (Genève)                           	software1	59.28
23. Wanghao-ftd-SJTU (Shanghai)             	software2	59.26
24. naistCL (Nara)                          	software1	57.07
25. METU (Ankara)                           	software2	56.34
26. UT (Tartu)                              	software1	55.72
27. Uppsala (Uppsala)                       	software1	52.36
28. ParisNLP (Paris)                        	software1	50.52
29. OpenU NLP Lab (Ra'anana)                	software6	47.69
30. TRL (Tokyo)                             	software1	34.21
31. MetaRomance (Santiago de Compostela)    	software1	25.65
32. ECNU (Shanghai)                         	software1	 6.72
33. Wenba-NLU (Wuhan)                       	software1	 0.34
</pre>



### nl

<pre>
 1. Stanford (Stanford)                     	software1	80.48
 2. C2L2 (Ithaca)                           	software5	75.50
 3. IMS (Stuttgart)                         	software2	75.07
 4. HIT-SCIR (Harbin)                       	software4	73.43
 5. NAIST SATO (Nara)                       	software1	73.22
 6. fbaml (Palo Alto)                       	software1	72.00
 7. LyS-FASTPARSE (A Coruña)                	software5	71.89
 8. LATTICE (Paris)                         	software7	70.60
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.52
10. Orange – Deskiñ (Lannion)               	software1	70.33
11. Koç University (İstanbul)               	software3	70.24
12. UParse (Edinburgh)                      	software1	69.90
13. Uppsala (Uppsala)                       	software1	69.83
14. TurkuNLP (Turku)                        	software1	69.59
15. MQuni (Sydney)                          	software2	69.29
16. darc (Tübingen)                         	software1	68.94
17. BASELINE UDPipe 1.1 (Praha)             	software2	68.90
18. Mengest (Shanghai)                      	software1	68.84
19. IIT Kharagpur (Kharagpur)               	software3	68.38
20. LIMSI-LIPN (Paris)                      	software2	68.31
21. RACAI (București)                       	software1	68.23
22. CLCL (Genève)                           	software1	67.70
23. naistCL (Nara)                          	software1	67.49
24. Wanghao-ftd-SJTU (Shanghai)             	software2	67.42
25. UALING (Tucson)                         	software1	66.14
26. UT (Tartu)                              	software1	65.22
27. METU (Ankara)                           	software2	64.73
28. ParisNLP (Paris)                        	software1	56.11
29. OpenU NLP Lab (Ra'anana)                	software6	41.89
30. TRL (Tokyo)                             	software1	39.44
31. MetaRomance (Santiago de Compostela)    	software1	35.65
32. ECNU (Shanghai)                         	software1	 4.27
33. Wenba-NLU (Wuhan)                       	software1	 0.32
</pre>



### nl_lassysmall

<pre>
 1. Stanford (Stanford)                     	software1	87.71
 2. IMS (Stuttgart)                         	software2	86.86
 3. HIT-SCIR (Harbin)                       	software4	86.85
 4. NAIST SATO (Nara)                       	software1	85.03
 5. fbaml (Palo Alto)                       	software1	82.67
 6. LyS-FASTPARSE (A Coruña)                	software5	82.49
 7. C2L2 (Ithaca)                           	software5	82.27
 8. Koç University (İstanbul)               	software3	80.85
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.15
10. darc (Tübingen)                         	software1	79.89
11. UParse (Edinburgh)                      	software1	79.56
12. RACAI (București)                       	software1	79.54
13. naistCL (Nara)                          	software1	79.18
14. TurkuNLP (Turku)                        	software1	79.06
15. Wanghao-ftd-SJTU (Shanghai)             	software2	78.52
16. LIMSI-LIPN (Paris)                      	software2	78.15
17. BASELINE UDPipe 1.1 (Praha)             	software2	78.15
18. Orange – Deskiñ (Lannion)               	software1	77.58
19. Uppsala (Uppsala)                       	software1	77.56
20. LATTICE (Paris)                         	software7	75.67
21. IIT Kharagpur (Kharagpur)               	software3	75.37
22. CLCL (Genève)                           	software1	73.97
23. UALING (Tucson)                         	software1	72.99
24. MQuni (Sydney)                          	software2	71.99
25. Mengest (Shanghai)                      	software1	71.53
26. METU (Ankara)                           	software2	71.12
27. OpenU NLP Lab (Ra'anana)                	software6	69.78
28. ParisNLP (Paris)                        	software1	57.83
29. UT (Tartu)                              	software1	54.42
30. MetaRomance (Santiago de Compostela)    	software1	42.56
31. TRL (Tokyo)                             	software1	35.32
32. ECNU (Shanghai)                         	software1	 4.98
33. Wenba-NLU (Wuhan)                       	software1	 1.38
</pre>



### no_bokmaal

<pre>
 1. Stanford (Stanford)                     	software1	89.88
 2. C2L2 (Ithaca)                           	software5	87.70
 3. HIT-SCIR (Harbin)                       	software4	86.90
 4. NAIST SATO (Nara)                       	software1	86.05
 5. IMS (Stuttgart)                         	software2	85.98
 6. LATTICE (Paris)                         	software7	85.55
 7. MQuni (Sydney)                          	software2	84.58
 8. LyS-FASTPARSE (A Coruña)                	software5	84.49
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	83.89
10. UParse (Edinburgh)                      	software1	83.81
11. Orange – Deskiñ (Lannion)               	software1	83.79
12. Koç University (İstanbul)               	software3	83.73
13. TurkuNLP (Turku)                        	software1	83.60
14. LIMSI-LIPN (Paris)                      	software2	83.27
15. BASELINE UDPipe 1.1 (Praha)             	software2	83.27
16. Uppsala (Uppsala)                       	software1	83.22
17. fbaml (Palo Alto)                       	software1	82.60
18. IIT Kharagpur (Kharagpur)               	software3	82.58
19. naistCL (Nara)                          	software1	82.54
20. CLCL (Genève)                           	software1	82.44
21. darc (Tübingen)                         	software1	82.29
22. Wanghao-ftd-SJTU (Shanghai)             	software2	81.18
23. UALING (Tucson)                         	software1	80.56
24. RACAI (București)                       	software1	79.84
25. METU (Ankara)                           	software2	78.51
26. OpenU NLP Lab (Ra'anana)                	software6	76.70
27. Mengest (Shanghai)                      	software1	75.96
28. ParisNLP (Paris)                        	software1	68.58
29. TRL (Tokyo)                             	software1	49.31
30. MetaRomance (Santiago de Compostela)    	software1	42.20
31. Wenba-NLU (Wuhan)                       	software1	 1.06
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### no_nynorsk

<pre>
 1. Stanford (Stanford)                     	software1	88.81
 2. C2L2 (Ithaca)                           	software5	87.05
 3. HIT-SCIR (Harbin)                       	software4	85.43
 4. IMS (Stuttgart)                         	software2	85.05
 5. LATTICE (Paris)                         	software7	84.57
 6. NAIST SATO (Nara)                       	software1	84.39
 7. LyS-FASTPARSE (A Coruña)                	software5	83.10
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	82.74
 9. Koç University (İstanbul)               	software3	82.72
10. TurkuNLP (Turku)                        	software1	82.35
11. MQuni (Sydney)                          	software2	82.12
12. UParse (Edinburgh)                      	software1	81.91
13. Orange – Deskiñ (Lannion)               	software1	81.69
14. LIMSI-LIPN (Paris)                      	software2	81.56
15. BASELINE UDPipe 1.1 (Praha)             	software2	81.56
16. IIT Kharagpur (Kharagpur)               	software3	81.13
17. Uppsala (Uppsala)                       	software1	81.12
18. darc (Tübingen)                         	software1	80.99
19. naistCL (Nara)                          	software1	80.80
20. Wanghao-ftd-SJTU (Shanghai)             	software2	79.85
21. CLCL (Genève)                           	software1	79.34
22. UALING (Tucson)                         	software1	79.16
23. RACAI (București)                       	software1	77.83
24. METU (Ankara)                           	software2	76.19
25. OpenU NLP Lab (Ra'anana)                	software6	71.89
26. Mengest (Shanghai)                      	software1	70.97
27. ParisNLP (Paris)                        	software1	65.11
28. TRL (Tokyo)                             	software1	46.83
29. MetaRomance (Santiago de Compostela)    	software1	39.10
30. fbaml (Palo Alto)                       	software1	 6.57
31. Wenba-NLU (Wuhan)                       	software1	 0.74
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pl

<pre>
 1. Stanford (Stanford)                     	software1	90.32
 2. C2L2 (Ithaca)                           	software5	87.15
 3. IMS (Stuttgart)                         	software2	86.75
 4. LATTICE (Paris)                         	software7	85.94
 5. HIT-SCIR (Harbin)                       	software4	83.75
 6. MQuni (Sydney)                          	software2	82.17
 7. LyS-FASTPARSE (A Coruña)                	software5	82.09
 8. Orange – Deskiñ (Lannion)               	software1	81.71
 9. Koç University (İstanbul)               	software3	80.84
10. NAIST SATO (Nara)                       	software1	80.68
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.21
12. TurkuNLP (Turku)                        	software1	80.11
13. LIMSI-LIPN (Paris)                      	software2	79.95
14. CLCL (Genève)                           	software1	79.83
15. darc (Tübingen)                         	software1	79.72
16. IIT Kharagpur (Kharagpur)               	software3	79.30
17. naistCL (Nara)                          	software1	79.28
18. UParse (Edinburgh)                      	software1	78.78
19. BASELINE UDPipe 1.1 (Praha)             	software2	78.78
20. fbaml (Palo Alto)                       	software1	78.61
21. RACAI (București)                       	software1	78.29
22. Wanghao-ftd-SJTU (Shanghai)             	software2	78.26
23. UALING (Tucson)                         	software1	78.24
24. Uppsala (Uppsala)                       	software1	77.39
25. METU (Ankara)                           	software2	76.40
26. ParisNLP (Paris)                        	software1	71.98
27. Mengest (Shanghai)                      	software1	67.63
28. OpenU NLP Lab (Ra'anana)                	software6	63.03
29. TRL (Tokyo)                             	software1	57.83
30. MetaRomance (Santiago de Compostela)    	software1	40.02
31. Wenba-NLU (Wuhan)                       	software1	 8.96
32. ECNU (Shanghai)                         	software1	 3.96
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt

<pre>
 1. Stanford (Stanford)                     	software1	87.65
 2. IMS (Stuttgart)                         	software2	85.11
 3. C2L2 (Ithaca)                           	software5	85.01
 4. HIT-SCIR (Harbin)                       	software4	84.90
 5. NAIST SATO (Nara)                       	software1	84.35
 6. LATTICE (Paris)                         	software7	84.08
 7. MQuni (Sydney)                          	software2	83.39
 8. UParse (Edinburgh)                      	software1	83.12
 9. Koç University (İstanbul)               	software3	82.92
10. TurkuNLP (Turku)                        	software1	82.91
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	82.72
12. LIMSI-LIPN (Paris)                      	software2	82.19
13. BASELINE UDPipe 1.1 (Praha)             	software2	82.11
14. fbaml (Palo Alto)                       	software1	82.03
15. naistCL (Nara)                          	software1	81.94
16. RACAI (București)                       	software1	81.92
17. darc (Tübingen)                         	software1	81.40
18. Uppsala (Uppsala)                       	software1	80.97
19. LyS-FASTPARSE (A Coruña)                	software5	80.91
20. IIT Kharagpur (Kharagpur)               	software3	80.77
21. Wanghao-ftd-SJTU (Shanghai)             	software2	80.27
22. CLCL (Genève)                           	software1	79.74
23. ParisNLP (Paris)                        	software1	79.21
24. METU (Ankara)                           	software2	76.48
25. Orange – Deskiñ (Lannion)               	software1	76.40
26. MetaRomance (Santiago de Compostela)    	software1	65.50
27. Mengest (Shanghai)                      	software1	62.85
28. OpenU NLP Lab (Ra'anana)                	software6	53.67
29. TRL (Tokyo)                             	software1	40.46
30. UALING (Tucson)                         	software1	36.40
31. Wenba-NLU (Wuhan)                       	software1	 5.09
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_br

<pre>
 1. Stanford (Stanford)                     	software1	91.36
 2. C2L2 (Ithaca)                           	software5	89.35
 3. HIT-SCIR (Harbin)                       	software4	88.71
 4. LATTICE (Paris)                         	software7	88.56
 5. MQuni (Sydney)                          	software2	87.91
 6. NAIST SATO (Nara)                       	software1	87.73
 7. IMS (Stuttgart)                         	software2	87.10
 8. Orange – Deskiñ (Lannion)               	software1	87.07
 9. LyS-FASTPARSE (A Coruña)                	software5	86.74
10. Koç University (İstanbul)               	software3	86.70
11. UParse (Edinburgh)                      	software1	86.38
12. TurkuNLP (Turku)                        	software1	86.36
13. Uppsala (Uppsala)                       	software1	86.15
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	85.97
15. naistCL (Nara)                          	software1	85.86
16. fbaml (Palo Alto)                       	software1	85.41
17. LIMSI-LIPN (Paris)                      	software2	85.36
18. BASELINE UDPipe 1.1 (Praha)             	software2	85.36
19. darc (Tübingen)                         	software1	84.98
20. IIT Kharagpur (Kharagpur)               	software3	84.40
21. CLCL (Genève)                           	software1	84.00
22. Wanghao-ftd-SJTU (Shanghai)             	software2	83.56
23. RACAI (București)                       	software1	83.54
24. METU (Ankara)                           	software2	83.17
25. UALING (Tucson)                         	software1	82.58
26. OpenU NLP Lab (Ra'anana)                	software6	80.65
27. Mengest (Shanghai)                      	software1	79.71
28. ParisNLP (Paris)                        	software1	61.30
29. MetaRomance (Santiago de Compostela)    	software1	56.18
30. TRL (Tokyo)                             	software1	43.76
31. Wenba-NLU (Wuhan)                       	software1	 1.50
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_pud

<pre>
 1. C2L2 (Ithaca)                           	software5	78.48
 2. Stanford (Stanford)                     	software1	77.14
 3. LATTICE (Paris)                         	software7	76.56
 4. NAIST SATO (Nara)                       	software1	76.35
 5. IMS (Stuttgart)                         	software2	75.53
 6. Koç University (İstanbul)               	software3	75.02
 7. ParisNLP (Paris)                        	software1	75.00
 8. MQuni (Sydney)                          	software2	74.81
 9. UParse (Edinburgh)                      	software1	74.76
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.43
11. naistCL (Nara)                          	software1	74.19
12. TurkuNLP (Turku)                        	software1	74.09
13. BASELINE UDPipe 1.1 (Praha)             	software2	73.96
14. darc (Tübingen)                         	software1	73.65
15. RACAI (București)                       	software1	73.27
16. IIT Kharagpur (Kharagpur)               	software3	73.02
17. CLCL (Genève)                           	software1	73.01
18. fbaml (Palo Alto)                       	software1	72.85
19. Uppsala (Uppsala)                       	software1	72.43
20. HIT-SCIR (Harbin)                       	software4	72.33
21. Wanghao-ftd-SJTU (Shanghai)             	software2	72.30
22. Orange – Deskiñ (Lannion)               	software1	69.00
23. METU (Ankara)                           	software2	68.97
24. MetaRomance (Santiago de Compostela)    	software1	66.35
25. LIMSI-LIPN (Paris)                      	software2	59.50
26. Mengest (Shanghai)                      	software1	59.32
27. LyS-FASTPARSE (A Coruña)                	software5	54.75
28. OpenU NLP Lab (Ra'anana)                	software6	53.89
29. TRL (Tokyo)                             	software1	44.86
30. UALING (Tucson)                         	software1	35.76
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ro

<pre>
 1. Stanford (Stanford)                     	software1	85.92
 2. C2L2 (Ithaca)                           	software5	84.40
 3. IMS (Stuttgart)                         	software2	83.50
 4. HIT-SCIR (Harbin)                       	software4	82.21
 5. LATTICE (Paris)                         	software7	81.93
 6. NAIST SATO (Nara)                       	software1	81.66
 7. Koç University (İstanbul)               	software3	81.48
 8. Orange – Deskiñ (Lannion)               	software1	81.34
 9. fbaml (Palo Alto)                       	software1	81.19
10. TurkuNLP (Turku)                        	software1	80.71
11. LyS-FASTPARSE (A Coruña)                	software5	80.58
12. MQuni (Sydney)                          	software2	80.53
13. UParse (Edinburgh)                      	software1	80.45
14. darc (Tübingen)                         	software1	80.42
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.32
16. LIMSI-LIPN (Paris)                      	software2	80.11
17. BASELINE UDPipe 1.1 (Praha)             	software2	79.88
18. RACAI (București)                       	software1	79.44
19. Uppsala (Uppsala)                       	software1	79.40
20. naistCL (Nara)                          	software1	79.37
21. IIT Kharagpur (Kharagpur)               	software3	78.46
22. Wanghao-ftd-SJTU (Shanghai)             	software2	78.22
23. CLCL (Genève)                           	software1	77.34
24. METU (Ankara)                           	software2	76.75
25. UT (Tartu)                              	software1	76.73
26. ParisNLP (Paris)                        	software1	76.69
27. UALING (Tucson)                         	software1	76.68
28. OpenU NLP Lab (Ra'anana)                	software6	72.14
29. Mengest (Shanghai)                      	software1	64.38
30. TRL (Tokyo)                             	software1	53.35
31. MetaRomance (Santiago de Compostela)    	software1	45.04
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### ru

<pre>
 1. Stanford (Stanford)                     	software1	83.65
 2. C2L2 (Ithaca)                           	software5	83.50
 3. IMS (Stuttgart)                         	software2	81.49
 4. HIT-SCIR (Harbin)                       	software4	80.58
 5. LATTICE (Paris)                         	software7	78.42
 6. NAIST SATO (Nara)                       	software1	77.63
 7. Koç University (İstanbul)               	software3	77.11
 8. LyS-FASTPARSE (A Coruña)                	software5	76.98
 9. MQuni (Sydney)                          	software2	76.65
10. fbaml (Palo Alto)                       	software1	76.53
11. Orange – Deskiñ (Lannion)               	software1	76.28
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.15
13. LIMSI-LIPN (Paris)                      	software2	75.65
14. RACAI (București)                       	software1	75.54
15. naistCL (Nara)                          	software1	74.86
16. darc (Tübingen)                         	software1	74.83
17. TurkuNLP (Turku)                        	software1	74.69
18. IIT Kharagpur (Kharagpur)               	software3	74.60
19. UParse (Edinburgh)                      	software1	74.03
20. BASELINE UDPipe 1.1 (Praha)             	software2	74.03
21. UALING (Tucson)                         	software1	73.56
22. CLCL (Genève)                           	software1	72.03
23. Uppsala (Uppsala)                       	software1	71.65
24. METU (Ankara)                           	software2	71.40
25. ParisNLP (Paris)                        	software1	66.83
26. OpenU NLP Lab (Ra'anana)                	software6	57.09
27. Mengest (Shanghai)                      	software1	56.56
28. Wanghao-ftd-SJTU (Shanghai)             	software2	53.09
29. TRL (Tokyo)                             	software1	45.52
30. MetaRomance (Santiago de Compostela)    	software1	45.01
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ru_pud

<pre>
 1. Stanford (Stanford)                     	software1	75.71
 2. LATTICE (Paris)                         	software7	72.03
 3. Koç University (İstanbul)               	software3	71.20
 4. NAIST SATO (Nara)                       	software1	70.51
 5. Orange – Deskiñ (Lannion)               	software1	69.58
 6. fbaml (Palo Alto)                       	software1	69.46
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	69.37
 8. TurkuNLP (Turku)                        	software1	69.11
 9. RACAI (București)                       	software1	68.96
10. MQuni (Sydney)                          	software2	68.88
11. UParse (Edinburgh)                      	software1	68.64
12. darc (Tübingen)                         	software1	68.61
13. BASELINE UDPipe 1.1 (Praha)             	software2	68.31
14. naistCL (Nara)                          	software1	68.10
15. UALING (Tucson)                         	software1	67.64
16. CLCL (Genève)                           	software1	67.22
17. ParisNLP (Paris)                        	software1	66.17
18. METU (Ankara)                           	software2	65.81
19. Uppsala (Uppsala)                       	software1	65.22
20. IIT Kharagpur (Kharagpur)               	software3	65.03
21. IMS (Stuttgart)                         	software2	62.72
22. C2L2 (Ithaca)                           	software5	61.82
23. HIT-SCIR (Harbin)                       	software4	61.60
24. Mengest (Shanghai)                      	software1	52.73
25. LIMSI-LIPN (Paris)                      	software2	52.36
26. OpenU NLP Lab (Ra'anana)                	software6	52.14
27. TRL (Tokyo)                             	software1	49.04
28. UT (Tartu)                              	software1	45.63
29. Wanghao-ftd-SJTU (Shanghai)             	software2	45.57
30. MetaRomance (Santiago de Compostela)    	software1	44.85
31. LyS-FASTPARSE (A Coruña)                	software5	44.69
32. ECNU (Shanghai)                         	software1	20.04
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### ru_syntagrus

<pre>
 1. Stanford (Stanford)                     	software1	92.60
 2. C2L2 (Ithaca)                           	software5	90.03
 3. IMS (Stuttgart)                         	software2	89.80
 4. HIT-SCIR (Harbin)                       	software4	89.77
 5. NAIST SATO (Nara)                       	software1	89.31
 6. UParse (Edinburgh)                      	software1	89.18
 7. Uppsala (Uppsala)                       	software1	88.04
 8. LATTICE (Paris)                         	software7	87.90
 9. LyS-FASTPARSE (A Coruña)                	software5	87.55
10. Orange – Deskiñ (Lannion)               	software1	87.10
11. fbaml (Palo Alto)                       	software1	86.83
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	86.80
13. TurkuNLP (Turku)                        	software1	86.79
14. LIMSI-LIPN (Paris)                      	software2	86.76
15. BASELINE UDPipe 1.1 (Praha)             	software2	86.76
16. darc (Tübingen)                         	software1	86.39
17. MQuni (Sydney)                          	software2	86.34
18. naistCL (Nara)                          	software1	85.43
19. RACAI (București)                       	software1	85.41
20. Koç University (İstanbul)               	software3	85.24
21. IIT Kharagpur (Kharagpur)               	software3	85.00
22. Wanghao-ftd-SJTU (Shanghai)             	software2	84.43
23. CLCL (Genève)                           	software1	83.89
24. Mengest (Shanghai)                      	software1	82.42
25. METU (Ankara)                           	software2	80.88
26. OpenU NLP Lab (Ra'anana)                	software6	75.63
27. TRL (Tokyo)                             	software1	61.66
28. ParisNLP (Paris)                        	software1	54.19
29. UALING (Tucson)                         	software1	52.22
30. MetaRomance (Santiago de Compostela)    	software1	38.96
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sk

<pre>
 1. Stanford (Stanford)                     	software1	86.04
 2. C2L2 (Ithaca)                           	software5	81.75
 3. IMS (Stuttgart)                         	software2	80.53
 4. HIT-SCIR (Harbin)                       	software4	79.82
 5. LATTICE (Paris)                         	software7	79.23
 6. LyS-FASTPARSE (A Coruña)                	software5	76.47
 7. Koç University (İstanbul)               	software3	76.46
 8. fbaml (Palo Alto)                       	software1	76.23
 9. Orange – Deskiñ (Lannion)               	software1	75.97
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.63
11. NAIST SATO (Nara)                       	software1	75.28
12. TurkuNLP (Turku)                        	software1	74.72
13. LIMSI-LIPN (Paris)                      	software2	74.45
14. RACAI (București)                       	software1	74.26
15. MQuni (Sydney)                          	software2	73.67
16. darc (Tübingen)                         	software1	73.49
17. IIT Kharagpur (Kharagpur)               	software3	73.33
18. CLCL (Genève)                           	software1	73.30
19. UALING (Tucson)                         	software1	72.95
20. UParse (Edinburgh)                      	software1	72.75
21. BASELINE UDPipe 1.1 (Praha)             	software2	72.75
22. Wanghao-ftd-SJTU (Shanghai)             	software2	72.42
23. naistCL (Nara)                          	software1	72.04
24. METU (Ankara)                           	software2	70.96
25. Uppsala (Uppsala)                       	software1	69.35
26. ParisNLP (Paris)                        	software1	67.72
27. Mengest (Shanghai)                      	software1	60.48
28. OpenU NLP Lab (Ra'anana)                	software6	50.25
29. MetaRomance (Santiago de Compostela)    	software1	38.74
30. TRL (Tokyo)                             	software1	38.69
31. ECNU (Shanghai)                         	software1	 2.66
32. Wenba-NLU (Wuhan)                       	software1	 0.98
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl

<pre>
 1. Stanford (Stanford)                     	software1	91.51
 2. C2L2 (Ithaca)                           	software5	88.24
 3. HIT-SCIR (Harbin)                       	software4	87.08
 4. IMS (Stuttgart)                         	software2	85.86
 5. LATTICE (Paris)                         	software7	84.52
 6. NAIST SATO (Nara)                       	software1	84.06
 7. LyS-FASTPARSE (A Coruña)                	software5	82.92
 8. TurkuNLP (Turku)                        	software1	82.77
 9. Orange – Deskiñ (Lannion)               	software1	82.38
10. fbaml (Palo Alto)                       	software1	82.19
11. Koç University (İstanbul)               	software3	82.04
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	81.84
13. LIMSI-LIPN (Paris)                      	software2	81.37
14. CLCL (Genève)                           	software1	81.32
15. UParse (Edinburgh)                      	software1	81.15
16. BASELINE UDPipe 1.1 (Praha)             	software2	81.15
17. MQuni (Sydney)                          	software2	81.13
18. darc (Tübingen)                         	software1	81.05
19. Wanghao-ftd-SJTU (Shanghai)             	software2	80.68
20. IIT Kharagpur (Kharagpur)               	software3	80.53
21. naistCL (Nara)                          	software1	80.28
22. ParisNLP (Paris)                        	software1	80.27
23. Uppsala (Uppsala)                       	software1	80.14
24. RACAI (București)                       	software1	79.61
25. UALING (Tucson)                         	software1	79.29
26. METU (Ankara)                           	software2	78.14
27. OpenU NLP Lab (Ra'anana)                	software6	65.25
28. Mengest (Shanghai)                      	software1	61.28
29. TRL (Tokyo)                             	software1	47.25
30. MetaRomance (Santiago de Compostela)    	software1	40.72
31. ECNU (Shanghai)                         	software1	 1.75
32. Wenba-NLU (Wuhan)                       	software1	 0.68
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl_sst

<pre>
 1. C2L2 (Ithaca)                           	software5	59.07
 2. Stanford (Stanford)                     	software1	56.02
 3. IMS (Stuttgart)                         	software2	55.88
 4. HIT-SCIR (Harbin)                       	software4	54.06
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	53.94
 6. NAIST SATO (Nara)                       	software1	50.16
 7. LATTICE (Paris)                         	software7	49.94
 8. Koç University (İstanbul)               	software3	49.56
 9. fbaml (Palo Alto)                       	software1	49.53
10. RACAI (București)                       	software1	48.13
11. TurkuNLP (Turku)                        	software1	47.50
12. darc (Tübingen)                         	software1	47.41
13. UParse (Edinburgh)                      	software1	46.97
14. Wanghao-ftd-SJTU (Shanghai)             	software2	46.83
15. LIMSI-LIPN (Paris)                      	software2	46.71
16. BASELINE UDPipe 1.1 (Praha)             	software2	46.45
17. UALING (Tucson)                         	software1	46.09
18. IIT Kharagpur (Kharagpur)               	software3	45.75
19. naistCL (Nara)                          	software1	44.07
20. MQuni (Sydney)                          	software2	44.00
21. LyS-FASTPARSE (A Coruña)                	software5	43.80
22. Orange – Deskiñ (Lannion)               	software1	40.25
23. ParisNLP (Paris)                        	software1	40.15
24. METU (Ankara)                           	software2	38.00
25. OpenU NLP Lab (Ra'anana)                	software6	37.57
26. Uppsala (Uppsala)                       	software1	36.97
27. TRL (Tokyo)                             	software1	29.92
28. Mengest (Shanghai)                      	software1	23.77
29. MetaRomance (Santiago de Compostela)    	software1	21.38
30. CLCL (Genève)                           	software1	 4.37
31. ECNU (Shanghai)                         	software1	 1.45
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sme

<pre>
 1. C2L2 (Ithaca)                           	software5	48.96
 2. IMS (Stuttgart)                         	software2	40.67
 3. HIT-SCIR (Harbin)                       	software4	38.91
 4. Koç University (İstanbul)               	software3	37.93
 5. ParisNLP (Paris)                        	software1	37.33
 6. Stanford (Stanford)                     	software1	37.21
 7. UParse (Edinburgh)                      	software1	36.04
 8. RACAI (București)                       	software1	35.47
 9. IIT Kharagpur (Kharagpur)               	software3	35.25
10. darc (Tübingen)                         	software1	34.89
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	33.62
12. Wanghao-ftd-SJTU (Shanghai)             	software2	33.39
13. Orange – Deskiñ (Lannion)               	software1	33.08
14. LyS-FASTPARSE (A Coruña)                	software5	32.58
15. UALING (Tucson)                         	software1	31.77
16. LIMSI-LIPN (Paris)                      	software2	31.03
17. BASELINE UDPipe 1.1 (Praha)             	software2	30.60
18. LATTICE (Paris)                         	software7	28.39
19. OpenU NLP Lab (Ra'anana)                	software6	28.36
20. naistCL (Nara)                          	software1	27.18
21. CLCL (Genève)                           	software2	23.99
22. METU (Ankara)                           	software2	23.95
23. NAIST SATO (Nara)                       	software1	23.54
24. MetaRomance (Santiago de Compostela)    	software1	22.23
25. fbaml (Palo Alto)                       	software1	17.10
26. Uppsala (Uppsala)                       	software1	11.70
27. TurkuNLP (Turku)                        	software1	10.99
28. Mengest (Shanghai)                      	software1	10.00
29. MQuni (Sydney)                          	software2	 8.31
30. TRL (Tokyo)                             	software1	 7.47
31. ECNU (Shanghai)                         	software1	 2.89
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv

<pre>
 1. Stanford (Stanford)                     	software1	85.87
 2. C2L2 (Ithaca)                           	software5	84.98
 3. IMS (Stuttgart)                         	software2	82.28
 4. LATTICE (Paris)                         	software7	81.07
 5. HIT-SCIR (Harbin)                       	software4	80.58
 6. NAIST SATO (Nara)                       	software1	79.68
 7. Orange – Deskiñ (Lannion)               	software1	78.85
 8. MQuni (Sydney)                          	software2	78.34
 9. Koç University (İstanbul)               	software3	78.31
10. fbaml (Palo Alto)                       	software1	77.70
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.58
12. TurkuNLP (Turku)                        	software1	77.35
13. LyS-FASTPARSE (A Coruña)                	software5	77.33
14. IIT Kharagpur (Kharagpur)               	software3	76.92
15. ParisNLP (Paris)                        	software1	76.77
16. LIMSI-LIPN (Paris)                      	software2	76.73
17. BASELINE UDPipe 1.1 (Praha)             	software2	76.73
18. darc (Tübingen)                         	software1	76.45
19. naistCL (Nara)                          	software1	76.11
20. CLCL (Genève)                           	software1	76.06
21. Wanghao-ftd-SJTU (Shanghai)             	software2	75.71
22. UALING (Tucson)                         	software1	75.32
23. UParse (Edinburgh)                      	software1	75.29
24. METU (Ankara)                           	software2	74.06
25. RACAI (București)                       	software1	73.56
26. Uppsala (Uppsala)                       	software1	73.45
27. OpenU NLP Lab (Ra'anana)                	software6	70.37
28. Mengest (Shanghai)                      	software1	61.43
29. TRL (Tokyo)                             	software1	45.17
30. MetaRomance (Santiago de Compostela)    	software1	37.31
31. Wenba-NLU (Wuhan)                       	software1	 0.82
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_lines

<pre>
 1. Stanford (Stanford)                     	software1	82.89
 2. C2L2 (Ithaca)                           	software5	82.29
 3. IMS (Stuttgart)                         	software2	78.88
 4. LATTICE (Paris)                         	software7	78.15
 5. HIT-SCIR (Harbin)                       	software4	77.30
 6. NAIST SATO (Nara)                       	software1	76.63
 7. Koç University (İstanbul)               	software3	75.71
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.57
 9. MQuni (Sydney)                          	software2	75.36
10. LyS-FASTPARSE (A Coruña)                	software5	75.04
11. fbaml (Palo Alto)                       	software1	74.89
12. IIT Kharagpur (Kharagpur)               	software3	74.74
13. TurkuNLP (Turku)                        	software1	74.46
14. LIMSI-LIPN (Paris)                      	software2	74.29
15. BASELINE UDPipe 1.1 (Praha)             	software2	74.29
16. Orange – Deskiñ (Lannion)               	software1	74.28
17. UParse (Edinburgh)                      	software1	74.04
18. CLCL (Genève)                           	software1	73.82
19. darc (Tübingen)                         	software1	73.62
20. naistCL (Nara)                          	software1	73.43
21. Wanghao-ftd-SJTU (Shanghai)             	software2	73.31
22. UALING (Tucson)                         	software1	72.63
23. METU (Ankara)                           	software2	71.93
24. RACAI (București)                       	software1	70.72
25. Uppsala (Uppsala)                       	software1	69.42
26. OpenU NLP Lab (Ra'anana)                	software6	69.21
27. ParisNLP (Paris)                        	software1	63.50
28. Mengest (Shanghai)                      	software1	61.09
29. TRL (Tokyo)                             	software1	47.13
30. MetaRomance (Santiago de Compostela)    	software1	32.32
31. ECNU (Shanghai)                         	software1	 3.65
32. Wenba-NLU (Wuhan)                       	software1	 0.24
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_pud

<pre>
 1. Stanford (Stanford)                     	software1	78.49
 2. C2L2 (Ithaca)                           	software5	77.97
 3. IMS (Stuttgart)                         	software2	74.41
 4. LATTICE (Paris)                         	software7	73.40
 5. NAIST SATO (Nara)                       	software1	72.89
 6. Koç University (İstanbul)               	software3	72.36
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.88
 8. ParisNLP (Paris)                        	software1	70.83
 9. Orange – Deskiñ (Lannion)               	software1	70.82
10. fbaml (Palo Alto)                       	software1	70.76
11. HIT-SCIR (Harbin)                       	software4	70.70
12. BASELINE UDPipe 1.1 (Praha)             	software2	70.62
13. IIT Kharagpur (Kharagpur)               	software3	70.49
14. MQuni (Sydney)                          	software2	70.46
15. UParse (Edinburgh)                      	software1	70.44
16. TurkuNLP (Turku)                        	software1	69.90
17. LyS-FASTPARSE (A Coruña)                	software5	69.60
18. UALING (Tucson)                         	software1	69.43
19. naistCL (Nara)                          	software1	69.13
20. darc (Tübingen)                         	software1	68.94
21. CLCL (Genève)                           	software1	68.92
22. Wanghao-ftd-SJTU (Shanghai)             	software2	68.84
23. RACAI (București)                       	software1	68.40
24. METU (Ankara)                           	software2	67.38
25. Uppsala (Uppsala)                       	software1	62.40
26. OpenU NLP Lab (Ra'anana)                	software6	61.42
27. Mengest (Shanghai)                      	software1	54.83
28. LIMSI-LIPN (Paris)                      	software2	49.41
29. TRL (Tokyo)                             	software1	42.58
30. MetaRomance (Santiago de Compostela)    	software1	40.50
31. ECNU (Shanghai)                         	software1	 2.88
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr

<pre>
 1. Stanford (Stanford)                     	software1	62.79
 2. C2L2 (Ithaca)                           	software5	62.66
 3. IMS (Stuttgart)                         	software2	62.39
 4. LATTICE (Paris)                         	software7	58.89
 5. LyS-FASTPARSE (A Coruña)                	software5	57.22
 6. Koç University (İstanbul)               	software3	56.80
 7. HIT-SCIR (Harbin)                       	software4	56.43
 8. MQuni (Sydney)                          	software2	56.18
 9. RACAI (București)                       	software1	55.74
10. LIMSI-LIPN (Paris)                      	software2	55.23
11. Orange – Deskiñ (Lannion)               	software1	55.21
12. darc (Tübingen)                         	software1	54.70
13. TurkuNLP (Turku)                        	software1	54.69
14. IIT Kharagpur (Kharagpur)               	software3	54.21
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	53.78
16. UParse (Edinburgh)                      	software1	53.22
17. BASELINE UDPipe 1.1 (Praha)             	software2	53.19
18. naistCL (Nara)                          	software1	53.10
19. fbaml (Palo Alto)                       	software1	53.08
20. Wanghao-ftd-SJTU (Shanghai)             	software2	51.67
21. NAIST SATO (Nara)                       	software1	51.44
22. UALING (Tucson)                         	software1	50.69
23. Mengest (Shanghai)                      	software1	49.11
24. METU (Ankara)                           	software2	48.53
25. Uppsala (Uppsala)                       	software1	48.29
26. CLCL (Genève)                           	software1	47.91
27. ParisNLP (Paris)                        	software1	46.38
28. OpenU NLP Lab (Ra'anana)                	software6	39.81
29. TRL (Tokyo)                             	software1	30.48
30. Wenba-NLU (Wuhan)                       	software1	 0.61
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr_pud

<pre>
 1. IMS (Stuttgart)                         	software2	38.22
 2. Stanford (Stanford)                     	software1	37.72
 3. C2L2 (Ithaca)                           	software5	37.65
 4. LyS-FASTPARSE (A Coruña)                	software5	34.96
 5. LATTICE (Paris)                         	software7	34.82
 6. Koç University (İstanbul)               	software3	34.65
 7. BASELINE UDPipe 1.1 (Praha)             	software2	34.53
 8. naistCL (Nara)                          	software1	34.44
 9. darc (Tübingen)                         	software1	34.37
10. Orange – Deskiñ (Lannion)               	software1	34.36
11. LIMSI-LIPN (Paris)                      	software2	34.15
12. HIT-SCIR (Harbin)                       	software4	34.15
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	34.12
14. IIT Kharagpur (Kharagpur)               	software3	34.11
15. TurkuNLP (Turku)                        	software1	34.09
16. UALING (Tucson)                         	software1	33.55
17. RACAI (București)                       	software1	33.20
18. Wanghao-ftd-SJTU (Shanghai)             	software2	33.03
19. MQuni (Sydney)                          	software2	32.87
20. UParse (Edinburgh)                      	software1	32.63
21. fbaml (Palo Alto)                       	software1	31.53
22. NAIST SATO (Nara)                       	software1	31.17
23. Uppsala (Uppsala)                       	software1	29.79
24. METU (Ankara)                           	software2	29.24
25. CLCL (Genève)                           	software1	29.01
26. ParisNLP (Paris)                        	software1	25.78
27. OpenU NLP Lab (Ra'anana)                	software6	23.90
28. Mengest (Shanghai)                      	software1	22.52
29. TRL (Tokyo)                             	software1	21.36
30. MetaRomance (Santiago de Compostela)    	software1	10.86
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ug

<pre>
 1. IMS (Stuttgart)                         	software2	43.51
 2. C2L2 (Ithaca)                           	software5	41.76
 3. Stanford (Stanford)                     	software1	39.79
 4. RACAI (București)                       	software1	38.76
 5. MQuni (Sydney)                          	software2	36.61
 6. TurkuNLP (Turku)                        	software1	36.51
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	35.67
 8. UALING (Tucson)                         	software1	34.97
 9. LATTICE (Paris)                         	software7	34.94
10. LIMSI-LIPN (Paris)                      	software2	34.70
11. fbaml (Palo Alto)                       	software1	34.57
12. HIT-SCIR (Harbin)                       	software4	34.52
13. IIT Kharagpur (Kharagpur)               	software3	34.38
14. darc (Tübingen)                         	software1	34.28
15. Orange – Deskiñ (Lannion)               	software1	34.24
16. UParse (Edinburgh)                      	software1	34.18
17. BASELINE UDPipe 1.1 (Praha)             	software2	34.18
18. ÚFAL – UDPipe 1.2 (Praha)               	software1	33.21
19. NAIST SATO (Nara)                       	software1	33.19
20. naistCL (Nara)                          	software1	32.03
21. Koç University (İstanbul)               	software3	31.59
22. Uppsala (Uppsala)                       	software1	28.35
23. LyS-FASTPARSE (A Coruña)                	software5	27.92
24. TRL (Tokyo)                             	software1	23.72
25. ParisNLP (Paris)                        	software1	19.65
26. METU (Ankara)                           	software2	15.66
27. CLCL (Genève)                           	software1	 9.29
28. MetaRomance (Santiago de Compostela)    	software1	 7.70
29. OpenU NLP Lab (Ra'anana)                	software6	 7.35
30. ECNU (Shanghai)                         	software1	 2.37
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. Mengest (Shanghai)                      	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### uk

<pre>
 1. Stanford (Stanford)                     	software1	75.33
 2. C2L2 (Ithaca)                           	software5	72.22
 3. IMS (Stuttgart)                         	software2	69.27
 4. ParisNLP (Paris)                        	software1	65.52
 5. fbaml (Palo Alto)                       	software1	65.17
 6. Koç University (İstanbul)               	software3	63.76
 7. TurkuNLP (Turku)                        	software1	63.70
 8. LATTICE (Paris)                         	software7	63.63
 9. RACAI (București)                       	software1	63.54
10. HIT-SCIR (Harbin)                       	software4	63.08
11. Orange – Deskiñ (Lannion)               	software1	62.30
12. Wanghao-ftd-SJTU (Shanghai)             	software2	62.13
13. darc (Tübingen)                         	software1	62.03
14. LIMSI-LIPN (Paris)                      	software2	61.68
15. LyS-FASTPARSE (A Coruña)                	software5	61.21
16. UALING (Tucson)                         	software1	61.12
17. ÚFAL – UDPipe 1.2 (Praha)               	software1	61.09
18. UParse (Edinburgh)                      	software1	60.76
19. BASELINE UDPipe 1.1 (Praha)             	software2	60.76
20. MQuni (Sydney)                          	software2	60.74
21. NAIST SATO (Nara)                       	software1	60.73
22. naistCL (Nara)                          	software1	59.81
23. Uppsala (Uppsala)                       	software1	47.00
24. OpenU NLP Lab (Ra'anana)                	software6	42.28
25. IIT Kharagpur (Kharagpur)               	software3	40.55
26. MetaRomance (Santiago de Compostela)    	software1	36.85
27. TRL (Tokyo)                             	software1	33.99
28. METU (Ankara)                           	software2	31.68
29. Mengest (Shanghai)                      	software1	20.61
30. CLCL (Genève)                           	software1	 7.87
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ur

<pre>
 1. Stanford (Stanford)                     	software1	82.28
 2. C2L2 (Ithaca)                           	software5	81.06
 3. IMS (Stuttgart)                         	software2	80.93
 4. HIT-SCIR (Harbin)                       	software4	79.72
 5. NAIST SATO (Nara)                       	software1	79.38
 6. LATTICE (Paris)                         	software7	79.26
 7. MQuni (Sydney)                          	software2	79.24
 8. fbaml (Palo Alto)                       	software1	78.61
 9. LyS-FASTPARSE (A Coruña)                	software5	78.31
10. Orange – Deskiñ (Lannion)               	software1	77.93
11. Koç University (İstanbul)               	software3	77.64
12. darc (Tübingen)                         	software1	77.21
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.09
14. TurkuNLP (Turku)                        	software1	77.06
15. naistCL (Nara)                          	software1	77.02
16. IIT Kharagpur (Kharagpur)               	software3	77.00
17. BASELINE UDPipe 1.1 (Praha)             	software2	76.69
18. LIMSI-LIPN (Paris)                      	software2	76.65
19. UParse (Edinburgh)                      	software1	76.35
20. CLCL (Genève)                           	software1	76.01
21. Wanghao-ftd-SJTU (Shanghai)             	software2	75.41
22. METU (Ankara)                           	software2	75.40
23. RACAI (București)                       	software1	75.17
24. UALING (Tucson)                         	software1	74.92
25. OpenU NLP Lab (Ra'anana)                	software6	69.86
26. Uppsala (Uppsala)                       	software1	64.96
27. Mengest (Shanghai)                      	software1	61.77
28. TRL (Tokyo)                             	software1	50.26
29. ParisNLP (Paris)                        	software1	39.73
30. MetaRomance (Santiago de Compostela)    	software1	 7.59
31. Wenba-NLU (Wuhan)                       	software1	 1.31
32. ECNU (Shanghai)                         	software1	 0.59
33. UT (Tartu)                              	software1	 0.00
</pre>



### vi

<pre>
 1. IMS (Stuttgart)                         	software2	47.51
 2. HIT-SCIR (Harbin)                       	software4	42.52
 3. Stanford (Stanford)                     	software1	42.13
 4. LIMSI-LIPN (Paris)                      	software2	42.02
 5. C2L2 (Ithaca)                           	software5	41.68
 6. fbaml (Palo Alto)                       	software1	40.89
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	39.97
 8. LATTICE (Paris)                         	software7	39.87
 9. Orange – Deskiñ (Lannion)               	software1	39.12
10. NAIST SATO (Nara)                       	software1	38.99
11. MQuni (Sydney)                          	software2	38.67
12. LyS-FASTPARSE (A Coruña)                	software5	38.33
13. Koç University (İstanbul)               	software3	38.30
14. TurkuNLP (Turku)                        	software1	38.07
15. Uppsala (Uppsala)                       	software1	37.99
16. naistCL (Nara)                          	software1	37.87
17. UParse (Edinburgh)                      	software1	37.47
18. BASELINE UDPipe 1.1 (Praha)             	software2	37.47
19. darc (Tübingen)                         	software1	37.31
20. Wanghao-ftd-SJTU (Shanghai)             	software2	37.05
21. IIT Kharagpur (Kharagpur)               	software3	36.88
22. METU (Ankara)                           	software2	36.51
23. OpenU NLP Lab (Ra'anana)                	software6	36.51
24. UALING (Tucson)                         	software1	35.98
25. CLCL (Genève)                           	software1	35.77
26. RACAI (București)                       	software1	34.19
27. ParisNLP (Paris)                        	software1	33.00
28. Mengest (Shanghai)                      	software1	31.67
29. TRL (Tokyo)                             	software1	31.01
30. MetaRomance (Santiago de Compostela)    	software1	11.93
31. ECNU (Shanghai)                         	software1	 1.33
32. Wenba-NLU (Wuhan)                       	software1	 0.74
33. UT (Tartu)                              	software1	 0.00
</pre>



### zh

<pre>
 1. IMS (Stuttgart)                         	software2	68.56
 2. Stanford (Stanford)                     	software1	65.88
 3. fbaml (Palo Alto)                       	software1	65.15
 4. HIT-SCIR (Harbin)                       	software4	65.10
 5. C2L2 (Ithaca)                           	software5	64.14
 6. LATTICE (Paris)                         	software7	61.94
 7. Uppsala (Uppsala)                       	software1	60.47
 8. NAIST SATO (Nara)                       	software1	59.99
 9. LIMSI-LIPN (Paris)                      	software2	59.98
10. MQuni (Sydney)                          	software2	59.45
11. Orange – Deskiñ (Lannion)               	software1	59.33
12. TurkuNLP (Turku)                        	software1	58.71
13. Mengest (Shanghai)                      	software1	58.03
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	57.89
15. RACAI (București)                       	software1	57.75
16. naistCL (Nara)                          	software1	57.65
17. UParse (Edinburgh)                      	software1	57.40
18. BASELINE UDPipe 1.1 (Praha)             	software2	57.40
19. Koç University (İstanbul)               	software3	57.15
20. IIT Kharagpur (Kharagpur)               	software3	56.92
21. LyS-FASTPARSE (A Coruña)                	software5	56.76
22. darc (Tübingen)                         	software1	56.44
23. UALING (Tucson)                         	software1	55.85
24. Wanghao-ftd-SJTU (Shanghai)             	software2	55.19
25. CLCL (Genève)                           	software1	54.89
26. METU (Ankara)                           	software2	53.84
27. OpenU NLP Lab (Ra'anana)                	software6	52.93
28. ParisNLP (Paris)                        	software1	45.83
29. ECNU (Shanghai)                         	software1	32.27
30. TRL (Tokyo)                             	software1	25.60
31. MetaRomance (Santiago de Compostela)    	software1	10.87
32. Wenba-NLU (Wuhan)                       	software1	 0.27
33. UT (Tartu)                              	software1	 0.00
</pre>
