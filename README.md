# RAW Crop
This is a repository for sharing the code and reports for the DA231 MTech (Online) class project.

Our goal is to find the correlation between literacy, rainfall, groundwater quality and crop production across India.

It is intuitive that good rainfall is conducive to good production. How do the regions perform during poor rainfall in the rainy season?

We also want to cross-match with the literacy rate of the region to see if higher levels of literacy affects crop production.

The project structure is as follows:
<pre>
root
  |- code : Contains the iPython files exported from Google Colab
  |- data : Contains all the data which is used for running the code

</pre>

##Dataset

###Crop/Agriculture Dataset:
**Source**: https://www.kaggle.com/anjali21/agricultural-production-india
<br>**Size** : 2,46,091 records X 7 columns (~14MB) 
<br>**Format**: CSV file
<br>**Granularity**: States and Districts in India. Years - 2000-2014

###Water Quality Dataset:
**Quality of Groundwater, Lake/Tank Water, River Water**: https://cpcb.nic.in/nwmp-data/
<br>**Size**: ~1500 records x 18 columns * 8 years
<br>**Format**: Individual PDF for each year
<br>**Granularity**: Detailed upto individual water sources for Years 2012-2019
<br>**Challenges**: 
- PDF to json/csv conversion
- Converting location code/location information to district for correlation with other data sets

###Rainfall:
**Source**: https://www.kagxgle.com/rajanand/rainfall-in-india 
<br>**Size**: 4116 records X 19 columns
<br>**Format**: CSV file
<br>**Granularity**: States in India. Years - 1901-2015

###Literacy:
**Source**: https://www.kaggle.com/doncorleone92/govt-of-india-literacy-rate 
<br>**Size**: 36 records x 8 columns
<br>**Format**: csv
<br>**Granularity**: State level from 2001 and 2011 census

## Code

The main code is available in [RAW Crop.ipynb](https://github.com/ganesh737/iisc-da231-raw_crop/blob/master/code/RAW_Crop.ipynb)

The evaluation code is available in [RAW Crop Evaluation.ipynb](https://github.com/ganesh737/iisc-da231-raw_crop/blob/master/code/RAW_Crop_Evaluations.ipynb)

