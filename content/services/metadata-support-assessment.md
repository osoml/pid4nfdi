---
title: Metadata Support and Assessment
date: 2024-10-09
type: landing

sections:
  - block: markdown
    content:
        title: Metadata Support and Assessment
        text: | 
            Metadata is essentially _data about data_, providing descriptive information that helps in organizing, finding, and understanding resources. Therefore, metadata support (creating, managing and maintaining metadata) and metadata assessment (evaluating the quality and effectiveness of metadata, and its adherence to standards) are crucial for managing and utilizing digital resources such as research data effectively. Most important is that data is FAIR, which means that the data – and its metadata – meet the [FAIR principles](https://www.go-fair.org/fair-principles/), so that data is Findable, Accessible, Interoperable and Reusable.[^1] Persistent identifiers (PIDs) play a crucial role in making data FAIR.

  - block: markdown
    content:
        title: Tools for Quality Assessment of Metadata
        text: |
            The following tools can help you with assessing metadata, for example if it is in compliance with the FAIR principles or other metadata standards. Furthermore, published overviews and comparisons of the tools for FAIR data assessment give more detailed insights into the workings of the tools and can help you selecting the right one for your purpose.
            
            ## Tools
            
            ### [FAIR-Checker](https://fair-checker.france-bioinformatique.fr)
            The [FAIR-Checker](https://fair-checker.france-bioinformatique.fr) makes use of semantic web technologies to check if metadata is compliant with the FAIR principles. It was developed by the [French Institute for Bioinformatics](https://www.france-bioinformatique.fr/en/home/).
            
            ### [F-UJI FAIR Assessment](https://www.f-uji.net/?action=test)
            The [F-UJI FAIR Assessment](https://www.f-uji.net/?action=test) assesses the FAIRness of research data objects (datasets) based on metrics developed by the [FAIRsFAIR project](https://www.fairsfair.eu). It only requires a PID or URL of the dataset which is to be assessed.
            
            ### [ARDC FAIR Data Self Assessment Tool](https://ardc.edu.au/resource/fair-data-self-assessment-tool/)
            The [ARDC FAIR Data Self Assessment Tool](https://ardc.edu.au/resource/fair-data-self-assessment-tool/) assesses how FAIR your research dataset is and gives practical tips on how to enhance its FAIRness. It is developed by the [Australian Research Data Commons (ARDC)](https://ardc.edu.au/).
            
            ### [FAIR Evaluation Services](https://fairsharing.github.io/FAIR-Evaluator-FrontEnd)
            The [FAIR Evaluation Services](https://fairsharing.github.io/FAIR-Evaluator-FrontEnd) collect resources and guidelines to assess the FAIRness of digital resources. It focuses on maturity indicator tests. It is maintained by the [FAIRmetrics](https://github.com/FAIRMetrics) and the [FAIRsharing](https://sansonegroup.eng.ox.ac.uk/) groups.
            
            ### [AtMoDat Data Checker](https://www.atmodat.de/adc)
            The [AtMoDat Data Checker](https://www.atmodat.de/adc) is a Python-based library that contains checks to ensure compliance with the [AtMoDat Standard](https://www.atmodat.de/atmodat-standard). It is based on the [IOOS compliance checker](https://github.com/ioos/compliance-checker).
            
            ## Overviews and Comparisons of Tools for FAIR Data Assessment
            
            In 2023, The Hyve, a support portal for the life sciences, has published [an overview and evaluation of four FAIR data assessment tools](https://www.thehyve.nl/articles/evaluation-fair-data-assessment-tools). In 2024, the EOSC FAIR-IMPACT project has [published a review](https://fair-impact.eu/news/comparison-tools-automated-fair-software-assessment) in which it examined the application and potential repurposing of three of these assessment tools for assessing FAIR data principles.

  - block: markdown
    content:
        title: Metadata Working Groups within NFDI
        text: |
            Of the sections of the NFDI, which work on cross-sectional topics across the consortia, the one most relevant in terms of PIDs is the section [_(Meta)data, Termino­­lo­gies, Provenance_](https://www.nfdi.de/section-meta/?lang=en). The section includes all consortia and communities and strives for connecting and harmonizing the developments in consortia that work with similar data structures, standards and tools in the topics of the section. Its goals are concepts and recommendations for the harmonization of (meta)data and the evaluation of existing approaches and best practices for the NFDI and beyond, among others. These goals are pursued in the section's different working groups.
            
            [^1]: Also see the original article [_The FAIR Guiding Principles for scientific data management and stewardship_](https://doi.org/10.1038/sdata.2016.18), and the official [interpretation of the FAIR principles](https://www.gofair.foundation/interpretation) as references for guiding FAIR implementation.
---