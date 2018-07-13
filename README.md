# MILES 
## Metadata Improvement Lab at ESIP: schema.org

### Presentations

#####  Overview of session
* What is the schema.org vocabulary
* What is JSON-LD
* NOAA's experience implementing them
* What you need to do to your site
* Using ESIPhub
* Metadata upload and prep
* Evaluation and Analysis 
* Guidance Reports
* Create JSON-LD
* Google's Structured Data Testing Tool
* Create your own dialect specific translation

##### Presentation on Schema.org Metadata: NOAA Implementation Status
* https://docs.google.com/presentation/d/1tuA24Xir10nTvn9bVHpI6y-NVydjRaOWWuqNNvn6zsA/edit

##### JupyterLab on ESIPhub tutorial
* [ESIPhub Quickstart](shared/Quickstart.md)
* html rendering of markdown files
* esiphub slack, jupyter slack channels
* logging in
* starting a terminal or Notebook
* navigate the file structure
* Difference between cell types
* running a cell
* altering a cell
* clearing the variables and restarting the kernel
* running all cells
* copying a Notebook
* copy a directory/file from /shared/2018_summer_workshops
    * cp -r shared/2018_summer_workshops/MILES MILES
* Share your own ideas    
* Other uses for the /shared directory

### Notebooks

##### [Ingest and Prepare a Metadata Collection for Evaluation](./00.CreateMetadataCollection.ipynb)
* How you can use JupyterLab's GUI to upload a local metadata record or a zip of many records and move the metadata to a directory
* Download a metadata collection from a repository or other URL
* normalize namespace location so concepts can be read accurately by the Metadata Evaluation Web Service

##### [Create Recommendation Report for a Metadata Collection](./01.CreateRecReport.ipynb)
* evaluate metadata for concepts and xpaths
* refine the conceptual evaluation with a recommendation
* Create data about the collection's concepts and xpaths
* create collection reports on data in Excel and Google Sheets

##### [Create JSON-LD for Datasets Using the schema.org Vocabulary and Test the Results](./02.CreateJSON-LD.ipynb)
* Create csv with recommendation concept content for the collection 
* translate concept names into the schema.org vocabulary
* create valid JSON-LD for a record
* Use Google's [Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool/u/0/) to test results

### Discussion / Questions / self-guided exploration

#### Citations(todo)
* MDeval
* Metadata Evaluation WebService
* Python packages
* Jupyter Notebooks
* JupyterHub
* ESIPhub
* [Google's recommendation for datasets using schema.org](https://developers.google.com/search/docs/data-types/dataset)
