# TAMIDS-Assessment

This is data extraction assessment towards the RDASH project. Below is the small description of each file in this repository:
1. **export.csv** - This is an input file which can be sourced from below page of [SCHOLARS@TAMU](https://scholars.library.tamu.edu/vivo/directory/People?collection=individual&fl=type,name,preferredTitle,researchAreas,positions,positionOrganization,thumbnail&facets=type,positionOrganization,researchAreas_nested_facets,selectedPublicationTag&type.type=STRING&type.pageSize=10&type.pageNumber=1&type.sort=COUNT,DESC&positionOrganization.type=STRING&positionOrganization.pageSize=10&positionOrganization.pageNumber=1&positionOrganization.sort=INDEX,ASC&researchAreas_nested_facets.type=STRING&researchAreas_nested_facets.pageSize=10&researchAreas_nested_facets.pageNumber=1&researchAreas_nested_facets.sort=COUNT,DESC&selectedPublicationTag.type=STRING&selectedPublicationTag.pageSize=10&selectedPublicationTag.pageNumber=1&selectedPublicationTag.sort=COUNT,DESC&class.filter=Person&class.opKey=EQUALS&filters=class&sort=name_sort,ASC&page=1). It gives a list of urls of individual web pages of all scholars available in the directory.

2. main.ipynb - This is the actual code file that extract required scholars data from the apis embedded in those web pages.

3. Scholar_Info.xlsx - Contains the dataset of Name, Email , Department (Dept), Keywords (comma-seperated), Publication List (Pub List-comma seperated).

## NOTE:

This code is adjusted to contain upto 100 scholars whose all required fields are available(*due to computation contraints).
