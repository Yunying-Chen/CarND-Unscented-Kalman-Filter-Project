# Unscented Kalman Filter Project 

In this project utilize an Unscented Kalman Filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. 

## Files                           
* main.cpp - reads in data, calls a function to run the Unscented Kalman filter, calls a function to calculate RMSE                  
* ukf.cpp - initializes the Unscented Kalman filter, calls the predict and update function, defines the predict and update functions      
* tools.cpp- function to calculate RMSE

## Other Important Dependencies
* cmake >= 3.5
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
* gcc/g++ >= 5.4

## Result
With Dataset 1 the result is as follows:                   
RMSE = [0.0692 0.0829 0.3333 0.2345]                       
![Image text](https://github.com/Yunying-Chen/CarND-Unscented-Kalman-Filter-Project/blob/master/img/data1.png)     







With Dataset 2 the result is as follows:                   
RMSE = [0.0780 0.0681 0.7265 0.2814]                       
![Image text](https://github.com/Yunying-Chen/CarND-Unscented-Kalman-Filter-Project/blob/master/img/data2.png)     






