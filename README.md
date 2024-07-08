# Converting from STanford EArthquake Dataset (STEAD) Format to Seisbench Format 

Quick Overview: Google Colab notebooks to parse STEAD data, convert STEAD formatted data to Seisbench formatted data. 

1. parse_STEAD_data.ipynb: Given a .hdf5 and .csv file pair from [STEAD](https://github.com/smousavi05/STEAD), takes a smaller subset. 
2. convert_STEAD_to_Seisbench.ipynb: Given a [STEAD](https://github.com/smousavi05/STEAD) formatted dataset, converts the data to [SeisBench](https://github.com/seisbench/seisbench) format. Creates an .hdf5 and .csv file pair. 

Possible Improvements: Use RDDs? 

