# UseGeo - UAV-based multi-sensor dataset for geospatial research

_________________________________________________________________________
### Description
<a href="https://usegeo.fbk.eu/" target=page>USEGEO</a> is an <a href="http://www.isprs.org" target=page>ISPRS</a> Scientific Initiative which aims to prepare and deliver a new and unique dataset for the rigorous assessment of image-based 3D reconstruction algorithms applied to datasets acquired with <b>UAV platforms</b>. 

USEGEO presents a new large-scale real-world set of data suitable for multiple tasks, such as monocular depth estimation, multi-view 3D reconstruction (MVS), etc. 
<p><center>
<img src="https://github.com/3DOM-FBK/NeRFBK/blob/master/pictures/Aerial/Drone.png" width=500><p>
<img src="https://github.com/3DOM-FBK/NeRFBK/blob/master/pictures/Aerial/Drone_network.png" width=500>
</center>
  
#### Flight specifications 

* Area Covered: 1100 x 650 meters
* Average flight height: 80m above ground
* GSD (Ground Sampling Distance - image resolution in object space): approx. 2 cm
* Image overlap: 80% (forward) - 60% (side)
* LiDaR point cloud density: ca 50 points/m2

#### Provided data: Images, depths, dense point clouds
* Total number of images (and relative ground truth depths): 829 in the 3 datasets
* Image size: 7952 x 5304 px
* Provided Ground Truth depth size: 1989 × 1320 px (1/4 resized / downsampled)
* Camera poses (X0, Y0, Z0, omega [deg], phi[deg], kappa[deg]) and interior parameters (c[px], x0[px], y0[px]): provided
* LiDAR point clouds: provided
* Photogrammetric point cloud (MVS): provided

|  Dataset | Strips  |  # images |  GSD [cm] | link |
|---|---|---|---|---|
|  1 | 8  |  224 |  1.7 | <a href="https://eostore.itc.utwente.nl:5001/sharing/1gJRLdQ71">download</a>|
|  2 |  8 | 328  |  1.8|  <a href="https://eostore.itc.utwente.nl:5001/sharing/c4LlTkVjT">download</a>|
| 3  |  8 | 277  |  1.9|  <a href="https://eostore.itc.utwente.nl:5001/sharing/r4o1tdCNv">download</a>|

The links to download can be blocked by the firewall of your university/institution. If the download does not work, please try with another network (e.g. home connection).
<p>


_________________________________________________________________________
### Related publications
Nex, F., Zhang, N., Remondino, F., Farella, E. M., Qin, R., and Zhang, C., 2023: <a href="https://isprs-archives.copernicus.org/articles/XLVIII-1-W3-2023/123/2023/" target=page>BENCHMARKING THE EXTRACTION OF 3D GEOMETRY FROM UAV IMAGES WITH DEEP LEARNING METHODS</a>. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLVIII-1/W3-2023, 123–130.

F. Nex, E.K. Stathopoulou, F. Remondino, M.Y. Yang, L. Madhuanand, Y. Yogender, B. Alsadik, M. Weinmann, B. Jutzi, R. Qin, 2024: <a href="https://www.sciencedirect.com/science/article/pii/S2667393224000140">UseGeo - A UAV-based multi-sensor dataset for geospatial research</a>.  ISPRS Open Journal of Photogrammetry and Remote Sensing, Vol. 13, 100070

M. Hermann, M. Weinmann, F. Nex, E.K. Stathopoulou, F. Remondino, B. Jutzi, B. Ruf, 2024: <a href="https://doi.org/10.1016/j.ophoto.2024.100065" target=page>Depth estimation and 3D reconstruction from UAV-borne imagery: Evaluation on the UseGeo dataset</a>. ISPRS Open Journal of Photogrammetry and Remote Sensing, 100065.

_________________________________________________________________________
### Related repository
Depth estimation and 3D model reconstruction from aerial imagery: <a href="https://github.com/UseGeoEvaluation/DepthEstimationAnd3DReconstruction">https://github.com/UseGeoEvaluation/DepthEstimationAnd3DReconstruction</a>

_________________________________________________________________________
### Credits
This dataset is publicly available for research purposes.
If you use this dataset for your research, please cite the ISPRS Scientific Initiative USEGEO - <a href="https://usegeo.fbk.eu" target=page>https://usegeo.fbk.eu</a>

_________________________________________________________________________
### License
The data provided here is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
