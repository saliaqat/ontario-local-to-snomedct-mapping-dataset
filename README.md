# ontario-local-to-snowmedct-mapping-dataset
This repository contains the mappings of procedures for Ontario hospitals to a regional standard.

# Files
**Ontario_local-to-SNOMEDCT_mapping_dataset1.csv** conatins 40,000 rows of procedures and their corresponding regional code/term. This file also indicates which *anonymized* hospital came the procedure came from.

**Ontario_local-to-SNOMEDCT_mapping_dataset2.csv** conatins 120,000 rows of procedures and their corresponding regional code/term. This file does not contain the originating hospital.

# Data Layout
The first 7 columns are the site-specific terminology used to describe the procedure. The **uit_code** column is the corresponding regional procedure code. **provicinal_term** is the description of **uit_code**. *Ontario_local-to-SNOMEDCT_mapping_dataset1.csv* also contains a **src** column provides the originating site's anonimized name. 


