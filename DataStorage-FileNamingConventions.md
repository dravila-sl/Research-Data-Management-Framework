# File Naming Conventions

<b>Before naming a file or a specific dataset: </b>

1. Check with your team if there is an estblished file naming convention.

2. Conventions should be documented so others in your team or lab could follow. 

3. It is not likely to have one convention for all files. Use different conventions for different type of files or datasets.


<details>
<summary> <b>Things to consider before establishing a naming convention</b> </summary>
  
1. What distinct these files from other files? (Consider metadata like the content, date, location, etc.)

2. Pick three most important metadata. (It is not a "the more the merrier" situation)

3. The name should be human readable and contain enough information for visually scanning the files.


</details>

<details>
<summary> <b>Keep the file name short, simple and self-explanatory</b> </summary>
  
1. Use abbreviation or code
   
   _Example: Labotory A = LabA, Project 2 = P2, Mouse with serial number 255 = MOU-255_
   

3. Document the chosen abbreviation and codes. Do not leave any "commonly known" abbreviation undocumented.

</details>

<details>
<summary> <b> Track the change of files</b> </summary>
  
1. Add version information. Could be number (_i.e. v1.2, v3.0_) or status (_i.e. \_processed, \_amended, \_raw_).

2. Add a date. Make sure the format of date is consistent. (_i.e. using YYYYMMDD or YYYY-MM-DD_)

</details>

<details>
<summary> <b> The order of metadata in the name</b> </summary>
  
1. Place the most important metadata at the beginning.

2. How would you like to sort the files? _(i.e. alphabetically, numerically or chronologically)_

</details>

<details>
<summary> <b> Recommended practices </b> </summary>
  
1. Use two digits for numbering
   _Example: using "01_File.tif", "05_file.tif" instead of "1_File.tif"._

   _Otherwise "10_File.tif" will appear on the top when sorting the files._

2. No spaces or special characters in the name.
3. Be case-sensitive for the machine readability. (_i.e. "sample" vs "Sample"_)

   Use dash "-" to seperate numbers.

   Use underscore "_" to seperate metadata.

   Capitalize the first letter of each word to make it readable.

4. Document naming convention in a ReadMe text and keep it with the files.
  
   _Example:_

   _The naming convention is:_

   _[Serial-ID-Number]\_[LabTestCode]\_[YYYY-MM-DD]\_[Version]\_[Status].[csv]_

</details>
