---
layout: page
title: CoNLL 2017 Shared Task
---

# Results: Unofficial runs included (LAS)

<strong style='color:red'>DISCLAIMER:</strong> This is not the official ranking of systems participating in the shared task.

<strong style='color:red'>WARNING:</strong> These results are subject to change (new runs may be added).

This page tries to complement the overall picture by considering software that was not marked as primary system of the
respective team, or runs of the primary system that were not marked as the final submission (and the software setting may
have changed between the runs). It also includes runs that were performed after the [official results](results.html) were
announced and the test data (including gold-standard annotation) were unblinded; furthermore, some of the runs were
performed outside TIRA, and the corresponding “software” on TIRA only copied the pre-computed output to the destination
folder.

(The teams were able to analyze their official test runs only after everything was unblinded. In some cases, they found out
that there was a bug that caused the system to select a wrong model. The out-of-TIRA runs circumvent the necessity to train
the system on the same machine on which the testing takes place.)
The secondary systems and the corrected runs of primary systems may be described in the respective system-description papers.

A “-P” after software name indicates a primary system. “[OK]” means that the run has non-zero scores for all 81 test files;
otherwise, a number identifies how many files had non-zero scores (runs with zero such files are not included).
The last column identifies the system run and the
corresponding evaluation run (in some cases files from several runs were combined). Runs marked “Fin:” were registered as the
official final submission of the team, i.e. the score (but not the ranking) on a line that contains both “-P” and “Fin:”
should be identical to the official result of the team. Runs marked “OOT:” were reported by their authors as “out-of-TIRA”,
i.e. parsing occurred elsewhere and results were copied to TIRA.

## Best run per team

