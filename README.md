# Uncovering-the-Hidden-Half-of-Plants
This project was developed at CSE REU 2021 at Washington University in St. Louis with Professor Tao Ju, in collaboration with the Danford Science Center. 
We worked to create graphic user interface annotation software for biomedical imaging and root segmentation. 

Why is this project important?
This project was developed at CSE REU 2021 at Washington University in St. Louis with Professor Tao Ju, in collaboration with the Danford Science Center. We worked to create a graphic user interface annotation software for biomedical imaging and root segmentation. Roots are essential to the plants' growth and health, playing a crucial role in providing food for our growing population. By growing the corn in artificial soil in a pot, we can gather data by taking 2D slices of a 3D CT scan. Then, biologists need to annotate to find where the roots are in the images. The process of annotation and navigation is tedious and cumbersome, and currently takes biologists 8 weeks to complete. In an ideal world, we would have a machine learning program to find the roots. However, to make such a program requires ground truth data, so manual annotation is still necessary. Thus, our goal is to create a tool that makes it easier and faster for biologists to find and annotate the roots. We believe that traveling orthogonally to the root allows for more efficient navigation and annotation.

The code for our prototype is in the file "rootSegmentation.py". 
The data (2D slices of a 3D CT scan of corn roots) is in "greyscale_400 2.zip". This contains a subset of a complete corn root system. 
The ground truth data shows the biologist's annotations, which is in "groundtruth_400 2.zip". This contains a subset of a complete corn root system. 
For a demo of the tool, click [here](https://www.youtube.com/watch?v=LFIK5Elue1U) for a video tutorial on using our prototype. 
