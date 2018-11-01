# Data pipelines <small>for biodiversity data</small>

## Process biodiversity data 

Data pipelines provides components to integrate, interpret and transform biodiversity data.
Built for extensibility, portability and high performance, data pipelines powers services such as [GBIF.org][1].

[![Material for MkDocs](images/primary.png)](images/primary.png)

  [1]: https://www.gbif.org/occurrence/search

## Features

Some of the high-level capabilities and objectives of Data pipelines include:

- Enable integration of a variety of input formats ([Darwin Core][1], [ABCD][2] etc) from batch and streaming (e.g. species tracking) datasources.
- Normalize data to a standardised format using reference multilingual vocabularies
- Apply data quality controls to flag errors, detect outliers and apply statements about the fitness for use of the data 
- Enrich data by:
    - cross referencing with geospatial gazetteers for political boundaries (e.g. [GADM.org][3],[EEZ][4], protected areas) and biogegraphic regions, landuse categorisation and environmental surfaces
    - organizating to multiple taxonomic classifications including the [GBIF Backbone taxonomy][5], [Catalogue of Life][6] and national legislative taxonomies such as [ITIS][11]    
- Maintain data provenance to ensure transparency in all data handling, and provide clear documentation    
- Support multiple runtime environments (portability) such as [Apache Spark][7], [Google Dataflow][8], [Amazon EMR][9] or local machine
- Ensure high throughput processing is possible: [GBIF.org][10] target processing of 1 Billion records in 12 hours
 
   [1]: https://www.tdwg.org/standards/dwc/
   [2]: https://www.tdwg.org/standards/abcd/
   [3]: https://gadm.org/
   [4]: http://vliz.be/vmdcdata/marbound/ 
   [5]: https://www.gbif.org/dataset/d7dddbf4-2cf0-4f39-9b2a-bb099caae36c
   [6]: http://www.catalogueoflife.org/
   [7]: https://spark.apache.org/ 
   [8]: https://cloud.google.com/dataflow/
   [9]: https://aws.amazon.com/emr/ 
   [10]: https://www.gbif.org
   [11]: https://www.itis.gov/
