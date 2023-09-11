# Fitness Classification Model Project

This project focuses on the process of transforming RAW video data into a fitness classification model. The steps involve segmenting the video, extracting joint positions using the MediaPipe library, converting these positions into angular data, and analyzing the periodicity of the time series data. This analysis is then used to create a model for classifying different exercises.

## 1. **DataSampling.ipynb**
- **Functionality**: 
  - Segments the RAW video into samples of 3-second durations.

## 2. **DataProcessing.ipynb**
- **Functionality**: 
  - Processes video data samples using the MediaPipe library.
  - Transforms the joint position data from the videos into angular data.
  - Conducts time series analysis to study the periodicity in the angular data.

## 3. **FitnessClassificationModel.ipynb**
- **Functionality**: 
  - Creates a fitness classification model based on the results of the time series analysis.

---

## Instructions for Use:
1. Run `DataSampling.ipynb` to segment the RAW videos into 3-second samples.
2. Execute `DataProcessing.ipynb` to process the segmented video samples, convert joint positions into angular data, and analyze the periodicity.
3. Finally, execute `FitnessClassificationModel.ipynb` to generate a model that classifies different exercises based on the analyzed data.

---