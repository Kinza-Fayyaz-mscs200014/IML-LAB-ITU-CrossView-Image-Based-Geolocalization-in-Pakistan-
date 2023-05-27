# Cross View Image Based Geolocalization in Pakistan
<b>Research Topic:</b> Cross View Image Based Geolocalization in Pakistan.<br>
<b>Dataset</b> available <a href = "https://drive.google.com/drive/folders/1LXXdwoJCEbaLp40OCQC5P3CiUtX2xrmg?usp=share_link" target="_blank">here</a><br>
<b>Dataset Name </b>Cross View Pakistan(CV PAK) Dataset<br>

In this research, we working on cross-view image-based geolocation that pertains to matching two images from diverse perspectives - one from a panorama viewpoint and the other from a satellite or aerial viewpoint. It is a process in which we compare a ground image that is a 360-degree panoramic image with their corresponding GPS-tagged satellite image to determine their location. There is a huge similarity gap between these two views. Recently, research has achieved extortionate accuracy on existing datasets such as CV USA, CV ACT, and VIGOR. There is no dataset available that covers Asian countries like Pakistan, India, Malaysia, etc. Existing datasets cover countries like America and Australia. Everyone worked on the existing datasets and applied their method to it and achieved high accuracy on it. By Filling the gap in the existing dataset we proposed a new large and scalable dataset in Pakistan that’s name cross view Pakistan (CV PAK). This dataset is very diverse and includes various images covering both rural and urban areas. The majority of the solutions that have been suggested for this issue attempt to use object recognition methods to identify things in photographs and then match those objects until they find the most suitable matching pairings. Therefore, VGG-16 is the most often utilized architecture for this topic among researchers. The majority of research initially tried to locate recognizable elements or objects in the picture under investigation and then looked for the best match within the reference database. However, these solutions were hindered by the challenge of appearance gaps. To overcome this issue and minimize the differences in appearance between images from diverse perspectives, the polar transformation method proved to be highly effective. Nonetheless, this method lacked orientation information, which was deemed critical in the process. As a result, recent research in this field has shifted towards using a transformer-based approach (TransGeo) instead of a CNN-based method. This approach maximizes the advantages of transformers, such as explicit location information encoding and global information modeling. This method also has less computational cost than the previous methods. That is relatively very fast in comparison to the other methods. Our contribution to this research is that we proposed a new dataset cross-view Pakistan (CV PAK) that is covering the cross-view images in Pakistan. Then we implement five previous methods on this dataset to compute the results. 

Previous datasets \cite{zhai2017predicting,liu2019lending, vo2016localizing,anguelov2010google, zhu2021vigor,zheng2020university} do not cover the dataset of developing countries. It mostly covers the dataset of developed countries. Street views(Panoramas) are in high resolution which is not available in many countries in the world. There are around 55 countries that are not covering Google street view according to the given below source. Source:\url{https://en.wikipedia.org/wiki/Google_Street_View}. Different datasets are required to cover almost the entire world, including Asia, Africa, and Europe. Most cutting-edge technologies struggle to function well in congested Asian cities.
, which poses a significant challenge. By generating datasets from such locations with identical settings, we can encounter new difficulties. Existing datasets do not accurately reflect real-world environments as they lack images with dense crowds of people and objects and are comparatively simple to work with.

<br>
<img src="sample image.jpg">
# Dataset Details
We proposed a new dataset cross-view Pakistan (CV PAK) that includes Pakistan's ground and satellite images. The contrast between our datasets is presented in Table 3.2 and the previous datasets. We will first discuss the process of collecting the ground-level and aerial imagery then later we will show some diverse collected images of our Dataset. 
We collected the 360$^{\circ}$ angled Panoramas and satellite images in Pakistan.
           \item We gathered 11,632 panorama views and their corresponding 11,632 satellite views from Pakistan.
           There is almost 40 days = 1440 hours = 86400 minutes = almost 2 months required for collecting my dataset.
In 40 Pakistani cities, we collected our dataset. Figure 3.1 shows a Map of collected cities along with the provinces.


There are two types of views that we want to collect in Pakistan.
\begin{itemize}
    \item Ground view( 360 Panorama images)
    \item Satellite view(satellite photos)
\end{itemize}

We'll look into the collection of ground-level perspectives in this part. We are using the “Street View Download 360” Application for collecting the  360$^{\circ}$ angled panoramic Images. Now, first, discuss details about the collection of panoramic images. we are covering 40 cities and 4 provinces of Pakistan in our dataset. Table 3.1 shows the name of the provinces along with their cities that are included in our dataset.
\item \textbf{Medium for gathering the aerial imagery}
For downloading high-resolution satellite images we used the "SAS Planet" application.
Application free version is available. We use their free version for collecting our satellite images. We want to collect correspondence satellite images of the panorama images. Copy all panorama image paths in an Excel file.



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
  
  ## Citation
  If you are using our dataset, please cite this publication.<br>
 <div class="snippet-clipboard-content position-relative overflow-auto" data-snippet-clipboard-copy-content=" @article{sultani2021towards,
  title={Towards Low-Cost and Efficient Malaria Detection},
  author={Sultani, Waqas and Nawaz, Wajahat and Javed, Syed and Danish, Muhammad Sohail and Saadia, Asma and Ali, Mohsen},
  journal={arXiv preprint arXiv:2111.13656},
  year={2021}
}"><pre><code> @article{sultani2021towards,
  title = {Towards Low-Cost and Efficient Malaria Detection},
  author = {Sultani, Waqas and Nawaz, Wajahat and Javed, Syed and Danish, Muhammad Sohail and Saadia, Asma and Ali, Mohsen},
  journal = {arXiv preprint arXiv:2111.13656},
  year = {2021}
}
</code></pre></div>
 
## Contact
In case of any question regarding dataset, downloading, papers details, please email all of us:
waqas.sultani@itu.edu.pk,
mohsen.ali@itu.edu.pk, 
syed.javed@itu.edu.pk,
msds20004@itu.edu.pk
