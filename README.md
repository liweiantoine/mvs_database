# Indoor Multiview System Datasets

## Calibrated
### 1. CMU PanopticStudio 3D PointCloud Dataset
http://domedb.perception.cs.cmu.edu/ptclouddb.html
- 10 synchronized RGB+D videos
- 3D point clouds from the 10 RGB+D videos
- 31 synchronized HD videos from other viewpoints for the same scenes
- Calibration parameters for 10 RGB+D cameras and 31 HD Cameras
- Sync table for all RGB+D and HD videos
- Optional: 480 synchronized VGA videos for the same scenes  

### 2. TUM Multiview Datasets
https://vision.in.tum.de/data/datasets/3dreconstruction
They provide multiple datasets capturing objects from various vantage points. Each entry contains an image sequence, corresponding silhouettes and full calibration parameters. 
- bird: 21 images
- beethoven: 33 images
- bunny: 36 images
- head: 33 images
- pig: 27 images  
  
  
## Non-calibrated
### 1. Tanks and Temples (large-scale)
https://www.tanksandtemples.org/download/

### 2. TUM NavVis Indoor Dataset (large-scale)
https://github.com/NavVisResearch/NavVis-Indoor-Dataset/
- More than 50,000 high-resolution images (still images, not video frames)
- Covering more than 50,000 m2 of 12 different buildings at Technical University of Munich
- Extrinsic poses for all images in a geo-referenced coordinate system  

#### Unknown: EPFL Multi-view database
https://mmspg.epfl.ch/MultiviewDatabase  

#### Ref.  
【1】 https://github.com/AIBluefisher/ComputerVisionDatasets/tree/master/3d_reconstruction  
【2】 https://github.com/sunbuny/3D-Recon_3D-DL_Datasets
