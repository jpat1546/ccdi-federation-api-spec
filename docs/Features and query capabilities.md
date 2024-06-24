# CCDI Federation Open API v1.0.0 Query Functionality
---

## Subjects

### Retrieve All Subjects:
Easily access a comprehensive list of subjects within the CCDI federated ecosystem.
- **Filtering:** Refine your search by sex, race, ethnicity, identifiers, vital status, age at vital status, and unharmonized metadata fields.

### Retrieve Specific Subject by ID:
Quickly fetch detailed information about a specific subject using its unique ID (organization, namespace, and name).

### Group Subjects and Get Counts:
Organize subjects by any metadata field and receive aggregated counts for better insights.
- **Fields include:** Sex, race, ethnicity, identifiers, vital status, age at vital status.

### Summary Information for Subjects:
Obtain summary statistics and high-level information for all subjects in the system.

## Samples

### Retrieve All Samples:
Access an extensive list of samples within the CCDI federated ecosystem.
- **Filtering:** Narrow down results by disease phase, library strategy, preservation method, tissue type, tumor classification, age at diagnosis, age at collection, tumor tissue morphology, depositions, and unharmonized metadata fields.

### Retrieve Specific Sample by Name:
Fetch detailed information about a specific sample using its unique name (organization, namespace, and name).

### Group Samples and Get Counts:
Organize samples by any metadata field and receive aggregated counts for better insights.
- **Fields include:** Disease phase, library strategy, preservation method, tissue type, tumor classification, age at diagnosis, age at collection, tumor tissue morphology, depositions.

### Summary Information for Samples:
Get summary statistics and high-level information for all samples in the system.

## Files

### Retrieve All Files:
Access a comprehensive list of files within the CCDI federated ecosystem.
- **Filtering:** Refine your search by file type, size, checksums, description, depositions, and unharmonized metadata fields.

### Retrieve Specific File by Name:
Quickly fetch detailed information about a specific file using its unique name (organization, namespace, and name).

### Group Files and Get Counts:
Organize files by any metadata field below and receive aggregated counts for better insights.
- **Fields include:** Type, size, checksums, description, depositions.

### Summary Information for Files:
Obtain summary statistics and high-level information for all files in the system.

## Metadata Fields

### Retrieve Metadata Fields for Subjects:
Access detailed metadata fields supported for subjects.
- **Fields Include:** Name, race, sex, vital status, age at vital status, identifiers, ethnicity.

### Retrieve Metadata Fields for Samples:
Access detailed metadata fields supported for samples.
- **Fields Include:** Disease phase, library strategy, tumor classification, tumor tissue morphology, preservation method, tissue type, age at collection, age at diagnosis, depositions.

### Retrieve Metadata Fields for Files:
Access detailed metadata fields supported for files.
- **Fields Include:** Description, name, size, type, MD5 checksum, depositions.

## Namespaces

### Retrieve All Namespaces:
View all namespaces within the server for better data organization.

### Retrieve Specific Namespace by Name:
Fetch detailed information about a specific namespace using its unique name (organization and namespace).

## Organizations

### Retrieve All Organizations:
Access a complete list of organizations within the server.

### Retrieve Specific Organization by Name:
Quickly fetch detailed information about a specific organization using its unique name.

### API Implementation Information:
Get detailed information about the API implementation for better integration and usage.


## Filter Support Table

| Filter                                   | PCDC | CHOP | St Jude | UCSC |
|------------------------------------------|---------|------|---------|------|
| **Subject**                          |         |      |         |      |
| Sex                                      | ✔️      | ✔️    | ✔️       | ✔️    |
| Race                                     | ✔️      | ✔️    | ✔️       | ✔️    |
| Ethnicity                                | ✔️      | ✔️    | ✔️       | ✔️    |
| Disease Phase                            | ✔️      | ✔️    | ✔️       | ✔️    |
| Vital Status                             | ✔️      | ✔️    | ✔️       | ✔️    |
| ICD-O Morphology Code & Term             | ✔️      | ✔️    | ✔️       | ✔️    |
| Participant ID                           | ✔️      | ✔️    | ✔️       | ✔️    |
| **Sample**                               |         |      |         |      |
| Sample Tumor Status                      |       | ✔️    | ✔️       | ✔️    |
| Tumor Classification                     |       | ✔️    | ✔️       | ✔️    |
| Age at Vital Status                      |       | ✔️    | ✔️       | ✔️    |
| Age at Diagnosis                         |       | ✔️    | ✔️       | ✔️    |
| Participant Age at Collection            |      | ✔️    | ✔️       | ✔️    |
| Library Strategy                         |      | ✔️    | ✔️       | ✔️    |
| Preservation Method                      |       | ✔️    | ✔️       | ✔️    |
| Disease Diagnosis (partially Implemented)|       |     |       | ✔️    |
| **Study**                                |         |      |         |      |
| Study Short Title                        |    ✔️ depositions?   | ✔️ depositions?   | ✔️ depositions?       | ✔️ depositions?    |
| Study Name                               |   ✔️ depositions?   | ✔️ depositions?    | ✔️ depositions?       | ✔️ depositions?    |
| dbGaP phs Accession                      |    ✔️ depositions?  | ✔️ depositions?    | ✔️ depositions?       | ✔️ depositions?    |
| Institution                              |   ✔️ depositions?   | ✔️ depositions?    | ✔️ depositions?       |✔️ depositions?    |
| **File**                                 |         |      |         |      |
| File Location (Link/Gateway)             |       | ✔️    | ✔️       | ✔️    |
| File Description                         |      | ✔️    | ✔️       |     |
| File Size                                |      | ✔️    | ✔️       |     |
| Md5sum                                   |       | ✔️    | ✔️       |     |
---
The v1.0.0 release of the CCDI Data federation API has been designed to be fully functional, providing useful and accessible information to users. For detailed information on the limitations of this version, please visit (link to limitations doc in this folder)

These features and query capabilities are designed to enhance your experience and efficiency with the CCDI Data federation API. 

For more details, please refer to our [API documentation](https://cbiit.github.io/ccdi-federation-api-aggregation/).
