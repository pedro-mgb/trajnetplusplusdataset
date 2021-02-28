# Converted Data - Using Code From this repo

This folder contains data that was converted from real pedestrian trajectory datasets used by state-of-the-art methods, to the Trajnet++ format.

These datasets are already part of the total set used in the Trajnet++ benchmark ([here](https://github.com/vita-epfl/trajnetplusplusdata/releases)), however those did not have validation subsets, nor access to ground truth (test_private folders).

Since there may be some difference in parameters or criteria used to convert these datasets, they have some differences in terms of scenes and trajectories, however the differences were found to be minimal.

--------------------------------------------

2 real pedestrian datasets were converted to this format:



### ETH (BIWI Walking Pedestrians Dataset)
 
Original raw dataset available in '..\data\ewap_dataset_light.tgz'

Citation available in repo's home directory README.

Subscenes used for testing and validation:

- **biwi_hotel.ndjson** - used for training (70%) / validation (30%).

- **biwi_eth.ndjson** - used for testing (ground truth data available in test_private)



### UCY (Crowds dataset)
 
Original raw dataset available in two .rar files: '..\data\data_zara.rar' and '..\data\data_university_students.rar'

Citation available in repo's home directory README.

Subscenes used:

- **crowds_students001.ndjson**, **crowds_students003.ndjson**, **crowds_zara01.ndjson**, **crowds_zara03.ndjson** - used for training (70%) / validation (30%).

- **crowds_uni_examples.ndjson**, **crowds_zara02.ndjson** - used for testing (ground truth data available in test_private)

