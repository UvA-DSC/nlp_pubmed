# NLP processing of PubMed
Natural Language Processing based on a query to Europe PMC Open Access database. 


# Europe PMC resources

## Europe PMC API documentation 

[Link to resources](https://www.ebi.ac.uk/training/online/courses/embl-ebi-programmatically/europe-pmc-programmatically/):  

  - Full developer friendly web service [guide](https://www.ebi.ac.uk/training/online/sites/ebi.ac.uk.training.online/files/EBI_Europe_PMC_Web_Service_40_Reference.pdf)

## A nice video tutorial on the Europe PMC REST API

[Link to the video](https://embl-ebi.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=df870f38-5e00-4f8f-8ed7-adce007adbd6)

Rest API
search = module to search the publication database.
fullTextXML = module to retrieve the full text of Open Access articles.

## Creating the query per article type
To search for research-article or review for instance:  
> From the [Europe PMC documentation](https://europepmc.org/RestfulWebService#!/Europe32PMC32Articles32RESTful32API/search):    
User query. Possible options are:
- a keyword or combination of keywords (e.g. HPV virus).
- a phrase with enclosing speech marks (e.g. "human malaria").
- a fielded search (e.g. auth:stoehr).
Available search fields are listed in the Appendix 1 of the Reference Guide or can be retrieved using the fields module of the API.
- a specific publication (e.g. ext_id:781840 src:med)
Specify ext_id as the article identifier, and src as the source database. List of the data sources can be found on the help pages or in section 3 of the Reference Guide.

__pub_type:research-article__  

Example query:  https://www.ebi.ac.uk/europepmc/webservices/rest/search?query=trichome%20pub_type:research-article&pageSize=20

# Wellcome Trust Utilities


# Papers to read

## Building a PubMed knowledge graph

[Building a knowledge graph from PubMed](https://www.nature.com/articles/s41597-020-0543-2)

