# mikrokosmos-difficulty dataset

We introduce score difficulty classification as a subtask of music information retrieval (MIR), which may be used in music education technologies, for personalised curriculum generation, and score retrieval. For this purpose, we introduce a novel dataset for the task, Mikrokosmos-difficulty, containing 147 symbolic piano pieces and the corresponding difficulty labels derived by its composer Béla Bartók and the publishers.

# Abaut the dataset


Béla Bartók’s Mikrokosmos Sz. 107 is a collection of 153 piano pieces published in six volumes between 1926 and 1939 and progressively ranked in terms of difficulty. Individual compositions go from extremely simple and easy beginner exercises to challenging advanced technical musical works.

We propose the Mikrokosmos-difficulty dataset based on a subset of 146 pieces from the Mikrokosmos collection, discarding the 7 pieces composed for four hands performance. We group the pieces on three levels of difficulty according to the original classification in the the editions by the publishers Wiener and Henle Verlag. Correspondingly, the beginner level contains the pieces 1-66 (Volumes I and II), the moderate level contains the pieces 67-121 (Volumes III and IV), the professional level contains the pieces 122-153 (Volumes V and VI). The 6-volume-long collection is obtained from IMSLP in pdf format. The conversion to machine-readable symbolic representations in musicXML was done semi-automatically using a commercial Optical Music Recognition (OMR) software [15], and manual corrections. The statistics are presented in the next table

|           | Beginner             | Moderate              | Professional          |
|-----------|----------------------|-----------------------|-----------------------|
| n scores  | 62                   | 54                    | 31                    |
| n notes   | μ = 108.58 σ = 57.16 | μ = 260.40 σ = 111.00 | μ = 650.06 σ = 322.15 |
| n bars    | μ = 20.37 σ = 9.64   | μ = 33.35 σ = 13.27   | μ = 63.12 σ = 29.30   |
| tempo     | μ = 107.25 σ = 24.48 | μ = 112.62 σ = 59.75  | μ = 182.45 σ = 113.13 |

,where we can see that Mikrokosmos-difficulty dataset is biased in lengths and tempo. Therefore, analyzing the technique difficulty in this dataset requires robustness to variations in length and tempo.

# Citation

Paper in review...
