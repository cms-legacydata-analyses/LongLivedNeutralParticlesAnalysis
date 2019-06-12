# DisplacedVertexAnalysis
## Description
## Requirements
This analysis example is met to be run within  [CMS VM 2011](http://opendata.cern.ch/record/252 "CMS VM Image") and utilizes CMSSW_5_3_32.

## How to run
### Setup
Within a terminal:
1. Create a CMSSW_5_3_32 environment, change directory into `CMSSW_5_3_32/src/` and clone this repository
```
cmsrel CMSSW_5_3_32
cd CMSSW_5_3_32
git clone git@github.com:cms-legacydata-analyses/DisplacedVertexAnalysis.git
```
Next set up CMS environment and compile the code

```
cmsenv
scram b
```
The analysis code is now ready to be run
### Running analysis

