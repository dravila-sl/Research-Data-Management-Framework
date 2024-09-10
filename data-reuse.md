> [!TIP]
> FAIR indicator: `[Findable]()` `[Accessable]()` `[Interoperable]()` `[Reusable]()`
>
> Project stage: `Beginning`  || Audience: `PI`, `Researcher`, `PhD`

# Reusing Existing Data

### What is data reuse?

Before starting your project, it's worth checking if the data you need is already available. In recent years, there has been a rapid growth in data produced by researchers, governments, non-profits, and industries. Rather than generating new datasets, you might benefit from reusing existing ones.

Data reuse refers to utilizing data for purposes beyond its original intent. This practice is especially valuable in science, as it allows researchers to analyze and publish findings independently using the same datasets. Reusability is a core aspect of the FAIR principles.

Data that is well-documented, curated, and shared with clear usage guidelines is more likely to be reused. Combining it with other datasets can unlock new, unforeseen insights and applications.

> **Important:**
> When planning to use data collected by others, there are several key factors to consider. It’s crucial to understand the data’s scope and limitations, such as when it was collected and whether it can effectively address your research question. Additionally, check if the metadata (information that describes the dataset) provides enough detail to help you assess its suitability. Equally important is reviewing the data’s licensing terms to ensure you have the necessary permissions to use and share it in line with your objectives. The optimal use and reuse of archived data can only be achieved when its accessibility and reusability are guaranteed. The FAIR data principles provide a framework for ensuring that research data is genuinely open and ready for reuse.

---

### Where can I find existing data to reuse?

A wide range of resources is available for exploring secondary datasets. Finding research data can be challenging due to the vast amount of available data and the variety of sources and formats. Data that follows the FAIR principles—providing a persistent identifier and rich metadata in searchable resources—tends to be easier to find compared to data on personal websites or as supplementary material in journal articles.

<details>
<summary><strong>Research data repositories/Portals/Search engines</strong></summary>

There are national and international online databases that house research data. Typically, this data can be downloaded and reused. These platforms index a wealth of domain-specific and general datasets.

