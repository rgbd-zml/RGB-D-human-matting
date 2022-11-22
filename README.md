# RGB-D Human Matting Project
## HDM-2K Dataset
### Introduction
<p align="justify">To support the research on the deep learning-based RGB-D human matting, a new RGB-D human matting dataset (HDM-2K) is established in this project. The HDM-2K dataset is comprised of <strong>2,270 real-world human images</strong> from various scenes, <strong>helpful depth maps</strong>, and manually annotated alpha mattes. The RGB-D images in HDM-2K are grouped into 27 scene subsets according to salient background objects and colors, including green plant, poster, bookcase, brown wall, etc. Meanwhile, the images are captured under different lighting conditions, which include strong light, normal light, and low light. Some examples are shown as below.
 
 <p align="center">
	<img src="https://github.com/rgbd-zml/RGB-D-human-matting/blob/main/demo/dataset/fig2.jpg"  width="760" height="800">
	<p align="center">
		<em>Fig. 1. Some examples from the HDM-2K dataset.</em>
	</p>
</p>
<br/>

 ### Benchmark Tracks
 <p align="justify">Based on HDM-2K, two benchmark tracks, HDM-2K-CTrack and HDM-2K-FTrack, are set up and equipped with two dataset partitions. Similar to the most common matting datasets, the dataset partition for <a href="#HDM-2k-CTrack"><strong>HDM-2k-CTrack</strong></a> is set without overlap between both the foreground human and background scene in the training and the test sets. As a result, the training set contains 1,897 RGB-D images and the test set contains the remaining 373 RGB-D images for HDM-2K-CTrack. The detailed distribution of light conditions and scenes of the training and test sets for HDM-2K-CTrack is shown in Fig. 2. There are 20 scenes in the training set and 7 scenes in the test set. Meanwhile, the lighting conditions of strong light, normal light, and low light are covered in both the training and test sets.

 <p align="center">
	<img src="https://github.com/rgbd-zml/RGB-D-human-matting/blob/main/demo/dataset/HDM2KCTrack.jpg"  width="460" height="480">
	<p align="center">
		<em>Fig. 2. Distribution of light conditions and scenes of the training and test sets for HDM-2K-CTrack. LL, NL, and SL denote the low light
scene, normal light scene, and strong light scene, respectively. TR and TE denote the training set and test set, respectively.</em>
	</p>
</p>
<br/>
<p align="justify">Additionally, considering that the matting applications with fixed scenes (e.g., video conference rooms, surveillance rooms, etc) have gradually increased in recent years, HDM-2K-FTrack is set up to research fixed-scenes matting. For <a href="#HDM-2k-FTrack"><strong>HDM-2k-FTrack</strong></a>, background-shared training and test sets are provided with 1,947 RGB-D images and 323 RGB-D images, respectively. As shown in Fig. 3, in the HDM-2K-FTrack, the training set contains all 27 scenes and the test set contains 12 scenes that overlap with the training set. Similarly, both the training set and test set cover three lighting conditions By providing two benchmark tracks and dataset partition of RGB-D human matting based on HDM-2K, it is hoped that the constructed HDM-2K can desirably promote the development of matting algorithms in academic research and practical applications.
 
 <p align="center">
	<img src="https://github.com/rgbd-zml/RGB-D-human-matting/blob/main/demo/dataset/HDM2KFTrack.jpg"  width="460" height="480">
	<p align="center">
		<em>Fig. 2. Distribution of light conditions and scenes of the training and test sets for HDM-2K-FTrack. LL, NL, and SL denote the low light
scene, normal light scene, and strong light scene, respectively. TR and TE denote the training set and test set, respectively.</em>
	</p>
</p>
<br/>
  
###  Download
The dataset <a href="#HDM-2k"><strong>HDM-2K</strong></a> can now be openly accessed from the links below.The dataset can only be used for research purposes. Besides, we will release the code after the paper is accepted for publication.
> | Dataset | <p>Dataset Link<br>(Baidu Netdisk)</p> | 
> | :----:| :----: | 
> |<strong>HDM-2k</strong>|[Link](https://pan.baidu.com/s/1kyRtc8VCG8cqo28-dS5yVA )(pw:rh5i)|
> 


