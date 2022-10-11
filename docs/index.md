---
title: "GDSCN Book: SARS Phylogeny on AnVIL"
date: "October 11, 2022"
site: bookdown::bookdown_site
documentclass: book
bibliography: book.bib
biblio-style: apalike
link-citations: yes
description: "This book provides resources for instructors to engage students in a cloud-based RStudio activity on AnVIL, focused on the evolutionary history of SARS-CoV-2 variants."
favicon: assets/GDSCN_style/gdscn_favicon.ico
output:
    bookdown::word_document2:
      reference_docx: assets/gdscn-template.docx
      toc: true
---

# Overview {-}

This book provides resources for instructors to engage students in a cloud-based RStudio activity on AnVIL, focused on the evolutionary relationships among the SARS-CoV-2 variants.

There is a growing need for undergraduate students to learn cutting-edge concepts in genomics data science, including performing analysis on the cloud instead of a personal computer. This lesson aims to introduce basic tree building and interpretation using publicly available genetic samples of SARS-CoV-2. Students will be introduced to the sequencing revolution, variants, the basics of tree building and reading phylogenies, and essentials of cloud computing prior to the lab activity. During the lesson, students will work hands-on with RStudio on the [AnVIL](https://anvilproject.org/) cloud computing resource to check data, build trees, and visualize their results.

## Skills Level {-}

<div class = "notice">
_Genetics_  
**Beginner**: minimal genetics knowledge needed
 
_Programming skills_  
**Beginner**: minimal programming experience needed
</div>

## Learning Objectives {-}

Learning objectives for this activity come from the [Genetics Core Competencies](https://genetics-gsa.org/education/genetics-learning-framework/):

- Generate and interpret trees displaying experimental results
- Use bioinformatics to assess genetics data
- Tap into the interdisciplinary nature of science

## AnVIL Collection {-}

Please check out our full collection of AnVIL resources below!

<table>
 <thead>
  <tr>
   <th style="text-align:left;"> Book Name </th>
   <th style="text-align:left;"> Description </th>
   <th style="text-align:left;"> Topics </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> [AnVIL Phylogenetic-Techniques](https://jhudatascience.org/AnVIL_Phylogenetic-Techniques/) ([github](https://github.com/jhudsl/AnVIL_Phylogenetic-Techniques)) </td>
   <td style="text-align:left;"> https://jhudatascience.org/AnVIL_Phylogenetic-Techniques/ </td>
   <td style="text-align:left;"> anvil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> [AnVIL: Getting Started](https://jhudatascience.org/AnVIL_Book_Getting_Started) ([github](https://github.com/jhudsl/AnVIL_Book_Getting_Started)) </td>
   <td style="text-align:left;"> A guide for getting started using AnVIL </td>
   <td style="text-align:left;"> anvil, cloud-computing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> [AnVIL: Instructor Guide](https://jhudatascience.org/AnVIL_Book_Instructor_Guide) ([github](https://github.com/jhudsl/AnVIL_Book_Instructor_Guide)) </td>
   <td style="text-align:left;"> A guide for instructors using AnVIL for workshops, lessons, or courses. </td>
   <td style="text-align:left;"> anvil, education </td>
  </tr>
  <tr>
   <td style="text-align:left;"> [GDSCN: SARS Galaxy on AnVIL](https://jhudatascience.org/GDSCN_Book_SARS_Galaxy_on_AnVIL/) ([github](https://github.com/jhudsl/GDSCN_Book_SARS_Galaxy_on_AnVIL)) </td>
   <td style="text-align:left;"> Lab module and lectures for variant detection in SARS-CoV-2 using Galaxy </td>
   <td style="text-align:left;"> anvil, genomics, module </td>
  </tr>
  <tr>
   <td style="text-align:left;"> [GDSCN: Statistics for Genomics Differential Expression](https://jhudatascience.org/GDSCN_Book_Statistics_for_Genomics_Differential_Expression/) ([github](https://github.com/jhudsl/GDSCN_Book_Statistics_for_Genomics_Differential_Expression)) </td>
   <td style="text-align:left;"> A set of lab modules for an introduction to differential gene expression </td>
   <td style="text-align:left;"> anvil, cloud-computing, gene-expression </td>
  </tr>
  <tr>
   <td style="text-align:left;"> [GDSCN: Statistics for Genomics PCA](https://jhudatascience.org/GDSCN_Book_Statistics_for_Genomics_PCA/) ([github](https://github.com/jhudsl/GDSCN_Book_Statistics_for_Genomics_PCA)) </td>
   <td style="text-align:left;"> A set of lab modules for PCA analysis </td>
   <td style="text-align:left;"> anvil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> [GDSCN: Statistics for Genomics RNA-seq](https://jhudatascience.org/GDSCN_Book_Statistics_for_Genomics_RNA-seq/) ([github](https://github.com/jhudsl/GDSCN_Book_Statistics_for_Genomics_RNA-seq)) </td>
   <td style="text-align:left;"> A set of lab modules for RNA-seq analysis </td>
   <td style="text-align:left;"> anvil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> [GDSCN: Statistics for Genomics scRNA-seq](http://jhudatascience.org/GDSCN_Book_Statistics_for_Genomics_SCRNA-seq/) ([github](https://github.com/jhudsl/GDSCN_Book_Statistics_for_Genomics_scRNA-seq)) </td>
   <td style="text-align:left;"> A set of lab modules for single cell RNA-seq analysis </td>
   <td style="text-align:left;"> anvil </td>
  </tr>
</tbody>
</table>

