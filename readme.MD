# Data Cleaning & Transformation with Pyspark
Rheeza Clinics & Pharmaceuticals conducted a research on Naproxen - a drug that has been claimed to normalize the blood pressure of teens and young adults. The trial was carried out in three of their clinic branches on over 2000 individuals of mixed genders from ages 14 - 22 between February and May 2021. This trial involved two groups - The in-active (Placebo) and active (Naproxen) groups to test the effect of the actual drug (Naproxen). Records of all procedures were kept; and extracted from the storage for the ML Engineers to develop algorithms for the next stages of the experiment. It was discovered that the dataset needed some Engineering to be performed on it for easier access by the Clinicians & ML Engineers. You have been hired as a Data Engineer specifically for this purpose.


## Tool
-pyspark

-sql



## Initial Schema
root
 |-- ageofparticipant: long (nullable = true)
 |-- clinician: struct (nullable = true)
 |    |-- branch: string (nullable = true)
 |    |-- name: string (nullable = true)
 |    |-- role: string (nullable = true)
 |-- drug_used: string (nullable = true)
 |-- experimentenddate: string (nullable = true)
 |-- experimentstartdate: string (nullable = true)
 |-- noofhourspassedatfirstreaction: long (nullable = true)
 |-- result: struct (nullable = true)
 |    |-- conclusion: string (nullable = true)
 |    |-- sideeffectsonparticipant: string (nullable = true)