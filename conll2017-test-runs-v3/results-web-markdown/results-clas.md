---
layout: page
title: CoNLL 2017 Shared Task
---

# Results: Content Word Labeled Attachment Score (CLAS)

CLAS is a new metric proposed for cross-linguistic comparison of parsing
results (cf. [Nivre and Fang 2017](http://stp.lingfil.uu.se/~nivre/docs/udeval-final.pdf)).
<!--
@inproceedings{nivre17udw,
author = {Nivre, Joakim and Fang, Chiao-Ting},
year = {2017},
title = {Universal Dependency Evaluation},
booktitle = {Proceedings of the NoDaLiDa 2017 Workshop on Universal Dependencies (UDW 2017)},
pages = {86--95}
}
-->
It differs from LAS in that it assigns weight 0
to selected dependency relations which attach function words to content-words,
and which may be realized by morphology in other languages.
The `punct` relation is also ignored (unlike in the main LAS metric of this task).

## All treebanks

<pre>
 1. Stanford (Stanford)                     	software1	72.57
 2. C2L2 (Ithaca)                           	software5	70.91
 3. IMS (Stuttgart)                         	software2	70.18
 4. HIT-SCIR (Harbin)                       	software4	67.63
 5. LATTICE (Paris)                         	software7	66.16
 6. NAIST SATO (Nara)                       	software1	65.15
 7. Koç University (İstanbul)               	software3	64.61
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	64.36
 9. Orange – Deskiñ (Lannion)               	software1	64.15
10. TurkuNLP (Turku)                        	software1	63.61
11. UParse (Edinburgh)                      	software1	63.55
12. darc (Tübingen)                         	software1	63.24
13. BASELINE UDPipe 1.1 (Praha)             	software2	63.02
14. MQuni (Sydney)                          	software2	62.87
15. fbaml (Palo Alto)                       	software1	62.65
16. LIMSI-LIPN (Paris)                      	software2	62.63
17. LyS-FASTPARSE (A Coruña)                	software5	62.52
18. RACAI (București)                       	software1	62.19
19. IIT Kharagpur (Kharagpur)               	software3	62.11
20. naistCL (Nara)                          	software1	62.07
21. Wanghao-ftd-SJTU (Shanghai)             	software2	60.85
22. Uppsala (Uppsala)                       	software1	59.60
23. UALING (Tucson)                         	software1	59.30
24. CLCL (Genève)                           	software2	57.02
25. METU (Ankara)                           	software2	56.26
26. Mengest (Shanghai)                      	software1	55.93
27. ParisNLP (Paris)                        	software1	54.12
28. OpenU NLP Lab (Ra'anana)                	software6	49.18
29. TRL (Tokyo)                             	software1	35.87
30. MetaRomance (Santiago de Compostela)    	software1	28.41
31. UT (Tartu)                              	software1	19.04
32. ECNU (Shanghai)                         	software1	 2.02
33. Wenba-NLU (Wuhan)                       	software1	 0.54
</pre>



## Big treebanks only

Macro-average CLAS-F1 of the 55 big treebanks: ar, bg, ca, cs, cs_cac, cs_cltt, cu, da, de, el, en, en_lines, en_partut, es, es_ancora, et, eu, fa, fi, fi_ftb, fr, fr_sequoia, gl, got, grc, grc_proiel, he, hi, hr, hu, id, it, ja, ko, la_ittb, la_proiel, lv, nl, nl_lassysmall, no_bokmaal, no_nynorsk, pl, pt, pt_br, ro, ru, ru_syntagrus, sk, sl, sv, sv_lines, tr, ur, vi, zh. These are the treebanks that have development data available, hence these results should be comparable to the performance of the systems on the development data.

<pre>
 1. Stanford (Stanford)                     	software1	78.40
 2. C2L2 (Ithaca)                           	software5	75.93
 3. IMS (Stuttgart)                         	software2	75.61
 4. HIT-SCIR (Harbin)                       	software4	73.19
 5. LATTICE (Paris)                         	software7	71.37
 6. NAIST SATO (Nara)                       	software1	70.99
 7. Orange – Deskiñ (Lannion)               	software1	70.14
 8. LyS-FASTPARSE (A Coruña)                	software5	69.64
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	69.59
10. Koç University (İstanbul)               	software3	69.56
11. TurkuNLP (Turku)                        	software1	69.45
12. MQuni (Sydney)                          	software2	69.09
13. LIMSI-LIPN (Paris)                      	software2	68.70
14. UParse (Edinburgh)                      	software1	68.46
15. darc (Tübingen)                         	software1	68.46
16. fbaml (Palo Alto)                       	software1	68.26
17. BASELINE UDPipe 1.1 (Praha)             	software2	68.04
18. IIT Kharagpur (Kharagpur)               	software3	67.53
19. naistCL (Nara)                          	software1	67.38
20. RACAI (București)                       	software1	67.22
21. Uppsala (Uppsala)                       	software1	65.96
22. Wanghao-ftd-SJTU (Shanghai)             	software2	65.76
23. CLCL (Genève)                           	software2	65.72
24. UALING (Tucson)                         	software1	63.80
25. METU (Ankara)                           	software2	63.09
26. Mengest (Shanghai)                      	software1	62.98
27. ParisNLP (Paris)                        	software1	56.53
28. OpenU NLP Lab (Ra'anana)                	software6	53.62
29. TRL (Tokyo)                             	software1	38.35
30. MetaRomance (Santiago de Compostela)    	software1	28.72
31. UT (Tartu)                              	software1	23.51
32. ECNU (Shanghai)                         	software1	 1.96
33. Wenba-NLU (Wuhan)                       	software1	 0.80
</pre>



## PUD treebanks only

Macro-average CLAS-F1 of the 14 PUD treebanks (additional parallel test sets): ar_pud, cs_pud, de_pud, en_pud, es_pud, fi_pud, fr_pud, hi_pud, it_pud, ja_pud, pt_pud, ru_pud, sv_pud, tr_pud. These are languages for which there exists at least one big training treebank. However, these test sets have been produced separately and their domain may differ.

<pre>
 1. Stanford (Stanford)                     	software1	69.88
 2. C2L2 (Ithaca)                           	software5	68.03
 3. IMS (Stuttgart)                         	software2	67.71
 4. LATTICE (Paris)                         	software7	66.13
 5. HIT-SCIR (Harbin)                       	software4	65.62
 6. NAIST SATO (Nara)                       	software1	65.07
 7. Koç University (İstanbul)               	software3	64.70
 8. MQuni (Sydney)                          	software2	64.26
 9. Orange – Deskiñ (Lannion)               	software1	63.83
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	63.68
11. UParse (Edinburgh)                      	software1	63.46
12. TurkuNLP (Turku)                        	software1	63.39
13. fbaml (Palo Alto)                       	software1	63.05
14. BASELINE UDPipe 1.1 (Praha)             	software2	62.98
15. naistCL (Nara)                          	software1	62.76
16. darc (Tübingen)                         	software1	62.60
17. IIT Kharagpur (Kharagpur)               	software3	61.80
18. RACAI (București)                       	software1	61.38
19. Uppsala (Uppsala)                       	software1	61.12
20. CLCL (Genève)                           	software2	61.10
21. Wanghao-ftd-SJTU (Shanghai)             	software2	59.54
22. METU (Ankara)                           	software2	59.19
23. UALING (Tucson)                         	software1	57.95
24. Mengest (Shanghai)                      	software1	57.89
25. LIMSI-LIPN (Paris)                      	software2	57.87
26. ParisNLP (Paris)                        	software1	57.03
27. LyS-FASTPARSE (A Coruña)                	software5	55.68
28. OpenU NLP Lab (Ra'anana)                	software6	47.71
29. TRL (Tokyo)                             	software1	40.25
30. MetaRomance (Santiago de Compostela)    	software1	33.02
31. UT (Tartu)                              	software1	15.51
32. ECNU (Shanghai)                         	software1	 3.10
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



## Small treebanks only

Macro-average CLAS-F1 of the 8 small treebanks: fr_partut, ga, gl_treegal, kk, la, sl_sst, ug, uk. These treebanks lack development data and some of them have very little training data (especially Uyghur and Kazakh).

<pre>
 1. C2L2 (Ithaca)                           	software5	55.34
 2. Stanford (Stanford)                     	software1	54.76
 3. IMS (Stuttgart)                         	software2	51.92
 4. HIT-SCIR (Harbin)                       	software4	47.63
 5. LATTICE (Paris)                         	software7	47.47
 6. fbaml (Palo Alto)                       	software1	47.11
 7. TurkuNLP (Turku)                        	software1	46.69
 8. RACAI (București)                       	software1	46.67
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	46.03
10. Koç University (İstanbul)               	software3	45.86
11. NAIST SATO (Nara)                       	software1	45.78
12. darc (Tübingen)                         	software1	44.54
13. UALING (Tucson)                         	software1	44.47
14. Wanghao-ftd-SJTU (Shanghai)             	software2	44.14
15. LIMSI-LIPN (Paris)                      	software2	44.03
16. BASELINE UDPipe 1.1 (Praha)             	software2	43.89
17. UParse (Edinburgh)                      	software1	43.50
18. MQuni (Sydney)                          	software2	43.44
19. ParisNLP (Paris)                        	software1	41.69
20. naistCL (Nara)                          	software1	41.46
21. LyS-FASTPARSE (A Coruña)                	software5	41.16
22. IIT Kharagpur (Kharagpur)               	software3	40.07
23. Orange – Deskiñ (Lannion)               	software1	38.49
24. Uppsala (Uppsala)                       	software1	34.20
25. OpenU NLP Lab (Ra'anana)                	software6	31.53
26. Mengest (Shanghai)                      	software1	27.75
27. TRL (Tokyo)                             	software1	25.19
28. METU (Ankara)                           	software2	23.82
29. MetaRomance (Santiago de Compostela)    	software1	23.04
30. CLCL (Genève)                           	software2	 5.87
31. UT (Tartu)                              	software1	 4.05
32. ECNU (Shanghai)                         	software1	 0.69
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



## Surprise languages only

Macro-average CLAS-F1 of the 4 surprise language treebanks: bxr, hsb, kmr, sme.

<pre>
 1. C2L2 (Ithaca)                           	software5	43.24
 2. IMS (Stuttgart)                         	software2	40.63
 3. HIT-SCIR (Harbin)                       	software4	38.20
 4. Stanford (Stanford)                     	software1	37.41
 5. UParse (Edinburgh)                      	software1	36.45
 6. ParisNLP (Paris)                        	software1	35.66
 7. Orange – Deskiñ (Lannion)               	software1	34.28
 8. Koç University (İstanbul)               	software3	33.78
 9. LIMSI-LIPN (Paris)                      	software2	33.17
10. IIT Kharagpur (Kharagpur)               	software3	32.73
11. BASELINE UDPipe 1.1 (Praha)             	software2	32.50
12. LATTICE (Paris)                         	software7	31.98
13. UALING (Tucson)                         	software1	31.86
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	31.55
15. Wanghao-ftd-SJTU (Shanghai)             	software2	31.39
16. LyS-FASTPARSE (A Coruña)                	software5	31.22
17. darc (Tübingen)                         	software1	31.20
18. OpenU NLP Lab (Ra'anana)                	software6	28.59
19. naistCL (Nara)                          	software1	27.80
20. RACAI (București)                       	software1	26.94
21. CLCL (Genève)                           	software2	25.28
22. NAIST SATO (Nara)                       	software1	23.79
23. MetaRomance (Santiago de Compostela)    	software1	18.67
24. TurkuNLP (Turku)                        	software1	17.85
25. Uppsala (Uppsala)                       	software1	17.49
26. METU (Ankara)                           	software2	16.94
27. fbaml (Palo Alto)                       	software1	15.30
28. MQuni (Sydney)                          	software2	11.36
29. Mengest (Shanghai)                      	software1	 8.51
30. TRL (Tokyo)                             	software1	 7.79
31. ECNU (Shanghai)                         	software1	 1.75
32. Wenba-NLU (Wuhan)                       	software1	 0.00
    UT (Tartu)                              	software1	 0.00
</pre>



## Per treebank CLAS-F1



### ar

<pre>
 1. IMS (Stuttgart)                         	software2	69.15
 2. Stanford (Stanford)                     	software1	68.17
 3. C2L2 (Ithaca)                           	software5	66.65
 4. HIT-SCIR (Harbin)                       	software4	64.83
 5. RACAI (București)                       	software1	64.35
 6. LATTICE (Paris)                         	software7	63.94
 7. MQuni (Sydney)                          	software2	63.78
 8. NAIST SATO (Nara)                       	software1	62.74
 9. Orange – Deskiñ (Lannion)               	software1	62.34
10. LyS-FASTPARSE (A Coruña)                	software5	61.05
11. UParse (Edinburgh)                      	software1	60.87
12. Koç University (İstanbul)               	software3	60.85
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	60.79
14. naistCL (Nara)                          	software1	60.73
15. Uppsala (Uppsala)                       	software1	60.66
16. LIMSI-LIPN (Paris)                      	software2	60.60
17. TurkuNLP (Turku)                        	software1	60.44
18. Mengest (Shanghai)                      	software1	60.35
19. darc (Tübingen)                         	software1	60.05
20. fbaml (Palo Alto)                       	software1	60.01
21. BASELINE UDPipe 1.1 (Praha)             	software2	59.60
22. CLCL (Genève)                           	software1	59.07
23. IIT Kharagpur (Kharagpur)               	software3	58.53
24. METU (Ankara)                           	software2	58.51
25. Wanghao-ftd-SJTU (Shanghai)             	software2	55.92
26. UALING (Tucson)                         	software1	55.43
27. ParisNLP (Paris)                        	software1	50.90
28. OpenU NLP Lab (Ra'anana)                	software6	39.00
29. TRL (Tokyo)                             	software1	32.30
30. MetaRomance (Santiago de Compostela)    	software1	22.47
31. Wenba-NLU (Wuhan)                       	software1	 0.17
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ar_pud

<pre>
 1. IMS (Stuttgart)                         	software2	46.32
 2. Stanford (Stanford)                     	software1	46.06
 3. C2L2 (Ithaca)                           	software5	45.72
 4. HIT-SCIR (Harbin)                       	software4	44.41
 5. RACAI (București)                       	software1	44.27
 6. LATTICE (Paris)                         	software7	43.30
 7. MQuni (Sydney)                          	software2	42.76
 8. Uppsala (Uppsala)                       	software1	41.71
 9. NAIST SATO (Nara)                       	software1	40.84
10. UParse (Edinburgh)                      	software1	40.29
11. Koç University (İstanbul)               	software3	40.28
12. Orange – Deskiñ (Lannion)               	software1	40.18
13. LyS-FASTPARSE (A Coruña)                	software5	39.91
14. fbaml (Palo Alto)                       	software1	39.86
15. naistCL (Nara)                          	software1	39.81
16. ÚFAL – UDPipe 1.2 (Praha)               	software1	39.25
17. LIMSI-LIPN (Paris)                      	software2	39.23
18. darc (Tübingen)                         	software1	39.22
19. Mengest (Shanghai)                      	software1	39.11
20. CLCL (Genève)                           	software1	38.40
21. IIT Kharagpur (Kharagpur)               	software3	38.16
22. BASELINE UDPipe 1.1 (Praha)             	software2	38.01
23. TurkuNLP (Turku)                        	software1	37.65
24. METU (Ankara)                           	software2	37.50
25. UALING (Tucson)                         	software1	37.10
26. ParisNLP (Paris)                        	software1	36.65
27. Wanghao-ftd-SJTU (Shanghai)             	software2	34.77
28. TRL (Tokyo)                             	software1	34.47
29. OpenU NLP Lab (Ra'anana)                	software6	25.83
30. MetaRomance (Santiago de Compostela)    	software1	21.68
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### bg

<pre>
 1. Stanford (Stanford)                     	software1	86.53
 2. C2L2 (Ithaca)                           	software5	84.45
 3. IMS (Stuttgart)                         	software2	83.68
 4. HIT-SCIR (Harbin)                       	software4	82.84
 5. NAIST SATO (Nara)                       	software1	81.60
 6. LyS-FASTPARSE (A Coruña)                	software5	81.39
 7. LATTICE (Paris)                         	software7	81.06
 8. Orange – Deskiñ (Lannion)               	software1	80.70
 9. Koç University (İstanbul)               	software3	80.30
10. TurkuNLP (Turku)                        	software1	80.24
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.08
12. darc (Tübingen)                         	software1	79.87
13. Mengest (Shanghai)                      	software1	79.60
14. fbaml (Palo Alto)                       	software1	79.30
15. UParse (Edinburgh)                      	software1	78.73
    BASELINE UDPipe 1.1 (Praha)             	software2	78.73
17. CLCL (Genève)                           	software1	78.49
18. LIMSI-LIPN (Paris)                      	software2	78.25
19. MQuni (Sydney)                          	software2	78.16
20. IIT Kharagpur (Kharagpur)               	software3	78.09
21. naistCL (Nara)                          	software1	77.94
22. Wanghao-ftd-SJTU (Shanghai)             	software2	77.50
23. RACAI (București)                       	software1	77.27
24. UALING (Tucson)                         	software1	76.96
25. METU (Ankara)                           	software2	76.85
26. UT (Tartu)                              	software1	76.76
27. Uppsala (Uppsala)                       	software1	76.38
28. OpenU NLP Lab (Ra'anana)                	software6	67.67
29. ParisNLP (Paris)                        	software1	66.96
30. TRL (Tokyo)                             	software1	45.00
31. MetaRomance (Santiago de Compostela)    	software1	37.21
32. Wenba-NLU (Wuhan)                       	software1	 0.33
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### bxr

<pre>
 1. ParisNLP (Paris)                        	software1	26.32
 2. IMS (Stuttgart)                         	software2	25.53
 3. Stanford (Stanford)                     	software1	25.37
 4. BASELINE UDPipe 1.1 (Praha)             	software2	25.18
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	25.01
 6. C2L2 (Ithaca)                           	software5	24.05
 7. LATTICE (Paris)                         	software7	21.23
 8. LyS-FASTPARSE (A Coruña)                	software5	20.98
 9. NAIST SATO (Nara)                       	software1	20.94
10. HIT-SCIR (Harbin)                       	software4	20.91
11. RACAI (București)                       	software1	20.66
12. IIT Kharagpur (Kharagpur)               	software3	20.49
13. CLCL (Genève)                           	software2	20.14
14. naistCL (Nara)                          	software1	19.94
15. UParse (Edinburgh)                      	software1	19.90
16. LIMSI-LIPN (Paris)                      	software2	19.08
17. Koç University (İstanbul)               	software3	18.25
18. Orange – Deskiñ (Lannion)               	software1	17.55
19. ÚFAL – UDPipe 1.2 (Praha)               	software1	15.15
20. OpenU NLP Lab (Ra'anana)                	software6	14.60
21. UALING (Tucson)                         	software1	14.27
22. METU (Ankara)                           	software2	13.70
23. darc (Tübingen)                         	software1	11.45
24. TurkuNLP (Turku)                        	software1	10.67
25. MQuni (Sydney)                          	software2	 9.71
26. Uppsala (Uppsala)                       	software1	 9.40
27. fbaml (Palo Alto)                       	software1	 8.90
28. Mengest (Shanghai)                      	software1	 6.90
29. TRL (Tokyo)                             	software1	 4.24
30. ECNU (Shanghai)                         	software1	 1.46
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ca

<pre>
 1. Stanford (Stanford)                     	software1	86.70
 2. HIT-SCIR (Harbin)                       	software4	83.36
 3. IMS (Stuttgart)                         	software2	82.62
 4. C2L2 (Ithaca)                           	software5	82.40
 5. NAIST SATO (Nara)                       	software1	81.90
 6. Orange – Deskiñ (Lannion)               	software1	81.59
 7. LATTICE (Paris)                         	software7	81.41
 8. UParse (Edinburgh)                      	software1	80.86
 9. Mengest (Shanghai)                      	software1	80.49
10. Koç University (İstanbul)               	software3	80.17
11. TurkuNLP (Turku)                        	software1	79.67
12. MQuni (Sydney)                          	software2	79.48
13. darc (Tübingen)                         	software1	79.42
14. Uppsala (Uppsala)                       	software1	79.41
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.32
16. LIMSI-LIPN (Paris)                      	software2	79.13
    BASELINE UDPipe 1.1 (Praha)             	software2	79.13
18. fbaml (Palo Alto)                       	software1	78.84
19. LyS-FASTPARSE (A Coruña)                	software5	78.72
20. naistCL (Nara)                          	software1	78.42
21. IIT Kharagpur (Kharagpur)               	software3	77.03
22. RACAI (București)                       	software1	77.01
23. Wanghao-ftd-SJTU (Shanghai)             	software2	76.08
24. CLCL (Genève)                           	software2	75.81
25. METU (Ankara)                           	software2	75.29
26. ParisNLP (Paris)                        	software1	74.34
27. UALING (Tucson)                         	software1	73.95
28. OpenU NLP Lab (Ra'anana)                	software6	63.88
29. MetaRomance (Santiago de Compostela)    	software1	44.56
30. TRL (Tokyo)                             	software1	38.60
31. Wenba-NLU (Wuhan)                       	software1	 0.08
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs

<pre>
 1. Stanford (Stanford)                     	software1	88.44
 2. HIT-SCIR (Harbin)                       	software4	84.18
 3. IMS (Stuttgart)                         	software2	84.13
 4. NAIST SATO (Nara)                       	software1	83.99
 5. C2L2 (Ithaca)                           	software5	83.72
 6. Uppsala (Uppsala)                       	software1	83.31
 7. Orange – Deskiñ (Lannion)               	software1	82.70
 8. UParse (Edinburgh)                      	software1	82.44
 9. fbaml (Palo Alto)                       	software1	81.57
10. LATTICE (Paris)                         	software7	81.04
11. Mengest (Shanghai)                      	software1	80.95
12. TurkuNLP (Turku)                        	software1	80.80
13. LyS-FASTPARSE (A Coruña)                	software5	80.60
14. MQuni (Sydney)                          	software2	80.38
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.32
16. CLCL (Genève)                           	software1	80.09
17. LIMSI-LIPN (Paris)                      	software2	79.90
    BASELINE UDPipe 1.1 (Praha)             	software2	79.90
19. darc (Tübingen)                         	software1	79.01
20. Koç University (İstanbul)               	software3	78.31
21. RACAI (București)                       	software1	77.83
22. METU (Ankara)                           	software2	76.93
23. IIT Kharagpur (Kharagpur)               	software3	76.71
24. naistCL (Nara)                          	software1	76.40
25. Wanghao-ftd-SJTU (Shanghai)             	software2	75.72
26. UALING (Tucson)                         	software1	74.10
27. ParisNLP (Paris)                        	software1	67.15
28. OpenU NLP Lab (Ra'anana)                	software6	65.21
29. TRL (Tokyo)                             	software1	51.28
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cac

<pre>
 1. Stanford (Stanford)                     	software1	88.31
 2. IMS (Stuttgart)                         	software2	84.27
 3. C2L2 (Ithaca)                           	software5	83.84
 4. NAIST SATO (Nara)                       	software1	83.27
 5. UParse (Edinburgh)                      	software1	82.08
 6. Orange – Deskiñ (Lannion)               	software1	81.91
 7. LATTICE (Paris)                         	software7	81.39
 8. TurkuNLP (Turku)                        	software1	80.90
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.78
10. HIT-SCIR (Harbin)                       	software4	80.41
11. Uppsala (Uppsala)                       	software1	80.05
12. MQuni (Sydney)                          	software2	79.70
13. fbaml (Palo Alto)                       	software1	79.63
14. Koç University (İstanbul)               	software3	79.45
15. Mengest (Shanghai)                      	software1	79.44
16. LIMSI-LIPN (Paris)                      	software2	78.81
    BASELINE UDPipe 1.1 (Praha)             	software2	78.81
18. LyS-FASTPARSE (A Coruña)                	software5	78.69
19. darc (Tübingen)                         	software1	78.40
20. CLCL (Genève)                           	software1	78.12
21. RACAI (București)                       	software1	77.78
22. naistCL (Nara)                          	software1	77.74
23. Wanghao-ftd-SJTU (Shanghai)             	software2	77.31
24. IIT Kharagpur (Kharagpur)               	software3	76.85
25. METU (Ankara)                           	software2	76.11
26. UALING (Tucson)                         	software1	74.68
27. ParisNLP (Paris)                        	software1	69.02
28. OpenU NLP Lab (Ra'anana)                	software6	67.03
29. TRL (Tokyo)                             	software1	53.16
30. MetaRomance (Santiago de Compostela)    	software1	40.33
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cltt

<pre>
 1. C2L2 (Ithaca)                           	software5	83.05
 2. Stanford (Stanford)                     	software1	79.62
 3. HIT-SCIR (Harbin)                       	software4	78.94
 4. IMS (Stuttgart)                         	software2	77.79
 5. NAIST SATO (Nara)                       	software1	73.89
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	72.80
 7. fbaml (Palo Alto)                       	software1	72.50
 8. LATTICE (Paris)                         	software7	72.27
 9. Orange – Deskiñ (Lannion)               	software1	70.86
10. MQuni (Sydney)                          	software2	70.45
11. LIMSI-LIPN (Paris)                      	software2	70.14
12. TurkuNLP (Turku)                        	software1	70.05
13. darc (Tübingen)                         	software1	69.94
14. Koç University (İstanbul)               	software3	69.93
15. IIT Kharagpur (Kharagpur)               	software3	69.08
16. UALING (Tucson)                         	software1	68.45
17. Wanghao-ftd-SJTU (Shanghai)             	software2	67.92
18. OpenU NLP Lab (Ra'anana)                	software6	67.69
19. UParse (Edinburgh)                      	software1	67.39
    BASELINE UDPipe 1.1 (Praha)             	software2	67.39
21. naistCL (Nara)                          	software1	65.57
22. METU (Ankara)                           	software2	65.37
23. LyS-FASTPARSE (A Coruña)                	software5	64.91
24. CLCL (Genève)                           	software1	64.68
25. Mengest (Shanghai)                      	software1	64.58
26. RACAI (București)                       	software1	62.75
27. Uppsala (Uppsala)                       	software1	56.77
28. ParisNLP (Paris)                        	software1	53.09
29. TRL (Tokyo)                             	software1	45.55
30. MetaRomance (Santiago de Compostela)    	software1	36.60
31. Wenba-NLU (Wuhan)                       	software1	 0.64
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_pud

<pre>
 1. Stanford (Stanford)                     	software1	81.60
 2. NAIST SATO (Nara)                       	software1	78.71
 3. C2L2 (Ithaca)                           	software5	78.60
 4. IMS (Stuttgart)                         	software2	78.01
 5. HIT-SCIR (Harbin)                       	software4	77.57
 6. UParse (Edinburgh)                      	software1	77.38
 7. LATTICE (Paris)                         	software7	77.19
 8. Orange – Deskiñ (Lannion)               	software1	76.81
 9. Uppsala (Uppsala)                       	software1	76.77
10. Mengest (Shanghai)                      	software1	76.74
11. TurkuNLP (Turku)                        	software1	76.60
12. LIMSI-LIPN (Paris)                      	software2	76.27
    BASELINE UDPipe 1.1 (Praha)             	software2	76.27
14. fbaml (Palo Alto)                       	software1	76.03
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.98
16. LyS-FASTPARSE (A Coruña)                	software5	75.93
17. darc (Tübingen)                         	software1	75.86
18. CLCL (Genève)                           	software1	75.65
19. MQuni (Sydney)                          	software2	75.40
20. Wanghao-ftd-SJTU (Shanghai)             	software2	74.37
21. Koç University (İstanbul)               	software3	74.35
22. IIT Kharagpur (Kharagpur)               	software3	73.81
23. naistCL (Nara)                          	software1	73.78
24. RACAI (București)                       	software1	73.64
25. METU (Ankara)                           	software2	73.30
26. UALING (Tucson)                         	software1	71.87
27. ParisNLP (Paris)                        	software1	67.88
28. OpenU NLP Lab (Ra'anana)                	software6	64.21
29. TRL (Tokyo)                             	software1	54.62
30. MetaRomance (Santiago de Compostela)    	software1	36.96
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cu

<pre>
 1. IMS (Stuttgart)                         	software2	75.59
 2. C2L2 (Ithaca)                           	software5	71.01
 3. Stanford (Stanford)                     	software1	70.49
 4. LyS-FASTPARSE (A Coruña)                	software5	65.25
 5. RACAI (București)                       	software1	64.98
 6. fbaml (Palo Alto)                       	software1	64.68
 7. darc (Tübingen)                         	software1	64.60
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	64.05
 9. TurkuNLP (Turku)                        	software1	63.79
10. HIT-SCIR (Harbin)                       	software4	63.45
11. LIMSI-LIPN (Paris)                      	software2	63.44
12. NAIST SATO (Nara)                       	software1	62.84
13. IIT Kharagpur (Kharagpur)               	software3	62.16
14. Orange – Deskiñ (Lannion)               	software1	61.91
15. ParisNLP (Paris)                        	software1	61.20
16. UT (Tartu)                              	software1	60.45
17. UParse (Edinburgh)                      	software1	60.41
    BASELINE UDPipe 1.1 (Praha)             	software2	60.41
19. Wanghao-ftd-SJTU (Shanghai)             	software2	60.12
20. CLCL (Genève)                           	software1	59.94
21. MQuni (Sydney)                          	software2	59.64
22. UALING (Tucson)                         	software1	58.65
23. LATTICE (Paris)                         	software7	58.11
24. METU (Ankara)                           	software2	57.60
25. naistCL (Nara)                          	software1	56.08
26. Koç University (İstanbul)               	software3	55.46
27. Uppsala (Uppsala)                       	software1	55.38
28. OpenU NLP Lab (Ra'anana)                	software6	52.93
29. Mengest (Shanghai)                      	software1	45.40
30. TRL (Tokyo)                             	software1	29.15
31. MetaRomance (Santiago de Compostela)    	software1	26.47
32. ECNU (Shanghai)                         	software1	 4.56
33. Wenba-NLU (Wuhan)                       	software1	 2.10
</pre>



### da

<pre>
 1. Stanford (Stanford)                     	software1	80.03
 2. C2L2 (Ithaca)                           	software5	78.30
 3. IMS (Stuttgart)                         	software2	76.18
 4. HIT-SCIR (Harbin)                       	software4	73.89
 5. NAIST SATO (Nara)                       	software1	72.53
 6. LATTICE (Paris)                         	software7	72.13
 7. Koç University (İstanbul)               	software3	71.93
 8. LyS-FASTPARSE (A Coruña)                	software5	71.19
 9. fbaml (Palo Alto)                       	software1	71.09
10. MQuni (Sydney)                          	software2	70.70
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.63
12. TurkuNLP (Turku)                        	software1	70.11
13. Orange – Deskiñ (Lannion)               	software1	69.69
14. LIMSI-LIPN (Paris)                      	software2	69.66
15. IIT Kharagpur (Kharagpur)               	software3	69.18
16. ParisNLP (Paris)                        	software1	69.08
17. darc (Tübingen)                         	software1	69.06
18. Wanghao-ftd-SJTU (Shanghai)             	software2	68.96
19. BASELINE UDPipe 1.1 (Praha)             	software2	68.84
20. naistCL (Nara)                          	software1	68.39
21. UParse (Edinburgh)                      	software1	68.32
22. Mengest (Shanghai)                      	software1	68.02
23. UALING (Tucson)                         	software1	67.94
24. RACAI (București)                       	software1	67.39
25. Uppsala (Uppsala)                       	software1	65.58
26. UT (Tartu)                              	software1	64.53
27. CLCL (Genève)                           	software1	64.02
28. METU (Ankara)                           	software2	62.15
29. OpenU NLP Lab (Ra'anana)                	software6	58.80
30. MetaRomance (Santiago de Compostela)    	software1	34.36
31. TRL (Tokyo)                             	software1	33.41
32. ECNU (Shanghai)                         	software1	 2.80
33. Wenba-NLU (Wuhan)                       	software1	 0.30
</pre>



### de

<pre>
 1. Stanford (Stanford)                     	software1	76.97
 2. C2L2 (Ithaca)                           	software5	73.13
 3. IMS (Stuttgart)                         	software2	70.55
 4. LATTICE (Paris)                         	software7	70.32
 5. HIT-SCIR (Harbin)                       	software4	69.85
 6. Orange – Deskiñ (Lannion)               	software1	69.62
 7. fbaml (Palo Alto)                       	software1	68.56
 8. NAIST SATO (Nara)                       	software1	68.40
 9. MQuni (Sydney)                          	software2	68.22
10. Uppsala (Uppsala)                       	software1	67.52
11. Koç University (İstanbul)               	software3	66.85
12. Mengest (Shanghai)                      	software1	65.88
13. naistCL (Nara)                          	software1	65.07
14. LIMSI-LIPN (Paris)                      	software2	64.63
15. UParse (Edinburgh)                      	software1	63.54
16. CLCL (Genève)                           	software1	63.41
17. BASELINE UDPipe 1.1 (Praha)             	software2	62.52
18. TurkuNLP (Turku)                        	software1	62.49
19. RACAI (București)                       	software1	62.36
20. METU (Ankara)                           	software2	61.66
21. ÚFAL – UDPipe 1.2 (Praha)               	software1	61.23
22. ParisNLP (Paris)                        	software1	61.11
23. darc (Tübingen)                         	software1	61.03
24. LyS-FASTPARSE (A Coruña)                	software5	60.97
25. IIT Kharagpur (Kharagpur)               	software3	60.43
26. Wanghao-ftd-SJTU (Shanghai)             	software2	58.84
27. UALING (Tucson)                         	software1	57.82
28. OpenU NLP Lab (Ra'anana)                	software6	37.95
29. TRL (Tokyo)                             	software1	36.77
30. MetaRomance (Santiago de Compostela)    	software1	25.42
31. Wenba-NLU (Wuhan)                       	software1	 0.52
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### de_pud

<pre>
 1. Stanford (Stanford)                     	software1	73.96
 2. C2L2 (Ithaca)                           	software5	72.26
 3. IMS (Stuttgart)                         	software2	69.87
 4. LATTICE (Paris)                         	software7	69.07
 5. HIT-SCIR (Harbin)                       	software4	68.71
 6. NAIST SATO (Nara)                       	software1	68.08
 7. Orange – Deskiñ (Lannion)               	software1	68.02
 8. Koç University (İstanbul)               	software3	67.67
 9. fbaml (Palo Alto)                       	software1	66.44
10. Mengest (Shanghai)                      	software1	66.18
11. MQuni (Sydney)                          	software2	66.14
12. naistCL (Nara)                          	software1	65.46
13. Uppsala (Uppsala)                       	software1	64.87
14. LIMSI-LIPN (Paris)                      	software2	64.69
15. CLCL (Genève)                           	software1	63.95
16. UParse (Edinburgh)                      	software1	63.23
17. BASELINE UDPipe 1.1 (Praha)             	software2	62.24
18. TurkuNLP (Turku)                        	software1	62.16
19. METU (Ankara)                           	software2	61.67
20. LyS-FASTPARSE (A Coruña)                	software5	61.65
21. ÚFAL – UDPipe 1.2 (Praha)               	software1	61.00
22. ParisNLP (Paris)                        	software1	60.68
23. darc (Tübingen)                         	software1	60.12
24. RACAI (București)                       	software1	60.01
25. IIT Kharagpur (Kharagpur)               	software3	59.89
26. Wanghao-ftd-SJTU (Shanghai)             	software2	59.08
27. UALING (Tucson)                         	software1	57.63
28. TRL (Tokyo)                             	software1	37.24
29. OpenU NLP Lab (Ra'anana)                	software6	36.04
30. MetaRomance (Santiago de Compostela)    	software1	25.95
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### el

<pre>
 1. Stanford (Stanford)                     	software1	83.59
 2. C2L2 (Ithaca)                           	software5	82.77
 3. IMS (Stuttgart)                         	software2	80.40
 4. HIT-SCIR (Harbin)                       	software4	77.77
 5. NAIST SATO (Nara)                       	software1	76.22
 6. Orange – Deskiñ (Lannion)               	software1	75.78
 7. LATTICE (Paris)                         	software7	75.63
 8. LyS-FASTPARSE (A Coruña)                	software5	75.61
 9. Koç University (İstanbul)               	software3	75.30
10. fbaml (Palo Alto)                       	software1	74.83
11. MQuni (Sydney)                          	software2	74.66
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	73.93
13. TurkuNLP (Turku)                        	software1	73.36
14. IIT Kharagpur (Kharagpur)               	software3	72.76
15. LIMSI-LIPN (Paris)                      	software2	72.70
16. darc (Tübingen)                         	software1	72.55
17. UParse (Edinburgh)                      	software1	72.54
    BASELINE UDPipe 1.1 (Praha)             	software2	72.54
19. RACAI (București)                       	software1	71.96
20. naistCL (Nara)                          	software1	71.90
21. Mengest (Shanghai)                      	software1	71.78
22. CLCL (Genève)                           	software1	70.97
23. UALING (Tucson)                         	software1	70.93
24. ParisNLP (Paris)                        	software1	69.41
25. METU (Ankara)                           	software2	69.18
26. Wanghao-ftd-SJTU (Shanghai)             	software2	68.92
27. Uppsala (Uppsala)                       	software1	65.62
28. UT (Tartu)                              	software1	65.15
29. OpenU NLP Lab (Ra'anana)                	software6	64.54
30. TRL (Tokyo)                             	software1	38.74
31. MetaRomance (Santiago de Compostela)    	software1	36.56
32. ECNU (Shanghai)                         	software1	 0.36
33. Wenba-NLU (Wuhan)                       	software1	 0.21
</pre>



### en

<pre>
 1. Stanford (Stanford)                     	software1	78.99
 2. HIT-SCIR (Harbin)                       	software4	75.94
 3. C2L2 (Ithaca)                           	software5	75.91
 4. LATTICE (Paris)                         	software7	75.06
 5. IMS (Stuttgart)                         	software2	74.91
 6. NAIST SATO (Nara)                       	software1	73.81
 7. Orange – Deskiñ (Lannion)               	software1	73.59
 8. fbaml (Palo Alto)                       	software1	73.37
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	73.00
10. TurkuNLP (Turku)                        	software1	72.77
11. Mengest (Shanghai)                      	software1	72.45
12. MQuni (Sydney)                          	software2	72.40
13. Uppsala (Uppsala)                       	software1	71.98
14. UParse (Edinburgh)                      	software1	71.95
15. LyS-FASTPARSE (A Coruña)                	software5	71.77
    Koç University (İstanbul)               	software3	71.77
17. LIMSI-LIPN (Paris)                      	software2	71.56
    BASELINE UDPipe 1.1 (Praha)             	software2	71.56
19. darc (Tübingen)                         	software1	71.36
20. IIT Kharagpur (Kharagpur)               	software3	71.24
21. CLCL (Genève)                           	software1	70.99
22. naistCL (Nara)                          	software1	70.70
23. RACAI (București)                       	software1	69.83
24. Wanghao-ftd-SJTU (Shanghai)             	software2	69.79
25. METU (Ankara)                           	software2	68.86
26. UALING (Tucson)                         	software1	67.62
27. ParisNLP (Paris)                        	software1	64.72
28. OpenU NLP Lab (Ra'anana)                	software6	61.28
29. TRL (Tokyo)                             	software1	43.65
30. MetaRomance (Santiago de Compostela)    	software1	31.18
31. Wenba-NLU (Wuhan)                       	software1	 1.08
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_lines

<pre>
 1. Stanford (Stanford)                     	software1	78.71
 2. C2L2 (Ithaca)                           	software5	77.53
 3. HIT-SCIR (Harbin)                       	software4	75.06
 4. IMS (Stuttgart)                         	software2	74.39
 5. NAIST SATO (Nara)                       	software1	73.56
 6. LATTICE (Paris)                         	software7	72.58
 7. Orange – Deskiñ (Lannion)               	software1	70.64
 8. TurkuNLP (Turku)                        	software1	70.61
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.50
10. fbaml (Palo Alto)                       	software1	70.36
11. IIT Kharagpur (Kharagpur)               	software3	69.78
12. Koç University (İstanbul)               	software3	69.42
13. MQuni (Sydney)                          	software2	69.31
14. LIMSI-LIPN (Paris)                      	software2	68.38
    BASELINE UDPipe 1.1 (Praha)             	software2	68.38
16. Mengest (Shanghai)                      	software1	68.23
17. darc (Tübingen)                         	software1	68.17
18. LyS-FASTPARSE (A Coruña)                	software5	68.13
19. UParse (Edinburgh)                      	software1	67.78
20. Wanghao-ftd-SJTU (Shanghai)             	software2	67.70
21. UALING (Tucson)                         	software1	67.68
22. CLCL (Genève)                           	software1	67.62
23. naistCL (Nara)                          	software1	67.30
24. METU (Ankara)                           	software2	65.69
25. RACAI (București)                       	software1	65.53
26. UT (Tartu)                              	software1	63.89
27. OpenU NLP Lab (Ra'anana)                	software6	62.41
28. Uppsala (Uppsala)                       	software1	62.19
29. ParisNLP (Paris)                        	software1	59.45
30. TRL (Tokyo)                             	software1	45.91
31. ECNU (Shanghai)                         	software1	27.30
32. MetaRomance (Santiago de Compostela)    	software1	25.91
33. Wenba-NLU (Wuhan)                       	software1	 0.54
</pre>



### en_partut

<pre>
 1. C2L2 (Ithaca)                           	software5	79.80
 2. Stanford (Stanford)                     	software1	77.40
 3. HIT-SCIR (Harbin)                       	software4	76.74
 4. LATTICE (Paris)                         	software7	74.98
 5. NAIST SATO (Nara)                       	software1	73.42
 6. IMS (Stuttgart)                         	software2	73.38
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.51
 8. fbaml (Palo Alto)                       	software1	70.14
 9. Orange – Deskiñ (Lannion)               	software1	69.67
10. Koç University (İstanbul)               	software3	69.23
11. MQuni (Sydney)                          	software2	68.90
12. darc (Tübingen)                         	software1	67.73
13. TurkuNLP (Turku)                        	software1	67.64
14. IIT Kharagpur (Kharagpur)               	software3	67.35
15. Wanghao-ftd-SJTU (Shanghai)             	software2	66.95
    LyS-FASTPARSE (A Coruña)                	software5	66.95
17. UALING (Tucson)                         	software1	66.44
18. LIMSI-LIPN (Paris)                      	software2	66.41
19. UParse (Edinburgh)                      	software1	66.40
    BASELINE UDPipe 1.1 (Praha)             	software2	66.40
21. Mengest (Shanghai)                      	software1	66.30
22. naistCL (Nara)                          	software1	65.74
23. METU (Ankara)                           	software2	65.24
24. RACAI (București)                       	software1	64.61
25. CLCL (Genève)                           	software1	64.31
26. ParisNLP (Paris)                        	software1	60.97
27. OpenU NLP Lab (Ra'anana)                	software6	59.77
28. Uppsala (Uppsala)                       	software1	56.24
29. TRL (Tokyo)                             	software1	44.68
30. MetaRomance (Santiago de Compostela)    	software1	34.66
31. Wenba-NLU (Wuhan)                       	software1	 0.05
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_pud

<pre>
 1. Stanford (Stanford)                     	software1	82.63
 2. LATTICE (Paris)                         	software7	78.80
 3. IMS (Stuttgart)                         	software2	78.17
 4. HIT-SCIR (Harbin)                       	software4	78.09
 5. NAIST SATO (Nara)                       	software1	77.29
 6. MQuni (Sydney)                          	software2	76.80
 7. Orange – Deskiñ (Lannion)               	software1	75.55
 8. fbaml (Palo Alto)                       	software1	75.40
 9. TurkuNLP (Turku)                        	software1	75.36
10. Koç University (İstanbul)               	software3	75.22
11. UParse (Edinburgh)                      	software1	74.91
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.81
13. Mengest (Shanghai)                      	software1	74.58
14. LyS-FASTPARSE (A Coruña)                	software5	74.53
15. LIMSI-LIPN (Paris)                      	software2	74.28
    BASELINE UDPipe 1.1 (Praha)             	software2	74.28
17. naistCL (Nara)                          	software1	74.05
18. CLCL (Genève)                           	software1	73.74
19. IIT Kharagpur (Kharagpur)               	software3	73.44
20. Wanghao-ftd-SJTU (Shanghai)             	software2	72.97
21. darc (Tübingen)                         	software1	72.88
22. C2L2 (Ithaca)                           	software5	72.85
23. RACAI (București)                       	software1	72.72
24. Uppsala (Uppsala)                       	software1	71.18
25. METU (Ankara)                           	software2	70.91
26. UALING (Tucson)                         	software1	70.88
27. ParisNLP (Paris)                        	software1	70.81
28. UT (Tartu)                              	software1	70.05
29. OpenU NLP Lab (Ra'anana)                	software6	67.51
30. TRL (Tokyo)                             	software1	46.71
31. MetaRomance (Santiago de Compostela)    	software1	37.18
32. ECNU (Shanghai)                         	software1	22.07
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### es

<pre>
 1. Stanford (Stanford)                     	software1	82.08
 2. LATTICE (Paris)                         	software7	79.08
 3. C2L2 (Ithaca)                           	software5	78.85
 4. HIT-SCIR (Harbin)                       	software4	78.28
 5. NAIST SATO (Nara)                       	software1	78.03
 6. Koç University (İstanbul)               	software3	76.84
 7. IMS (Stuttgart)                         	software2	76.61
 8. MQuni (Sydney)                          	software2	76.41
 9. LyS-FASTPARSE (A Coruña)                	software5	76.27
10. UParse (Edinburgh)                      	software1	76.21
11. Orange – Deskiñ (Lannion)               	software1	76.08
12. Uppsala (Uppsala)                       	software1	75.38
13. naistCL (Nara)                          	software1	74.75
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.59
15. TurkuNLP (Turku)                        	software1	74.54
16. fbaml (Palo Alto)                       	software1	74.24
17. LIMSI-LIPN (Paris)                      	software2	73.96
    BASELINE UDPipe 1.1 (Praha)             	software2	73.96
19. darc (Tübingen)                         	software1	73.84
20. CLCL (Genève)                           	software2	72.63
21. IIT Kharagpur (Kharagpur)               	software3	72.60
22. RACAI (București)                       	software1	72.12
23. Wanghao-ftd-SJTU (Shanghai)             	software2	71.83
24. UALING (Tucson)                         	software1	69.88
25. ParisNLP (Paris)                        	software1	69.21
26. METU (Ankara)                           	software2	68.54
27. Mengest (Shanghai)                      	software1	66.66
28. OpenU NLP Lab (Ra'anana)                	software6	55.79
29. MetaRomance (Santiago de Compostela)    	software1	47.49
30. TRL (Tokyo)                             	software1	47.13
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_ancora

<pre>
 1. Stanford (Stanford)                     	software1	86.15
 2. HIT-SCIR (Harbin)                       	software4	82.73
 3. NAIST SATO (Nara)                       	software1	82.47
 4. IMS (Stuttgart)                         	software2	82.39
 5. C2L2 (Ithaca)                           	software5	82.27
 6. LATTICE (Paris)                         	software7	82.00
 7. LyS-FASTPARSE (A Coruña)                	software5	81.52
 8. Orange – Deskiñ (Lannion)               	software1	81.02
 9. Koç University (İstanbul)               	software3	80.27
10. UParse (Edinburgh)                      	software1	80.13
11. MQuni (Sydney)                          	software2	79.92
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.25
13. Uppsala (Uppsala)                       	software1	79.04
14. naistCL (Nara)                          	software1	78.54
15. darc (Tübingen)                         	software1	78.44
16. TurkuNLP (Turku)                        	software1	78.35
17. fbaml (Palo Alto)                       	software1	77.91
18. LIMSI-LIPN (Paris)                      	software2	77.82
    BASELINE UDPipe 1.1 (Praha)             	software2	77.82
20. IIT Kharagpur (Kharagpur)               	software3	75.89
21. Wanghao-ftd-SJTU (Shanghai)             	software2	75.50
22. RACAI (București)                       	software1	75.45
23. CLCL (Genève)                           	software2	75.21
24. METU (Ankara)                           	software2	74.22
25. UALING (Tucson)                         	software1	73.27
26. Mengest (Shanghai)                      	software1	71.73
27. ParisNLP (Paris)                        	software1	68.36
28. OpenU NLP Lab (Ra'anana)                	software6	60.97
29. MetaRomance (Santiago de Compostela)    	software1	51.04
30. TRL (Tokyo)                             	software1	43.50
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_pud

<pre>
 1. Stanford (Stanford)                     	software1	74.60
 2. C2L2 (Ithaca)                           	software5	73.64
 3. LATTICE (Paris)                         	software7	72.75
 4. NAIST SATO (Nara)                       	software1	72.50
 5. MQuni (Sydney)                          	software2	72.34
 6. UParse (Edinburgh)                      	software1	71.72
 7. IMS (Stuttgart)                         	software2	71.56
 8. Koç University (İstanbul)               	software3	71.30
 9. Orange – Deskiñ (Lannion)               	software1	71.22
10. Uppsala (Uppsala)                       	software1	70.68
11. TurkuNLP (Turku)                        	software1	70.41
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.38
13. naistCL (Nara)                          	software1	70.14
14. BASELINE UDPipe 1.1 (Praha)             	software2	69.61
15. darc (Tübingen)                         	software1	69.47
16. fbaml (Palo Alto)                       	software1	69.16
17. Wanghao-ftd-SJTU (Shanghai)             	software2	69.08
18. ParisNLP (Paris)                        	software1	68.48
19. IIT Kharagpur (Kharagpur)               	software3	68.04
20. RACAI (București)                       	software1	67.92
21. CLCL (Genève)                           	software1	67.77
22. UALING (Tucson)                         	software1	67.33
23. METU (Ankara)                           	software2	66.26
    HIT-SCIR (Harbin)                       	software4	66.26
25. Mengest (Shanghai)                      	software1	63.04
26. LIMSI-LIPN (Paris)                      	software2	57.09
27. OpenU NLP Lab (Ra'anana)                	software6	55.85
28. MetaRomance (Santiago de Compostela)    	software1	54.12
29. TRL (Tokyo)                             	software1	48.14
30. LyS-FASTPARSE (A Coruña)                	software5	41.71
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### et

<pre>
 1. Stanford (Stanford)                     	software1	69.85
 2. C2L2 (Ithaca)                           	software5	67.63
 3. IMS (Stuttgart)                         	software2	65.32
 4. HIT-SCIR (Harbin)                       	software4	61.72
 5. LATTICE (Paris)                         	software7	59.95
 6. Koç University (İstanbul)               	software3	58.99
 7. LyS-FASTPARSE (A Coruña)                	software5	58.92
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	56.75
 9. Orange – Deskiñ (Lannion)               	software1	56.72
    TurkuNLP (Turku)                        	software1	56.72
11. LIMSI-LIPN (Paris)                      	software2	56.38
12. darc (Tübingen)                         	software1	56.32
13. IIT Kharagpur (Kharagpur)               	software3	56.15
14. UALING (Tucson)                         	software1	55.56
15. BASELINE UDPipe 1.1 (Praha)             	software2	55.38
16. UParse (Edinburgh)                      	software1	55.37
17. RACAI (București)                       	software1	55.11
18. Wanghao-ftd-SJTU (Shanghai)             	software2	54.36
19. fbaml (Palo Alto)                       	software1	53.97
20. MQuni (Sydney)                          	software2	53.52
21. NAIST SATO (Nara)                       	software1	53.28
22. ParisNLP (Paris)                        	software1	52.26
23. naistCL (Nara)                          	software1	51.57
24. Mengest (Shanghai)                      	software1	50.93
25. UT (Tartu)                              	software1	49.24
26. CLCL (Genève)                           	software1	47.95
27. METU (Ankara)                           	software2	47.69
28. Uppsala (Uppsala)                       	software1	44.46
29. OpenU NLP Lab (Ra'anana)                	software6	39.71
30. TRL (Tokyo)                             	software1	29.35
31. MetaRomance (Santiago de Compostela)    	software1	23.17
32. ECNU (Shanghai)                         	software1	 2.66
33. Wenba-NLU (Wuhan)                       	software1	 0.93
</pre>



### eu

<pre>
 1. Stanford (Stanford)                     	software1	79.71
 2. C2L2 (Ithaca)                           	software5	77.66
 3. IMS (Stuttgart)                         	software2	75.94
 4. HIT-SCIR (Harbin)                       	software4	70.92
 5. LyS-FASTPARSE (A Coruña)                	software5	70.54
 6. MQuni (Sydney)                          	software2	69.93
 7. LATTICE (Paris)                         	software7	69.15
 8. Koç University (İstanbul)               	software3	68.69
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	68.16
10. TurkuNLP (Turku)                        	software1	68.14
11. naistCL (Nara)                          	software1	67.55
12. fbaml (Palo Alto)                       	software1	67.19
13. BASELINE UDPipe 1.1 (Praha)             	software2	66.77
14. RACAI (București)                       	software1	66.74
15. LIMSI-LIPN (Paris)                      	software2	66.68
16. Uppsala (Uppsala)                       	software1	66.34
17. IIT Kharagpur (Kharagpur)               	software3	66.33
18. NAIST SATO (Nara)                       	software1	66.30
19. darc (Tübingen)                         	software1	65.92
20. UParse (Edinburgh)                      	software1	65.85
21. Orange – Deskiñ (Lannion)               	software1	65.44
22. UALING (Tucson)                         	software1	64.12
23. Wanghao-ftd-SJTU (Shanghai)             	software2	63.59
24. UT (Tartu)                              	software1	60.35
25. Mengest (Shanghai)                      	software1	57.82
26. CLCL (Genève)                           	software2	57.63
27. METU (Ankara)                           	software2	54.65
28. OpenU NLP Lab (Ra'anana)                	software6	50.65
29. ParisNLP (Paris)                        	software1	46.01
30. TRL (Tokyo)                             	software1	35.58
31. MetaRomance (Santiago de Compostela)    	software1	10.68
32. ECNU (Shanghai)                         	software1	 1.86
33. Wenba-NLU (Wuhan)                       	software1	 0.83
</pre>



### fa

<pre>
 1. Stanford (Stanford)                     	software1	82.93
 2. C2L2 (Ithaca)                           	software5	81.12
 3. IMS (Stuttgart)                         	software2	79.32
 4. LATTICE (Paris)                         	software7	78.45
 5. NAIST SATO (Nara)                       	software1	77.84
 6. HIT-SCIR (Harbin)                       	software4	77.80
 7. MQuni (Sydney)                          	software2	76.96
 8. Orange – Deskiñ (Lannion)               	software1	76.75
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.07
10. Koç University (İstanbul)               	software3	75.45
11. UParse (Edinburgh)                      	software1	75.41
12. naistCL (Nara)                          	software1	75.22
13. LIMSI-LIPN (Paris)                      	software2	74.87
    BASELINE UDPipe 1.1 (Praha)             	software2	74.87
15. IIT Kharagpur (Kharagpur)               	software3	74.76
16. LyS-FASTPARSE (A Coruña)                	software5	73.28
17. darc (Tübingen)                         	software1	73.22
18. fbaml (Palo Alto)                       	software1	73.03
19. RACAI (București)                       	software1	72.56
20. TurkuNLP (Turku)                        	software1	71.58
21. Uppsala (Uppsala)                       	software1	71.17
22. UALING (Tucson)                         	software1	71.13
23. METU (Ankara)                           	software2	71.04
24. CLCL (Genève)                           	software2	70.86
25. Wanghao-ftd-SJTU (Shanghai)             	software2	70.39
26. OpenU NLP Lab (Ra'anana)                	software6	57.38
27. Mengest (Shanghai)                      	software1	56.13
28. ParisNLP (Paris)                        	software1	55.05
29. TRL (Tokyo)                             	software1	40.46
30. MetaRomance (Santiago de Compostela)    	software1	22.27
31. Wenba-NLU (Wuhan)                       	software1	 0.76
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi

<pre>
 1. Stanford (Stanford)                     	software1	84.25
 2. C2L2 (Ithaca)                           	software5	80.23
 3. IMS (Stuttgart)                         	software2	79.51
 4. Koç University (İstanbul)               	software3	75.12
 5. HIT-SCIR (Harbin)                       	software4	75.11
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.93
 7. LATTICE (Paris)                         	software7	74.67
 8. TurkuNLP (Turku)                        	software1	73.85
 9. LyS-FASTPARSE (A Coruña)                	software5	73.73
10. darc (Tübingen)                         	software1	72.71
11. MQuni (Sydney)                          	software2	72.70
12. naistCL (Nara)                          	software1	72.49
13. UParse (Edinburgh)                      	software1	72.35
14. IIT Kharagpur (Kharagpur)               	software3	72.03
15. Orange – Deskiñ (Lannion)               	software1	72.02
16. fbaml (Palo Alto)                       	software1	71.84
17. NAIST SATO (Nara)                       	software1	71.76
18. Uppsala (Uppsala)                       	software1	71.68
19. LIMSI-LIPN (Paris)                      	software2	71.38
    BASELINE UDPipe 1.1 (Praha)             	software2	71.38
21. Wanghao-ftd-SJTU (Shanghai)             	software2	70.73
22. UALING (Tucson)                         	software1	70.08
23. RACAI (București)                       	software1	69.73
24. UT (Tartu)                              	software1	66.58
25. Mengest (Shanghai)                      	software1	65.95
26. METU (Ankara)                           	software2	62.90
27. CLCL (Genève)                           	software2	60.21
28. ParisNLP (Paris)                        	software1	56.03
29. OpenU NLP Lab (Ra'anana)                	software6	39.47
30. TRL (Tokyo)                             	software1	32.60
31. MetaRomance (Santiago de Compostela)    	software1	24.22
32. Wenba-NLU (Wuhan)                       	software1	 0.88
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### fi_ftb

<pre>
 1. Stanford (Stanford)                     	software1	84.12
 2. C2L2 (Ithaca)                           	software5	78.69
 3. IMS (Stuttgart)                         	software2	77.19
 4. LATTICE (Paris)                         	software7	74.97
 5. Orange – Deskiñ (Lannion)               	software1	74.04
 6. HIT-SCIR (Harbin)                       	software4	73.04
 7. LyS-FASTPARSE (A Coruña)                	software5	71.82
 8. CLCL (Genève)                           	software2	71.26
 9. TurkuNLP (Turku)                        	software1	70.50
10. darc (Tübingen)                         	software1	70.24
11. Koç University (İstanbul)               	software3	70.11
12. Mengest (Shanghai)                      	software1	69.96
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	69.91
14. NAIST SATO (Nara)                       	software1	68.84
15. IIT Kharagpur (Kharagpur)               	software3	68.79
16. UParse (Edinburgh)                      	software1	68.41
    LIMSI-LIPN (Paris)                      	software2	68.41
    BASELINE UDPipe 1.1 (Praha)             	software2	68.41
19. MQuni (Sydney)                          	software2	68.40
20. naistCL (Nara)                          	software1	67.19
21. UALING (Tucson)                         	software1	66.67
22. METU (Ankara)                           	software2	66.25
23. Wanghao-ftd-SJTU (Shanghai)             	software2	66.22
24. RACAI (București)                       	software1	66.17
25. Uppsala (Uppsala)                       	software1	65.90
26. fbaml (Palo Alto)                       	software1	65.86
27. ParisNLP (Paris)                        	software1	43.57
28. OpenU NLP Lab (Ra'anana)                	software6	42.23
29. TRL (Tokyo)                             	software1	33.71
30. MetaRomance (Santiago de Compostela)    	software1	25.32
31. Wenba-NLU (Wuhan)                       	software1	 2.44
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi_pud

<pre>
 1. Stanford (Stanford)                     	software1	86.82
 2. IMS (Stuttgart)                         	software2	83.50
 3. C2L2 (Ithaca)                           	software5	83.16
 4. Koç University (İstanbul)               	software3	79.94
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	78.39
 6. LATTICE (Paris)                         	software7	78.38
 7. TurkuNLP (Turku)                        	software1	77.76
 8. MQuni (Sydney)                          	software2	76.65
 9. UParse (Edinburgh)                      	software1	76.60
10. BASELINE UDPipe 1.1 (Praha)             	software2	76.30
11. darc (Tübingen)                         	software1	76.23
12. HIT-SCIR (Harbin)                       	software4	76.21
13. naistCL (Nara)                          	software1	76.14
14. Orange – Deskiñ (Lannion)               	software1	74.98
15. UALING (Tucson)                         	software1	74.47
16. fbaml (Palo Alto)                       	software1	74.37
17. Wanghao-ftd-SJTU (Shanghai)             	software2	74.17
18. IIT Kharagpur (Kharagpur)               	software3	73.82
19. NAIST SATO (Nara)                       	software1	73.63
20. Uppsala (Uppsala)                       	software1	72.80
21. RACAI (București)                       	software1	72.41
22. Mengest (Shanghai)                      	software1	67.65
23. METU (Ankara)                           	software2	65.38
24. CLCL (Genève)                           	software1	61.05
25. ParisNLP (Paris)                        	software1	58.75
26. LIMSI-LIPN (Paris)                      	software2	51.24
27. LyS-FASTPARSE (A Coruña)                	software5	45.48
28. OpenU NLP Lab (Ra'anana)                	software6	39.30
29. TRL (Tokyo)                             	software1	34.88
30. MetaRomance (Santiago de Compostela)    	software1	28.30
31. ECNU (Shanghai)                         	software1	 3.25
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr

<pre>
 1. Stanford (Stanford)                     	software1	82.14
 2. C2L2 (Ithaca)                           	software5	80.40
 3. IMS (Stuttgart)                         	software2	79.49
 4. HIT-SCIR (Harbin)                       	software4	79.04
 5. LATTICE (Paris)                         	software7	78.72
 6. MQuni (Sydney)                          	software2	78.58
 7. NAIST SATO (Nara)                       	software1	78.34
 8. Orange – Deskiñ (Lannion)               	software1	77.59
 9. UParse (Edinburgh)                      	software1	76.92
10. Koç University (İstanbul)               	software3	76.53
11. LIMSI-LIPN (Paris)                      	software2	76.03
    BASELINE UDPipe 1.1 (Praha)             	software2	76.03
13. darc (Tübingen)                         	software1	75.84
14. TurkuNLP (Turku)                        	software1	75.76
15. CLCL (Genève)                           	software2	75.45
16. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.39
17. Mengest (Shanghai)                      	software1	75.36
18. fbaml (Palo Alto)                       	software1	75.25
19. Uppsala (Uppsala)                       	software1	75.12
20. naistCL (Nara)                          	software1	75.01
21. LyS-FASTPARSE (A Coruña)                	software5	74.65
22. IIT Kharagpur (Kharagpur)               	software3	73.98
23. Wanghao-ftd-SJTU (Shanghai)             	software2	73.63
24. RACAI (București)                       	software1	72.51
25. UALING (Tucson)                         	software1	71.64
26. ParisNLP (Paris)                        	software1	71.60
27. METU (Ankara)                           	software2	71.58
28. OpenU NLP Lab (Ra'anana)                	software6	63.56
29. TRL (Tokyo)                             	software1	48.73
30. MetaRomance (Santiago de Compostela)    	software1	45.02
31. Wenba-NLU (Wuhan)                       	software1	 0.41
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_partut

<pre>
 1. C2L2 (Ithaca)                           	software5	83.58
 2. Stanford (Stanford)                     	software1	79.49
 3. HIT-SCIR (Harbin)                       	software4	79.42
 4. IMS (Stuttgart)                         	software2	77.37
 5. LATTICE (Paris)                         	software7	76.88
 6. NAIST SATO (Nara)                       	software1	73.59
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	73.34
 8. Koç University (İstanbul)               	software3	73.32
 9. fbaml (Palo Alto)                       	software1	73.27
10. MQuni (Sydney)                          	software2	71.60
11. TurkuNLP (Turku)                        	software1	71.47
12. darc (Tübingen)                         	software1	71.32
13. Wanghao-ftd-SJTU (Shanghai)             	software2	71.23
14. UALING (Tucson)                         	software1	70.75
15. LIMSI-LIPN (Paris)                      	software2	70.61
16. Orange – Deskiñ (Lannion)               	software1	70.34
17. naistCL (Nara)                          	software1	69.25
18. UParse (Edinburgh)                      	software1	69.17
    BASELINE UDPipe 1.1 (Praha)             	software2	69.17
20. RACAI (București)                       	software1	68.79
21. ParisNLP (Paris)                        	software1	66.52
22. IIT Kharagpur (Kharagpur)               	software3	66.28
23. OpenU NLP Lab (Ra'anana)                	software6	63.10
24. LyS-FASTPARSE (A Coruña)                	software5	62.21
25. Mengest (Shanghai)                      	software1	61.77
26. METU (Ankara)                           	software2	60.55
27. Uppsala (Uppsala)                       	software1	58.73
28. TRL (Tokyo)                             	software1	50.56
29. MetaRomance (Santiago de Compostela)    	software1	43.48
30. CLCL (Genève)                           	software2	 6.90
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_pud

<pre>
 1. Stanford (Stanford)                     	software1	77.37
 2. C2L2 (Ithaca)                           	software5	76.55
 3. IMS (Stuttgart)                         	software2	74.96
 4. HIT-SCIR (Harbin)                       	software4	74.87
 5. LATTICE (Paris)                         	software7	73.99
 6. MQuni (Sydney)                          	software2	72.96
 7. Koç University (İstanbul)               	software3	72.88
 8. Orange – Deskiñ (Lannion)               	software1	72.12
 9. NAIST SATO (Nara)                       	software1	72.05
10. UParse (Edinburgh)                      	software1	71.19
11. CLCL (Genève)                           	software1	70.90
12. Mengest (Shanghai)                      	software1	70.60
13. TurkuNLP (Turku)                        	software1	70.50
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.39
15. LIMSI-LIPN (Paris)                      	software2	70.02
    BASELINE UDPipe 1.1 (Praha)             	software2	70.02
    fbaml (Palo Alto)                       	software1	70.02
18. naistCL (Nara)                          	software1	69.82
19. ParisNLP (Paris)                        	software1	69.73
20. darc (Tübingen)                         	software1	69.52
21. IIT Kharagpur (Kharagpur)               	software3	69.41
22. LyS-FASTPARSE (A Coruña)                	software5	69.33
23. Wanghao-ftd-SJTU (Shanghai)             	software2	69.09
24. Uppsala (Uppsala)                       	software1	68.89
25. RACAI (București)                       	software1	68.15
26. UALING (Tucson)                         	software1	67.03
27. METU (Ankara)                           	software2	66.41
28. OpenU NLP Lab (Ra'anana)                	software6	60.84
29. MetaRomance (Santiago de Compostela)    	software1	50.08
30. TRL (Tokyo)                             	software1	49.87
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_sequoia

<pre>
 1. C2L2 (Ithaca)                           	software5	84.09
 2. Stanford (Stanford)                     	software1	83.37
 3. HIT-SCIR (Harbin)                       	software4	81.70
 4. IMS (Stuttgart)                         	software2	81.31
 5. LATTICE (Paris)                         	software7	79.66
 6. NAIST SATO (Nara)                       	software1	79.15
 7. Orange – Deskiñ (Lannion)               	software1	77.61
 8. Koç University (İstanbul)               	software3	77.44
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.78
10. TurkuNLP (Turku)                        	software1	76.43
11. fbaml (Palo Alto)                       	software1	75.42
12. MQuni (Sydney)                          	software2	75.41
13. IIT Kharagpur (Kharagpur)               	software3	75.37
14. LIMSI-LIPN (Paris)                      	software2	75.00
15. BASELINE UDPipe 1.1 (Praha)             	software2	74.65
16. darc (Tübingen)                         	software1	74.14
17. Mengest (Shanghai)                      	software1	74.02
18. OpenU NLP Lab (Ra'anana)                	software6	73.79
19. UALING (Tucson)                         	software1	73.61
20. Wanghao-ftd-SJTU (Shanghai)             	software2	73.59
21. naistCL (Nara)                          	software1	73.54
22. UParse (Edinburgh)                      	software1	72.43
23. RACAI (București)                       	software1	71.85
24. LyS-FASTPARSE (A Coruña)                	software5	71.45
25. CLCL (Genève)                           	software2	70.09
26. METU (Ankara)                           	software2	70.00
27. Uppsala (Uppsala)                       	software1	68.77
28. ParisNLP (Paris)                        	software1	67.33
29. TRL (Tokyo)                             	software1	47.31
30. MetaRomance (Santiago de Compostela)    	software1	46.21
31. Wenba-NLU (Wuhan)                       	software1	 0.84
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ga

<pre>
 1. Stanford (Stanford)                     	software1	61.38
 2. C2L2 (Ithaca)                           	software5	59.84
 3. IMS (Stuttgart)                         	software2	59.82
 4. fbaml (Palo Alto)                       	software1	56.21
 5. RACAI (București)                       	software1	54.55
 6. TurkuNLP (Turku)                        	software1	53.38
 7. Orange – Deskiñ (Lannion)               	software1	53.30
 8. LATTICE (Paris)                         	software7	53.20
 9. Koç University (İstanbul)               	software3	51.95
10. darc (Tübingen)                         	software1	51.25
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	51.24
12. NAIST SATO (Nara)                       	software1	50.84
13. LIMSI-LIPN (Paris)                      	software2	50.68
14. UALING (Tucson)                         	software1	50.59
15. HIT-SCIR (Harbin)                       	software4	50.11
16. UParse (Edinburgh)                      	software1	50.06
    BASELINE UDPipe 1.1 (Praha)             	software2	50.06
18. MQuni (Sydney)                          	software2	49.64
19. Wanghao-ftd-SJTU (Shanghai)             	software2	49.49
20. naistCL (Nara)                          	software1	49.47
21. IIT Kharagpur (Kharagpur)               	software3	46.06
22. LyS-FASTPARSE (A Coruña)                	software5	45.85
23. ParisNLP (Paris)                        	software1	44.12
24. Mengest (Shanghai)                      	software1	41.01
25. OpenU NLP Lab (Ra'anana)                	software6	40.72
26. Uppsala (Uppsala)                       	software1	40.43
27. TRL (Tokyo)                             	software1	25.94
28. MetaRomance (Santiago de Compostela)    	software1	13.85
29. METU (Ankara)                           	software2	 5.41
30. CLCL (Genève)                           	software2	 2.66
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### gl

<pre>
 1. Stanford (Stanford)                     	software1	78.05
 2. C2L2 (Ithaca)                           	software5	77.70
 3. IMS (Stuttgart)                         	software2	76.05
 4. LATTICE (Paris)                         	software7	74.59
 5. HIT-SCIR (Harbin)                       	software4	74.15
 6. Koç University (İstanbul)               	software3	73.96
 7. fbaml (Palo Alto)                       	software1	73.70
 8. MQuni (Sydney)                          	software2	73.68
 9. NAIST SATO (Nara)                       	software1	73.65
10. Orange – Deskiñ (Lannion)               	software1	73.50
11. LyS-FASTPARSE (A Coruña)                	software5	72.84
12. Mengest (Shanghai)                      	software1	72.80
13. naistCL (Nara)                          	software1	71.77
14. RACAI (București)                       	software1	71.28
15. UParse (Edinburgh)                      	software1	70.86
16. TurkuNLP (Turku)                        	software1	70.78
17. ÚFAL – UDPipe 1.2 (Praha)               	software1	70.53
18. LIMSI-LIPN (Paris)                      	software2	69.89
    BASELINE UDPipe 1.1 (Praha)             	software2	69.89
20. ParisNLP (Paris)                        	software1	69.74
21. darc (Tübingen)                         	software1	69.73
22. CLCL (Genève)                           	software2	68.36
23. IIT Kharagpur (Kharagpur)               	software3	68.15
24. METU (Ankara)                           	software2	67.26
25. OpenU NLP Lab (Ra'anana)                	software6	66.82
26. Uppsala (Uppsala)                       	software1	66.81
27. Wanghao-ftd-SJTU (Shanghai)             	software2	66.07
28. UT (Tartu)                              	software1	65.80
29. UALING (Tucson)                         	software1	65.35
30. TRL (Tokyo)                             	software1	42.75
31. MetaRomance (Santiago de Compostela)    	software1	41.50
32. ECNU (Shanghai)                         	software1	 6.82
33. Wenba-NLU (Wuhan)                       	software1	 0.11
</pre>



### gl_treegal

<pre>
 1. C2L2 (Ithaca)                           	software5	67.59
 2. Stanford (Stanford)                     	software1	66.02
 3. IMS (Stuttgart)                         	software2	63.11
 4. Koç University (İstanbul)               	software3	60.27
 5. LATTICE (Paris)                         	software7	59.28
 6. fbaml (Palo Alto)                       	software1	58.70
 7. HIT-SCIR (Harbin)                       	software4	58.10
 8. TurkuNLP (Turku)                        	software1	57.71
 9. NAIST SATO (Nara)                       	software1	57.59
10. ParisNLP (Paris)                        	software1	57.38
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	57.30
12. UALING (Tucson)                         	software1	56.67
13. BASELINE UDPipe 1.1 (Praha)             	software2	56.55
14. LIMSI-LIPN (Paris)                      	software2	56.30
15. Wanghao-ftd-SJTU (Shanghai)             	software2	55.98
16. LyS-FASTPARSE (A Coruña)                	software5	55.56
17. MQuni (Sydney)                          	software2	55.49
18. darc (Tübingen)                         	software1	55.17
19. UParse (Edinburgh)                      	software1	55.01
20. RACAI (București)                       	software1	54.71
21. naistCL (Nara)                          	software1	54.35
22. IIT Kharagpur (Kharagpur)               	software3	53.90
23. Mengest (Shanghai)                      	software1	50.59
24. OpenU NLP Lab (Ra'anana)                	software6	47.86
25. MetaRomance (Santiago de Compostela)    	software1	46.46
26. Uppsala (Uppsala)                       	software1	45.34
27. METU (Ankara)                           	software2	28.46
28. TRL (Tokyo)                             	software1	26.69
29. Orange – Deskiñ (Lannion)               	software1	13.72
30. CLCL (Genève)                           	software2	 2.06
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### got

<pre>
 1. IMS (Stuttgart)                         	software2	69.02
 2. C2L2 (Ithaca)                           	software5	65.77
 3. Stanford (Stanford)                     	software1	63.87
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	59.99
 5. fbaml (Palo Alto)                       	software1	59.00
 6. darc (Tübingen)                         	software1	58.77
 7. LyS-FASTPARSE (A Coruña)                	software5	58.67
 8. RACAI (București)                       	software1	58.61
 9. TurkuNLP (Turku)                        	software1	58.05
10. LIMSI-LIPN (Paris)                      	software2	57.36
11. IIT Kharagpur (Kharagpur)               	software3	56.89
12. HIT-SCIR (Harbin)                       	software4	56.88
13. UParse (Edinburgh)                      	software1	56.71
14. LATTICE (Paris)                         	software7	56.70
15. NAIST SATO (Nara)                       	software1	56.29
16. BASELINE UDPipe 1.1 (Praha)             	software2	56.13
17. Wanghao-ftd-SJTU (Shanghai)             	software2	55.47
18. MQuni (Sydney)                          	software2	55.23
19. ParisNLP (Paris)                        	software1	54.50
20. Orange – Deskiñ (Lannion)               	software1	54.01
21. UALING (Tucson)                         	software1	53.92
22. CLCL (Genève)                           	software2	53.85
23. Mengest (Shanghai)                      	software1	53.01
24. Uppsala (Uppsala)                       	software1	52.63
25. Koç University (İstanbul)               	software3	52.03
26. naistCL (Nara)                          	software1	50.74
27. UT (Tartu)                              	software1	47.83
28. OpenU NLP Lab (Ra'anana)                	software6	45.55
29. TRL (Tokyo)                             	software1	29.15
30. MetaRomance (Santiago de Compostela)    	software1	27.59
31. METU (Ankara)                           	software2	12.62
32. Wenba-NLU (Wuhan)                       	software1	 2.48
33. ECNU (Shanghai)                         	software1	 0.84
</pre>



### grc

<pre>
 1. Stanford (Stanford)                     	software1	67.59
 2. IMS (Stuttgart)                         	software2	61.68
 3. C2L2 (Ithaca)                           	software5	58.84
 4. NAIST SATO (Nara)                       	software1	53.71
 5. LyS-FASTPARSE (A Coruña)                	software5	52.83
 6. RACAI (București)                       	software1	52.77
 7. TurkuNLP (Turku)                        	software1	52.75
 8. HIT-SCIR (Harbin)                       	software4	52.40
 9. darc (Tübingen)                         	software1	51.32
10. Orange – Deskiñ (Lannion)               	software1	50.72
11. fbaml (Palo Alto)                       	software1	50.49
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	50.19
13. UParse (Edinburgh)                      	software1	49.82
14. LIMSI-LIPN (Paris)                      	software2	48.50
    BASELINE UDPipe 1.1 (Praha)             	software2	48.50
16. CLCL (Genève)                           	software2	47.68
17. IIT Kharagpur (Kharagpur)               	software3	45.76
18. LATTICE (Paris)                         	software7	44.46
19. UALING (Tucson)                         	software1	44.40
20. Wanghao-ftd-SJTU (Shanghai)             	software2	43.52
21. Uppsala (Uppsala)                       	software1	42.72
22. Mengest (Shanghai)                      	software1	41.96
23. METU (Ankara)                           	software2	41.94
24. naistCL (Nara)                          	software1	40.97
25. MQuni (Sydney)                          	software2	40.57
26. Koç University (İstanbul)               	software3	40.53
27. ParisNLP (Paris)                        	software1	38.61
28. UT (Tartu)                              	software1	32.50
29. OpenU NLP Lab (Ra'anana)                	software6	22.80
30. TRL (Tokyo)                             	software1	17.09
31. MetaRomance (Santiago de Compostela)    	software1	11.65
32. Wenba-NLU (Wuhan)                       	software1	 1.39
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### grc_proiel

<pre>
 1. IMS (Stuttgart)                         	software2	69.73
 2. Stanford (Stanford)                     	software1	68.83
 3. C2L2 (Ithaca)                           	software5	64.45
 4. NAIST SATO (Nara)                       	software1	62.43
 5. RACAI (București)                       	software1	62.29
 6. HIT-SCIR (Harbin)                       	software4	62.25
 7. LyS-FASTPARSE (A Coruña)                	software5	61.03
 8. TurkuNLP (Turku)                        	software1	60.98
 9. fbaml (Palo Alto)                       	software1	60.06
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	59.43
11. darc (Tübingen)                         	software1	59.12
12. Orange – Deskiñ (Lannion)               	software1	57.65
13. LIMSI-LIPN (Paris)                      	software2	57.52
    BASELINE UDPipe 1.1 (Praha)             	software2	57.52
15. Uppsala (Uppsala)                       	software1	56.90
16. UParse (Edinburgh)                      	software1	56.69
17. IIT Kharagpur (Kharagpur)               	software3	56.35
18. Wanghao-ftd-SJTU (Shanghai)             	software2	54.41
19. CLCL (Genève)                           	software2	54.38
20. naistCL (Nara)                          	software1	53.70
21. UALING (Tucson)                         	software1	53.41
22. Koç University (İstanbul)               	software3	52.32
23. MQuni (Sydney)                          	software2	51.79
24. LATTICE (Paris)                         	software7	51.62
25. Mengest (Shanghai)                      	software1	51.23
26. METU (Ankara)                           	software2	50.66
27. OpenU NLP Lab (Ra'anana)                	software6	40.95
28. ParisNLP (Paris)                        	software1	39.07
29. TRL (Tokyo)                             	software1	24.29
30. MetaRomance (Santiago de Compostela)    	software1	20.77
31. Wenba-NLU (Wuhan)                       	software1	 0.75
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### he

<pre>
 1. IMS (Stuttgart)                         	software2	61.10
 2. Stanford (Stanford)                     	software1	56.78
 3. C2L2 (Ithaca)                           	software5	55.01
 4. Uppsala (Uppsala)                       	software1	54.72
 5. LATTICE (Paris)                         	software7	53.25
 6. HIT-SCIR (Harbin)                       	software4	51.95
 7. RACAI (București)                       	software1	51.74
 8. LyS-FASTPARSE (A Coruña)                	software5	50.79
 9. NAIST SATO (Nara)                       	software1	50.69
10. Koç University (İstanbul)               	software3	50.63
11. MQuni (Sydney)                          	software2	50.01
12. Mengest (Shanghai)                      	software1	49.49
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	49.32
14. Orange – Deskiñ (Lannion)               	software1	49.30
15. TurkuNLP (Turku)                        	software1	49.04
16. LIMSI-LIPN (Paris)                      	software2	48.48
    BASELINE UDPipe 1.1 (Praha)             	software2	48.48
18. naistCL (Nara)                          	software1	48.39
19. darc (Tübingen)                         	software1	48.24
20. UParse (Edinburgh)                      	software1	48.17
21. IIT Kharagpur (Kharagpur)               	software3	47.80
22. Wanghao-ftd-SJTU (Shanghai)             	software2	46.98
23. UALING (Tucson)                         	software1	46.63
24. METU (Ankara)                           	software2	46.16
25. CLCL (Genève)                           	software2	45.96
    fbaml (Palo Alto)                       	software1	45.96
27. ParisNLP (Paris)                        	software1	33.96
28. OpenU NLP Lab (Ra'anana)                	software6	31.41
29. TRL (Tokyo)                             	software1	24.47
30. MetaRomance (Santiago de Compostela)    	software1	18.97
31. Wenba-NLU (Wuhan)                       	software1	 0.20
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hi

<pre>
 1. Stanford (Stanford)                     	software1	87.92
 2. IMS (Stuttgart)                         	software2	86.30
 3. C2L2 (Ithaca)                           	software5	86.06
 4. HIT-SCIR (Harbin)                       	software4	85.04
 5. NAIST SATO (Nara)                       	software1	83.80
 6. fbaml (Palo Alto)                       	software1	82.76
 7. TurkuNLP (Turku)                        	software1	82.71
 8. Orange – Deskiñ (Lannion)               	software1	82.37
 9. darc (Tübingen)                         	software1	82.33
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	82.09
11. Koç University (İstanbul)               	software3	81.76
12. LATTICE (Paris)                         	software7	81.63
13. naistCL (Nara)                          	software1	81.56
14. CLCL (Genève)                           	software2	81.55
15. LIMSI-LIPN (Paris)                      	software2	81.44
16. UParse (Edinburgh)                      	software1	81.42
17. BASELINE UDPipe 1.1 (Praha)             	software2	81.34
18. LyS-FASTPARSE (A Coruña)                	software5	81.32
19. MQuni (Sydney)                          	software2	81.24
20. Mengest (Shanghai)                      	software1	81.22
21. IIT Kharagpur (Kharagpur)               	software3	81.01
22. Wanghao-ftd-SJTU (Shanghai)             	software2	79.83
23. UALING (Tucson)                         	software1	79.34
24. UT (Tartu)                              	software1	79.31
25. METU (Ankara)                           	software2	78.65
26. RACAI (București)                       	software1	78.59
27. Uppsala (Uppsala)                       	software1	71.46
28. OpenU NLP Lab (Ra'anana)                	software6	59.90
29. ParisNLP (Paris)                        	software1	38.59
30. TRL (Tokyo)                             	software1	37.96
31. MetaRomance (Santiago de Compostela)    	software1	 7.66
32. Wenba-NLU (Wuhan)                       	software1	 0.57
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### hi_pud

<pre>
 1. Stanford (Stanford)                     	software1	48.87
 2. C2L2 (Ithaca)                           	software5	48.12
 3. HIT-SCIR (Harbin)                       	software4	48.03
 4. IMS (Stuttgart)                         	software2	47.53
 5. NAIST SATO (Nara)                       	software1	46.85
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	46.18
 7. TurkuNLP (Turku)                        	software1	45.67
 8. UParse (Edinburgh)                      	software1	45.20
 9. Orange – Deskiñ (Lannion)               	software1	45.06
10. Koç University (İstanbul)               	software3	44.87
11. IIT Kharagpur (Kharagpur)               	software3	44.82
12. CLCL (Genève)                           	software1	44.77
13. Wanghao-ftd-SJTU (Shanghai)             	software2	44.75
14. darc (Tübingen)                         	software1	44.64
15. LIMSI-LIPN (Paris)                      	software2	44.59
16. LATTICE (Paris)                         	software7	44.51
17. LyS-FASTPARSE (A Coruña)                	software5	44.48
18. BASELINE UDPipe 1.1 (Praha)             	software2	44.42
19. Mengest (Shanghai)                      	software1	44.34
20. naistCL (Nara)                          	software1	44.29
21. UALING (Tucson)                         	software1	44.13
22. METU (Ankara)                           	software2	43.33
23. MQuni (Sydney)                          	software2	43.13
24. UT (Tartu)                              	software1	42.86
25. RACAI (București)                       	software1	39.47
26. Uppsala (Uppsala)                       	software1	39.26
27. fbaml (Palo Alto)                       	software1	36.58
28. OpenU NLP Lab (Ra'anana)                	software6	35.07
29. ParisNLP (Paris)                        	software1	28.33
30. TRL (Tokyo)                             	software1	24.13
31. MetaRomance (Santiago de Compostela)    	software1	 9.71
32. ECNU (Shanghai)                         	software1	 0.23
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### hr

<pre>
 1. Stanford (Stanford)                     	software1	82.36
 2. C2L2 (Ithaca)                           	software5	80.11
 3. IMS (Stuttgart)                         	software2	79.56
 4. HIT-SCIR (Harbin)                       	software4	78.01
 5. LATTICE (Paris)                         	software7	77.82
 6. NAIST SATO (Nara)                       	software1	75.77
 7. Koç University (İstanbul)               	software3	75.71
 8. MQuni (Sydney)                          	software2	75.30
 9. TurkuNLP (Turku)                        	software1	75.07
10. LIMSI-LIPN (Paris)                      	software2	74.63
11. LyS-FASTPARSE (A Coruña)                	software5	73.90
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	73.85
13. darc (Tübingen)                         	software1	73.54
14. UParse (Edinburgh)                      	software1	73.42
    BASELINE UDPipe 1.1 (Praha)             	software2	73.42
16. Orange – Deskiñ (Lannion)               	software1	73.31
17. RACAI (București)                       	software1	73.08
18. fbaml (Palo Alto)                       	software1	73.05
19. Mengest (Shanghai)                      	software1	72.89
20. naistCL (Nara)                          	software1	72.79
21. IIT Kharagpur (Kharagpur)               	software3	72.65
22. Uppsala (Uppsala)                       	software1	71.58
23. UT (Tartu)                              	software1	71.39
24. Wanghao-ftd-SJTU (Shanghai)             	software2	71.09
25. ParisNLP (Paris)                        	software1	70.92
26. UALING (Tucson)                         	software1	70.67
27. CLCL (Genève)                           	software1	69.86
28. METU (Ankara)                           	software2	67.21
29. OpenU NLP Lab (Ra'anana)                	software6	54.16
30. TRL (Tokyo)                             	software1	40.56
31. MetaRomance (Santiago de Compostela)    	software1	38.58
32. ECNU (Shanghai)                         	software1	 0.81
33. Wenba-NLU (Wuhan)                       	software1	 0.20
</pre>



### hsb

<pre>
 1. Stanford (Stanford)                     	software1	56.32
 2. C2L2 (Ithaca)                           	software5	55.96
 3. IMS (Stuttgart)                         	software2	55.95
 4. UParse (Edinburgh)                      	software1	54.26
 5. HIT-SCIR (Harbin)                       	software4	53.67
 6. Orange – Deskiñ (Lannion)               	software1	53.14
 7. LIMSI-LIPN (Paris)                      	software2	52.70
 8. Wanghao-ftd-SJTU (Shanghai)             	software2	51.82
 9. ParisNLP (Paris)                        	software1	51.61
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	51.04
11. darc (Tübingen)                         	software1	49.50
12. IIT Kharagpur (Kharagpur)               	software3	49.31
13. BASELINE UDPipe 1.1 (Praha)             	software2	47.27
14. LyS-FASTPARSE (A Coruña)                	software5	46.16
15. OpenU NLP Lab (Ra'anana)                	software6	45.88
16. Koç University (İstanbul)               	software3	45.73
17. LATTICE (Paris)                         	software7	45.08
18. naistCL (Nara)                          	software1	42.72
19. UALING (Tucson)                         	software1	42.15
20. CLCL (Genève)                           	software2	41.02
21. RACAI (București)                       	software1	38.29
22. Uppsala (Uppsala)                       	software1	37.00
23. NAIST SATO (Nara)                       	software1	35.37
24. MetaRomance (Santiago de Compostela)    	software1	34.25
25. TurkuNLP (Turku)                        	software1	33.40
26. fbaml (Palo Alto)                       	software1	18.00
27. TRL (Tokyo)                             	software1	15.34
28. METU (Ankara)                           	software2	14.51
29. MQuni (Sydney)                          	software2	12.39
30. Mengest (Shanghai)                      	software1	11.94
31. ECNU (Shanghai)                         	software1	 3.66
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hu

<pre>
 1. Stanford (Stanford)                     	software1	76.08
 2. C2L2 (Ithaca)                           	software5	74.36
 3. IMS (Stuttgart)                         	software2	70.87
 4. Koç University (İstanbul)               	software3	66.69
 5. LATTICE (Paris)                         	software7	64.99
 6. LyS-FASTPARSE (A Coruña)                	software5	64.14
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	63.48
 8. MQuni (Sydney)                          	software2	63.36
 9. TurkuNLP (Turku)                        	software1	62.82
10. darc (Tübingen)                         	software1	62.55
11. Orange – Deskiñ (Lannion)               	software1	62.19
12. HIT-SCIR (Harbin)                       	software4	61.97
13. IIT Kharagpur (Kharagpur)               	software3	61.86
14. Wanghao-ftd-SJTU (Shanghai)             	software2	61.72
    LIMSI-LIPN (Paris)                      	software2	61.72
16. RACAI (București)                       	software1	61.67
17. UALING (Tucson)                         	software1	61.38
18. UParse (Edinburgh)                      	software1	60.83
    BASELINE UDPipe 1.1 (Praha)             	software2	60.83
20. fbaml (Palo Alto)                       	software1	59.39
21. naistCL (Nara)                          	software1	58.76
22. NAIST SATO (Nara)                       	software1	54.53
23. UT (Tartu)                              	software1	52.39
24. Mengest (Shanghai)                      	software1	51.76
25. Uppsala (Uppsala)                       	software1	51.27
26. METU (Ankara)                           	software2	46.23
27. CLCL (Genève)                           	software1	44.92
28. ParisNLP (Paris)                        	software1	44.29
29. OpenU NLP Lab (Ra'anana)                	software6	32.36
30. TRL (Tokyo)                             	software1	27.83
31. MetaRomance (Santiago de Compostela)    	software1	26.43
32. ECNU (Shanghai)                         	software1	 3.79
33. Wenba-NLU (Wuhan)                       	software1	 0.07
</pre>



### id

<pre>
 1. Stanford (Stanford)                     	software1	77.15
 2. C2L2 (Ithaca)                           	software5	76.20
 3. IMS (Stuttgart)                         	software2	75.18
 4. LATTICE (Paris)                         	software7	74.49
 5. MQuni (Sydney)                          	software2	74.33
 6. HIT-SCIR (Harbin)                       	software4	74.27
 7. NAIST SATO (Nara)                       	software1	74.08
 8. fbaml (Palo Alto)                       	software1	73.53
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	73.37
10. Koç University (İstanbul)               	software3	73.23
11. TurkuNLP (Turku)                        	software1	72.50
12. LIMSI-LIPN (Paris)                      	software2	72.46
13. UParse (Edinburgh)                      	software1	72.42
14. BASELINE UDPipe 1.1 (Praha)             	software2	72.21
15. naistCL (Nara)                          	software1	72.11
16. RACAI (București)                       	software1	72.01
17. Mengest (Shanghai)                      	software1	71.85
18. IIT Kharagpur (Kharagpur)               	software3	71.66
19. darc (Tübingen)                         	software1	71.43
20. Orange – Deskiñ (Lannion)               	software1	70.93
21. Wanghao-ftd-SJTU (Shanghai)             	software2	70.84
22. LyS-FASTPARSE (A Coruña)                	software5	70.53
23. UALING (Tucson)                         	software1	69.97
24. UT (Tartu)                              	software1	69.95
25. Uppsala (Uppsala)                       	software1	69.73
26. CLCL (Genève)                           	software2	67.05
27. METU (Ankara)                           	software2	65.89
28. OpenU NLP Lab (Ra'anana)                	software6	65.23
29. ParisNLP (Paris)                        	software1	61.52
30. TRL (Tokyo)                             	software1	50.75
31. MetaRomance (Santiago de Compostela)    	software1	33.51
32. ECNU (Shanghai)                         	software1	 2.41
33. Wenba-NLU (Wuhan)                       	software1	 1.66
</pre>



### it

<pre>
 1. Stanford (Stanford)                     	software1	86.18
 2. C2L2 (Ithaca)                           	software5	83.80
 3. LATTICE (Paris)                         	software7	82.43
 4. HIT-SCIR (Harbin)                       	software4	82.29
 5. IMS (Stuttgart)                         	software2	82.26
 6. NAIST SATO (Nara)                       	software1	81.48
 7. Orange – Deskiñ (Lannion)               	software1	80.75
 8. MQuni (Sydney)                          	software2	80.68
 9. Koç University (İstanbul)               	software3	80.52
10. UParse (Edinburgh)                      	software1	80.46
11. fbaml (Palo Alto)                       	software1	80.14
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.70
13. Mengest (Shanghai)                      	software1	79.63
14. TurkuNLP (Turku)                        	software1	79.40
15. LyS-FASTPARSE (A Coruña)                	software5	79.18
16. naistCL (Nara)                          	software1	79.16
17. BASELINE UDPipe 1.1 (Praha)             	software2	78.62
18. LIMSI-LIPN (Paris)                      	software2	78.61
19. darc (Tübingen)                         	software1	78.41
20. CLCL (Genève)                           	software2	78.15
21. Wanghao-ftd-SJTU (Shanghai)             	software2	77.79
    Uppsala (Uppsala)                       	software1	77.79
23. IIT Kharagpur (Kharagpur)               	software3	77.64
24. RACAI (București)                       	software1	77.28
25. UALING (Tucson)                         	software1	76.54
26. METU (Ankara)                           	software2	75.75
27. ParisNLP (Paris)                        	software1	73.13
28. OpenU NLP Lab (Ra'anana)                	software6	68.75
29. MetaRomance (Santiago de Compostela)    	software1	50.08
30. TRL (Tokyo)                             	software1	45.71
31. Wenba-NLU (Wuhan)                       	software1	 0.42
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### it_pud

<pre>
 1. Stanford (Stanford)                     	software1	84.49
 2. C2L2 (Ithaca)                           	software5	82.54
 3. LATTICE (Paris)                         	software7	82.22
 4. IMS (Stuttgart)                         	software2	81.97
 5. HIT-SCIR (Harbin)                       	software4	80.97
 6. NAIST SATO (Nara)                       	software1	80.45
 7. UParse (Edinburgh)                      	software1	80.35
 8. Orange – Deskiñ (Lannion)               	software1	80.16
 9. MQuni (Sydney)                          	software2	80.13
10. fbaml (Palo Alto)                       	software1	79.31
11. Koç University (İstanbul)               	software3	79.28
12. TurkuNLP (Turku)                        	software1	79.04
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	78.72
14. naistCL (Nara)                          	software1	78.43
15. darc (Tübingen)                         	software1	78.42
16. LyS-FASTPARSE (A Coruña)                	software5	78.38
17. LIMSI-LIPN (Paris)                      	software2	78.24
    BASELINE UDPipe 1.1 (Praha)             	software2	78.24
19. Mengest (Shanghai)                      	software1	78.18
20. Uppsala (Uppsala)                       	software1	77.77
21. CLCL (Genève)                           	software1	77.50
22. IIT Kharagpur (Kharagpur)               	software3	77.15
23. Wanghao-ftd-SJTU (Shanghai)             	software2	76.59
24. RACAI (București)                       	software1	76.32
25. UALING (Tucson)                         	software1	75.93
26. ParisNLP (Paris)                        	software1	75.06
27. METU (Ankara)                           	software2	73.88
28. OpenU NLP Lab (Ra'anana)                	software6	65.40
29. MetaRomance (Santiago de Compostela)    	software1	54.37
30. TRL (Tokyo)                             	software1	45.69
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ja

<pre>
 1. TRL (Tokyo)                             	software1	83.18
 2. HIT-SCIR (Harbin)                       	software4	72.53
 3. LIMSI-LIPN (Paris)                      	software2	70.83
 4. fbaml (Palo Alto)                       	software1	69.97
 5. IMS (Stuttgart)                         	software2	69.52
 6. Stanford (Stanford)                     	software1	65.90
 7. C2L2 (Ithaca)                           	software5	65.77
 8. LATTICE (Paris)                         	software7	65.04
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	64.71
10. NAIST SATO (Nara)                       	software1	64.07
11. Orange – Deskiñ (Lannion)               	software1	63.50
12. Mengest (Shanghai)                      	software1	63.39
13. MQuni (Sydney)                          	software2	63.32
14. LyS-FASTPARSE (A Coruña)                	software5	63.21
15. TurkuNLP (Turku)                        	software1	62.97
16. Koç University (İstanbul)               	software3	62.89
17. UT (Tartu)                              	software1	62.88
18. darc (Tübingen)                         	software1	62.60
19. IIT Kharagpur (Kharagpur)               	software3	62.26
20. UParse (Edinburgh)                      	software1	62.06
    BASELINE UDPipe 1.1 (Praha)             	software2	62.06
22. Wanghao-ftd-SJTU (Shanghai)             	software2	61.63
23. CLCL (Genève)                           	software2	61.45
24. UALING (Tucson)                         	software1	61.24
25. naistCL (Nara)                          	software1	60.69
26. METU (Ankara)                           	software2	59.31
27. OpenU NLP Lab (Ra'anana)                	software6	56.55
28. Uppsala (Uppsala)                       	software1	55.90
29. RACAI (București)                       	software1	55.51
30. ParisNLP (Paris)                        	software1	46.68
31. MetaRomance (Santiago de Compostela)    	software1	 2.41
32. ECNU (Shanghai)                         	software1	 0.64
33. Wenba-NLU (Wuhan)                       	software1	 0.04
</pre>



### ja_pud

<pre>
 1. HIT-SCIR (Harbin)                       	software4	75.63
 2. LIMSI-LIPN (Paris)                      	software2	74.23
 3. IMS (Stuttgart)                         	software2	73.28
 4. fbaml (Palo Alto)                       	software1	71.46
 5. C2L2 (Ithaca)                           	software5	69.21
 6. Stanford (Stanford)                     	software1	68.95
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	68.31
 8. LATTICE (Paris)                         	software7	68.05
 9. NAIST SATO (Nara)                       	software1	67.26
10. MQuni (Sydney)                          	software2	67.03
11. Mengest (Shanghai)                      	software1	66.81
12. Orange – Deskiñ (Lannion)               	software1	66.68
13. UT (Tartu)                              	software1	66.27
14. BASELINE UDPipe 1.1 (Praha)             	software2	66.26
15. LyS-FASTPARSE (A Coruña)                	software5	66.11
    Koç University (İstanbul)               	software3	66.11
17. TurkuNLP (Turku)                        	software1	65.96
18. CLCL (Genève)                           	software1	65.81
19. IIT Kharagpur (Kharagpur)               	software3	65.63
20. darc (Tübingen)                         	software1	65.16
21. Uppsala (Uppsala)                       	software1	64.90
22. UALING (Tucson)                         	software1	64.65
23. Wanghao-ftd-SJTU (Shanghai)             	software2	64.52
24. METU (Ankara)                           	software2	63.17
25. RACAI (București)                       	software1	62.73
26. UParse (Edinburgh)                      	software1	62.51
27. naistCL (Nara)                          	software1	62.11
28. OpenU NLP Lab (Ra'anana)                	software6	58.70
29. TRL (Tokyo)                             	software1	46.61
30. ParisNLP (Paris)                        	software1	43.62
31. MetaRomance (Santiago de Compostela)    	software1	 1.96
32. ECNU (Shanghai)                         	software1	 0.44
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### kk

<pre>
 1. RACAI (București)                       	software1	25.14
 2. TurkuNLP (Turku)                        	software1	23.39
 3. C2L2 (Ithaca)                           	software5	23.30
 4. ParisNLP (Paris)                        	software1	21.70
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	20.17
 6. UALING (Tucson)                         	software1	19.66
 7. HIT-SCIR (Harbin)                       	software4	19.53
 8. BASELINE UDPipe 1.1 (Praha)             	software2	19.33
 9. Stanford (Stanford)                     	software1	19.32
10. IMS (Stuttgart)                         	software2	19.07
11. IIT Kharagpur (Kharagpur)               	software3	18.87
12. darc (Tübingen)                         	software1	18.57
13. TRL (Tokyo)                             	software1	18.27
14. fbaml (Palo Alto)                       	software1	17.32
15. naistCL (Nara)                          	software1	17.22
16. Wanghao-ftd-SJTU (Shanghai)             	software2	17.07
17. UParse (Edinburgh)                      	software1	16.89
18. LIMSI-LIPN (Paris)                      	software2	16.85
19. NAIST SATO (Nara)                       	software1	16.78
20. LATTICE (Paris)                         	software7	16.73
21. Koç University (İstanbul)               	software3	15.80
22. Orange – Deskiñ (Lannion)               	software1	14.67
23. MQuni (Sydney)                          	software2	14.63
24. LyS-FASTPARSE (A Coruña)                	software5	12.48
25. METU (Ankara)                           	software2	11.65
26. OpenU NLP Lab (Ra'anana)                	software6	11.63
27. Uppsala (Uppsala)                       	software1	10.37
28. MetaRomance (Santiago de Compostela)    	software1	 5.58
29. CLCL (Genève)                           	software2	 1.18
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. UT (Tartu)                              	software1	 0.00
33. Mengest (Shanghai)                      	software1	 0.00
</pre>



### kmr

<pre>
 1. C2L2 (Ithaca)                           	software5	44.54
 2. IMS (Stuttgart)                         	software2	40.47
 3. HIT-SCIR (Harbin)                       	software4	40.27
 4. UALING (Tucson)                         	software1	37.77
    Koç University (İstanbul)               	software3	37.77
 6. LATTICE (Paris)                         	software7	34.29
 7. UParse (Edinburgh)                      	software1	33.77
 8. Orange – Deskiñ (Lannion)               	software1	32.41
 9. LIMSI-LIPN (Paris)                      	software2	28.84
10. Stanford (Stanford)                     	software1	28.72
11. OpenU NLP Lab (Ra'anana)                	software6	26.42
12. darc (Tübingen)                         	software1	25.90
13. ParisNLP (Paris)                        	software1	25.78
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	25.16
15. BASELINE UDPipe 1.1 (Praha)             	software2	24.81
16. LyS-FASTPARSE (A Coruña)                	software5	24.60
17. IIT Kharagpur (Kharagpur)               	software3	24.19
18. naistCL (Nara)                          	software1	21.42
19. fbaml (Palo Alto)                       	software1	19.91
20. MetaRomance (Santiago de Compostela)    	software1	17.97
21. MQuni (Sydney)                          	software2	15.59
22. NAIST SATO (Nara)                       	software1	14.99
23. METU (Ankara)                           	software2	14.62
24. CLCL (Genève)                           	software2	14.52
25. TurkuNLP (Turku)                        	software1	14.51
26. Wanghao-ftd-SJTU (Shanghai)             	software2	14.27
27. Uppsala (Uppsala)                       	software1	12.22
28. RACAI (București)                       	software1	10.85
29. Mengest (Shanghai)                      	software1	 5.46
30. TRL (Tokyo)                             	software1	 3.73
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ko

<pre>
 1. Stanford (Stanford)                     	software1	80.85
 2. C2L2 (Ithaca)                           	software5	79.23
 3. IMS (Stuttgart)                         	software2	77.33
 4. naistCL (Nara)                          	software1	72.08
 5. MQuni (Sydney)                          	software2	71.29
 6. LATTICE (Paris)                         	software7	70.25
 7. HIT-SCIR (Harbin)                       	software4	69.68
 8. Koç University (İstanbul)               	software3	69.13
 9. Uppsala (Uppsala)                       	software1	67.14
10. Orange – Deskiñ (Lannion)               	software1	65.35
11. TurkuNLP (Turku)                        	software1	64.42
12. NAIST SATO (Nara)                       	software1	61.76
13. METU (Ankara)                           	software2	61.63
14. LyS-FASTPARSE (A Coruña)                	software5	61.16
15. Mengest (Shanghai)                      	software1	60.72
16. RACAI (București)                       	software1	60.48
17. fbaml (Palo Alto)                       	software1	59.02
18. CLCL (Genève)                           	software2	58.66
19. UT (Tartu)                              	software1	57.63
20. ÚFAL – UDPipe 1.2 (Praha)               	software1	57.18
21. UParse (Edinburgh)                      	software1	55.91
    LIMSI-LIPN (Paris)                      	software2	55.91
    BASELINE UDPipe 1.1 (Praha)             	software2	55.91
24. IIT Kharagpur (Kharagpur)               	software3	55.15
25. darc (Tübingen)                         	software1	54.95
26. Wanghao-ftd-SJTU (Shanghai)             	software2	50.61
27. UALING (Tucson)                         	software1	49.35
28. OpenU NLP Lab (Ra'anana)                	software6	48.37
29. TRL (Tokyo)                             	software1	42.12
30. ParisNLP (Paris)                        	software1	39.67
31. MetaRomance (Santiago de Compostela)    	software1	12.15
32. ECNU (Shanghai)                         	software1	 7.04
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la

<pre>
 1. Stanford (Stanford)                     	software1	58.96
 2. C2L2 (Ithaca)                           	software5	54.69
 3. LATTICE (Paris)                         	software7	47.16
 4. IMS (Stuttgart)                         	software2	46.69
 5. NAIST SATO (Nara)                       	software1	45.96
 6. HIT-SCIR (Harbin)                       	software4	44.04
 7. fbaml (Palo Alto)                       	software1	43.46
 8. TurkuNLP (Turku)                        	software1	42.69
 9. LyS-FASTPARSE (A Coruña)                	software5	42.63
10. Orange – Deskiñ (Lannion)               	software1	42.17
11. Koç University (İstanbul)               	software3	42.02
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	41.83
13. RACAI (București)                       	software1	41.22
14. darc (Tübingen)                         	software1	40.51
15. UALING (Tucson)                         	software1	39.52
16. Wanghao-ftd-SJTU (Shanghai)             	software2	39.01
17. IIT Kharagpur (Kharagpur)               	software3	38.73
18. UParse (Edinburgh)                      	software1	38.72
    BASELINE UDPipe 1.1 (Praha)             	software2	38.72
20. LIMSI-LIPN (Paris)                      	software2	38.30
21. MQuni (Sydney)                          	software2	37.75
22. ParisNLP (Paris)                        	software1	37.08
23. Mengest (Shanghai)                      	software1	33.26
24. UT (Tartu)                              	software1	32.40
25. Uppsala (Uppsala)                       	software1	31.89
26. naistCL (Nara)                          	software1	29.48
27. TRL (Tokyo)                             	software1	19.91
28. OpenU NLP Lab (Ra'anana)                	software6	19.21
29. MetaRomance (Santiago de Compostela)    	software1	17.25
30. METU (Ankara)                           	software2	14.38
31. CLCL (Genève)                           	software2	 6.72
32. ECNU (Shanghai)                         	software1	 2.77
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_ittb

<pre>
 1. Stanford (Stanford)                     	software1	84.94
 2. IMS (Stuttgart)                         	software2	81.64
 3. C2L2 (Ithaca)                           	software5	79.67
 4. NAIST SATO (Nara)                       	software1	79.03
 5. HIT-SCIR (Harbin)                       	software4	78.53
 6. Uppsala (Uppsala)                       	software1	76.47
 7. Orange – Deskiñ (Lannion)               	software1	76.42
 8. LyS-FASTPARSE (A Coruña)                	software5	75.84
 9. UParse (Edinburgh)                      	software1	75.50
10. TurkuNLP (Turku)                        	software1	75.48
11. fbaml (Palo Alto)                       	software1	73.81
12. darc (Tübingen)                         	software1	73.38
13. LIMSI-LIPN (Paris)                      	software2	73.13
    BASELINE UDPipe 1.1 (Praha)             	software2	73.13
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	72.91
16. IIT Kharagpur (Kharagpur)               	software3	72.04
17. CLCL (Genève)                           	software1	71.89
18. Koç University (İstanbul)               	software3	71.86
19. Wanghao-ftd-SJTU (Shanghai)             	software2	70.97
20. RACAI (București)                       	software1	70.67
21. naistCL (Nara)                          	software1	70.64
22. Mengest (Shanghai)                      	software1	69.95
23. LATTICE (Paris)                         	software7	69.73
24. MQuni (Sydney)                          	software2	69.34
25. UALING (Tucson)                         	software1	68.73
26. METU (Ankara)                           	software2	66.22
27. ParisNLP (Paris)                        	software1	46.87
28. OpenU NLP Lab (Ra'anana)                	software6	44.04
29. TRL (Tokyo)                             	software1	31.04
30. MetaRomance (Santiago de Compostela)    	software1	26.08
31. UT (Tartu)                              	software1	23.69
32. ECNU (Shanghai)                         	software1	 4.54
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_proiel

<pre>
 1. IMS (Stuttgart)                         	software2	68.93
 2. Stanford (Stanford)                     	software1	66.56
 3. C2L2 (Ithaca)                           	software5	60.89
 4. HIT-SCIR (Harbin)                       	software4	60.40
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	58.27
 6. LyS-FASTPARSE (A Coruña)                	software5	57.95
 7. fbaml (Palo Alto)                       	software1	57.91
 8. NAIST SATO (Nara)                       	software1	57.90
 9. Orange – Deskiñ (Lannion)               	software1	56.87
10. RACAI (București)                       	software1	56.77
11. darc (Tübingen)                         	software1	56.13
    TurkuNLP (Turku)                        	software1	56.13
13. Koç University (İstanbul)               	software3	55.76
14. Uppsala (Uppsala)                       	software1	54.92
15. BASELINE UDPipe 1.1 (Praha)             	software2	53.91
16. LIMSI-LIPN (Paris)                      	software2	53.83
17. UParse (Edinburgh)                      	software1	53.55
18. IIT Kharagpur (Kharagpur)               	software3	53.37
19. LATTICE (Paris)                         	software7	51.78
20. Wanghao-ftd-SJTU (Shanghai)             	software2	51.49
21. UALING (Tucson)                         	software1	50.36
22. CLCL (Genève)                           	software1	49.84
23. Mengest (Shanghai)                      	software1	49.34
24. naistCL (Nara)                          	software1	48.98
25. MQuni (Sydney)                          	software2	48.66
26. METU (Ankara)                           	software2	47.77
27. ParisNLP (Paris)                        	software1	38.14
28. OpenU NLP Lab (Ra'anana)                	software6	31.87
29. TRL (Tokyo)                             	software1	21.46
30. MetaRomance (Santiago de Compostela)    	software1	19.30
31. Wenba-NLU (Wuhan)                       	software1	 0.83
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### lv

<pre>
 1. Stanford (Stanford)                     	software1	70.22
 2. C2L2 (Ithaca)                           	software5	66.90
 3. IMS (Stuttgart)                         	software2	63.29
 4. LATTICE (Paris)                         	software7	60.02
 5. HIT-SCIR (Harbin)                       	software4	59.43
 6. Koç University (İstanbul)               	software3	58.59
 7. LyS-FASTPARSE (A Coruña)                	software5	57.48
 8. darc (Tübingen)                         	software1	57.28
 9. TurkuNLP (Turku)                        	software1	57.25
10. Orange – Deskiñ (Lannion)               	software1	57.00
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	56.75
12. IIT Kharagpur (Kharagpur)               	software3	56.44
13. fbaml (Palo Alto)                       	software1	55.40
14. MQuni (Sydney)                          	software2	55.10
15. LIMSI-LIPN (Paris)                      	software2	55.01
16. UParse (Edinburgh)                      	software1	54.75
    BASELINE UDPipe 1.1 (Praha)             	software2	54.75
18. UALING (Tucson)                         	software1	54.70
19. RACAI (București)                       	software1	54.51
20. CLCL (Genève)                           	software1	54.23
21. Mengest (Shanghai)                      	software1	54.18
22. Wanghao-ftd-SJTU (Shanghai)             	software2	54.02
23. NAIST SATO (Nara)                       	software1	53.96
24. METU (Ankara)                           	software2	51.47
25. naistCL (Nara)                          	software1	50.72
26. UT (Tartu)                              	software1	49.02
27. Uppsala (Uppsala)                       	software1	47.88
28. ParisNLP (Paris)                        	software1	45.13
29. OpenU NLP Lab (Ra'anana)                	software6	40.34
30. TRL (Tokyo)                             	software1	28.62
31. MetaRomance (Santiago de Compostela)    	software1	20.12
32. ECNU (Shanghai)                         	software1	 2.09
33. Wenba-NLU (Wuhan)                       	software1	 0.29
</pre>



### nl

<pre>
 1. Stanford (Stanford)                     	software1	75.19
 2. IMS (Stuttgart)                         	software2	68.18
 3. C2L2 (Ithaca)                           	software5	67.68
 4. HIT-SCIR (Harbin)                       	software4	66.93
 5. NAIST SATO (Nara)                       	software1	66.21
 6. fbaml (Palo Alto)                       	software1	64.78
 7. Orange – Deskiñ (Lannion)               	software1	64.68
 8. LyS-FASTPARSE (A Coruña)                	software5	64.40
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	63.16
10. LATTICE (Paris)                         	software7	62.84
11. TurkuNLP (Turku)                        	software1	62.27
12. Uppsala (Uppsala)                       	software1	62.12
13. Koç University (İstanbul)               	software3	61.99
14. UParse (Edinburgh)                      	software1	61.70
15. BASELINE UDPipe 1.1 (Praha)             	software2	61.27
16. darc (Tübingen)                         	software1	61.18
17. Mengest (Shanghai)                      	software1	60.79
18. MQuni (Sydney)                          	software2	60.61
19. IIT Kharagpur (Kharagpur)               	software3	60.07
20. naistCL (Nara)                          	software1	59.80
21. LIMSI-LIPN (Paris)                      	software2	59.72
22. RACAI (București)                       	software1	59.48
23. CLCL (Genève)                           	software1	59.36
24. Wanghao-ftd-SJTU (Shanghai)             	software2	59.19
25. UALING (Tucson)                         	software1	57.06
26. METU (Ankara)                           	software2	56.33
27. UT (Tartu)                              	software1	56.27
28. ParisNLP (Paris)                        	software1	44.63
29. OpenU NLP Lab (Ra'anana)                	software6	30.97
30. TRL (Tokyo)                             	software1	28.57
31. MetaRomance (Santiago de Compostela)    	software1	24.00
32. ECNU (Shanghai)                         	software1	 2.50
33. Wenba-NLU (Wuhan)                       	software1	 0.38
</pre>



### nl_lassysmall

<pre>
 1. Stanford (Stanford)                     	software1	85.22
 2. HIT-SCIR (Harbin)                       	software4	83.92
 3. IMS (Stuttgart)                         	software2	83.76
 4. NAIST SATO (Nara)                       	software1	81.69
 5. C2L2 (Ithaca)                           	software5	78.92
 6. Orange – Deskiñ (Lannion)               	software1	78.63
 7. LyS-FASTPARSE (A Coruña)                	software5	78.46
 8. fbaml (Palo Alto)                       	software1	78.43
 9. Koç University (İstanbul)               	software3	77.76
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.09
11. darc (Tübingen)                         	software1	75.47
12. TurkuNLP (Turku)                        	software1	74.93
13. naistCL (Nara)                          	software1	74.90
14. UParse (Edinburgh)                      	software1	74.27
15. Wanghao-ftd-SJTU (Shanghai)             	software2	74.14
16. LIMSI-LIPN (Paris)                      	software2	73.79
    BASELINE UDPipe 1.1 (Praha)             	software2	73.79
18. RACAI (București)                       	software1	73.60
19. Uppsala (Uppsala)                       	software1	72.83
20. LATTICE (Paris)                         	software7	70.61
21. IIT Kharagpur (Kharagpur)               	software3	70.00
22. CLCL (Genève)                           	software1	67.91
23. UALING (Tucson)                         	software1	66.91
24. METU (Ankara)                           	software2	65.55
25. MQuni (Sydney)                          	software2	65.53
26. Mengest (Shanghai)                      	software1	65.52
27. OpenU NLP Lab (Ra'anana)                	software6	63.40
28. ParisNLP (Paris)                        	software1	53.41
29. UT (Tartu)                              	software1	47.38
30. MetaRomance (Santiago de Compostela)    	software1	33.71
31. TRL (Tokyo)                             	software1	25.25
32. ECNU (Shanghai)                         	software1	 3.42
33. Wenba-NLU (Wuhan)                       	software1	 1.94
</pre>



### no_bokmaal

<pre>
 1. Stanford (Stanford)                     	software1	87.67
 2. C2L2 (Ithaca)                           	software5	85.02
 3. HIT-SCIR (Harbin)                       	software4	83.95
 4. IMS (Stuttgart)                         	software2	83.04
 5. NAIST SATO (Nara)                       	software1	82.98
 6. LATTICE (Paris)                         	software7	82.49
 7. MQuni (Sydney)                          	software2	81.20
 8. LyS-FASTPARSE (A Coruña)                	software5	81.01
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.46
10. Orange – Deskiñ (Lannion)               	software1	80.24
11. TurkuNLP (Turku)                        	software1	80.14
12. UParse (Edinburgh)                      	software1	80.09
13. Koç University (İstanbul)               	software3	79.97
14. Uppsala (Uppsala)                       	software1	79.67
15. LIMSI-LIPN (Paris)                      	software2	79.62
    BASELINE UDPipe 1.1 (Praha)             	software2	79.62
17. IIT Kharagpur (Kharagpur)               	software3	78.81
18. CLCL (Genève)                           	software1	78.72
19. fbaml (Palo Alto)                       	software1	78.69
20. darc (Tübingen)                         	software1	78.64
21. naistCL (Nara)                          	software1	78.60
22. Wanghao-ftd-SJTU (Shanghai)             	software2	77.11
23. UALING (Tucson)                         	software1	76.03
24. RACAI (București)                       	software1	75.60
25. METU (Ankara)                           	software2	73.62
26. OpenU NLP Lab (Ra'anana)                	software6	71.52
27. Mengest (Shanghai)                      	software1	71.29
28. ParisNLP (Paris)                        	software1	62.54
29. TRL (Tokyo)                             	software1	41.72
30. MetaRomance (Santiago de Compostela)    	software1	35.98
31. Wenba-NLU (Wuhan)                       	software1	 1.33
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### no_nynorsk

<pre>
 1. Stanford (Stanford)                     	software1	86.41
 2. C2L2 (Ithaca)                           	software5	83.83
 3. HIT-SCIR (Harbin)                       	software4	82.24
 4. IMS (Stuttgart)                         	software2	81.89
 5. LATTICE (Paris)                         	software7	80.89
 6. NAIST SATO (Nara)                       	software1	80.78
 7. LyS-FASTPARSE (A Coruña)                	software5	79.23
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.07
 9. Koç University (İstanbul)               	software3	78.85
10. TurkuNLP (Turku)                        	software1	78.37
11. MQuni (Sydney)                          	software2	78.19
12. UParse (Edinburgh)                      	software1	77.57
13. LIMSI-LIPN (Paris)                      	software2	77.49
    BASELINE UDPipe 1.1 (Praha)             	software2	77.49
15. Orange – Deskiñ (Lannion)               	software1	77.39
16. Uppsala (Uppsala)                       	software1	77.17
17. darc (Tübingen)                         	software1	76.91
18. IIT Kharagpur (Kharagpur)               	software3	76.86
19. naistCL (Nara)                          	software1	76.56
20. Wanghao-ftd-SJTU (Shanghai)             	software2	75.42
21. CLCL (Genève)                           	software1	74.92
22. UALING (Tucson)                         	software1	74.22
23. RACAI (București)                       	software1	72.77
24. METU (Ankara)                           	software2	70.72
25. OpenU NLP Lab (Ra'anana)                	software6	65.78
26. Mengest (Shanghai)                      	software1	65.66
27. ParisNLP (Paris)                        	software1	58.62
28. TRL (Tokyo)                             	software1	39.62
29. MetaRomance (Santiago de Compostela)    	software1	31.88
30. fbaml (Palo Alto)                       	software1	 4.67
31. Wenba-NLU (Wuhan)                       	software1	 1.02
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pl

<pre>
 1. Stanford (Stanford)                     	software1	87.94
 2. C2L2 (Ithaca)                           	software5	83.86
 3. IMS (Stuttgart)                         	software2	83.58
 4. LATTICE (Paris)                         	software7	82.86
 5. HIT-SCIR (Harbin)                       	software4	80.47
 6. LyS-FASTPARSE (A Coruña)                	software5	77.85
 7. MQuni (Sydney)                          	software2	77.79
 8. Orange – Deskiñ (Lannion)               	software1	77.76
 9. Koç University (İstanbul)               	software3	76.95
10. NAIST SATO (Nara)                       	software1	76.44
11. TurkuNLP (Turku)                        	software1	75.85
12. LIMSI-LIPN (Paris)                      	software2	75.79
13. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.73
14. CLCL (Genève)                           	software1	75.65
15. darc (Tübingen)                         	software1	75.19
16. fbaml (Palo Alto)                       	software1	74.92
17. IIT Kharagpur (Kharagpur)               	software3	74.77
18. naistCL (Nara)                          	software1	74.49
19. UParse (Edinburgh)                      	software1	74.32
    BASELINE UDPipe 1.1 (Praha)             	software2	74.32
21. Wanghao-ftd-SJTU (Shanghai)             	software2	73.76
22. UALING (Tucson)                         	software1	73.64
23. RACAI (București)                       	software1	73.53
24. Uppsala (Uppsala)                       	software1	72.93
25. METU (Ankara)                           	software2	71.47
26. ParisNLP (Paris)                        	software1	66.74
27. Mengest (Shanghai)                      	software1	63.41
28. OpenU NLP Lab (Ra'anana)                	software6	56.40
29. TRL (Tokyo)                             	software1	52.14
30. MetaRomance (Santiago de Compostela)    	software1	34.25
31. Wenba-NLU (Wuhan)                       	software1	10.55
32. ECNU (Shanghai)                         	software1	 2.70
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt

<pre>
 1. Stanford (Stanford)                     	software1	83.27
 2. C2L2 (Ithaca)                           	software5	79.88
 3. IMS (Stuttgart)                         	software2	79.85
 4. HIT-SCIR (Harbin)                       	software4	79.67
 5. LATTICE (Paris)                         	software7	78.87
 6. NAIST SATO (Nara)                       	software1	78.74
 7. MQuni (Sydney)                          	software2	77.50
 8. Koç University (İstanbul)               	software3	76.96
 9. TurkuNLP (Turku)                        	software1	76.89
10. UParse (Edinburgh)                      	software1	76.49
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.34
12. fbaml (Palo Alto)                       	software1	75.94
13. LIMSI-LIPN (Paris)                      	software2	75.70
14. BASELINE UDPipe 1.1 (Praha)             	software2	75.63
15. RACAI (București)                       	software1	75.28
16. naistCL (Nara)                          	software1	75.07
17. darc (Tübingen)                         	software1	74.65
18. Uppsala (Uppsala)                       	software1	73.85
19. LyS-FASTPARSE (A Coruña)                	software5	73.58
20. IIT Kharagpur (Kharagpur)               	software3	73.51
21. Wanghao-ftd-SJTU (Shanghai)             	software2	73.23
22. CLCL (Genève)                           	software1	72.91
23. ParisNLP (Paris)                        	software1	72.77
24. Orange – Deskiñ (Lannion)               	software1	70.79
25. METU (Ankara)                           	software2	68.06
26. MetaRomance (Santiago de Compostela)    	software1	55.27
27. Mengest (Shanghai)                      	software1	53.68
28. OpenU NLP Lab (Ra'anana)                	software6	39.46
29. TRL (Tokyo)                             	software1	34.79
30. UALING (Tucson)                         	software1	24.16
31. Wenba-NLU (Wuhan)                       	software1	 1.18
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_br

<pre>
 1. Stanford (Stanford)                     	software1	87.48
 2. C2L2 (Ithaca)                           	software5	84.44
 3. HIT-SCIR (Harbin)                       	software4	83.98
 4. LATTICE (Paris)                         	software7	83.76
 5. MQuni (Sydney)                          	software2	82.61
 6. NAIST SATO (Nara)                       	software1	82.45
 7. Orange – Deskiñ (Lannion)               	software1	81.59
 8. IMS (Stuttgart)                         	software2	81.56
 9. Koç University (İstanbul)               	software3	81.21
10. LyS-FASTPARSE (A Coruña)                	software5	80.91
11. UParse (Edinburgh)                      	software1	80.38
12. Uppsala (Uppsala)                       	software1	80.34
13. TurkuNLP (Turku)                        	software1	80.31
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.98
15. naistCL (Nara)                          	software1	79.72
16. fbaml (Palo Alto)                       	software1	79.33
17. LIMSI-LIPN (Paris)                      	software2	78.91
    BASELINE UDPipe 1.1 (Praha)             	software2	78.91
19. darc (Tübingen)                         	software1	78.42
20. IIT Kharagpur (Kharagpur)               	software3	77.49
21. CLCL (Genève)                           	software1	77.37
22. RACAI (București)                       	software1	76.32
23. Wanghao-ftd-SJTU (Shanghai)             	software2	76.11
24. METU (Ankara)                           	software2	76.00
25. UALING (Tucson)                         	software1	74.68
26. Mengest (Shanghai)                      	software1	72.83
27. OpenU NLP Lab (Ra'anana)                	software6	72.49
28. ParisNLP (Paris)                        	software1	46.83
29. MetaRomance (Santiago de Compostela)    	software1	41.27
30. TRL (Tokyo)                             	software1	37.91
31. Wenba-NLU (Wuhan)                       	software1	 0.05
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_pud

<pre>
 1. C2L2 (Ithaca)                           	software5	72.80
 2. Stanford (Stanford)                     	software1	71.68
 3. NAIST SATO (Nara)                       	software1	70.46
 4. LATTICE (Paris)                         	software7	70.37
 5. Koç University (İstanbul)               	software3	68.55
 6. MQuni (Sydney)                          	software2	68.21
 7. UParse (Edinburgh)                      	software1	68.07
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	68.01
 9. ParisNLP (Paris)                        	software1	67.88
10. naistCL (Nara)                          	software1	67.40
11. TurkuNLP (Turku)                        	software1	67.34
12. BASELINE UDPipe 1.1 (Praha)             	software2	67.12
13. darc (Tübingen)                         	software1	66.76
14. IMS (Stuttgart)                         	software2	66.62
15. fbaml (Palo Alto)                       	software1	66.15
16. RACAI (București)                       	software1	66.04
17. IIT Kharagpur (Kharagpur)               	software3	65.98
18. CLCL (Genève)                           	software1	65.91
19. Uppsala (Uppsala)                       	software1	65.20
20. Wanghao-ftd-SJTU (Shanghai)             	software2	64.89
21. HIT-SCIR (Harbin)                       	software4	63.78
22. Orange – Deskiñ (Lannion)               	software1	61.85
23. METU (Ankara)                           	software2	60.12
24. MetaRomance (Santiago de Compostela)    	software1	56.30
25. Mengest (Shanghai)                      	software1	49.71
26. LIMSI-LIPN (Paris)                      	software2	47.37
27. LyS-FASTPARSE (A Coruña)                	software5	40.79
28. OpenU NLP Lab (Ra'anana)                	software6	40.60
29. TRL (Tokyo)                             	software1	38.26
30. UALING (Tucson)                         	software1	24.35
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ro

<pre>
 1. Stanford (Stanford)                     	software1	81.87
 2. C2L2 (Ithaca)                           	software5	79.53
 3. IMS (Stuttgart)                         	software2	79.02
 4. HIT-SCIR (Harbin)                       	software4	77.05
 5. LATTICE (Paris)                         	software7	76.66
 6. Orange – Deskiñ (Lannion)               	software1	76.31
 7. Koç University (İstanbul)               	software3	76.29
 8. NAIST SATO (Nara)                       	software1	76.18
 9. fbaml (Palo Alto)                       	software1	75.74
10. TurkuNLP (Turku)                        	software1	75.29
11. darc (Tübingen)                         	software1	75.02
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	74.90
13. MQuni (Sydney)                          	software2	74.89
14. LyS-FASTPARSE (A Coruña)                	software5	74.48
15. LIMSI-LIPN (Paris)                      	software2	74.37
16. UParse (Edinburgh)                      	software1	74.31
17. BASELINE UDPipe 1.1 (Praha)             	software2	74.01
18. RACAI (București)                       	software1	73.74
19. naistCL (Nara)                          	software1	73.51
20. Uppsala (Uppsala)                       	software1	73.42
21. IIT Kharagpur (Kharagpur)               	software3	72.61
22. Wanghao-ftd-SJTU (Shanghai)             	software2	72.06
23. CLCL (Genève)                           	software1	71.15
24. UALING (Tucson)                         	software1	70.52
25. METU (Ankara)                           	software2	70.46
26. ParisNLP (Paris)                        	software1	70.22
27. UT (Tartu)                              	software1	69.92
28. OpenU NLP Lab (Ra'anana)                	software6	64.25
29. Mengest (Shanghai)                      	software1	57.85
30. TRL (Tokyo)                             	software1	45.14
31. MetaRomance (Santiago de Compostela)    	software1	36.73
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### ru

<pre>
 1. Stanford (Stanford)                     	software1	81.80
 2. C2L2 (Ithaca)                           	software5	81.64
 3. IMS (Stuttgart)                         	software2	79.24
 4. HIT-SCIR (Harbin)                       	software4	78.80
 5. LATTICE (Paris)                         	software7	76.28
 6. NAIST SATO (Nara)                       	software1	76.10
 7. Koç University (İstanbul)               	software3	74.68
 8. Orange – Deskiñ (Lannion)               	software1	74.65
 9. MQuni (Sydney)                          	software2	74.05
10. LyS-FASTPARSE (A Coruña)                	software5	74.03
11. fbaml (Palo Alto)                       	software1	74.01
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	73.22
13. LIMSI-LIPN (Paris)                      	software2	73.21
14. RACAI (București)                       	software1	72.93
15. naistCL (Nara)                          	software1	72.20
16. darc (Tübingen)                         	software1	72.18
17. TurkuNLP (Turku)                        	software1	72.12
18. IIT Kharagpur (Kharagpur)               	software3	71.78
19. UParse (Edinburgh)                      	software1	71.13
    BASELINE UDPipe 1.1 (Praha)             	software2	71.13
21. UALING (Tucson)                         	software1	70.86
22. CLCL (Genève)                           	software1	69.21
23. METU (Ankara)                           	software2	68.67
24. Uppsala (Uppsala)                       	software1	68.40
25. ParisNLP (Paris)                        	software1	63.60
26. Mengest (Shanghai)                      	software1	54.58
27. OpenU NLP Lab (Ra'anana)                	software6	51.43
28. TRL (Tokyo)                             	software1	48.12
29. Wanghao-ftd-SJTU (Shanghai)             	software2	45.89
30. MetaRomance (Santiago de Compostela)    	software1	42.20
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ru_pud

<pre>
 1. Stanford (Stanford)                     	software1	73.13
 2. IMS (Stuttgart)                         	software2	70.88
 3. C2L2 (Ithaca)                           	software5	70.08
 4. HIT-SCIR (Harbin)                       	software4	69.93
 5. NAIST SATO (Nara)                       	software1	69.50
 6. LATTICE (Paris)                         	software7	68.92
 7. Koç University (İstanbul)               	software3	68.07
 8. Orange – Deskiñ (Lannion)               	software1	66.94
 9. fbaml (Palo Alto)                       	software1	65.82
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	65.72
11. TurkuNLP (Turku)                        	software1	65.71
12. RACAI (București)                       	software1	65.27
13. MQuni (Sydney)                          	software2	65.25
14. darc (Tübingen)                         	software1	65.19
15. UParse (Edinburgh)                      	software1	64.76
16. naistCL (Nara)                          	software1	64.53
17. BASELINE UDPipe 1.1 (Praha)             	software2	64.40
18. UALING (Tucson)                         	software1	63.81
19. CLCL (Genève)                           	software1	63.39
20. METU (Ankara)                           	software2	62.12
21. ParisNLP (Paris)                        	software1	61.70
22. IIT Kharagpur (Kharagpur)               	software3	61.51
23. Uppsala (Uppsala)                       	software1	60.95
24. LIMSI-LIPN (Paris)                      	software2	57.10
25. TRL (Tokyo)                             	software1	52.34
26. Mengest (Shanghai)                      	software1	49.72
27. LyS-FASTPARSE (A Coruña)                	software5	47.48
28. OpenU NLP Lab (Ra'anana)                	software6	45.97
29. MetaRomance (Santiago de Compostela)    	software1	42.01
30. UT (Tartu)                              	software1	37.99
31. Wanghao-ftd-SJTU (Shanghai)             	software2	37.85
32. ECNU (Shanghai)                         	software1	15.31
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### ru_syntagrus

<pre>
 1. Stanford (Stanford)                     	software1	90.11
 2. C2L2 (Ithaca)                           	software5	86.66
 3. IMS (Stuttgart)                         	software2	86.38
 4. HIT-SCIR (Harbin)                       	software4	86.30
 5. NAIST SATO (Nara)                       	software1	85.61
 6. UParse (Edinburgh)                      	software1	85.57
 7. Uppsala (Uppsala)                       	software1	84.04
 8. LATTICE (Paris)                         	software7	83.96
 9. LyS-FASTPARSE (A Coruña)                	software5	83.24
10. Orange – Deskiñ (Lannion)               	software1	82.69
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	82.42
12. TurkuNLP (Turku)                        	software1	82.40
13. LIMSI-LIPN (Paris)                      	software2	82.37
    BASELINE UDPipe 1.1 (Praha)             	software2	82.37
15. fbaml (Palo Alto)                       	software1	82.24
16. darc (Tübingen)                         	software1	82.00
17. MQuni (Sydney)                          	software2	81.90
18. RACAI (București)                       	software1	80.67
19. naistCL (Nara)                          	software1	80.65
20. Koç University (İstanbul)               	software3	80.22
21. IIT Kharagpur (Kharagpur)               	software3	80.07
22. Wanghao-ftd-SJTU (Shanghai)             	software2	79.26
23. CLCL (Genève)                           	software1	78.72
24. Mengest (Shanghai)                      	software1	76.57
25. METU (Ankara)                           	software2	74.49
26. OpenU NLP Lab (Ra'anana)                	software6	66.20
27. ParisNLP (Paris)                        	software1	60.00
28. TRL (Tokyo)                             	software1	51.41
29. UALING (Tucson)                         	software1	39.99
30. MetaRomance (Santiago de Compostela)    	software1	35.59
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sk

<pre>
 1. Stanford (Stanford)                     	software1	83.86
 2. C2L2 (Ithaca)                           	software5	78.23
 3. IMS (Stuttgart)                         	software2	77.18
 4. HIT-SCIR (Harbin)                       	software4	76.27
 5. LATTICE (Paris)                         	software7	76.16
 6. LyS-FASTPARSE (A Coruña)                	software5	72.51
 7. Koç University (İstanbul)               	software3	72.46
 8. Orange – Deskiñ (Lannion)               	software1	72.15
 9. fbaml (Palo Alto)                       	software1	72.12
10. NAIST SATO (Nara)                       	software1	71.65
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	71.64
12. TurkuNLP (Turku)                        	software1	71.20
13. LIMSI-LIPN (Paris)                      	software2	70.47
14. RACAI (București)                       	software1	69.88
15. CLCL (Genève)                           	software1	69.66
16. darc (Tübingen)                         	software1	69.49
17. IIT Kharagpur (Kharagpur)               	software3	69.19
18. MQuni (Sydney)                          	software2	69.11
19. UALING (Tucson)                         	software1	69.00
20. UParse (Edinburgh)                      	software1	68.97
    BASELINE UDPipe 1.1 (Praha)             	software2	68.97
22. Wanghao-ftd-SJTU (Shanghai)             	software2	68.45
23. naistCL (Nara)                          	software1	67.43
24. METU (Ankara)                           	software2	66.86
25. Uppsala (Uppsala)                       	software1	64.94
26. ParisNLP (Paris)                        	software1	62.26
27. Mengest (Shanghai)                      	software1	56.65
28. OpenU NLP Lab (Ra'anana)                	software6	43.10
29. MetaRomance (Santiago de Compostela)    	software1	35.72
30. TRL (Tokyo)                             	software1	30.93
31. ECNU (Shanghai)                         	software1	 1.53
32. Wenba-NLU (Wuhan)                       	software1	 1.27
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl

<pre>
 1. Stanford (Stanford)                     	software1	88.98
 2. C2L2 (Ithaca)                           	software5	84.74
 3. HIT-SCIR (Harbin)                       	software4	83.91
 4. IMS (Stuttgart)                         	software2	82.18
 5. LATTICE (Paris)                         	software7	80.84
 6. NAIST SATO (Nara)                       	software1	80.17
 7. Orange – Deskiñ (Lannion)               	software1	79.64
 8. LyS-FASTPARSE (A Coruña)                	software5	78.42
    TurkuNLP (Turku)                        	software1	78.42
10. fbaml (Palo Alto)                       	software1	78.19
11. Koç University (İstanbul)               	software3	77.95
12. ÚFAL – UDPipe 1.2 (Praha)               	software1	77.60
13. CLCL (Genève)                           	software1	77.44
14. LIMSI-LIPN (Paris)                      	software2	77.05
15. UParse (Edinburgh)                      	software1	76.74
    BASELINE UDPipe 1.1 (Praha)             	software2	76.74
17. darc (Tübingen)                         	software1	76.58
18. MQuni (Sydney)                          	software2	76.33
19. Wanghao-ftd-SJTU (Shanghai)             	software2	76.14
20. IIT Kharagpur (Kharagpur)               	software3	75.89
21. Uppsala (Uppsala)                       	software1	75.72
22. naistCL (Nara)                          	software1	75.63
23. ParisNLP (Paris)                        	software1	75.25
24. RACAI (București)                       	software1	74.73
25. UALING (Tucson)                         	software1	74.41
26. METU (Ankara)                           	software2	73.20
27. OpenU NLP Lab (Ra'anana)                	software6	58.69
28. Mengest (Shanghai)                      	software1	58.26
29. TRL (Tokyo)                             	software1	38.73
30. MetaRomance (Santiago de Compostela)    	software1	37.22
31. ECNU (Shanghai)                         	software1	 0.75
32. Wenba-NLU (Wuhan)                       	software1	 0.05
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl_sst

<pre>
 1. C2L2 (Ithaca)                           	software5	54.30
 2. IMS (Stuttgart)                         	software2	51.33
 3. Stanford (Stanford)                     	software1	51.04
 4. HIT-SCIR (Harbin)                       	software4	49.20
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	49.15
 6. NAIST SATO (Nara)                       	software1	45.04
 7. LATTICE (Paris)                         	software7	44.99
 8. fbaml (Palo Alto)                       	software1	44.31
 9. Koç University (İstanbul)               	software3	44.03
10. RACAI (București)                       	software1	42.98
11. TurkuNLP (Turku)                        	software1	42.41
12. darc (Tübingen)                         	software1	42.00
13. UParse (Edinburgh)                      	software1	41.94
14. LIMSI-LIPN (Paris)                      	software2	41.56
15. Wanghao-ftd-SJTU (Shanghai)             	software2	41.35
16. BASELINE UDPipe 1.1 (Praha)             	software2	41.03
17. UALING (Tucson)                         	software1	40.88
18. IIT Kharagpur (Kharagpur)               	software3	40.51
19. naistCL (Nara)                          	software1	38.58
20. MQuni (Sydney)                          	software2	38.35
21. LyS-FASTPARSE (A Coruña)                	software5	38.19
22. Orange – Deskiñ (Lannion)               	software1	34.44
23. ParisNLP (Paris)                        	software1	33.86
24. Uppsala (Uppsala)                       	software1	32.13
25. OpenU NLP Lab (Ra'anana)                	software6	32.10
26. METU (Ankara)                           	software2	31.39
27. TRL (Tokyo)                             	software1	23.70
28. Mengest (Shanghai)                      	software1	20.06
29. MetaRomance (Santiago de Compostela)    	software1	16.81
30. CLCL (Genève)                           	software1	 5.14
31. ECNU (Shanghai)                         	software1	 1.94
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sme

<pre>
 1. C2L2 (Ithaca)                           	software5	48.42
 2. IMS (Stuttgart)                         	software2	40.58
 3. Stanford (Stanford)                     	software1	39.22
 4. ParisNLP (Paris)                        	software1	38.94
 5. RACAI (București)                       	software1	37.96
 6. HIT-SCIR (Harbin)                       	software4	37.95
 7. darc (Tübingen)                         	software1	37.93
 8. UParse (Edinburgh)                      	software1	37.89
 9. IIT Kharagpur (Kharagpur)               	software3	36.91
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	34.85
11. Wanghao-ftd-SJTU (Shanghai)             	software2	34.45
12. Orange – Deskiñ (Lannion)               	software1	34.01
13. Koç University (İstanbul)               	software3	33.38
14. UALING (Tucson)                         	software1	33.24
15. LyS-FASTPARSE (A Coruña)                	software5	33.13
16. BASELINE UDPipe 1.1 (Praha)             	software2	32.74
17. LIMSI-LIPN (Paris)                      	software2	32.06
18. OpenU NLP Lab (Ra'anana)                	software6	27.45
19. LATTICE (Paris)                         	software7	27.30
20. naistCL (Nara)                          	software1	27.10
21. CLCL (Genève)                           	software2	25.42
22. METU (Ankara)                           	software2	24.94
23. NAIST SATO (Nara)                       	software1	23.88
24. MetaRomance (Santiago de Compostela)    	software1	22.47
25. fbaml (Palo Alto)                       	software1	14.41
26. TurkuNLP (Turku)                        	software1	12.83
27. Uppsala (Uppsala)                       	software1	11.33
28. Mengest (Shanghai)                      	software1	 9.73
29. TRL (Tokyo)                             	software1	 7.85
30. MQuni (Sydney)                          	software2	 7.74
31. ECNU (Shanghai)                         	software1	 1.88
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv

<pre>
 1. Stanford (Stanford)                     	software1	83.71
 2. C2L2 (Ithaca)                           	software5	82.52
 3. IMS (Stuttgart)                         	software2	79.40
 4. LATTICE (Paris)                         	software7	78.14
 5. HIT-SCIR (Harbin)                       	software4	77.49
 6. NAIST SATO (Nara)                       	software1	76.84
 7. Orange – Deskiñ (Lannion)               	software1	75.79
 8. Koç University (İstanbul)               	software3	75.10
 9. MQuni (Sydney)                          	software2	74.50
10. fbaml (Palo Alto)                       	software1	74.03
11. ÚFAL – UDPipe 1.2 (Praha)               	software1	73.99
12. TurkuNLP (Turku)                        	software1	73.71
13. LyS-FASTPARSE (A Coruña)                	software5	73.62
14. IIT Kharagpur (Kharagpur)               	software3	73.36
15. ParisNLP (Paris)                        	software1	73.16
16. LIMSI-LIPN (Paris)                      	software2	72.86
    BASELINE UDPipe 1.1 (Praha)             	software2	72.86
18. darc (Tübingen)                         	software1	72.82
19. CLCL (Genève)                           	software1	72.47
20. naistCL (Nara)                          	software1	72.31
21. Wanghao-ftd-SJTU (Shanghai)             	software2	71.70
22. UALING (Tucson)                         	software1	71.29
23. UParse (Edinburgh)                      	software1	71.00
24. METU (Ankara)                           	software2	70.37
25. Uppsala (Uppsala)                       	software1	69.74
26. RACAI (București)                       	software1	68.86
27. OpenU NLP Lab (Ra'anana)                	software6	65.49
28. Mengest (Shanghai)                      	software1	57.32
29. TRL (Tokyo)                             	software1	38.79
30. MetaRomance (Santiago de Compostela)    	software1	33.59
31. Wenba-NLU (Wuhan)                       	software1	 1.03
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_lines

<pre>
 1. Stanford (Stanford)                     	software1	79.92
 2. C2L2 (Ithaca)                           	software5	79.48
 3. IMS (Stuttgart)                         	software2	75.32
 4. LATTICE (Paris)                         	software7	74.98
 5. HIT-SCIR (Harbin)                       	software4	73.25
 6. NAIST SATO (Nara)                       	software1	72.91
 7. Koç University (İstanbul)               	software3	71.96
 8. Orange – Deskiñ (Lannion)               	software1	71.73
 9. ÚFAL – UDPipe 1.2 (Praha)               	software1	71.70
10. MQuni (Sydney)                          	software2	71.27
11. LyS-FASTPARSE (A Coruña)                	software5	70.83
12. fbaml (Palo Alto)                       	software1	70.70
13. IIT Kharagpur (Kharagpur)               	software3	70.62
14. TurkuNLP (Turku)                        	software1	70.21
15. UParse (Edinburgh)                      	software1	70.01
16. LIMSI-LIPN (Paris)                      	software2	69.98
    BASELINE UDPipe 1.1 (Praha)             	software2	69.98
18. CLCL (Genève)                           	software1	69.70
19. darc (Tübingen)                         	software1	69.34
20. naistCL (Nara)                          	software1	69.24
21. Wanghao-ftd-SJTU (Shanghai)             	software2	69.04
22. UALING (Tucson)                         	software1	68.01
23. METU (Ankara)                           	software2	67.45
24. RACAI (București)                       	software1	66.23
25. Uppsala (Uppsala)                       	software1	64.54
26. OpenU NLP Lab (Ra'anana)                	software6	63.67
27. ParisNLP (Paris)                        	software1	57.69
28. Mengest (Shanghai)                      	software1	56.76
29. TRL (Tokyo)                             	software1	41.23
30. MetaRomance (Santiago de Compostela)    	software1	25.23
31. ECNU (Shanghai)                         	software1	 2.01
32. Wenba-NLU (Wuhan)                       	software1	 0.35
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_pud

<pre>
 1. Stanford (Stanford)                     	software1	76.48
 2. C2L2 (Ithaca)                           	software5	75.24
 3. IMS (Stuttgart)                         	software2	72.96
 4. LATTICE (Paris)                         	software7	69.45
 5. NAIST SATO (Nara)                       	software1	69.15
 6. Koç University (İstanbul)               	software3	68.67
 7. ParisNLP (Paris)                        	software1	67.41
 8. Orange – Deskiñ (Lannion)               	software1	66.85
 9. HIT-SCIR (Harbin)                       	software4	66.59
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	66.38
11. IIT Kharagpur (Kharagpur)               	software3	66.36
    fbaml (Palo Alto)                       	software1	66.36
13. MQuni (Sydney)                          	software2	66.26
14. BASELINE UDPipe 1.1 (Praha)             	software2	65.99
15. UParse (Edinburgh)                      	software1	65.96
16. TurkuNLP (Turku)                        	software1	65.47
17. LyS-FASTPARSE (A Coruña)                	software5	65.09
18. UALING (Tucson)                         	software1	64.77
19. naistCL (Nara)                          	software1	64.61
20. darc (Tübingen)                         	software1	64.49
21. Wanghao-ftd-SJTU (Shanghai)             	software2	64.31
22. CLCL (Genève)                           	software1	64.29
23. RACAI (București)                       	software1	63.07
24. METU (Ankara)                           	software2	62.66
25. Uppsala (Uppsala)                       	software1	57.46
26. OpenU NLP Lab (Ra'anana)                	software6	55.04
27. Mengest (Shanghai)                      	software1	50.08
28. LIMSI-LIPN (Paris)                      	software2	47.84
29. TRL (Tokyo)                             	software1	35.82
30. MetaRomance (Santiago de Compostela)    	software1	35.53
31. ECNU (Shanghai)                         	software1	 2.06
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr

<pre>
 1. Stanford (Stanford)                     	software1	60.01
 2. C2L2 (Ithaca)                           	software5	59.63
 3. IMS (Stuttgart)                         	software2	59.06
 4. LATTICE (Paris)                         	software7	55.49
 5. LyS-FASTPARSE (A Coruña)                	software5	53.52
 6. Koç University (İstanbul)               	software3	53.40
 7. HIT-SCIR (Harbin)                       	software4	52.52
 8. RACAI (București)                       	software1	51.93
 9. MQuni (Sydney)                          	software2	51.86
10. LIMSI-LIPN (Paris)                      	software2	51.73
11. Orange – Deskiñ (Lannion)               	software1	51.56
12. TurkuNLP (Turku)                        	software1	51.50
13. darc (Tübingen)                         	software1	51.38
14. IIT Kharagpur (Kharagpur)               	software3	51.02
15. ÚFAL – UDPipe 1.2 (Praha)               	software1	50.72
16. UParse (Edinburgh)                      	software1	49.98
17. BASELINE UDPipe 1.1 (Praha)             	software2	49.95
18. naistCL (Nara)                          	software1	49.17
19. fbaml (Palo Alto)                       	software1	48.71
20. Wanghao-ftd-SJTU (Shanghai)             	software2	47.33
21. UALING (Tucson)                         	software1	46.84
22. NAIST SATO (Nara)                       	software1	46.02
23. Uppsala (Uppsala)                       	software1	44.08
24. METU (Ankara)                           	software2	44.02
25. Mengest (Shanghai)                      	software1	43.44
26. CLCL (Genève)                           	software1	42.86
27. ParisNLP (Paris)                        	software1	42.37
28. OpenU NLP Lab (Ra'anana)                	software6	33.62
29. TRL (Tokyo)                             	software1	25.71
30. Wenba-NLU (Wuhan)                       	software1	 0.81
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr_pud

<pre>
 1. IMS (Stuttgart)                         	software2	32.32
 2. Stanford (Stanford)                     	software1	31.71
 3. C2L2 (Ithaca)                           	software5	31.60
 4. LATTICE (Paris)                         	software7	28.89
 5. LyS-FASTPARSE (A Coruña)                	software5	28.69
 6. Koç University (İstanbul)               	software3	28.56
 7. BASELINE UDPipe 1.1 (Praha)             	software2	28.51
 8. darc (Tübingen)                         	software1	28.45
 9. naistCL (Nara)                          	software1	28.09
10. ÚFAL – UDPipe 1.2 (Praha)               	software1	28.04
11. LIMSI-LIPN (Paris)                      	software2	27.97
12. TurkuNLP (Turku)                        	software1	27.84
13. HIT-SCIR (Harbin)                       	software4	27.66
14. UALING (Tucson)                         	software1	27.32
15. RACAI (București)                       	software1	27.30
16. Orange – Deskiñ (Lannion)               	software1	27.20
17. IIT Kharagpur (Kharagpur)               	software3	27.13
18. Wanghao-ftd-SJTU (Shanghai)             	software2	27.06
19. MQuni (Sydney)                          	software2	26.61
20. UParse (Edinburgh)                      	software1	26.28
21. fbaml (Palo Alto)                       	software1	25.70
22. NAIST SATO (Nara)                       	software1	24.14
23. Uppsala (Uppsala)                       	software1	23.30
24. CLCL (Genève)                           	software1	22.23
25. METU (Ankara)                           	software2	21.98
26. ParisNLP (Paris)                        	software1	21.47
27. OpenU NLP Lab (Ra'anana)                	software6	17.61
28. TRL (Tokyo)                             	software1	14.74
29. Mengest (Shanghai)                      	software1	13.70
30. MetaRomance (Santiago de Compostela)    	software1	 8.08
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ug

<pre>
 1. IMS (Stuttgart)                         	software2	34.07
 2. C2L2 (Ithaca)                           	software5	32.64
 3. Stanford (Stanford)                     	software1	30.11
 4. RACAI (București)                       	software1	28.42
 5. MQuni (Sydney)                          	software2	26.16
 6. TurkuNLP (Turku)                        	software1	24.95
 7. fbaml (Palo Alto)                       	software1	24.03
 8. Wanghao-ftd-SJTU (Shanghai)             	software2	23.57
 9. LATTICE (Paris)                         	software7	23.15
10. UALING (Tucson)                         	software1	23.01
11. HIT-SCIR (Harbin)                       	software4	22.94
12. Orange – Deskiñ (Lannion)               	software1	22.40
13. LIMSI-LIPN (Paris)                      	software2	22.18
14. darc (Tübingen)                         	software1	22.09
15. IIT Kharagpur (Kharagpur)               	software3	22.02
16. NAIST SATO (Nara)                       	software1	21.83
17. UParse (Edinburgh)                      	software1	21.56
    BASELINE UDPipe 1.1 (Praha)             	software2	21.56
19. Koç University (İstanbul)               	software3	20.86
20. ÚFAL – UDPipe 1.2 (Praha)               	software1	20.28
21. naistCL (Nara)                          	software1	20.16
22. LyS-FASTPARSE (A Coruña)                	software5	17.15
23. Uppsala (Uppsala)                       	software1	14.48
24. TRL (Tokyo)                             	software1	14.22
25. ParisNLP (Paris)                        	software1	12.45
26. CLCL (Genève)                           	software1	12.08
27. METU (Ankara)                           	software2	10.36
28. MetaRomance (Santiago de Compostela)    	software1	 6.80
29. OpenU NLP Lab (Ra'anana)                	software6	 4.75
30. ECNU (Shanghai)                         	software1	 0.78
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. UT (Tartu)                              	software1	 0.00
33. Mengest (Shanghai)                      	software1	 0.00
</pre>



### uk

<pre>
 1. Stanford (Stanford)                     	software1	71.72
 2. C2L2 (Ithaca)                           	software5	66.74
 3. IMS (Stuttgart)                         	software2	63.92
 4. ParisNLP (Paris)                        	software1	60.38
 5. fbaml (Palo Alto)                       	software1	59.55
 6. Koç University (İstanbul)               	software3	58.64
 7. LATTICE (Paris)                         	software7	58.40
 8. HIT-SCIR (Harbin)                       	software4	57.67
 9. TurkuNLP (Turku)                        	software1	57.53
10. RACAI (București)                       	software1	57.52
11. Orange – Deskiñ (Lannion)               	software1	56.85
12. LIMSI-LIPN (Paris)                      	software2	55.73
13. Wanghao-ftd-SJTU (Shanghai)             	software2	55.41
14. darc (Tübingen)                         	software1	55.40
15. LyS-FASTPARSE (A Coruña)                	software5	55.19
16. ÚFAL – UDPipe 1.2 (Praha)               	software1	54.89
17. UALING (Tucson)                         	software1	54.70
18. UParse (Edinburgh)                      	software1	54.68
    BASELINE UDPipe 1.1 (Praha)             	software2	54.68
20. NAIST SATO (Nara)                       	software1	54.65
21. MQuni (Sydney)                          	software2	53.88
22. naistCL (Nara)                          	software1	53.16
23. Uppsala (Uppsala)                       	software1	40.27
24. IIT Kharagpur (Kharagpur)               	software3	34.19
25. MetaRomance (Santiago de Compostela)    	software1	34.07
26. OpenU NLP Lab (Ra'anana)                	software6	32.85
27. METU (Ankara)                           	software2	28.35
28. TRL (Tokyo)                             	software1	22.26
29. Mengest (Shanghai)                      	software1	15.32
30. CLCL (Genève)                           	software1	10.24
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ur

<pre>
 1. Stanford (Stanford)                     	software1	75.88
 2. C2L2 (Ithaca)                           	software5	74.33
 3. IMS (Stuttgart)                         	software2	74.23
 4. HIT-SCIR (Harbin)                       	software4	72.48
 5. MQuni (Sydney)                          	software2	71.95
 6. NAIST SATO (Nara)                       	software1	71.93
 7. LATTICE (Paris)                         	software7	71.73
 8. fbaml (Palo Alto)                       	software1	70.96
 9. LyS-FASTPARSE (A Coruña)                	software5	70.56
10. Orange – Deskiñ (Lannion)               	software1	70.11
11. Koç University (İstanbul)               	software3	69.57
12. darc (Tübingen)                         	software1	69.42
13. IIT Kharagpur (Kharagpur)               	software3	69.05
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	69.03
15. naistCL (Nara)                          	software1	68.97
16. TurkuNLP (Turku)                        	software1	68.91
17. BASELINE UDPipe 1.1 (Praha)             	software2	68.46
18. LIMSI-LIPN (Paris)                      	software2	68.33
19. CLCL (Genève)                           	software1	68.14
20. UParse (Edinburgh)                      	software1	67.48
21. METU (Ankara)                           	software2	66.71
22. Wanghao-ftd-SJTU (Shanghai)             	software2	66.68
23. UALING (Tucson)                         	software1	65.76
24. RACAI (București)                       	software1	65.52
25. OpenU NLP Lab (Ra'anana)                	software6	61.28
26. Uppsala (Uppsala)                       	software1	58.17
27. Mengest (Shanghai)                      	software1	52.51
28. TRL (Tokyo)                             	software1	34.38
29. ParisNLP (Paris)                        	software1	32.52
30. MetaRomance (Santiago de Compostela)    	software1	 8.70
31. Wenba-NLU (Wuhan)                       	software1	 0.89
32. ECNU (Shanghai)                         	software1	 0.34
33. UT (Tartu)                              	software1	 0.00
</pre>



### vi

<pre>
 1. IMS (Stuttgart)                         	software2	44.12
 2. HIT-SCIR (Harbin)                       	software4	38.64
 3. Stanford (Stanford)                     	software1	38.59
 4. LIMSI-LIPN (Paris)                      	software2	38.55
 5. C2L2 (Ithaca)                           	software5	37.71
 6. fbaml (Palo Alto)                       	software1	36.73
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	36.71
 8. LATTICE (Paris)                         	software7	36.12
 9. Orange – Deskiñ (Lannion)               	software1	35.29
10. NAIST SATO (Nara)                       	software1	35.06
11. MQuni (Sydney)                          	software2	34.58
12. LyS-FASTPARSE (A Coruña)                	software5	34.46
13. Koç University (İstanbul)               	software3	34.42
14. Uppsala (Uppsala)                       	software1	34.13
15. TurkuNLP (Turku)                        	software1	34.07
16. naistCL (Nara)                          	software1	34.00
17. darc (Tübingen)                         	software1	33.88
18. UParse (Edinburgh)                      	software1	33.75
    BASELINE UDPipe 1.1 (Praha)             	software2	33.75
20. Wanghao-ftd-SJTU (Shanghai)             	software2	33.19
21. IIT Kharagpur (Kharagpur)               	software3	32.94
22. OpenU NLP Lab (Ra'anana)                	software6	32.59
23. METU (Ankara)                           	software2	32.48
24. UALING (Tucson)                         	software1	32.21
25. CLCL (Genève)                           	software1	32.17
26. RACAI (București)                       	software1	30.01
27. ParisNLP (Paris)                        	software1	29.21
28. TRL (Tokyo)                             	software1	28.11
29. Mengest (Shanghai)                      	software1	28.00
30. MetaRomance (Santiago de Compostela)    	software1	 8.74
31. Wenba-NLU (Wuhan)                       	software1	 0.94
32. ECNU (Shanghai)                         	software1	 0.55
33. UT (Tartu)                              	software1	 0.00
</pre>



### zh

<pre>
 1. IMS (Stuttgart)                         	software2	64.23
 2. Stanford (Stanford)                     	software1	62.03
 3. HIT-SCIR (Harbin)                       	software4	60.22
 4. fbaml (Palo Alto)                       	software1	60.06
 5. C2L2 (Ithaca)                           	software5	59.60
 6. LATTICE (Paris)                         	software7	57.52
 7. NAIST SATO (Nara)                       	software1	55.46
 8. LIMSI-LIPN (Paris)                      	software2	54.96
 9. Uppsala (Uppsala)                       	software1	54.92
10. MQuni (Sydney)                          	software2	54.82
11. Orange – Deskiñ (Lannion)               	software1	54.35
12. TurkuNLP (Turku)                        	software1	54.12
13. Mengest (Shanghai)                      	software1	53.42
14. ÚFAL – UDPipe 1.2 (Praha)               	software1	53.15
15. naistCL (Nara)                          	software1	52.90
16. RACAI (București)                       	software1	52.63
17. UParse (Edinburgh)                      	software1	52.53
    BASELINE UDPipe 1.1 (Praha)             	software2	52.53
19. IIT Kharagpur (Kharagpur)               	software3	52.05
20. Koç University (İstanbul)               	software3	52.04
21. LyS-FASTPARSE (A Coruña)                	software5	51.00
22. darc (Tübingen)                         	software1	50.87
23. UALING (Tucson)                         	software1	50.79
24. Wanghao-ftd-SJTU (Shanghai)             	software2	49.91
25. CLCL (Genève)                           	software1	49.79
26. METU (Ankara)                           	software2	48.51
27. OpenU NLP Lab (Ra'anana)                	software6	47.74
28. ParisNLP (Paris)                        	software1	39.58
29. ECNU (Shanghai)                         	software1	25.50
30. TRL (Tokyo)                             	software1	22.97
31. MetaRomance (Santiago de Compostela)    	software1	11.68
32. Wenba-NLU (Wuhan)                       	software1	 0.03
33. UT (Tartu)                              	software1	 0.00
</pre>



