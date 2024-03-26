# Feasibility Analysis of the UAV Toolkit

|              proposer               |              reviewer               |              approver               |
|:-----------------------------------:|:-----------------------------------:|:-----------------------------------:|
| [李昌哲](https://github.com/Jaffe2718) | [李昌哲](https://github.com/Jaffe2718) | [李昌哲](https://github.com/Jaffe2718) |

## Change History

| id  |    date    | version |   description    |       reason        | proposer | reviewer | approver |
|:---:|:----------:|:-------:|:----------------:|:-------------------:|:--------:|:--------:|:--------:|
| 001 | 2024-03-19 |   1.0   |   First Draft    |                     |   李昌哲    |   李昌哲    |   李昌哲    |
| 002 | 2024-03-22 |   1.1   | Content revision | Specific objectives |   李昌哲    |   李昌哲    |   李昌哲    |

> **Note:** The reason for the change is mainly divided into:
> 1. Establish the first draft
> 2. Content revision
> 3. Official release

## Catalog

1. [Document Overview](#document-overview)
    1. [Purpose](#purpose)
    2. [Scope](#scope)
    3. [Readership](#readership)
    4. [Reference Documents](#reference-documents)
2. [Project Introduction](#project-introduction)
    1. [Overview](#overview)
    2. [Background](#background)
    3. [Objectives](#objectives)
    4. [Range of Application](#range-of-application)
    5. [Assumptions and Dependencies](#assumptions-and-dependencies)
3. [Status Quo and User Requirements](#status-quo-and-user-requirements)
    1. [User Analysis](#user-analysis)
    2. [User Environments](#user-environments)

## Document Overview

### Purpose

The purpose of this document is to provide a comprehensive analysis of the feasibility of the UAV Toolkit project.

### Scope

This document should not replace the outputs of other project stages such as overall design,
detailed design, code design, test plan, and operation manual. To better understand the content of the document, it is
recommended that readers refer to the listed reference materials to learn more information related to the system.

### Readership

This document is applicable to requirement personnel, design personnel, development personnel, testing personnel,
deployment implementation personnel, other document users stipulated by the project contract, and relevant personnel to
understand the requirements.

### Reference Documents

|        Document Name        |                                 Document Location                                  |
|:---------------------------:|:----------------------------------------------------------------------------------:|
| ArcGIS Pro Python reference | https://pro.arcgis.com/en/pro-app/latest/arcpy/main/arcgis-pro-arcpy-reference.htm |

[//]: # (TODO unfinished)

## Project Introduction

### Overview

Project Name: UAV Toolkit

Developers: [李昌哲](https://github.com/Jaffe2718), [佘誉鸿](https://github.com/sirasuazusa), [南明骏](https://github.com/mingzuer),
[杨希哲](https://github.com/Xizhe03), [彭焱](https://github.com/pengsanhuo), 满宇, 苏雅

This project is a python-toolbox for UAV remote sensing data processing
in ArcGIS Pro environment. It is aimed at providing a series of functions
to help users process and visualize UAV remote sensing data more efficiently.

### Background

With the development of UAV technology, UAV remote sensing technology has been widely used in various fields.
So far, there are many software tools that can be used to process remote sensing data,
but most of them are not specifically designed for UAV remote sensing data processing.
Therefore, the development of a toolkit specifically for UAV remote sensing data processing is necessary.

### Objectives

1. To develop a UAV image correction and leveling tool based on ArcGIS Pro.
2. Exposure and enhancement problems of nighttime urban UAV images, combined with application testing and development of interpretation techniques.
3. To provide a series of functions or develop a tool to help users visualize UAV remote sensing data in 3D.
4. To develop a tool that can be used to check the accuracy of image matching based on ArcGIS Pro.
5. To develop a tool that can be used to optimize the deep learning processing of UAV remote sensing images based on
   ArcGIS Pro.
6. To integrate the above functions into one or more toolkits (`*.tbx`) and provide a user-friendly interface with the
   user documentations as the final product.

### Range of Application

This toolkit is designed to help users process UAV remote sensing data more efficiently.
The toolkit needs to be developed based on Python3,
and it should support ArcGIS Pro 3.0 and above versions, with no special requirements for the operating system.

### Assumptions and Dependencies

1. The toolkit is developed based on Python3, and it should support ArcGIS Pro 3.0 and above versions.
2. The toolkit should be developed based on the ArcGIS Pro Python reference.

## Status Quo and User Requirements

### User Analysis

The target users of this project are mainly professionals and researchers in UAV remote sensing data processing.
They usually have a strong technical background, are familiar with the processing flow of UAV remote sensing data,
and can proficiently use professional software such as ArcGIS Pro.
Their main needs are to process UAV remote sensing data efficiently and accurately,
including data preprocessing, target detection, data visualization, etc.
They expect this tool to provide a one-stop solution, simplify the data processing flow, and improve work efficiency.

### User Environments

| Environment |                            Description                             |
|:-----------:|:------------------------------------------------------------------:|
|  Hardware   | CPU: x86-64/ARM64, RAM: >= 8GB, Storage: >= 100GB, GPU: (optional) |
|     OS      |             Windows 10, Windows 11, Linux, macOS, etc.             |
|  Software   |                 ArcGIS Pro 3.0 and above versions                  |

    