<pre style='overflow-x:visible; width:950px;'>
  1. Stanford (Stanford)                     	software1-P	76.30 [OK]	Fin: 2017-05-14-10-36-20 => 2017-05-15-02-58-52
  2. C2L2 (Ithaca)                           	software5-P	75.00 [OK]	Fin: 2017-05-12-09-27-46 => 2017-05-12-17-36-03
  3. IMS (Stuttgart)                         	software2-P	74.42 [OK]	Fin: 2017-05-19-16-00-44 => 2017-05-20-21-39-04
  4. ParisNLP (Paris)                        	software1-P	72.45 [OK]	     2017-07-18-21-58-38 => 2017-07-20-00-38-07
  5. HIT-SCIR (Harbin)                       	software4-P	72.11 [OK]	Fin: 2017-05-10-17-38-36 => 2017-05-11-04-53-11
  6. LATTICE (Paris)                         	software7-P	70.93 [OK]	Fin: 2017-05-15-11-18-08 => 2017-05-15-20-28-49
  7. Uppsala (Uppsala)                       	software3	70.49 [OK]	OOT: 2017-06-07-16-57-58 => 2017-06-07-17-02-33
  8. NAIST SATO (Nara)                       	software1-P	70.14 [OK]	Fin: 2017-05-15-08-05-20 => 2017-05-15-11-48-44
  9. Koç University (İstanbul)               	software3-P	69.76 [OK]	Fin: 2017-05-11-18-53-35 => 2017-05-11-23-16-25
 10. ÚFAL – UDPipe 1.2 (Praha)               	software1-P	69.52 [OK]	Fin: 2017-05-15-09-58-56 => 2017-05-15-12-16-30
 11. LyS-FASTPARSE (A Coruña)                	software5-P	69.15 [OK]	     2017-05-20-10-51-06 => 2017-05-22-09-34-33
 12. LIMSI (Paris)                           	software3	68.90 [OK]	     2017-05-22-00-54-35 => 2017-05-22-12-05-17
 13. UParse (Edinburgh)                      	software1-P	68.87 [OK]	Fin: 2017-05-12-22-37-39 => 2017-05-13-01-27-31
 14. RACAI (București)                       	software1-P	68.79 [OK]	     2017-05-18-16-05-12 => 2017-05-19-00-50-13
 15. Orange – Deskiñ (Lannion)               	software1-P	68.63 [OK]	     2017-05-09-19-00-13 => 2017-05-09-23-12-28
 16. TurkuNLP (Turku)                        	software1-P	68.59 [OK]	Fin: 2017-05-14-02-33-45 => 2017-05-14-08-32-00
 17. darc (Tübingen)                         	software1-P	68.41 [OK]	Fin: 2017-05-09-19-56-24 => 2017-05-09-21-54-48
 18. BASELINE UDPipe 1.1 (Praha)             	software2-P	68.35 [OK]	Fin: 2017-05-15-09-35-05 => 2017-05-15-10-42-39
 19. MQuni (Sydney)                          	software2-P	68.05 [OK]	Fin: 2017-05-09-20-35-48 => 2017-05-10-05-14-53
 20. fbaml (Palo Alto)                       	software1-P	67.92 [80]	     2017-05-15-18-00-23 => 2017-05-18-19-26-02
 21. IIT Kharagpur (Kharagpur)               	software2	67.75 [OK]	     2017-05-09-21-17-16 => 2017-05-09-21-42-32
 22. naistCL (Nara)                          	software1-P	67.59 [OK]	Fin: 2017-05-14-05-33-50 => 2017-05-14-07-31-46
 23. Wanghao-ftd-SJTU (Shanghai)             	software2-P	66.53 [OK]	Fin: 2017-05-14-12-32-00 => 2017-05-14-13-21-51
 24. UALING (Tucson)                         	software2	65.68 [OK]	     2017-05-16-12-04-27 => 2017-05-16-16-31-20
 25. METU (Ankara)                           	software2-P	61.98 [OK]	Fin: 2017-05-14-08-05-06 => 2017-05-14-09-38-40
 26. CLCL (Genève)                           	software2-P	61.82 [OK]	Fin: 2017-05-15-17-08-20+2017-05-15-12-58-58+2017...
 27. Mengest (Shanghai)                      	software1-P	61.33 [79]	Fin: 2017-05-15-12-26-00+2017-05-15-11-48-07+2017...
 28. Wenba-NLU (Wuhan)                       	software1-P	57.50 [76]	     2017-05-20-15-43-16 => 2017-05-20-20-30-57
 29. OpenU NLP Lab (Ra'anana)                	software6-P	57.06 [OK]	     2017-05-15-10-14-12 => 2017-05-22-20-47-45
 30. TRL (Tokyo)                             	software1-P	43.07 [OK]	Fin: 2017-05-15-13-31-13 => 2017-05-15-13-44-26
 31. MetaRomance (Santiago de Compostela)    	software1-P	34.05 [78]	Fin: 2017-05-12-10-34-18 => 2017-05-12-11-14-57
 32. UT (Tartu)                              	software1-P	21.10 [27]	Fin: 2017-05-15-01-44-30+2017-05-14-17-15-26+2017...
 33. ECNU (Shanghai)                         	software1-P	 3.18 [36]	Fin: 2017-05-13-17-22-09 => 2017-05-14-09-39-04
</pre>

## All runs

<pre style='overflow-x:visible; width:950px;'>
  1. Stanford (Stanford)                     	software1-P	76.30 [OK]	Fin: 2017-05-14-10-36-20 => 2017-05-15-02-58-52
  2. Stanford (Stanford)                     	software1-P	76.26 [OK]	     2017-05-13-04-08-02 => 2017-05-13-21-16-10
  3. C2L2 (Ithaca)                           	software5-P	75.00 [OK]	Fin: 2017-05-12-09-27-46 => 2017-05-12-17-36-03
  4. C2L2 (Ithaca)                           	software7	74.79 [OK]	     2017-05-12-06-53-22 => 2017-05-12-09-08-19
  5. C2L2 (Ithaca)                           	software10	74.69 [OK]	     2017-05-14-08-20-46 => 2017-05-14-17-27-19
  6. IMS (Stuttgart)                         	software2-P	74.42 [OK]	Fin: 2017-05-19-16-00-44 => 2017-05-20-21-39-04
  7. C2L2 (Ithaca)                           	software6	74.32 [OK]	     2017-05-13-01-02-08 => 2017-05-13-03-15-26
  8. IMS (Stuttgart)                         	software2-P	74.31 [OK]	     2017-05-10-14-37-31 => 2017-05-11-22-26-51
  9. C2L2 (Ithaca)                           	software6	74.21 [OK]	     2017-05-11-00-21-07 => 2017-05-11-02-42-14
 10. IMS (Stuttgart)                         	software2-P	74.19 [OK]	     2017-05-12-05-46-00 => 2017-05-13-13-59-27
 11. C2L2 (Ithaca)                           	software8	74.00 [OK]	     2017-05-13-07-09-39 => 2017-05-13-16-32-30
 12. C2L2 (Ithaca)                           	software9	73.75 [OK]	     2017-05-13-18-48-59 => 2017-05-13-20-51-25
 13. ParisNLP (Paris)                        	software1-P	72.45 [OK]	     2017-07-18-21-58-38 => 2017-07-20-00-38-07
 14. HIT-SCIR (Harbin)                       	software4-P	72.11 [OK]	Fin: 2017-05-10-17-38-36 => 2017-05-11-04-53-11
 15. IMS (Stuttgart)                         	software4	72.04 [OK]	     2017-05-14-21-46-37 => 2017-05-15-07-43-21
 16. IMS (Stuttgart)                         	software4	71.82 [OK]	     2017-05-09-23-23-01 => 2017-05-10-07-04-24
 17. ParisNLP (Paris)                        	software1-P	71.22 [OK]	     2017-07-13-20-19-37 => 2017-07-14-21-54-57
 18. LATTICE (Paris)                         	software7-P	70.93 [OK]	Fin: 2017-05-15-11-18-08 => 2017-05-15-20-28-49
 19. LATTICE (Paris)                         	software6	70.54 [OK]	     2017-05-11-02-27-54 => 2017-05-11-09-05-54
 20. Uppsala (Uppsala)                       	software3	70.49 [OK]	OOT: 2017-06-07-16-57-58 => 2017-06-07-17-02-33
 21. ParisNLP (Paris)                        	software1-P	70.35 [OK]	     2017-05-18-18-30-47 => 2017-05-19-03-26-19
 22. Uppsala (Uppsala)                       	software3	70.21 [OK]	OOT: 2017-05-31-16-47-25 => 2017-05-31-16-54-17
 23. NAIST SATO (Nara)                       	software1-P	70.14 [OK]	Fin: 2017-05-15-08-05-20 => 2017-05-15-11-48-44
 24. Koç University (İstanbul)               	software3-P	69.76 [OK]	Fin: 2017-05-11-18-53-35 => 2017-05-11-23-16-25
 25. Uppsala (Uppsala)                       	software3	69.66 [OK]	OOT: 2017-05-21-22-25-52 => 2017-05-21-22-37-55
 26. ÚFAL – UDPipe 1.2 (Praha)               	software1-P	69.52 [OK]	Fin: 2017-05-15-09-58-56 => 2017-05-15-12-16-30
 27. ParisNLP (Paris)                        	software1-P	69.32 [79]	     2017-07-04-10-58-00 => 2017-07-05-08-28-36
 28. LyS-FASTPARSE (A Coruña)                	software5-P	69.15 [OK]	     2017-05-20-10-51-06 => 2017-05-22-09-34-33
 29. NAIST SATO (Nara)                       	software1-P	69.04 [80]	     2017-05-14-20-25-23 => 2017-05-15-01-54-28
 30. NAIST SATO (Nara)                       	software1-P	69.03 [80]	     2017-05-14-15-56-56 => 2017-05-14-19-23-00
 31. LIMSI (Paris)                           	software3	68.90 [OK]	     2017-05-22-00-54-35 => 2017-05-22-12-05-17
 32. UParse (Edinburgh)                      	software1-P	68.87 [OK]	Fin: 2017-05-12-22-37-39 => 2017-05-13-01-27-31
 33. RACAI (București)                       	software1-P	68.79 [OK]	     2017-05-18-16-05-12 => 2017-05-19-00-50-13
 34. Orange – Deskiñ (Lannion)               	software1-P	68.63 [OK]	     2017-05-09-19-00-13 => 2017-05-09-23-12-28
 35. Orange – Deskiñ (Lannion)               	software1-P	68.61 [OK]	Fin: 2017-05-10-12-02-22 => 2017-05-10-15-33-39
 36. TurkuNLP (Turku)                        	software1-P	68.59 [OK]	Fin: 2017-05-14-02-33-45 => 2017-05-14-08-32-00
 37. darc (Tübingen)                         	software1-P	68.41 [OK]	Fin: 2017-05-09-19-56-24 => 2017-05-09-21-54-48
 38. BASELINE UDPipe 1.1 (Praha)             	software2-P	68.35 [OK]	Fin: 2017-05-15-09-35-05 => 2017-05-15-10-42-39
 39. TurkuNLP (Turku)                        	software3	68.34 [OK]	     2017-05-12-15-15-19 => 2017-05-12-16-21-07
 40. UParse (Edinburgh)                      	software3	68.09 [OK]	     2017-05-13-08-59-16 => 2017-05-13-12-52-22
     UParse (Edinburgh)                      	software2	68.09 [OK]	     2017-05-13-02-21-38 => 2017-05-13-08-27-31
 42. MQuni (Sydney)                          	software2-P	68.05 [OK]	Fin: 2017-05-09-20-35-48 => 2017-05-10-05-14-53
 43. fbaml (Palo Alto)                       	software1-P	67.92 [80]	     2017-05-15-18-00-23 => 2017-05-18-19-26-02
 44. fbaml (Palo Alto)                       	software1-P	67.87 [OK]	Fin: 2017-05-12-02-00-55+2017-05-15-02-50-42+2017...
 45. LyS-FASTPARSE (A Coruña)                	software5-P	67.81 [OK]	Fin: 2017-05-13-02-21-56 => 2017-05-14-10-10-24
 46. LyS-FASTPARSE (A Coruña)                	software4	67.77 [OK]	     2017-05-11-14-05-14 => 2017-05-12-20-40-59
 47. fbaml (Palo Alto)                       	software1-P	67.76 [77]	     2017-05-18-19-18-01 => 2017-05-26-21-41-20
 48. IIT Kharagpur (Kharagpur)               	software2	67.75 [OK]	     2017-05-09-21-17-16 => 2017-05-09-21-42-32
 49. RACAI (București)                       	software1-P	67.73 [OK]	     2017-05-19-12-58-35 => 2017-05-20-19-49-50
 50. LIMSI (Paris)                           	software2-P	67.72 [OK]	Fin: 2017-05-13-16-28-36 => 2017-05-14-03-47-23
 51. RACAI (București)                       	software1-P	67.71 [OK]	Fin: 2017-05-15-10-36-29+2017-05-14-21-47-35 => 2...
 52. IIT Kharagpur (Kharagpur)               	software7	67.63 [OK]	     2017-05-14-07-11-39 => 2017-05-14-07-33-51
 53. IIT Kharagpur (Kharagpur)               	software10	67.62 [OK]	     2017-05-14-08-49-10 => 2017-05-14-09-18-58
     IIT Kharagpur (Kharagpur)               	software9	67.62 [OK]	     2017-05-14-08-18-35 => 2017-05-14-08-41-47
 55. IIT Kharagpur (Kharagpur)               	software3-P	67.61 [OK]	Fin: 2017-05-13-17-01-25 => 2017-05-13-17-23-08
 56. IIT Kharagpur (Kharagpur)               	software5	67.60 [OK]	     2017-05-14-06-03-14 => 2017-05-14-06-26-06
     IIT Kharagpur (Kharagpur)               	software4	67.60 [OK]	     2017-05-13-18-49-21 => 2017-05-13-19-11-08
     IIT Kharagpur (Kharagpur)               	software8	67.60 [OK]	     2017-05-14-07-39-57 => 2017-05-14-08-12-52
 59. naistCL (Nara)                          	software1-P	67.59 [OK]	Fin: 2017-05-14-05-33-50 => 2017-05-14-07-31-46
 60. IIT Kharagpur (Kharagpur)               	software6	67.56 [OK]	     2017-05-14-06-33-23 => 2017-05-14-06-55-57
 61. LIMSI (Paris)                           	software2-P	67.51 [OK]	     2017-05-12-15-59-15 => 2017-05-13-10-31-43
 62. BASELINE UDPipe 1.1 (Praha)             	software2-P	67.17 [OK]	     2017-05-09-16-57-43 => 2017-05-09-17-37-05
 63. BASELINE UDPipe 1.1 (Praha)             	software2-P	67.02 [OK]	     2017-05-14-22-50-01 => 2017-05-14-23-26-01
 64. RACAI (București)                       	software1-P	66.70 [OK]	     2017-05-13-14-13-38 => 2017-05-13-22-29-15
 65. RACAI (București)                       	software1-P	66.66 [OK]	     2017-05-11-13-52-37 => 2017-05-11-22-28-51
 66. Wanghao-ftd-SJTU (Shanghai)             	software2-P	66.53 [OK]	Fin: 2017-05-14-12-32-00 => 2017-05-14-13-21-51
 67. RACAI (București)                       	software1-P	66.28 [77]	     2017-05-14-21-47-35 => 2017-05-15-08-45-31
     Wanghao-ftd-SJTU (Shanghai)             	software2-P	66.28 [80]	     2017-05-14-11-26-13 => 2017-05-14-12-07-19
 69. LyS-FASTPARSE (A Coruña)                	software3	65.81 [77]	     2017-05-09-18-43-05 => 2017-05-11-00-23-06
 70. UALING (Tucson)                         	software2	65.68 [OK]	     2017-05-16-12-04-27 => 2017-05-16-16-31-20
 71. UALING (Tucson)                         	software3	65.31 [OK]	     2017-05-16-16-39-37 => 2017-05-16-17-01-30
 72. UALING (Tucson)                         	software1-P	65.24 [OK]	Fin: 2017-05-15-06-10-21 => 2017-05-15-06-34-39
 73. Uppsala (Uppsala)                       	software1-P	65.11 [OK]	Fin: 2017-05-14-17-46-28 => 2017-05-15-07-22-05
 74. Uppsala (Uppsala)                       	software1-P	64.91 [OK]	     2017-05-13-02-51-39 => 2017-05-13-09-57-41
 75. Wanghao-ftd-SJTU (Shanghai)             	software2-P	64.82 [77]	     2017-05-13-18-01-57 => 2017-05-13-18-53-58
     Wanghao-ftd-SJTU (Shanghai)             	software2-P	64.82 [77]	     2017-05-13-18-01-57 => 2017-05-13-19-13-52
 77. naistCL (Nara)                          	software1-P	64.77 [OK]	     2017-05-13-20-41-11 => 2017-05-14-07-28-48
 78. Uppsala (Uppsala)                       	software1-P	64.36 [!!]	     2017-05-12-20-06-50 => 2017-05-13-02-15-52
 79. METU (Ankara)                           	software2-P	61.98 [OK]	Fin: 2017-05-14-08-05-06 => 2017-05-14-09-38-40
 80. CLCL (Genève)                           	software2-P	61.82 [OK]	Fin: 2017-05-15-17-08-20+2017-05-15-12-58-58+2017...
 81. CLCL (Genève)                           	software1	61.82 [OK]	     2017-05-18-19-45-11 => 2017-05-19-12-38-45
 82. Mengest (Shanghai)                      	software1-P	61.33 [79]	Fin: 2017-05-15-12-26-00+2017-05-15-11-48-07+2017...
 83. Mengest (Shanghai)                      	software1-P	61.33 [79]	     2017-05-20-17-41-31 => 2017-05-21-07-58-53
 84. NAIST SATO (Nara)                       	software1-P	61.29 [79]	     2017-05-13-11-52-21 => 2017-05-13-18-05-21
 85. darc (Tübingen)                         	software4	61.13 [OK]	     2017-05-14-23-40-19 => 2017-05-15-03-09-24
 86. Wanghao-ftd-SJTU (Shanghai)             	software1	61.08 [OK]	     2017-05-13-12-17-21 => 2017-05-13-13-06-56
     Wanghao-ftd-SJTU (Shanghai)             	software2-P	61.08 [OK]	     2017-05-13-09-08-54 => 2017-05-13-09-41-20
     Wanghao-ftd-SJTU (Shanghai)             	software1	61.08 [OK]	     2017-05-13-08-13-21 => 2017-05-13-09-00-36
 89. Uppsala (Uppsala)                       	software1-P	60.94 [73]	     2017-05-12-08-45-53 => 2017-05-12-14-01-29
 90. ParisNLP (Paris)                        	software1-P	60.86 [80]	     2017-05-11-02-24-27 => 2017-05-11-11-56-10
 91. ParisNLP (Paris)                        	software1-P	60.02 [OK]	Fin: 2017-05-15-02-05-49 => 2017-05-15-13-53-08
     ParisNLP (Paris)                        	software1-P	60.02 [OK]	Fin: 2017-05-15-02-05-49 => 2017-05-15-07-59-07
 93. ParisNLP (Paris)                        	software1-P	59.59 [OK]	     2017-05-12-23-01-18 => 2017-05-13-10-05-26
 94. ParisNLP (Paris)                        	software1-P	58.31 [OK]	     2017-05-12-00-02-52 => 2017-05-12-04-55-07
 95. Wenba-NLU (Wuhan)                       	software1-P	57.50 [76]	     2017-05-20-15-43-16 => 2017-05-20-20-30-57
 96. OpenU NLP Lab (Ra'anana)                	software6-P	57.06 [OK]	     2017-05-15-10-14-12 => 2017-05-22-20-47-45
 97. OpenU NLP Lab (Ra'anana)                	software6-P	56.56 [OK]	Fin: 2017-05-14-23-13-45+2017-05-14-16-57-08+2017...
 98. NAIST SATO (Nara)                       	software1-P	54.47 [62]	     2017-05-15-04-02-07 => 2017-05-15-07-24-25
 99. naistCL (Nara)                          	software1-P	54.21 [63]	     2017-05-13-13-43-15 => 2017-05-13-18-26-36
100. RACAI (București)                       	software1-P	53.06 [68]	     2017-05-10-08-50-07 => 2017-05-10-17-12-07
101. Uppsala (Uppsala)                       	software1-P	50.29 [60]	     2017-05-11-18-50-48 => 2017-05-11-23-11-18
102. OpenU NLP Lab (Ra'anana)                	software6-P	50.22 [74]	     2017-05-13-01-48-49 => 2017-05-13-14-58-39
103. METU (Ankara)                           	software2-P	46.27 [55]	     2017-05-13-13-51-31 => 2017-05-13-15-02-37
104. RACAI (București)                       	software1-P	46.07 [55]	     2017-05-10-19-08-11 => 2017-05-11-09-01-59
105. TRL (Tokyo)                             	software1-P	43.07 [OK]	Fin: 2017-05-15-13-31-13 => 2017-05-15-13-44-26
106. TRL (Tokyo)                             	software1-P	43.01 [OK]	     2017-05-15-12-48-45 => 2017-05-15-13-01-14
107. TRL (Tokyo)                             	software1-P	42.94 [OK]	     2017-05-15-07-43-56 => 2017-05-15-08-22-20
108. Wanghao-ftd-SJTU (Shanghai)             	software2-P	41.94 [49]	     2017-05-14-10-05-51 => 2017-05-14-11-07-01
109. TRL (Tokyo)                             	software1-P	41.47 [OK]	     2017-05-14-13-35-37 => 2017-05-14-14-37-08
     TRL (Tokyo)                             	software1-P	41.47 [OK]	     2017-05-13-14-05-38 => 2017-05-13-14-18-29
111. TRL (Tokyo)                             	software1-P	40.74 [80]	     2017-05-13-07-49-50 => 2017-05-13-08-04-19
     TRL (Tokyo)                             	software1-P	40.74 [80]	     2017-05-13-07-08-55 => 2017-05-13-07-31-18
113. Mengest (Shanghai)                      	software1-P	34.97 [43]	     2017-05-15-09-38-56 => 2017-05-15-10-42-03
114. MetaRomance (Santiago de Compostela)    	software1-P	34.05 [78]	Fin: 2017-05-12-10-34-18 => 2017-05-12-11-14-57
115. Uppsala (Uppsala)                       	software1-P	32.08 [37]	     2017-05-11-09-42-12 => 2017-05-11-13-30-55
116. Mengest (Shanghai)                      	software1-P	25.51 [32]	     2017-05-15-06-39-45 => 2017-05-15-07-16-05
117. fbaml (Palo Alto)                       	software1-P	22.38 [24]	     2017-05-15-20-23-04 => 2017-05-18-19-15-45
118. fbaml (Palo Alto)                       	software1-P	22.07 [27]	     2017-05-13-14-34-43 => 2017-05-15-00-24-54
     fbaml (Palo Alto)                       	software1-P	22.07 [27]	     2017-05-13-14-34-43 => 2017-05-15-01-29-27
120. TRL (Tokyo)                             	software1-P	21.38 [42]	     2017-05-12-12-01-52 => 2017-05-12-12-15-59
121. UT (Tartu)                              	software1-P	21.10 [27]	Fin: 2017-05-15-01-44-30+2017-05-14-17-15-26+2017...
122. IMS (Stuttgart)                         	software2-P	18.10 [20]	     2017-05-14-00-31-18 => 2017-05-14-09-27-04
123. CLCL (Genève)                           	software2-P	15.23 [17]	     2017-05-15-00-29-33 => 2017-05-15-10-02-48
124. UT (Tartu)                              	software1-P	15.18 [20]	     2017-05-15-01-44-30 => 2017-05-15-11-24-20
125. C2L2 (Ithaca)                           	software11	12.65 [14]	     2017-05-25-22-36-08 => 2017-05-25-23-34-28
126. fbaml (Palo Alto)                       	software1-P	12.62 [17]	     2017-05-15-11-45-54 => 2017-05-15-17-54-49
127. CLCL (Genève)                           	software1	11.51 [14]	     2017-05-14-20-47-03 => 2017-05-14-22-16-54
128. LATTICE (Paris)                         	software7-P	10.24 [15]	     2017-05-15-06-35-50 => 2017-05-15-07-48-18
129. CLCL (Genève)                           	software1	 9.55 [14]	     2017-05-15-12-23-01 => 2017-05-15-13-01-41
130. fbaml (Palo Alto)                       	software1-P	 9.22 [11]	     2017-05-12-02-00-55 => 2017-05-14-23-44-14
131. CLCL (Genève)                           	software1	 8.77 [10]	     2017-05-14-22-33-29 => 2017-05-15-08-50-05
132. CLCL (Genève)                           	software1	 7.49 [8]	     2017-05-15-11-56-31 => 2017-05-15-12-19-58
133. CLCL (Genève)                           	software2-P	 7.19 [8]	     2017-05-14-12-15-56 => 2017-05-15-22-00-58
134. UT (Tartu)                              	software1-P	 6.77 [8]	     2017-05-12-14-58-40 => 2017-05-14-16-03-28
135. fbaml (Palo Alto)                       	software1-P	 6.60 [8]	     2017-05-11-04-06-39 => 2017-05-11-06-42-15
136. CLCL (Genève)                           	software2-P	 5.80 [9]	     2017-05-15-11-59-45 => 2017-05-15-12-38-24
137. OpenU NLP Lab (Ra'anana)                	software6-P	 4.47 [5]	     2017-05-14-16-57-08 => 2017-05-14-22-37-03
138. fbaml (Palo Alto)                       	software1-P	 4.46 [5]	     2017-05-11-02-06-37 => 2017-05-11-03-49-18
139. HIT-SCIR (Harbin)                       	software4-P	 3.57 [4]	     2017-05-24-16-51-58 => 2017-05-24-17-24-11
140. Mengest (Shanghai)                      	software1-P	 3.22 [5]	     2017-05-15-12-26-00 => 2017-05-15-12-31-23
141. ECNU (Shanghai)                         	software1-P	 3.18 [36]	Fin: 2017-05-13-17-22-09 => 2017-05-14-09-39-04
142. Mengest (Shanghai)                      	software1-P	 3.04 [3]	     2017-05-27-12-15-27 => 2017-05-27-13-09-48
143. CLCL (Genève)                           	software2-P	 2.70 [4]	     2017-05-15-12-41-38 => 2017-05-15-12-54-24
144. fbaml (Palo Alto)                       	software1-P	 2.59 [4]	     2017-05-19-01-41-05 => 2017-05-19-20-50-08
145. fbaml (Palo Alto)                       	software1-P	 2.38 [3]	     2017-05-09-18-24-12 => 2017-05-09-19-11-07
     fbaml (Palo Alto)                       	software1-P	 2.38 [3]	     2017-05-11-01-27-22 => 2017-05-11-02-03-29
147. CLCL (Genève)                           	software2-P	 2.35 [3]	     2017-05-11-09-45-24 => 2017-05-15-21-56-07
148. Stanford (Stanford)                     	software1-P	 2.00 [4]	     2017-05-13-01-56-15 => 2017-05-13-02-07-12
149. CLCL (Genève)                           	software2-P	 1.93 [3]	     2017-05-15-12-58-58 => 2017-05-15-14-17-50
150. Uppsala (Uppsala)                       	software1-P	 1.87 [2]	     2017-05-12-15-45-21 => 2017-05-12-16-11-30
151. OpenU NLP Lab (Ra'anana)                	software6-P	 1.86 [2]	     2017-05-14-23-13-45 => 2017-05-14-23-37-48
152. UT (Tartu)                              	software1-P	 1.78 [2]	     2017-05-14-20-03-55 => 2017-05-14-21-19-59
153. CLCL (Genève)                           	software1	 1.60 [2]	     2017-05-15-11-17-14 => 2017-05-15-11-51-37
154. Stanford (Stanford)                     	software1-P	 1.57 [3]	     2017-05-12-23-51-03 => 2017-05-13-00-01-50
155. CLCL (Genève)                           	software1	 1.54 [2]	     2017-05-15-10-49-17 => 2017-05-15-11-13-08
156. Wanghao-ftd-SJTU (Shanghai)             	software2-P	 1.46 [3]	     2017-05-14-12-11-46 => 2017-05-14-12-25-37
157. CLCL (Genève)                           	software2-P	 1.45 [4]	     2017-05-14-23-18-36 => 2017-05-15-00-19-42
158. NAIST SATO (Nara)                       	software1-P	 1.44 [2]	     2017-05-15-02-08-05 => 2017-05-15-02-24-38
     NAIST SATO (Nara)                       	software1-P	 1.44 [2]	     2017-05-15-07-46-42 => 2017-05-15-08-03-08
160. RACAI (București)                       	software1-P	 1.43 [4]	     2017-05-15-10-36-29 => 2017-05-17-01-29-33
     RACAI (București)                       	software1-P	 1.43 [4]	     2017-05-15-10-36-29 => 2017-05-15-11-14-24
162. Uppsala (Uppsala)                       	software1-P	 1.23 [6]	     2017-05-12-19-09-22 => 2017-05-12-19-28-23
163. CLCL (Genève)                           	software1	 1.02 [1]	     2017-05-15-16-25-50 => 2017-05-15-17-25-10
     UT (Tartu)                              	software1-P	 1.02 [1]	     2017-05-14-17-15-26 => 2017-05-14-19-09-04
165. CLCL (Genève)                           	software2-P	 0.99 [1]	     2017-05-15-10-24-34 => 2017-05-15-10-55-40
     fbaml (Palo Alto)                       	software1-P	 0.99 [1]	     2017-05-11-07-21-26 => 2017-05-11-17-53-46
167. Mengest (Shanghai)                      	software1-P	 0.94 [1]	     2017-05-14-22-25-54 => 2017-05-14-22-30-32
168. CLCL (Genève)                           	software1	 0.93 [1]	     2017-05-15-18-00-38 => 2017-05-15-18-14-51
169. ECNU (Shanghai)                         	software1-P	 0.90 [2]	     2017-05-13-13-23-50 => 2017-05-13-14-51-51
170. CLCL (Genève)                           	software2-P	 0.86 [1]	     2017-05-15-17-08-20 => 2017-05-15-17-18-57
171. fbaml (Palo Alto)                       	software1-P	 0.83 [1]	     2017-05-15-02-50-42 => 2017-05-15-07-23-25
172. CLCL (Genève)                           	software1	 0.79 [1]	     2017-05-15-09-07-48 => 2017-05-15-09-30-03
173. fbaml (Palo Alto)                       	software1-P	 0.76 [1]	     2017-05-15-07-30-20 => 2017-05-15-11-35-57
174. IMS (Stuttgart)                         	software2-P	 0.64 [1]	     2017-05-14-18-34-01 => 2017-05-14-18-48-36
175. Wenba-NLU (Wuhan)                       	software1-P	 0.58 [46]	Fin: 2017-05-13-01-44-52 => 2017-05-14-06-53-39
     Wenba-NLU (Wuhan)                       	software1-P	 0.58 [46]	Fin: 2017-05-13-01-44-52 => 2017-05-13-07-28-04
177. HIT-SCIR (Harbin)                       	software4-P	 0.57 [4]	     2017-05-24-14-28-46 => 2017-05-24-16-05-44
178. Mengest (Shanghai)                      	software1-P	 0.56 [4]	     2017-05-15-11-48-07 => 2017-05-15-12-01-21
179. Uppsala (Uppsala)                       	software1-P	 0.55 [1]	     2017-05-13-02-35-34 => 2017-05-13-02-43-04
     fbaml (Palo Alto)                       	software1-P	 0.55 [1]	     2017-05-11-00-08-00 => 2017-05-11-00-28-45
     fbaml (Palo Alto)                       	software1-P	 0.55 [1]	     2017-05-11-00-50-37 => 2017-05-11-01-06-43
     fbaml (Palo Alto)                       	software1-P	 0.55 [1]	     2017-05-11-23-43-44 => 2017-05-12-00-05-28
183. CLCL (Genève)                           	software2-P	 0.22 [1]	     2017-05-15-11-48-22 => 2017-05-15-11-58-06
</pre>
