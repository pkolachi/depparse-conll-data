---
layout: page
title: CoNLL 2017 Shared Task
---

# Results: Tokenization F1

## All treebanks

<pre>
 1. LIMSI-LIPN (Paris)                      	software2	98.95
 2. HIT-SCIR (Harbin)                       	software4	98.95
 3. IMS (Stuttgart)                         	software2	98.92
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.89
 5. ParisNLP (Paris)                        	software1	98.85
 6. darc (Tübingen)                         	software1	98.81
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	98.81
 8. NAIST SATO (Nara)                       	software1	98.77
    Orange – Deskiñ (Lannion)               	software1	98.77
    UParse (Edinburgh)                      	software1	98.77
    MQuni (Sydney)                          	software2	98.77
    LATTICE (Paris)                         	software7	98.77
    naistCL (Nara)                          	software1	98.77
    BASELINE UDPipe 1.1 (Praha)             	software2	98.77
    Stanford (Stanford)                     	software1	98.77
    METU (Ankara)                           	software2	98.77
    C2L2 (Ithaca)                           	software5	98.77
    CLCL (Genève)                           	software2	98.77
19. IIT Kharagpur (Kharagpur)               	software3	98.77
    LyS-FASTPARSE (A Coruña)                	software5	98.77
    TurkuNLP (Turku)                        	software1	98.77
    UALING (Tucson)                         	software1	98.77
    Koç University (İstanbul)               	software3	98.77
    OpenU NLP Lab (Ra'anana)                	software6	98.77
25. RACAI (București)                       	software1	98.58
26. fbaml (Palo Alto)                       	software1	98.51
27. Uppsala (Uppsala)                       	software1	97.64
28. Mengest (Shanghai)                      	software1	96.37
29. TRL (Tokyo)                             	software1	96.12
30. MetaRomance (Santiago de Compostela)    	software1	95.07
31. Wenba-NLU (Wuhan)                       	software1	56.21
32. ECNU (Shanghai)                         	software1	43.68
33. UT (Tartu)                              	software1	32.99
</pre>



## Big treebanks only

Macro-average Tokens-F1 of the 55 big treebanks: ar, bg, ca, cs, cs_cac, cs_cltt, cu, da, de, el, en, en_lines, en_partut, es, es_ancora, et, eu, fa, fi, fi_ftb, fr, fr_sequoia, gl, got, grc, grc_proiel, he, hi, hr, hu, id, it, ja, ko, la_ittb, la_proiel, lv, nl, nl_lassysmall, no_bokmaal, no_nynorsk, pl, pt, pt_br, ro, ru, ru_syntagrus, sk, sl, sv, sv_lines, tr, ur, vi, zh. These are the treebanks that have development data available, hence these results should be comparable to the performance of the systems on the development data.

<pre>
 1. LIMSI-LIPN (Paris)                      	software2	99.33
 2. IMS (Stuttgart)                         	software2	99.31
 3. HIT-SCIR (Harbin)                       	software4	99.28
 4. fbaml (Palo Alto)                       	software1	99.25
 5. ParisNLP (Paris)                        	software1	99.25
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.21
 7. darc (Tübingen)                         	software1	99.14
 8. Wanghao-ftd-SJTU (Shanghai)             	software2	99.13
 9. IIT Kharagpur (Kharagpur)               	software3	99.12
    Orange – Deskiñ (Lannion)               	software1	99.12
    UParse (Edinburgh)                      	software1	99.12
    TurkuNLP (Turku)                        	software1	99.12
    C2L2 (Ithaca)                           	software5	99.12
    Mengest (Shanghai)                      	software1	99.12
15. NAIST SATO (Nara)                       	software1	99.12
    naistCL (Nara)                          	software1	99.12
    UALING (Tucson)                         	software1	99.12
    METU (Ankara)                           	software2	99.12
    CLCL (Genève)                           	software2	99.12
20. MQuni (Sydney)                          	software2	99.12
    LyS-FASTPARSE (A Coruña)                	software5	99.12
    LATTICE (Paris)                         	software7	99.12
    Koç University (İstanbul)               	software3	99.12
    BASELINE UDPipe 1.1 (Praha)             	software2	99.12
    Stanford (Stanford)                     	software1	99.12
    OpenU NLP Lab (Ra'anana)                	software6	99.12
27. RACAI (București)                       	software1	99.09
28. Uppsala (Uppsala)                       	software1	97.76
29. TRL (Tokyo)                             	software1	95.68
30. MetaRomance (Santiago de Compostela)    	software1	95.49
31. Wenba-NLU (Wuhan)                       	software1	82.79
32. ECNU (Shanghai)                         	software1	42.85
33. UT (Tartu)                              	software1	39.75
</pre>



## PUD treebanks only

Macro-average Tokens-F1 of the 14 PUD treebanks (additional parallel test sets): ar_pud, cs_pud, de_pud, en_pud, es_pud, fi_pud, fr_pud, hi_pud, it_pud, ja_pud, pt_pud, ru_pud, sv_pud, tr_pud. These are languages for which there exists at least one big training treebank. However, these test sets have been produced separately and their domain may differ.

<pre>
 1. HIT-SCIR (Harbin)                       	software4	97.30
 2. LIMSI-LIPN (Paris)                      	software2	97.28
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	97.25
 4. IMS (Stuttgart)                         	software2	97.18
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	97.11
 6. darc (Tübingen)                         	software1	97.01
    Orange – Deskiñ (Lannion)               	software1	97.01
    UParse (Edinburgh)                      	software1	97.01
    OpenU NLP Lab (Ra'anana)                	software6	97.01
10. ParisNLP (Paris)                        	software1	97.01
    NAIST SATO (Nara)                       	software1	97.01
    MQuni (Sydney)                          	software2	97.01
    LyS-FASTPARSE (A Coruña)                	software5	97.01
    TurkuNLP (Turku)                        	software1	97.01
    LATTICE (Paris)                         	software7	97.01
    UALING (Tucson)                         	software1	97.01
    Koç University (İstanbul)               	software3	97.01
    BASELINE UDPipe 1.1 (Praha)             	software2	97.01
    METU (Ankara)                           	software2	97.01
    C2L2 (Ithaca)                           	software5	97.01
    CLCL (Genève)                           	software2	97.01
22. naistCL (Nara)                          	software1	97.01
    Stanford (Stanford)                     	software1	97.01
    MetaRomance (Santiago de Compostela)    	software1	97.01
    Mengest (Shanghai)                      	software1	97.01
26. IIT Kharagpur (Kharagpur)               	software3	97.01
27. TRL (Tokyo)                             	software1	96.75
28. Uppsala (Uppsala)                       	software1	96.54
29. fbaml (Palo Alto)                       	software1	96.42
30. RACAI (București)                       	software1	96.13
31. ECNU (Shanghai)                         	software1	41.68
32. UT (Tartu)                              	software1	27.55
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



## Small treebanks only

Macro-average Tokens-F1 of the 8 small treebanks: fr_partut, ga, gl_treegal, kk, la, sl_sst, ug, uk. These treebanks lack development data and some of them have very little training data (especially Uyghur and Kazakh).

<pre>
 1. darc (Tübingen)                         	software1	99.34
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.30
 3. HIT-SCIR (Harbin)                       	software4	99.26
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	99.24
 5. NAIST SATO (Nara)                       	software1	99.01
    UParse (Edinburgh)                      	software1	99.01
    UALING (Tucson)                         	software1	99.01
 8. ParisNLP (Paris)                        	software1	99.01
    IIT Kharagpur (Kharagpur)               	software3	99.01
    Orange – Deskiñ (Lannion)               	software1	99.01
    LIMSI-LIPN (Paris)                      	software2	99.01
    MQuni (Sydney)                          	software2	99.01
    LyS-FASTPARSE (A Coruña)                	software5	99.01
    TurkuNLP (Turku)                        	software1	99.01
    LATTICE (Paris)                         	software7	99.01
    naistCL (Nara)                          	software1	99.01
    Koç University (İstanbul)               	software3	99.01
    BASELINE UDPipe 1.1 (Praha)             	software2	99.01
    Stanford (Stanford)                     	software1	99.01
    METU (Ankara)                           	software2	99.01
    C2L2 (Ithaca)                           	software5	99.01
    MetaRomance (Santiago de Compostela)    	software1	99.01
    OpenU NLP Lab (Ra'anana)                	software6	99.01
    CLCL (Genève)                           	software2	99.01
    IMS (Stuttgart)                         	software2	99.01
26. RACAI (București)                       	software1	98.87
27. fbaml (Palo Alto)                       	software1	98.78
28. Uppsala (Uppsala)                       	software1	98.50
29. TRL (Tokyo)                             	software1	96.92
30. Mengest (Shanghai)                      	software1	74.79
31. ECNU (Shanghai)                         	software1	37.29
32. UT (Tartu)                              	software1	12.50
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



## Surprise languages only

Macro-average Tokens-F1 of the 4 surprise language treebanks: bxr, hsb, kmr, sme.

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.52
    ParisNLP (Paris)                        	software1	99.52
    darc (Tübingen)                         	software1	99.52
    IIT Kharagpur (Kharagpur)               	software3	99.52
    NAIST SATO (Nara)                       	software1	99.52
    Orange – Deskiñ (Lannion)               	software1	99.52
    UParse (Edinburgh)                      	software1	99.52
    LIMSI-LIPN (Paris)                      	software2	99.52
    LyS-FASTPARSE (A Coruña)                	software5	99.52
    TurkuNLP (Turku)                        	software1	99.52
    LATTICE (Paris)                         	software7	99.52
    naistCL (Nara)                          	software1	99.52
    BASELINE UDPipe 1.1 (Praha)             	software2	99.52
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.52
    Stanford (Stanford)                     	software1	99.52
    Mengest (Shanghai)                      	software1	99.52
    RACAI (București)                       	software1	99.52
    OpenU NLP Lab (Ra'anana)                	software6	99.52
    CLCL (Genève)                           	software2	99.52
    IMS (Stuttgart)                         	software2	99.52
21. MQuni (Sydney)                          	software2	99.52
    UALING (Tucson)                         	software1	99.52
    Koç University (İstanbul)               	software3	99.52
    METU (Ankara)                           	software2	99.52
    C2L2 (Ithaca)                           	software5	99.52
    HIT-SCIR (Harbin)                       	software4	99.52
27. TRL (Tokyo)                             	software1	98.35
28. Uppsala (Uppsala)                       	software1	98.24
29. fbaml (Palo Alto)                       	software1	95.02
30. ECNU (Shanghai)                         	software1	74.77
31. MetaRomance (Santiago de Compostela)    	software1	74.68
32. Wenba-NLU (Wuhan)                       	software1	 0.00
    UT (Tartu)                              	software1	 0.00
</pre>



## Per treebank Tokens-F1



### ar

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.99
 2. Wenba-NLU (Wuhan)                       	software1	99.98
    ParisNLP (Paris)                        	software1	99.98
    darc (Tübingen)                         	software1	99.98
    IIT Kharagpur (Kharagpur)               	software3	99.98
    CLCL (Genève)                           	software1	99.98
    NAIST SATO (Nara)                       	software1	99.98
    Orange – Deskiñ (Lannion)               	software1	99.98
    UParse (Edinburgh)                      	software1	99.98
    LIMSI-LIPN (Paris)                      	software2	99.98
    MQuni (Sydney)                          	software2	99.98
    LyS-FASTPARSE (A Coruña)                	software5	99.98
    TurkuNLP (Turku)                        	software1	99.98
    LATTICE (Paris)                         	software7	99.98
    naistCL (Nara)                          	software1	99.98
    UALING (Tucson)                         	software1	99.98
    Koç University (İstanbul)               	software3	99.98
    BASELINE UDPipe 1.1 (Praha)             	software2	99.98
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.98
    Stanford (Stanford)                     	software1	99.98
    METU (Ankara)                           	software2	99.98
    C2L2 (Ithaca)                           	software5	99.98
    MetaRomance (Santiago de Compostela)    	software1	99.98
    HIT-SCIR (Harbin)                       	software4	99.98
    Mengest (Shanghai)                      	software1	99.98
    RACAI (București)                       	software1	99.98
    OpenU NLP Lab (Ra'anana)                	software6	99.98
    IMS (Stuttgart)                         	software2	99.98
29. fbaml (Palo Alto)                       	software1	99.96
30. Uppsala (Uppsala)                       	software1	83.23
31. TRL (Tokyo)                             	software1	79.04
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ar_pud

<pre>
 1. TRL (Tokyo)                             	software1	96.05
 2. Uppsala (Uppsala)                       	software1	94.24
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	80.92
    HIT-SCIR (Harbin)                       	software4	80.92
 5. ParisNLP (Paris)                        	software1	80.89
    darc (Tübingen)                         	software1	80.89
    IIT Kharagpur (Kharagpur)               	software3	80.89
    CLCL (Genève)                           	software1	80.89
    NAIST SATO (Nara)                       	software1	80.89
    Orange – Deskiñ (Lannion)               	software1	80.89
    UParse (Edinburgh)                      	software1	80.89
    LIMSI-LIPN (Paris)                      	software2	80.89
    MQuni (Sydney)                          	software2	80.89
    LyS-FASTPARSE (A Coruña)                	software5	80.89
    TurkuNLP (Turku)                        	software1	80.89
    LATTICE (Paris)                         	software7	80.89
    naistCL (Nara)                          	software1	80.89
    UALING (Tucson)                         	software1	80.89
    Koç University (İstanbul)               	software3	80.89
    BASELINE UDPipe 1.1 (Praha)             	software2	80.89
    Stanford (Stanford)                     	software1	80.89
    METU (Ankara)                           	software2	80.89
    C2L2 (Ithaca)                           	software5	80.89
    MetaRomance (Santiago de Compostela)    	software1	80.89
    Mengest (Shanghai)                      	software1	80.89
    OpenU NLP Lab (Ra'anana)                	software6	80.89
    IMS (Stuttgart)                         	software2	80.89
28. fbaml (Palo Alto)                       	software1	80.87
29. ÚFAL – UDPipe 1.2 (Praha)               	software1	80.85
30. RACAI (București)                       	software1	80.81
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### bg

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.92
 2. Wenba-NLU (Wuhan)                       	software1	99.91
    ParisNLP (Paris)                        	software1	99.91
    darc (Tübingen)                         	software1	99.91
    IIT Kharagpur (Kharagpur)               	software3	99.91
    CLCL (Genève)                           	software1	99.91
    NAIST SATO (Nara)                       	software1	99.91
    Orange – Deskiñ (Lannion)               	software1	99.91
    UParse (Edinburgh)                      	software1	99.91
    LIMSI-LIPN (Paris)                      	software2	99.91
    MQuni (Sydney)                          	software2	99.91
    LyS-FASTPARSE (A Coruña)                	software5	99.91
    TurkuNLP (Turku)                        	software1	99.91
    LATTICE (Paris)                         	software7	99.91
    naistCL (Nara)                          	software1	99.91
    UALING (Tucson)                         	software1	99.91
    Koç University (İstanbul)               	software3	99.91
    BASELINE UDPipe 1.1 (Praha)             	software2	99.91
    Stanford (Stanford)                     	software1	99.91
    METU (Ankara)                           	software2	99.91
    C2L2 (Ithaca)                           	software5	99.91
    MetaRomance (Santiago de Compostela)    	software1	99.91
    HIT-SCIR (Harbin)                       	software4	99.91
    Mengest (Shanghai)                      	software1	99.91
    RACAI (București)                       	software1	99.91
    OpenU NLP Lab (Ra'anana)                	software6	99.91
    UT (Tartu)                              	software1	99.91
    IMS (Stuttgart)                         	software2	99.91
29. Wanghao-ftd-SJTU (Shanghai)             	software2	99.90
30. fbaml (Palo Alto)                       	software1	99.82
31. Uppsala (Uppsala)                       	software1	99.70
32. TRL (Tokyo)                             	software1	97.43
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### bxr

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.35
    ECNU (Shanghai)                         	software1	99.35
    ParisNLP (Paris)                        	software1	99.35
    darc (Tübingen)                         	software1	99.35
    IIT Kharagpur (Kharagpur)               	software3	99.35
    NAIST SATO (Nara)                       	software1	99.35
    Orange – Deskiñ (Lannion)               	software1	99.35
    UParse (Edinburgh)                      	software1	99.35
    LIMSI-LIPN (Paris)                      	software2	99.35
    MQuni (Sydney)                          	software2	99.35
    LyS-FASTPARSE (A Coruña)                	software5	99.35
    TurkuNLP (Turku)                        	software1	99.35
    LATTICE (Paris)                         	software7	99.35
    naistCL (Nara)                          	software1	99.35
    UALING (Tucson)                         	software1	99.35
    Koç University (İstanbul)               	software3	99.35
    BASELINE UDPipe 1.1 (Praha)             	software2	99.35
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.35
    Stanford (Stanford)                     	software1	99.35
    METU (Ankara)                           	software2	99.35
    C2L2 (Ithaca)                           	software5	99.35
    HIT-SCIR (Harbin)                       	software4	99.35
    Mengest (Shanghai)                      	software1	99.35
    RACAI (București)                       	software1	99.35
    OpenU NLP Lab (Ra'anana)                	software6	99.35
    CLCL (Genève)                           	software2	99.35
    IMS (Stuttgart)                         	software2	99.35
28. TRL (Tokyo)                             	software1	98.44
29. Uppsala (Uppsala)                       	software1	97.77
30. fbaml (Palo Alto)                       	software1	97.46
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ca

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	99.97
    ParisNLP (Paris)                        	software1	99.97
    IIT Kharagpur (Kharagpur)               	software3	99.97
    NAIST SATO (Nara)                       	software1	99.97
    Orange – Deskiñ (Lannion)               	software1	99.97
    UParse (Edinburgh)                      	software1	99.97
    LIMSI-LIPN (Paris)                      	software2	99.97
    MQuni (Sydney)                          	software2	99.97
    LyS-FASTPARSE (A Coruña)                	software5	99.97
    TurkuNLP (Turku)                        	software1	99.97
    LATTICE (Paris)                         	software7	99.97
    naistCL (Nara)                          	software1	99.97
    UALING (Tucson)                         	software1	99.97
    Koç University (İstanbul)               	software3	99.97
    BASELINE UDPipe 1.1 (Praha)             	software2	99.97
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.97
    Stanford (Stanford)                     	software1	99.97
    METU (Ankara)                           	software2	99.97
    C2L2 (Ithaca)                           	software5	99.97
    MetaRomance (Santiago de Compostela)    	software1	99.97
    Mengest (Shanghai)                      	software1	99.97
    OpenU NLP Lab (Ra'anana)                	software6	99.97
    CLCL (Genève)                           	software2	99.97
    fbaml (Palo Alto)                       	software1	99.97
    IMS (Stuttgart)                         	software2	99.97
26. Wanghao-ftd-SJTU (Shanghai)             	software2	99.96
    darc (Tübingen)                         	software1	99.96
    HIT-SCIR (Harbin)                       	software4	99.96
    RACAI (București)                       	software1	99.96
30. Uppsala (Uppsala)                       	software1	99.69
31. TRL (Tokyo)                             	software1	91.67
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs

<pre>
 1. fbaml (Palo Alto)                       	software1	99.99
 2. Uppsala (Uppsala)                       	software1	99.96
    RACAI (București)                       	software1	99.96
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.93
 5. darc (Tübingen)                         	software1	99.92
    HIT-SCIR (Harbin)                       	software4	99.92
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	99.90
    ParisNLP (Paris)                        	software1	99.90
    IIT Kharagpur (Kharagpur)               	software3	99.90
    CLCL (Genève)                           	software1	99.90
    NAIST SATO (Nara)                       	software1	99.90
    Orange – Deskiñ (Lannion)               	software1	99.90
    UParse (Edinburgh)                      	software1	99.90
    LIMSI-LIPN (Paris)                      	software2	99.90
    MQuni (Sydney)                          	software2	99.90
    LyS-FASTPARSE (A Coruña)                	software5	99.90
    TurkuNLP (Turku)                        	software1	99.90
    LATTICE (Paris)                         	software7	99.90
    naistCL (Nara)                          	software1	99.90
    UALING (Tucson)                         	software1	99.90
    Koç University (İstanbul)               	software3	99.90
    BASELINE UDPipe 1.1 (Praha)             	software2	99.90
    Stanford (Stanford)                     	software1	99.90
    METU (Ankara)                           	software2	99.90
    C2L2 (Ithaca)                           	software5	99.90
    Mengest (Shanghai)                      	software1	99.90
    OpenU NLP Lab (Ra'anana)                	software6	99.90
    IMS (Stuttgart)                         	software2	99.90
29. TRL (Tokyo)                             	software1	97.26
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cac

<pre>
 1. ParisNLP (Paris)                        	software1	100.00
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
    Mengest (Shanghai)                      	software1	100.00
    RACAI (București)                       	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    IMS (Stuttgart)                         	software2	100.00
24. darc (Tübingen)                         	software1	99.99
    Uppsala (Uppsala)                       	software1	99.99
    HIT-SCIR (Harbin)                       	software4	99.99
27. Wanghao-ftd-SJTU (Shanghai)             	software2	99.97
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.97
29. fbaml (Palo Alto)                       	software1	99.96
30. TRL (Tokyo)                             	software1	97.69
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_cltt

<pre>
 1. RACAI (București)                       	software1	99.82
 2. fbaml (Palo Alto)                       	software1	99.59
 3. Uppsala (Uppsala)                       	software1	99.54
 4. Wenba-NLU (Wuhan)                       	software1	99.35
    ParisNLP (Paris)                        	software1	99.35
    IIT Kharagpur (Kharagpur)               	software3	99.35
    CLCL (Genève)                           	software1	99.35
    NAIST SATO (Nara)                       	software1	99.35
    Orange – Deskiñ (Lannion)               	software1	99.35
    UParse (Edinburgh)                      	software1	99.35
    LIMSI-LIPN (Paris)                      	software2	99.35
    MQuni (Sydney)                          	software2	99.35
    LyS-FASTPARSE (A Coruña)                	software5	99.35
    TurkuNLP (Turku)                        	software1	99.35
    LATTICE (Paris)                         	software7	99.35
    naistCL (Nara)                          	software1	99.35
    UALING (Tucson)                         	software1	99.35
    Koç University (İstanbul)               	software3	99.35
    BASELINE UDPipe 1.1 (Praha)             	software2	99.35
    Stanford (Stanford)                     	software1	99.35
    METU (Ankara)                           	software2	99.35
    C2L2 (Ithaca)                           	software5	99.35
    MetaRomance (Santiago de Compostela)    	software1	99.35
    Mengest (Shanghai)                      	software1	99.35
    OpenU NLP Lab (Ra'anana)                	software6	99.35
    IMS (Stuttgart)                         	software2	99.35
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.34
28. darc (Tübingen)                         	software1	99.31
    HIT-SCIR (Harbin)                       	software4	99.31
30. Wanghao-ftd-SJTU (Shanghai)             	software2	99.25
31. TRL (Tokyo)                             	software1	88.92
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cs_pud

<pre>
 1. ParisNLP (Paris)                        	software1	99.29
    darc (Tübingen)                         	software1	99.29
    IIT Kharagpur (Kharagpur)               	software3	99.29
    CLCL (Genève)                           	software1	99.29
    NAIST SATO (Nara)                       	software1	99.29
    Orange – Deskiñ (Lannion)               	software1	99.29
    UParse (Edinburgh)                      	software1	99.29
    LIMSI-LIPN (Paris)                      	software2	99.29
    MQuni (Sydney)                          	software2	99.29
    LyS-FASTPARSE (A Coruña)                	software5	99.29
    TurkuNLP (Turku)                        	software1	99.29
    LATTICE (Paris)                         	software7	99.29
    naistCL (Nara)                          	software1	99.29
    UALING (Tucson)                         	software1	99.29
    Koç University (İstanbul)               	software3	99.29
    BASELINE UDPipe 1.1 (Praha)             	software2	99.29
    Stanford (Stanford)                     	software1	99.29
    METU (Ankara)                           	software2	99.29
    C2L2 (Ithaca)                           	software5	99.29
    MetaRomance (Santiago de Compostela)    	software1	99.29
    Mengest (Shanghai)                      	software1	99.29
    OpenU NLP Lab (Ra'anana)                	software6	99.29
    IMS (Stuttgart)                         	software2	99.29
24. Wanghao-ftd-SJTU (Shanghai)             	software2	99.28
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.28
    HIT-SCIR (Harbin)                       	software4	99.28
27. fbaml (Palo Alto)                       	software1	98.47
28. Uppsala (Uppsala)                       	software1	98.41
29. RACAI (București)                       	software1	97.98
30. TRL (Tokyo)                             	software1	97.83
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### cu

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    darc (Tübingen)                         	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
    fbaml (Palo Alto)                       	software1	100.00
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.99
 6. TRL (Tokyo)                             	software1	99.97
 7. Wenba-NLU (Wuhan)                       	software1	99.96
    ECNU (Shanghai)                         	software1	99.96
    ParisNLP (Paris)                        	software1	99.96
    IIT Kharagpur (Kharagpur)               	software3	99.96
    CLCL (Genève)                           	software1	99.96
    NAIST SATO (Nara)                       	software1	99.96
    Orange – Deskiñ (Lannion)               	software1	99.96
    UParse (Edinburgh)                      	software1	99.96
    LIMSI-LIPN (Paris)                      	software2	99.96
    MQuni (Sydney)                          	software2	99.96
    LyS-FASTPARSE (A Coruña)                	software5	99.96
    TurkuNLP (Turku)                        	software1	99.96
    LATTICE (Paris)                         	software7	99.96
    naistCL (Nara)                          	software1	99.96
    UALING (Tucson)                         	software1	99.96
    Koç University (İstanbul)               	software3	99.96
    BASELINE UDPipe 1.1 (Praha)             	software2	99.96
    Stanford (Stanford)                     	software1	99.96
    METU (Ankara)                           	software2	99.96
    C2L2 (Ithaca)                           	software5	99.96
    MetaRomance (Santiago de Compostela)    	software1	99.96
    Mengest (Shanghai)                      	software1	99.96
    RACAI (București)                       	software1	99.96
    OpenU NLP Lab (Ra'anana)                	software6	99.96
    UT (Tartu)                              	software1	99.96
    IMS (Stuttgart)                         	software2	99.96
33. Uppsala (Uppsala)                       	software1	99.73
</pre>



### da

<pre>
 1. ParisNLP (Paris)                        	software1	100.00
    RACAI (București)                       	software1	100.00
    fbaml (Palo Alto)                       	software1	100.00
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	99.96
    HIT-SCIR (Harbin)                       	software4	99.96
 6. Uppsala (Uppsala)                       	software1	99.93
 7. darc (Tübingen)                         	software1	99.70
 8. Wenba-NLU (Wuhan)                       	software1	99.69
    ECNU (Shanghai)                         	software1	99.69
    IIT Kharagpur (Kharagpur)               	software3	99.69
    CLCL (Genève)                           	software1	99.69
    NAIST SATO (Nara)                       	software1	99.69
    Orange – Deskiñ (Lannion)               	software1	99.69
    UParse (Edinburgh)                      	software1	99.69
    LIMSI-LIPN (Paris)                      	software2	99.69
    MQuni (Sydney)                          	software2	99.69
    LyS-FASTPARSE (A Coruña)                	software5	99.69
    TurkuNLP (Turku)                        	software1	99.69
    LATTICE (Paris)                         	software7	99.69
    naistCL (Nara)                          	software1	99.69
    UALING (Tucson)                         	software1	99.69
    Koç University (İstanbul)               	software3	99.69
    BASELINE UDPipe 1.1 (Praha)             	software2	99.69
    Stanford (Stanford)                     	software1	99.69
    METU (Ankara)                           	software2	99.69
    C2L2 (Ithaca)                           	software5	99.69
    MetaRomance (Santiago de Compostela)    	software1	99.69
    Mengest (Shanghai)                      	software1	99.69
    OpenU NLP Lab (Ra'anana)                	software6	99.69
    UT (Tartu)                              	software1	99.69
    IMS (Stuttgart)                         	software2	99.69
32. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.60
33. TRL (Tokyo)                             	software1	93.61
</pre>



### de

<pre>
 1. darc (Tübingen)                         	software1	99.67
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.67
    HIT-SCIR (Harbin)                       	software4	99.67
 4. Wenba-NLU (Wuhan)                       	software1	99.64
    ParisNLP (Paris)                        	software1	99.64
    IIT Kharagpur (Kharagpur)               	software3	99.64
    CLCL (Genève)                           	software1	99.64
    NAIST SATO (Nara)                       	software1	99.64
    Orange – Deskiñ (Lannion)               	software1	99.64
    UParse (Edinburgh)                      	software1	99.64
    LIMSI-LIPN (Paris)                      	software2	99.64
    MQuni (Sydney)                          	software2	99.64
    LyS-FASTPARSE (A Coruña)                	software5	99.64
    TurkuNLP (Turku)                        	software1	99.64
    LATTICE (Paris)                         	software7	99.64
    naistCL (Nara)                          	software1	99.64
    UALING (Tucson)                         	software1	99.64
    Koç University (İstanbul)               	software3	99.64
    BASELINE UDPipe 1.1 (Praha)             	software2	99.64
    Stanford (Stanford)                     	software1	99.64
    METU (Ankara)                           	software2	99.64
    C2L2 (Ithaca)                           	software5	99.64
    MetaRomance (Santiago de Compostela)    	software1	99.64
    Mengest (Shanghai)                      	software1	99.64
    OpenU NLP Lab (Ra'anana)                	software6	99.64
    IMS (Stuttgart)                         	software2	99.64
27. fbaml (Palo Alto)                       	software1	99.60
28. Wanghao-ftd-SJTU (Shanghai)             	software2	99.58
29. Uppsala (Uppsala)                       	software1	99.44
    RACAI (București)                       	software1	99.44
31. TRL (Tokyo)                             	software1	92.25
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### de_pud

<pre>
 1. ParisNLP (Paris)                        	software1	97.97
    darc (Tübingen)                         	software1	97.97
    IIT Kharagpur (Kharagpur)               	software3	97.97
    CLCL (Genève)                           	software1	97.97
    NAIST SATO (Nara)                       	software1	97.97
    Orange – Deskiñ (Lannion)               	software1	97.97
    UParse (Edinburgh)                      	software1	97.97
    LIMSI-LIPN (Paris)                      	software2	97.97
    MQuni (Sydney)                          	software2	97.97
    LyS-FASTPARSE (A Coruña)                	software5	97.97
    TurkuNLP (Turku)                        	software1	97.97
    LATTICE (Paris)                         	software7	97.97
    naistCL (Nara)                          	software1	97.97
    UALING (Tucson)                         	software1	97.97
    Koç University (İstanbul)               	software3	97.97
    BASELINE UDPipe 1.1 (Praha)             	software2	97.97
    Stanford (Stanford)                     	software1	97.97
    METU (Ankara)                           	software2	97.97
    C2L2 (Ithaca)                           	software5	97.97
    MetaRomance (Santiago de Compostela)    	software1	97.97
    Mengest (Shanghai)                      	software1	97.97
    OpenU NLP Lab (Ra'anana)                	software6	97.97
    IMS (Stuttgart)                         	software2	97.97
24. Wanghao-ftd-SJTU (Shanghai)             	software2	97.96
25. HIT-SCIR (Harbin)                       	software4	97.91
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	97.90
27. RACAI (București)                       	software1	96.72
28. Uppsala (Uppsala)                       	software1	96.67
29. fbaml (Palo Alto)                       	software1	96.52
30. TRL (Tokyo)                             	software1	95.27
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### el

<pre>
 1. darc (Tübingen)                         	software1	99.94
    HIT-SCIR (Harbin)                       	software4	99.94
 3. Wenba-NLU (Wuhan)                       	software1	99.88
    ECNU (Shanghai)                         	software1	99.88
    IIT Kharagpur (Kharagpur)               	software3	99.88
    CLCL (Genève)                           	software1	99.88
    NAIST SATO (Nara)                       	software1	99.88
    Orange – Deskiñ (Lannion)               	software1	99.88
    UParse (Edinburgh)                      	software1	99.88
    LIMSI-LIPN (Paris)                      	software2	99.88
    MQuni (Sydney)                          	software2	99.88
    LyS-FASTPARSE (A Coruña)                	software5	99.88
    TurkuNLP (Turku)                        	software1	99.88
    LATTICE (Paris)                         	software7	99.88
    naistCL (Nara)                          	software1	99.88
    UALING (Tucson)                         	software1	99.88
    Koç University (İstanbul)               	software3	99.88
    BASELINE UDPipe 1.1 (Praha)             	software2	99.88
    Stanford (Stanford)                     	software1	99.88
    METU (Ankara)                           	software2	99.88
    C2L2 (Ithaca)                           	software5	99.88
    MetaRomance (Santiago de Compostela)    	software1	99.88
    Mengest (Shanghai)                      	software1	99.88
    OpenU NLP Lab (Ra'anana)                	software6	99.88
    UT (Tartu)                              	software1	99.88
    IMS (Stuttgart)                         	software2	99.88
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.87
28. Uppsala (Uppsala)                       	software1	99.83
    RACAI (București)                       	software1	99.83
30. Wanghao-ftd-SJTU (Shanghai)             	software2	99.76
31. ParisNLP (Paris)                        	software1	99.70
32. fbaml (Palo Alto)                       	software1	99.68
33. TRL (Tokyo)                             	software1	98.12
</pre>



### en

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.03
 2. fbaml (Palo Alto)                       	software1	98.98
 3. darc (Tübingen)                         	software1	98.96
    HIT-SCIR (Harbin)                       	software4	98.96
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	98.83
 6. Wenba-NLU (Wuhan)                       	software1	98.67
    ParisNLP (Paris)                        	software1	98.67
    IIT Kharagpur (Kharagpur)               	software3	98.67
    CLCL (Genève)                           	software1	98.67
    NAIST SATO (Nara)                       	software1	98.67
    Orange – Deskiñ (Lannion)               	software1	98.67
    UParse (Edinburgh)                      	software1	98.67
    LIMSI-LIPN (Paris)                      	software2	98.67
    MQuni (Sydney)                          	software2	98.67
    LyS-FASTPARSE (A Coruña)                	software5	98.67
    TurkuNLP (Turku)                        	software1	98.67
    LATTICE (Paris)                         	software7	98.67
    naistCL (Nara)                          	software1	98.67
    UALING (Tucson)                         	software1	98.67
    Koç University (İstanbul)               	software3	98.67
    BASELINE UDPipe 1.1 (Praha)             	software2	98.67
    Stanford (Stanford)                     	software1	98.67
    METU (Ankara)                           	software2	98.67
    C2L2 (Ithaca)                           	software5	98.67
    MetaRomance (Santiago de Compostela)    	software1	98.67
    Mengest (Shanghai)                      	software1	98.67
    RACAI (București)                       	software1	98.67
    OpenU NLP Lab (Ra'anana)                	software6	98.67
    IMS (Stuttgart)                         	software2	98.67
30. Uppsala (Uppsala)                       	software1	98.38
31. TRL (Tokyo)                             	software1	94.31
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_lines

<pre>
 1. fbaml (Palo Alto)                       	software1	99.96
 2. Wenba-NLU (Wuhan)                       	software1	99.94
    ECNU (Shanghai)                         	software1	99.94
    ParisNLP (Paris)                        	software1	99.94
    IIT Kharagpur (Kharagpur)               	software3	99.94
    CLCL (Genève)                           	software1	99.94
    NAIST SATO (Nara)                       	software1	99.94
    Orange – Deskiñ (Lannion)               	software1	99.94
    UParse (Edinburgh)                      	software1	99.94
    LIMSI-LIPN (Paris)                      	software2	99.94
    MQuni (Sydney)                          	software2	99.94
    LyS-FASTPARSE (A Coruña)                	software5	99.94
    TurkuNLP (Turku)                        	software1	99.94
    LATTICE (Paris)                         	software7	99.94
    naistCL (Nara)                          	software1	99.94
    UALING (Tucson)                         	software1	99.94
    Koç University (İstanbul)               	software3	99.94
    BASELINE UDPipe 1.1 (Praha)             	software2	99.94
    Stanford (Stanford)                     	software1	99.94
    METU (Ankara)                           	software2	99.94
    C2L2 (Ithaca)                           	software5	99.94
    MetaRomance (Santiago de Compostela)    	software1	99.94
    Mengest (Shanghai)                      	software1	99.94
    OpenU NLP Lab (Ra'anana)                	software6	99.94
    UT (Tartu)                              	software1	99.94
    IMS (Stuttgart)                         	software2	99.94
27. Wanghao-ftd-SJTU (Shanghai)             	software2	99.93
28. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.92
    RACAI (București)                       	software1	99.92
30. darc (Tübingen)                         	software1	99.91
    HIT-SCIR (Harbin)                       	software4	99.91
32. Uppsala (Uppsala)                       	software1	99.82
33. TRL (Tokyo)                             	software1	98.63
</pre>



### en_partut

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.63
 2. darc (Tübingen)                         	software1	99.57
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.57
    HIT-SCIR (Harbin)                       	software4	99.57
 5. Uppsala (Uppsala)                       	software1	99.54
 6. Wenba-NLU (Wuhan)                       	software1	99.51
    ParisNLP (Paris)                        	software1	99.51
    IIT Kharagpur (Kharagpur)               	software3	99.51
    CLCL (Genève)                           	software1	99.51
    NAIST SATO (Nara)                       	software1	99.51
    Orange – Deskiñ (Lannion)               	software1	99.51
    UParse (Edinburgh)                      	software1	99.51
    LIMSI-LIPN (Paris)                      	software2	99.51
    MQuni (Sydney)                          	software2	99.51
    LyS-FASTPARSE (A Coruña)                	software5	99.51
    TurkuNLP (Turku)                        	software1	99.51
    LATTICE (Paris)                         	software7	99.51
    naistCL (Nara)                          	software1	99.51
    UALING (Tucson)                         	software1	99.51
    Koç University (İstanbul)               	software3	99.51
    BASELINE UDPipe 1.1 (Praha)             	software2	99.51
    Stanford (Stanford)                     	software1	99.51
    METU (Ankara)                           	software2	99.51
    C2L2 (Ithaca)                           	software5	99.51
    MetaRomance (Santiago de Compostela)    	software1	99.51
    Mengest (Shanghai)                      	software1	99.51
    RACAI (București)                       	software1	99.51
    OpenU NLP Lab (Ra'anana)                	software6	99.51
    IMS (Stuttgart)                         	software2	99.51
30. fbaml (Palo Alto)                       	software1	99.47
31. TRL (Tokyo)                             	software1	99.43
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### en_pud

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.74
 2. HIT-SCIR (Harbin)                       	software4	99.73
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.70
 4. ECNU (Shanghai)                         	software1	99.66
    ParisNLP (Paris)                        	software1	99.66
    darc (Tübingen)                         	software1	99.66
    IIT Kharagpur (Kharagpur)               	software3	99.66
    CLCL (Genève)                           	software1	99.66
    NAIST SATO (Nara)                       	software1	99.66
    Orange – Deskiñ (Lannion)               	software1	99.66
    UParse (Edinburgh)                      	software1	99.66
    LIMSI-LIPN (Paris)                      	software2	99.66
    MQuni (Sydney)                          	software2	99.66
    LyS-FASTPARSE (A Coruña)                	software5	99.66
    TurkuNLP (Turku)                        	software1	99.66
    LATTICE (Paris)                         	software7	99.66
    naistCL (Nara)                          	software1	99.66
    UALING (Tucson)                         	software1	99.66
    Koç University (İstanbul)               	software3	99.66
    BASELINE UDPipe 1.1 (Praha)             	software2	99.66
    Stanford (Stanford)                     	software1	99.66
    METU (Ankara)                           	software2	99.66
    C2L2 (Ithaca)                           	software5	99.66
    MetaRomance (Santiago de Compostela)    	software1	99.66
    Mengest (Shanghai)                      	software1	99.66
    RACAI (București)                       	software1	99.66
    OpenU NLP Lab (Ra'anana)                	software6	99.66
    UT (Tartu)                              	software1	99.66
    IMS (Stuttgart)                         	software2	99.66
30. fbaml (Palo Alto)                       	software1	99.59
31. Uppsala (Uppsala)                       	software1	99.45
32. TRL (Tokyo)                             	software1	99.04
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### es

<pre>
 1. fbaml (Palo Alto)                       	software1	99.97
 2. darc (Tübingen)                         	software1	99.94
    HIT-SCIR (Harbin)                       	software4	99.94
    RACAI (București)                       	software1	99.94
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	99.91
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.91
 7. ParisNLP (Paris)                        	software1	99.87
    IIT Kharagpur (Kharagpur)               	software3	99.87
    NAIST SATO (Nara)                       	software1	99.87
    Orange – Deskiñ (Lannion)               	software1	99.87
    UParse (Edinburgh)                      	software1	99.87
    LIMSI-LIPN (Paris)                      	software2	99.87
    MQuni (Sydney)                          	software2	99.87
    LyS-FASTPARSE (A Coruña)                	software5	99.87
    TurkuNLP (Turku)                        	software1	99.87
    LATTICE (Paris)                         	software7	99.87
    naistCL (Nara)                          	software1	99.87
    UALING (Tucson)                         	software1	99.87
    Koç University (İstanbul)               	software3	99.87
    BASELINE UDPipe 1.1 (Praha)             	software2	99.87
    Stanford (Stanford)                     	software1	99.87
    METU (Ankara)                           	software2	99.87
    C2L2 (Ithaca)                           	software5	99.87
    MetaRomance (Santiago de Compostela)    	software1	99.87
    Mengest (Shanghai)                      	software1	99.87
    OpenU NLP Lab (Ra'anana)                	software6	99.87
    CLCL (Genève)                           	software2	99.87
    IMS (Stuttgart)                         	software2	99.87
29. Uppsala (Uppsala)                       	software1	99.37
30. TRL (Tokyo)                             	software1	98.32
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_ancora

<pre>
 1. ParisNLP (Paris)                        	software1	99.97
    IIT Kharagpur (Kharagpur)               	software3	99.97
    NAIST SATO (Nara)                       	software1	99.97
    Orange – Deskiñ (Lannion)               	software1	99.97
    UParse (Edinburgh)                      	software1	99.97
    LIMSI-LIPN (Paris)                      	software2	99.97
    MQuni (Sydney)                          	software2	99.97
    LyS-FASTPARSE (A Coruña)                	software5	99.97
    TurkuNLP (Turku)                        	software1	99.97
    LATTICE (Paris)                         	software7	99.97
    naistCL (Nara)                          	software1	99.97
    UALING (Tucson)                         	software1	99.97
    Koç University (İstanbul)               	software3	99.97
    BASELINE UDPipe 1.1 (Praha)             	software2	99.97
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.97
    Stanford (Stanford)                     	software1	99.97
    METU (Ankara)                           	software2	99.97
    C2L2 (Ithaca)                           	software5	99.97
    fbaml (Palo Alto)                       	software1	99.97
    MetaRomance (Santiago de Compostela)    	software1	99.97
    Mengest (Shanghai)                      	software1	99.97
    OpenU NLP Lab (Ra'anana)                	software6	99.97
    CLCL (Genève)                           	software2	99.97
    IMS (Stuttgart)                         	software2	99.97
25. Wanghao-ftd-SJTU (Shanghai)             	software2	99.96
26. RACAI (București)                       	software1	99.95
27. darc (Tübingen)                         	software1	99.93
    HIT-SCIR (Harbin)                       	software4	99.93
29. Uppsala (Uppsala)                       	software1	99.49
30. TRL (Tokyo)                             	software1	98.07
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### es_pud

<pre>
 1. HIT-SCIR (Harbin)                       	software4	99.54
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	99.53
    RACAI (București)                       	software1	99.53
 4. ParisNLP (Paris)                        	software1	99.52
    darc (Tübingen)                         	software1	99.52
    IIT Kharagpur (Kharagpur)               	software3	99.52
    CLCL (Genève)                           	software1	99.52
    NAIST SATO (Nara)                       	software1	99.52
    Orange – Deskiñ (Lannion)               	software1	99.52
    UParse (Edinburgh)                      	software1	99.52
    LIMSI-LIPN (Paris)                      	software2	99.52
    MQuni (Sydney)                          	software2	99.52
    LyS-FASTPARSE (A Coruña)                	software5	99.52
    TurkuNLP (Turku)                        	software1	99.52
    LATTICE (Paris)                         	software7	99.52
    naistCL (Nara)                          	software1	99.52
    UALING (Tucson)                         	software1	99.52
    Koç University (İstanbul)               	software3	99.52
    BASELINE UDPipe 1.1 (Praha)             	software2	99.52
    Stanford (Stanford)                     	software1	99.52
    METU (Ankara)                           	software2	99.52
    C2L2 (Ithaca)                           	software5	99.52
    MetaRomance (Santiago de Compostela)    	software1	99.52
    Mengest (Shanghai)                      	software1	99.52
    OpenU NLP Lab (Ra'anana)                	software6	99.52
    IMS (Stuttgart)                         	software2	99.52
27. fbaml (Palo Alto)                       	software1	99.51
28. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.48
29. Uppsala (Uppsala)                       	software1	99.05
30. TRL (Tokyo)                             	software1	99.04
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### et

<pre>
 1. darc (Tübingen)                         	software1	99.89
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.89
    HIT-SCIR (Harbin)                       	software4	99.89
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	99.85
    RACAI (București)                       	software1	99.85
 6. Wenba-NLU (Wuhan)                       	software1	99.77
    ECNU (Shanghai)                         	software1	99.77
    IIT Kharagpur (Kharagpur)               	software3	99.77
    CLCL (Genève)                           	software1	99.77
    NAIST SATO (Nara)                       	software1	99.77
    Orange – Deskiñ (Lannion)               	software1	99.77
    UParse (Edinburgh)                      	software1	99.77
    LIMSI-LIPN (Paris)                      	software2	99.77
    MQuni (Sydney)                          	software2	99.77
    LyS-FASTPARSE (A Coruña)                	software5	99.77
    TurkuNLP (Turku)                        	software1	99.77
    LATTICE (Paris)                         	software7	99.77
    naistCL (Nara)                          	software1	99.77
    UALING (Tucson)                         	software1	99.77
    Koç University (İstanbul)               	software3	99.77
    BASELINE UDPipe 1.1 (Praha)             	software2	99.77
    Stanford (Stanford)                     	software1	99.77
    METU (Ankara)                           	software2	99.77
    C2L2 (Ithaca)                           	software5	99.77
    MetaRomance (Santiago de Compostela)    	software1	99.77
    Mengest (Shanghai)                      	software1	99.77
    OpenU NLP Lab (Ra'anana)                	software6	99.77
    UT (Tartu)                              	software1	99.77
    IMS (Stuttgart)                         	software2	99.77
30. Uppsala (Uppsala)                       	software1	99.69
31. ParisNLP (Paris)                        	software1	99.54
32. fbaml (Palo Alto)                       	software1	99.28
33. TRL (Tokyo)                             	software1	98.73
</pre>



### eu

<pre>
 1. fbaml (Palo Alto)                       	software1	99.99
 2. RACAI (București)                       	software1	99.98
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.97
    darc (Tübingen)                         	software1	99.97
    Uppsala (Uppsala)                       	software1	99.97
    HIT-SCIR (Harbin)                       	software4	99.97
 7. Wenba-NLU (Wuhan)                       	software1	99.96
    ECNU (Shanghai)                         	software1	99.96
    ParisNLP (Paris)                        	software1	99.96
    IIT Kharagpur (Kharagpur)               	software3	99.96
    NAIST SATO (Nara)                       	software1	99.96
    Orange – Deskiñ (Lannion)               	software1	99.96
    UParse (Edinburgh)                      	software1	99.96
    LIMSI-LIPN (Paris)                      	software2	99.96
    MQuni (Sydney)                          	software2	99.96
    LyS-FASTPARSE (A Coruña)                	software5	99.96
    TurkuNLP (Turku)                        	software1	99.96
    LATTICE (Paris)                         	software7	99.96
    naistCL (Nara)                          	software1	99.96
    UALING (Tucson)                         	software1	99.96
    Koç University (İstanbul)               	software3	99.96
    BASELINE UDPipe 1.1 (Praha)             	software2	99.96
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.96
    Stanford (Stanford)                     	software1	99.96
    METU (Ankara)                           	software2	99.96
    C2L2 (Ithaca)                           	software5	99.96
    MetaRomance (Santiago de Compostela)    	software1	99.96
    Mengest (Shanghai)                      	software1	99.96
    OpenU NLP Lab (Ra'anana)                	software6	99.96
    CLCL (Genève)                           	software2	99.96
    UT (Tartu)                              	software1	99.96
    IMS (Stuttgart)                         	software2	99.96
33. TRL (Tokyo)                             	software1	97.52
</pre>



### fa

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    Wenba-NLU (Wuhan)                       	software1	100.00
    ParisNLP (Paris)                        	software1	100.00
    darc (Tübingen)                         	software1	100.00
    IIT Kharagpur (Kharagpur)               	software3	100.00
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
    fbaml (Palo Alto)                       	software1	100.00
    MetaRomance (Santiago de Compostela)    	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
    Mengest (Shanghai)                      	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    CLCL (Genève)                           	software2	100.00
    IMS (Stuttgart)                         	software2	100.00
29. TRL (Tokyo)                             	software1	99.99
    RACAI (București)                       	software1	99.99
31. Uppsala (Uppsala)                       	software1	99.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.69
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	99.66
 3. darc (Tübingen)                         	software1	99.64
    HIT-SCIR (Harbin)                       	software4	99.64
 5. Wenba-NLU (Wuhan)                       	software1	99.63
    IIT Kharagpur (Kharagpur)               	software3	99.63
    NAIST SATO (Nara)                       	software1	99.63
    Orange – Deskiñ (Lannion)               	software1	99.63
    UParse (Edinburgh)                      	software1	99.63
    LIMSI-LIPN (Paris)                      	software2	99.63
    MQuni (Sydney)                          	software2	99.63
    LyS-FASTPARSE (A Coruña)                	software5	99.63
    TurkuNLP (Turku)                        	software1	99.63
    LATTICE (Paris)                         	software7	99.63
    naistCL (Nara)                          	software1	99.63
    UALING (Tucson)                         	software1	99.63
    Koç University (İstanbul)               	software3	99.63
    BASELINE UDPipe 1.1 (Praha)             	software2	99.63
    Stanford (Stanford)                     	software1	99.63
    METU (Ankara)                           	software2	99.63
    C2L2 (Ithaca)                           	software5	99.63
    MetaRomance (Santiago de Compostela)    	software1	99.63
    Mengest (Shanghai)                      	software1	99.63
    OpenU NLP Lab (Ra'anana)                	software6	99.63
    CLCL (Genève)                           	software2	99.63
    UT (Tartu)                              	software1	99.63
    IMS (Stuttgart)                         	software2	99.63
28. Uppsala (Uppsala)                       	software1	99.62
29. fbaml (Palo Alto)                       	software1	99.60
30. RACAI (București)                       	software1	99.46
31. ParisNLP (Paris)                        	software1	99.41
32. TRL (Tokyo)                             	software1	96.10
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### fi_ftb

<pre>
 1. fbaml (Palo Alto)                       	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.99
    ParisNLP (Paris)                        	software1	99.99
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.97
 6. darc (Tübingen)                         	software1	99.96
 7. Wenba-NLU (Wuhan)                       	software1	99.90
    IIT Kharagpur (Kharagpur)               	software3	99.90
    NAIST SATO (Nara)                       	software1	99.90
    Orange – Deskiñ (Lannion)               	software1	99.90
    UParse (Edinburgh)                      	software1	99.90
    LIMSI-LIPN (Paris)                      	software2	99.90
    MQuni (Sydney)                          	software2	99.90
    LyS-FASTPARSE (A Coruña)                	software5	99.90
    TurkuNLP (Turku)                        	software1	99.90
    LATTICE (Paris)                         	software7	99.90
    naistCL (Nara)                          	software1	99.90
    UALING (Tucson)                         	software1	99.90
    Koç University (İstanbul)               	software3	99.90
    BASELINE UDPipe 1.1 (Praha)             	software2	99.90
    Stanford (Stanford)                     	software1	99.90
    METU (Ankara)                           	software2	99.90
    C2L2 (Ithaca)                           	software5	99.90
    MetaRomance (Santiago de Compostela)    	software1	99.90
    Mengest (Shanghai)                      	software1	99.90
    RACAI (București)                       	software1	99.90
    OpenU NLP Lab (Ra'anana)                	software6	99.90
    CLCL (Genève)                           	software2	99.90
    IMS (Stuttgart)                         	software2	99.90
30. Uppsala (Uppsala)                       	software1	99.70
31. TRL (Tokyo)                             	software1	98.89
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fi_pud

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.63
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	99.61
    ECNU (Shanghai)                         	software1	99.61
    ParisNLP (Paris)                        	software1	99.61
    darc (Tübingen)                         	software1	99.61
    IIT Kharagpur (Kharagpur)               	software3	99.61
    CLCL (Genève)                           	software1	99.61
    NAIST SATO (Nara)                       	software1	99.61
    Orange – Deskiñ (Lannion)               	software1	99.61
    UParse (Edinburgh)                      	software1	99.61
    LIMSI-LIPN (Paris)                      	software2	99.61
    MQuni (Sydney)                          	software2	99.61
    LyS-FASTPARSE (A Coruña)                	software5	99.61
    TurkuNLP (Turku)                        	software1	99.61
    LATTICE (Paris)                         	software7	99.61
    naistCL (Nara)                          	software1	99.61
    UALING (Tucson)                         	software1	99.61
    Koç University (İstanbul)               	software3	99.61
    BASELINE UDPipe 1.1 (Praha)             	software2	99.61
    Stanford (Stanford)                     	software1	99.61
    METU (Ankara)                           	software2	99.61
    C2L2 (Ithaca)                           	software5	99.61
    MetaRomance (Santiago de Compostela)    	software1	99.61
    HIT-SCIR (Harbin)                       	software4	99.61
    Mengest (Shanghai)                      	software1	99.61
    OpenU NLP Lab (Ra'anana)                	software6	99.61
    IMS (Stuttgart)                         	software2	99.61
28. fbaml (Palo Alto)                       	software1	99.56
29. Uppsala (Uppsala)                       	software1	99.39
    RACAI (București)                       	software1	99.39
31. TRL (Tokyo)                             	software1	96.28
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.76
 2. Wenba-NLU (Wuhan)                       	software1	99.75
    ParisNLP (Paris)                        	software1	99.75
    IIT Kharagpur (Kharagpur)               	software3	99.75
    NAIST SATO (Nara)                       	software1	99.75
    Orange – Deskiñ (Lannion)               	software1	99.75
    UParse (Edinburgh)                      	software1	99.75
    LIMSI-LIPN (Paris)                      	software2	99.75
    MQuni (Sydney)                          	software2	99.75
    LyS-FASTPARSE (A Coruña)                	software5	99.75
    TurkuNLP (Turku)                        	software1	99.75
    LATTICE (Paris)                         	software7	99.75
    naistCL (Nara)                          	software1	99.75
    UALING (Tucson)                         	software1	99.75
    Koç University (İstanbul)               	software3	99.75
    BASELINE UDPipe 1.1 (Praha)             	software2	99.75
    Stanford (Stanford)                     	software1	99.75
    METU (Ankara)                           	software2	99.75
    C2L2 (Ithaca)                           	software5	99.75
    MetaRomance (Santiago de Compostela)    	software1	99.75
    Mengest (Shanghai)                      	software1	99.75
    OpenU NLP Lab (Ra'anana)                	software6	99.75
    CLCL (Genève)                           	software2	99.75
    IMS (Stuttgart)                         	software2	99.75
25. fbaml (Palo Alto)                       	software1	99.73
26. RACAI (București)                       	software1	99.72
27. Uppsala (Uppsala)                       	software1	99.70
28. Wanghao-ftd-SJTU (Shanghai)             	software2	99.60
29. darc (Tübingen)                         	software1	99.55
    HIT-SCIR (Harbin)                       	software4	99.55
31. TRL (Tokyo)                             	software1	97.93
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_partut

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.89
 2. darc (Tübingen)                         	software1	99.87
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.85
 4. ParisNLP (Paris)                        	software1	99.83
    IIT Kharagpur (Kharagpur)               	software3	99.83
    NAIST SATO (Nara)                       	software1	99.83
    Orange – Deskiñ (Lannion)               	software1	99.83
    UParse (Edinburgh)                      	software1	99.83
    LIMSI-LIPN (Paris)                      	software2	99.83
    MQuni (Sydney)                          	software2	99.83
    LyS-FASTPARSE (A Coruña)                	software5	99.83
    TurkuNLP (Turku)                        	software1	99.83
    LATTICE (Paris)                         	software7	99.83
    naistCL (Nara)                          	software1	99.83
    UALING (Tucson)                         	software1	99.83
    Koç University (İstanbul)               	software3	99.83
    BASELINE UDPipe 1.1 (Praha)             	software2	99.83
    Stanford (Stanford)                     	software1	99.83
    METU (Ankara)                           	software2	99.83
    C2L2 (Ithaca)                           	software5	99.83
    MetaRomance (Santiago de Compostela)    	software1	99.83
    Mengest (Shanghai)                      	software1	99.83
    OpenU NLP Lab (Ra'anana)                	software6	99.83
    CLCL (Genève)                           	software2	99.83
    IMS (Stuttgart)                         	software2	99.83
26. HIT-SCIR (Harbin)                       	software4	99.80
27. RACAI (București)                       	software1	99.75
28. Uppsala (Uppsala)                       	software1	99.74
29. fbaml (Palo Alto)                       	software1	99.72
30. TRL (Tokyo)                             	software1	99.28
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_pud

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.82
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.81
 3. HIT-SCIR (Harbin)                       	software4	99.65
 4. ParisNLP (Paris)                        	software1	99.10
    darc (Tübingen)                         	software1	99.10
    IIT Kharagpur (Kharagpur)               	software3	99.10
    CLCL (Genève)                           	software1	99.10
    NAIST SATO (Nara)                       	software1	99.10
    Orange – Deskiñ (Lannion)               	software1	99.10
    UParse (Edinburgh)                      	software1	99.10
    LIMSI-LIPN (Paris)                      	software2	99.10
    MQuni (Sydney)                          	software2	99.10
    LyS-FASTPARSE (A Coruña)                	software5	99.10
    TurkuNLP (Turku)                        	software1	99.10
    LATTICE (Paris)                         	software7	99.10
    naistCL (Nara)                          	software1	99.10
    UALING (Tucson)                         	software1	99.10
    Koç University (İstanbul)               	software3	99.10
    BASELINE UDPipe 1.1 (Praha)             	software2	99.10
    Stanford (Stanford)                     	software1	99.10
    METU (Ankara)                           	software2	99.10
    C2L2 (Ithaca)                           	software5	99.10
    MetaRomance (Santiago de Compostela)    	software1	99.10
    Mengest (Shanghai)                      	software1	99.10
    OpenU NLP Lab (Ra'anana)                	software6	99.10
    IMS (Stuttgart)                         	software2	99.10
27. TRL (Tokyo)                             	software1	98.63
28. Uppsala (Uppsala)                       	software1	97.58
29. fbaml (Palo Alto)                       	software1	97.53
30. RACAI (București)                       	software1	97.43
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### fr_sequoia

<pre>
 1. fbaml (Palo Alto)                       	software1	99.83
 2. Wenba-NLU (Wuhan)                       	software1	99.77
    ParisNLP (Paris)                        	software1	99.77
    IIT Kharagpur (Kharagpur)               	software3	99.77
    NAIST SATO (Nara)                       	software1	99.77
    Orange – Deskiñ (Lannion)               	software1	99.77
    UParse (Edinburgh)                      	software1	99.77
    LIMSI-LIPN (Paris)                      	software2	99.77
    MQuni (Sydney)                          	software2	99.77
    LyS-FASTPARSE (A Coruña)                	software5	99.77
    TurkuNLP (Turku)                        	software1	99.77
    LATTICE (Paris)                         	software7	99.77
    naistCL (Nara)                          	software1	99.77
    UALING (Tucson)                         	software1	99.77
    Koç University (İstanbul)               	software3	99.77
    BASELINE UDPipe 1.1 (Praha)             	software2	99.77
    Stanford (Stanford)                     	software1	99.77
    METU (Ankara)                           	software2	99.77
    C2L2 (Ithaca)                           	software5	99.77
    MetaRomance (Santiago de Compostela)    	software1	99.77
    Mengest (Shanghai)                      	software1	99.77
    RACAI (București)                       	software1	99.77
    OpenU NLP Lab (Ra'anana)                	software6	99.77
    CLCL (Genève)                           	software2	99.77
    IMS (Stuttgart)                         	software2	99.77
26. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.76
27. Wanghao-ftd-SJTU (Shanghai)             	software2	99.75
28. darc (Tübingen)                         	software1	99.72
    HIT-SCIR (Harbin)                       	software4	99.72
30. Uppsala (Uppsala)                       	software1	99.63
31. TRL (Tokyo)                             	software1	97.30
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ga

<pre>
 1. RACAI (București)                       	software1	99.73
 2. fbaml (Palo Alto)                       	software1	99.64
 3. Uppsala (Uppsala)                       	software1	99.62
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	99.50
    darc (Tübingen)                         	software1	99.50
 6. HIT-SCIR (Harbin)                       	software4	99.47
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.40
 8. ParisNLP (Paris)                        	software1	99.29
    IIT Kharagpur (Kharagpur)               	software3	99.29
    NAIST SATO (Nara)                       	software1	99.29
    Orange – Deskiñ (Lannion)               	software1	99.29
    UParse (Edinburgh)                      	software1	99.29
    LIMSI-LIPN (Paris)                      	software2	99.29
    MQuni (Sydney)                          	software2	99.29
    LyS-FASTPARSE (A Coruña)                	software5	99.29
    TurkuNLP (Turku)                        	software1	99.29
    LATTICE (Paris)                         	software7	99.29
    naistCL (Nara)                          	software1	99.29
    UALING (Tucson)                         	software1	99.29
    Koç University (İstanbul)               	software3	99.29
    BASELINE UDPipe 1.1 (Praha)             	software2	99.29
    Stanford (Stanford)                     	software1	99.29
    METU (Ankara)                           	software2	99.29
    C2L2 (Ithaca)                           	software5	99.29
    MetaRomance (Santiago de Compostela)    	software1	99.29
    Mengest (Shanghai)                      	software1	99.29
    OpenU NLP Lab (Ra'anana)                	software6	99.29
    CLCL (Genève)                           	software2	99.29
    IMS (Stuttgart)                         	software2	99.29
30. TRL (Tokyo)                             	software1	96.44
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### gl

<pre>
 1. fbaml (Palo Alto)                       	software1	99.98
 2. darc (Tübingen)                         	software1	99.95
    HIT-SCIR (Harbin)                       	software4	99.95
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.93
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	99.92
    Wenba-NLU (Wuhan)                       	software1	99.92
    ECNU (Shanghai)                         	software1	99.92
    ParisNLP (Paris)                        	software1	99.92
    IIT Kharagpur (Kharagpur)               	software3	99.92
    NAIST SATO (Nara)                       	software1	99.92
    Orange – Deskiñ (Lannion)               	software1	99.92
    UParse (Edinburgh)                      	software1	99.92
    LIMSI-LIPN (Paris)                      	software2	99.92
    MQuni (Sydney)                          	software2	99.92
    LyS-FASTPARSE (A Coruña)                	software5	99.92
    TurkuNLP (Turku)                        	software1	99.92
    LATTICE (Paris)                         	software7	99.92
    naistCL (Nara)                          	software1	99.92
    UALING (Tucson)                         	software1	99.92
    Koç University (İstanbul)               	software3	99.92
    BASELINE UDPipe 1.1 (Praha)             	software2	99.92
    Stanford (Stanford)                     	software1	99.92
    METU (Ankara)                           	software2	99.92
    C2L2 (Ithaca)                           	software5	99.92
    MetaRomance (Santiago de Compostela)    	software1	99.92
    Mengest (Shanghai)                      	software1	99.92
    RACAI (București)                       	software1	99.92
    OpenU NLP Lab (Ra'anana)                	software6	99.92
    CLCL (Genève)                           	software2	99.92
    UT (Tartu)                              	software1	99.92
    IMS (Stuttgart)                         	software2	99.92
32. Uppsala (Uppsala)                       	software1	99.91
33. TRL (Tokyo)                             	software1	98.39
</pre>



### gl_treegal

<pre>
 1. HIT-SCIR (Harbin)                       	software4	99.68
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.62
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.61
    darc (Tübingen)                         	software1	99.61
 5. ParisNLP (Paris)                        	software1	99.59
    IIT Kharagpur (Kharagpur)               	software3	99.59
    NAIST SATO (Nara)                       	software1	99.59
    Orange – Deskiñ (Lannion)               	software1	99.59
    UParse (Edinburgh)                      	software1	99.59
    LIMSI-LIPN (Paris)                      	software2	99.59
    MQuni (Sydney)                          	software2	99.59
    LyS-FASTPARSE (A Coruña)                	software5	99.59
    TurkuNLP (Turku)                        	software1	99.59
    LATTICE (Paris)                         	software7	99.59
    naistCL (Nara)                          	software1	99.59
    UALING (Tucson)                         	software1	99.59
    Koç University (İstanbul)               	software3	99.59
    BASELINE UDPipe 1.1 (Praha)             	software2	99.59
    Stanford (Stanford)                     	software1	99.59
    METU (Ankara)                           	software2	99.59
    C2L2 (Ithaca)                           	software5	99.59
    MetaRomance (Santiago de Compostela)    	software1	99.59
    Mengest (Shanghai)                      	software1	99.59
    OpenU NLP Lab (Ra'anana)                	software6	99.59
    CLCL (Genève)                           	software2	99.59
    IMS (Stuttgart)                         	software2	99.59
27. fbaml (Palo Alto)                       	software1	99.52
28. TRL (Tokyo)                             	software1	99.22
29. RACAI (București)                       	software1	98.91
30. Uppsala (Uppsala)                       	software1	98.21
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### got

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    Wenba-NLU (Wuhan)                       	software1	100.00
    ECNU (Shanghai)                         	software1	100.00
    ParisNLP (Paris)                        	software1	100.00
    darc (Tübingen)                         	software1	100.00
    IIT Kharagpur (Kharagpur)               	software3	100.00
    Uppsala (Uppsala)                       	software1	100.00
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
    fbaml (Palo Alto)                       	software1	100.00
    MetaRomance (Santiago de Compostela)    	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
    Mengest (Shanghai)                      	software1	100.00
    RACAI (București)                       	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    CLCL (Genève)                           	software2	100.00
    UT (Tartu)                              	software1	100.00
    IMS (Stuttgart)                         	software2	100.00
33. TRL (Tokyo)                             	software1	99.90
</pre>



### grc

<pre>
 1. fbaml (Palo Alto)                       	software1	100.00
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	99.98
    darc (Tübingen)                         	software1	99.98
    HIT-SCIR (Harbin)                       	software4	99.98
    RACAI (București)                       	software1	99.98
 6. TRL (Tokyo)                             	software1	99.96
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.96
 8. Wenba-NLU (Wuhan)                       	software1	99.95
    ParisNLP (Paris)                        	software1	99.95
    IIT Kharagpur (Kharagpur)               	software3	99.95
    NAIST SATO (Nara)                       	software1	99.95
    Orange – Deskiñ (Lannion)               	software1	99.95
    UParse (Edinburgh)                      	software1	99.95
    LIMSI-LIPN (Paris)                      	software2	99.95
    MQuni (Sydney)                          	software2	99.95
    LyS-FASTPARSE (A Coruña)                	software5	99.95
    TurkuNLP (Turku)                        	software1	99.95
    LATTICE (Paris)                         	software7	99.95
    naistCL (Nara)                          	software1	99.95
    UALING (Tucson)                         	software1	99.95
    Koç University (İstanbul)               	software3	99.95
    BASELINE UDPipe 1.1 (Praha)             	software2	99.95
    Stanford (Stanford)                     	software1	99.95
    METU (Ankara)                           	software2	99.95
    C2L2 (Ithaca)                           	software5	99.95
    MetaRomance (Santiago de Compostela)    	software1	99.95
    Mengest (Shanghai)                      	software1	99.95
    OpenU NLP Lab (Ra'anana)                	software6	99.95
    CLCL (Genève)                           	software2	99.95
    UT (Tartu)                              	software1	99.95
    IMS (Stuttgart)                         	software2	99.95
32. Uppsala (Uppsala)                       	software1	96.78
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### grc_proiel

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    Wenba-NLU (Wuhan)                       	software1	100.00
    ParisNLP (Paris)                        	software1	100.00
    darc (Tübingen)                         	software1	100.00
    IIT Kharagpur (Kharagpur)               	software3	100.00
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
    Mengest (Shanghai)                      	software1	100.00
    RACAI (București)                       	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    CLCL (Genève)                           	software2	100.00
    fbaml (Palo Alto)                       	software1	100.00
    IMS (Stuttgart)                         	software2	100.00
30. Uppsala (Uppsala)                       	software1	99.99
31. TRL (Tokyo)                             	software1	98.93
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### he

<pre>
 1. darc (Tübingen)                         	software1	99.98
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.98
    HIT-SCIR (Harbin)                       	software4	99.98
    RACAI (București)                       	software1	99.98
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	99.94
    Wenba-NLU (Wuhan)                       	software1	99.94
    ParisNLP (Paris)                        	software1	99.94
    IIT Kharagpur (Kharagpur)               	software3	99.94
    NAIST SATO (Nara)                       	software1	99.94
    Orange – Deskiñ (Lannion)               	software1	99.94
    UParse (Edinburgh)                      	software1	99.94
    LIMSI-LIPN (Paris)                      	software2	99.94
    MQuni (Sydney)                          	software2	99.94
    LyS-FASTPARSE (A Coruña)                	software5	99.94
    TurkuNLP (Turku)                        	software1	99.94
    LATTICE (Paris)                         	software7	99.94
    naistCL (Nara)                          	software1	99.94
    UALING (Tucson)                         	software1	99.94
    Koç University (İstanbul)               	software3	99.94
    BASELINE UDPipe 1.1 (Praha)             	software2	99.94
    Stanford (Stanford)                     	software1	99.94
    METU (Ankara)                           	software2	99.94
    C2L2 (Ithaca)                           	software5	99.94
    MetaRomance (Santiago de Compostela)    	software1	99.94
    Mengest (Shanghai)                      	software1	99.94
    OpenU NLP Lab (Ra'anana)                	software6	99.94
    CLCL (Genève)                           	software2	99.94
    IMS (Stuttgart)                         	software2	99.94
29. fbaml (Palo Alto)                       	software1	99.93
30. Uppsala (Uppsala)                       	software1	63.44
31. TRL (Tokyo)                             	software1	62.07
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hi

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	100.00
    ParisNLP (Paris)                        	software1	100.00
    IIT Kharagpur (Kharagpur)               	software3	100.00
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
    Mengest (Shanghai)                      	software1	100.00
    RACAI (București)                       	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    CLCL (Genève)                           	software2	100.00
    UT (Tartu)                              	software1	100.00
    IMS (Stuttgart)                         	software2	100.00
27. Wanghao-ftd-SJTU (Shanghai)             	software2	99.99
    darc (Tübingen)                         	software1	99.99
    HIT-SCIR (Harbin)                       	software4	99.99
    fbaml (Palo Alto)                       	software1	99.99
31. TRL (Tokyo)                             	software1	99.06
32. Uppsala (Uppsala)                       	software1	92.74
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### hi_pud

<pre>
 1. TRL (Tokyo)                             	software1	99.65
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.78
 3. HIT-SCIR (Harbin)                       	software4	98.53
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	98.40
 5. ECNU (Shanghai)                         	software1	97.81
    ParisNLP (Paris)                        	software1	97.81
    darc (Tübingen)                         	software1	97.81
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
    Mengest (Shanghai)                      	software1	97.81
    OpenU NLP Lab (Ra'anana)                	software6	97.81
    UT (Tartu)                              	software1	97.81
    IMS (Stuttgart)                         	software2	97.81
30. fbaml (Palo Alto)                       	software1	92.38
31. Uppsala (Uppsala)                       	software1	92.27
    RACAI (București)                       	software1	92.27
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### hr

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	99.93
    ECNU (Shanghai)                         	software1	99.93
    ParisNLP (Paris)                        	software1	99.93
    IIT Kharagpur (Kharagpur)               	software3	99.93
    CLCL (Genève)                           	software1	99.93
    NAIST SATO (Nara)                       	software1	99.93
    Orange – Deskiñ (Lannion)               	software1	99.93
    UParse (Edinburgh)                      	software1	99.93
    LIMSI-LIPN (Paris)                      	software2	99.93
    MQuni (Sydney)                          	software2	99.93
    LyS-FASTPARSE (A Coruña)                	software5	99.93
    TurkuNLP (Turku)                        	software1	99.93
    LATTICE (Paris)                         	software7	99.93
    naistCL (Nara)                          	software1	99.93
    UALING (Tucson)                         	software1	99.93
    Koç University (İstanbul)               	software3	99.93
    BASELINE UDPipe 1.1 (Praha)             	software2	99.93
    Stanford (Stanford)                     	software1	99.93
    METU (Ankara)                           	software2	99.93
    C2L2 (Ithaca)                           	software5	99.93
    MetaRomance (Santiago de Compostela)    	software1	99.93
    Mengest (Shanghai)                      	software1	99.93
    OpenU NLP Lab (Ra'anana)                	software6	99.93
    UT (Tartu)                              	software1	99.93
    IMS (Stuttgart)                         	software2	99.93
26. darc (Tübingen)                         	software1	99.90
    Uppsala (Uppsala)                       	software1	99.90
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.90
    HIT-SCIR (Harbin)                       	software4	99.90
30. Wanghao-ftd-SJTU (Shanghai)             	software2	99.88
    fbaml (Palo Alto)                       	software1	99.88
32. RACAI (București)                       	software1	99.84
33. TRL (Tokyo)                             	software1	98.01
</pre>



### hsb

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.84
    ECNU (Shanghai)                         	software1	99.84
    ParisNLP (Paris)                        	software1	99.84
    darc (Tübingen)                         	software1	99.84
    IIT Kharagpur (Kharagpur)               	software3	99.84
    NAIST SATO (Nara)                       	software1	99.84
    Orange – Deskiñ (Lannion)               	software1	99.84
    UParse (Edinburgh)                      	software1	99.84
    LIMSI-LIPN (Paris)                      	software2	99.84
    MQuni (Sydney)                          	software2	99.84
    LyS-FASTPARSE (A Coruña)                	software5	99.84
    TurkuNLP (Turku)                        	software1	99.84
    LATTICE (Paris)                         	software7	99.84
    naistCL (Nara)                          	software1	99.84
    UALING (Tucson)                         	software1	99.84
    Koç University (İstanbul)               	software3	99.84
    BASELINE UDPipe 1.1 (Praha)             	software2	99.84
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.84
    Stanford (Stanford)                     	software1	99.84
    METU (Ankara)                           	software2	99.84
    C2L2 (Ithaca)                           	software5	99.84
    MetaRomance (Santiago de Compostela)    	software1	99.84
    HIT-SCIR (Harbin)                       	software4	99.84
    Mengest (Shanghai)                      	software1	99.84
    RACAI (București)                       	software1	99.84
    OpenU NLP Lab (Ra'anana)                	software6	99.84
    CLCL (Genève)                           	software2	99.84
    IMS (Stuttgart)                         	software2	99.84
29. TRL (Tokyo)                             	software1	99.51
30. Uppsala (Uppsala)                       	software1	99.28
31. fbaml (Palo Alto)                       	software1	94.32
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### hu

<pre>
 1. Uppsala (Uppsala)                       	software1	99.85
 2. Wenba-NLU (Wuhan)                       	software1	99.82
    ECNU (Shanghai)                         	software1	99.82
    ParisNLP (Paris)                        	software1	99.82
    IIT Kharagpur (Kharagpur)               	software3	99.82
    CLCL (Genève)                           	software1	99.82
    NAIST SATO (Nara)                       	software1	99.82
    Orange – Deskiñ (Lannion)               	software1	99.82
    UParse (Edinburgh)                      	software1	99.82
    LIMSI-LIPN (Paris)                      	software2	99.82
    MQuni (Sydney)                          	software2	99.82
    LyS-FASTPARSE (A Coruña)                	software5	99.82
    TurkuNLP (Turku)                        	software1	99.82
    LATTICE (Paris)                         	software7	99.82
    naistCL (Nara)                          	software1	99.82
    UALING (Tucson)                         	software1	99.82
    Koç University (İstanbul)               	software3	99.82
    BASELINE UDPipe 1.1 (Praha)             	software2	99.82
    Stanford (Stanford)                     	software1	99.82
    METU (Ankara)                           	software2	99.82
    C2L2 (Ithaca)                           	software5	99.82
    MetaRomance (Santiago de Compostela)    	software1	99.82
    Mengest (Shanghai)                      	software1	99.82
    OpenU NLP Lab (Ra'anana)                	software6	99.82
    UT (Tartu)                              	software1	99.82
    IMS (Stuttgart)                         	software2	99.82
27. Wanghao-ftd-SJTU (Shanghai)             	software2	99.81
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.81
29. darc (Tübingen)                         	software1	99.78
    HIT-SCIR (Harbin)                       	software4	99.78
31. fbaml (Palo Alto)                       	software1	99.75
32. RACAI (București)                       	software1	99.70
33. TRL (Tokyo)                             	software1	94.42
</pre>



### id

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    darc (Tübingen)                         	software1	100.00
    Uppsala (Uppsala)                       	software1	100.00
    ÚFAL – UDPipe 1.2 (Praha)               	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
 6. Wenba-NLU (Wuhan)                       	software1	99.99
    ECNU (Shanghai)                         	software1	99.99
    ParisNLP (Paris)                        	software1	99.99
    IIT Kharagpur (Kharagpur)               	software3	99.99
    NAIST SATO (Nara)                       	software1	99.99
    Orange – Deskiñ (Lannion)               	software1	99.99
    UParse (Edinburgh)                      	software1	99.99
    LIMSI-LIPN (Paris)                      	software2	99.99
    MQuni (Sydney)                          	software2	99.99
    LyS-FASTPARSE (A Coruña)                	software5	99.99
    TurkuNLP (Turku)                        	software1	99.99
    LATTICE (Paris)                         	software7	99.99
    naistCL (Nara)                          	software1	99.99
    UALING (Tucson)                         	software1	99.99
    Koç University (İstanbul)               	software3	99.99
    BASELINE UDPipe 1.1 (Praha)             	software2	99.99
    Stanford (Stanford)                     	software1	99.99
    METU (Ankara)                           	software2	99.99
    C2L2 (Ithaca)                           	software5	99.99
    MetaRomance (Santiago de Compostela)    	software1	99.99
    Mengest (Shanghai)                      	software1	99.99
    RACAI (București)                       	software1	99.99
    OpenU NLP Lab (Ra'anana)                	software6	99.99
    CLCL (Genève)                           	software2	99.99
    UT (Tartu)                              	software1	99.99
    IMS (Stuttgart)                         	software2	99.99
32. fbaml (Palo Alto)                       	software1	99.96
33. TRL (Tokyo)                             	software1	99.07
</pre>



### it

<pre>
 1. RACAI (București)                       	software1	99.92
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.91
 3. fbaml (Palo Alto)                       	software1	99.89
 4. ParisNLP (Paris)                        	software1	99.87
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	99.83
 6. Wenba-NLU (Wuhan)                       	software1	99.81
    IIT Kharagpur (Kharagpur)               	software3	99.81
    NAIST SATO (Nara)                       	software1	99.81
    Orange – Deskiñ (Lannion)               	software1	99.81
    UParse (Edinburgh)                      	software1	99.81
    LIMSI-LIPN (Paris)                      	software2	99.81
    MQuni (Sydney)                          	software2	99.81
    LyS-FASTPARSE (A Coruña)                	software5	99.81
    TurkuNLP (Turku)                        	software1	99.81
    LATTICE (Paris)                         	software7	99.81
    naistCL (Nara)                          	software1	99.81
    UALING (Tucson)                         	software1	99.81
    Koç University (İstanbul)               	software3	99.81
    BASELINE UDPipe 1.1 (Praha)             	software2	99.81
    Stanford (Stanford)                     	software1	99.81
    METU (Ankara)                           	software2	99.81
    C2L2 (Ithaca)                           	software5	99.81
    MetaRomance (Santiago de Compostela)    	software1	99.81
    Mengest (Shanghai)                      	software1	99.81
    OpenU NLP Lab (Ra'anana)                	software6	99.81
    CLCL (Genève)                           	software2	99.81
    IMS (Stuttgart)                         	software2	99.81
28. darc (Tübingen)                         	software1	99.80
    HIT-SCIR (Harbin)                       	software4	99.80
30. TRL (Tokyo)                             	software1	99.53
31. Uppsala (Uppsala)                       	software1	98.92
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### it_pud

<pre>
 1. fbaml (Palo Alto)                       	software1	99.68
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.64
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.62
 4. RACAI (București)                       	software1	99.60
 5. ParisNLP (Paris)                        	software1	99.59
    darc (Tübingen)                         	software1	99.59
    IIT Kharagpur (Kharagpur)               	software3	99.59
    CLCL (Genève)                           	software1	99.59
    NAIST SATO (Nara)                       	software1	99.59
    Orange – Deskiñ (Lannion)               	software1	99.59
    UParse (Edinburgh)                      	software1	99.59
    LIMSI-LIPN (Paris)                      	software2	99.59
    MQuni (Sydney)                          	software2	99.59
    LyS-FASTPARSE (A Coruña)                	software5	99.59
    TurkuNLP (Turku)                        	software1	99.59
    LATTICE (Paris)                         	software7	99.59
    naistCL (Nara)                          	software1	99.59
    UALING (Tucson)                         	software1	99.59
    Koç University (İstanbul)               	software3	99.59
    BASELINE UDPipe 1.1 (Praha)             	software2	99.59
    Stanford (Stanford)                     	software1	99.59
    METU (Ankara)                           	software2	99.59
    C2L2 (Ithaca)                           	software5	99.59
    MetaRomance (Santiago de Compostela)    	software1	99.59
    HIT-SCIR (Harbin)                       	software4	99.59
    Mengest (Shanghai)                      	software1	99.59
    OpenU NLP Lab (Ra'anana)                	software6	99.59
    IMS (Stuttgart)                         	software2	99.59
29. TRL (Tokyo)                             	software1	99.23
30. Uppsala (Uppsala)                       	software1	98.68
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ja

<pre>
 1. TRL (Tokyo)                             	software1	98.59
 2. LIMSI-LIPN (Paris)                      	software2	93.82
 3. fbaml (Palo Alto)                       	software1	93.32
 4. HIT-SCIR (Harbin)                       	software4	92.95
 5. ParisNLP (Paris)                        	software1	92.57
 6. IMS (Stuttgart)                         	software2	91.68
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	90.97
 8. darc (Tübingen)                         	software1	89.78
 9. Wenba-NLU (Wuhan)                       	software1	89.68
    ECNU (Shanghai)                         	software1	89.68
    IIT Kharagpur (Kharagpur)               	software3	89.68
    NAIST SATO (Nara)                       	software1	89.68
    Orange – Deskiñ (Lannion)               	software1	89.68
    UParse (Edinburgh)                      	software1	89.68
    MQuni (Sydney)                          	software2	89.68
    LyS-FASTPARSE (A Coruña)                	software5	89.68
    TurkuNLP (Turku)                        	software1	89.68
    LATTICE (Paris)                         	software7	89.68
    naistCL (Nara)                          	software1	89.68
    UALING (Tucson)                         	software1	89.68
    Koç University (İstanbul)               	software3	89.68
    BASELINE UDPipe 1.1 (Praha)             	software2	89.68
    Stanford (Stanford)                     	software1	89.68
    METU (Ankara)                           	software2	89.68
    C2L2 (Ithaca)                           	software5	89.68
    MetaRomance (Santiago de Compostela)    	software1	89.68
    Mengest (Shanghai)                      	software1	89.68
    OpenU NLP Lab (Ra'anana)                	software6	89.68
    CLCL (Genève)                           	software2	89.68
    UT (Tartu)                              	software1	89.68
31. Wanghao-ftd-SJTU (Shanghai)             	software2	89.46
32. RACAI (București)                       	software1	87.57
33. Uppsala (Uppsala)                       	software1	84.26
</pre>



### ja_pud

<pre>
 1. LIMSI-LIPN (Paris)                      	software2	94.93
 2. HIT-SCIR (Harbin)                       	software4	94.02
 3. fbaml (Palo Alto)                       	software1	93.57
 4. IMS (Stuttgart)                         	software2	93.44
 5. TRL (Tokyo)                             	software1	93.16
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	92.41
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	91.16
 8. ECNU (Shanghai)                         	software1	91.06
    ParisNLP (Paris)                        	software1	91.06
    darc (Tübingen)                         	software1	91.06
    IIT Kharagpur (Kharagpur)               	software3	91.06
    CLCL (Genève)                           	software1	91.06
    NAIST SATO (Nara)                       	software1	91.06
    Orange – Deskiñ (Lannion)               	software1	91.06
    UParse (Edinburgh)                      	software1	91.06
    MQuni (Sydney)                          	software2	91.06
    LyS-FASTPARSE (A Coruña)                	software5	91.06
    TurkuNLP (Turku)                        	software1	91.06
    LATTICE (Paris)                         	software7	91.06
    naistCL (Nara)                          	software1	91.06
    UALING (Tucson)                         	software1	91.06
    Koç University (İstanbul)               	software3	91.06
    BASELINE UDPipe 1.1 (Praha)             	software2	91.06
    Stanford (Stanford)                     	software1	91.06
    METU (Ankara)                           	software2	91.06
    C2L2 (Ithaca)                           	software5	91.06
    MetaRomance (Santiago de Compostela)    	software1	91.06
    Mengest (Shanghai)                      	software1	91.06
    OpenU NLP Lab (Ra'anana)                	software6	91.06
    UT (Tartu)                              	software1	91.06
31. RACAI (București)                       	software1	89.87
32. Uppsala (Uppsala)                       	software1	86.34
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### kk

<pre>
 1. darc (Tübingen)                         	software1	96.40
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	96.07
 3. HIT-SCIR (Harbin)                       	software4	95.91
 4. Uppsala (Uppsala)                       	software1	95.45
 5. ParisNLP (Paris)                        	software1	95.20
    IIT Kharagpur (Kharagpur)               	software3	95.20
    NAIST SATO (Nara)                       	software1	95.20
    Orange – Deskiñ (Lannion)               	software1	95.20
    UParse (Edinburgh)                      	software1	95.20
    LIMSI-LIPN (Paris)                      	software2	95.20
    MQuni (Sydney)                          	software2	95.20
    LyS-FASTPARSE (A Coruña)                	software5	95.20
    TurkuNLP (Turku)                        	software1	95.20
    LATTICE (Paris)                         	software7	95.20
    naistCL (Nara)                          	software1	95.20
    UALING (Tucson)                         	software1	95.20
    Koç University (İstanbul)               	software3	95.20
    BASELINE UDPipe 1.1 (Praha)             	software2	95.20
    Stanford (Stanford)                     	software1	95.20
    METU (Ankara)                           	software2	95.20
    C2L2 (Ithaca)                           	software5	95.20
    MetaRomance (Santiago de Compostela)    	software1	95.20
    OpenU NLP Lab (Ra'anana)                	software6	95.20
    CLCL (Genève)                           	software2	95.20
    IMS (Stuttgart)                         	software2	95.20
26. Wanghao-ftd-SJTU (Shanghai)             	software2	95.19
27. TRL (Tokyo)                             	software1	94.78
28. fbaml (Palo Alto)                       	software1	94.60
29. RACAI (București)                       	software1	94.52
30. Wenba-NLU (Wuhan)                       	software1	 0.00
31. ECNU (Shanghai)                         	software1	 0.00
32. Mengest (Shanghai)                      	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### kmr

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.01
    ParisNLP (Paris)                        	software1	99.01
    darc (Tübingen)                         	software1	99.01
    IIT Kharagpur (Kharagpur)               	software3	99.01
    NAIST SATO (Nara)                       	software1	99.01
    Orange – Deskiñ (Lannion)               	software1	99.01
    UParse (Edinburgh)                      	software1	99.01
    LIMSI-LIPN (Paris)                      	software2	99.01
    MQuni (Sydney)                          	software2	99.01
    LyS-FASTPARSE (A Coruña)                	software5	99.01
    TurkuNLP (Turku)                        	software1	99.01
    LATTICE (Paris)                         	software7	99.01
    naistCL (Nara)                          	software1	99.01
    UALING (Tucson)                         	software1	99.01
    Koç University (İstanbul)               	software3	99.01
    BASELINE UDPipe 1.1 (Praha)             	software2	99.01
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.01
    Stanford (Stanford)                     	software1	99.01
    METU (Ankara)                           	software2	99.01
    C2L2 (Ithaca)                           	software5	99.01
    MetaRomance (Santiago de Compostela)    	software1	99.01
    HIT-SCIR (Harbin)                       	software4	99.01
    Mengest (Shanghai)                      	software1	99.01
    RACAI (București)                       	software1	99.01
    OpenU NLP Lab (Ra'anana)                	software6	99.01
    CLCL (Genève)                           	software2	99.01
    IMS (Stuttgart)                         	software2	99.01
28. Uppsala (Uppsala)                       	software1	97.48
29. TRL (Tokyo)                             	software1	97.18
30. fbaml (Palo Alto)                       	software1	91.76
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ko

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.73
    ECNU (Shanghai)                         	software1	99.73
    ParisNLP (Paris)                        	software1	99.73
    IIT Kharagpur (Kharagpur)               	software3	99.73
    NAIST SATO (Nara)                       	software1	99.73
    Orange – Deskiñ (Lannion)               	software1	99.73
    UParse (Edinburgh)                      	software1	99.73
    LIMSI-LIPN (Paris)                      	software2	99.73
    MQuni (Sydney)                          	software2	99.73
    LyS-FASTPARSE (A Coruña)                	software5	99.73
    TurkuNLP (Turku)                        	software1	99.73
    LATTICE (Paris)                         	software7	99.73
    naistCL (Nara)                          	software1	99.73
    UALING (Tucson)                         	software1	99.73
    Koç University (İstanbul)               	software3	99.73
    BASELINE UDPipe 1.1 (Praha)             	software2	99.73
    Stanford (Stanford)                     	software1	99.73
    METU (Ankara)                           	software2	99.73
    C2L2 (Ithaca)                           	software5	99.73
    MetaRomance (Santiago de Compostela)    	software1	99.73
    Mengest (Shanghai)                      	software1	99.73
    RACAI (București)                       	software1	99.73
    OpenU NLP Lab (Ra'anana)                	software6	99.73
    CLCL (Genève)                           	software2	99.73
    UT (Tartu)                              	software1	99.73
    IMS (Stuttgart)                         	software2	99.73
27. darc (Tübingen)                         	software1	99.69
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.69
    HIT-SCIR (Harbin)                       	software4	99.69
30. Uppsala (Uppsala)                       	software1	99.63
31. fbaml (Palo Alto)                       	software1	98.24
32. TRL (Tokyo)                             	software1	98.12
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    Uppsala (Uppsala)                       	software1	100.00
    TRL (Tokyo)                             	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
 5. ECNU (Shanghai)                         	software1	99.99
    ParisNLP (Paris)                        	software1	99.99
    darc (Tübingen)                         	software1	99.99
    IIT Kharagpur (Kharagpur)               	software3	99.99
    NAIST SATO (Nara)                       	software1	99.99
    Orange – Deskiñ (Lannion)               	software1	99.99
    UParse (Edinburgh)                      	software1	99.99
    LIMSI-LIPN (Paris)                      	software2	99.99
    MQuni (Sydney)                          	software2	99.99
    LyS-FASTPARSE (A Coruña)                	software5	99.99
    TurkuNLP (Turku)                        	software1	99.99
    LATTICE (Paris)                         	software7	99.99
    naistCL (Nara)                          	software1	99.99
    UALING (Tucson)                         	software1	99.99
    Koç University (İstanbul)               	software3	99.99
    BASELINE UDPipe 1.1 (Praha)             	software2	99.99
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.99
    Stanford (Stanford)                     	software1	99.99
    METU (Ankara)                           	software2	99.99
    C2L2 (Ithaca)                           	software5	99.99
    fbaml (Palo Alto)                       	software1	99.99
    MetaRomance (Santiago de Compostela)    	software1	99.99
    Mengest (Shanghai)                      	software1	99.99
    OpenU NLP Lab (Ra'anana)                	software6	99.99
    CLCL (Genève)                           	software2	99.99
    UT (Tartu)                              	software1	99.99
    IMS (Stuttgart)                         	software2	99.99
32. RACAI (București)                       	software1	99.97
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_ittb

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.99
    ECNU (Shanghai)                         	software1	99.99
    IIT Kharagpur (Kharagpur)               	software3	99.99
    CLCL (Genève)                           	software1	99.99
    NAIST SATO (Nara)                       	software1	99.99
    Orange – Deskiñ (Lannion)               	software1	99.99
    UParse (Edinburgh)                      	software1	99.99
    LIMSI-LIPN (Paris)                      	software2	99.99
    MQuni (Sydney)                          	software2	99.99
    LyS-FASTPARSE (A Coruña)                	software5	99.99
    TurkuNLP (Turku)                        	software1	99.99
    LATTICE (Paris)                         	software7	99.99
    naistCL (Nara)                          	software1	99.99
    UALING (Tucson)                         	software1	99.99
    Koç University (İstanbul)               	software3	99.99
    BASELINE UDPipe 1.1 (Praha)             	software2	99.99
    Stanford (Stanford)                     	software1	99.99
    METU (Ankara)                           	software2	99.99
    C2L2 (Ithaca)                           	software5	99.99
    MetaRomance (Santiago de Compostela)    	software1	99.99
    Mengest (Shanghai)                      	software1	99.99
    OpenU NLP Lab (Ra'anana)                	software6	99.99
    UT (Tartu)                              	software1	99.99
    IMS (Stuttgart)                         	software2	99.99
25. ParisNLP (Paris)                        	software1	99.97
    Uppsala (Uppsala)                       	software1	99.97
    fbaml (Palo Alto)                       	software1	99.97
28. RACAI (București)                       	software1	99.91
29. darc (Tübingen)                         	software1	99.89
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.89
    HIT-SCIR (Harbin)                       	software4	99.89
32. TRL (Tokyo)                             	software1	99.19
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### la_proiel

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    Wenba-NLU (Wuhan)                       	software1	100.00
    ParisNLP (Paris)                        	software1	100.00
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
    Mengest (Shanghai)                      	software1	100.00
    RACAI (București)                       	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    fbaml (Palo Alto)                       	software1	100.00
    IMS (Stuttgart)                         	software2	100.00
30. Uppsala (Uppsala)                       	software1	99.99
31. TRL (Tokyo)                             	software1	99.77
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### lv

<pre>
 1. fbaml (Palo Alto)                       	software1	99.45
 2. RACAI (București)                       	software1	99.30
 3. Uppsala (Uppsala)                       	software1	99.20
 4. darc (Tübingen)                         	software1	99.03
    HIT-SCIR (Harbin)                       	software4	99.03
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.94
 7. Wanghao-ftd-SJTU (Shanghai)             	software2	98.92
    ParisNLP (Paris)                        	software1	98.92
 9. Wenba-NLU (Wuhan)                       	software1	98.91
    ECNU (Shanghai)                         	software1	98.91
    IIT Kharagpur (Kharagpur)               	software3	98.91
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
    Mengest (Shanghai)                      	software1	98.91
    OpenU NLP Lab (Ra'anana)                	software6	98.91
    UT (Tartu)                              	software1	98.91
    IMS (Stuttgart)                         	software2	98.91
33. TRL (Tokyo)                             	software1	98.07
</pre>



### nl

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	99.88
    ECNU (Shanghai)                         	software1	99.88
    ParisNLP (Paris)                        	software1	99.88
    darc (Tübingen)                         	software1	99.88
    IIT Kharagpur (Kharagpur)               	software3	99.88
    CLCL (Genève)                           	software1	99.88
    NAIST SATO (Nara)                       	software1	99.88
    Orange – Deskiñ (Lannion)               	software1	99.88
    UParse (Edinburgh)                      	software1	99.88
    LIMSI-LIPN (Paris)                      	software2	99.88
    MQuni (Sydney)                          	software2	99.88
    LyS-FASTPARSE (A Coruña)                	software5	99.88
    TurkuNLP (Turku)                        	software1	99.88
    LATTICE (Paris)                         	software7	99.88
    naistCL (Nara)                          	software1	99.88
    UALING (Tucson)                         	software1	99.88
    Koç University (İstanbul)               	software3	99.88
    BASELINE UDPipe 1.1 (Praha)             	software2	99.88
    Stanford (Stanford)                     	software1	99.88
    METU (Ankara)                           	software2	99.88
    C2L2 (Ithaca)                           	software5	99.88
    MetaRomance (Santiago de Compostela)    	software1	99.88
    HIT-SCIR (Harbin)                       	software4	99.88
    Mengest (Shanghai)                      	software1	99.88
    OpenU NLP Lab (Ra'anana)                	software6	99.88
    UT (Tartu)                              	software1	99.88
    IMS (Stuttgart)                         	software2	99.88
28. Wanghao-ftd-SJTU (Shanghai)             	software2	99.87
29. RACAI (București)                       	software1	99.85
30. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.80
31. fbaml (Palo Alto)                       	software1	99.79
32. Uppsala (Uppsala)                       	software1	99.73
33. TRL (Tokyo)                             	software1	92.67
</pre>



### nl_lassysmall

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.99
 2. darc (Tübingen)                         	software1	99.94
    HIT-SCIR (Harbin)                       	software4	99.94
 4. Wanghao-ftd-SJTU (Shanghai)             	software2	99.93
    Wenba-NLU (Wuhan)                       	software1	99.93
    ECNU (Shanghai)                         	software1	99.93
    ParisNLP (Paris)                        	software1	99.93
    IIT Kharagpur (Kharagpur)               	software3	99.93
    CLCL (Genève)                           	software1	99.93
    NAIST SATO (Nara)                       	software1	99.93
    Orange – Deskiñ (Lannion)               	software1	99.93
    UParse (Edinburgh)                      	software1	99.93
    LIMSI-LIPN (Paris)                      	software2	99.93
    MQuni (Sydney)                          	software2	99.93
    LyS-FASTPARSE (A Coruña)                	software5	99.93
    TurkuNLP (Turku)                        	software1	99.93
    LATTICE (Paris)                         	software7	99.93
    naistCL (Nara)                          	software1	99.93
    UALING (Tucson)                         	software1	99.93
    Koç University (İstanbul)               	software3	99.93
    BASELINE UDPipe 1.1 (Praha)             	software2	99.93
    Stanford (Stanford)                     	software1	99.93
    METU (Ankara)                           	software2	99.93
    C2L2 (Ithaca)                           	software5	99.93
    fbaml (Palo Alto)                       	software1	99.93
    MetaRomance (Santiago de Compostela)    	software1	99.93
    Mengest (Shanghai)                      	software1	99.93
    RACAI (București)                       	software1	99.93
    OpenU NLP Lab (Ra'anana)                	software6	99.93
    UT (Tartu)                              	software1	99.93
    IMS (Stuttgart)                         	software2	99.93
32. Uppsala (Uppsala)                       	software1	99.85
33. TRL (Tokyo)                             	software1	93.68
</pre>



### no_bokmaal

<pre>
 1. RACAI (București)                       	software1	99.88
 2. fbaml (Palo Alto)                       	software1	99.85
 3. Uppsala (Uppsala)                       	software1	99.84
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.79
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	99.75
    Wenba-NLU (Wuhan)                       	software1	99.75
    ParisNLP (Paris)                        	software1	99.75
    IIT Kharagpur (Kharagpur)               	software3	99.75
    CLCL (Genève)                           	software1	99.75
    NAIST SATO (Nara)                       	software1	99.75
    Orange – Deskiñ (Lannion)               	software1	99.75
    UParse (Edinburgh)                      	software1	99.75
    LIMSI-LIPN (Paris)                      	software2	99.75
    MQuni (Sydney)                          	software2	99.75
    LyS-FASTPARSE (A Coruña)                	software5	99.75
    TurkuNLP (Turku)                        	software1	99.75
    LATTICE (Paris)                         	software7	99.75
    naistCL (Nara)                          	software1	99.75
    UALING (Tucson)                         	software1	99.75
    Koç University (İstanbul)               	software3	99.75
    BASELINE UDPipe 1.1 (Praha)             	software2	99.75
    Stanford (Stanford)                     	software1	99.75
    METU (Ankara)                           	software2	99.75
    C2L2 (Ithaca)                           	software5	99.75
    MetaRomance (Santiago de Compostela)    	software1	99.75
    Mengest (Shanghai)                      	software1	99.75
    OpenU NLP Lab (Ra'anana)                	software6	99.75
    IMS (Stuttgart)                         	software2	99.75
29. darc (Tübingen)                         	software1	99.72
    HIT-SCIR (Harbin)                       	software4	99.72
31. TRL (Tokyo)                             	software1	95.51
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### no_nynorsk

<pre>
 1. Uppsala (Uppsala)                       	software1	99.93
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.93
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.91
 4. darc (Tübingen)                         	software1	99.88
    HIT-SCIR (Harbin)                       	software4	99.88
 6. Wenba-NLU (Wuhan)                       	software1	99.85
    ParisNLP (Paris)                        	software1	99.85
    IIT Kharagpur (Kharagpur)               	software3	99.85
    CLCL (Genève)                           	software1	99.85
    NAIST SATO (Nara)                       	software1	99.85
    Orange – Deskiñ (Lannion)               	software1	99.85
    UParse (Edinburgh)                      	software1	99.85
    LIMSI-LIPN (Paris)                      	software2	99.85
    MQuni (Sydney)                          	software2	99.85
    LyS-FASTPARSE (A Coruña)                	software5	99.85
    TurkuNLP (Turku)                        	software1	99.85
    LATTICE (Paris)                         	software7	99.85
    naistCL (Nara)                          	software1	99.85
    UALING (Tucson)                         	software1	99.85
    Koç University (İstanbul)               	software3	99.85
    BASELINE UDPipe 1.1 (Praha)             	software2	99.85
    Stanford (Stanford)                     	software1	99.85
    METU (Ankara)                           	software2	99.85
    C2L2 (Ithaca)                           	software5	99.85
    MetaRomance (Santiago de Compostela)    	software1	99.85
    Mengest (Shanghai)                      	software1	99.85
    RACAI (București)                       	software1	99.85
    OpenU NLP Lab (Ra'anana)                	software6	99.85
    IMS (Stuttgart)                         	software2	99.85
30. fbaml (Palo Alto)                       	software1	96.99
31. TRL (Tokyo)                             	software1	94.88
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pl

<pre>
 1. fbaml (Palo Alto)                       	software1	100.00
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	99.99
    Wenba-NLU (Wuhan)                       	software1	99.99
    ParisNLP (Paris)                        	software1	99.99
    IIT Kharagpur (Kharagpur)               	software3	99.99
    CLCL (Genève)                           	software1	99.99
    NAIST SATO (Nara)                       	software1	99.99
    Orange – Deskiñ (Lannion)               	software1	99.99
    UParse (Edinburgh)                      	software1	99.99
    LIMSI-LIPN (Paris)                      	software2	99.99
    MQuni (Sydney)                          	software2	99.99
    LyS-FASTPARSE (A Coruña)                	software5	99.99
    TurkuNLP (Turku)                        	software1	99.99
    LATTICE (Paris)                         	software7	99.99
    naistCL (Nara)                          	software1	99.99
    UALING (Tucson)                         	software1	99.99
    Koç University (İstanbul)               	software3	99.99
    BASELINE UDPipe 1.1 (Praha)             	software2	99.99
    Stanford (Stanford)                     	software1	99.99
    METU (Ankara)                           	software2	99.99
    C2L2 (Ithaca)                           	software5	99.99
    MetaRomance (Santiago de Compostela)    	software1	99.99
    Mengest (Shanghai)                      	software1	99.99
    OpenU NLP Lab (Ra'anana)                	software6	99.99
    IMS (Stuttgart)                         	software2	99.99
26. darc (Tübingen)                         	software1	99.98
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.98
    HIT-SCIR (Harbin)                       	software4	99.98
29. RACAI (București)                       	software1	99.97
30. ECNU (Shanghai)                         	software1	98.57
    Uppsala (Uppsala)                       	software1	98.57
32. TRL (Tokyo)                             	software1	98.56
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt

<pre>
 1. fbaml (Palo Alto)                       	software1	99.71
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	99.67
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.66
 4. Wenba-NLU (Wuhan)                       	software1	99.64
    ParisNLP (Paris)                        	software1	99.64
    darc (Tübingen)                         	software1	99.64
    IIT Kharagpur (Kharagpur)               	software3	99.64
    CLCL (Genève)                           	software1	99.64
    NAIST SATO (Nara)                       	software1	99.64
    Orange – Deskiñ (Lannion)               	software1	99.64
    UParse (Edinburgh)                      	software1	99.64
    LIMSI-LIPN (Paris)                      	software2	99.64
    MQuni (Sydney)                          	software2	99.64
    LyS-FASTPARSE (A Coruña)                	software5	99.64
    TurkuNLP (Turku)                        	software1	99.64
    LATTICE (Paris)                         	software7	99.64
    naistCL (Nara)                          	software1	99.64
    UALING (Tucson)                         	software1	99.64
    Koç University (İstanbul)               	software3	99.64
    BASELINE UDPipe 1.1 (Praha)             	software2	99.64
    Stanford (Stanford)                     	software1	99.64
    METU (Ankara)                           	software2	99.64
    C2L2 (Ithaca)                           	software5	99.64
    MetaRomance (Santiago de Compostela)    	software1	99.64
    HIT-SCIR (Harbin)                       	software4	99.64
    Mengest (Shanghai)                      	software1	99.64
    RACAI (București)                       	software1	99.64
    OpenU NLP Lab (Ra'anana)                	software6	99.64
    IMS (Stuttgart)                         	software2	99.64
30. Uppsala (Uppsala)                       	software1	98.57
31. TRL (Tokyo)                             	software1	97.13
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_br

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.96
 2. RACAI (București)                       	software1	99.95
 3. Wanghao-ftd-SJTU (Shanghai)             	software2	99.94
    Wenba-NLU (Wuhan)                       	software1	99.94
    ParisNLP (Paris)                        	software1	99.94
    darc (Tübingen)                         	software1	99.94
    IIT Kharagpur (Kharagpur)               	software3	99.94
    CLCL (Genève)                           	software1	99.94
    NAIST SATO (Nara)                       	software1	99.94
    Orange – Deskiñ (Lannion)               	software1	99.94
    UParse (Edinburgh)                      	software1	99.94
    LIMSI-LIPN (Paris)                      	software2	99.94
    MQuni (Sydney)                          	software2	99.94
    LyS-FASTPARSE (A Coruña)                	software5	99.94
    TurkuNLP (Turku)                        	software1	99.94
    LATTICE (Paris)                         	software7	99.94
    naistCL (Nara)                          	software1	99.94
    UALING (Tucson)                         	software1	99.94
    Koç University (İstanbul)               	software3	99.94
    BASELINE UDPipe 1.1 (Praha)             	software2	99.94
    Stanford (Stanford)                     	software1	99.94
    METU (Ankara)                           	software2	99.94
    C2L2 (Ithaca)                           	software5	99.94
    MetaRomance (Santiago de Compostela)    	software1	99.94
    HIT-SCIR (Harbin)                       	software4	99.94
    Mengest (Shanghai)                      	software1	99.94
    OpenU NLP Lab (Ra'anana)                	software6	99.94
    IMS (Stuttgart)                         	software2	99.94
29. fbaml (Palo Alto)                       	software1	99.93
30. Uppsala (Uppsala)                       	software1	99.14
31. TRL (Tokyo)                             	software1	98.72
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### pt_pud

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.33
 2. HIT-SCIR (Harbin)                       	software4	99.32
 3. ParisNLP (Paris)                        	software1	99.29
    darc (Tübingen)                         	software1	99.29
    IIT Kharagpur (Kharagpur)               	software3	99.29
    CLCL (Genève)                           	software1	99.29
    NAIST SATO (Nara)                       	software1	99.29
    Orange – Deskiñ (Lannion)               	software1	99.29
    UParse (Edinburgh)                      	software1	99.29
    LIMSI-LIPN (Paris)                      	software2	99.29
    MQuni (Sydney)                          	software2	99.29
    LyS-FASTPARSE (A Coruña)                	software5	99.29
    TurkuNLP (Turku)                        	software1	99.29
    LATTICE (Paris)                         	software7	99.29
    naistCL (Nara)                          	software1	99.29
    UALING (Tucson)                         	software1	99.29
    Koç University (İstanbul)               	software3	99.29
    BASELINE UDPipe 1.1 (Praha)             	software2	99.29
    Stanford (Stanford)                     	software1	99.29
    METU (Ankara)                           	software2	99.29
    C2L2 (Ithaca)                           	software5	99.29
    MetaRomance (Santiago de Compostela)    	software1	99.29
    Mengest (Shanghai)                      	software1	99.29
    RACAI (București)                       	software1	99.29
    OpenU NLP Lab (Ra'anana)                	software6	99.29
    IMS (Stuttgart)                         	software2	99.29
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.27
28. fbaml (Palo Alto)                       	software1	98.51
29. TRL (Tokyo)                             	software1	98.37
30. Uppsala (Uppsala)                       	software1	98.08
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ro

<pre>
 1. Uppsala (Uppsala)                       	software1	99.77
 2. darc (Tübingen)                         	software1	99.67
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.67
    HIT-SCIR (Harbin)                       	software4	99.67
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	99.64
    ParisNLP (Paris)                        	software1	99.64
    IIT Kharagpur (Kharagpur)               	software3	99.64
    CLCL (Genève)                           	software1	99.64
    NAIST SATO (Nara)                       	software1	99.64
    Orange – Deskiñ (Lannion)               	software1	99.64
    UParse (Edinburgh)                      	software1	99.64
    LIMSI-LIPN (Paris)                      	software2	99.64
    MQuni (Sydney)                          	software2	99.64
    LyS-FASTPARSE (A Coruña)                	software5	99.64
    TurkuNLP (Turku)                        	software1	99.64
    LATTICE (Paris)                         	software7	99.64
    naistCL (Nara)                          	software1	99.64
    UALING (Tucson)                         	software1	99.64
    Koç University (İstanbul)               	software3	99.64
    BASELINE UDPipe 1.1 (Praha)             	software2	99.64
    Stanford (Stanford)                     	software1	99.64
    METU (Ankara)                           	software2	99.64
    C2L2 (Ithaca)                           	software5	99.64
    fbaml (Palo Alto)                       	software1	99.64
    MetaRomance (Santiago de Compostela)    	software1	99.64
    Mengest (Shanghai)                      	software1	99.64
    OpenU NLP Lab (Ra'anana)                	software6	99.64
    UT (Tartu)                              	software1	99.64
    IMS (Stuttgart)                         	software2	99.64
30. RACAI (București)                       	software1	99.54
31. TRL (Tokyo)                             	software1	96.37
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. ECNU (Shanghai)                         	software1	 0.00
</pre>



### ru

<pre>
 1. RACAI (București)                       	software1	99.94
 2. ParisNLP (Paris)                        	software1	99.91
    IIT Kharagpur (Kharagpur)               	software3	99.91
    CLCL (Genève)                           	software1	99.91
    NAIST SATO (Nara)                       	software1	99.91
    Orange – Deskiñ (Lannion)               	software1	99.91
    UParse (Edinburgh)                      	software1	99.91
    LIMSI-LIPN (Paris)                      	software2	99.91
    MQuni (Sydney)                          	software2	99.91
    LyS-FASTPARSE (A Coruña)                	software5	99.91
    TurkuNLP (Turku)                        	software1	99.91
    LATTICE (Paris)                         	software7	99.91
    naistCL (Nara)                          	software1	99.91
    UALING (Tucson)                         	software1	99.91
    Koç University (İstanbul)               	software3	99.91
    BASELINE UDPipe 1.1 (Praha)             	software2	99.91
    Stanford (Stanford)                     	software1	99.91
    METU (Ankara)                           	software2	99.91
    C2L2 (Ithaca)                           	software5	99.91
    MetaRomance (Santiago de Compostela)    	software1	99.91
    Mengest (Shanghai)                      	software1	99.91
    OpenU NLP Lab (Ra'anana)                	software6	99.91
    IMS (Stuttgart)                         	software2	99.91
24. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.90
25. darc (Tübingen)                         	software1	99.88
    HIT-SCIR (Harbin)                       	software4	99.88
27. Uppsala (Uppsala)                       	software1	99.83
28. Wanghao-ftd-SJTU (Shanghai)             	software2	99.82
29. fbaml (Palo Alto)                       	software1	99.81
30. TRL (Tokyo)                             	software1	93.87
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ru_pud

<pre>
 1. TRL (Tokyo)                             	software1	98.30
 2. Uppsala (Uppsala)                       	software1	97.32
 3. ÚFAL – UDPipe 1.2 (Praha)               	software1	97.25
 4. RACAI (București)                       	software1	97.22
 5. HIT-SCIR (Harbin)                       	software4	97.21
 6. ECNU (Shanghai)                         	software1	97.18
    ParisNLP (Paris)                        	software1	97.18
    darc (Tübingen)                         	software1	97.18
    IIT Kharagpur (Kharagpur)               	software3	97.18
    CLCL (Genève)                           	software1	97.18
    NAIST SATO (Nara)                       	software1	97.18
    Orange – Deskiñ (Lannion)               	software1	97.18
    UParse (Edinburgh)                      	software1	97.18
    LIMSI-LIPN (Paris)                      	software2	97.18
    MQuni (Sydney)                          	software2	97.18
    LyS-FASTPARSE (A Coruña)                	software5	97.18
    TurkuNLP (Turku)                        	software1	97.18
    LATTICE (Paris)                         	software7	97.18
    naistCL (Nara)                          	software1	97.18
    UALING (Tucson)                         	software1	97.18
    Koç University (İstanbul)               	software3	97.18
    BASELINE UDPipe 1.1 (Praha)             	software2	97.18
    Stanford (Stanford)                     	software1	97.18
    METU (Ankara)                           	software2	97.18
    C2L2 (Ithaca)                           	software5	97.18
    MetaRomance (Santiago de Compostela)    	software1	97.18
    Mengest (Shanghai)                      	software1	97.18
    OpenU NLP Lab (Ra'anana)                	software6	97.18
    UT (Tartu)                              	software1	97.18
    IMS (Stuttgart)                         	software2	97.18
31. fbaml (Palo Alto)                       	software1	97.15
32. Wanghao-ftd-SJTU (Shanghai)             	software2	97.14
33. Wenba-NLU (Wuhan)                       	software1	 0.00
</pre>



### ru_syntagrus

<pre>
 1. fbaml (Palo Alto)                       	software1	99.69
 2. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.58
 3. ParisNLP (Paris)                        	software1	99.57
    IIT Kharagpur (Kharagpur)               	software3	99.57
    CLCL (Genève)                           	software1	99.57
    NAIST SATO (Nara)                       	software1	99.57
    Orange – Deskiñ (Lannion)               	software1	99.57
    UParse (Edinburgh)                      	software1	99.57
    LIMSI-LIPN (Paris)                      	software2	99.57
    MQuni (Sydney)                          	software2	99.57
    LyS-FASTPARSE (A Coruña)                	software5	99.57
    TurkuNLP (Turku)                        	software1	99.57
    LATTICE (Paris)                         	software7	99.57
    naistCL (Nara)                          	software1	99.57
    UALING (Tucson)                         	software1	99.57
    Koç University (İstanbul)               	software3	99.57
    BASELINE UDPipe 1.1 (Praha)             	software2	99.57
    Stanford (Stanford)                     	software1	99.57
    METU (Ankara)                           	software2	99.57
    C2L2 (Ithaca)                           	software5	99.57
    MetaRomance (Santiago de Compostela)    	software1	99.57
    Mengest (Shanghai)                      	software1	99.57
    OpenU NLP Lab (Ra'anana)                	software6	99.57
    IMS (Stuttgart)                         	software2	99.57
25. HIT-SCIR (Harbin)                       	software4	99.55
26. darc (Tübingen)                         	software1	99.51
    Uppsala (Uppsala)                       	software1	99.51
    RACAI (București)                       	software1	99.51
29. Wanghao-ftd-SJTU (Shanghai)             	software2	99.49
30. TRL (Tokyo)                             	software1	98.36
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sk

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	100.00
    ECNU (Shanghai)                         	software1	100.00
    ParisNLP (Paris)                        	software1	100.00
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
    Mengest (Shanghai)                      	software1	100.00
    RACAI (București)                       	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    IMS (Stuttgart)                         	software2	100.00
29. Wanghao-ftd-SJTU (Shanghai)             	software2	99.98
    fbaml (Palo Alto)                       	software1	99.98
31. Uppsala (Uppsala)                       	software1	99.97
32. TRL (Tokyo)                             	software1	99.75
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl

<pre>
 1. Wenba-NLU (Wuhan)                       	software1	99.96
    ECNU (Shanghai)                         	software1	99.96
    ParisNLP (Paris)                        	software1	99.96
    darc (Tübingen)                         	software1	99.96
    IIT Kharagpur (Kharagpur)               	software3	99.96
    Uppsala (Uppsala)                       	software1	99.96
    CLCL (Genève)                           	software1	99.96
    NAIST SATO (Nara)                       	software1	99.96
    Orange – Deskiñ (Lannion)               	software1	99.96
    UParse (Edinburgh)                      	software1	99.96
    LIMSI-LIPN (Paris)                      	software2	99.96
    MQuni (Sydney)                          	software2	99.96
    LyS-FASTPARSE (A Coruña)                	software5	99.96
    TurkuNLP (Turku)                        	software1	99.96
    LATTICE (Paris)                         	software7	99.96
    naistCL (Nara)                          	software1	99.96
    UALING (Tucson)                         	software1	99.96
    Koç University (İstanbul)               	software3	99.96
    BASELINE UDPipe 1.1 (Praha)             	software2	99.96
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.96
    Stanford (Stanford)                     	software1	99.96
    METU (Ankara)                           	software2	99.96
    C2L2 (Ithaca)                           	software5	99.96
    MetaRomance (Santiago de Compostela)    	software1	99.96
    HIT-SCIR (Harbin)                       	software4	99.96
    Mengest (Shanghai)                      	software1	99.96
    RACAI (București)                       	software1	99.96
    OpenU NLP Lab (Ra'anana)                	software6	99.96
    IMS (Stuttgart)                         	software2	99.96
30. fbaml (Palo Alto)                       	software1	99.93
31. Wanghao-ftd-SJTU (Shanghai)             	software2	99.91
32. TRL (Tokyo)                             	software1	99.73
33. UT (Tartu)                              	software1	 0.00
</pre>



### sl_sst

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    fbaml (Palo Alto)                       	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
 4. darc (Tübingen)                         	software1	99.91
 5. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.87
 6. ECNU (Shanghai)                         	software1	99.82
    ParisNLP (Paris)                        	software1	99.82
    IIT Kharagpur (Kharagpur)               	software3	99.82
    CLCL (Genève)                           	software1	99.82
    NAIST SATO (Nara)                       	software1	99.82
    Orange – Deskiñ (Lannion)               	software1	99.82
    UParse (Edinburgh)                      	software1	99.82
    LIMSI-LIPN (Paris)                      	software2	99.82
    MQuni (Sydney)                          	software2	99.82
    LyS-FASTPARSE (A Coruña)                	software5	99.82
    TurkuNLP (Turku)                        	software1	99.82
    LATTICE (Paris)                         	software7	99.82
    naistCL (Nara)                          	software1	99.82
    UALING (Tucson)                         	software1	99.82
    Koç University (İstanbul)               	software3	99.82
    BASELINE UDPipe 1.1 (Praha)             	software2	99.82
    Stanford (Stanford)                     	software1	99.82
    METU (Ankara)                           	software2	99.82
    C2L2 (Ithaca)                           	software5	99.82
    MetaRomance (Santiago de Compostela)    	software1	99.82
    Mengest (Shanghai)                      	software1	99.82
    RACAI (București)                       	software1	99.82
    OpenU NLP Lab (Ra'anana)                	software6	99.82
    IMS (Stuttgart)                         	software2	99.82
30. Uppsala (Uppsala)                       	software1	97.75
31. TRL (Tokyo)                             	software1	88.87
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sme

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.88
    ECNU (Shanghai)                         	software1	99.88
    ParisNLP (Paris)                        	software1	99.88
    darc (Tübingen)                         	software1	99.88
    IIT Kharagpur (Kharagpur)               	software3	99.88
    NAIST SATO (Nara)                       	software1	99.88
    Orange – Deskiñ (Lannion)               	software1	99.88
    UParse (Edinburgh)                      	software1	99.88
    LIMSI-LIPN (Paris)                      	software2	99.88
    MQuni (Sydney)                          	software2	99.88
    LyS-FASTPARSE (A Coruña)                	software5	99.88
    TurkuNLP (Turku)                        	software1	99.88
    LATTICE (Paris)                         	software7	99.88
    naistCL (Nara)                          	software1	99.88
    UALING (Tucson)                         	software1	99.88
    Koç University (İstanbul)               	software3	99.88
    BASELINE UDPipe 1.1 (Praha)             	software2	99.88
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.88
    Stanford (Stanford)                     	software1	99.88
    METU (Ankara)                           	software2	99.88
    C2L2 (Ithaca)                           	software5	99.88
    MetaRomance (Santiago de Compostela)    	software1	99.88
    HIT-SCIR (Harbin)                       	software4	99.88
    Mengest (Shanghai)                      	software1	99.88
    RACAI (București)                       	software1	99.88
    OpenU NLP Lab (Ra'anana)                	software6	99.88
    CLCL (Genève)                           	software2	99.88
    IMS (Stuttgart)                         	software2	99.88
29. Uppsala (Uppsala)                       	software1	98.44
30. TRL (Tokyo)                             	software1	98.28
31. fbaml (Palo Alto)                       	software1	96.52
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.87
 2. darc (Tübingen)                         	software1	99.86
    Uppsala (Uppsala)                       	software1	99.86
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.86
    HIT-SCIR (Harbin)                       	software4	99.86
 6. Wenba-NLU (Wuhan)                       	software1	99.84
    ParisNLP (Paris)                        	software1	99.84
    IIT Kharagpur (Kharagpur)               	software3	99.84
    CLCL (Genève)                           	software1	99.84
    NAIST SATO (Nara)                       	software1	99.84
    Orange – Deskiñ (Lannion)               	software1	99.84
    UParse (Edinburgh)                      	software1	99.84
    LIMSI-LIPN (Paris)                      	software2	99.84
    MQuni (Sydney)                          	software2	99.84
    LyS-FASTPARSE (A Coruña)                	software5	99.84
    TurkuNLP (Turku)                        	software1	99.84
    LATTICE (Paris)                         	software7	99.84
    naistCL (Nara)                          	software1	99.84
    UALING (Tucson)                         	software1	99.84
    Koç University (İstanbul)               	software3	99.84
    BASELINE UDPipe 1.1 (Praha)             	software2	99.84
    Stanford (Stanford)                     	software1	99.84
    METU (Ankara)                           	software2	99.84
    C2L2 (Ithaca)                           	software5	99.84
    fbaml (Palo Alto)                       	software1	99.84
    MetaRomance (Santiago de Compostela)    	software1	99.84
    Mengest (Shanghai)                      	software1	99.84
    OpenU NLP Lab (Ra'anana)                	software6	99.84
    IMS (Stuttgart)                         	software2	99.84
30. RACAI (București)                       	software1	99.59
31. TRL (Tokyo)                             	software1	94.51
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_lines

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.98
    Wenba-NLU (Wuhan)                       	software1	99.98
    ECNU (Shanghai)                         	software1	99.98
    ParisNLP (Paris)                        	software1	99.98
    IIT Kharagpur (Kharagpur)               	software3	99.98
    CLCL (Genève)                           	software1	99.98
    NAIST SATO (Nara)                       	software1	99.98
    Orange – Deskiñ (Lannion)               	software1	99.98
    UParse (Edinburgh)                      	software1	99.98
    LIMSI-LIPN (Paris)                      	software2	99.98
    MQuni (Sydney)                          	software2	99.98
    LyS-FASTPARSE (A Coruña)                	software5	99.98
    TurkuNLP (Turku)                        	software1	99.98
    LATTICE (Paris)                         	software7	99.98
    naistCL (Nara)                          	software1	99.98
    UALING (Tucson)                         	software1	99.98
    Koç University (İstanbul)               	software3	99.98
    BASELINE UDPipe 1.1 (Praha)             	software2	99.98
    Stanford (Stanford)                     	software1	99.98
    METU (Ankara)                           	software2	99.98
    C2L2 (Ithaca)                           	software5	99.98
    fbaml (Palo Alto)                       	software1	99.98
    MetaRomance (Santiago de Compostela)    	software1	99.98
    Mengest (Shanghai)                      	software1	99.98
    OpenU NLP Lab (Ra'anana)                	software6	99.98
    IMS (Stuttgart)                         	software2	99.98
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.97
28. darc (Tübingen)                         	software1	99.96
    HIT-SCIR (Harbin)                       	software4	99.96
30. RACAI (București)                       	software1	99.90
31. Uppsala (Uppsala)                       	software1	99.86
32. TRL (Tokyo)                             	software1	96.59
33. UT (Tartu)                              	software1	 0.00
</pre>



### sv_pud

<pre>
 1. Uppsala (Uppsala)                       	software1	98.56
 2. fbaml (Palo Alto)                       	software1	98.39
    RACAI (București)                       	software1	98.39
 4. ÚFAL – UDPipe 1.2 (Praha)               	software1	98.35
 5. Wanghao-ftd-SJTU (Shanghai)             	software2	98.30
 6. HIT-SCIR (Harbin)                       	software4	98.29
 7. ECNU (Shanghai)                         	software1	98.26
    ParisNLP (Paris)                        	software1	98.26
    darc (Tübingen)                         	software1	98.26
    IIT Kharagpur (Kharagpur)               	software3	98.26
    CLCL (Genève)                           	software1	98.26
    NAIST SATO (Nara)                       	software1	98.26
    Orange – Deskiñ (Lannion)               	software1	98.26
    UParse (Edinburgh)                      	software1	98.26
    LIMSI-LIPN (Paris)                      	software2	98.26
    MQuni (Sydney)                          	software2	98.26
    LyS-FASTPARSE (A Coruña)                	software5	98.26
    TurkuNLP (Turku)                        	software1	98.26
    LATTICE (Paris)                         	software7	98.26
    naistCL (Nara)                          	software1	98.26
    UALING (Tucson)                         	software1	98.26
    Koç University (İstanbul)               	software3	98.26
    BASELINE UDPipe 1.1 (Praha)             	software2	98.26
    Stanford (Stanford)                     	software1	98.26
    METU (Ankara)                           	software2	98.26
    C2L2 (Ithaca)                           	software5	98.26
    MetaRomance (Santiago de Compostela)    	software1	98.26
    Mengest (Shanghai)                      	software1	98.26
    OpenU NLP Lab (Ra'anana)                	software6	98.26
    IMS (Stuttgart)                         	software2	98.26
31. TRL (Tokyo)                             	software1	95.00
32. Wenba-NLU (Wuhan)                       	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.88
 2. darc (Tübingen)                         	software1	99.86
    fbaml (Palo Alto)                       	software1	99.86
    HIT-SCIR (Harbin)                       	software4	99.86
 5. Wenba-NLU (Wuhan)                       	software1	99.85
    ParisNLP (Paris)                        	software1	99.85
    IIT Kharagpur (Kharagpur)               	software3	99.85
    CLCL (Genève)                           	software1	99.85
    NAIST SATO (Nara)                       	software1	99.85
    Orange – Deskiñ (Lannion)               	software1	99.85
    UParse (Edinburgh)                      	software1	99.85
    LIMSI-LIPN (Paris)                      	software2	99.85
    MQuni (Sydney)                          	software2	99.85
    LyS-FASTPARSE (A Coruña)                	software5	99.85
    TurkuNLP (Turku)                        	software1	99.85
    LATTICE (Paris)                         	software7	99.85
    naistCL (Nara)                          	software1	99.85
    UALING (Tucson)                         	software1	99.85
    Koç University (İstanbul)               	software3	99.85
    BASELINE UDPipe 1.1 (Praha)             	software2	99.85
    ÚFAL – UDPipe 1.2 (Praha)               	software1	99.85
    Stanford (Stanford)                     	software1	99.85
    METU (Ankara)                           	software2	99.85
    C2L2 (Ithaca)                           	software5	99.85
    Mengest (Shanghai)                      	software1	99.85
    OpenU NLP Lab (Ra'anana)                	software6	99.85
    IMS (Stuttgart)                         	software2	99.85
28. RACAI (București)                       	software1	99.76
29. Uppsala (Uppsala)                       	software1	97.70
30. TRL (Tokyo)                             	software1	91.27
31. ECNU (Shanghai)                         	software1	 0.00
32. MetaRomance (Santiago de Compostela)    	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### tr_pud

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.13
 2. ParisNLP (Paris)                        	software1	98.86
    darc (Tübingen)                         	software1	98.86
    IIT Kharagpur (Kharagpur)               	software3	98.86
    CLCL (Genève)                           	software1	98.86
    NAIST SATO (Nara)                       	software1	98.86
    Orange – Deskiñ (Lannion)               	software1	98.86
    UParse (Edinburgh)                      	software1	98.86
    LIMSI-LIPN (Paris)                      	software2	98.86
    MQuni (Sydney)                          	software2	98.86
    LyS-FASTPARSE (A Coruña)                	software5	98.86
    TurkuNLP (Turku)                        	software1	98.86
    LATTICE (Paris)                         	software7	98.86
    naistCL (Nara)                          	software1	98.86
    UALING (Tucson)                         	software1	98.86
    Koç University (İstanbul)               	software3	98.86
    BASELINE UDPipe 1.1 (Praha)             	software2	98.86
    Stanford (Stanford)                     	software1	98.86
    METU (Ankara)                           	software2	98.86
    C2L2 (Ithaca)                           	software5	98.86
    MetaRomance (Santiago de Compostela)    	software1	98.86
    Mengest (Shanghai)                      	software1	98.86
    OpenU NLP Lab (Ra'anana)                	software6	98.86
    IMS (Stuttgart)                         	software2	98.86
25. Wanghao-ftd-SJTU (Shanghai)             	software2	98.70
26. HIT-SCIR (Harbin)                       	software4	98.59
27. fbaml (Palo Alto)                       	software1	98.19
28. RACAI (București)                       	software1	97.61
29. Uppsala (Uppsala)                       	software1	95.56
30. TRL (Tokyo)                             	software1	88.65
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ug

<pre>
 1. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.94
 2. Wanghao-ftd-SJTU (Shanghai)             	software2	99.79
 3. darc (Tübingen)                         	software1	99.67
 4. HIT-SCIR (Harbin)                       	software4	99.33
 5. RACAI (București)                       	software1	98.57
 6. ECNU (Shanghai)                         	software1	98.52
    ParisNLP (Paris)                        	software1	98.52
    IIT Kharagpur (Kharagpur)               	software3	98.52
    CLCL (Genève)                           	software1	98.52
    NAIST SATO (Nara)                       	software1	98.52
    Orange – Deskiñ (Lannion)               	software1	98.52
    UParse (Edinburgh)                      	software1	98.52
    LIMSI-LIPN (Paris)                      	software2	98.52
    MQuni (Sydney)                          	software2	98.52
    LyS-FASTPARSE (A Coruña)                	software5	98.52
    TurkuNLP (Turku)                        	software1	98.52
    LATTICE (Paris)                         	software7	98.52
    naistCL (Nara)                          	software1	98.52
    UALING (Tucson)                         	software1	98.52
    Koç University (İstanbul)               	software3	98.52
    BASELINE UDPipe 1.1 (Praha)             	software2	98.52
    Stanford (Stanford)                     	software1	98.52
    METU (Ankara)                           	software2	98.52
    C2L2 (Ithaca)                           	software5	98.52
    MetaRomance (Santiago de Compostela)    	software1	98.52
    OpenU NLP Lab (Ra'anana)                	software6	98.52
    IMS (Stuttgart)                         	software2	98.52
28. TRL (Tokyo)                             	software1	98.23
29. Uppsala (Uppsala)                       	software1	97.82
30. fbaml (Palo Alto)                       	software1	96.94
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. Mengest (Shanghai)                      	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### uk

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	99.92
 2. HIT-SCIR (Harbin)                       	software4	99.88
 3. fbaml (Palo Alto)                       	software1	99.82
 4. ParisNLP (Paris)                        	software1	99.81
    IIT Kharagpur (Kharagpur)               	software3	99.81
    CLCL (Genève)                           	software1	99.81
    NAIST SATO (Nara)                       	software1	99.81
    Orange – Deskiñ (Lannion)               	software1	99.81
    UParse (Edinburgh)                      	software1	99.81
    LIMSI-LIPN (Paris)                      	software2	99.81
    MQuni (Sydney)                          	software2	99.81
    LyS-FASTPARSE (A Coruña)                	software5	99.81
    TurkuNLP (Turku)                        	software1	99.81
    LATTICE (Paris)                         	software7	99.81
    naistCL (Nara)                          	software1	99.81
    UALING (Tucson)                         	software1	99.81
    Koç University (İstanbul)               	software3	99.81
    BASELINE UDPipe 1.1 (Praha)             	software2	99.81
    Stanford (Stanford)                     	software1	99.81
    METU (Ankara)                           	software2	99.81
    C2L2 (Ithaca)                           	software5	99.81
    MetaRomance (Santiago de Compostela)    	software1	99.81
    Mengest (Shanghai)                      	software1	99.81
    OpenU NLP Lab (Ra'anana)                	software6	99.81
    IMS (Stuttgart)                         	software2	99.81
26. darc (Tübingen)                         	software1	99.80
27. ÚFAL – UDPipe 1.2 (Praha)               	software1	99.66
28. RACAI (București)                       	software1	99.65
29. Uppsala (Uppsala)                       	software1	99.41
30. TRL (Tokyo)                             	software1	98.58
31. Wenba-NLU (Wuhan)                       	software1	 0.00
32. ECNU (Shanghai)                         	software1	 0.00
33. UT (Tartu)                              	software1	 0.00
</pre>



### ur

<pre>
 1. Wanghao-ftd-SJTU (Shanghai)             	software2	100.00
    Wenba-NLU (Wuhan)                       	software1	100.00
    ECNU (Shanghai)                         	software1	100.00
    ParisNLP (Paris)                        	software1	100.00
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
    fbaml (Palo Alto)                       	software1	100.00
    MetaRomance (Santiago de Compostela)    	software1	100.00
    HIT-SCIR (Harbin)                       	software4	100.00
    Mengest (Shanghai)                      	software1	100.00
    RACAI (București)                       	software1	100.00
    OpenU NLP Lab (Ra'anana)                	software6	100.00
    IMS (Stuttgart)                         	software2	100.00
31. TRL (Tokyo)                             	software1	97.70
32. Uppsala (Uppsala)                       	software1	94.55
33. UT (Tartu)                              	software1	 0.00
</pre>



### vi

<pre>
 1. LIMSI-LIPN (Paris)                      	software2	87.30
 2. ParisNLP (Paris)                        	software1	86.75
 3. IMS (Stuttgart)                         	software2	86.67
 4. Uppsala (Uppsala)                       	software1	86.63
 5. TRL (Tokyo)                             	software1	85.41
 6. HIT-SCIR (Harbin)                       	software4	84.70
 7. ÚFAL – UDPipe 1.2 (Praha)               	software1	84.26
 8. fbaml (Palo Alto)                       	software1	83.80
 9. Wanghao-ftd-SJTU (Shanghai)             	software2	82.80
10. darc (Tübingen)                         	software1	82.66
11. Wenba-NLU (Wuhan)                       	software1	82.47
    ECNU (Shanghai)                         	software1	82.47
    IIT Kharagpur (Kharagpur)               	software3	82.47
    CLCL (Genève)                           	software1	82.47
    NAIST SATO (Nara)                       	software1	82.47
    Orange – Deskiñ (Lannion)               	software1	82.47
    UParse (Edinburgh)                      	software1	82.47
    MQuni (Sydney)                          	software2	82.47
    LyS-FASTPARSE (A Coruña)                	software5	82.47
    TurkuNLP (Turku)                        	software1	82.47
    LATTICE (Paris)                         	software7	82.47
    naistCL (Nara)                          	software1	82.47
    UALING (Tucson)                         	software1	82.47
    Koç University (İstanbul)               	software3	82.47
    BASELINE UDPipe 1.1 (Praha)             	software2	82.47
    Stanford (Stanford)                     	software1	82.47
    METU (Ankara)                           	software2	82.47
    C2L2 (Ithaca)                           	software5	82.47
    MetaRomance (Santiago de Compostela)    	software1	82.47
    Mengest (Shanghai)                      	software1	82.47
    RACAI (București)                       	software1	82.47
    OpenU NLP Lab (Ra'anana)                	software6	82.47
33. UT (Tartu)                              	software1	 0.00
</pre>



### zh

<pre>
 1. fbaml (Palo Alto)                       	software1	94.57
 2. Uppsala (Uppsala)                       	software1	93.81
 3. IMS (Stuttgart)                         	software2	92.81
 4. LIMSI-LIPN (Paris)                      	software2	91.35
 5. HIT-SCIR (Harbin)                       	software4	91.19
 6. ÚFAL – UDPipe 1.2 (Praha)               	software1	89.55
 7. darc (Tübingen)                         	software1	88.99
 8. Wenba-NLU (Wuhan)                       	software1	88.91
    ECNU (Shanghai)                         	software1	88.91
    ParisNLP (Paris)                        	software1	88.91
    IIT Kharagpur (Kharagpur)               	software3	88.91
    CLCL (Genève)                           	software1	88.91
    NAIST SATO (Nara)                       	software1	88.91
    Orange – Deskiñ (Lannion)               	software1	88.91
    UParse (Edinburgh)                      	software1	88.91
    MQuni (Sydney)                          	software2	88.91
    LyS-FASTPARSE (A Coruña)                	software5	88.91
    TurkuNLP (Turku)                        	software1	88.91
    LATTICE (Paris)                         	software7	88.91
    naistCL (Nara)                          	software1	88.91
    UALING (Tucson)                         	software1	88.91
    Koç University (İstanbul)               	software3	88.91
    BASELINE UDPipe 1.1 (Praha)             	software2	88.91
    Stanford (Stanford)                     	software1	88.91
    METU (Ankara)                           	software2	88.91
    C2L2 (Ithaca)                           	software5	88.91
    MetaRomance (Santiago de Compostela)    	software1	88.91
    Mengest (Shanghai)                      	software1	88.91
    RACAI (București)                       	software1	88.91
    OpenU NLP Lab (Ra'anana)                	software6	88.91
31. Wanghao-ftd-SJTU (Shanghai)             	software2	88.72
32. TRL (Tokyo)                             	software1	83.64
33. UT (Tartu)                              	software1	 0.00
</pre>



