---
title: Unit 5.2
collaborators: 
date: May 2026
---

## Unit overview

!!! example ""

    **Unit study time**

    - 45 minutes

    **Intended Learning Outcomes**

    By the end of the unit, you will ...


In Units X and X, we explored dataset and variable metadata elements and the benefits of creating structured metadata and in unit X we explored the relationships between metadata. In this activity, you will apply this knowledge to a real example dataset.

We will use Excel to document metadata in this exercise. Excel is widely used, accessible, and familiar to many researchers. It allows you to structure metadata in a clear tabular format, apply basic validation rules, and organise information consistently without requiring specialist software. While other metadata tools exist which produce machine readable output, we will use Excel as a flexible and practical starting point for creating and managing metadata.

!!! important "Excel"
    Excel has features that can help ensure your metadata is clean, structured and standardised. For example, you can lock cells so that metadata element titles can't be changed or you can control what data can be input into certain metadata fields using data validation tools. This helps us to implement contolled vocabularies in our metadata creation (to recap controlled vocabularies, go to unit 2.5 in the Introduction course) and reduces risk of human errors[1].

    You can also download tools compatible with Excel. For example [Collectica for Excel](https://www.colectica.com/software/colecticaforExcel/) is an add-on for Excel which includes pre-defined metadata elements where you can input your metadata directly into the dataset file (rather than having a separate Excel file for your metadata).

We will practice what you've learnt using a small teaching dataset based on the 2011 Young Life and Times Survey delivered by ARK in Northern Ireland. The full dataset has been deposited on the UK Data Service and [can be seen here](https://datacatalogue.ukdataservice.ac.uk/studies/study/7058#details).

**Research practice example**

Imagine you're a social science researcher who has collected data using the survey below.

<img src="../img/Younglifeandtimes2011Qu.png" alt="Alt Text" width="425" height="900"> 

Through conducting this research you create the following dataset.

**Dataset title:** 7058_ylt11 teaching dataset

respondentID | rsex | yearsni | placeliv | ethncat | memmec | thisoct | oct2yrs | typeschl | relschl
------------ | ---- | ------- | -------- | -------- | ------- | ------- | -------- | -------- | -------
1211 | 2 | 16 | 2 | [closed data] | [closed data] | 1 | 1 | 2 | 5
1212 | 1 | 16 | 3 | [closed data] | [closed data] | 1 | 1 | 2 | 1
1213 | 1 | 16 | 2 | [closed data] | [closed data] | 1 | 4 | 2 | 3
1214 | 1 | 16 | 5 | [closed data] | [closed data] | 1 | 1 | 3 | 2
1215 | 2 | 16 | 3 | [closed data] | [closed data] | 4 | 4 | 2 | 2
1216 | 1 | 16 | 1 | [closed data] | [closed data] | 1 | 1 | 3 | 2
1217 | 1 | 16 | 2 | [closed data] | [closed data] | 1 | 1 | 2 | 2
1218 | 2 | 16 | 3 | [closed data] | [closed data] | 1 | 4 | 2 | 1
1219 | 2 | 16 | 2 | [closed data] | [closed data] | 1 | 1 | 2 | 2
1220 | 1 | 16 | 2 | [closed data] | [closed data] | 1 | 1 | 2 | 2

ARK. Young Life and Times Survey, 2011 [computer file]. ARK www.ark.ac.uk/ylt [distributor], May 2012

If you want to use an alternative teaching dataset, you can find more on the UK Data Service. Expand the box below to explore more.

??? info "List of Open Access Teaching datasets from UKDS"

    - 2021 Census: Public Microdata Teaching Sample (England and Wales): 1% Sample: Open Access
    - British Social Attitudes Survey, 2021, Health Care and Equalities: Open Access Teaching Dataset
    - British Social Attitudes Survey, 2019, Poverty and Welfare: Open Access Teaching Dataset
    - British Social Attitudes Survey, 2017, Environment and Politics: Open Access Teaching Dataset
    - SN 7913&nbsp;Opinions and Lifestyle Survey, Well-Being Module, April-May 2015: Unrestricted Access Teaching Dataset
    - SN 7912 Quarterly Labour Force Survey, January - March, 2015: Unrestricted Access Teaching Dataset

    You can download one of these datasets to practice metadata creation. In order to do this, you can download the dataset as a CSV or Excel file and download the user guide for the data so you have the background information about the dataset.

You want to make sure you preserve your data, documenting it clearly for your own records and share documentation where needed with colleagues and collaborators.



>[!NOTE]
> Signpost to other training around metadata creation for other forms research data that is not tabular data 




##Task 1 Create the metadata
Think about what minimum metadata you would create for this study and dataset. Document the study, quustion and responses, dataset and variable metadata. You do not need to document everything. 

You can download and use this template to enter your metadata. If you are not using Excel, you can still complete the task using your preferred tool.

[YLT Metadata template](</YLT_metadata_template.xlsx>)

The template is structured across multiple sheets:

- Study metadata
- Question metadata
- Codes and categories metadata 
- Dataset metadata 
- Variable metadata


Each tab contains a metadata template to describe different areas of the research project. Each metadata element relates to information you have already encountered in this course. If you add new metadata elements to the template, it is important to define them clearly and specify what information should be recorded. This helps ensure that your metadata is consistent and understandable to others.

??? success "Example answer"

    Download this completed Excel template to compare your answers. 
    
    [YLT Metadata template](</YLT_metadata_example.xlsx>)
---

##Task 2: Map the relationships

Describe (or draw) how the following metadata are connected:

- Study 
- Question
- Codes and categories 
- Dataset  
- Variable 

Think about how these relationships would appear in a table for example questions may include a column linking to Variable_ID.

Edit your Excel to include the relationships between the metadata accross the worksheet tabs. 

??? success "Example answer"
    Download this completed Excel template to compare your answers. Focus on how the different levels (study, dataset, variable, question, codes) are connected.

   
    [YLT Metadata template](</YLT_metadata_example_relationships.xlsx>)
    

    What to notice in this example

    - Each level is clearly linked using IDs (Study_ID, Dataset_ID, Question_ID)
    - Variables act as the connection between questions and data
    - Codes are required to interpret categorical values
    - The structure allows someone to trace meaning from value → variable → question → study, as it should reflect real life


    This structure ensures that metadata is:
    
        - connected
        - consistent  
        - reusable  
        - easier to interpret  


## References

- [1] Video explains the tools you can use in Excel to implement metadata best practice: https://www.uu.nl/en/research/research-data-management/guides/during-research/metadata-and-documentation
