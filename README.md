# Cross View Image Based Geolocalization in Pakistan
<b>Research Topic:</b> Cross View Image Based Geolocalization in Pakistan.<br>
<b>Dataset</b> available <a href = "https://drive.google.com/drive/folders/1LXXdwoJCEbaLp40OCQC5P3CiUtX2xrmg?usp=share_link" target="_blank">here</a><br>
<b>Dataset Name </b>Cross View Pakistan(CV PAK) Dataset<br>

In this research, we working on cross-view image-based geolocation pertains to matching two images from diverse perspectives - one from a panorama viewpoint and the other from a satellite or aerial viewpoint. It is a process in which we compare a ground image that is a 360-degree panoramic image with their corresponding GPS-tagged satellite image to determine their location. There is a huge similarity gap between these two views. Recently, research has achieved extortionate accuracy on existing datasets such as CV USA, CV ACT, and VIGOR. There is no dataset available that covers Asian countries like Pakistan, India, Malaysia, etc. Existing datasets cover countries like America and Australia. Everyone worked on the existing datasets and applied their method to it and achieved high accuracy on it. By Filling the gap in the existing dataset we proposed a new large and scalable dataset in Pakistan that’s name cross view Pakistan (CV PAK).This dataset is very diverse and includes various images covering both rural and urban areas. The majority of the solutions that have been suggested for this issue attempt to use object recognition methods to identify things in photographs and then match those objects until they find the most suitable matching pairings. Therefore, VGG-16 is the most often utilized architecture for this topic among researchers. The majority of research initially tried to locate recognizable elements or objects in the picture under investigation and then looked for the best match within the reference database. However, these solutions were hindered by the challenge of appearance gaps. To overcome this issue and minimize the differences in appearance between images from diverse perspectives, the polar transformation method proved to be highly effective. Nonetheless, this method lacked orientation information, which was deemed critical in the process. As a result, recent research in this field has shifted towards using a transformer-based approach (TransGeo) instead of a CNN-based method. This approach maximizes the advantages of transformers, such as explicit location information encoding and global information modeling. This method also has less computational cost than the previous methods. That is relatively very fast in comparison to the other methods. Our contribution to this research is that we proposed a new dataset cross-view Pakistan (CV PAK) that is covering the cross-view images in Pakistan. Then we implement five previous methods \cite{liu2019lending, shi2019spatial,shi2020looking,toker2021coming,zhu2022transgeo} on this dataset to compute the results. 

<br>
<img src="sample image.jpg">
# Dataset Details
M5-Malaria Dataset (Multi Micrscope Multi Magnification Malaria Dataset) contains 2x3x1257 Images containing malarial blood cells. We have 1257 images from thin blood smears and the same regions have been tracked and captured on three different magnifications of two different microscope. We captured the images using HCM (high cost microscope) on three magnifications (100x, 400x, 1000x) and then tracked and captured the same locations with LCM (Low cost microscope). The images are in .png format and annotations are in pascal_voc format. If you need the COCO format of our dataset, you can generate the coco format annotations using the file <a href="https://github.com/intelligentMachines-ITU/LowCostMalariaDetection_CVPR_2022/blob/main/pascalToCoco.py">PascalToCoco.py</a>.

### Dataset Link
You can download our dataset from <a href="https://drive.google.com/drive/folders/1k2GuIu6obj3Nz--dOTLuwQnJ2qs1sXxE?usp=sharing" target = "_blank">here</a>. <br>
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
