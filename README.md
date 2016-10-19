# SensorFusion

This is the sample app showing sensor fusion from Gyroscope and Accelerometer

Gyroscope suffers from drift, it is not stable over long-term
Accelerometer data is not stable over short-term,

so here apply high-pass filter on Gyro; low-pass filter on Accl
