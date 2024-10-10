# Real-Time-Human-Activity-Recognition-Using-Inertial-Sensors

Description of Experiment
We conducted experiments with 30 volunteers aged 19 to 48. Each participant performed six activities: WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, and LAYING down, while wearing a Samsung Galaxy S II smartphone on their waist. The phone's built-in accelerometer and gyroscope collected data on linear acceleration and angular velocity at a rate of 50Hz. We also recorded videos of the activities to help label the data later. The dataset was divided into two parts: 70% of the volunteers were used for training the model, and 30% for testing.

Before analysis, we pre-processed the sensor data by applying noise filters. We then split the data into sliding windows of 2.56 seconds with 50% overlap, resulting in 128 readings per window. To separate body movement from gravity effects, we used a Butterworth low-pass filter with a cutoff frequency of 0.3 Hz. From each window, we calculated various features based on the time and frequency of the signals.
