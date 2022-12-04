# dkNET-Repository-Finder-Data
Repository for the data behind the repository finder

## Models:

## Original Paper Model [dkNET-DRP](split-by-model/dkNET-DRP)

Model: http://trees.scicrunch.io/models/dkNET-DRP/7/?localizationName=en-US

Top Coordinate: `DataRepoCompliance`

## Repository Tagging for the dkNET tool [nih-repotag](split-by-model/nih-repotag/)

Model: http://trees.scicrunch.io/models/nih-repotag/4/?localizationName=en_US

Top Coordinate: `NIHDSP`

## Log

### Initial Work

. Splitting the .xml files in the repo according to questionnaire that created them. New files are placed in [split-by-modal](split-by-modal).
    * Problems: The following files are mentioned in the [index csv](scicrunch-raw-data/Policy_Interviews.csv), but the xml file itself is missing:
    ````
    cp: scicrunch-raw-data/6165af2cb187d.xml: No such file or directory
    cp: scicrunch-raw-data/61783f4d79d42.xml: No such file or directory
    cp: scicrunch-raw-data/618063ccbdc33.xml: No such file or directory
    cp: scicrunch-raw-data/61ae86c8d478a.xml: No such file or directory
    cp: scicrunch-raw-data/621d07ad2f91a.xml: No such file or directory
    ````
. Creating the index files.
