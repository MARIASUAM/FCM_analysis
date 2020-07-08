# README

This folder contains the data required to execute the analysis of Fuzzy Cognitive Maps elicited, analysed and presented by M. Suárez-Muñoz, F.J. García-Bonet, M.B. Neumann and M. Olazabal.

Description of folders:

input_files: contains the set of original and homogenised matrices used in the scripts. 

database: contains a set of tables which allows to build a database for further analysis. Description of tables:

	- Table_Concepts.csv - list of homogenised concepts. Variables: concept ID, name, definition, tag, DPSIR concept class

	- Table_Relationships.csv - list of unique relationships. Variables: relationship ID, Source (concept_name), Target (concept_name)

	- Table_Matrix_to_Relationships.csv - list of all elicited relationships. Variables: ID, ID_matrix, ID_relationship, weight

	- Table_Matrices.csv - matrices information. Variables: matrix ID, stakeholder action level, stakeholder age range, stakeholder knowledge area, stakeholder type ID

	- Table_Workbench.csv - homogenisation worbench. Variables: element ID, matrix ID, original concept, concept translation, terminological homogenisation, hierarchical homogenisation, sign change requirement, disaggregaition requirement, final concept ID

	- Table_Stakeholders_types.csv - stakeholder type ID, stakeholder type