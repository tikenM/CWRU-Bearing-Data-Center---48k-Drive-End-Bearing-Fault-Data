# CWRU-Bearing-Data-Center---48k-Drive-End-Bearing-Fault-Data
The 48k Drive End Bearing Fault Data from the Case Western Reserve University Bearing Data Center provides a comprehensive dataset designed for fault diagnosis and analysis of bearing failures in rotating machinery.

## Dataset Features:
Sampling Frequency: 48 kHz.
Fault Types: The dataset includes data from healthy bearings as well as bearings with various induced faults such as:
Inner race faults
Outer race faults
Ball faults
## Fault Sizes: Fault sizes range from 0.007 inches to 0.021 inches in diameter.
## Operating Conditions: The data has been recorded under different load conditions, including:

1 hp (full load)

2 hp

3 hp

## Sensor Placement: Vibration data is collected from accelerometers mounted on the drive end of the motor, providing high-quality time-series data for analysis.
## Data Structure:
The dataset contains time-domain vibration signals in .mat format, making it accessible for various signal processing and machine learning tasks. Each file is named according to the specific fault type and operating condition, allowing for targeted analysis. Data includes fields such as:

DE_time (Drive End Vibration Signal)
FE_time (Fan End Vibration Signal)
BA_time (Baseplate Vibration Signal)

## Applications:
This dataset is widely used in research and industrial settings for:

Fault diagnosis
Condition monitoring
Predictive maintenance
Signal processing
Machine learning model training and validation
Usage:
Researchers and engineers can use this dataset to develop and validate algorithms for bearing fault detection, classification, and prognosis. With its rich variety of operating conditions and fault types, the dataset provides an excellent testbed for investigating machine health and performance.


Reference:
https://engineering.case.edu/bearingdatacenter/welcome
