---
layout: papers
title: "The Biological Object Notation (BON): a structured file format for biological data"
authors: ['Buchmann JP', 'Fourment M', 'Holmes EC']
year: 2018
journal: Scientific Reports
doi: 10.1038/s41598-018-28016-6
image: /images/papers/buchmann-bon.png
---

# Abstract

The large size and high complexity of biological data can represent a major methodological challenge for the analysis and exchange of data sets between computers and applications. There has also been a substantial increase in the amount of metadata associated with biological data sets, which is being increasingly incorporated into existing data formats. Despite the existence of structured formats based on XML, biological data sets are mainly formatted using unstructured file formats, and the incorporation of metadata results in increasingly complex parsing routines such that they become more error prone. To overcome these problems, we present the “biological object notation” (BON) format, a new way to exchange and parse nearly all biological data sets more efficiently and with less error than other currently available formats. Based on JavaScript Object Notation (JSON), BON simplifies parsing by clearly separating the biological data from its metadata and reduces complexity compared to XML based formats. The ability to selectively compress data up to 87% compared to other file formats and the reduced complexity results in improved transfer times and less error prone applications.