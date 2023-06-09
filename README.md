# Cross View Image Based Geo-localization in Pakistan
<b>Research Topic:</b> Cross View Image Based Geo-localization in Pakistan.<br>
<b>Dataset:</b> available <a href = "https://drive.google.com/drive/folders/1LXXdwoJCEbaLp40OCQC5P3CiUtX2xrmg?usp=share_link" target="_blank">here.</a><br>
<b>Dataset Name:</b>Cross View Pakistan(CV PAK) Dataset.<br>

In this research, we worked on cross-view image-based geolocation that pertains to matching two images from diverse perspectives - one from a panorama viewpoint and the other from a satellite or aerial viewpoint. It is a process in which we compare a ground image that is a 360-degree panoramic image with their corresponding GPS-tagged satellite image to determine their location. There is a huge similarity gap between these two views. Recently, research has achieved extortionate accuracy on existing datasets such as CV USA, CV ACT, and VIGOR. Previous datasets do not cover the dataset of developing countries. It mostly covers the dataset of developed countries. Street views(Panoramas) are in high resolution which is not available in many countries in the world. There are around 55 countries that are not covering Google street view according to the <a href = "https://en.wikipedia.org/wiki/Google_Street_View" target="_blank">source.</a><br> Different datasets are required to cover almost the entire world, including Asia, Africa, India, Malaysia, and Europe. Existing datasets cover countries like America and Australia. Everyone worked on the existing datasets and applied their method to it and achieved high accuracy on it. Existing datasets do not accurately reflect real-world environments as they lack images with dense crowds of people and objects and are comparatively simple to work with. By Filling the gap in the existing dataset we proposed a first largest and scalable geo-localized dataset in Pakistan that’s name cross view Pakistan (CV PAK). The CV PAK dataset covering the four provinces and 40 cities of Pakistan. This dataset is very diverse and includes various images covering both rural and urban areas. Our contribution to this research is that we proposed a new dataset cross-view Pakistan (CV PAK) that is covering the cross-view images in Pakistan. Then we implement five previous methods on this dataset to compute the results. 
<br>
<img src="prob.png">

# Dataset Details
We proposed a new dataset cross-view Pakistan (CV PAK) that includes Pakistan's 360° angled Panoramas and satellite images. We gathered 11,632 panoramas views and their corresponding 11,632 satellite views from Pakistan. Our dataset includes the four provinces and 40 cities of Pakistan. The cities name that includes in our dataset are Lahore, Multan, Dera-ismail-khan, Mian-wali, Murree, Faisalabad, Rahim-yar-khan, Gujranwala, Layyah, Gujrat, Jhang, Rawalpindi, Sahiwal, Sargodha, Sialkot, Mandi-bahauddin, Jhelum, Attock, Islamabad, Karachi, Shikarpur, Hyderabad, Mirpur Khas, Sukkur, Nawabshah, Quetta, Gwadar, Sibi, Chaman, Turbat, Mastung, Peshawar, Abbottabad, lakki-marwat, Mansehra, Sawat, Mardan, Nowshera, Malakand and Muzaffarabad. We are using the pro version of “Street View Download 360” Application for collecting the 360° angled panoramic Images and for downloading high-resolution satellite images we used the "SAS Planet" application. There is almost 40 days = 1440 hours = 86400 minutes = almost 2 months required for collecting the dataset. The given below shows a map of Pakistan that includes 4 provinces of Pakistan with 40 cities that we covered in our Dataset.

<br>
<img src="Map_pakistan_dataset.png">

### Dataset Link
You can download our dataset from <a href="https://drive.google.com/drive/folders/1LXXdwoJCEbaLp40OCQC5P3CiUtX2xrmg?usp=share_link">here</a>. <br>
Total size of the dataset is 20GB. 

### Dataset Contents
In the above link you should find CV PAK DATASET folder and in the folder you will find two subfolders:
<ul>
  <li>Satellite_images</li>
  <li>Panorama_images</li>
 </ul>
Satellite images includes 11,632 satellite views that are collected from 40 cities of Pakistan. Panorama images folder includes 11,632 panoramas views.

### Limitations of CV PAK Dataset
There are still many limitations present in our research. As I discussed earlier we made a large and diverse dataset cross view Pakistan CV PAK that are covering the different 40 cities of Pakistan. The dataset includes two types of views: a 360° ground view and its corresponding satellite image. There are some noises present in the panorama images. When we downloaded the dataset we removed some noises in the panorama images that are given below: 
<ul>
  <li>Removed the multiple clicked panoramas Images of the same location.</li>
  <li>Removed repetitive panoramas.</li>
  <li>Removed indoor panoramas.</li>
  <li>Removed night panoramas.</li>
</ul>

The several sorts of noises that still found in panoramic images are listed below:

<ul>
  <li>Appearance of black patches in the panorama view.</li>
  <li>Unwanted advertisements at the top or below the panorama view.</li>
  <li>Many images include reflections of different objects.</li>
  <li>Many panoramas are distorted and deformed. Objects are stretched. Cars and bikes are overstretched.</li>
  <li>Some panoramas are blurred in different patches of the image.</li>
</ul>

In the future, we will try to eliminate the current noises in panorama images. 

  
## Contact
In case of any question regarding dataset, please email us:
waqas.sultani@itu.edu.pk,
mscs20014@itu.edu.pk

