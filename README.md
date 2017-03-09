# CSV exports of the Getty Photo Archive

### Table of Contents

* [Introduction](#introduction)
* [Repository structure](#repository-structure)
* [Usage guidelines](#usage-guidelines)
  * [License](#license)
  * [Attribution](#attribution)
  * [Data Integrity/DISCLAIMER OF WARRANTIES](#data-integritydisclaimer-of-warranties)
  * [Trademark Policy/No Endorsement](#trademark-policyno-endorsement)
  * [Pull Requests, Issues, and Bug Reports](#pull-requests-issues-and-bug-reports)
* [Acknowledgment](#acknowledgment)

## Introduction

The J. Paul Getty Trust (the "Trust"), operating as the Getty Research Institute, intends to embark on a project to digitize, and redesign the current infrastructure of the [Getty Photo Archive](http://www.getty.edu/research/tools/photo/index.html), in order to republish the description of the archive as Linked Open Data (LOD) as part of the [Pharos Project](http://pharosartresearch.org/). This project will take some time to complete, and the data provided in this repository is the input to that process.

**These data will eventually be superseded by the Linked Open Data release.**

While this repository will remain public after the LOD release, the datasets it contains will not then be maintained in any way.

## Repository structure

The Photo Archive is comprised of several distinct databases. The quantity and scope of the material that is available in each database varies.

Each database is provided in one or more CSV (comma separated values) files in its own directory. Each of these directories contains a database-specific README file documenting the sources from which each dataset has been derived, as well as a data dictionary with a description of each table column. 

### Sample Dataset

The current dataset is a [sample](sample/) of less than a thousand photographs of artworks for which Peter Paul Rubens was an attributed artist.  

## Usage guidelines

### License

The Trust makes these datasets available under the least restrictive open license possible; however, **please check the README documentation specific to each dataset, as rights may vary between datasets**.
If you create a derivative dataset, we ask that you consider releasing the derivative under the least restrictive license possible as well.

### Attribution

We respectfully ask that you acknowledge the Getty Research Institute® as sources wherever possible, in order to preserve links to the datasets. By providing acknowledgment or citation, you enable others to verify, replicate, and further explore your presentation and interpretation of our data.

Suggested citation:

>Getty Research Institute®, _CSV exports of the Getty Photo Archive_ (DATE HERE, 2017), <https://github.com/gettyopendata/photoarchive-csv/releases/tag/v1>

Note that a new tagged release will be made whenever any of these datasets are added or updated. A list of these tagged releases can be seen here: <https://github.com/gettyopendata/photoarchive-csv/releases>

### Data Integrity/DISCLAIMER OF WARRANTIES

These data are provided for the purposes of exploration, education, experimentation, and fun, but are to be used at your own risk. 
The Trust shall not be held liable for any improper or incorrect use of the information contained herein and assumes no responsibility for anyone's use of the information.

The databases are regularly updated by editors to reflect our latest research. Updates to the datasets in this repository are not scheduled but may occur. You are advised to use, or update to, the most current version of these datasets for best accuracy.

**No warranty, express or implied, is made regarding accuracy, adequacy, completeness, legality, reliability or usefulness of any information provided.
The Trust provides this information on an "AS IS" basis.
All warranties of any kind, express or implied, including but not limited to the IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, freedom from contamination by computer viruses and non-infringement of proprietary rights ARE DISCLAIMED to the maximum extent permitted by law.**

### Trademark Policy/No Endorsement

Use of these datasets does not grant or imply the Trust's approval, commission, or support of your work. 
The names "Getty®, "The Getty®" and "The Getty Research Institute®" are registered trademarks of the Trust, and are not part of the datasets. 
If you transform or modify a dataset, you must clearly distinguish the resulting work as having been modified from this dataset and may not imply any endorsement by the Trust.

### Pull Requests, Issues, and Bug Reports

Please note that, as these data are exported from our internal databases, we cannot accept pull requests for the data in this repository. 
However, during the period when this repository is actively maintained (before the LOD release), we will review issues and pull requests for documentation or other non-data content issues posted here.

## Acknowledgment

This repository and README are largely inspired by the detailed work done by the [Carnegie Museum of Art](https://github.com/cmoa/collection) on their own collections data repository.
We thank them for providing an excellent model!
