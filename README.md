# Data_Generation_for_Pose_estimation
6D pose estimation refers to estimating the poses of objects i.e. their rotation and translation. It is a classic computer vision problem and is of great significance in the fields of augmented reality, robotic, etc. Various algorithms have been formulated in order to tackle the problem of pose estimation and there has been significant improvement in the field in recent times. 

We can face various problems during pose estimationa and developing a dataset with various criteria can help us tackle the uncertainity associated with various algorithms and how well they performs in a natural setting. In this repo I develop criteria and apply them in the rendering process and finally come up with our own dataset with its own unique parameters. The renderer used in this project is called BlenderProc.

# BlenderProc
BlenderProc was chosen as the renderer because of the following reasons:
1. BlenderProc is a blender pipeline with extensive documentation.
2. It is easy to understand and implement
3. It has a well maintained repository.

# Criteria
The following parameters were used in the rendering process:

•	Lighting conditions/Illumination

•	Occlusion/ extent of clutter 

•	Texture/ Surface reflectance properties 

•	Truncation 

•	Symmetry

•	Complexity of Scene 

•	Complexity of Objects e.g. shape, size, compactness etc. 

•	Background Characteristics: Not too rough or having extensive features to avoid wrong classifications

•	Camera pose sampling

•	Errors/anomalies in the objects

•	Geometric object features

# Citation
Denninger, M., Sundermeyer, M., Winkelbauer, D., Olefir, D., Hodan, T., Zidan, Y., Elbadrawy, M., Knauer, M., Katam, H., Lodhi, A., "BlenderProc: Reducing the Reality Gap with Photorealistic Rendering", RSS 2020.
