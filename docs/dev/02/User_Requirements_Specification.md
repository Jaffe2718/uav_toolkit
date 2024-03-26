# User Requirements Specification of UAV Toolkit

## Change History

| id  |    date    | version | description | reason | proposer | reviewer | approver |
|:---:|:----------:|:-------:|:-----------:|:------:|:--------:|:--------:|:--------:|
| 001 | 2024-03-22 |   1.0   | First Draft |        |   李昌哲    |   李昌哲    |   李昌哲    |

## Catalog

1. [Functional requirements](#functional-requirements)
    1. [UAV Image Correction and Leveling](#uav-image-correction-and-leveling)
    2. [Image Matching Accuracy Checking](#image-matching-accuracy-checking)
    3. [Exposure and Enhancement Tool Development or Integration for Nighttime Urban UAV Images](#exposure-and-enhancement-tool-development-or-integration-for-nighttime-urban-uav-images)
    4. [UAV 3D Visualization Technology Development or Integration](#uav-3d-visualization-technology-development-or-integration)
    5. [Deep Learning UAV Image Processing](#deep-learning-uav-image-processing)
2. [Non-functional requirements](#non-functional-requirements)
    1. [Compatibility Requirements](#compatibility-requirements)
        - [Hardware Compatibility](#hardware-compatibility)
        - [Operating System Compatibility](#operating-system-compatibility)
        - [Software Compatibility](#software-compatibility)
    2. [Performance Requirements](#performance-requirements)
    3. [Product Release Format](#product-release-format)

## Functional Requirements

### UAV Image Correction and Leveling

1. Develop a plug-in that can achieve the following functions: Import drone images in batches in Arcgis pro,
And the UAV image coordinates are accurately corrected and displayed in Arcgis pro.

### Image Matching Accuracy Checking

[//]: # (TODO: 由满宇填写)

### Exposure and Enhancement Tool Development or Integration for Nighttime Urban UAV Images

[//]: # (TODO: 由彭焱、苏雅填写)

### UAV 3D Visualization Technology Development or Integration

[//]: # (TODO: 由杨希哲、南明骏填写)

### Deep Learning UAV Image Processing

1. Develop a tool to automatically segment all objects in the UAV image.
2. Develop a tool to segment specified objects in the UAV image.

## Non-Functional Requirements

### Compatibility Requirements

#### Hardware Compatibility

| Requirement | Description  |
|:-----------:|:------------:|
|     CPU     | x86-64/ARM64 |
|     RAM     |    >= 8GB    |
|   Storage   |   >= 100GB   |
|     GPU     |  (optional)  |

#### Operating System Compatibility

At least Windows 10 and Windows 11 are supported.

- OS
  - Windows
     - [x] Windows 10
     - [x] Windows 11
     - [ ] Windows Server (Optional)
  - Linux
  - macOS
  - ...

#### Software Compatibility

- ArcGIS Pro 3.0 and above versions
- Python >= 3.9

### Performance Requirements

Just run normally, no excessive requirements.

### Product Release Format

- [x] Source Code
- [x] Documentation
- [x] Toolkit in python toolbox format (`*.pyt`)
