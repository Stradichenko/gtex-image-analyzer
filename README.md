# gtex-image-analyzer
The objective of this project is to provide an ML method for histopathological image analysis.
To develop a framework to do histopathology image analysis and gene expression trajectory inference during aging using general GTEx (and not dGTEx). 
This approach, however, should be applicable once the dGTEx data is available. The GTEx data is much larger than the dGTEx but it goes from 18-70 year old. 
This project is part of a much larger endeavour to evaluate changes in gene expression through age.



## Introduction


### GTEx Images
SVS (Scalable Vector Graphics) images refer to a file format used in digital pathology for storing and viewing whole-slide images (WSIs). Whole-slide images are high-resolution digital representations of complete tissue slides that are typically scanned using specialized slide scanners. These images capture the entire slide at various magnification levels, allowing pathologists and researchers to examine the tissue samples in detail.

The SVS  file format is commonly used to store and distribute whole-slide images due to its ability to handle large file sizes and support multiple resolution levels. SVS files are based on the XML-based SVG format and can contain image data, metadata, and annotations associated with the slide.

## On going process
To possible do a better job at training model would be to create first a model that is able to estimate what is tissue and what is just _milieu extérieur_. When doing future training this could save time and costs.

Ongoing questions are:
- how can large chunk of data be accessed for training? 
-   Options are to either download as much of the database as possible or do 
-   data streaming.
- What are other good ML approaches to Image analysis besides CNN?


## License
