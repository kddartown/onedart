---
title: Documenting your order - DArT sample file format description and preparation method
layout: article
keywords: ["key1", "key2"]
description: "DArTFAQ"
author: DArTSupport
author_image: /assets/img/author.png
date: August 11, 2022
updated: August 01, 2022
categories: ordering
---

You can use your DArT sample tracking file to define and track your samples, once they have arrived at our lab.

The Sample Tracking File is a “comma separated values” (\*.csv) file with the following columns:

​ PlateID,Row,Column,Organism,Species,Genotype,Tissue,Comments

The easiest way to create this file is to use the guidelines outlined in S*teps to Create a Sample Tracking File*. After you create the template, fill in the Genotype column. This will usually be enough to create an appropriate sample tracking file to order the service

The Genotype Name can be any string of less than 100 characters long, **uniquely identifying the sample**.

Some other requirements include:

| **Requirement**     | **Description**                                                                                                                             |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Commas (,)          | Must be used to separate fields in the CSV file                                                                                             |
| Illegal Characters  | semi colon (;), single quote (‘) and double quote (“)                                                                                       |
| Mandatory fields    | All fields must have values except for Species and Comments, which may remain blank                                                         |
| Species Name        | If there is uncertainty with the species name, leave the Species Name column blank. Add the Species Name in the Comments column             |
| 94 Sample Plates    | The CSV file cannot contain information for wells G12 and H12                                                                               |
| Empty wells         | Do not include any empty wells in the Sample Tracking File. DArT CAN NOT ACCEPT any alternatives to empty wells - eg Blank, N/A, Water, TBA |
| Name Compliance     | Names of organisms and tissues must match our database. If you can’t find the required organisms and tissues, please contact DArT           |
| Name Length         | Names of genotypes can be any string of less than 100 characters                                                                            |
| Unique Combinations | PlateID, Row and Column must be unique within the sample tracking file                                                                      |

### Here’s an example of a correct Sample Tracking File

PlateID,Row,Column,Organism,Species,Genotype,Tissue,Comments

1,A,1,Barley,Hordeum vulgare L.,genotype 1,leaf,header row (above) must be present in the file

1,B,1,Barley,Hordeum vulgare L.,genotype 2,leaf,genotype name number

21,C,1,Barley,Hordeum vulgare L.,genotype 2,leaf,genotype 2 again - names can repeat

2,A,1,Barley,Hordeum vulgare L.,genotype 3,leaf,start of plate 2 (skipping empty wells) - no records for them

2,B,1,Barley,Hordeum vulgare L.,genotype 4,root,tissues (here root) may vary within a file

2,C,1,Barley,Hordeum spontaneum K. Koch,genotype 5,leaf,species names may vary within a file

pl3,A,1,Barley,Hordeum vulgare L.,genotype 6,leaf,start of plate 3 - plate ids do not have to be consecutive numbers

pl3,B,1,Barley,,genotype 7,root,names of Species are not compulsory to provide

pl3,C,3,Barley,Hordeum vulgare L.,genotype 8,leaf,no gaps in wells, samples organised column-wise

> Remember wells G12 and H12 are used for controls and MUST BE LEFT EMPTY

![document](/assets/img/document.png)

Green represents a sample. Wells G12 and H12 must be left empty.

![docuent](/assets/img/document-2.png)

Green represents a sample. White circles indicate empty wells. If there are partial plates in the order, they should be assembled in columns as shown by the arrows in this diagram, starting with A1, B1, C1 - H1, then A2, B2, C2 - H2, then A3 and so on as required. All unused wells must be empty, and must not be included in the Sample Tracking File.
