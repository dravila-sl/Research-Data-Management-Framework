# File Naming Conventions

### Why do we need conventions for file names?

A file/dataset with an informative name improves the efficiency.

You don't have to open the file/dataset to know what the content is. Your team or collaborators from another institute could easily identify the file/dataset they need without asking you for details. 

For example, you have to open _"dataset3.csv"_ to know what is in the dataset. While you can visually understand what is in _"adverseEvent_hospital-05_20240501.csv"_ and use the dataset. 
<pre>
  Project_A
    |- dataset3.csv    
    |- adverseEvent_hospital-05_20240501.csv
</pre>

### Before naming a file or a specific dataset

1. Check with your team if there is an estblished file naming convention.

2. Conventions should be documented so others in your team or researchers from anothre institute could also apply them. 

3. It is not likely to have one convention for all files. Use different conventions for different type of files or datasets.


<details>
<summary> <b>What to consider before establishing a naming convention?</b> </summary>
  
1. What distinct these files from other files? (Consider metadata like the content, date, location, etc.)

2. Pick three most important metadata. (It is not a "the more the merrier" situation)

3. The name should be human readable and contain enough information for visually scanning the files.


</details>

<details>
<summary> <b>How to keep the file name short, simple and self-explanatory?</b> </summary>
  
1. Use abbreviation or code.
   
   _Example:_

   _Labotory A = LabA, Project 2 = P2, Mouse with serial number 255 = MOU-255_
   

2. Document the chosen abbreviation and codes. Do not leave any "commonly known" abbreviation undocumented.

</details>

<details>
<summary> <b> How to track the change of files?</b> </summary>
  
1. Add version information. Could be number (_i.e. v1.2, v3.0_) or status (_i.e. \_processed, \_amended, \_raw_).

2. Add a date. Make sure the format of date is consistent. (_i.e. using YYYYMMDD or YYYY-MM-DD_)

</details>

<details>
<summary> <b> How to decide the order of metadata in the name?</b> </summary>
  
1. Place the most important metadata at the beginning.

2. How would you like to sort the files? _(i.e. alphabetically, numerically or chronologically)_

</details>
<br></br>

>[!NOTE]
><b> Recommended practices </b>
  
1. Use two or three digits for numbering.

   _Example:_

   _Use "01_image.tif", "05_image.tif" instead of "1_image.tif"._

   _Otherwise "10_image.tif" will appear on the top when sorting the files._

2. No blank spaces in the name.
   
3. Be case-sensitive for the machine readability. (_i.e. "sample" vs "Sample"_)

4. Capitalize the first letter of each word to make it readable.

5. Avoid special characters. Use dash <b>( - )</b> to seperate numbers and underscore <b>( _ )</b> to seperate metadata.

   _Example:_

   _LiverTissue\_Mou-255\_SampleId-8526\_2020-01-30.tif_
   
   _MedImage\_Forearm-1\_PatId-123\_Hospital-09\_20210325.dcm_

6. Keep a reasonable length of file name. Ideally under 50 characters. 
    
7. Document the naming convention in a README text and keep it with the files. (link to how-to-readMe)
  
   _Example_01:_

   _The naming convention for tissue sample dataset is:_

   _<b>[TissueName]\_[Serial-ID-Number]\_[YYYY-MM-DD]\_[Status].[csv]</b>_
   
   <br>
   
   _Example_02:_

   _The image files are named <b> lll\_ssss\_rr\_vv.tif </b> where:_

     _lll = Three digits location code to indicate where the image was generated_

     _ssss = Numeric sample Id_

     _rr = Resoulation level_

     _vv = Two digits version code_


<details>
  <summary> <b>References</b> </summary>
<br>
  This page organized knowledge and experiences from following resources:

  1. [HMS RDM 2020 Workshop - How to name a file](https://www.youtube.com/watch?v=WKViHPvBo_Y&list=PLWIsV2soJK-VaW7IhxYyyOwiamjVV_FuB&index=87)
  
  2. [CDS - File Management](https://data.research.cornell.edu/data-management/storing-and-managing/file-management/)

</details>
