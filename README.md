# Converting from STanford EArthquake Dataset (STEAD) Format to Seisbench Format 

**Quick Overview:** Google Colab notebooks to parse STEAD data, convert STEAD formatted data to Seisbench formatted data. 

**Motivation:** To retrieve a small subset of the STEAD data, and convert to Seisbench format to use for Seisbench models.  

1. **parse_STEAD_data.ipynb**: Given a .hdf5 and .csv file pair from [STEAD](https://github.com/smousavi05/STEAD), takes a subset of the data. 
2. **convert_STEAD_to_Seisbench.ipynb**: Given a [STEAD](https://github.com/smousavi05/STEAD) formatted dataset, converts the data to [SeisBench](https://github.com/seisbench/seisbench) format. Creates an .hdf5 and .csv file pair.

Developed for UW CSE547 Project. 

------

**prase_STEAD_data.ipynb**

Creates a STEAD formatted .hdf5 and .csv file pair containing a subset of noise waveforms (STEAD chunk1) and a subset of earthquake waveforms (STEAD chunk2). 

------

**convert_STEAD_to_Seisbench.ipynb**

Converts a STEAD formatted .hdf5 and .csv file pair to a SeisBench formatted .hdf5 and .csv file pair. 

------

Possible Improvements: Use RDDs? 

