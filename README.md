<div align="center">
    <a href="https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence">
        <img src="./img/logo.png" alt="Intelligent Vehicle Perception Based on Inertial Sensing and Artificial Intelligence" height="250" align="center"/>
    </a>
</div>

<div align="center">

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://img.shields.io/badge/Project_Status-Active-green?style=flat-square&color=success)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square&color=success)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence)
[![GitHub](https://img.shields.io/github/license/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence?style=flat-square&color=success)](LICENSE) 

[![GitHub issues](https://img.shields.io/github/issues/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence/issues)
[![GitHub contributors](https://img.shields.io/github/contributors/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence?style=flat-square&color=success)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence/graphs/contributors/)
[![HitCount](http://hits.dwyl.io/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence/badges.svg)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence)
[![GitHub forks](https://img.shields.io/github/forks/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence/network/members)
[![GitHub stars](https://img.shields.io/github/stars/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence?style=flat-square)](https://github.com/Intelligent-Vehicle-Perception/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence/watchers)

</div>

# Intelligent Vehicle Perception Based on Inertial Sensing and Artificial Intelligence
This project aims to develop solutions for vehicular perception through inertial sensor signals and Artificial Intelligence models. Vehicular perception comprises exteroception and proprioception. Exteroception aims to understand the environment outside the vehicle, recognizing the road features on which it travels. These features include transient events in the form of anomalies and obstacles, such as potholes, cracks, speed bumps, etc.; and persistent events, such as surface type, conservation condition, and the road surface quality. On the other hand, proprioception aims to understand vehicular movements to identify their own behavior. These identifications can also be transient in the form of driving events, such as lane change, braking, skidding, aquaplaning, turning right or left; and persistent, as a safe or dangerous driving behavior profile. This situational information (perceptions) has wide applicability in Intelligent Transport Systems (ITS) such as Advanced Driver Assistance Systems (ADAS) and autonomous vehicles.

For the development of this project, we collect nine datasets using GPS, camera, inertial sensors (accelerometers and gyroscopes), magnetometer, and temperature sensor. These data were produced with contextual variations including three different vehicles, driven by three different drivers, traveling through three different environments. To recognize and classify the vehicular perception patterns, we have developed several models based on Artificial Intelligence, among Classical Machine Learning and Deep Learning approaches. Below we describe the datasets produced, models developed and the results obtained, together with published scientific papers and source-codes.

## Table of Contents
  - [Vehicular Perception Research](#vehicular-perception-research)
  - [Passive Vehicular Sensors Dataset](#passive-vehicular-sensors-dataset-pvs)
  - [Data Classes](#data-classes)
  - [Best Models](#best-models)
  - [Aplications](#aplications)
  - [How To Cite](#how-to-cite)
  - [License](#license)

## Vehicular Perception Research

The project is active and we are currently developing new models for new perception pattern recognition. Below are described the research progress, in chronological order of research development. At the [Research Gate](https://www.researchgate.net/project/Intelligent-Vehicle-Perception-Based-on-Inertial-Sensing-and-Artificial-Intelligence) you can also find the published scientific papers and request a full text for free.

> #### [Vehicular Perception Based on Inertial Sensing: a Systematic Review](Vehicular%20Perception%20Based%20on%20Inertial%20Sensing%20-%20a%20Systematic%20Review/Vehicular-Perception-Based-on-Inertial-Sensing-A-Systematic-Review.md)
>
> In this paper, we describe the state-of-the-art vehicle perception produced through inertial sensors and Artificial Intelligence techniques. Through a literature review, we compiled the data extracted from the selected studies and described each paper in detail and chronological order of publication.
> **[Access here](Vehicular%20Perception%20Based%20on%20Inertial%20Sensing%20-%20a%20Systematic%20Review/Vehicular-Perception-Based-on-Inertial-Sensing-A-Systematic-Review.md)**

> #### [Vehicular Perception Based on Inertial Sensing: A Structured Mapping of Approaches and Methods](Vehicular%20Perception%20Based%20on%20Inertial%20Sensing%20-%20A%20Structured%20Mapping%20of%20Approaches%20and%20Methods/Vehicular-Perception-Based-on-Inertial-Sensing-A-Structured-Mapping-of-Approaches-and-Methods.md)
>
> In this paper, we present a structured literature mapping of the state-of-the-art vehicle perception produced through inertial sensors and Artificial Intelligence techniques. We describe a structured, approach, and technologies-oriented panorama of this field.
> **[Access here](Vehicular%20Perception%20Based%20on%20Inertial%20Sensing%20-%20A%20Structured%20Mapping%20of%20Approaches%20and%20Methods/Vehicular-Perception-Based-on-Inertial-Sensing-A-Structured-Mapping-of-Approaches-and-Methods.md)**

> #### [Road Surface Type Classification Based on Inertial Sensors and Machine Learning: A Comparison Between Classical and Deep Machine Learning Approaches For Multi-Contextual Real-world Scenarios](https://github.com/Intelligent-Vehicle-Perception/Road-Surface-Type-Classification-1)
> In this research, we developed models for the road surface type classification, classifying between segments of dirt, cobblestone, and asphalt roads. We applied classical techniques of K-Means Clustering (KMC), Support Vector Machine (SVM), and K-Nearest Neighbors (KNN); and Deep Learning techniques based on Convolutional Neural Network (CNN), Long Short-Term Memory Network (LSTM), and hybrid LSTM-CNN. We analyzed in the time domain the data collected near and below the suspension, in addition to the impact of the data window size. We also evaluate the generability of model learning for unknown contexts, such as an unknown car, driver, or environment.
> **[Access here](https://github.com/Intelligent-Vehicle-Perception/Road-Surface-Type-Classification-1)**

> #### [Multi-Contextual and Multi-Aspect Analysis for Road Surface Type Classification Through Inertial Sensors and Deep Learning](https://github.com/Intelligent-Vehicle-Perception/Road-Surface-Type-Classification-2)
> In this research, we developed models for the road surface type classification, classifying between segments of dirt, cobblestone, and asphalt roads. We applied Deep Learning techniques based on Convolutional Neural Network (CNN), Gated Recurrent Unit (GRU), and Long Short-Term Memory Network (LSTM). We analyzed various aspects, such as the influence of the vehicle data collection placement, the analysis domain, the model input features, and the data window size. We also evaluate the generability of model learning for unknown contexts, such as an unknown car, driver, or environment.
> **[Access here](https://github.com/Intelligent-Vehicle-Perception/Road-Surface-Type-Classification-2)** 

> #### [Speed Bump Detection Through Inertial Sensors and Deep Learning in a Multi-Contextual Analysis](https://github.com/Intelligent-Vehicle-Perception/Speed-Bump-Detection)
> In this research, we developed models for the speed bump detection in segments of cobblestone and asphalt pavements. We applied Deep Learning techniques based on Convolutional Neural Network (CNN), Gated Recurrent Unit (GRU), Long Short-Term Memory Network (LSTM), Convolutional Neural Network Long Short-Term Memory (CNN-LSTM), and Convolutional Long Short-Term Memory (ConvLSTM). We analyzed some aspects, such as the influence of the vehicle data collection placement and the data window size. We also evaluate the generability of model learning for unknown contexts, such as an unknown car, driver, or environment.
> **[Access here](https://github.com/Intelligent-Vehicle-Perception/Speed-Bump-Detection)** 

## Passive Vehicular Sensors Dataset (PVS)

The nine datasets collected are available for download at [Kaggle](https://www.kaggle.com/jefmenegazzo/datasets) and [Arquivos UFSC](https://arquivos.ufsc.br/d/55ee83c2c9d647eaa252/?p=/&mode=grid). To collect and preprocess the raw data that resulted in the PVS datasets, the following projects were used:

- [MPU-9250 Sensors Data Collect](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-Sensors-Data-Collect)
    - Source-code used to manipulate the sensors in the data collection.

- [MPU-9250 and GPS Raw Data Pre-Processing](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-and-GPS-Raw-Data-Pre-Processing)
    - Source-code used for initial adjustments to inertial sensor raw data, such as combining with GPS data and creating data class labels.

- [MPU-9250 Data Plot Video Creator](https://github.com/Intelligent-Vehicle-Perception/MPU-9250-Data-Plot-Video-Creator/)
    - Source-code to create videos with data plot of speed and signals from inertial sensors.

For data collection, we use several passive approach sensors, detailed in the following table:

|      Hardware     |     Sensor    |                   Data                  | Sampling Rate |
|:-----------------:|:-------------:|:---------------------------------------:|:-------------:|
| HP Webcam HD-4110 | Camera        | 720p Video                              |     30 Hz     |
| Xiaomi Mi 8       | GPS           | Speed in m/s, latitude, longitude, etc. |      1 Hz     |
| MPU-9250          | Accelerometer | 3-axis acceleration in m/s²             |     100 Hz    |
| MPU-9250          | Gyroscope     | 3-axis rotation rate in deg/s           |     100 Hz    |
| MPU-9250          | Magnetometer  | 3-axis ambient geomagnetic field in µT  |     100 Hz    |
| MPU-9250          | Temperature   | Sensor temperature in ◦C                |     100 Hz    |

All the hardware equipment was attached to the vehicle as shown in the next figure. The camera was placed on the outside car roof (1), and the GPS receiver was placed internally on the dashboard (2). Two networks with MPU-9250 modules were distributed in the vehicle to get data coming from different points. Thus, each end of the front axle (right and left side) received one of the sensor networks, where a module was attached to the control arm (4), located below and near to the vehicle’s suspension system; another module was placed above and near the suspension system, attached to the body immediately above the tire (3); and a third module was attached to the vehicle’s dashboard  (2), inside the cabin.

<div align="center">
    <img src="./img/sensor_network.png" alt="Sensor Hardware Network Placement" align="center"/>
</div>

The data were produced in three different vehicles, with three different drivers, in three different environments in which there are three different surface types, in addition to variations in conservation state and presence of obstacles and anomalies, such as speed bumps and potholes. The following table details the data collection contexts.

| DataSet |       Vehicle      |  Driver  |  Scenario  | Distance |
|:-------:|:------------------:|:--------:|:----------:|:--------:|
| PVS 1   | Volkswagen Saveiro | Driver 1 | Scenario 1 | 13.81 km |
| PVS 2   | Volkswagen Saveiro | Driver 1 | Scenario 2 | 11.62 km |
| PVS 3   | Volkswagen Saveiro | Driver 1 | Scenario 3 | 10.72 km |
| PVS 4   | Fiat Bravo         | Driver 2 | Scenario 1 | 13.81 km |
| PVS 5   | Fiat Bravo         | Driver 2 | Scenario 2 | 11.63 km |
| PVS 6   | Fiat Bravo         | Driver 2 | Scenario 3 | 10.73 km |
| PVS 7   | Fiat Palio         | Driver 3 | Scenario 1 | 13.78 km |
| PVS 8   | Fiat Palio         | Driver 3 | Scenario 2 | 11.63 km |
| PVS 9   | Fiat Palio         | Driver 3 | Scenario 3 | 10.74 km |

Each dataset consists of the following files:

| File                       | Description                                                                                                            |
|----------------------------|------------------------------------------------------------------------------------------------------------------------|
| dataset_gps.csv            | GPS data, including latitude, longitude, altitude, speed, accuracy, etc.                                               |
| dataset_gps_mpu_left.csv   | Inertial sensor data on the left side of the vehicle, combined with GPS data.                                          |
| dataset_gps_mpu_right.csv  | Inertial sensor data on the right side of the vehicle, combined with GPS data.                                         |
| dataset_labels.csv         | Data classes for each sample data in the dataset (for both sides).                                                |
| dataset_mpu_left.csv       | Inertial sensor data on the left side of the vehicle.                                                                  |
| dataset_mpu_right.csv      | Inertial sensor data on the right side of the vehicle.                                                                 |
| dataset_settings_left.csv  | Settings of the inertial sensors placed on the left side of the vehicle. Includes measurement range, resolution, etc.  |
| dataset_settings_right.csv | Settings of the inertial sensors placed on the right side of the vehicle. Includes measurement range, resolution, etc. |
| map.html                   | Map of the data collection location.                                                                                   |
| video_dataset_left.mp4     | Video with data plotted from inertial sensors and speed, sampled on the left side of the vehicle.                      |
| video_dataset_right.mp4    | Video with data plotted from inertial sensors and speed, sampled on the right side of the vehicle.                     |
| video_environment.mp4      | External environment video.                                                                                            |
| video_environment_dataset_left.mp4      | Videos side by side from video_environment.mp4 and video_dataset_left.mp4                                 |
| video_environment_dataset_right.mp4     | Videos side by side from video_environment.mp4 and video_dataset_ight.mp4                                 |

You can find the playlist of videos side by side on [Youtube](https://www.youtube.com/playlist?list=PLTG6ZC9RiP1dxQk5Wf6UiNxwRyGv-keY7).

<div align="center">
    <a href="https://www.youtube.com/playlist?list=PLTG6ZC9RiP1dxQk5Wf6UiNxwRyGv-keY7">
        <img src="./img/video.png" alt="Play PVS Playlist" align="center"/>
    </a>
</div>

## Data Classes

The data classes are available in the **dataset_labels.csv** file were built in one-hot-encoded form. We are currently developing new data class labels. The following are already available:

- **Road Surface Type Labels**

|    Description   |    Label    |
|:----------------:|:-----------:|
| Dirt Road        | dirt_road        |
| Cobblestone Road | cobblestone_road |
| Asphalt Road     | asphalt_road     |

<br>

|    Description   |    Label    |
|:----------------:|:-----------:|
| Paved Road       | paved_road   |
| Unpaved Road     | unpaved_road |

<br>

<div align="center">
    <img src="./img/road_surface_types.png" alt="Road Surface Type" align="center"/>
</div>

- **Speed Bump**

|    Description   |    Label    |
|:----------------:|:-----------:|
| No Speed Bump        | no_speed_bump        |
| Speed Bump in Asphalt   | speed_bump_asphalt   |
| Speed Bump in Cobblestone | speed_bump_cobblestone |

<br>

<div align="center">
    <img src="./img/speed_bump_types.png" alt="Speed Bump" align="center"/>
</div>

## Best Models

Soon we will provide the best models available in a simplified way, ready for end-use in any application.

## Aplications

The recognized and classified patterns of vehicular perception have wide applicability. Below are some applications that can use this information:

- Autonomous Vehicles
- Advanced Vehicle Control Systems
- Advanced Driver Assistance Systems
- Advanced Public Transport Management Systems
- Advanced Traffic Management Systems
- Advanced Traveler Information Systems
- Vehicle Black Box
- Evaluation Software for Control and Quality Assurance in Civil Engineering
- Mobile Crowdsensing Applications

## How To Cite

To cite PVS Datasets, use the reference below:

```
J. Menegazzo and A. von Wangenheim, "Multi-Contextual and Multi-Aspect Analysis for Road Surface Type Classification Through Inertial Sensors and Deep Learning," 2020 X Brazilian Symposium on Computing Systems Engineering (SBESC), Florianopolis, 2020, pp. 1-8, doi: 10.1109/SBESC51047.2020.9277846.
```

```bibtex
@INPROCEEDINGS{9277846,
  author={J. {Menegazzo} and A. {von Wangenheim}},
  booktitle={2020 X Brazilian Symposium on Computing Systems Engineering (SBESC)}, 
  title={Multi-Contextual and Multi-Aspect Analysis for Road Surface Type Classification Through Inertial Sensors and Deep Learning}, 
  year={2020},
  volume={},
  number={},
  pages={1-8},
  doi={10.1109/SBESC51047.2020.9277846}
}
```

## License

This project is under MIT License (MIT). Please see [License File](LICENSE) for more information.