---
layout: page
title: CoNLL 2017 Shared Task
---

# Results: Sentence segmentation F1

## All treebanks

<pre>
 1. IMS (Stuttgart)                         	software2	89.10
 2. Uppsala (Uppsala)                       	software1	89.03
 3. HIT-SCIR (Harbin)                       	software4	88.91
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	88.68
 5. darc (Tübingen)                         	software1	88.66
 6. ParisNLP (Paris)                        	software1	88.61
 7. IIT Kharagpur (Kharagpur)               	software3	88.49
    TurkuNLP (Turku)                        	software1	88.49
    Koç University (İstanbul)               	software3	88.49
    C2L2 (Ithaca)                           	software5	88.49
11. NAIST SATO (Nara)                       	software1	88.49
    UParse (Edinburgh)                      	software1	88.49
    MQuni (Sydney)                          	software2	88.49
    BASELINE UDPipe 1.1 (Praha)             	software2	88.49
    Stanford (Stanford)                     	software1	88.49
    CLCL (Genève)                           	software2	88.49
    OpenU NLP Lab (Ra'anana)                	software6	88.49
18. Orange – Deskiñ (Lannion)               	software1	88.49
    LyS-FASTPARSE (A Coruña)                	software5	88.49
    LATTICE (Paris)                         	software7	88.49
    METU (Ankara)                           	software2	88.49
22. LIMSI-LIPN (Paris)                      	software2	88.49
    naistCL (Nara)                          	software1	88.49
    UALING (Tucson)                         	software1	88.49
25. Wanghao-ftd-SJTU (Shanghai)             	software2	88.40
26. RACAI (București)                       	software1	87.52
27. fbaml (Palo Alto)                       	software1	87.46
28. Mengest (Shanghai)                      	software1	86.70
29. MetaRomance (Santiago de Compostela)    	software1	85.03
30. TRL (Tokyo)                             	software1	79.99
31. Wenba-NLU (Wuhan)                       	software1	49.18
32. ECNU (Shanghai)                         	software1	38.28
33. UT (Tartu)                              	software1	29.22
</pre>



## Big treebanks only

Macro-average Sentences-F1 of the 55 big treebanks: ar, bg, ca, cs, cs_cac, cs_cltt, cu, da, de, el, en, en_lines, en_partut, es, es_ancora, et, eu, fa, fi, fi_ftb, fr, fr_sequoia, gl, got, grc, grc_proiel, he, hi, hr, hu, id, it, ja, ko, la_ittb, la_proiel, lv, nl, nl_lassysmall, no_bokmaal, no_nynorsk, pl, pt, pt_br, ro, ru, ru_syntagrus, sk, sl, sv, sv_lines, tr, ur, vi, zh. These are the treebanks that have development data available, hence these results should be comparable to the performance of the systems on the development data.

<pre>
 1. IMS (Stuttgart)                         	software2	88.96
 2. Uppsala (Uppsala)                       	software1	88.94
 3. HIT-SCIR (Harbin)                       	software4	88.52
 4. fbaml (Palo Alto)                       	software1	88.41
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	88.21
 6. ParisNLP (Paris)                        	software1	88.20
 7. darc (Tübingen)                         	software1	88.07
 8. UParse (Edinburgh)                      	software1	88.02
    LIMSI-LIPN (Paris)                      	software2	88.02
    MQuni (Sydney)                          	software2	88.02
    LyS-FASTPARSE (A Coruña)                	software5	88.02
    UALING (Tucson)                         	software1	88.02
    Koç University (İstanbul)               	software3	88.02
    BASELINE UDPipe 1.1 (Praha)             	software2	88.02
    Stanford (Stanford)                     	software1	88.02
    C2L2 (Ithaca)                           	software5	88.02
    OpenU NLP Lab (Ra'anana)                	software6	88.02
    Mengest (Shanghai)                      	software1	88.02
19. Orange – Deskiñ (Lannion)               	software1	88.02
    LATTICE (Paris)                         	software7	88.02
    METU (Ankara)                           	software2	88.02
22. TurkuNLP (Turku)                        	software1	88.02
    CLCL (Genève)                           	software2	88.02
24. IIT Kharagpur (Kharagpur)               	software3	88.02
    NAIST SATO (Nara)                       	software1	88.02
    naistCL (Nara)                          	software1	88.02
27. Wanghao-ftd-SJTU (Shanghai)             	software2	87.88
28. RACAI (București)                       	software1	86.34
29. MetaRomance (Santiago de Compostela)    	software1	84.59
30. TRL (Tokyo)                             	software1	76.91
31. Wenba-NLU (Wuhan)                       	software1	72.43
32. ECNU (Shanghai)                         	software1	37.74
33. UT (Tartu)                              	software1	34.30
</pre>



## PUD treebanks only

Macro-average Sentences-F1 of the 14 PUD treebanks (additional parallel test sets): ar_pud, cs_pud, de_pud, en_pud, es_pud, fi_pud, fr_pud, hi_pud, it_pud, ja_pud, pt_pud, ru_pud, sv_pud, tr_pud. These are languages for which there exists at least one big training treebank. However, these test sets have been produced separately and their domain may differ.

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.47
 2. RACAI (București)                       	software1	94.43
 3. ParisNLP (Paris)                        	software1	94.32
    NAIST SATO (Nara)                       	software1	94.32
    UParse (Edinburgh)                      	software1	94.32
    LyS-FASTPARSE (A Coruña)                	software5	94.32
    TurkuNLP (Turku)                        	software1	94.32
    LATTICE (Paris)                         	software7	94.32
    CLCL (Genève)                           	software2	94.32
    OpenU NLP Lab (Ra'anana)                	software6	94.32
11. darc (Tübingen)                         	software1	94.32
    IIT Kharagpur (Kharagpur)               	software3	94.32
    Orange – Deskiñ (Lannion)               	software1	94.32
    LIMSI-LIPN (Paris)                      	software2	94.32
    MQuni (Sydney)                          	software2	94.32
    naistCL (Nara)                          	software1	94.32
    UALING (Tucson)                         	software1	94.32
    Koç University (İstanbul)               	software3	94.32
    BASELINE UDPipe 1.1 (Praha)             	software2	94.32
    Stanford (Stanford)                     	software1	94.32
    METU (Ankara)                           	software2	94.32
    C2L2 (Ithaca)                           	software5	94.32
    MetaRomance (Santiago de Compostela)    	software1	94.32
    Mengest (Shanghai)                      	software1	94.32
25. HIT-SCIR (Harbin)                       	software4	94.22
26. IMS (Stuttgart)                         	software2	94.09
27. TRL (Tokyo)                             	software1	93.71
28. Uppsala (Uppsala)                       	software1	93.37
29. Wanghao-ftd-SJTU (Shanghai)             	software2	93.33
30. fbaml (Palo Alto)                       	software1	88.55
31. ECNU (Shanghai)                         	software1	40.41
32. UT (Tartu)                              	software1	27.27
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



## Small treebanks only

Macro-average Sentences-F1 of the 8 small treebanks: fr_partut, ga, gl_treegal, kk, la, sl_sst, ug, uk. These treebanks lack development data and some of them have very little training data (especially Uyghur and Kazakh).

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	80.32
 2. Uppsala (Uppsala)                       	software1	80.12
 3. RACAI (București)                       	software1	80.06
 4. darc (Tübingen)                         	software1	79.88
 5. HIT-SCIR (Harbin)                       	software4	79.48
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	78.87
 7. IMS (Stuttgart)                         	software2	78.52
 8. NAIST SATO (Nara)                       	software1	78.47
    UParse (Edinburgh)                      	software1	78.47
    MQuni (Sydney)                          	software2	78.47
    LyS-FASTPARSE (A Coruña)                	software5	78.47
    TurkuNLP (Turku)                        	software1	78.47
    LATTICE (Paris)                         	software7	78.47
    Stanford (Stanford)                     	software1	78.47
    METU (Ankara)                           	software2	78.47
    C2L2 (Ithaca)                           	software5	78.47
    MetaRomance (Santiago de Compostela)    	software1	78.47
    OpenU NLP Lab (Ra'anana)                	software6	78.47
19. ParisNLP (Paris)                        	software1	78.47
    IIT Kharagpur (Kharagpur)               	software3	78.47
    Orange – Deskiñ (Lannion)               	software1	78.47
    LIMSI-LIPN (Paris)                      	software2	78.47
    naistCL (Nara)                          	software1	78.47
    UALING (Tucson)                         	software1	78.47
    Koç University (İstanbul)               	software3	78.47
    BASELINE UDPipe 1.1 (Praha)             	software2	78.47
    CLCL (Genève)                           	software2	78.47
28. fbaml (Palo Alto)                       	software1	78.40
29. TRL (Tokyo)                             	software1	72.13
30. Mengest (Shanghai)                      	software1	60.36
31. ECNU (Shanghai)                         	software1	22.30
32. UT (Tartu)                              	software1	12.26
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



## Surprise languages only

Macro-average Sentences-F1 of the 4 surprise language treebanks: bxr, hsb, kmr, sme.

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	94.58
    ParisNLP (Paris)                        	software1	94.58
    darc (Tübingen)                         	software1	94.58
    IIT Kharagpur (Kharagpur)               	software3	94.58
    NAIST SATO (Nara)                       	software1	94.58
    Orange – Deskiñ (Lannion)               	software1	94.58
    UParse (Edinburgh)                      	software1	94.58
    LIMSI-LIPN (Paris)                      	software2	94.58
    MQuni (Sydney)                          	software2	94.58
    LyS-FASTPARSE (A Coruña)                	software5	94.58
    TurkuNLP (Turku)                        	software1	94.58
    LATTICE (Paris)                         	software7	94.58
    naistCL (Nara)                          	software1	94.58
    UALING (Tucson)                         	software1	94.58
    Koç University (İstanbul)               	software3	94.58
    BASELINE UDPipe 1.1 (Praha)             	software2	94.58
    ÚFAL – UDPipe 1.2 (Praha)               	software1	94.58
    Stanford (Stanford)                     	software1	94.58
    METU (Ankara)                           	software2	94.58
    C2L2 (Ithaca)                           	software5	94.58
    HIT-SCIR (Harbin)                       	software4	94.58
    CLCL (Genève)                           	software2	94.58
    OpenU NLP Lab (Ra'anana)                	software6	94.58
    RACAI (București)                       	software1	94.58
    IMS (Stuttgart)                         	software2	94.58
    Mengest (Shanghai)                      	software1	94.58
27. Uppsala (Uppsala)                       	software1	92.84
28. TRL (Tokyo)                             	software1	89.92
29. fbaml (Palo Alto)                       	software1	88.64
30. MetaRomance (Santiago de Compostela)    	software1	71.62
31. ECNU (Shanghai)                         	software1	70.32
32. Wenba-NLU (Wuhan)                       	software1	 0.00
    UT (Tartu)                              	software1	 0.00
</pre>



## Per treebank Sentences-F1



### ar

<pre>
 1. fbaml (Palo Alto)                       	software1	85.69
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	85.40
 3. Wenba-NLU (Wuhan)                       	software1	84.57
    ParisNLP (Paris)                        	software1	84.57
    IIT Kharagpur (Kharagpur)               	software3	84.57
    CLCL (Genève)                           	software1	84.57
    NAIST SATO (Nara)                       	software1	84.57
    Orange – Deskiñ (Lannion)               	software1	84.57
    UParse (Edinburgh)                      	software1	84.57
    LIMSI-LIPN (Paris)                      	software2	84.57
    MQuni (Sydney)                          	software2	84.57
    LyS-FASTPARSE (A Coruña)                	software5	84.57
    TurkuNLP (Turku)                        	software1	84.57
    LATTICE (Paris)                         	software7	84.57
    naistCL (Nara)                          	software1	84.57
    UALING (Tucson)                         	software1	84.57
    Koç University (İstanbul)               	software3	84.57
    BASELINE UDPipe 1.1 (Praha)             	software2	84.57
    Stanford (Stanford)                     	software1	84.57
    METU (Ankara)                           	software2	84.57
    C2L2 (Ithaca)                           	software5	84.57
    MetaRomance (Santiago de Compostela)    	software1	84.57
    OpenU NLP Lab (Ra'anana)                	software6	84.57
    Mengest (Shanghai)                      	software1	84.57
25. darc (Tübingen)                         	software1	82.10
    HIT-SCIR (Harbin)                       	software4	82.10
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	81.77
28. IMS (Stuttgart)                         	software2	77.71
29. Uppsala (Uppsala)                       	software1	77.32
30. TRL (Tokyo)                             	software1	77.10
31. RACAI (București)                       	software1	60.50
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ar_pud

<pre>
 1. ParisNLP (Paris)                        	software1	100.00
    darc (Tübingen)                         	software1	100.00
    IIT Kharagpur (Kharagpur)               	software3	100.00
    CLCL (Genève)                           	software1	100.00
    NAIST SATO (Nara)                       	software1	100.00
    Orange – Deskiñ (Lannion)               	software1	100.00
    UParse (Edinburgh)                      	software1	100.00
    LIMSI-LIPN (Paris)                      	software2	100.00
    MQuni (Sydney)                          	software2	100.00
    LyS-FASTPARSE (A Coruña)                	software5	100.00
    TurkuNLP (Turku)                        	software1	100.00
    LATTICE (Paris)                         	software7	100.00
    naistCL (Nara)                          	software1	100.00
    UALING (Tucson)                         	software1	100.00
    Koç University (İstanbul)               	software3	100.00
    BASELINE UDPipe 1.1 (Praha)             	software2	100.00
    Stanford (Stanford)                     	software1	100.00
    METU (Ankara)                           	software2	100.00
    C2L2 (Ithaca)                           	software5	100.00
    MetaRomance (Santiago de Compostela)    	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    Mengest (Shanghai)                      	software1	100.00
23. fbaml (Palo Alto)                       	software1	99.40
24. Wanghao-ftd-SJTU (Shanghai)             	software2	99.10
    TRL (Tokyo)                             	software1	99.10
    HIT-SCIR (Harbin)                       	software4	99.10
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.95
28. RACAI (București)                       	software1	98.80
29. Uppsala (Uppsala)                       	software1	97.18
30. IMS (Stuttgart)                         	software2	96.79
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### bg

<pre>
 1. Uppsala (Uppsala)                       	software1	93.36
 2. darc (Tübingen)                         	software1	92.97
    HIT-SCIR (Harbin)                       	software4	92.97
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	92.90
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	92.85
 6. Wenba-NLU (Wuhan)                       	software1	92.83
    ParisNLP (Paris)                        	software1	92.83
    IIT Kharagpur (Kharagpur)               	software3	92.83
    CLCL (Genève)                           	software1	92.83
    NAIST SATO (Nara)                       	software1	92.83
    Orange – Deskiñ (Lannion)               	software1	92.83
    UParse (Edinburgh)                      	software1	92.83
    LIMSI-LIPN (Paris)                      	software2	92.83
    MQuni (Sydney)                          	software2	92.83
    LyS-FASTPARSE (A Coruña)                	software5	92.83
    TurkuNLP (Turku)                        	software1	92.83
    LATTICE (Paris)                         	software7	92.83
    naistCL (Nara)                          	software1	92.83
    UALING (Tucson)                         	software1	92.83
    Koç University (İstanbul)               	software3	92.83
    BASELINE UDPipe 1.1 (Praha)             	software2	92.83
    Stanford (Stanford)                     	software1	92.83
    METU (Ankara)                           	software2	92.83
    C2L2 (Ithaca)                           	software5	92.83
    MetaRomance (Santiago de Compostela)    	software1	92.83
    UT (Tartu)                              	software1	92.83
    OpenU NLP Lab (Ra'anana)                	software6	92.83
    RACAI (București)                       	software1	92.83
    IMS (Stuttgart)                         	software2	92.83
    Mengest (Shanghai)                      	software1	92.83
31. fbaml (Palo Alto)                       	software1	91.50
32. TRL (Tokyo)                             	software1	80.71
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### bxr

<pre>
 1. TRL (Tokyo)                             	software1	93.69
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	91.81
    ECNU (Shanghai)                         	software1	91.81
    ParisNLP (Paris)                        	software1	91.81
    darc (Tübingen)                         	software1	91.81
    IIT Kharagpur (Kharagpur)               	software3	91.81
    NAIST SATO (Nara)                       	software1	91.81
    Orange – Deskiñ (Lannion)               	software1	91.81
    UParse (Edinburgh)                      	software1	91.81
    LIMSI-LIPN (Paris)                      	software2	91.81
    MQuni (Sydney)                          	software2	91.81
    LyS-FASTPARSE (A Coruña)                	software5	91.81
    TurkuNLP (Turku)                        	software1	91.81
    LATTICE (Paris)                         	software7	91.81
    naistCL (Nara)                          	software1	91.81
    UALING (Tucson)                         	software1	91.81
    Koç University (İstanbul)               	software3	91.81
    BASELINE UDPipe 1.1 (Praha)             	software2	91.81
    ÚFAL – UDPipe 1.2 (Praha)               	software1	91.81
    Stanford (Stanford)                     	software1	91.81
    METU (Ankara)                           	software2	91.81
    C2L2 (Ithaca)                           	software5	91.81
    HIT-SCIR (Harbin)                       	software4	91.81
    CLCL (Genève)                           	software2	91.81
    OpenU NLP Lab (Ra'anana)                	software6	91.81
    RACAI (București)                       	software1	91.81
    IMS (Stuttgart)                         	software2	91.81
    Mengest (Shanghai)                      	software1	91.81
29. fbaml (Palo Alto)                       	software1	90.62
30. Uppsala (Uppsala)                       	software1	86.93
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ca

<pre>
 1. Uppsala (Uppsala)                       	software1	99.43
 2. fbaml (Palo Alto)                       	software1	99.35
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.19
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.03
 5. Wenba-NLU (Wuhan)                       	software1	98.95
    ParisNLP (Paris)                        	software1	98.95
    IIT Kharagpur (Kharagpur)               	software3	98.95
    NAIST SATO (Nara)                       	software1	98.95
    Orange – Deskiñ (Lannion)               	software1	98.95
    UParse (Edinburgh)                      	software1	98.95
    LIMSI-LIPN (Paris)                      	software2	98.95
    MQuni (Sydney)                          	software2	98.95
    LyS-FASTPARSE (A Coruña)                	software5	98.95
    TurkuNLP (Turku)                        	software1	98.95
    LATTICE (Paris)                         	software7	98.95
    naistCL (Nara)                          	software1	98.95
    UALING (Tucson)                         	software1	98.95
    Koç University (İstanbul)               	software3	98.95
    BASELINE UDPipe 1.1 (Praha)             	software2	98.95
    Stanford (Stanford)                     	software1	98.95
    METU (Ankara)                           	software2	98.95
    C2L2 (Ithaca)                           	software5	98.95
    MetaRomance (Santiago de Compostela)    	software1	98.95
    CLCL (Genève)                           	software2	98.95
    OpenU NLP Lab (Ra'anana)                	software6	98.95
    RACAI (București)                       	software1	98.95
    IMS (Stuttgart)                         	software2	98.95
    Mengest (Shanghai)                      	software1	98.95
29. darc (Tübingen)                         	software1	98.79
    HIT-SCIR (Harbin)                       	software4	98.79
31. TRL (Tokyo)                             	software1	97.25
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs

<pre>
 1. fbaml (Palo Alto)                       	software1	95.10
 2. Uppsala (Uppsala)                       	software1	93.97
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	92.30
 4. darc (Tübingen)                         	software1	92.07
    HIT-SCIR (Harbin)                       	software4	92.07
 6. ParisNLP (Paris)                        	software1	92.03
    IIT Kharagpur (Kharagpur)               	software3	92.03
    CLCL (Genève)                           	software1	92.03
    NAIST SATO (Nara)                       	software1	92.03
    Orange – Deskiñ (Lannion)               	software1	92.03
    UParse (Edinburgh)                      	software1	92.03
    LIMSI-LIPN (Paris)                      	software2	92.03
    MQuni (Sydney)                          	software2	92.03
    LyS-FASTPARSE (A Coruña)                	software5	92.03
    TurkuNLP (Turku)                        	software1	92.03
    LATTICE (Paris)                         	software7	92.03
    naistCL (Nara)                          	software1	92.03
    UALING (Tucson)                         	software1	92.03
    Koç University (İstanbul)               	software3	92.03
    BASELINE UDPipe 1.1 (Praha)             	software2	92.03
    Stanford (Stanford)                     	software1	92.03
    METU (Ankara)                           	software2	92.03
    C2L2 (Ithaca)                           	software5	92.03
    OpenU NLP Lab (Ra'anana)                	software6	92.03
    IMS (Stuttgart)                         	software2	92.03
    Mengest (Shanghai)                      	software1	92.03
27. Wanghao-ftd-SJTU (Shanghai)             	software2	91.46
28. RACAI (București)                       	software1	82.83
29. TRL (Tokyo)                             	software1	77.90
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cac

<pre>
 1. ParisNLP (Paris)                        	software1	100.00
    darc (Tübingen)                         	software1	100.00
    IIT Kharagpur (Kharagpur)               	software3	100.00
    CLCL (Genève)                           	software1	100.00
    NAIST SATO (Nara)                       	software1	100.00
    Orange – Deskiñ (Lannion)               	software1	100.00
    UParse (Edinburgh)                      	software1	100.00
    LIMSI-LIPN (Paris)                      	software2	100.00
    MQuni (Sydney)                          	software2	100.00
    LyS-FASTPARSE (A Coruña)                	software5	100.00
    TurkuNLP (Turku)                        	software1	100.00
    LATTICE (Paris)                         	software7	100.00
    naistCL (Nara)                          	software1	100.00
    UALING (Tucson)                         	software1	100.00
    Koç University (İstanbul)               	software3	100.00
    BASELINE UDPipe 1.1 (Praha)             	software2	100.00
    ÚFAL – UDPipe 1.2 (Praha)               	software1	100.00
    Stanford (Stanford)                     	software1	100.00
    METU (Ankara)                           	software2	100.00
    C2L2 (Ithaca)                           	software5	100.00
    MetaRomance (Santiago de Compostela)    	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    RACAI (București)                       	software1	100.00
    IMS (Stuttgart)                         	software2	100.00
    Mengest (Shanghai)                      	software1	100.00
27. Wanghao-ftd-SJTU (Shanghai)             	software2	99.76
    Uppsala (Uppsala)                       	software1	99.76
    TRL (Tokyo)                             	software1	99.76
    fbaml (Palo Alto)                       	software1	99.76
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cltt

<pre>
 1. darc (Tübingen)                         	software1	95.69
 2. Wenba-NLU (Wuhan)                       	software1	95.06
    ParisNLP (Paris)                        	software1	95.06
    IIT Kharagpur (Kharagpur)               	software3	95.06
    CLCL (Genève)                           	software1	95.06
    NAIST SATO (Nara)                       	software1	95.06
    Orange – Deskiñ (Lannion)               	software1	95.06
    UParse (Edinburgh)                      	software1	95.06
    LIMSI-LIPN (Paris)                      	software2	95.06
    MQuni (Sydney)                          	software2	95.06
    LyS-FASTPARSE (A Coruña)                	software5	95.06
    TurkuNLP (Turku)                        	software1	95.06
    LATTICE (Paris)                         	software7	95.06
    naistCL (Nara)                          	software1	95.06
    UALING (Tucson)                         	software1	95.06
    Koç University (İstanbul)               	software3	95.06
    BASELINE UDPipe 1.1 (Praha)             	software2	95.06
    Stanford (Stanford)                     	software1	95.06
    METU (Ankara)                           	software2	95.06
    C2L2 (Ithaca)                           	software5	95.06
    MetaRomance (Santiago de Compostela)    	software1	95.06
    OpenU NLP Lab (Ra'anana)                	software6	95.06
    IMS (Stuttgart)                         	software2	95.06
    Mengest (Shanghai)                      	software1	95.06
25. Wanghao-ftd-SJTU (Shanghai)             	software2	94.27
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.19
27. Uppsala (Uppsala)                       	software1	92.99
28. fbaml (Palo Alto)                       	software1	91.99
29. HIT-SCIR (Harbin)                       	software4	88.09
30. RACAI (București)                       	software1	80.14
31. TRL (Tokyo)                             	software1	45.04
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_pud

<pre>
 1. ParisNLP (Paris)                        	software1	96.43
    darc (Tübingen)                         	software1	96.43
    IIT Kharagpur (Kharagpur)               	software3	96.43
    CLCL (Genève)                           	software1	96.43
    NAIST SATO (Nara)                       	software1	96.43
    Orange – Deskiñ (Lannion)               	software1	96.43
    UParse (Edinburgh)                      	software1	96.43
    LIMSI-LIPN (Paris)                      	software2	96.43
    MQuni (Sydney)                          	software2	96.43
    LyS-FASTPARSE (A Coruña)                	software5	96.43
    TurkuNLP (Turku)                        	software1	96.43
    LATTICE (Paris)                         	software7	96.43
    naistCL (Nara)                          	software1	96.43
    UALING (Tucson)                         	software1	96.43
    Koç University (İstanbul)               	software3	96.43
    BASELINE UDPipe 1.1 (Praha)             	software2	96.43
    Stanford (Stanford)                     	software1	96.43
    METU (Ankara)                           	software2	96.43
    C2L2 (Ithaca)                           	software5	96.43
    MetaRomance (Santiago de Compostela)    	software1	96.43
    OpenU NLP Lab (Ra'anana)                	software6	96.43
    IMS (Stuttgart)                         	software2	96.43
    Mengest (Shanghai)                      	software1	96.43
24. fbaml (Palo Alto)                       	software1	96.13
25. Wanghao-ftd-SJTU (Shanghai)             	software2	95.53
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	95.40
27. HIT-SCIR (Harbin)                       	software4	95.35
28. Uppsala (Uppsala)                       	software1	94.18
29. RACAI (București)                       	software1	93.23
30. TRL (Tokyo)                             	software1	87.57
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cu

<pre>
 1. IMS (Stuttgart)                         	software2	50.44
 2. HIT-SCIR (Harbin)                       	software4	41.67
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	40.94
 4. Uppsala (Uppsala)                       	software1	39.71
 5. darc (Tübingen)                         	software1	39.46
 6. fbaml (Palo Alto)                       	software1	37.46
 7. Wenba-NLU (Wuhan)                       	software1	36.05
    ECNU (Shanghai)                         	software1	36.05
    ParisNLP (Paris)                        	software1	36.05
    IIT Kharagpur (Kharagpur)               	software3	36.05
    CLCL (Genève)                           	software1	36.05
    NAIST SATO (Nara)                       	software1	36.05
    Orange – Deskiñ (Lannion)               	software1	36.05
    UParse (Edinburgh)                      	software1	36.05
    LIMSI-LIPN (Paris)                      	software2	36.05
    MQuni (Sydney)                          	software2	36.05
    LyS-FASTPARSE (A Coruña)                	software5	36.05
    TurkuNLP (Turku)                        	software1	36.05
    LATTICE (Paris)                         	software7	36.05
    naistCL (Nara)                          	software1	36.05
    UALING (Tucson)                         	software1	36.05
    Koç University (İstanbul)               	software3	36.05
    BASELINE UDPipe 1.1 (Praha)             	software2	36.05
    Stanford (Stanford)                     	software1	36.05
    METU (Ankara)                           	software2	36.05
    C2L2 (Ithaca)                           	software5	36.05
    MetaRomance (Santiago de Compostela)    	software1	36.05
    UT (Tartu)                              	software1	36.05
    OpenU NLP Lab (Ra'anana)                	software6	36.05
    RACAI (București)                       	software1	36.05
    Mengest (Shanghai)                      	software1	36.05
32. Wanghao-ftd-SJTU (Shanghai)             	software2	35.29
33. TRL (Tokyo)                             	software1	 1.16
</pre>



### da

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	82.59
 2. darc (Tübingen)                         	software1	81.46
 3. fbaml (Palo Alto)                       	software1	81.41
 4. HIT-SCIR (Harbin)                       	software4	81.16
 5. Uppsala (Uppsala)                       	software1	81.12
 6. Wenba-NLU (Wuhan)                       	software1	79.36
    ECNU (Shanghai)                         	software1	79.36
    ParisNLP (Paris)                        	software1	79.36
    IIT Kharagpur (Kharagpur)               	software3	79.36
    CLCL (Genève)                           	software1	79.36
    NAIST SATO (Nara)                       	software1	79.36
    Orange – Deskiñ (Lannion)               	software1	79.36
    UParse (Edinburgh)                      	software1	79.36
    LIMSI-LIPN (Paris)                      	software2	79.36
    MQuni (Sydney)                          	software2	79.36
    LyS-FASTPARSE (A Coruña)                	software5	79.36
    TurkuNLP (Turku)                        	software1	79.36
    LATTICE (Paris)                         	software7	79.36
    naistCL (Nara)                          	software1	79.36
    UALING (Tucson)                         	software1	79.36
    Koç University (İstanbul)               	software3	79.36
    BASELINE UDPipe 1.1 (Praha)             	software2	79.36
    Stanford (Stanford)                     	software1	79.36
    METU (Ankara)                           	software2	79.36
    C2L2 (Ithaca)                           	software5	79.36
    MetaRomance (Santiago de Compostela)    	software1	79.36
    UT (Tartu)                              	software1	79.36
    OpenU NLP Lab (Ra'anana)                	software6	79.36
    IMS (Stuttgart)                         	software2	79.36
    Mengest (Shanghai)                      	software1	79.36
31. ÚFAL – UDPipe 1.2 (Praha)               	software1	78.97
32. RACAI (București)                       	software1	76.85
33. TRL (Tokyo)                             	software1	72.76
</pre>



### de

<pre>
 1. Uppsala (Uppsala)                       	software1	80.47
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	79.35
 3. Wenba-NLU (Wuhan)                       	software1	79.11
    ParisNLP (Paris)                        	software1	79.11
    IIT Kharagpur (Kharagpur)               	software3	79.11
    CLCL (Genève)                           	software1	79.11
    NAIST SATO (Nara)                       	software1	79.11
    Orange – Deskiñ (Lannion)               	software1	79.11
    UParse (Edinburgh)                      	software1	79.11
    LIMSI-LIPN (Paris)                      	software2	79.11
    MQuni (Sydney)                          	software2	79.11
    LyS-FASTPARSE (A Coruña)                	software5	79.11
    TurkuNLP (Turku)                        	software1	79.11
    LATTICE (Paris)                         	software7	79.11
    naistCL (Nara)                          	software1	79.11
    UALING (Tucson)                         	software1	79.11
    Koç University (İstanbul)               	software3	79.11
    BASELINE UDPipe 1.1 (Praha)             	software2	79.11
    Stanford (Stanford)                     	software1	79.11
    METU (Ankara)                           	software2	79.11
    C2L2 (Ithaca)                           	software5	79.11
    MetaRomance (Santiago de Compostela)    	software1	79.11
    OpenU NLP Lab (Ra'anana)                	software6	79.11
    IMS (Stuttgart)                         	software2	79.11
    Mengest (Shanghai)                      	software1	79.11
26. fbaml (Palo Alto)                       	software1	78.78
27. Wanghao-ftd-SJTU (Shanghai)             	software2	78.60
28. darc (Tübingen)                         	software1	77.58
    HIT-SCIR (Harbin)                       	software4	77.58
30. RACAI (București)                       	software1	76.80
31. TRL (Tokyo)                             	software1	69.84
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### de_pud

<pre>
 1. HIT-SCIR (Harbin)                       	software4	91.40
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	90.75
 3. RACAI (București)                       	software1	89.87
 4. fbaml (Palo Alto)                       	software1	88.40
 5. Uppsala (Uppsala)                       	software1	87.16
 6. TRL (Tokyo)                             	software1	86.93
 7. ParisNLP (Paris)                        	software1	86.49
    darc (Tübingen)                         	software1	86.49
    IIT Kharagpur (Kharagpur)               	software3	86.49
    CLCL (Genève)                           	software1	86.49
    NAIST SATO (Nara)                       	software1	86.49
    Orange – Deskiñ (Lannion)               	software1	86.49
    UParse (Edinburgh)                      	software1	86.49
    LIMSI-LIPN (Paris)                      	software2	86.49
    MQuni (Sydney)                          	software2	86.49
    LyS-FASTPARSE (A Coruña)                	software5	86.49
    TurkuNLP (Turku)                        	software1	86.49
    LATTICE (Paris)                         	software7	86.49
    naistCL (Nara)                          	software1	86.49
    UALING (Tucson)                         	software1	86.49
    Koç University (İstanbul)               	software3	86.49
    BASELINE UDPipe 1.1 (Praha)             	software2	86.49
    Stanford (Stanford)                     	software1	86.49
    METU (Ankara)                           	software2	86.49
    C2L2 (Ithaca)                           	software5	86.49
    MetaRomance (Santiago de Compostela)    	software1	86.49
    OpenU NLP Lab (Ra'anana)                	software6	86.49
    IMS (Stuttgart)                         	software2	86.49
    Mengest (Shanghai)                      	software1	86.49
30. Wanghao-ftd-SJTU (Shanghai)             	software2	86.08
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### el

<pre>
 1. ParisNLP (Paris)                        	software1	92.68
 2. Wenba-NLU (Wuhan)                       	software1	90.79
    ECNU (Shanghai)                         	software1	90.79
    IIT Kharagpur (Kharagpur)               	software3	90.79
    CLCL (Genève)                           	software1	90.79
    NAIST SATO (Nara)                       	software1	90.79
    Orange – Deskiñ (Lannion)               	software1	90.79
    UParse (Edinburgh)                      	software1	90.79
    LIMSI-LIPN (Paris)                      	software2	90.79
    MQuni (Sydney)                          	software2	90.79
    LyS-FASTPARSE (A Coruña)                	software5	90.79
    TurkuNLP (Turku)                        	software1	90.79
    LATTICE (Paris)                         	software7	90.79
    naistCL (Nara)                          	software1	90.79
    UALING (Tucson)                         	software1	90.79
    Koç University (İstanbul)               	software3	90.79
    BASELINE UDPipe 1.1 (Praha)             	software2	90.79
    Stanford (Stanford)                     	software1	90.79
    METU (Ankara)                           	software2	90.79
    C2L2 (Ithaca)                           	software5	90.79
    MetaRomance (Santiago de Compostela)    	software1	90.79
    UT (Tartu)                              	software1	90.79
    OpenU NLP Lab (Ra'anana)                	software6	90.79
    IMS (Stuttgart)                         	software2	90.79
    Mengest (Shanghai)                      	software1	90.79
26. fbaml (Palo Alto)                       	software1	90.41
27. Uppsala (Uppsala)                       	software1	90.38
28. ÚFAL – UDPipe 1.2 (Praha)               	software1	90.00
29. darc (Tübingen)                         	software1	89.99
    HIT-SCIR (Harbin)                       	software4	89.99
31. Wanghao-ftd-SJTU (Shanghai)             	software2	89.62
32. RACAI (București)                       	software1	87.56
33. TRL (Tokyo)                             	software1	81.03
</pre>



### en

<pre>
 1. fbaml (Palo Alto)                       	software1	78.01
 2. HIT-SCIR (Harbin)                       	software4	77.99
 3. Uppsala (Uppsala)                       	software1	76.91
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	75.33
 5. IMS (Stuttgart)                         	software2	74.72
 6. Wanghao-ftd-SJTU (Shanghai)             	software2	73.28
 7. Wenba-NLU (Wuhan)                       	software1	73.22
    ParisNLP (Paris)                        	software1	73.22
    IIT Kharagpur (Kharagpur)               	software3	73.22
    CLCL (Genève)                           	software1	73.22
    NAIST SATO (Nara)                       	software1	73.22
    Orange – Deskiñ (Lannion)               	software1	73.22
    UParse (Edinburgh)                      	software1	73.22
    LIMSI-LIPN (Paris)                      	software2	73.22
    MQuni (Sydney)                          	software2	73.22
    LyS-FASTPARSE (A Coruña)                	software5	73.22
    TurkuNLP (Turku)                        	software1	73.22
    LATTICE (Paris)                         	software7	73.22
    naistCL (Nara)                          	software1	73.22
    UALING (Tucson)                         	software1	73.22
    Koç University (İstanbul)               	software3	73.22
    BASELINE UDPipe 1.1 (Praha)             	software2	73.22
    Stanford (Stanford)                     	software1	73.22
    METU (Ankara)                           	software2	73.22
    C2L2 (Ithaca)                           	software5	73.22
    MetaRomance (Santiago de Compostela)    	software1	73.22
    OpenU NLP Lab (Ra'anana)                	software6	73.22
    RACAI (București)                       	software1	73.22
    Mengest (Shanghai)                      	software1	73.22
30. darc (Tübingen)                         	software1	72.92
31. TRL (Tokyo)                             	software1	64.77
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_lines

<pre>
 1. darc (Tübingen)                         	software1	87.55
    HIT-SCIR (Harbin)                       	software4	87.55
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	87.40
 4. fbaml (Palo Alto)                       	software1	86.95
 5. Uppsala (Uppsala)                       	software1	86.84
 6. Wanghao-ftd-SJTU (Shanghai)             	software2	86.25
 7. Wenba-NLU (Wuhan)                       	software1	85.84
    ECNU (Shanghai)                         	software1	85.84
    ParisNLP (Paris)                        	software1	85.84
    IIT Kharagpur (Kharagpur)               	software3	85.84
    CLCL (Genève)                           	software1	85.84
    NAIST SATO (Nara)                       	software1	85.84
    Orange – Deskiñ (Lannion)               	software1	85.84
    UParse (Edinburgh)                      	software1	85.84
    LIMSI-LIPN (Paris)                      	software2	85.84
    MQuni (Sydney)                          	software2	85.84
    LyS-FASTPARSE (A Coruña)                	software5	85.84
    TurkuNLP (Turku)                        	software1	85.84
    LATTICE (Paris)                         	software7	85.84
    naistCL (Nara)                          	software1	85.84
    UALING (Tucson)                         	software1	85.84
    Koç University (İstanbul)               	software3	85.84
    BASELINE UDPipe 1.1 (Praha)             	software2	85.84
    Stanford (Stanford)                     	software1	85.84
    METU (Ankara)                           	software2	85.84
    C2L2 (Ithaca)                           	software5	85.84
    MetaRomance (Santiago de Compostela)    	software1	85.84
    UT (Tartu)                              	software1	85.84
    OpenU NLP Lab (Ra'anana)                	software6	85.84
    IMS (Stuttgart)                         	software2	85.84
    Mengest (Shanghai)                      	software1	85.84
32. RACAI (București)                       	software1	82.11
33. TRL (Tokyo)                             	software1	81.72
</pre>



### en_partut

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.40
 2. Uppsala (Uppsala)                       	software1	98.20
 3. fbaml (Palo Alto)                       	software1	98.10
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	97.80
    darc (Tübingen)                         	software1	97.80
    HIT-SCIR (Harbin)                       	software4	97.80
 7. Wenba-NLU (Wuhan)                       	software1	97.51
    ParisNLP (Paris)                        	software1	97.51
    IIT Kharagpur (Kharagpur)               	software3	97.51
    CLCL (Genève)                           	software1	97.51
    NAIST SATO (Nara)                       	software1	97.51
    Orange – Deskiñ (Lannion)               	software1	97.51
    UParse (Edinburgh)                      	software1	97.51
    LIMSI-LIPN (Paris)                      	software2	97.51
    MQuni (Sydney)                          	software2	97.51
    LyS-FASTPARSE (A Coruña)                	software5	97.51
    TurkuNLP (Turku)                        	software1	97.51
    LATTICE (Paris)                         	software7	97.51
    naistCL (Nara)                          	software1	97.51
    UALING (Tucson)                         	software1	97.51
    Koç University (İstanbul)               	software3	97.51
    BASELINE UDPipe 1.1 (Praha)             	software2	97.51
    Stanford (Stanford)                     	software1	97.51
    METU (Ankara)                           	software2	97.51
    C2L2 (Ithaca)                           	software5	97.51
    MetaRomance (Santiago de Compostela)    	software1	97.51
    OpenU NLP Lab (Ra'anana)                	software6	97.51
    RACAI (București)                       	software1	97.51
    IMS (Stuttgart)                         	software2	97.51
    Mengest (Shanghai)                      	software1	97.51
31. TRL (Tokyo)                             	software1	90.61
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_pud

<pre>
 1. fbaml (Palo Alto)                       	software1	98.06
 2. ECNU (Shanghai)                         	software1	97.13
    ParisNLP (Paris)                        	software1	97.13
    darc (Tübingen)                         	software1	97.13
    IIT Kharagpur (Kharagpur)               	software3	97.13
    CLCL (Genève)                           	software1	97.13
    NAIST SATO (Nara)                       	software1	97.13
    Orange – Deskiñ (Lannion)               	software1	97.13
    UParse (Edinburgh)                      	software1	97.13
    LIMSI-LIPN (Paris)                      	software2	97.13
    MQuni (Sydney)                          	software2	97.13
    LyS-FASTPARSE (A Coruña)                	software5	97.13
    TurkuNLP (Turku)                        	software1	97.13
    LATTICE (Paris)                         	software7	97.13
    naistCL (Nara)                          	software1	97.13
    UALING (Tucson)                         	software1	97.13
    Koç University (İstanbul)               	software3	97.13
    BASELINE UDPipe 1.1 (Praha)             	software2	97.13
    Stanford (Stanford)                     	software1	97.13
    METU (Ankara)                           	software2	97.13
    C2L2 (Ithaca)                           	software5	97.13
    MetaRomance (Santiago de Compostela)    	software1	97.13
    UT (Tartu)                              	software1	97.13
    OpenU NLP Lab (Ra'anana)                	software6	97.13
    RACAI (București)                       	software1	97.13
    IMS (Stuttgart)                         	software2	97.13
    Mengest (Shanghai)                      	software1	97.13
28. Wanghao-ftd-SJTU (Shanghai)             	software2	96.45
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	95.57
30. Uppsala (Uppsala)                       	software1	95.28
31. TRL (Tokyo)                             	software1	94.29
32. HIT-SCIR (Harbin)                       	software4	93.26
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### es

<pre>
 1. Uppsala (Uppsala)                       	software1	95.37
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	95.26
 3. darc (Tübingen)                         	software1	94.89
    HIT-SCIR (Harbin)                       	software4	94.89
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	94.52
 6. RACAI (București)                       	software1	94.17
 7. ParisNLP (Paris)                        	software1	94.15
    IIT Kharagpur (Kharagpur)               	software3	94.15
    NAIST SATO (Nara)                       	software1	94.15
    Orange – Deskiñ (Lannion)               	software1	94.15
    UParse (Edinburgh)                      	software1	94.15
    LIMSI-LIPN (Paris)                      	software2	94.15
    MQuni (Sydney)                          	software2	94.15
    LyS-FASTPARSE (A Coruña)                	software5	94.15
    TurkuNLP (Turku)                        	software1	94.15
    LATTICE (Paris)                         	software7	94.15
    naistCL (Nara)                          	software1	94.15
    UALING (Tucson)                         	software1	94.15
    Koç University (İstanbul)               	software3	94.15
    BASELINE UDPipe 1.1 (Praha)             	software2	94.15
    Stanford (Stanford)                     	software1	94.15
    METU (Ankara)                           	software2	94.15
    C2L2 (Ithaca)                           	software5	94.15
    MetaRomance (Santiago de Compostela)    	software1	94.15
    CLCL (Genève)                           	software2	94.15
    OpenU NLP Lab (Ra'anana)                	software6	94.15
    IMS (Stuttgart)                         	software2	94.15
    Mengest (Shanghai)                      	software1	94.15
29. fbaml (Palo Alto)                       	software1	94.05
30. TRL (Tokyo)                             	software1	88.19
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_ancora

<pre>
 1. fbaml (Palo Alto)                       	software1	98.67
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.26
 3. Uppsala (Uppsala)                       	software1	98.06
    RACAI (București)                       	software1	98.06
 5. darc (Tübingen)                         	software1	98.00
    HIT-SCIR (Harbin)                       	software4	98.00
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	97.18
 8. ParisNLP (Paris)                        	software1	97.05
    IIT Kharagpur (Kharagpur)               	software3	97.05
    NAIST SATO (Nara)                       	software1	97.05
    Orange – Deskiñ (Lannion)               	software1	97.05
    UParse (Edinburgh)                      	software1	97.05
    LIMSI-LIPN (Paris)                      	software2	97.05
    MQuni (Sydney)                          	software2	97.05
    LyS-FASTPARSE (A Coruña)                	software5	97.05
    TurkuNLP (Turku)                        	software1	97.05
    LATTICE (Paris)                         	software7	97.05
    naistCL (Nara)                          	software1	97.05
    UALING (Tucson)                         	software1	97.05
    Koç University (İstanbul)               	software3	97.05
    BASELINE UDPipe 1.1 (Praha)             	software2	97.05
    Stanford (Stanford)                     	software1	97.05
    METU (Ankara)                           	software2	97.05
    C2L2 (Ithaca)                           	software5	97.05
    MetaRomance (Santiago de Compostela)    	software1	97.05
    CLCL (Genève)                           	software2	97.05
    OpenU NLP Lab (Ra'anana)                	software6	97.05
    IMS (Stuttgart)                         	software2	97.05
    Mengest (Shanghai)                      	software1	97.05
30. TRL (Tokyo)                             	software1	95.44
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_pud

<pre>
 1. HIT-SCIR (Harbin)                       	software4	98.19
 2. TRL (Tokyo)                             	software1	95.40
 3. RACAI (București)                       	software1	95.27
 4. fbaml (Palo Alto)                       	software1	94.88
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.14
 6. Wanghao-ftd-SJTU (Shanghai)             	software2	93.50
 7. ParisNLP (Paris)                        	software1	93.42
    darc (Tübingen)                         	software1	93.42
    IIT Kharagpur (Kharagpur)               	software3	93.42
    CLCL (Genève)                           	software1	93.42
    NAIST SATO (Nara)                       	software1	93.42
    Orange – Deskiñ (Lannion)               	software1	93.42
    UParse (Edinburgh)                      	software1	93.42
    LIMSI-LIPN (Paris)                      	software2	93.42
    MQuni (Sydney)                          	software2	93.42
    LyS-FASTPARSE (A Coruña)                	software5	93.42
    TurkuNLP (Turku)                        	software1	93.42
    LATTICE (Paris)                         	software7	93.42
    naistCL (Nara)                          	software1	93.42
    UALING (Tucson)                         	software1	93.42
    Koç University (İstanbul)               	software3	93.42
    BASELINE UDPipe 1.1 (Praha)             	software2	93.42
    Stanford (Stanford)                     	software1	93.42
    METU (Ankara)                           	software2	93.42
    C2L2 (Ithaca)                           	software5	93.42
    MetaRomance (Santiago de Compostela)    	software1	93.42
    OpenU NLP Lab (Ra'anana)                	software6	93.42
    IMS (Stuttgart)                         	software2	93.42
    Mengest (Shanghai)                      	software1	93.42
30. Uppsala (Uppsala)                       	software1	93.41
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### et

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	93.66
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	93.52
 3. darc (Tübingen)                         	software1	93.47
    HIT-SCIR (Harbin)                       	software4	93.47
 5. Uppsala (Uppsala)                       	software1	92.74
 6. fbaml (Palo Alto)                       	software1	92.63
 7. RACAI (București)                       	software1	92.53
 8. ParisNLP (Paris)                        	software1	88.30
 9. IMS (Stuttgart)                         	software2	85.21
10. Wenba-NLU (Wuhan)                       	software1	85.20
    ECNU (Shanghai)                         	software1	85.20
    IIT Kharagpur (Kharagpur)               	software3	85.20
    CLCL (Genève)                           	software1	85.20
    NAIST SATO (Nara)                       	software1	85.20
    Orange – Deskiñ (Lannion)               	software1	85.20
    UParse (Edinburgh)                      	software1	85.20
    LIMSI-LIPN (Paris)                      	software2	85.20
    MQuni (Sydney)                          	software2	85.20
    LyS-FASTPARSE (A Coruña)                	software5	85.20
    TurkuNLP (Turku)                        	software1	85.20
    LATTICE (Paris)                         	software7	85.20
    naistCL (Nara)                          	software1	85.20
    UALING (Tucson)                         	software1	85.20
    Koç University (İstanbul)               	software3	85.20
    BASELINE UDPipe 1.1 (Praha)             	software2	85.20
    Stanford (Stanford)                     	software1	85.20
    METU (Ankara)                           	software2	85.20
    C2L2 (Ithaca)                           	software5	85.20
    MetaRomance (Santiago de Compostela)    	software1	85.20
    UT (Tartu)                              	software1	85.20
    OpenU NLP Lab (Ra'anana)                	software6	85.20
    Mengest (Shanghai)                      	software1	85.20
33. TRL (Tokyo)                             	software1	80.91
</pre>



### eu

<pre>
 1. RACAI (București)                       	software1	99.83
 2. fbaml (Palo Alto)                       	software1	99.75
 3. Uppsala (Uppsala)                       	software1	99.67
 4. Wenba-NLU (Wuhan)                       	software1	99.58
    ECNU (Shanghai)                         	software1	99.58
    ParisNLP (Paris)                        	software1	99.58
    darc (Tübingen)                         	software1	99.58
    IIT Kharagpur (Kharagpur)               	software3	99.58
    NAIST SATO (Nara)                       	software1	99.58
    Orange – Deskiñ (Lannion)               	software1	99.58
    UParse (Edinburgh)                      	software1	99.58
    LIMSI-LIPN (Paris)                      	software2	99.58
    MQuni (Sydney)                          	software2	99.58
    LyS-FASTPARSE (A Coruña)                	software5	99.58
    TurkuNLP (Turku)                        	software1	99.58
    LATTICE (Paris)                         	software7	99.58
    naistCL (Nara)                          	software1	99.58
    UALING (Tucson)                         	software1	99.58
    Koç University (İstanbul)               	software3	99.58
    BASELINE UDPipe 1.1 (Praha)             	software2	99.58
    Stanford (Stanford)                     	software1	99.58
    METU (Ankara)                           	software2	99.58
    C2L2 (Ithaca)                           	software5	99.58
    MetaRomance (Santiago de Compostela)    	software1	99.58
    HIT-SCIR (Harbin)                       	software4	99.58
    UT (Tartu)                              	software1	99.58
    CLCL (Genève)                           	software2	99.58
    OpenU NLP Lab (Ra'anana)                	software6	99.58
    IMS (Stuttgart)                         	software2	99.58
    Mengest (Shanghai)                      	software1	99.58
31. Wanghao-ftd-SJTU (Shanghai)             	software2	99.50
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.50
33. TRL (Tokyo)                             	software1	91.06
</pre>



### fa

<pre>
 1. fbaml (Palo Alto)                       	software1	99.25
 2. Uppsala (Uppsala)                       	software1	98.75
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	98.50
 4. RACAI (București)                       	software1	98.01
 5. Wenba-NLU (Wuhan)                       	software1	98.00
    ParisNLP (Paris)                        	software1	98.00
    darc (Tübingen)                         	software1	98.00
    IIT Kharagpur (Kharagpur)               	software3	98.00
    NAIST SATO (Nara)                       	software1	98.00
    Orange – Deskiñ (Lannion)               	software1	98.00
    UParse (Edinburgh)                      	software1	98.00
    LIMSI-LIPN (Paris)                      	software2	98.00
    MQuni (Sydney)                          	software2	98.00
    LyS-FASTPARSE (A Coruña)                	software5	98.00
    TurkuNLP (Turku)                        	software1	98.00
    LATTICE (Paris)                         	software7	98.00
    naistCL (Nara)                          	software1	98.00
    UALING (Tucson)                         	software1	98.00
    Koç University (İstanbul)               	software3	98.00
    BASELINE UDPipe 1.1 (Praha)             	software2	98.00
    Stanford (Stanford)                     	software1	98.00
    METU (Ankara)                           	software2	98.00
    C2L2 (Ithaca)                           	software5	98.00
    MetaRomance (Santiago de Compostela)    	software1	98.00
    HIT-SCIR (Harbin)                       	software4	98.00
    CLCL (Genève)                           	software2	98.00
    OpenU NLP Lab (Ra'anana)                	software6	98.00
    IMS (Stuttgart)                         	software2	98.00
    Mengest (Shanghai)                      	software1	98.00
30. ÚFAL – UDPipe 1.2 (Praha)               	software1	97.76
31. TRL (Tokyo)                             	software1	96.11
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi

<pre>
 1. Uppsala (Uppsala)                       	software1	90.88
 2. fbaml (Palo Alto)                       	software1	89.48
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	86.75
 4. RACAI (București)                       	software1	86.05
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	85.91
 6. darc (Tübingen)                         	software1	85.66
    HIT-SCIR (Harbin)                       	software4	85.66
 8. ParisNLP (Paris)                        	software1	85.24
 9. Wenba-NLU (Wuhan)                       	software1	84.56
    IIT Kharagpur (Kharagpur)               	software3	84.56
    NAIST SATO (Nara)                       	software1	84.56
    Orange – Deskiñ (Lannion)               	software1	84.56
    UParse (Edinburgh)                      	software1	84.56
    LIMSI-LIPN (Paris)                      	software2	84.56
    MQuni (Sydney)                          	software2	84.56
    LyS-FASTPARSE (A Coruña)                	software5	84.56
    TurkuNLP (Turku)                        	software1	84.56
    LATTICE (Paris)                         	software7	84.56
    naistCL (Nara)                          	software1	84.56
    UALING (Tucson)                         	software1	84.56
    Koç University (İstanbul)               	software3	84.56
    BASELINE UDPipe 1.1 (Praha)             	software2	84.56
    Stanford (Stanford)                     	software1	84.56
    METU (Ankara)                           	software2	84.56
    C2L2 (Ithaca)                           	software5	84.56
    MetaRomance (Santiago de Compostela)    	software1	84.56
    UT (Tartu)                              	software1	84.56
    CLCL (Genève)                           	software2	84.56
    OpenU NLP Lab (Ra'anana)                	software6	84.56
    IMS (Stuttgart)                         	software2	84.56
    Mengest (Shanghai)                      	software1	84.56
32. TRL (Tokyo)                             	software1	80.34
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### fi_ftb

<pre>
 1. Uppsala (Uppsala)                       	software1	86.98
 2. ParisNLP (Paris)                        	software1	86.57
 3. fbaml (Palo Alto)                       	software1	86.46
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	85.54
 5. HIT-SCIR (Harbin)                       	software4	85.11
 6. Wanghao-ftd-SJTU (Shanghai)             	software2	84.78
 7. Wenba-NLU (Wuhan)                       	software1	83.83
    IIT Kharagpur (Kharagpur)               	software3	83.83
    NAIST SATO (Nara)                       	software1	83.83
    Orange – Deskiñ (Lannion)               	software1	83.83
    UParse (Edinburgh)                      	software1	83.83
    LIMSI-LIPN (Paris)                      	software2	83.83
    MQuni (Sydney)                          	software2	83.83
    LyS-FASTPARSE (A Coruña)                	software5	83.83
    TurkuNLP (Turku)                        	software1	83.83
    LATTICE (Paris)                         	software7	83.83
    naistCL (Nara)                          	software1	83.83
    UALING (Tucson)                         	software1	83.83
    Koç University (İstanbul)               	software3	83.83
    BASELINE UDPipe 1.1 (Praha)             	software2	83.83
    Stanford (Stanford)                     	software1	83.83
    METU (Ankara)                           	software2	83.83
    C2L2 (Ithaca)                           	software5	83.83
    MetaRomance (Santiago de Compostela)    	software1	83.83
    CLCL (Genève)                           	software2	83.83
    OpenU NLP Lab (Ra'anana)                	software6	83.83
    RACAI (București)                       	software1	83.83
    IMS (Stuttgart)                         	software2	83.83
    Mengest (Shanghai)                      	software1	83.83
30. darc (Tübingen)                         	software1	83.69
31. TRL (Tokyo)                             	software1	75.42
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi_pud

<pre>
 1. ECNU (Shanghai)                         	software1	93.67
    ParisNLP (Paris)                        	software1	93.67
    darc (Tübingen)                         	software1	93.67
    IIT Kharagpur (Kharagpur)               	software3	93.67
    CLCL (Genève)                           	software1	93.67
    NAIST SATO (Nara)                       	software1	93.67
    Orange – Deskiñ (Lannion)               	software1	93.67
    UParse (Edinburgh)                      	software1	93.67
    LIMSI-LIPN (Paris)                      	software2	93.67
    MQuni (Sydney)                          	software2	93.67
    LyS-FASTPARSE (A Coruña)                	software5	93.67
    TurkuNLP (Turku)                        	software1	93.67
    LATTICE (Paris)                         	software7	93.67
    naistCL (Nara)                          	software1	93.67
    UALING (Tucson)                         	software1	93.67
    Koç University (İstanbul)               	software3	93.67
    BASELINE UDPipe 1.1 (Praha)             	software2	93.67
    Stanford (Stanford)                     	software1	93.67
    METU (Ankara)                           	software2	93.67
    C2L2 (Ithaca)                           	software5	93.67
    MetaRomance (Santiago de Compostela)    	software1	93.67
    OpenU NLP Lab (Ra'anana)                	software6	93.67
    IMS (Stuttgart)                         	software2	93.67
    Mengest (Shanghai)                      	software1	93.67
25. fbaml (Palo Alto)                       	software1	92.93
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	92.20
27. Uppsala (Uppsala)                       	software1	92.02
28. RACAI (București)                       	software1	91.91
29. Wanghao-ftd-SJTU (Shanghai)             	software2	89.95
30. HIT-SCIR (Harbin)                       	software4	89.23
31. TRL (Tokyo)                             	software1	87.50
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.58
 2. Uppsala (Uppsala)                       	software1	93.85
 3. Wenba-NLU (Wuhan)                       	software1	93.59
    ParisNLP (Paris)                        	software1	93.59
    IIT Kharagpur (Kharagpur)               	software3	93.59
    NAIST SATO (Nara)                       	software1	93.59
    Orange – Deskiñ (Lannion)               	software1	93.59
    UParse (Edinburgh)                      	software1	93.59
    LIMSI-LIPN (Paris)                      	software2	93.59
    MQuni (Sydney)                          	software2	93.59
    LyS-FASTPARSE (A Coruña)                	software5	93.59
    TurkuNLP (Turku)                        	software1	93.59
    LATTICE (Paris)                         	software7	93.59
    naistCL (Nara)                          	software1	93.59
    UALING (Tucson)                         	software1	93.59
    Koç University (İstanbul)               	software3	93.59
    BASELINE UDPipe 1.1 (Praha)             	software2	93.59
    Stanford (Stanford)                     	software1	93.59
    METU (Ankara)                           	software2	93.59
    C2L2 (Ithaca)                           	software5	93.59
    MetaRomance (Santiago de Compostela)    	software1	93.59
    CLCL (Genève)                           	software2	93.59
    OpenU NLP Lab (Ra'anana)                	software6	93.59
    IMS (Stuttgart)                         	software2	93.59
    Mengest (Shanghai)                      	software1	93.59
26. fbaml (Palo Alto)                       	software1	92.49
27. RACAI (București)                       	software1	92.12
28. darc (Tübingen)                         	software1	92.05
    HIT-SCIR (Harbin)                       	software4	92.05
30. Wanghao-ftd-SJTU (Shanghai)             	software2	91.68
31. TRL (Tokyo)                             	software1	86.99
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_partut

<pre>
 1. Uppsala (Uppsala)                       	software1	99.13
 2. RACAI (București)                       	software1	99.12
 3. fbaml (Palo Alto)                       	software1	98.50
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	98.01
    darc (Tübingen)                         	software1	98.01
    HIT-SCIR (Harbin)                       	software4	98.01
 7. ParisNLP (Paris)                        	software1	98.00
    IIT Kharagpur (Kharagpur)               	software3	98.00
    NAIST SATO (Nara)                       	software1	98.00
    Orange – Deskiñ (Lannion)               	software1	98.00
    UParse (Edinburgh)                      	software1	98.00
    LIMSI-LIPN (Paris)                      	software2	98.00
    MQuni (Sydney)                          	software2	98.00
    LyS-FASTPARSE (A Coruña)                	software5	98.00
    TurkuNLP (Turku)                        	software1	98.00
    LATTICE (Paris)                         	software7	98.00
    naistCL (Nara)                          	software1	98.00
    UALING (Tucson)                         	software1	98.00
    Koç University (İstanbul)               	software3	98.00
    BASELINE UDPipe 1.1 (Praha)             	software2	98.00
    Stanford (Stanford)                     	software1	98.00
    METU (Ankara)                           	software2	98.00
    C2L2 (Ithaca)                           	software5	98.00
    MetaRomance (Santiago de Compostela)    	software1	98.00
    CLCL (Genève)                           	software2	98.00
    OpenU NLP Lab (Ra'anana)                	software6	98.00
    IMS (Stuttgart)                         	software2	98.00
    Mengest (Shanghai)                      	software1	98.00
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	97.76
30. TRL (Tokyo)                             	software1	89.99
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_pud

<pre>
 1. fbaml (Palo Alto)                       	software1	96.55
 2. TRL (Tokyo)                             	software1	95.85
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	95.36
 4. HIT-SCIR (Harbin)                       	software4	93.61
 5. Uppsala (Uppsala)                       	software1	93.52
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	93.33
 7. ParisNLP (Paris)                        	software1	92.32
    darc (Tübingen)                         	software1	92.32
    IIT Kharagpur (Kharagpur)               	software3	92.32
    CLCL (Genève)                           	software1	92.32
    NAIST SATO (Nara)                       	software1	92.32
    Orange – Deskiñ (Lannion)               	software1	92.32
    UParse (Edinburgh)                      	software1	92.32
    LIMSI-LIPN (Paris)                      	software2	92.32
    MQuni (Sydney)                          	software2	92.32
    LyS-FASTPARSE (A Coruña)                	software5	92.32
    TurkuNLP (Turku)                        	software1	92.32
    LATTICE (Paris)                         	software7	92.32
    naistCL (Nara)                          	software1	92.32
    UALING (Tucson)                         	software1	92.32
    Koç University (İstanbul)               	software3	92.32
    BASELINE UDPipe 1.1 (Praha)             	software2	92.32
    Stanford (Stanford)                     	software1	92.32
    METU (Ankara)                           	software2	92.32
    C2L2 (Ithaca)                           	software5	92.32
    MetaRomance (Santiago de Compostela)    	software1	92.32
    OpenU NLP Lab (Ra'anana)                	software6	92.32
    IMS (Stuttgart)                         	software2	92.32
    Mengest (Shanghai)                      	software1	92.32
30. RACAI (București)                       	software1	91.71
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_sequoia

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	84.60
 2. darc (Tübingen)                         	software1	83.91
    HIT-SCIR (Harbin)                       	software4	83.91
 4. Wenba-NLU (Wuhan)                       	software1	83.75
    ParisNLP (Paris)                        	software1	83.75
    IIT Kharagpur (Kharagpur)               	software3	83.75
    NAIST SATO (Nara)                       	software1	83.75
    Orange – Deskiñ (Lannion)               	software1	83.75
    UParse (Edinburgh)                      	software1	83.75
    LIMSI-LIPN (Paris)                      	software2	83.75
    MQuni (Sydney)                          	software2	83.75
    LyS-FASTPARSE (A Coruña)                	software5	83.75
    TurkuNLP (Turku)                        	software1	83.75
    LATTICE (Paris)                         	software7	83.75
    naistCL (Nara)                          	software1	83.75
    UALING (Tucson)                         	software1	83.75
    Koç University (İstanbul)               	software3	83.75
    BASELINE UDPipe 1.1 (Praha)             	software2	83.75
    Stanford (Stanford)                     	software1	83.75
    METU (Ankara)                           	software2	83.75
    C2L2 (Ithaca)                           	software5	83.75
    MetaRomance (Santiago de Compostela)    	software1	83.75
    CLCL (Genève)                           	software2	83.75
    OpenU NLP Lab (Ra'anana)                	software6	83.75
    RACAI (București)                       	software1	83.75
    IMS (Stuttgart)                         	software2	83.75
    Mengest (Shanghai)                      	software1	83.75
28. fbaml (Palo Alto)                       	software1	82.97
29. Wanghao-ftd-SJTU (Shanghai)             	software2	82.40
30. Uppsala (Uppsala)                       	software1	81.89
31. TRL (Tokyo)                             	software1	67.24
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ga

<pre>
 1. darc (Tübingen)                         	software1	96.92
 2. RACAI (București)                       	software1	96.69
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	96.48
 4. ParisNLP (Paris)                        	software1	95.81
    IIT Kharagpur (Kharagpur)               	software3	95.81
    NAIST SATO (Nara)                       	software1	95.81
    Orange – Deskiñ (Lannion)               	software1	95.81
    UParse (Edinburgh)                      	software1	95.81
    LIMSI-LIPN (Paris)                      	software2	95.81
    MQuni (Sydney)                          	software2	95.81
    LyS-FASTPARSE (A Coruña)                	software5	95.81
    TurkuNLP (Turku)                        	software1	95.81
    LATTICE (Paris)                         	software7	95.81
    naistCL (Nara)                          	software1	95.81
    UALING (Tucson)                         	software1	95.81
    Koç University (İstanbul)               	software3	95.81
    BASELINE UDPipe 1.1 (Praha)             	software2	95.81
    Stanford (Stanford)                     	software1	95.81
    METU (Ankara)                           	software2	95.81
    C2L2 (Ithaca)                           	software5	95.81
    MetaRomance (Santiago de Compostela)    	software1	95.81
    CLCL (Genève)                           	software2	95.81
    OpenU NLP Lab (Ra'anana)                	software6	95.81
    IMS (Stuttgart)                         	software2	95.81
    Mengest (Shanghai)                      	software1	95.81
26. Uppsala (Uppsala)                       	software1	95.70
27. TRL (Tokyo)                             	software1	95.49
28. HIT-SCIR (Harbin)                       	software4	95.13
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.78
30. fbaml (Palo Alto)                       	software1	94.75
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### gl

<pre>
 1. Uppsala (Uppsala)                       	software1	96.36
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	96.18
 3. Wenba-NLU (Wuhan)                       	software1	96.15
    ECNU (Shanghai)                         	software1	96.15
    ParisNLP (Paris)                        	software1	96.15
    IIT Kharagpur (Kharagpur)               	software3	96.15
    NAIST SATO (Nara)                       	software1	96.15
    Orange – Deskiñ (Lannion)               	software1	96.15
    UParse (Edinburgh)                      	software1	96.15
    LIMSI-LIPN (Paris)                      	software2	96.15
    MQuni (Sydney)                          	software2	96.15
    LyS-FASTPARSE (A Coruña)                	software5	96.15
    TurkuNLP (Turku)                        	software1	96.15
    LATTICE (Paris)                         	software7	96.15
    naistCL (Nara)                          	software1	96.15
    UALING (Tucson)                         	software1	96.15
    Koç University (İstanbul)               	software3	96.15
    BASELINE UDPipe 1.1 (Praha)             	software2	96.15
    Stanford (Stanford)                     	software1	96.15
    METU (Ankara)                           	software2	96.15
    C2L2 (Ithaca)                           	software5	96.15
    MetaRomance (Santiago de Compostela)    	software1	96.15
    UT (Tartu)                              	software1	96.15
    CLCL (Genève)                           	software2	96.15
    OpenU NLP Lab (Ra'anana)                	software6	96.15
    IMS (Stuttgart)                         	software2	96.15
    Mengest (Shanghai)                      	software1	96.15
28. fbaml (Palo Alto)                       	software1	96.14
29. RACAI (București)                       	software1	95.92
30. Wanghao-ftd-SJTU (Shanghai)             	software2	95.74
31. darc (Tübingen)                         	software1	95.17
    HIT-SCIR (Harbin)                       	software4	95.17
33. TRL (Tokyo)                             	software1	90.64
</pre>



### gl_treegal

<pre>
 1. fbaml (Palo Alto)                       	software1	86.74
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	85.35
 3. RACAI (București)                       	software1	84.80
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	84.56
 5. HIT-SCIR (Harbin)                       	software4	84.26
 6. darc (Tübingen)                         	software1	83.06
 7. Uppsala (Uppsala)                       	software1	82.71
 8. ParisNLP (Paris)                        	software1	81.63
    IIT Kharagpur (Kharagpur)               	software3	81.63
    NAIST SATO (Nara)                       	software1	81.63
    Orange – Deskiñ (Lannion)               	software1	81.63
    UParse (Edinburgh)                      	software1	81.63
    LIMSI-LIPN (Paris)                      	software2	81.63
    MQuni (Sydney)                          	software2	81.63
    LyS-FASTPARSE (A Coruña)                	software5	81.63
    TurkuNLP (Turku)                        	software1	81.63
    LATTICE (Paris)                         	software7	81.63
    naistCL (Nara)                          	software1	81.63
    UALING (Tucson)                         	software1	81.63
    Koç University (İstanbul)               	software3	81.63
    BASELINE UDPipe 1.1 (Praha)             	software2	81.63
    Stanford (Stanford)                     	software1	81.63
    METU (Ankara)                           	software2	81.63
    C2L2 (Ithaca)                           	software5	81.63
    MetaRomance (Santiago de Compostela)    	software1	81.63
    CLCL (Genève)                           	software2	81.63
    OpenU NLP Lab (Ra'anana)                	software6	81.63
    IMS (Stuttgart)                         	software2	81.63
    Mengest (Shanghai)                      	software1	81.63
30. TRL (Tokyo)                             	software1	78.79
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### got

<pre>
 1. IMS (Stuttgart)                         	software2	41.65
 2. HIT-SCIR (Harbin)                       	software4	35.32
 3. Uppsala (Uppsala)                       	software1	29.65
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	28.98
 5. fbaml (Palo Alto)                       	software1	28.35
 6. Wenba-NLU (Wuhan)                       	software1	27.85
    ECNU (Shanghai)                         	software1	27.85
    ParisNLP (Paris)                        	software1	27.85
    IIT Kharagpur (Kharagpur)               	software3	27.85
    NAIST SATO (Nara)                       	software1	27.85
    Orange – Deskiñ (Lannion)               	software1	27.85
    UParse (Edinburgh)                      	software1	27.85
    LIMSI-LIPN (Paris)                      	software2	27.85
    MQuni (Sydney)                          	software2	27.85
    LyS-FASTPARSE (A Coruña)                	software5	27.85
    TurkuNLP (Turku)                        	software1	27.85
    LATTICE (Paris)                         	software7	27.85
    naistCL (Nara)                          	software1	27.85
    UALING (Tucson)                         	software1	27.85
    Koç University (İstanbul)               	software3	27.85
    BASELINE UDPipe 1.1 (Praha)             	software2	27.85
    Stanford (Stanford)                     	software1	27.85
    METU (Ankara)                           	software2	27.85
    C2L2 (Ithaca)                           	software5	27.85
    MetaRomance (Santiago de Compostela)    	software1	27.85
    UT (Tartu)                              	software1	27.85
    CLCL (Genève)                           	software2	27.85
    OpenU NLP Lab (Ra'anana)                	software6	27.85
    RACAI (București)                       	software1	27.85
    Mengest (Shanghai)                      	software1	27.85
31. darc (Tübingen)                         	software1	26.87
32. ÚFAL – UDPipe 1.2 (Praha)               	software1	24.12
33. TRL (Tokyo)                             	software1	 3.20
</pre>



### grc

<pre>
 1. fbaml (Palo Alto)                       	software1	98.96
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	98.73
    ÚFAL – UDPipe 1.2 (Praha)               	software1	98.73
 4. Uppsala (Uppsala)                       	software1	98.70
    RACAI (București)                       	software1	98.70
 6. darc (Tübingen)                         	software1	98.62
    HIT-SCIR (Harbin)                       	software4	98.62
 8. Wenba-NLU (Wuhan)                       	software1	98.43
    ParisNLP (Paris)                        	software1	98.43
    IIT Kharagpur (Kharagpur)               	software3	98.43
    NAIST SATO (Nara)                       	software1	98.43
    Orange – Deskiñ (Lannion)               	software1	98.43
    UParse (Edinburgh)                      	software1	98.43
    LIMSI-LIPN (Paris)                      	software2	98.43
    MQuni (Sydney)                          	software2	98.43
    LyS-FASTPARSE (A Coruña)                	software5	98.43
    TurkuNLP (Turku)                        	software1	98.43
    LATTICE (Paris)                         	software7	98.43
    naistCL (Nara)                          	software1	98.43
    UALING (Tucson)                         	software1	98.43
    Koç University (İstanbul)               	software3	98.43
    BASELINE UDPipe 1.1 (Praha)             	software2	98.43
    Stanford (Stanford)                     	software1	98.43
    METU (Ankara)                           	software2	98.43
    C2L2 (Ithaca)                           	software5	98.43
    MetaRomance (Santiago de Compostela)    	software1	98.43
    UT (Tartu)                              	software1	98.43
    CLCL (Genève)                           	software2	98.43
    OpenU NLP Lab (Ra'anana)                	software6	98.43
    IMS (Stuttgart)                         	software2	98.43
    Mengest (Shanghai)                      	software1	98.43
32. TRL (Tokyo)                             	software1	41.91
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### grc_proiel

<pre>
 1. IMS (Stuttgart)                         	software2	51.38
 2. Uppsala (Uppsala)                       	software1	49.31
 3. HIT-SCIR (Harbin)                       	software4	48.28
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	47.09
 5. darc (Tübingen)                         	software1	45.50
 6. Wanghao-ftd-SJTU (Shanghai)             	software2	43.67
 7. fbaml (Palo Alto)                       	software1	43.47
 8. Wenba-NLU (Wuhan)                       	software1	43.11
    ParisNLP (Paris)                        	software1	43.11
    IIT Kharagpur (Kharagpur)               	software3	43.11
    NAIST SATO (Nara)                       	software1	43.11
    Orange – Deskiñ (Lannion)               	software1	43.11
    UParse (Edinburgh)                      	software1	43.11
    LIMSI-LIPN (Paris)                      	software2	43.11
    MQuni (Sydney)                          	software2	43.11
    LyS-FASTPARSE (A Coruña)                	software5	43.11
    TurkuNLP (Turku)                        	software1	43.11
    LATTICE (Paris)                         	software7	43.11
    naistCL (Nara)                          	software1	43.11
    UALING (Tucson)                         	software1	43.11
    Koç University (İstanbul)               	software3	43.11
    BASELINE UDPipe 1.1 (Praha)             	software2	43.11
    Stanford (Stanford)                     	software1	43.11
    METU (Ankara)                           	software2	43.11
    C2L2 (Ithaca)                           	software5	43.11
    MetaRomance (Santiago de Compostela)    	software1	43.11
    CLCL (Genève)                           	software2	43.11
    OpenU NLP Lab (Ra'anana)                	software6	43.11
    RACAI (București)                       	software1	43.11
    Mengest (Shanghai)                      	software1	43.11
31. TRL (Tokyo)                             	software1	 1.42
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### he

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	100.00
    RACAI (București)                       	software1	100.00
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.69
 4. fbaml (Palo Alto)                       	software1	99.49
 5. Wenba-NLU (Wuhan)                       	software1	99.39
    ParisNLP (Paris)                        	software1	99.39
    darc (Tübingen)                         	software1	99.39
    IIT Kharagpur (Kharagpur)               	software3	99.39
    NAIST SATO (Nara)                       	software1	99.39
    Orange – Deskiñ (Lannion)               	software1	99.39
    UParse (Edinburgh)                      	software1	99.39
    LIMSI-LIPN (Paris)                      	software2	99.39
    MQuni (Sydney)                          	software2	99.39
    LyS-FASTPARSE (A Coruña)                	software5	99.39
    TurkuNLP (Turku)                        	software1	99.39
    LATTICE (Paris)                         	software7	99.39
    naistCL (Nara)                          	software1	99.39
    UALING (Tucson)                         	software1	99.39
    Koç University (İstanbul)               	software3	99.39
    BASELINE UDPipe 1.1 (Praha)             	software2	99.39
    Stanford (Stanford)                     	software1	99.39
    METU (Ankara)                           	software2	99.39
    C2L2 (Ithaca)                           	software5	99.39
    MetaRomance (Santiago de Compostela)    	software1	99.39
    HIT-SCIR (Harbin)                       	software4	99.39
    CLCL (Genève)                           	software2	99.39
    OpenU NLP Lab (Ra'anana)                	software6	99.39
    IMS (Stuttgart)                         	software2	99.39
    Mengest (Shanghai)                      	software1	99.39
30. Uppsala (Uppsala)                       	software1	99.29
31. TRL (Tokyo)                             	software1	98.89
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hi

<pre>
 1. Uppsala (Uppsala)                       	software1	99.29
 2. Wenba-NLU (Wuhan)                       	software1	99.20
    ParisNLP (Paris)                        	software1	99.20
    IIT Kharagpur (Kharagpur)               	software3	99.20
    NAIST SATO (Nara)                       	software1	99.20
    Orange – Deskiñ (Lannion)               	software1	99.20
    UParse (Edinburgh)                      	software1	99.20
    LIMSI-LIPN (Paris)                      	software2	99.20
    MQuni (Sydney)                          	software2	99.20
    LyS-FASTPARSE (A Coruña)                	software5	99.20
    TurkuNLP (Turku)                        	software1	99.20
    LATTICE (Paris)                         	software7	99.20
    naistCL (Nara)                          	software1	99.20
    UALING (Tucson)                         	software1	99.20
    Koç University (İstanbul)               	software3	99.20
    BASELINE UDPipe 1.1 (Praha)             	software2	99.20
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.20
    Stanford (Stanford)                     	software1	99.20
    METU (Ankara)                           	software2	99.20
    C2L2 (Ithaca)                           	software5	99.20
    MetaRomance (Santiago de Compostela)    	software1	99.20
    UT (Tartu)                              	software1	99.20
    CLCL (Genève)                           	software2	99.20
    OpenU NLP Lab (Ra'anana)                	software6	99.20
    RACAI (București)                       	software1	99.20
    IMS (Stuttgart)                         	software2	99.20
    Mengest (Shanghai)                      	software1	99.20
28. fbaml (Palo Alto)                       	software1	99.11
29. darc (Tübingen)                         	software1	98.93
    HIT-SCIR (Harbin)                       	software4	98.93
31. Wanghao-ftd-SJTU (Shanghai)             	software2	98.04
32. TRL (Tokyo)                             	software1	90.22
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### hi_pud

<pre>
 1. Uppsala (Uppsala)                       	software1	94.85
 2. TRL (Tokyo)                             	software1	94.47
 3. RACAI (București)                       	software1	94.45
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	93.26
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	92.09
 6. HIT-SCIR (Harbin)                       	software4	90.95
 7. ECNU (Shanghai)                         	software1	90.83
    ParisNLP (Paris)                        	software1	90.83
    darc (Tübingen)                         	software1	90.83
    IIT Kharagpur (Kharagpur)               	software3	90.83
    CLCL (Genève)                           	software1	90.83
    NAIST SATO (Nara)                       	software1	90.83
    Orange – Deskiñ (Lannion)               	software1	90.83
    UParse (Edinburgh)                      	software1	90.83
    LIMSI-LIPN (Paris)                      	software2	90.83
    MQuni (Sydney)                          	software2	90.83
    LyS-FASTPARSE (A Coruña)                	software5	90.83
    TurkuNLP (Turku)                        	software1	90.83
    LATTICE (Paris)                         	software7	90.83
    naistCL (Nara)                          	software1	90.83
    UALING (Tucson)                         	software1	90.83
    Koç University (İstanbul)               	software3	90.83
    BASELINE UDPipe 1.1 (Praha)             	software2	90.83
    Stanford (Stanford)                     	software1	90.83
    METU (Ankara)                           	software2	90.83
    C2L2 (Ithaca)                           	software5	90.83
    MetaRomance (Santiago de Compostela)    	software1	90.83
    UT (Tartu)                              	software1	90.83
    OpenU NLP Lab (Ra'anana)                	software6	90.83
    IMS (Stuttgart)                         	software2	90.83
    Mengest (Shanghai)                      	software1	90.83
32. fbaml (Palo Alto)                       	software1	 1.17
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### hr

<pre>
 1. Uppsala (Uppsala)                       	software1	97.75
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	97.50
    darc (Tübingen)                         	software1	97.50
    HIT-SCIR (Harbin)                       	software4	97.50
 5. Wenba-NLU (Wuhan)                       	software1	96.92
    ECNU (Shanghai)                         	software1	96.92
    ParisNLP (Paris)                        	software1	96.92
    IIT Kharagpur (Kharagpur)               	software3	96.92
    CLCL (Genève)                           	software1	96.92
    NAIST SATO (Nara)                       	software1	96.92
    Orange – Deskiñ (Lannion)               	software1	96.92
    UParse (Edinburgh)                      	software1	96.92
    LIMSI-LIPN (Paris)                      	software2	96.92
    MQuni (Sydney)                          	software2	96.92
    LyS-FASTPARSE (A Coruña)                	software5	96.92
    TurkuNLP (Turku)                        	software1	96.92
    LATTICE (Paris)                         	software7	96.92
    naistCL (Nara)                          	software1	96.92
    UALING (Tucson)                         	software1	96.92
    Koç University (İstanbul)               	software3	96.92
    BASELINE UDPipe 1.1 (Praha)             	software2	96.92
    Stanford (Stanford)                     	software1	96.92
    METU (Ankara)                           	software2	96.92
    C2L2 (Ithaca)                           	software5	96.92
    MetaRomance (Santiago de Compostela)    	software1	96.92
    UT (Tartu)                              	software1	96.92
    OpenU NLP Lab (Ra'anana)                	software6	96.92
    IMS (Stuttgart)                         	software2	96.92
    Mengest (Shanghai)                      	software1	96.92
30. fbaml (Palo Alto)                       	software1	95.92
31. RACAI (București)                       	software1	95.91
32. ÚFAL – UDPipe 1.2 (Praha)               	software1	95.56
33. TRL (Tokyo)                             	software1	84.67
</pre>



### hsb

<pre>
 1. Uppsala (Uppsala)                       	software1	91.65
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	90.69
    ECNU (Shanghai)                         	software1	90.69
    ParisNLP (Paris)                        	software1	90.69
    darc (Tübingen)                         	software1	90.69
    IIT Kharagpur (Kharagpur)               	software3	90.69
    NAIST SATO (Nara)                       	software1	90.69
    Orange – Deskiñ (Lannion)               	software1	90.69
    UParse (Edinburgh)                      	software1	90.69
    LIMSI-LIPN (Paris)                      	software2	90.69
    MQuni (Sydney)                          	software2	90.69
    LyS-FASTPARSE (A Coruña)                	software5	90.69
    TurkuNLP (Turku)                        	software1	90.69
    LATTICE (Paris)                         	software7	90.69
    naistCL (Nara)                          	software1	90.69
    UALING (Tucson)                         	software1	90.69
    Koç University (İstanbul)               	software3	90.69
    BASELINE UDPipe 1.1 (Praha)             	software2	90.69
    ÚFAL – UDPipe 1.2 (Praha)               	software1	90.69
    Stanford (Stanford)                     	software1	90.69
    METU (Ankara)                           	software2	90.69
    C2L2 (Ithaca)                           	software5	90.69
    MetaRomance (Santiago de Compostela)    	software1	90.69
    HIT-SCIR (Harbin)                       	software4	90.69
    CLCL (Genève)                           	software2	90.69
    OpenU NLP Lab (Ra'anana)                	software6	90.69
    RACAI (București)                       	software1	90.69
    IMS (Stuttgart)                         	software2	90.69
    Mengest (Shanghai)                      	software1	90.69
30. fbaml (Palo Alto)                       	software1	72.93
31. TRL (Tokyo)                             	software1	68.23
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hu

<pre>
 1. Uppsala (Uppsala)                       	software1	96.56
 2. darc (Tübingen)                         	software1	95.80
    HIT-SCIR (Harbin)                       	software4	95.80
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	95.54
 5. fbaml (Palo Alto)                       	software1	94.10
 6. Wenba-NLU (Wuhan)                       	software1	93.85
    ECNU (Shanghai)                         	software1	93.85
    ParisNLP (Paris)                        	software1	93.85
    IIT Kharagpur (Kharagpur)               	software3	93.85
    CLCL (Genève)                           	software1	93.85
    NAIST SATO (Nara)                       	software1	93.85
    Orange – Deskiñ (Lannion)               	software1	93.85
    UParse (Edinburgh)                      	software1	93.85
    LIMSI-LIPN (Paris)                      	software2	93.85
    MQuni (Sydney)                          	software2	93.85
    LyS-FASTPARSE (A Coruña)                	software5	93.85
    TurkuNLP (Turku)                        	software1	93.85
    LATTICE (Paris)                         	software7	93.85
    naistCL (Nara)                          	software1	93.85
    UALING (Tucson)                         	software1	93.85
    Koç University (İstanbul)               	software3	93.85
    BASELINE UDPipe 1.1 (Praha)             	software2	93.85
    Stanford (Stanford)                     	software1	93.85
    METU (Ankara)                           	software2	93.85
    C2L2 (Ithaca)                           	software5	93.85
    MetaRomance (Santiago de Compostela)    	software1	93.85
    UT (Tartu)                              	software1	93.85
    OpenU NLP Lab (Ra'anana)                	software6	93.85
    IMS (Stuttgart)                         	software2	93.85
    Mengest (Shanghai)                      	software1	93.85
31. Wanghao-ftd-SJTU (Shanghai)             	software2	92.82
32. RACAI (București)                       	software1	89.75
33. TRL (Tokyo)                             	software1	88.86
</pre>



### id

<pre>
 1. Uppsala (Uppsala)                       	software1	92.66
 2. fbaml (Palo Alto)                       	software1	92.14
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	91.73
 4. Wenba-NLU (Wuhan)                       	software1	91.15
    ECNU (Shanghai)                         	software1	91.15
    ParisNLP (Paris)                        	software1	91.15
    IIT Kharagpur (Kharagpur)               	software3	91.15
    NAIST SATO (Nara)                       	software1	91.15
    Orange – Deskiñ (Lannion)               	software1	91.15
    UParse (Edinburgh)                      	software1	91.15
    LIMSI-LIPN (Paris)                      	software2	91.15
    MQuni (Sydney)                          	software2	91.15
    LyS-FASTPARSE (A Coruña)                	software5	91.15
    TurkuNLP (Turku)                        	software1	91.15
    LATTICE (Paris)                         	software7	91.15
    naistCL (Nara)                          	software1	91.15
    UALING (Tucson)                         	software1	91.15
    Koç University (İstanbul)               	software3	91.15
    BASELINE UDPipe 1.1 (Praha)             	software2	91.15
    Stanford (Stanford)                     	software1	91.15
    METU (Ankara)                           	software2	91.15
    C2L2 (Ithaca)                           	software5	91.15
    MetaRomance (Santiago de Compostela)    	software1	91.15
    UT (Tartu)                              	software1	91.15
    CLCL (Genève)                           	software2	91.15
    OpenU NLP Lab (Ra'anana)                	software6	91.15
    IMS (Stuttgart)                         	software2	91.15
    Mengest (Shanghai)                      	software1	91.15
29. Wanghao-ftd-SJTU (Shanghai)             	software2	90.73
30. darc (Tübingen)                         	software1	90.22
    HIT-SCIR (Harbin)                       	software4	90.22
32. RACAI (București)                       	software1	88.41
33. TRL (Tokyo)                             	software1	85.37
</pre>



### it

<pre>
 1. Uppsala (Uppsala)                       	software1	99.07
 2. ParisNLP (Paris)                        	software1	98.76
    fbaml (Palo Alto)                       	software1	98.76
 4. RACAI (București)                       	software1	98.45
 5. darc (Tübingen)                         	software1	97.41
    HIT-SCIR (Harbin)                       	software4	97.41
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	97.11
 8. Wenba-NLU (Wuhan)                       	software1	97.10
    IIT Kharagpur (Kharagpur)               	software3	97.10
    NAIST SATO (Nara)                       	software1	97.10
    Orange – Deskiñ (Lannion)               	software1	97.10
    UParse (Edinburgh)                      	software1	97.10
    LIMSI-LIPN (Paris)                      	software2	97.10
    MQuni (Sydney)                          	software2	97.10
    LyS-FASTPARSE (A Coruña)                	software5	97.10
    TurkuNLP (Turku)                        	software1	97.10
    LATTICE (Paris)                         	software7	97.10
    naistCL (Nara)                          	software1	97.10
    UALING (Tucson)                         	software1	97.10
    Koç University (İstanbul)               	software3	97.10
    BASELINE UDPipe 1.1 (Praha)             	software2	97.10
    Stanford (Stanford)                     	software1	97.10
    METU (Ankara)                           	software2	97.10
    C2L2 (Ithaca)                           	software5	97.10
    MetaRomance (Santiago de Compostela)    	software1	97.10
    CLCL (Genève)                           	software2	97.10
    OpenU NLP Lab (Ra'anana)                	software6	97.10
    IMS (Stuttgart)                         	software2	97.10
    Mengest (Shanghai)                      	software1	97.10
30. Wanghao-ftd-SJTU (Shanghai)             	software2	96.91
31. TRL (Tokyo)                             	software1	89.05
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### it_pud

<pre>
 1. TRL (Tokyo)                             	software1	97.81
 2. ParisNLP (Paris)                        	software1	96.58
    darc (Tübingen)                         	software1	96.58
    IIT Kharagpur (Kharagpur)               	software3	96.58
    CLCL (Genève)                           	software1	96.58
    NAIST SATO (Nara)                       	software1	96.58
    Orange – Deskiñ (Lannion)               	software1	96.58
    UParse (Edinburgh)                      	software1	96.58
    LIMSI-LIPN (Paris)                      	software2	96.58
    MQuni (Sydney)                          	software2	96.58
    LyS-FASTPARSE (A Coruña)                	software5	96.58
    TurkuNLP (Turku)                        	software1	96.58
    LATTICE (Paris)                         	software7	96.58
    naistCL (Nara)                          	software1	96.58
    UALING (Tucson)                         	software1	96.58
    Koç University (İstanbul)               	software3	96.58
    BASELINE UDPipe 1.1 (Praha)             	software2	96.58
    Stanford (Stanford)                     	software1	96.58
    METU (Ankara)                           	software2	96.58
    C2L2 (Ithaca)                           	software5	96.58
    MetaRomance (Santiago de Compostela)    	software1	96.58
    OpenU NLP Lab (Ra'anana)                	software6	96.58
    IMS (Stuttgart)                         	software2	96.58
    Mengest (Shanghai)                      	software1	96.58
25. RACAI (București)                       	software1	94.56
26. HIT-SCIR (Harbin)                       	software4	94.38
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.11
28. fbaml (Palo Alto)                       	software1	93.97
29. Uppsala (Uppsala)                       	software1	93.39
30. Wanghao-ftd-SJTU (Shanghai)             	software2	93.05
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ja

<pre>
 1. HIT-SCIR (Harbin)                       	software4	95.11
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	95.01
    darc (Tübingen)                         	software1	95.01
    ÚFAL – UDPipe 1.2 (Praha)               	software1	95.01
 5. Wenba-NLU (Wuhan)                       	software1	94.92
    ECNU (Shanghai)                         	software1	94.92
    ParisNLP (Paris)                        	software1	94.92
    IIT Kharagpur (Kharagpur)               	software3	94.92
    Uppsala (Uppsala)                       	software1	94.92
    NAIST SATO (Nara)                       	software1	94.92
    Orange – Deskiñ (Lannion)               	software1	94.92
    UParse (Edinburgh)                      	software1	94.92
    LIMSI-LIPN (Paris)                      	software2	94.92
    MQuni (Sydney)                          	software2	94.92
    LyS-FASTPARSE (A Coruña)                	software5	94.92
    TurkuNLP (Turku)                        	software1	94.92
    LATTICE (Paris)                         	software7	94.92
    naistCL (Nara)                          	software1	94.92
    UALING (Tucson)                         	software1	94.92
    Koç University (İstanbul)               	software3	94.92
    BASELINE UDPipe 1.1 (Praha)             	software2	94.92
    Stanford (Stanford)                     	software1	94.92
    METU (Ankara)                           	software2	94.92
    C2L2 (Ithaca)                           	software5	94.92
    MetaRomance (Santiago de Compostela)    	software1	94.92
    UT (Tartu)                              	software1	94.92
    CLCL (Genève)                           	software2	94.92
    OpenU NLP Lab (Ra'anana)                	software6	94.92
    IMS (Stuttgart)                         	software2	94.92
    Mengest (Shanghai)                      	software1	94.92
31. fbaml (Palo Alto)                       	software1	94.64
32. TRL (Tokyo)                             	software1	94.56
33. RACAI (București)                       	software1	93.18
</pre>



### ja_pud

<pre>
 1. TRL (Tokyo)                             	software1	97.52
 2. Uppsala (Uppsala)                       	software1	97.31
 3. fbaml (Palo Alto)                       	software1	96.60
 4. RACAI (București)                       	software1	96.21
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	95.04
    ÚFAL – UDPipe 1.2 (Praha)               	software1	95.04
 7. HIT-SCIR (Harbin)                       	software4	94.99
 8. ECNU (Shanghai)                         	software1	94.89
    ParisNLP (Paris)                        	software1	94.89
    darc (Tübingen)                         	software1	94.89
    IIT Kharagpur (Kharagpur)               	software3	94.89
    CLCL (Genève)                           	software1	94.89
    NAIST SATO (Nara)                       	software1	94.89
    Orange – Deskiñ (Lannion)               	software1	94.89
    UParse (Edinburgh)                      	software1	94.89
    LIMSI-LIPN (Paris)                      	software2	94.89
    MQuni (Sydney)                          	software2	94.89
    LyS-FASTPARSE (A Coruña)                	software5	94.89
    TurkuNLP (Turku)                        	software1	94.89
    LATTICE (Paris)                         	software7	94.89
    naistCL (Nara)                          	software1	94.89
    UALING (Tucson)                         	software1	94.89
    Koç University (İstanbul)               	software3	94.89
    BASELINE UDPipe 1.1 (Praha)             	software2	94.89
    Stanford (Stanford)                     	software1	94.89
    METU (Ankara)                           	software2	94.89
    C2L2 (Ithaca)                           	software5	94.89
    MetaRomance (Santiago de Compostela)    	software1	94.89
    UT (Tartu)                              	software1	94.89
    OpenU NLP Lab (Ra'anana)                	software6	94.89
    IMS (Stuttgart)                         	software2	94.89
    Mengest (Shanghai)                      	software1	94.89
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### kk

<pre>
 1. TRL (Tokyo)                             	software1	89.35
 2. Uppsala (Uppsala)                       	software1	87.52
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	81.83
 4. RACAI (București)                       	software1	81.50
 5. ParisNLP (Paris)                        	software1	81.38
    IIT Kharagpur (Kharagpur)               	software3	81.38
    NAIST SATO (Nara)                       	software1	81.38
    Orange – Deskiñ (Lannion)               	software1	81.38
    UParse (Edinburgh)                      	software1	81.38
    LIMSI-LIPN (Paris)                      	software2	81.38
    MQuni (Sydney)                          	software2	81.38
    LyS-FASTPARSE (A Coruña)                	software5	81.38
    TurkuNLP (Turku)                        	software1	81.38
    LATTICE (Paris)                         	software7	81.38
    naistCL (Nara)                          	software1	81.38
    UALING (Tucson)                         	software1	81.38
    Koç University (İstanbul)               	software3	81.38
    BASELINE UDPipe 1.1 (Praha)             	software2	81.38
    Stanford (Stanford)                     	software1	81.38
    METU (Ankara)                           	software2	81.38
    C2L2 (Ithaca)                           	software5	81.38
    MetaRomance (Santiago de Compostela)    	software1	81.38
    CLCL (Genève)                           	software2	81.38
    OpenU NLP Lab (Ra'anana)                	software6	81.38
    IMS (Stuttgart)                         	software2	81.38
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	81.23
27. HIT-SCIR (Harbin)                       	software4	80.65
28. darc (Tübingen)                         	software1	80.46
29. fbaml (Palo Alto)                       	software1	71.84
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. UT (Tartu)                              	software1	 0.00
33. Mengest (Shanghai)                      	software1	 0.00
</pre>



### kmr

<pre>
 1. TRL (Tokyo)                             	software1	98.64
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	97.02
    ParisNLP (Paris)                        	software1	97.02
    darc (Tübingen)                         	software1	97.02
    IIT Kharagpur (Kharagpur)               	software3	97.02
    NAIST SATO (Nara)                       	software1	97.02
    Orange – Deskiñ (Lannion)               	software1	97.02
    UParse (Edinburgh)                      	software1	97.02
    LIMSI-LIPN (Paris)                      	software2	97.02
    MQuni (Sydney)                          	software2	97.02
    LyS-FASTPARSE (A Coruña)                	software5	97.02
    TurkuNLP (Turku)                        	software1	97.02
    LATTICE (Paris)                         	software7	97.02
    naistCL (Nara)                          	software1	97.02
    UALING (Tucson)                         	software1	97.02
    Koç University (İstanbul)               	software3	97.02
    BASELINE UDPipe 1.1 (Praha)             	software2	97.02
    ÚFAL – UDPipe 1.2 (Praha)               	software1	97.02
    Stanford (Stanford)                     	software1	97.02
    METU (Ankara)                           	software2	97.02
    C2L2 (Ithaca)                           	software5	97.02
    MetaRomance (Santiago de Compostela)    	software1	97.02
    HIT-SCIR (Harbin)                       	software4	97.02
    CLCL (Genève)                           	software2	97.02
    OpenU NLP Lab (Ra'anana)                	software6	97.02
    RACAI (București)                       	software1	97.02
    IMS (Stuttgart)                         	software2	97.02
    Mengest (Shanghai)                      	software1	97.02
29. Uppsala (Uppsala)                       	software1	94.49
30. fbaml (Palo Alto)                       	software1	92.91
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ko

<pre>
 1. ECNU (Shanghai)                         	software1	93.05
    ParisNLP (Paris)                        	software1	93.05
    IIT Kharagpur (Kharagpur)               	software3	93.05
    NAIST SATO (Nara)                       	software1	93.05
    Orange – Deskiñ (Lannion)               	software1	93.05
    UParse (Edinburgh)                      	software1	93.05
    LIMSI-LIPN (Paris)                      	software2	93.05
    MQuni (Sydney)                          	software2	93.05
    LyS-FASTPARSE (A Coruña)                	software5	93.05
    TurkuNLP (Turku)                        	software1	93.05
    LATTICE (Paris)                         	software7	93.05
    naistCL (Nara)                          	software1	93.05
    UALING (Tucson)                         	software1	93.05
    Koç University (İstanbul)               	software3	93.05
    BASELINE UDPipe 1.1 (Praha)             	software2	93.05
    Stanford (Stanford)                     	software1	93.05
    METU (Ankara)                           	software2	93.05
    C2L2 (Ithaca)                           	software5	93.05
    MetaRomance (Santiago de Compostela)    	software1	93.05
    UT (Tartu)                              	software1	93.05
    CLCL (Genève)                           	software2	93.05
    OpenU NLP Lab (Ra'anana)                	software6	93.05
    RACAI (București)                       	software1	93.05
    IMS (Stuttgart)                         	software2	93.05
    Mengest (Shanghai)                      	software1	93.05
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	92.41
27. Uppsala (Uppsala)                       	software1	92.39
28. darc (Tübingen)                         	software1	92.01
    HIT-SCIR (Harbin)                       	software4	92.01
30. fbaml (Palo Alto)                       	software1	90.99
31. Wanghao-ftd-SJTU (Shanghai)             	software2	90.05
32. TRL (Tokyo)                             	software1	69.87
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la

<pre>
 1. RACAI (București)                       	software1	99.20
 2. darc (Tübingen)                         	software1	98.72
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.56
 4. fbaml (Palo Alto)                       	software1	98.14
 5. ECNU (Shanghai)                         	software1	98.09
    ParisNLP (Paris)                        	software1	98.09
    IIT Kharagpur (Kharagpur)               	software3	98.09
    NAIST SATO (Nara)                       	software1	98.09
    Orange – Deskiñ (Lannion)               	software1	98.09
    UParse (Edinburgh)                      	software1	98.09
    LIMSI-LIPN (Paris)                      	software2	98.09
    MQuni (Sydney)                          	software2	98.09
    LyS-FASTPARSE (A Coruña)                	software5	98.09
    TurkuNLP (Turku)                        	software1	98.09
    LATTICE (Paris)                         	software7	98.09
    naistCL (Nara)                          	software1	98.09
    UALING (Tucson)                         	software1	98.09
    Koç University (İstanbul)               	software3	98.09
    BASELINE UDPipe 1.1 (Praha)             	software2	98.09
    Stanford (Stanford)                     	software1	98.09
    METU (Ankara)                           	software2	98.09
    C2L2 (Ithaca)                           	software5	98.09
    MetaRomance (Santiago de Compostela)    	software1	98.09
    UT (Tartu)                              	software1	98.09
    CLCL (Genève)                           	software2	98.09
    OpenU NLP Lab (Ra'anana)                	software6	98.09
    Mengest (Shanghai)                      	software1	98.09
28. Uppsala (Uppsala)                       	software1	98.04
29. HIT-SCIR (Harbin)                       	software4	97.98
30. Wanghao-ftd-SJTU (Shanghai)             	software2	97.52
31. IMS (Stuttgart)                         	software2	93.75
32. TRL (Tokyo)                             	software1	62.03
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_ittb

<pre>
 1. Uppsala (Uppsala)                       	software1	94.34
 2. IMS (Stuttgart)                         	software2	93.37
 3. ECNU (Shanghai)                         	software1	93.24
    IIT Kharagpur (Kharagpur)               	software3	93.24
    CLCL (Genève)                           	software1	93.24
    NAIST SATO (Nara)                       	software1	93.24
    Orange – Deskiñ (Lannion)               	software1	93.24
    UParse (Edinburgh)                      	software1	93.24
    LIMSI-LIPN (Paris)                      	software2	93.24
    MQuni (Sydney)                          	software2	93.24
    LyS-FASTPARSE (A Coruña)                	software5	93.24
    TurkuNLP (Turku)                        	software1	93.24
    LATTICE (Paris)                         	software7	93.24
    naistCL (Nara)                          	software1	93.24
    UALING (Tucson)                         	software1	93.24
    Koç University (İstanbul)               	software3	93.24
    BASELINE UDPipe 1.1 (Praha)             	software2	93.24
    Stanford (Stanford)                     	software1	93.24
    METU (Ankara)                           	software2	93.24
    C2L2 (Ithaca)                           	software5	93.24
    MetaRomance (Santiago de Compostela)    	software1	93.24
    UT (Tartu)                              	software1	93.24
    OpenU NLP Lab (Ra'anana)                	software6	93.24
    Mengest (Shanghai)                      	software1	93.24
25. ParisNLP (Paris)                        	software1	93.19
26. Wanghao-ftd-SJTU (Shanghai)             	software2	93.09
27. fbaml (Palo Alto)                       	software1	92.91
28. RACAI (București)                       	software1	83.10
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	82.58
30. HIT-SCIR (Harbin)                       	software4	82.50
31. darc (Tübingen)                         	software1	81.53
32. TRL (Tokyo)                             	software1	74.82
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_proiel

<pre>
 1. IMS (Stuttgart)                         	software2	40.63
 2. HIT-SCIR (Harbin)                       	software4	32.93
 3. Uppsala (Uppsala)                       	software1	30.24
 4. fbaml (Palo Alto)                       	software1	28.28
 5. darc (Tübingen)                         	software1	26.61
 6. Wenba-NLU (Wuhan)                       	software1	25.80
    ParisNLP (Paris)                        	software1	25.80
    IIT Kharagpur (Kharagpur)               	software3	25.80
    CLCL (Genève)                           	software1	25.80
    NAIST SATO (Nara)                       	software1	25.80
    Orange – Deskiñ (Lannion)               	software1	25.80
    UParse (Edinburgh)                      	software1	25.80
    LIMSI-LIPN (Paris)                      	software2	25.80
    MQuni (Sydney)                          	software2	25.80
    LyS-FASTPARSE (A Coruña)                	software5	25.80
    TurkuNLP (Turku)                        	software1	25.80
    LATTICE (Paris)                         	software7	25.80
    naistCL (Nara)                          	software1	25.80
    UALING (Tucson)                         	software1	25.80
    Koç University (İstanbul)               	software3	25.80
    BASELINE UDPipe 1.1 (Praha)             	software2	25.80
    Stanford (Stanford)                     	software1	25.80
    METU (Ankara)                           	software2	25.80
    C2L2 (Ithaca)                           	software5	25.80
    MetaRomance (Santiago de Compostela)    	software1	25.80
    OpenU NLP Lab (Ra'anana)                	software6	25.80
    RACAI (București)                       	software1	25.80
    Mengest (Shanghai)                      	software1	25.80
29. Wanghao-ftd-SJTU (Shanghai)             	software2	23.68
30. ÚFAL – UDPipe 1.2 (Praha)               	software1	19.56
31. TRL (Tokyo)                             	software1	 1.25
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### lv

<pre>
 1. fbaml (Palo Alto)                       	software1	98.80
 2. Wenba-NLU (Wuhan)                       	software1	98.59
    ECNU (Shanghai)                         	software1	98.59
    ParisNLP (Paris)                        	software1	98.59
    IIT Kharagpur (Kharagpur)               	software3	98.59
    CLCL (Genève)                           	software1	98.59
    NAIST SATO (Nara)                       	software1	98.59
    Orange – Deskiñ (Lannion)               	software1	98.59
    UParse (Edinburgh)                      	software1	98.59
    LIMSI-LIPN (Paris)                      	software2	98.59
    MQuni (Sydney)                          	software2	98.59
    LyS-FASTPARSE (A Coruña)                	software5	98.59
    TurkuNLP (Turku)                        	software1	98.59
    LATTICE (Paris)                         	software7	98.59
    naistCL (Nara)                          	software1	98.59
    UALING (Tucson)                         	software1	98.59
    Koç University (İstanbul)               	software3	98.59
    BASELINE UDPipe 1.1 (Praha)             	software2	98.59
    Stanford (Stanford)                     	software1	98.59
    METU (Ankara)                           	software2	98.59
    C2L2 (Ithaca)                           	software5	98.59
    MetaRomance (Santiago de Compostela)    	software1	98.59
    UT (Tartu)                              	software1	98.59
    OpenU NLP Lab (Ra'anana)                	software6	98.59
    IMS (Stuttgart)                         	software2	98.59
    Mengest (Shanghai)                      	software1	98.59
27. darc (Tübingen)                         	software1	98.53
    HIT-SCIR (Harbin)                       	software4	98.53
29. Wanghao-ftd-SJTU (Shanghai)             	software2	98.48
30. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.32
31. TRL (Tokyo)                             	software1	97.36
32. Uppsala (Uppsala)                       	software1	93.45
33. RACAI (București)                       	software1	93.30
</pre>



### nl

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	77.14
    ECNU (Shanghai)                         	software1	77.14
    ParisNLP (Paris)                        	software1	77.14
    IIT Kharagpur (Kharagpur)               	software3	77.14
    CLCL (Genève)                           	software1	77.14
    NAIST SATO (Nara)                       	software1	77.14
    Orange – Deskiñ (Lannion)               	software1	77.14
    UParse (Edinburgh)                      	software1	77.14
    LIMSI-LIPN (Paris)                      	software2	77.14
    MQuni (Sydney)                          	software2	77.14
    LyS-FASTPARSE (A Coruña)                	software5	77.14
    TurkuNLP (Turku)                        	software1	77.14
    LATTICE (Paris)                         	software7	77.14
    naistCL (Nara)                          	software1	77.14
    UALING (Tucson)                         	software1	77.14
    Koç University (İstanbul)               	software3	77.14
    BASELINE UDPipe 1.1 (Praha)             	software2	77.14
    Stanford (Stanford)                     	software1	77.14
    METU (Ankara)                           	software2	77.14
    C2L2 (Ithaca)                           	software5	77.14
    MetaRomance (Santiago de Compostela)    	software1	77.14
    UT (Tartu)                              	software1	77.14
    OpenU NLP Lab (Ra'anana)                	software6	77.14
    IMS (Stuttgart)                         	software2	77.14
    Mengest (Shanghai)                      	software1	77.14
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	76.95
27. darc (Tübingen)                         	software1	76.90
    HIT-SCIR (Harbin)                       	software4	76.90
29. fbaml (Palo Alto)                       	software1	76.83
30. Uppsala (Uppsala)                       	software1	75.15
31. RACAI (București)                       	software1	74.52
32. TRL (Tokyo)                             	software1	72.92
33. Wanghao-ftd-SJTU (Shanghai)             	software2	72.19
</pre>



### nl_lassysmall

<pre>
 1. Uppsala (Uppsala)                       	software1	85.33
 2. HIT-SCIR (Harbin)                       	software4	84.73
 3. IMS (Stuttgart)                         	software2	84.59
 4. fbaml (Palo Alto)                       	software1	82.80
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	81.83
 6. darc (Tübingen)                         	software1	79.26
 7. Wenba-NLU (Wuhan)                       	software1	78.62
    ECNU (Shanghai)                         	software1	78.62
    ParisNLP (Paris)                        	software1	78.62
    IIT Kharagpur (Kharagpur)               	software3	78.62
    CLCL (Genève)                           	software1	78.62
    NAIST SATO (Nara)                       	software1	78.62
    Orange – Deskiñ (Lannion)               	software1	78.62
    UParse (Edinburgh)                      	software1	78.62
    LIMSI-LIPN (Paris)                      	software2	78.62
    MQuni (Sydney)                          	software2	78.62
    LyS-FASTPARSE (A Coruña)                	software5	78.62
    TurkuNLP (Turku)                        	software1	78.62
    LATTICE (Paris)                         	software7	78.62
    naistCL (Nara)                          	software1	78.62
    UALING (Tucson)                         	software1	78.62
    Koç University (İstanbul)               	software3	78.62
    BASELINE UDPipe 1.1 (Praha)             	software2	78.62
    Stanford (Stanford)                     	software1	78.62
    METU (Ankara)                           	software2	78.62
    C2L2 (Ithaca)                           	software5	78.62
    MetaRomance (Santiago de Compostela)    	software1	78.62
    UT (Tartu)                              	software1	78.62
    OpenU NLP Lab (Ra'anana)                	software6	78.62
    RACAI (București)                       	software1	78.62
    Mengest (Shanghai)                      	software1	78.62
32. Wanghao-ftd-SJTU (Shanghai)             	software2	74.02
33. TRL (Tokyo)                             	software1	33.65
</pre>



### no_bokmaal

<pre>
 1. Uppsala (Uppsala)                       	software1	96.44
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	96.38
 3. fbaml (Palo Alto)                       	software1	96.26
 4. darc (Tübingen)                         	software1	96.03
    HIT-SCIR (Harbin)                       	software4	96.03
 6. Wenba-NLU (Wuhan)                       	software1	95.76
    ParisNLP (Paris)                        	software1	95.76
    IIT Kharagpur (Kharagpur)               	software3	95.76
    CLCL (Genève)                           	software1	95.76
    NAIST SATO (Nara)                       	software1	95.76
    Orange – Deskiñ (Lannion)               	software1	95.76
    UParse (Edinburgh)                      	software1	95.76
    LIMSI-LIPN (Paris)                      	software2	95.76
    MQuni (Sydney)                          	software2	95.76
    LyS-FASTPARSE (A Coruña)                	software5	95.76
    TurkuNLP (Turku)                        	software1	95.76
    LATTICE (Paris)                         	software7	95.76
    naistCL (Nara)                          	software1	95.76
    UALING (Tucson)                         	software1	95.76
    Koç University (İstanbul)               	software3	95.76
    BASELINE UDPipe 1.1 (Praha)             	software2	95.76
    Stanford (Stanford)                     	software1	95.76
    METU (Ankara)                           	software2	95.76
    C2L2 (Ithaca)                           	software5	95.76
    MetaRomance (Santiago de Compostela)    	software1	95.76
    OpenU NLP Lab (Ra'anana)                	software6	95.76
    IMS (Stuttgart)                         	software2	95.76
    Mengest (Shanghai)                      	software1	95.76
29. Wanghao-ftd-SJTU (Shanghai)             	software2	95.63
30. RACAI (București)                       	software1	93.11
31. TRL (Tokyo)                             	software1	86.72
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### no_nynorsk

<pre>
 1. Uppsala (Uppsala)                       	software1	94.56
 2. darc (Tübingen)                         	software1	92.13
    HIT-SCIR (Harbin)                       	software4	92.13
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	92.08
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	91.65
 6. Wenba-NLU (Wuhan)                       	software1	91.23
    ParisNLP (Paris)                        	software1	91.23
    IIT Kharagpur (Kharagpur)               	software3	91.23
    CLCL (Genève)                           	software1	91.23
    NAIST SATO (Nara)                       	software1	91.23
    Orange – Deskiñ (Lannion)               	software1	91.23
    UParse (Edinburgh)                      	software1	91.23
    LIMSI-LIPN (Paris)                      	software2	91.23
    MQuni (Sydney)                          	software2	91.23
    LyS-FASTPARSE (A Coruña)                	software5	91.23
    TurkuNLP (Turku)                        	software1	91.23
    LATTICE (Paris)                         	software7	91.23
    naistCL (Nara)                          	software1	91.23
    UALING (Tucson)                         	software1	91.23
    Koç University (İstanbul)               	software3	91.23
    BASELINE UDPipe 1.1 (Praha)             	software2	91.23
    Stanford (Stanford)                     	software1	91.23
    METU (Ankara)                           	software2	91.23
    C2L2 (Ithaca)                           	software5	91.23
    MetaRomance (Santiago de Compostela)    	software1	91.23
    OpenU NLP Lab (Ra'anana)                	software6	91.23
    RACAI (București)                       	software1	91.23
    IMS (Stuttgart)                         	software2	91.23
    Mengest (Shanghai)                      	software1	91.23
30. fbaml (Palo Alto)                       	software1	80.51
31. TRL (Tokyo)                             	software1	80.12
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pl

<pre>
 1. RACAI (București)                       	software1	99.59
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.18
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	98.91
    Wenba-NLU (Wuhan)                       	software1	98.91
    ECNU (Shanghai)                         	software1	98.91
    ParisNLP (Paris)                        	software1	98.91
    darc (Tübingen)                         	software1	98.91
    IIT Kharagpur (Kharagpur)               	software3	98.91
    Uppsala (Uppsala)                       	software1	98.91
    CLCL (Genève)                           	software1	98.91
    NAIST SATO (Nara)                       	software1	98.91
    Orange – Deskiñ (Lannion)               	software1	98.91
    UParse (Edinburgh)                      	software1	98.91
    LIMSI-LIPN (Paris)                      	software2	98.91
    MQuni (Sydney)                          	software2	98.91
    LyS-FASTPARSE (A Coruña)                	software5	98.91
    TurkuNLP (Turku)                        	software1	98.91
    LATTICE (Paris)                         	software7	98.91
    naistCL (Nara)                          	software1	98.91
    UALING (Tucson)                         	software1	98.91
    Koç University (İstanbul)               	software3	98.91
    BASELINE UDPipe 1.1 (Praha)             	software2	98.91
    Stanford (Stanford)                     	software1	98.91
    METU (Ankara)                           	software2	98.91
    C2L2 (Ithaca)                           	software5	98.91
    MetaRomance (Santiago de Compostela)    	software1	98.91
    HIT-SCIR (Harbin)                       	software4	98.91
    OpenU NLP Lab (Ra'anana)                	software6	98.91
    IMS (Stuttgart)                         	software2	98.91
    Mengest (Shanghai)                      	software1	98.91
31. fbaml (Palo Alto)                       	software1	98.73
32. TRL (Tokyo)                             	software1	97.83
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt

<pre>
 1. fbaml (Palo Alto)                       	software1	91.67
 2. Uppsala (Uppsala)                       	software1	90.33
 3. darc (Tübingen)                         	software1	89.95
    HIT-SCIR (Harbin)                       	software4	89.95
 5. Wenba-NLU (Wuhan)                       	software1	89.79
    ParisNLP (Paris)                        	software1	89.79
    IIT Kharagpur (Kharagpur)               	software3	89.79
    CLCL (Genève)                           	software1	89.79
    NAIST SATO (Nara)                       	software1	89.79
    Orange – Deskiñ (Lannion)               	software1	89.79
    UParse (Edinburgh)                      	software1	89.79
    LIMSI-LIPN (Paris)                      	software2	89.79
    MQuni (Sydney)                          	software2	89.79
    LyS-FASTPARSE (A Coruña)                	software5	89.79
    TurkuNLP (Turku)                        	software1	89.79
    LATTICE (Paris)                         	software7	89.79
    naistCL (Nara)                          	software1	89.79
    UALING (Tucson)                         	software1	89.79
    Koç University (İstanbul)               	software3	89.79
    BASELINE UDPipe 1.1 (Praha)             	software2	89.79
    Stanford (Stanford)                     	software1	89.79
    METU (Ankara)                           	software2	89.79
    C2L2 (Ithaca)                           	software5	89.79
    MetaRomance (Santiago de Compostela)    	software1	89.79
    OpenU NLP Lab (Ra'anana)                	software6	89.79
    RACAI (București)                       	software1	89.79
    IMS (Stuttgart)                         	software2	89.79
    Mengest (Shanghai)                      	software1	89.79
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	89.24
30. Wanghao-ftd-SJTU (Shanghai)             	software2	88.08
31. TRL (Tokyo)                             	software1	77.79
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_br

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	96.84
    ParisNLP (Paris)                        	software1	96.84
    IIT Kharagpur (Kharagpur)               	software3	96.84
    CLCL (Genève)                           	software1	96.84
    NAIST SATO (Nara)                       	software1	96.84
    Orange – Deskiñ (Lannion)               	software1	96.84
    UParse (Edinburgh)                      	software1	96.84
    LIMSI-LIPN (Paris)                      	software2	96.84
    MQuni (Sydney)                          	software2	96.84
    LyS-FASTPARSE (A Coruña)                	software5	96.84
    TurkuNLP (Turku)                        	software1	96.84
    LATTICE (Paris)                         	software7	96.84
    naistCL (Nara)                          	software1	96.84
    UALING (Tucson)                         	software1	96.84
    Koç University (İstanbul)               	software3	96.84
    BASELINE UDPipe 1.1 (Praha)             	software2	96.84
    Stanford (Stanford)                     	software1	96.84
    METU (Ankara)                           	software2	96.84
    C2L2 (Ithaca)                           	software5	96.84
    MetaRomance (Santiago de Compostela)    	software1	96.84
    OpenU NLP Lab (Ra'anana)                	software6	96.84
    IMS (Stuttgart)                         	software2	96.84
    Mengest (Shanghai)                      	software1	96.84
24. Wanghao-ftd-SJTU (Shanghai)             	software2	96.79
25. darc (Tübingen)                         	software1	96.72
    HIT-SCIR (Harbin)                       	software4	96.72
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	96.71
28. fbaml (Palo Alto)                       	software1	96.63
29. Uppsala (Uppsala)                       	software1	96.51
30. RACAI (București)                       	software1	95.51
31. TRL (Tokyo)                             	software1	92.65
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_pud

<pre>
 1. fbaml (Palo Alto)                       	software1	97.32
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	95.94
 3. TRL (Tokyo)                             	software1	95.80
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	95.69
 5. HIT-SCIR (Harbin)                       	software4	95.66
 6. ParisNLP (Paris)                        	software1	95.65
    darc (Tübingen)                         	software1	95.65
    IIT Kharagpur (Kharagpur)               	software3	95.65
    CLCL (Genève)                           	software1	95.65
    NAIST SATO (Nara)                       	software1	95.65
    Orange – Deskiñ (Lannion)               	software1	95.65
    UParse (Edinburgh)                      	software1	95.65
    LIMSI-LIPN (Paris)                      	software2	95.65
    MQuni (Sydney)                          	software2	95.65
    LyS-FASTPARSE (A Coruña)                	software5	95.65
    TurkuNLP (Turku)                        	software1	95.65
    LATTICE (Paris)                         	software7	95.65
    naistCL (Nara)                          	software1	95.65
    UALING (Tucson)                         	software1	95.65
    Koç University (İstanbul)               	software3	95.65
    BASELINE UDPipe 1.1 (Praha)             	software2	95.65
    Stanford (Stanford)                     	software1	95.65
    METU (Ankara)                           	software2	95.65
    C2L2 (Ithaca)                           	software5	95.65
    MetaRomance (Santiago de Compostela)    	software1	95.65
    OpenU NLP Lab (Ra'anana)                	software6	95.65
    RACAI (București)                       	software1	95.65
    IMS (Stuttgart)                         	software2	95.65
    Mengest (Shanghai)                      	software1	95.65
30. Uppsala (Uppsala)                       	software1	93.58
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ro

<pre>
 1. Uppsala (Uppsala)                       	software1	96.57
 2. fbaml (Palo Alto)                       	software1	94.79
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	94.34
 4. darc (Tübingen)                         	software1	93.91
    HIT-SCIR (Harbin)                       	software4	93.91
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	93.72
 7. ParisNLP (Paris)                        	software1	93.42
    IIT Kharagpur (Kharagpur)               	software3	93.42
    CLCL (Genève)                           	software1	93.42
    NAIST SATO (Nara)                       	software1	93.42
    Orange – Deskiñ (Lannion)               	software1	93.42
    UParse (Edinburgh)                      	software1	93.42
    LIMSI-LIPN (Paris)                      	software2	93.42
    MQuni (Sydney)                          	software2	93.42
    LyS-FASTPARSE (A Coruña)                	software5	93.42
    TurkuNLP (Turku)                        	software1	93.42
    LATTICE (Paris)                         	software7	93.42
    naistCL (Nara)                          	software1	93.42
    UALING (Tucson)                         	software1	93.42
    Koç University (İstanbul)               	software3	93.42
    BASELINE UDPipe 1.1 (Praha)             	software2	93.42
    Stanford (Stanford)                     	software1	93.42
    METU (Ankara)                           	software2	93.42
    C2L2 (Ithaca)                           	software5	93.42
    MetaRomance (Santiago de Compostela)    	software1	93.42
    UT (Tartu)                              	software1	93.42
    OpenU NLP Lab (Ra'anana)                	software6	93.42
    IMS (Stuttgart)                         	software2	93.42
    Mengest (Shanghai)                      	software1	93.42
30. RACAI (București)                       	software1	92.60
31. TRL (Tokyo)                             	software1	89.13
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### ru

<pre>
 1. Uppsala (Uppsala)                       	software1	97.16
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	96.59
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	96.42
    ParisNLP (Paris)                        	software1	96.42
    IIT Kharagpur (Kharagpur)               	software3	96.42
    CLCL (Genève)                           	software1	96.42
    NAIST SATO (Nara)                       	software1	96.42
    Orange – Deskiñ (Lannion)               	software1	96.42
    UParse (Edinburgh)                      	software1	96.42
    LIMSI-LIPN (Paris)                      	software2	96.42
    MQuni (Sydney)                          	software2	96.42
    LyS-FASTPARSE (A Coruña)                	software5	96.42
    TurkuNLP (Turku)                        	software1	96.42
    LATTICE (Paris)                         	software7	96.42
    naistCL (Nara)                          	software1	96.42
    UALING (Tucson)                         	software1	96.42
    Koç University (İstanbul)               	software3	96.42
    BASELINE UDPipe 1.1 (Praha)             	software2	96.42
    Stanford (Stanford)                     	software1	96.42
    METU (Ankara)                           	software2	96.42
    C2L2 (Ithaca)                           	software5	96.42
    MetaRomance (Santiago de Compostela)    	software1	96.42
    OpenU NLP Lab (Ra'anana)                	software6	96.42
    IMS (Stuttgart)                         	software2	96.42
    Mengest (Shanghai)                      	software1	96.42
26. fbaml (Palo Alto)                       	software1	95.75
27. RACAI (București)                       	software1	95.30
28. darc (Tübingen)                         	software1	95.21
    HIT-SCIR (Harbin)                       	software4	95.21
30. TRL (Tokyo)                             	software1	91.52
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ru_pud

<pre>
 1. ECNU (Shanghai)                         	software1	98.95
    ParisNLP (Paris)                        	software1	98.95
    darc (Tübingen)                         	software1	98.95
    IIT Kharagpur (Kharagpur)               	software3	98.95
    CLCL (Genève)                           	software1	98.95
    NAIST SATO (Nara)                       	software1	98.95
    Orange – Deskiñ (Lannion)               	software1	98.95
    UParse (Edinburgh)                      	software1	98.95
    LIMSI-LIPN (Paris)                      	software2	98.95
    MQuni (Sydney)                          	software2	98.95
    LyS-FASTPARSE (A Coruña)                	software5	98.95
    TurkuNLP (Turku)                        	software1	98.95
    LATTICE (Paris)                         	software7	98.95
    naistCL (Nara)                          	software1	98.95
    UALING (Tucson)                         	software1	98.95
    Koç University (İstanbul)               	software3	98.95
    BASELINE UDPipe 1.1 (Praha)             	software2	98.95
    Stanford (Stanford)                     	software1	98.95
    METU (Ankara)                           	software2	98.95
    C2L2 (Ithaca)                           	software5	98.95
    MetaRomance (Santiago de Compostela)    	software1	98.95
    UT (Tartu)                              	software1	98.95
    OpenU NLP Lab (Ra'anana)                	software6	98.95
    IMS (Stuttgart)                         	software2	98.95
    Mengest (Shanghai)                      	software1	98.95
26. Wanghao-ftd-SJTU (Shanghai)             	software2	98.80
27. Uppsala (Uppsala)                       	software1	98.66
28. HIT-SCIR (Harbin)                       	software4	98.65
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.51
30. fbaml (Palo Alto)                       	software1	97.23
31. RACAI (București)                       	software1	96.93
32. TRL (Tokyo)                             	software1	95.28
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### ru_syntagrus

<pre>
 1. Uppsala (Uppsala)                       	software1	98.64
 2. HIT-SCIR (Harbin)                       	software4	98.05
 3. darc (Tübingen)                         	software1	98.04
 4. RACAI (București)                       	software1	98.01
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	97.97
    fbaml (Palo Alto)                       	software1	97.97
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	97.86
 8. ParisNLP (Paris)                        	software1	97.81
    IIT Kharagpur (Kharagpur)               	software3	97.81
    CLCL (Genève)                           	software1	97.81
    NAIST SATO (Nara)                       	software1	97.81
    Orange – Deskiñ (Lannion)               	software1	97.81
    UParse (Edinburgh)                      	software1	97.81
    LIMSI-LIPN (Paris)                      	software2	97.81
    MQuni (Sydney)                          	software2	97.81
    LyS-FASTPARSE (A Coruña)                	software5	97.81
    TurkuNLP (Turku)                        	software1	97.81
    LATTICE (Paris)                         	software7	97.81
    naistCL (Nara)                          	software1	97.81
    UALING (Tucson)                         	software1	97.81
    Koç University (İstanbul)               	software3	97.81
    BASELINE UDPipe 1.1 (Praha)             	software2	97.81
    Stanford (Stanford)                     	software1	97.81
    METU (Ankara)                           	software2	97.81
    C2L2 (Ithaca)                           	software5	97.81
    MetaRomance (Santiago de Compostela)    	software1	97.81
    OpenU NLP Lab (Ra'anana)                	software6	97.81
    IMS (Stuttgart)                         	software2	97.81
    Mengest (Shanghai)                      	software1	97.81
30. TRL (Tokyo)                             	software1	89.75
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sk

<pre>
 1. Uppsala (Uppsala)                       	software1	85.32
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	84.26
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	84.06
 4. Wenba-NLU (Wuhan)                       	software1	83.53
    ECNU (Shanghai)                         	software1	83.53
    ParisNLP (Paris)                        	software1	83.53
    IIT Kharagpur (Kharagpur)               	software3	83.53
    CLCL (Genève)                           	software1	83.53
    NAIST SATO (Nara)                       	software1	83.53
    Orange – Deskiñ (Lannion)               	software1	83.53
    UParse (Edinburgh)                      	software1	83.53
    LIMSI-LIPN (Paris)                      	software2	83.53
    MQuni (Sydney)                          	software2	83.53
    LyS-FASTPARSE (A Coruña)                	software5	83.53
    TurkuNLP (Turku)                        	software1	83.53
    LATTICE (Paris)                         	software7	83.53
    naistCL (Nara)                          	software1	83.53
    UALING (Tucson)                         	software1	83.53
    Koç University (İstanbul)               	software3	83.53
    BASELINE UDPipe 1.1 (Praha)             	software2	83.53
    Stanford (Stanford)                     	software1	83.53
    METU (Ankara)                           	software2	83.53
    C2L2 (Ithaca)                           	software5	83.53
    MetaRomance (Santiago de Compostela)    	software1	83.53
    OpenU NLP Lab (Ra'anana)                	software6	83.53
    RACAI (București)                       	software1	83.53
    IMS (Stuttgart)                         	software2	83.53
    Mengest (Shanghai)                      	software1	83.53
29. darc (Tübingen)                         	software1	83.33
    HIT-SCIR (Harbin)                       	software4	83.33
31. fbaml (Palo Alto)                       	software1	82.04
32. TRL (Tokyo)                             	software1	68.30
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.24
    Wenba-NLU (Wuhan)                       	software1	99.24
    ECNU (Shanghai)                         	software1	99.24
    ParisNLP (Paris)                        	software1	99.24
    IIT Kharagpur (Kharagpur)               	software3	99.24
    CLCL (Genève)                           	software1	99.24
    NAIST SATO (Nara)                       	software1	99.24
    Orange – Deskiñ (Lannion)               	software1	99.24
    UParse (Edinburgh)                      	software1	99.24
    LIMSI-LIPN (Paris)                      	software2	99.24
    MQuni (Sydney)                          	software2	99.24
    LyS-FASTPARSE (A Coruña)                	software5	99.24
    TurkuNLP (Turku)                        	software1	99.24
    LATTICE (Paris)                         	software7	99.24
    naistCL (Nara)                          	software1	99.24
    UALING (Tucson)                         	software1	99.24
    Koç University (İstanbul)               	software3	99.24
    BASELINE UDPipe 1.1 (Praha)             	software2	99.24
    Stanford (Stanford)                     	software1	99.24
    METU (Ankara)                           	software2	99.24
    C2L2 (Ithaca)                           	software5	99.24
    fbaml (Palo Alto)                       	software1	99.24
    MetaRomance (Santiago de Compostela)    	software1	99.24
    OpenU NLP Lab (Ra'anana)                	software6	99.24
    RACAI (București)                       	software1	99.24
    IMS (Stuttgart)                         	software2	99.24
    Mengest (Shanghai)                      	software1	99.24
28. darc (Tübingen)                         	software1	98.86
    ÚFAL – UDPipe 1.2 (Praha)               	software1	98.86
    HIT-SCIR (Harbin)                       	software4	98.86
31. Uppsala (Uppsala)                       	software1	98.67
32. TRL (Tokyo)                             	software1	96.49
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl_sst

<pre>
 1. IMS (Stuttgart)                         	software2	21.41
 2. darc (Tübingen)                         	software1	20.02
 3. HIT-SCIR (Harbin)                       	software4	19.38
 4. Uppsala (Uppsala)                       	software1	19.03
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	17.94
 6. fbaml (Palo Alto)                       	software1	17.58
 7. ECNU (Shanghai)                         	software1	16.72
    ParisNLP (Paris)                        	software1	16.72
    IIT Kharagpur (Kharagpur)               	software3	16.72
    CLCL (Genève)                           	software1	16.72
    NAIST SATO (Nara)                       	software1	16.72
    Orange – Deskiñ (Lannion)               	software1	16.72
    UParse (Edinburgh)                      	software1	16.72
    LIMSI-LIPN (Paris)                      	software2	16.72
    MQuni (Sydney)                          	software2	16.72
    LyS-FASTPARSE (A Coruña)                	software5	16.72
    TurkuNLP (Turku)                        	software1	16.72
    LATTICE (Paris)                         	software7	16.72
    naistCL (Nara)                          	software1	16.72
    UALING (Tucson)                         	software1	16.72
    Koç University (İstanbul)               	software3	16.72
    BASELINE UDPipe 1.1 (Praha)             	software2	16.72
    Stanford (Stanford)                     	software1	16.72
    METU (Ankara)                           	software2	16.72
    C2L2 (Ithaca)                           	software5	16.72
    MetaRomance (Santiago de Compostela)    	software1	16.72
    OpenU NLP Lab (Ra'anana)                	software6	16.72
    RACAI (București)                       	software1	16.72
    Mengest (Shanghai)                      	software1	16.72
30. ÚFAL – UDPipe 1.2 (Praha)               	software1	13.13
31. TRL (Tokyo)                             	software1	 0.52
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sme

<pre>
 1. TRL (Tokyo)                             	software1	99.13
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	98.79
    ECNU (Shanghai)                         	software1	98.79
    ParisNLP (Paris)                        	software1	98.79
    darc (Tübingen)                         	software1	98.79
    IIT Kharagpur (Kharagpur)               	software3	98.79
    NAIST SATO (Nara)                       	software1	98.79
    Orange – Deskiñ (Lannion)               	software1	98.79
    UParse (Edinburgh)                      	software1	98.79
    LIMSI-LIPN (Paris)                      	software2	98.79
    MQuni (Sydney)                          	software2	98.79
    LyS-FASTPARSE (A Coruña)                	software5	98.79
    TurkuNLP (Turku)                        	software1	98.79
    LATTICE (Paris)                         	software7	98.79
    naistCL (Nara)                          	software1	98.79
    UALING (Tucson)                         	software1	98.79
    Koç University (İstanbul)               	software3	98.79
    BASELINE UDPipe 1.1 (Praha)             	software2	98.79
    ÚFAL – UDPipe 1.2 (Praha)               	software1	98.79
    Stanford (Stanford)                     	software1	98.79
    METU (Ankara)                           	software2	98.79
    C2L2 (Ithaca)                           	software5	98.79
    MetaRomance (Santiago de Compostela)    	software1	98.79
    HIT-SCIR (Harbin)                       	software4	98.79
    CLCL (Genève)                           	software2	98.79
    OpenU NLP Lab (Ra'anana)                	software6	98.79
    RACAI (București)                       	software1	98.79
    IMS (Stuttgart)                         	software2	98.79
    Mengest (Shanghai)                      	software1	98.79
30. Uppsala (Uppsala)                       	software1	98.27
31. fbaml (Palo Alto)                       	software1	98.09
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv

<pre>
 1. Uppsala (Uppsala)                       	software1	97.26
 2. Wenba-NLU (Wuhan)                       	software1	96.37
    ParisNLP (Paris)                        	software1	96.37
    IIT Kharagpur (Kharagpur)               	software3	96.37
    CLCL (Genève)                           	software1	96.37
    NAIST SATO (Nara)                       	software1	96.37
    Orange – Deskiñ (Lannion)               	software1	96.37
    UParse (Edinburgh)                      	software1	96.37
    LIMSI-LIPN (Paris)                      	software2	96.37
    MQuni (Sydney)                          	software2	96.37
    LyS-FASTPARSE (A Coruña)                	software5	96.37
    TurkuNLP (Turku)                        	software1	96.37
    LATTICE (Paris)                         	software7	96.37
    naistCL (Nara)                          	software1	96.37
    UALING (Tucson)                         	software1	96.37
    Koç University (İstanbul)               	software3	96.37
    BASELINE UDPipe 1.1 (Praha)             	software2	96.37
    Stanford (Stanford)                     	software1	96.37
    METU (Ankara)                           	software2	96.37
    C2L2 (Ithaca)                           	software5	96.37
    MetaRomance (Santiago de Compostela)    	software1	96.37
    OpenU NLP Lab (Ra'anana)                	software6	96.37
    IMS (Stuttgart)                         	software2	96.37
    Mengest (Shanghai)                      	software1	96.37
25. Wanghao-ftd-SJTU (Shanghai)             	software2	95.89
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	95.57
27. fbaml (Palo Alto)                       	software1	94.92
28. darc (Tübingen)                         	software1	94.53
    HIT-SCIR (Harbin)                       	software4	94.53
30. RACAI (București)                       	software1	89.87
31. TRL (Tokyo)                             	software1	89.69
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_lines

<pre>
 1. Uppsala (Uppsala)                       	software1	87.89
 2. fbaml (Palo Alto)                       	software1	87.08
 3. darc (Tübingen)                         	software1	86.84
 4. HIT-SCIR (Harbin)                       	software4	86.61
 5. Wenba-NLU (Wuhan)                       	software1	86.44
    ECNU (Shanghai)                         	software1	86.44
    ParisNLP (Paris)                        	software1	86.44
    IIT Kharagpur (Kharagpur)               	software3	86.44
    CLCL (Genève)                           	software1	86.44
    NAIST SATO (Nara)                       	software1	86.44
    Orange – Deskiñ (Lannion)               	software1	86.44
    UParse (Edinburgh)                      	software1	86.44
    LIMSI-LIPN (Paris)                      	software2	86.44
    MQuni (Sydney)                          	software2	86.44
    LyS-FASTPARSE (A Coruña)                	software5	86.44
    TurkuNLP (Turku)                        	software1	86.44
    LATTICE (Paris)                         	software7	86.44
    naistCL (Nara)                          	software1	86.44
    UALING (Tucson)                         	software1	86.44
    Koç University (İstanbul)               	software3	86.44
    BASELINE UDPipe 1.1 (Praha)             	software2	86.44
    Stanford (Stanford)                     	software1	86.44
    METU (Ankara)                           	software2	86.44
    C2L2 (Ithaca)                           	software5	86.44
    MetaRomance (Santiago de Compostela)    	software1	86.44
    OpenU NLP Lab (Ra'anana)                	software6	86.44
    IMS (Stuttgart)                         	software2	86.44
    Mengest (Shanghai)                      	software1	86.44
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	86.43
30. RACAI (București)                       	software1	84.96
31. Wanghao-ftd-SJTU (Shanghai)             	software2	84.85
32. TRL (Tokyo)                             	software1	79.82
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_pud

<pre>
 1. TRL (Tokyo)                             	software1	95.52
 2. RACAI (București)                       	software1	94.46
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.44
 4. fbaml (Palo Alto)                       	software1	94.11
 5. HIT-SCIR (Harbin)                       	software4	92.96
 6. ECNU (Shanghai)                         	software1	90.20
    ParisNLP (Paris)                        	software1	90.20
    darc (Tübingen)                         	software1	90.20
    IIT Kharagpur (Kharagpur)               	software3	90.20
    CLCL (Genève)                           	software1	90.20
    NAIST SATO (Nara)                       	software1	90.20
    Orange – Deskiñ (Lannion)               	software1	90.20
    UParse (Edinburgh)                      	software1	90.20
    LIMSI-LIPN (Paris)                      	software2	90.20
    MQuni (Sydney)                          	software2	90.20
    LyS-FASTPARSE (A Coruña)                	software5	90.20
    TurkuNLP (Turku)                        	software1	90.20
    LATTICE (Paris)                         	software7	90.20
    naistCL (Nara)                          	software1	90.20
    UALING (Tucson)                         	software1	90.20
    Koç University (İstanbul)               	software3	90.20
    BASELINE UDPipe 1.1 (Praha)             	software2	90.20
    Stanford (Stanford)                     	software1	90.20
    METU (Ankara)                           	software2	90.20
    C2L2 (Ithaca)                           	software5	90.20
    MetaRomance (Santiago de Compostela)    	software1	90.20
    OpenU NLP Lab (Ra'anana)                	software6	90.20
    IMS (Stuttgart)                         	software2	90.20
    Mengest (Shanghai)                      	software1	90.20
30. Uppsala (Uppsala)                       	software1	84.63
31. Wanghao-ftd-SJTU (Shanghai)             	software2	82.30
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr

<pre>
 1. darc (Tübingen)                         	software1	97.04
    HIT-SCIR (Harbin)                       	software4	97.04
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	96.93
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	96.89
 5. Wenba-NLU (Wuhan)                       	software1	96.63
    ParisNLP (Paris)                        	software1	96.63
    IIT Kharagpur (Kharagpur)               	software3	96.63
    CLCL (Genève)                           	software1	96.63
    NAIST SATO (Nara)                       	software1	96.63
    Orange – Deskiñ (Lannion)               	software1	96.63
    UParse (Edinburgh)                      	software1	96.63
    LIMSI-LIPN (Paris)                      	software2	96.63
    MQuni (Sydney)                          	software2	96.63
    LyS-FASTPARSE (A Coruña)                	software5	96.63
    TurkuNLP (Turku)                        	software1	96.63
    LATTICE (Paris)                         	software7	96.63
    naistCL (Nara)                          	software1	96.63
    UALING (Tucson)                         	software1	96.63
    Koç University (İstanbul)               	software3	96.63
    BASELINE UDPipe 1.1 (Praha)             	software2	96.63
    Stanford (Stanford)                     	software1	96.63
    METU (Ankara)                           	software2	96.63
    C2L2 (Ithaca)                           	software5	96.63
    OpenU NLP Lab (Ra'anana)                	software6	96.63
    IMS (Stuttgart)                         	software2	96.63
    Mengest (Shanghai)                      	software1	96.63
27. fbaml (Palo Alto)                       	software1	96.32
28. Uppsala (Uppsala)                       	software1	96.29
29. RACAI (București)                       	software1	95.77
30. TRL (Tokyo)                             	software1	93.57
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr_pud

<pre>
 1. ParisNLP (Paris)                        	software1	93.91
    darc (Tübingen)                         	software1	93.91
    IIT Kharagpur (Kharagpur)               	software3	93.91
    CLCL (Genève)                           	software1	93.91
    NAIST SATO (Nara)                       	software1	93.91
    Orange – Deskiñ (Lannion)               	software1	93.91
    UParse (Edinburgh)                      	software1	93.91
    LIMSI-LIPN (Paris)                      	software2	93.91
    MQuni (Sydney)                          	software2	93.91
    LyS-FASTPARSE (A Coruña)                	software5	93.91
    TurkuNLP (Turku)                        	software1	93.91
    LATTICE (Paris)                         	software7	93.91
    naistCL (Nara)                          	software1	93.91
    UALING (Tucson)                         	software1	93.91
    Koç University (İstanbul)               	software3	93.91
    BASELINE UDPipe 1.1 (Praha)             	software2	93.91
    Stanford (Stanford)                     	software1	93.91
    METU (Ankara)                           	software2	93.91
    C2L2 (Ithaca)                           	software5	93.91
    MetaRomance (Santiago de Compostela)    	software1	93.91
    OpenU NLP Lab (Ra'anana)                	software6	93.91
    IMS (Stuttgart)                         	software2	93.91
    Mengest (Shanghai)                      	software1	93.91
24. Wanghao-ftd-SJTU (Shanghai)             	software2	93.62
25. fbaml (Palo Alto)                       	software1	93.00
26. Uppsala (Uppsala)                       	software1	92.08
27. RACAI (București)                       	software1	91.79
28. HIT-SCIR (Harbin)                       	software4	91.30
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	90.87
30. TRL (Tokyo)                             	software1	88.88
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ug

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	70.47
 2. TRL (Tokyo)                             	software1	69.05
 3. Uppsala (Uppsala)                       	software1	68.76
 4. RACAI (București)                       	software1	68.17
 5. HIT-SCIR (Harbin)                       	software4	67.59
 6. darc (Tübingen)                         	software1	67.53
 7. fbaml (Palo Alto)                       	software1	67.13
 8. ÚFAL – UDPipe 1.2 (Praha)               	software1	65.31
 9. ECNU (Shanghai)                         	software1	63.55
    ParisNLP (Paris)                        	software1	63.55
    IIT Kharagpur (Kharagpur)               	software3	63.55
    CLCL (Genève)                           	software1	63.55
    NAIST SATO (Nara)                       	software1	63.55
    Orange – Deskiñ (Lannion)               	software1	63.55
    UParse (Edinburgh)                      	software1	63.55
    LIMSI-LIPN (Paris)                      	software2	63.55
    MQuni (Sydney)                          	software2	63.55
    LyS-FASTPARSE (A Coruña)                	software5	63.55
    TurkuNLP (Turku)                        	software1	63.55
    LATTICE (Paris)                         	software7	63.55
    naistCL (Nara)                          	software1	63.55
    UALING (Tucson)                         	software1	63.55
    Koç University (İstanbul)               	software3	63.55
    BASELINE UDPipe 1.1 (Praha)             	software2	63.55
    Stanford (Stanford)                     	software1	63.55
    METU (Ankara)                           	software2	63.55
    C2L2 (Ithaca)                           	software5	63.55
    MetaRomance (Santiago de Compostela)    	software1	63.55
    OpenU NLP Lab (Ra'anana)                	software6	63.55
    IMS (Stuttgart)                         	software2	63.55
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. UT (Tartu)                              	software1	 0.00
33. Mengest (Shanghai)                      	software1	 0.00
</pre>



### uk

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	95.75
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	94.84
 3. darc (Tübingen)                         	software1	94.34
 4. RACAI (București)                       	software1	94.25
 5. HIT-SCIR (Harbin)                       	software4	92.87
 6. ParisNLP (Paris)                        	software1	92.59
    IIT Kharagpur (Kharagpur)               	software3	92.59
    CLCL (Genève)                           	software1	92.59
    NAIST SATO (Nara)                       	software1	92.59
    Orange – Deskiñ (Lannion)               	software1	92.59
    UParse (Edinburgh)                      	software1	92.59
    LIMSI-LIPN (Paris)                      	software2	92.59
    MQuni (Sydney)                          	software2	92.59
    LyS-FASTPARSE (A Coruña)                	software5	92.59
    TurkuNLP (Turku)                        	software1	92.59
    LATTICE (Paris)                         	software7	92.59
    naistCL (Nara)                          	software1	92.59
    UALING (Tucson)                         	software1	92.59
    Koç University (İstanbul)               	software3	92.59
    BASELINE UDPipe 1.1 (Praha)             	software2	92.59
    Stanford (Stanford)                     	software1	92.59
    METU (Ankara)                           	software2	92.59
    C2L2 (Ithaca)                           	software5	92.59
    MetaRomance (Santiago de Compostela)    	software1	92.59
    OpenU NLP Lab (Ra'anana)                	software6	92.59
    IMS (Stuttgart)                         	software2	92.59
    Mengest (Shanghai)                      	software1	92.59
28. fbaml (Palo Alto)                       	software1	92.49
29. TRL (Tokyo)                             	software1	91.80
30. Uppsala (Uppsala)                       	software1	90.04
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ur

<pre>
 1. Uppsala (Uppsala)                       	software1	98.60
 2. Wenba-NLU (Wuhan)                       	software1	98.32
    ECNU (Shanghai)                         	software1	98.32
    ParisNLP (Paris)                        	software1	98.32
    IIT Kharagpur (Kharagpur)               	software3	98.32
    CLCL (Genève)                           	software1	98.32
    NAIST SATO (Nara)                       	software1	98.32
    Orange – Deskiñ (Lannion)               	software1	98.32
    UParse (Edinburgh)                      	software1	98.32
    LIMSI-LIPN (Paris)                      	software2	98.32
    MQuni (Sydney)                          	software2	98.32
    LyS-FASTPARSE (A Coruña)                	software5	98.32
    TurkuNLP (Turku)                        	software1	98.32
    LATTICE (Paris)                         	software7	98.32
    naistCL (Nara)                          	software1	98.32
    UALING (Tucson)                         	software1	98.32
    Koç University (İstanbul)               	software3	98.32
    BASELINE UDPipe 1.1 (Praha)             	software2	98.32
    ÚFAL – UDPipe 1.2 (Praha)               	software1	98.32
    Stanford (Stanford)                     	software1	98.32
    METU (Ankara)                           	software2	98.32
    C2L2 (Ithaca)                           	software5	98.32
    MetaRomance (Santiago de Compostela)    	software1	98.32
    OpenU NLP Lab (Ra'anana)                	software6	98.32
    IMS (Stuttgart)                         	software2	98.32
    Mengest (Shanghai)                      	software1	98.32
27. Wanghao-ftd-SJTU (Shanghai)             	software2	98.04
    darc (Tübingen)                         	software1	98.04
    HIT-SCIR (Harbin)                       	software4	98.04
30. TRL (Tokyo)                             	software1	97.93
31. fbaml (Palo Alto)                       	software1	97.67
32. RACAI (București)                       	software1	96.83
33. UT (Tartu)                              	software1	 0.00
</pre>



### vi

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	92.95
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	92.87
 3. darc (Tübingen)                         	software1	92.67
    HIT-SCIR (Harbin)                       	software4	92.67
 5. Wenba-NLU (Wuhan)                       	software1	92.59
    ECNU (Shanghai)                         	software1	92.59
    ParisNLP (Paris)                        	software1	92.59
    IIT Kharagpur (Kharagpur)               	software3	92.59
    CLCL (Genève)                           	software1	92.59
    NAIST SATO (Nara)                       	software1	92.59
    Orange – Deskiñ (Lannion)               	software1	92.59
    UParse (Edinburgh)                      	software1	92.59
    LIMSI-LIPN (Paris)                      	software2	92.59
    MQuni (Sydney)                          	software2	92.59
    LyS-FASTPARSE (A Coruña)                	software5	92.59
    TurkuNLP (Turku)                        	software1	92.59
    LATTICE (Paris)                         	software7	92.59
    naistCL (Nara)                          	software1	92.59
    UALING (Tucson)                         	software1	92.59
    Koç University (İstanbul)               	software3	92.59
    BASELINE UDPipe 1.1 (Praha)             	software2	92.59
    Stanford (Stanford)                     	software1	92.59
    METU (Ankara)                           	software2	92.59
    C2L2 (Ithaca)                           	software5	92.59
    MetaRomance (Santiago de Compostela)    	software1	92.59
    OpenU NLP Lab (Ra'anana)                	software6	92.59
    RACAI (București)                       	software1	92.59
    IMS (Stuttgart)                         	software2	92.59
    Mengest (Shanghai)                      	software1	92.59
30. fbaml (Palo Alto)                       	software1	92.44
31. Uppsala (Uppsala)                       	software1	87.30
32. TRL (Tokyo)                             	software1	86.12
33. UT (Tartu)                              	software1	 0.00
</pre>



### zh

<pre>
 1. HIT-SCIR (Harbin)                       	software4	98.80
 2. darc (Tübingen)                         	software1	98.50
    fbaml (Palo Alto)                       	software1	98.50
 4. Uppsala (Uppsala)                       	software1	98.20
    ÚFAL – UDPipe 1.2 (Praha)               	software1	98.20
 6. Wenba-NLU (Wuhan)                       	software1	98.19
    ECNU (Shanghai)                         	software1	98.19
    ParisNLP (Paris)                        	software1	98.19
    IIT Kharagpur (Kharagpur)               	software3	98.19
    CLCL (Genève)                           	software1	98.19
    NAIST SATO (Nara)                       	software1	98.19
    Orange – Deskiñ (Lannion)               	software1	98.19
    UParse (Edinburgh)                      	software1	98.19
    LIMSI-LIPN (Paris)                      	software2	98.19
    MQuni (Sydney)                          	software2	98.19
    LyS-FASTPARSE (A Coruña)                	software5	98.19
    TurkuNLP (Turku)                        	software1	98.19
    LATTICE (Paris)                         	software7	98.19
    naistCL (Nara)                          	software1	98.19
    UALING (Tucson)                         	software1	98.19
    Koç University (İstanbul)               	software3	98.19
    BASELINE UDPipe 1.1 (Praha)             	software2	98.19
    Stanford (Stanford)                     	software1	98.19
    METU (Ankara)                           	software2	98.19
    C2L2 (Ithaca)                           	software5	98.19
    MetaRomance (Santiago de Compostela)    	software1	98.19
    OpenU NLP Lab (Ra'anana)                	software6	98.19
    RACAI (București)                       	software1	98.19
    IMS (Stuttgart)                         	software2	98.19
    Mengest (Shanghai)                      	software1	98.19
31. Wanghao-ftd-SJTU (Shanghai)             	software2	97.90
32. TRL (Tokyo)                             	software1	92.81
33. UT (Tartu)                              	software1	 0.00
</pre>



