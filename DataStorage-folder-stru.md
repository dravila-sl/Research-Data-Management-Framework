## Why should we structure the directory?

Which following project directory would you like to see?

<pre>
Project_A
 |- 1 Data
 |   |- README.txt
 |   |- 1 Raw Data 
 |   |- 2 Processed Data
 | 
 |- 2 Analysis
   
</pre>

<pre>
Project_B
 |- dataset_copy
 |- DATASET2
 |- dataset_1
 |- Dataset_2.3
 |- Script
 |- Script_NEW
 |- Script500

</pre>



## Recommended practices for folder structure

1. Establish the system and stay consistently.

2. Create folders based on file type, data or project stages.
   
   _(i.e. Raw Data, Audio files, Imaging data, Lab Books, Methodologies, etc.)_

3. How should files be organized in this folder?
   
   _(i.e. by dates, by classifications, etc.)_

4. Create a README file at the beginning and update it throughout the research.

   It is not mandatory for each directory but recommanded for a higher level directory or a complex dataset.

   For more details about README file, see [How to write a README file] (link to the readme-page)

<details>
  <summary> <b>Example</b> </summary>
<pre>
Project_A
 |
 |- 0 Basic Information 
 |   |- Role & Responsibilites
 |   |- Project Introduction
 |
 |- 1 Data
 |   |
 |   |- README.txt (What is in these folders? How to find a specific file/data?)
 |   | 
 |   |- 1 Raw Data 
 |   |   |- 1 Local Laboratory 
 |   |   |   |- Data specification
 |   |   |   |- Codebook/CodeDictionary
 |   |   |   |- Raw dataset 1
 |   |   |   |- Raw dataset 2
 |   |   |
 |   |   |- 2 External Data Source
 |   |   |   |- Data specification
 |   |   |   |- Codebook/CodeDictionary
 |   |   |   |- Raw dataset 1
 |   |   |   |- Raw dataset 2
 |   |   |   |- Script 1
 |   |   |   |- Script 2
 |   |   |   |- DataLicensing/Authorization 
 |   |   
 |   |- 2 Processed Data
 |   |   |- Processed Dataset
 |   |   |- Codebook/CodeDictionary
 |   |   |- Script
 | 
 |- 2 Result/Analysis
 |   |- Script
 |   |- Statistical Model
 |   |- Figure
 |   |- Plot
 |   |- Results/Report
   
</pre>
</details>

<details>
  <summary> <b>References</b> </summary>
<br>
  This page organized knowledge and experiences from following resources:

  1. [HMS RDM 2024 Webinar - I've generated Data, Now What? The When, Where, and How of Data Storage](https://www.youtube.com/watch?v=prtBCHQ2c50&list=PLWIsV2soJK-VaW7IhxYyyOwiamjVV_FuB&index=4)
  
  2. [HMS RDM - File Organization](https://datamanagement.hms.harvard.edu/plan-design/directory-structure)

</details>
