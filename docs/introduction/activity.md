---
title: Unit 3.0 Creating metadata, study level
authors: 
---

# Unit 3.0 Metadata activity

## Unit overview

!!! example ""

    **Unit study time**

    - 30 minutes

    **Intended Learning Outcomes**

     By the end of the unit, you will be able to ...

     - Identify key metadata elements
     - Evaluate dataset suitability
     - Apply good metadata practices to support FAIR (Findable, Accessible, Interoperable, Reusable) data principles

## Evaluating a dataset using metadata

!!! question ""

    You are looking for data to support a research project on physical activity 
    in young adults in Wales before and after the Covid-19 pandemic.

    Below is a metadata record for a fictional dataset.

    **Dataset metadata**

    - **Title:** Health and Lifestyle Survey  
    - **Creator:** –  
    - **Date:** 2018–2019  
    - **Geographic coverage:** UK  
    - **Topics:** Exercise, diet, demographics, hobbies  
    - **File format:** CSV  
    - **Documentation:** Codebook  
    - **License:** Not specified  

### Task 1: What metadata is useful and what metadata is missing or unclear?

Identify at least two important gaps or ambiguities and two useful aspects of the metadata.

??? success "Example answer"

    **Missing or unclear metadata:**
    
    - Creator (who produced the data)  
    - Population  
    - Sample size  
    - Variable list and definitions  
    - Methodology (how data was collected)  
    - Licensing and access conditions  
    - Whether the codebook is accessible  
    - Geographic detail  

    **Useful metadata:**
    
    - Topics provide an indication of relevance  
    - Presence of a codebook (even if not accessible)  
    - File format (CSV)  
    - Time period

---

### Task 2: Is this dataset suitable for the study?

Based on the metadata, would you use this dataset for your research?

??? success "Example answer"

    No as it is unclear whether this dataset is suitable based on the available metadata.

    - The data only covers the pre-pandemic period (2018–2019), so it does not support comparison with post-pandemic data. It also does not state whether similar data was collected later.  

    - The population is not described, so it is unclear whether young adults are included.  

    - Geographic coverage is broad (UK). While this may include Wales, this is not explicit and does not indicate sample size or breakdown.  

    - Missing creator information makes it difficult to assess credibility.  

    - Licensing is unclear, so reuse may not be permitted or may involve restrictions (e.g. fees, application process, secure access).  

    - Variables are not listed, so it is unclear whether relevant measures are included.  

---

### Task 3: What would you do next?

If you wanted to use this dataset, what steps would you take?

??? success "Example answer"

    - Check whether post-pandemic data exists  
    - Look for additional documentation  
    - Locate and review the codebook  
    - Identify where the dataset is stored (repository or catalogue)  
    - Contact the data provider for clarification  
    - Search for alternative or additional datasets  

---

### Task 4: How could this metadata record be improved?

What specific changes would make this metadata record easier to find, understand, 
and decide whether it is suitable for your research?

??? success "Example answer"

    **Key improvements (quick summary):**
    
    - Add population and methodology details  
    - Clarify geographic coverage  
    - Provide licensing and access information  
    - Include a persistent identifier to the data (e.g. DOI)  
    - Provide a link to the codebook  

    **More detailed improvements:**

    The metadata could be improved by making it more complete and aligned with 
    recognised standards and controlled vocabularies.

    - **Apply a metadata standard (e.g. Dublin Core):**
          - *Title* – Expand to include more relevant details (e.g. study name, population)  
            → Improves findability and helps assess relevance  

          - *Creator* – Include the organisation or researchers responsible (add ORCID IDs)  
            → Supports trust and assessment of data quality  

          - *Description* – Provide a clear summary including purpose, methodology, and population  
            → Improves understanding and suitability decisions  

          - *Publisher* – State the organisation hosting the data  
            → Helps locate and assess reliability  

          - *Coverage* – Specify geographic detail (e.g. GB-WLS for Wales)  
            → Improves relevance to the research question  

          - *Identifier* – Include a DOI or stable link  
            → Ensures reliable access and citation  

          - *Rights* – Clearly state licensing and reuse conditions  
            → Enables decisions about access and reuse  

    - **Improve detailed documentation:**
        - Ensure the codebook is accessible  
        - Include variable-level metadata (names, labels, definitions)  
        → Supports interpretation and analysis  

    - **Use controlled vocabularies:**
        - Standard subject terms or discipline-specific terms (e.g. “exercise” vs “physical activity”)  
        - Standard geographic codes (e.g. ISO 3166: GB-WLS)  
        → Improves searchability, consistency, and interoperability  

    **Overall:**

    These improvements make the dataset:
    
    - **Easier to find** through clear titles, identifiers, and standardised terms  
    - **Easier to understand** through detailed descriptions and documentation  
    - **Easier to assess and reuse** through clear provenance, coverage, and licensing  

---

### Task 5: Reflection

- Think about your own research or a dataset you have used. What metadata did you rely on most?  
- What is one thing you will do differently when creating or using metadata after this activity?  

---

### Summary

Good quality metadata allows researchers to quickly assess whether a dataset is relevant, reliable, and usable. Incomplete or unclear metadata can make valuable data difficult to find, interpret, or reuse. Metadata is not just descriptive, it supports decision-making throughout 
the research process.
