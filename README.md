# Exploring Architectural Knowledge in Blogs 2022 

This repository consists of the following files: 

* **latex\_source\_files\_report.zip:** contains the latex source files of the report Thesis.pdf
* **Thesis.pdf:** report 
* **Thesis.xlsx:** all spreadsheets used, explanation is below
* **Thesis.atlproj22:** an Atlas.ti file containing 35 documents representing the 35 blogs used in Step 3.

This file will provide more insight into **Thesis.xlsx:**. Section 1 provides the sheet numbers for commonly sought after results. Section 2 provides a brief explanation of each sheet.

## Section 1: Sheet numbers for specific results

Examples:

* Step 1: 13
* Step 2: 16
* Step 3: 25

Definitions:

* Step 2: 18
* Step 3: 24 and 26

Results Table:

* Step 1: 11,12
* Step 2: 17
* Step 3: 27

Comparisons:

* Type vs Topic: 19
* Type vs Task: 21 
* Type vs AK concept: 29 and 32 
* Topic vs AK concept: 30 and 32 

Chi2 tests:

* Type vs Task: 22
* AK vs Type: 33
* AK vs Topic: 33
* Code co-occurence table: 35


## Section 2: Thesis.xlsx explanation

**Thesis.xlsx** contains all the spreadsheets used during this project. All tables, calculations, and graphs were created in this file. Below are short explanations for each sheet. I have separated them into 4 groups: sheets from the initial dataset, sheets used for Step 1, sheets used for Step 2 and sheets used for Step 3. 

#### Initial dataset sheets

1. **Blogs_Ece:** the set of 945 blogs split up into 3 sub-sets
2. **Blogs_Samuli:** the set of 945 blogs split up into 3 sub-sets
3. **Blogs_Kerstin:** the set of 945 blogs split up into 3 sub-sets
4. **Original relevance rankings:** spreadsheet retrieved from previous study with the following columns: *username, task name, searchqueryid, url* and *relevance*
5. **Original 945 blog set:** URLS of 945 blogs
6. **Histogram of relevance of 945 blogs:** relevance for 945 blogs extracted from sheet 4
7. **Average Relevance calculation:** relevance averaged for blogs appearing multiple times in sheet 4

#### Step 1 sheets

8. **Step 1 sample:** types allocated to 300 blogs of sheet 3
9. **Step 1 Results incl. duplicates:** types allocated to all 945 blogs
10. **Step 1 Full Results:** duplicates removed from sheet 9
11. **Step 1 results:** table summary of frequencies of each blog type
12. **Step 1 results excl. sub-categories:** removed sub-categories from sheet 11 + graph
13. **Type examples:** 3 example URLs for each blog type

#### Step 2 sheets

14. **Topics sampling calculation:** 2 tables calculating blogs needed for step 2
15. **Topic Full Results:** topics allocated for all blogs used in step 2
16. **Topic examples:** 3 example URLs for each blog topic
17. **Step 2 results:** table summary of frequencies of each blog topic + graph
18. **Topic Definitions:** table of definitions and sub-categories for topics
19. **Type vs Topic:** table of number of blogs in each type and topic
20. **Type vs Task:** table of number of blogs in each type and task
21. **Type vs Task high relevance:** table from sheet 20 but only of blogs with a relevance of 3 and above
22. **Chi2 AK vs Tasks:** chi-squared matrix of table in sheet 21

#### Step 3 sheets

23. **AK sources table:** original list of AK concepts collected from literature 
24. **AK definitions from sources:** definitions of all concepts in original list 
25. **AK examples:** 3 examples for each of the 13 AK concepts used in step 3
26. **AK definitions:** definitions of 13 concepts used in step 3
27. **Step 3 results:** table of 35 blog URLs, document title from Atlas.ti, types, topics, relevances, number of codes and number of quotations
28. **AK relevance 4 vs 5:** average relevance calculated for 3 groups: blogs with a relevance 4, between 4 and 5, and 5. 
29. **AK vs Types:** table showing number of blogs used in step 3 per type, annotations per type, and normalised value of annotations per blog type
30. **AK vs Topics:** table showing number of blogs used in step 3 per topic, annotations per topic, and normalised value of annotations per blog topic
31. **AK frequencies:** number of annotations for each concept in step 3
32. **AK groups vs Type + Topic: table showing number of annotations per type and concept, and per topic and concept + graphs
33. **Chi2 AK groups vs Type + Topic:** normalised tables from sheet 32 + chi square matrices of normalised tables
34. **Doc-code table:** retrieved from Atlas.ti. Number of annotations per blog and AK concept
35. **Code co-occurence table:** retrieved from Atlas.ti. AK concepts that commonly occur together (defined by their quotations overlapping)
36. **Chi2 code-co:** chi-squared matrix of table from sheet 35. 
