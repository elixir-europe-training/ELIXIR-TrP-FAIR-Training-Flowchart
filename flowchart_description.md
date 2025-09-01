# Make course materials open and FAIR 

At ELIXIR, we aim to have all our training materials Open and FAIR. In this context, Open refers to 'publicly accessible' and [FAIR to Findable, Accessible, Interoperable and Reusable](https://www.go-fair.org/fair-principles/). A good place to start would be the paper “[Ten simple rules for making training materials FAIR](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007854)”. As a second step, it is recommended that the trainer uses the [ELIXIR FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/) to learn more about training materials FAIRification in practive.  The flow chart below helps to organise the associated tasks to make your training materials FAIR. 

!!! warning "The flow chart is **not** chronological"
    Note that the ordering in the flowchart is not in an order as you would apply to your training materials. It is rather a way to collect all the activities/resources. However, the numbering is ordered according to the descriptive text, and can loosly be considered as an order of importance, or even a chronological order. 

![](FAIR_training_flowchart.drawio.svg)

## Explanation of the different components

**1\. Metadata**

Using metadata is important for making your materials findable and reusable. It is therefore very helpful to check whether the associated metadata is correct, in the right standard, and available. Metadata can be associated with training materials in many ways. Therefore, depending on the registries/databases you are using, you might have to make your metadata available in multiple places. More information in the [FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_04/), including on the richness of metadata.

Typically, the standard used is determined by the registry or database you are using. However, one commonly used standard is the [Bioschemas Training Material standard](https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE). This standard is used by, amongst others, the [TeSS](https://tess.elixir-europe.org/) registry. Another frequently used standard for metadata describing training material is the one used by [Zenodo](https://about.zenodo.org/principles/).

For ELIXIR related courses to appear in TeSS, you need to annotate them with the [Training Material](https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE) profile from Bioschemas (more on how to annotate ELIXIR materials in the  [ELIXIR Guide for Bioschemas Annotation of Training Assets](https://elixir-europe-training.github.io/ELIXIR-TrP-Bioschemas/)).

**2\. Attribution**

Reuse is a good practice in developing training materials, and typically, it is absolutely necessary that you give credit to the original authors. You will find a comprehensive explanation of how to do this here:

* [Chapter 10 of the ELIXIR FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_10/#)  
* [ELIXIR FAIR material by design course](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-Material-By-Design/chapters/chapter_05/)

**3\. License**

The default copyright laws apply if a license is not specified, meaning that no one can use, copy, distribute, or modify the materials. You need to add a license to allow others to use your materials. 

For ELIXIR courses, we recommend using the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). More information on licenses can be found:

* [ELIXIR FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_08/#)  
* [ELIXIR FAIR material by design course](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-Material-By-Design/chapters/chapter_05/#53-licenses)

**4\. Accessibility**

In order to make materials open for re-use, it is important that potential re-users can easily access them, that they are in a format that can be re-used, and that they are persistently available. (Internal) servers and cloud instances are typically not a good option because they are often not stable in terms of permissions, availability, and persistence. Therefore, it is recommended to use GitHub linked with Zenodo, or, if you are not using GitHub, host materials on Zenodo. If Zenodo is not an option, you can also use other repositories like Figshare, or institutional repositories.

For ELIXIR courses, we recommend using [GitHub linked with Zenodo](https://help.zenodo.org/docs/profile/linking-accounts/). As mentioned above, if GitHub is not used, materials can be hosted on Zenodo.

**5\. Versioning system**

Using version control like git is a great way to share and collaborate on training materials. You can add your materials directly in the repository, e.g. in GitHub, and let participants interact with the materials through GitHub. It is also possible to host websites with GitHub pages, which might give a nicer interface for the course participants.

For ELIXIR courses, we recommend using GitHub. You can use the following template:

* ELIXIR GitHub [Lesson Template](https://elixir-europe-training.github.io/ELIXIR-TrP-LessonTemplate-MkDocs/) and the [instructions](https://elixir-europe-training.github.io/ELIXIR-TrP-LessonTemplateInstructions-MkDocs/) on how to use the template.

ELIXIR courses are typically hosted within the [ELIXIR Training GitHub organisation](https://github.com/elixir-europe-training). Contact a member of the ELIXIR training team to get access to this organisation. If you name the repository, make sure it ends with \-training. This way, it is clear that it is a training repository.

**6\. Zenodo**

Zenodo is a repository that allows you to deposit your materials and assign a DOI (Digital Object Identifier) to them. It is a great way to make your materials persistent and findable. Zenodo can be used to host training materials, as well as other materials like software, data, and publications.

**7\. Persistent identifier**

A persistent identifier (PID) is a long-lasting reference to a document, file, page, or other object. It is used to ensure that the object can always be found, even if the URL changes. The most common PID is the DOI, which is used for scientific publications. For training materials, the DOI is often used, but there are other PIDs that can be used as well. PIDs are typically assigned if you register your materials in a database or registry.

For ELIXIR courses, we recommend using Zenodo, which assigns a DOI to your materials.

**8\. Specific materials**

Training materials can consist of various types of files, including slides, datasets, notebooks, lecture videos, software, workflows, and more. All of these materials are valuable resources for both learners and trainers to reuse. However, with so many different types of materials, there are also numerous options for repositories. Here are some suggestions for sharing ELIXIR training material types:

* Slides: [Zenodo](https://zenodo.org),  
* Workflows: [WorkflowHubs](https://workflowhub.eu),  
* Docker images: [DockerHub](https://hub.docker.com),  
* Videos: [YouTube](https://www.youtube.com) or [Vimeo](https://vimeo.com/watch). These platforms are very good for sharing and viewing videos, but they are not for long-term storage. For archiving, you can use Zenodo.  
* Datasets: usually it is recommended that you use the repositories that fit your datasets. For instance, ENA for genomics sequencing, PRIDE for proteomics data, etc. If you are not sure of the best repository for your datasets, you can look for the best options in [Re3data.org](http://Re3data.org) or [FAIRsharing.org](http://FAIRsharing.org).

**9\. Glittr.org**

Materials that are hosted on GitHub are often hard to find, especially if they are not indexed elsewhere. Glittr.org is a platform that indexes GitHub repositories and makes them findable. It also provides additional metadata based on the metadata available in the GitHub repository.

All ELIXIR courses on GitHub should be available from Glittr.org. If your course material is missing, submit it at [https://glittr.org/contribute](https://glittr.org/contribute).

**10\. TeSS**

[TeSS](https://tess.elixir-europe.org) indexes training materials and events from various sources, including GitHub repositories. It is a great platform to make your materials findable. TeSS uses the Bioschemas profile that can be automatically scraped from websites. An alternative to using Bioschemas is to manually add metadata to TeSS.

ELIXIR training materials should be findable in TeSS. Contact a member of the [TeSS team](https://www.google.com/url?q=https://tess.elixir-europe.org/about/us%23team&sa=D&source=docs&ust=1755767850648521&usg=AOvVaw3yhnDuh1thwBXBKlPcXS1F) to have more information on how to do these steps. But if you already annotated your materials with the Bioschemas metadata, it should be fairly easy.

**11\. Communication**

Although now your materials have been made FAIR, it is important to communicate this to the world. You can do this by sharing your materials on social media, in newsletters, or by presenting them at conferences.

The recommended channels for sharing your training materials are the ELIXIR Weekly Brief, the ELIXIR LinkedIn pages, and any other social media that you might be using at your own institution (the more you communicate about your materials, the merrier).

### 1. Metadata

Using metadata is important for making your materials findable and reusable. It is therefore very helpful to check whether the associated metadata is correct, in the right standard and is available.  Metadata can be associated with training materials in many ways. Therefore, depending on the registries/databases you are using, you might have to check your metadata in multiple places. More information in the [FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_04/).

Typically, the standard used depends on the registry or database you are using. So, the registries decide on the standards they use. However, one commonly used standard is the [Bioschemas Training Material standard](https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE). This standard is used by amongst others the [TeSS](https://tess.elixir-europe.org/) registry. Another frequently used standard for metadata describing training material is the one used by [zenodo](https://about.zenodo.org/principles/). 

**@ELIXIR:** if you want your training materials to be displayed in TeSS, we recommend you to annotate them with the TrainingMaterial profile from Bioschemas.

### 2. Attribution

Reuse is a good practice in developing training materials, and typically it is absolutely necessary that you give credit to the original authors. You will find a comprehensive explanation of how to this here: 

- [Chapter 10 of the ELIXIR FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_10/#)
- [ELIXIR FAIR material by design course](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-Material-By-Design/chapters/chapter_05/)


### 3. License

Without a license, the default copyright laws apply, meaning that no one can use, copy, distribute, or modify the materials. To allow others to use your materials, you need to add a license. For ELIXIR courses, we recommend using the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). More information on licenses can be found: 

- [ELIXIR FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_08/#)
- [ELIXIR FAIR material by design course](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-Material-By-Design/chapters/chapter_05/#53-licenses)


### 4. Accessibility 

In order to make materials open for re-use, it is important that potential re-users can easily access them, that they are in a format that can be re-used, and that they are persistently available. (Internal) servers and cloud instances typically are not a good option because they are often not stable in terms of permissions, availability and persistence. Therefore, it is recommended to use GitHub linked with Zenodo, or, if you are not using GitHub, host materials on Zenodo. If Zenodo is not an option, you can also use other repositories like Figshare, or institutional repositories. 

**@ELIXIR:** we recommend using GitHub linked with Zenodo. As mentioned above, if GitHub is not used, materials can be hosted on Zenodo.

### 5. Versioning system

Using version control like git is a great way to share and collaborate on training materials. You can add your materials directly in the repository, e.g. in GitHub, and let participants interact with the materials through GitHub. It is also possible to host websites with GitHub pages, which might give a nicer interface for the course participants. 

**@ELIXIR:** we recommend using GitHub. You can use the following template:

- ELIXIR GitHub Lesson Template [Lesson Template](https://elixir-europe-training.github.io/ELIXIR-TrP-LessonTemplateInstructions-MkDocs/)

ELIXIR courses are typically hosted within the [ELIXIR Training GitHub organisation](https://github.com/elixir-europe-training). Contact a member of the ELIXIR training team to get access to this organisation. If you name the repository, make sure it ends with `-training`. This way, it is clear that it is a training repository.

### 6. Zenodo

Zenodo is a repository that allows you to deposit your materials and assign a DOI to them. It is a great way to make your materials persistent and findable. Zenodo can be used to host training materials, but also to host other materials like software, data, and publications. 

<!--  **@SIB:** If you are submitting course material to Zenodo, make sure you add it to the [SIB training community](https://zenodo.org/communities/sib-training/). This way, all SIB training materials are findable in one place. -->

### 7. Persistent identifier

A persistent identifier (PID) is a long-lasting reference to a document, file, page, or other object. It is used to ensure that the object can always be found, even if the URL changes. The most common PID is the DOI (Digital Object Identifier), which is used for scientific publications. For training materials, the DOI is often used, but there are  PIDs that can be used as well. PIDs are typically assigned if you register your materials in a database or registry.

**@ELIXIR:** For ELIXIR courses, we recommend using Zenodo, which assigns a DOI to your materials. 

### 8. Video materials

Videos of lectures are very valuable materials for both learners and trainers to reuse materials. For sharing videos you can use YouTube or Vimeo. These platforms are great for sharing and viewing videos, but they are not for long-term storage. For archiving, you can use Zenodo.

<!--  **@SIB:** we use the [SIB YouTube channel](https://www.youtube.com/@SIBTraining). More information [here](../procedure/record_lectures.md). Currently, we do not have a procedure in place for long-term storage. However, they are stored on the SIB servers.-->

### 9. Glittr.org

Materials that are hosted on GitHub are often hard to find, especially if they are not indexed elsewhere. Glittr.org is a platform that indexes GitHub repositories and makes them findable. It also provides additional metadata based on the metadata available in the GitHub repository.

**@ELIXIR:** All ELIXIR courses on GitHub should be available from Glittr.org. If your course material is missing, submit it at [https://glittr.org/contribute](https://glittr.org/contribute)

### 10. TeSS

TeSS indexes training materials and events from various sources, including GitHub repositories. It is a great platform to make your materials findable. TeSS uses the bioschemas profile that can be automatically scraped from websites. An alternative to using bioschemas is to manually add metadata to TeSS.

**@ELIXIR:** ELIXIR training materials should be findable in TeSS. Contact a member of the [TeSS team](https://tess.elixir-europe.org) to have more information on how to do this steps. But if you already annotated your materials with the Bioschemas metadata, it should be fairly easy.


### 11. Communication

Although now your materials have been made FAIR, it is important to communicate this to the world. You can do this by sharing your materials on social media, in newsletters, or by presenting them at conferences.

**@ELIXIR:** The recommended channel for sharing your training materials is through the ELIXIR Weekly Brief, the ELIXIR LinkedIn pages, and any other social media that you might be using at your own institution too (the more you communicate about your materials, the merrier).


