# TODO 

# OpRa 

# OpRa (Operational Raw Data) XML schema
**(C) 2024-2024 OpRa, CEN**

## Schemas for:

- OpRa
- using NeTEx as submodule (https://github.com/NeTEx-CEN/NeTEx)
- using SIRI as submodule (https://github.com/SIRI-CEN/SIRI)
- using OJP as submodule (https://github.com/VDVde/OJP)

### Overview

- OpRa (Operational Raw Data) complements the Transmodel series (NeTEx for static data, SIRI for dynamic data, OJP for trip description and journey planning) with an additional XML schema to provide a standardized format for exchanging historical data.


### Folder structure 📁

The individual XML files are organized hierarchically in folders, following the same structure as the uses case identified in the OpRa Technical Report. The architecture is: 

- **Main Folder for Each Part**: There is a main folder for each parcategory  of the schema (e.g., Generic, Offer, Demand, Externality, Economy, Efficiency, etc.).
- **Subfolders for Functional Areas**: Within each main folder, there are subfolders for each OpRa functional area, keeping the schema well-structured.

### UML models

- You can refer to the Transmodel UML Conceptual models for a detailed UML view of the schema packages.
- These models are available in electronic format.
  
## Getting started 🚀

### Main root schemas

1. **opra_publication**
   - Embeds OpRa XML model elements in a bulk output file format for use in asynchronous publication.
   - The intended content scope can be indicated by a filter object.

2. **netex_siri.xsd**
   - Embeds OpRa XML model elements in the SIRI protocol for dynamic exchange of elements between servers.
   - Supports both request/response and publish/subscribe.


### XML examples

- Explore XML examples of the use of both protocols in the */examples* subdirectory.

### Support for XML editors

- **Altova XMLSpy Project**: Find an organized view of the schema and examples in the root directory.
   - Project file: OpRa.spp

- **Oxygen Project File**: 
   - Project file: TODO

----

### Note on the schema

The schema is systematically divided into small modular files. Generally, for each functional package in the design model (See UML Model), there are two XML schema files:

- **OpRa_xxxx_suppport.xsd**: Contains data type and ref structure definitions.
- **OpRa_xxxx_version.xsd**: Contains the element definitions.

----
## Branches  🌿

| Branch Name | Description                                             | Link                                            |
| ----------- | ------------------------------------------------------- | ----------------------------------------------- |
| `master`    | Current head of the project                            | [GitHub](https://github.com/OpRa-CEN/OpRa)    |
| `next`      | Work for the next release                              | [GitHub](TBD) |

# Change Log
## Releases
| Release Number | Release Date  | Description                                    | Link | Release Notes                                                                                   |
| -------------- | ------------- | ---------------------------------------------- | ------------- | ----------------------------------------------------------------------------------------------- |
| 1.0            | Month 2024    | Initial productive version | [Code](https://github.com/OpRa-CEN/OpRa/releases/tag/v1.0) | [Release Notes](https://github.com/OpRa-CEN/OpRa/blob/v1.0/README.md) |

## Full Version History 📚