Examples:
- [re3data.org](https://www.re3data.org): The Registry of Research Data Repositories is a great place to start for finding data across various subject areas.
- [FAIRsharing](https://fairsharing.org): A catalog of databases described using BioDBcore guidelines, including information about the standards used in each one.
- [EU Open Data Portal](https://data.europa.eu/euodp/en/home): Offers a wide range of data, including geographic, geopolitical, financial, statistical, electoral, legal, crime, health, environmental, transport, and scientific research data.
- [DataCite Metadata Search](https://search.datacite.org): Provides a large index of research data by gathering metadata for each DOI. You can use it to find datasets, get statistics, and explore connections.

</details>

<details>
<summary><strong>Data journals</strong></summary>

Journals such as *Scientific Data* provide peer-reviewed descriptions of datasets with significant reuse potential.

</details>

<details>
<summary><strong>Within research articles</strong></summary>

Publishers are pushing authors to include information on how to access the data behind their research. So, when you’re looking through journal articles or other literature, you might find links and DOIs (digital object identifiers) that show you how to get and use the data from the article itself. These datasets can be found in supplementary materials sections or within the aforementioned data repositories associated with the journal.

</details>

<details>
<summary><strong>Government and public data sources</strong></summary>

Government websites such as Data.gov (UK, USA, Australia), Data.gouv (France), and govdata.de (Germany) provide extensive public datasets from their respective countries.

</details>

<details>
<summary><strong>Contacting Authors</strong></summary>

If you find a research paper without a description of where to find the data of interest, you may contact the authors to ask about accessing the underlying datasets.

</details>

<details>
<summary><strong>External organizations</strong></summary>

If you are obtaining existing data, that are not publicly available, from an external organization (e.g. hospital), a data agreement needs to be put in place. Contact your supervisor/data steward.

</details>

> [!NOTE]
> Remember, while finding existing research data is valuable, it’s essential to ensure that the data is properly cited, used according to its license, and relevant to your research goals. Always adhere to data usage policies and ethical guidelines when reusing data.

---

### Legal Considerations for Data Reuse

When reusing existing data, it's important to adhere to the specified conditions for access and use. You might face restrictions due to factors like confidentiality or intellectual property rights.

- **Open vs. restricted data**: Some data is freely available for use, while other data may have specific access and usage conditions. Understand whether the data falls into open or restricted categories.
- **Understanding terms and conditions & owner consent**: Review the terms of access and use, ideally provided through an access category, license, or user agreement. If not explicitly stated, determine how to access and use the data and obtain any necessary permissions by contacting the owner/author directly.
- **Consent and Ethical Approval**: Ensure that the data were collected ethically and that reusing it complies with any consent agreements (check if reconsent is needed).
- **Proper citation**: Cite the data in your publications as required by the access and use conditions. Proper citation is also a key aspect of research integrity, so always acknowledge the original sources of the data.

---

### Assessing the Quality of Data Archives

Data archives should meet quality standards for the data they store and make accessible. Before using a data source for your work, review:

- The repository’s policies and guidelines
- Any certifications it holds, like CoreTrustSeal or ISO/DIN standards

If the data archive lacks certifications, the following are some points to consider if you plan to use their data:

- **Persistent identifiers**: Check for the use of persistent identifiers, such as DOIs, to ensure data discoverability.
- **Metadata adequacy**: Verify if there is adequate metadata to support the reuse of the data.
- **Versioning**: Check for versioning policies to ensure consistency in data usage.
- **Long-term availability**: Assess whether the data source is stable and likely to remain available throughout the research.

---

### Getting to know the data

To effectively use data, it's crucial to:

- **Review Documentation**: Examine the documentation that includes collection methods, data cleaning processes, and technical details like study descriptions (metadata), user guides, codebooks, or data dictionaries.
- **Familiarize Yourself with the Data**: Thoroughly understand the data to assess its relevance and suitability for your research.
- **Assess Data Suitability**: Evaluate whether the data is appropriate for your research needs and objectives.

---

### Data Resource Versioning

Understanding and managing versioning is crucial when working with data resources. Here’s how to handle versioning effectively:

- **Check Versioning Policies**: Review the versioning policies of the data source to understand how updates are managed and documented.
- **Select the Appropriate Version**: Choose the version of the data that best fits your needs and ensure you have access to it.
- **Manage Updates**: Decide how you will handle future updates to the data. If you need a specific version, consider downloading and storing it to ensure you can always access it.
- **Document Your Version**: Record and publish the exact version of the data you used in your analysis to maintain transparency and reproducibility.
- **Subscribe for Updates**: If available, subscribe to notifications for updates to stay informed about changes.
- **Clarify Update Policies**: If the update policy is unclear, contact the data provider to seek clarification and suggest including a versioning policy if none exists.

---

### Harmonizing Data Sources

When reusing data from multiple sources, it’s important to ensure consistency and compatibility. Consider the following aspects to effectively integrate and utilize diverse datasets:

- **Data Formats**: Review how data elements are formatted across different sources to ensure compatibility with your analysis tools.
- **Terminology Consistency**: Check for consistency in terminology across data sources and adjust your analysis pipelines accordingly.
- **Data Capture Strategies**: Consider how the formats and structures of various data sources will impact your approach to capturing and integrating data.
- **Metadata Management**: Assess whether metadata needs to be translated or mapped to ensure it aligns with your data’s structure and use.
- **Data Integration**: Where possible, reformat data to enable better integration and linkability, and provide feedback to data source providers to improve their datasets.

> [!NOTE]
> Compliance with License Agreements: Some data licenses require that any modifications or derivatives be communicated to the original data provider. This ensures that the data owner is aware of how their data is being used and modified.

---

### Best Practices for Reusing Data

1. **Check Data Sources**: Use reliable, trusted repositories with clear licensing policies. Make sure the quality of the data is sufficient for your research undertaking.
2. **Metadata Matters**: Ensure datasets are accompanied by sufficient metadata to understand the data structure and collection context.
3. **Data Standards and Formats**: Understand the data formats and standards used, and determine if conversion or ETL processes are necessary for integration into your workflow.
4. **Document Your Work**: Add relevant metadata to how you modified the data
5. **Keep Track of Versions**: Always document the dataset version and track updates. Consider the need to store a local copy to ensure long-term access to the same version.
6. **Legal and Ethical Compliance**: Verify consent and licensing, especially when working with sensitive data.
7. **Cite Properly**: Follow citation guidelines to ensure proper credit is given to data providers.

---

<blockquote>
  
Authors: Ahmad Abu Dayeh
 
Last updated: 2024.09.10

References:
  1. Mons, B. (2021). Data Stewardship for Open Science: Implementing Fair principles. Chapman & Hall/CRC

Supplementary reading:
 
  1. [Can I reuse someone else’s research data?](https://www.openaire.eu/can-i-reuse-someone-else-research-data)
  
  2. [Data reuse stories & use cases](https://www.openaire.eu/data-reuse-use-cases)

</blockquote>
