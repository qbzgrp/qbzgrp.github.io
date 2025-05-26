---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-24
type: landing

sections:
  - block: markdown
    id: home
    content:
      title: |
        About Us
      
      text: |
        <br>
        
        Our research group focuses on developing new mass spectrometric capabilities for measurement of biomolecules and the clinical applications of proteomics, lipidomics, and metabolomics. We aim for identification of early disease biomarkers and systems biological understanding of the pathogenic mechanisms underlying human diseases. 

        <p align="center"><img src="group_photo.jpg" height="600" width="800" </p>


  
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: people
    id: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: hero
    id: research
    content:
      title: |
        Proteomic method development
      image:
        filename: Glycation_2DLC.png
      text: |
        <br>
        
        Proteomic method development is driven by biomedical needs in measurement sensitivity, specificity and throughout. Many post-translational modifications to proteins are low abundant, accurate analysis of protein PTM requires specific enrichment methods. We developed online boronic affinity enrichment method for 2DLC-MS/MS analysis of glycated proteins, which has been used in identification of biomarkers to glycemic control and diabetic complications. We also developed laser capture microdissection-based methods for spatial proteomics to investigate the pathologies assoicated with specific cell types in a tissue. In addition, we developed streamlined method for highthroughout plasma protemics with improved proteome coverage, reproducibility and robustness. 

  - block: hero
    content:
      title: |
        Lipidomic method development
      image:
        filename: Glycation_2DLC.png
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
        
  - block: hero
    content:
      title: |
        Early diagnosis of human diseases and mechanistic investigation
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.

  - block: hero
    content:
      title: |
        Informatics
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.

  - block: markdown
    id: apply
    content:
      title: Apply
      text: We always welcome talented researchers to join our lab! Graduate students who wish to pursue a PhD or MS degree in Chemistry, please submit your application through the [graduate program](https://chem.uncg.edu/#academics) in the Department of Chemistry & Biochemistry of UNCG. If you are interested in joining us as a postdoctoral researcher or a research scientist, please contact Dr. Zhang, include a CV and a statement of your research interests and skills and how they align with our research projects.

  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        Our research lab is in the UNCG Center for Translational Biomedical Research, located on the beautiful North Carolina Research Campus in the thriving downtown Kannapolis, a suburb of Charlotte.
      email: q_zhang2@uncg.edu
      phone: 704-250-5803
      address:
        street: 600 Laureate Way
        city: Kannapolis
        region: NC
        postcode: '28081'
        country: United States
        country_code: US
      coordinates:
        latitude: '35.50157'
        longitude: '-80.62401'
      office_hours:
        - 'M-F 9:00 to 6:00'

      # Automatically link email and phone or display as text?
      autolink: true
    
    design:
      columns: '1'
---
