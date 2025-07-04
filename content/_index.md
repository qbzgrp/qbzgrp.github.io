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
        
        Our research group focuses on developing new mass spectrometric capabilities for measurement of biomolecules and the clinical applications of proteomics, lipidomics, and metabolomics. We aim for identification of early stage disease biomarkers and systems biological understanding of the pathogenic mechanisms underlying human diseases. 

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

  - block: markdown
    id: research
    content:
      title: Proteomic method development
      text: |-
        <div style="display: flex; justify-content: space-between; margin-top: 20px;">
          <div style="width: 65%; display: flex; align-items: center;">
            <p>
              Analytical method development is driven by biomedical needs in measurement sensitivity, specificity and throughout. Many post-translational modifications to proteins are low abundant, accurate analysis of protein PTM requires specific enrichment methods. We developed online boronic affinity enrichment method for 2DLC-MS/MS analysis of glycated proteins, which has been used in identification of biomarkers to glycemic control and diabetic complications. We also developed laser capture microdissection-based methods for spatial proteomics to investigate the pathologies assoicated with specific cell types in a tissue. In addition, we developed a streamlined method for highthroughout plasma proteomics with improved proteome coverage, reproducibility and robustness.
            </p>
          </div>
          <div style="width: 30%; display: flex; align-items: center;">
            <img src="/uploads/Glycation_2DLC.png" alt="glycation image" style="width: 100%; border-radius: 8px;">
          </div>
        </div>

  - block: markdown
    content:
      title: Lipidomic method development
      text: |-
        <div style="display: flex; justify-content: space-between; margin-top: 20px;">
          <div style="width: 30%; display: flex; align-items: center;">
            <img src="/uploads/lipids.png" alt="lipids image" style="width: 100%; border-radius: 8px;">
          </div>
          <div style="width: 65%; display: flex; align-items: center;">
            <p>
              Lipids are structurally very diverse molecules. Different classes of lipids have different chemical properties, which makes their separation and identification from a complex biological sample very challenging.  We developed methods for comprehensive lipidomic analysis, which include offline 2DLC separation coupled with high resolution mass spectrometry, novel ion chemistry OzNOxESI for determination of C=C position within unsaturated lipids, isobaric chemical labeling for more sensitive and multiplexed analysis of gangliosides, and very specific method for distinguishing isomeric oxylipins. 
            </p>
          </div>
        </div>

  - block: markdown
    content:
      title: Human disease biomarkers and human performance assessment
      text: |-
        <div style="display: flex; justify-content: space-between; margin-top: 20px;">
          <div style="width: 65%; display: flex; align-items: center;">
            <p>
              Reliable biomarkers are greatly needed in clinics for early diagnosis of human diseases and for assessment of human performance. Our lab is the first that reported the most comprehensive profiling of longitudinal changes in plasma proteome during childhood development. Applying proteomics and lipidomics, we have identified panels of proteins that predict the onset of type 1 diabetes, established gangliosides as a critical factor in hepatitus A virus entry into the host cells and assessed functional foods in their effect on mitigating the inflammation induced by intensive exercise. This line of research is typically done collaboratively with renowned scientists and clinicians in diabetes, hepatitis, virology and sports medicine. 
            </p>
          </div>
          <div style="width: 30%; display: flex; align-items: center;">
            <img src="/uploads/mehari.jpg" alt="research image" style="width: 100%; border-radius: 8px;">
          </div>
        </div>

  - block: markdown
    content:
      title: Informatics
      text: |-
        <div style="display: flex; justify-content: space-between; margin-top: 20px;">
          <div style="width: 30%; display: flex; align-items: center;">
            <img src="/uploads/software.png" alt="lipids image" style="width: 100%; border-radius: 8px;">
          </div>
          <div style="width: 65%; display: flex; align-items: center;">
            <p>
              We developed <a href="https://github.com/QibinZhangLab">software tools</a> for automated processing of isotopic labeling mass spectrometry data and of the data generated by the novel OzNOxESI ion chemistry for C=C position analysis in lipids. Developing niche software to facilitate mass spectrometric data processing and data visualization will be a continous focus area of our research.
            </p>
          </div>
        </div>

  - block: markdown
    id: apply
    content:
      title: Apply
      text: We always welcome talented researchers to join our lab! Graduate students who wish to pursue a PhD or MS degree in Chemistry, please submit your application through the [graduate programs](https://chem.uncg.edu/#academics) in the Department of Chemistry & Biochemistry of UNCG. If you are interested in joining us as a postdoctoral researcher or a research scientist, please contact Dr. Zhang, including a CV, a statement of your research interests and skills and how they align with our research projects.

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
