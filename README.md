# Development of UAV Images from the Bonarka Area

## Project Objective
This project involves processing aerial data collected by an unmanned aerial vehicle (UAV) over the Bonarka Nature Reserve. Images, taken during favorable weather conditions in 2023, were analyzed using photometric reference points to enhance accuracy. Due to adverse weather conditions, images from other periods were not suitable for analysis. The project output includes a detailed report evaluating the accuracy of the data processing and various photogrammetric products, such as a dense point cloud, a digital surface model, and an orthophoto.

## Tools and Software
- **DJI Terra** for importing, processing, and analyzing UAV data.
- **Agisoft Metashape** for creating 3D models, elevation maps, and orthomosaics.

## Study Area and Data Collection
- **Location**: Bonarka Nature Reserve
- **Date of UAV Operation**: May 22, 2023
- **Total Images Captured**: 321
- **Photometric Points**: 4 locations within the study area

![image](https://github.com/user-attachments/assets/c9ad86c1-c8bc-4491-b127-d5da7b9d47e3)


### UAV and Equipment Information
#### UAV Details:
- **Model**: DJI Mavic 3 Enterprise
- **Flight Specs**: Maximum ascent speed: 6 m/s (Mode-N), 8 m/s (Mode-S); Maximum descent speed: 6 m/s; Maximum range: FCC - 15 km, CE - 8 km
- **Total Weight**: 915 g (including battery, memory card, and propellers)

#### GNSS Receiver Information:
- **Model**: Hi-Target V100 GNSS
- **Correction Type**: RTK (Real-Time Kinematic)
- **Coordinate System**: 2000 System Zone 7
- **Geoid Model Used**: Yes

## Workflow Overview

1. **Data Import in DJI Terra**:
   - All 321 UAV images were imported and automatically geolocated on a map based on GPS metadata.
   - Irrelevant images (e.g., from drone turns or return-to-start path) were filtered out to focus only on usable data for the analysis.

2. **Comparison of DJI Terra and Agisoft Metashape**:
   - Both software applications provide extensive aerial data processing capabilities, but DJI Terra was observed to perform better in terms of reprojection error accuracy and processing speed, particularly for aerotriangulation and model generation.
   - Our team found the DJI Terra interface to be more intuitive, leading to a more efficient and pleasant user experience.

## Results
The processed data produced several photogrammetric products:
- **Dense Point Cloud**
- **Digital Surface Model (DSM)**
- **Orthophoto Mosaic**

## Screenshots

![image](https://github.com/user-attachments/assets/9a884e61-747e-4d44-8824-644d8544804b)

![image](https://github.com/user-attachments/assets/8426abed-873b-4dbe-a4ac-14c08b58efba)

![image](https://github.com/user-attachments/assets/00cf733f-41b5-45ff-9269-6411cc8ffcf8)

![image](https://github.com/user-attachments/assets/ced94036-7117-498d-8337-a0551d767bed)

![image](https://github.com/user-attachments/assets/f471db52-0c2f-4629-8503-57935ccfcc6c)

![image](https://github.com/user-attachments/assets/f4af1e69-1432-4d29-87db-55025e39ba85)

