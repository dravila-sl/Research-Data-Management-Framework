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
 |- dataset_copy.json
 |- DATASET2.csv
 |- dataset_1.xml
 |- Dataset_2.3.csv
 |- script.py
 |- Script500.rdata
 |- plot_data6.rdata
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
 |   |- README_data.txt (What is in these folders? How to find a specific file/dataset?)
 |   |- 1 Raw Data 
 |   |   |- 1 Local Laboratory 
 |   |   |   |- README_rawData_local.txt
 |   |   |   |- dataset_1.csv
 |   |   |   |- dataset_2.csv
 |   |   |
 |   |   |- 2 External Data Source
 |   |   |   |- README_rawData_external.txt
 |   |   |   |- dataset_e_1.csv
 |   |   |   |- dataset_e_2.csv
 |   |   |   |- Script_1.py
 |   |   |   |- Script_2.py
 |   |   |   |- DataTransferAgreement/AuthorizationToReuse.pdf
 |   |   
 |   |- 2 Processed Data
 |   |   |- README_processedData.txt
 |   |   |- Processed_data.csv
 |   |   |- Script_processed.py
 | 
 |- 2 Result/Analysis
 |   |- README_analysis.txt
 |   |- Script_model_1.py
 |   |- Script_model_2.py
 |   |- Plot_model_1.jpg
 |   |- Plot_model_2.jpg
   
</pre>
</details>

<details>
  <summary> <b>References</b> </summary>
<br>
  This page organized knowledge and experiences from following resources:

  1. [HMS RDM 2024 Webinar - I've generated Data, Now What? The When, Where, and How of Data Storage](https://www.youtube.com/watch?v=prtBCHQ2c50&list=PLWIsV2soJK-VaW7IhxYyyOwiamjVV_FuB&index=4)
  
  2. [HMS RDM - File Organization](https://datamanagement.hms.harvard.edu/plan-design/directory-structure)

</details>
