# MCAST BSc (Hons) in Software Development - Dissertation Prototype
This repository hosts the resources developed for a real-time litter detection system as part of my dissertation project at MCAST BSc (Hons) in Software Development.

Due to the large size of some files, they have been stored in a OneDrive folder. This includes the trained weights of the machine learning models, output videos demonstrating real-time litter detection, and two test footages captured with both a drone and a CCTV camera.

## OneDrive Contents

Access the OneDrive folder using the following link:

[OneDrive Folder Link](https://1drv.ms/f/s!AsEn51KpByY4huk7kfif7PlDFabDDQ?e=lIVbzL)

The folder contains:

1. **models**: The trained weights of the machine learning models. The models have been trained using three different datasets: public, custom, and mixed.

2. **output_detection**: Several output videos demonstrating real-time litter detection. These files also showcase the limitations of the current implementation.

3. **test_footage**: Two test videos are included in this directory. They are captured both from a drone and a CCTV camera, and can be used for testing the litter detection system.

## Repository Contents

```
.
├── training_logs
├── real-time_litter_detection.ipynb
```
### 1. training_logs
This folder contains all the logs related to model training. These can be useful for debugging, understanding the training process, and further improving the models.

### 2. real-time_litter_detection.ipynb
This is a Jupyter notebook file which outlines all the techniques mentioned in this study. It includes data preprocessing, model training, evaluation, and real-time litter detection.

## Usage
To use the system, run the provided Jupyter notebook. Make sure to install all required dependencies. 

Download the trained model weights and test footage from the OneDrive link and place them in a suitable directory. Ensure to change the relevant variables in the script to point to these directories.

If you wish to train the models yourself, the training logs can assist you in understanding the process and improving upon it.

