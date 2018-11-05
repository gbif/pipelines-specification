# Data pipelines <small>for biodiversity data</small>

## Process biodiversity data 

Data pipelines provides components to integrate, structure, interpret and transform biodiversity data.
Built for extensibility, portability and high performance, data pipelines powers services such as [GBIF.org][1].

[![Material for MkDocs](images/primary.png)](images/primary.png)

  [1]: https://www.gbif.org/occurrence/search

## Features

Some of the high-level capabilities and objectives of Data pipelines include:

- Support a variety of input formats ([Darwin Core][1], [ABCD][2], CSV files, Excel files, Shapefiles etc) with easy opportunity to include new connectors
- Support batch (e.g. a project CSV) and streaming inout (e.g. append-only tracking data)  
- Align data to a standardized vocabularies, supporting multilingual data labelling
- Apply quality controls to flag errors, detect outliers and apply statements about the suitability of the data for a variety of uses (also known as _fitness for use_ indicators)
- Enrich data by:
    - cross referencing with geospatial gazetteers for political boundaries (e.g. [GADM.org][3], [EEZ][4], protected areas) and biogegraphic regions, landuse categorisation and environmental surfaces
    - organizating to multiple taxonomic classifications including the [GBIF Backbone taxonomy][5], [Catalogue of Life][6] and national legislative taxonomies such as [ITIS][11]    
- Allow consumers to easily understand the data preparation and enrichment process that has been applied (i.e. preserve and document data provenance).
- Provide clear documentation for all data transformations    
- Support multiple runtime environments such as [Apache Spark][7], [Google Dataflow][8], [Amazon EMR][9] or local machine
- Ensure pipelines can be deployed in a high throughput environment. [GBIF.org][10] target the processing and indexing into Elasticsearch of 1 Billion records in under 12 hours 
 
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
