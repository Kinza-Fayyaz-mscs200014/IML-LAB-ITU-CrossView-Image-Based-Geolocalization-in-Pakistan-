# Cross View Image Based Geolocalization in Pakistan
<b>Research Topic:</b> Cross View Image Based Geolocalization in Pakistan.<br>
<b>Dataset</b> available <a href = "https://drive.google.com/drive/folders/1LXXdwoJCEbaLp40OCQC5P3CiUtX2xrmg?usp=share_link" target="_blank">here</a><br>
<b>Dataset Name </b>Cross View Pakistan(CV PAK) Dataset<br>

In this research, we working on cross-view image-based geolocation that pertains to matching two images from diverse perspectives - one from a panorama viewpoint and the other from a satellite or aerial viewpoint. It is a process in which we compare a ground image that is a 360-degree panoramic image with their corresponding GPS-tagged satellite image to determine their location. There is a huge similarity gap between these two views. Recently, research has achieved extortionate accuracy on existing datasets such as CV USA, CV ACT, and VIGOR. Previous datasets do not cover the dataset of developing countries. It mostly covers the dataset of developed countries. Street views(Panoramas) are in high resolution which is not available in many countries in the world. There are around 55 countries that are not covering Google street view according to the given below source. Source: <a href = "https://en.wikipedia.org/wiki/Google_Street_View" target="_blank">here</a><br> Different datasets are required to cover almost the entire world, including Asia, Africa,India, Malaysia and Europe. Existing datasets cover countries like America and Australia. Everyone worked on the existing datasets and applied their method to it and achieved high accuracy on it. Existing datasets do not accurately reflect real-world environments as they lack images with dense crowds of people and objects and are comparatively simple to work with. By Filling the gap in the existing dataset we proposed a new large and scalable dataset in Pakistan that’s name cross view Pakistan (CV PAK). This dataset is very diverse and includes various images covering both rural and urban areas. Our contribution to this research is that we proposed a new dataset cross-view Pakistan (CV PAK) that is covering the cross-view images in Pakistan. Then we implement five previous methods on this dataset to compute the results. 

<br>
<img src="sample image.jpg">

# Dataset Details
We proposed a new dataset cross-view Pakistan (CV PAK) that includes Pakistan's 360° angled Panoramas and satellite images. Our dataset includes the 4 provinces and 40 cities of Pakistan. The cities name that includes in our dataset are Lahore, Multan, Dera-ismail-khan, Mian-wali, Murree, Faisalabad, Rahim-yar-khan, Gujranwala, Layyah, Gujrat, Jhang, Rawalpindi, Sahiwal, Sargodha, Sialkot, Mandi-bahauddin, Jhelum, Attock, Islamabad, Karachi, Shikarpur, Hyderabad, Mirpur Khas, Sukkur, Nawabshah, Quetta, Gwadar, Sibi, Chaman, Turbat, Mastung, Peshawar, Abbottabad, lakki-marwat, Mansehra, Sawat, Mardan, Nowshera, Malakand and Muzaffarabad. We are using the pro version of “Street View Download 360” Application for collecting the 360° angled panoramic Images and for downloading high-resolution satellite images we used the "SAS Planet" application. There is almost 40 days = 1440 hours = 86400 minutes = almost 2 months required for collecting the dataset.

### Dataset Link
You can download our dataset from <a href="https://drive.google.com/drive/folders/1LXXdwoJCEbaLp40OCQC5P3CiUtX2xrmg?usp=share_link">here</a>. <br>
Total size of the dataset is 23GB. For ease in downloading, we have put it in smaller divisions that you will see in the link.

### Dataset Contents
In the above link you should find M5-Malaria Dataset folder and in the folder you will find three subfolders:
<ul>
  <li>Images</li>
  <li>Splits</li>
  <li>Annotations</li>
 </ul>
 You will find complete details in <a href="https://github.com/intelligentMachines-ITU/LowCostMalariaDetection_CVPR_2022/blob/main/M5-Malaria_Dataset_Contents.txt">this file</a>.

### Visualizing the Annotations
In order to visualize the annotations, you can pick some sample images and their annotations from the dataset and run the file <a href = "https://github.com/intelligentMachines-ITU/LowCostMalariaDetection_CVPR_2022/blob/main/Plot_Annotationss.ipynb">Plot_Annotationss.ipynb</a> on them. Or you can run <a href="https://github.com/intelligentMachines-ITU/LowCostMalariaDetection_CVPR_2022/blob/main/plot_annotationss.py">plot_annotationss.py</a>.
You should follow the following steps:
<br>To run the visualization code, you need the following libraries:
<ul><li>lxml</li>
  <li>cv2 (opencv-python)</li>
  </ul>
<ol>
  <b><li>Create Folders</li></b>
  Create a folder for annotations, one for images and one for the results.
  <b><li>Choose sample images for visualization</li></b>
    You should pick some images from the dataset and their corresponding annotations. Remember that the images and their annotations have the same names with different extensions. Put the images and annotations in the folders that you just created.
  <b><li>Update the paths</li></b>
  Update the paths in the "Plot_Annotationss.ipynb" file. You will find the path variables in the third cell of the notebook. Or if you are working with the .py version, plot_annotationss.py, you will find the path variables on line number 72-74.
  <b><li>Run All the Cells</li></b></ol>
  Just run all the cells and you will find the resultant images with plotted color coded boundary boxes in the results folder that you created. In case the code runs well and you don't see your resultant images in the results folder, check the paths variable again.
   
## Contact
In case of any question regarding dataset, please email us:
waqas.sultani@itu.edu.pk,
mscs20014@itu.edu.pk

