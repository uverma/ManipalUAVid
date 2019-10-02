# ManipalUAVid
Finely Annotated UAV Aerial Video Dataset for Semantic Segmentation


In the last few years, Unmanned Aerial Vehicles (UAV) have been used for various applications such as object detection and tracking, action recognition, etc. There exist different datasets for evaluating the performance of these tasks. However, there is no standard dataset with fine annotation for semantic segmentation of UAV aerial videos. In this work, a new UAV aerial video dataset is developed for semantic segmentation. This dataset contains aerial videos of a closed campus (Manipal Institute of Technology, India) captured using DJI Phantom 3 Professional drone with 1280 x 720 resolution. We provide a four-class fine annotation (Greenery, Construction, Road, and Water Bodies) describing the general layout of the scene. 


## Dataset Details

Few sample images and the corresponding annotation are shown below. 
![alt text](https://github.com/uverma/ManipalUAVid/blob/master/f_168.jpg)
![alt text](https://github.com/uverma/ManipalUAVid/blob/master/label_f_168.png)


![alt text](https://github.com/uverma/ManipalUAVid/blob/master/frame191.jpg)
![alt text](https://github.com/uverma/ManipalUAVid/blob/master/label_frame191.png)


![alt text](https://github.com/uverma/ManipalUAVid/blob/master/85.png)
![alt text](https://github.com/uverma/ManipalUAVid/blob/master/label_85.png)

The four class ground truth as per our labelling policy is provided in JSON file using the LabelMe tool. The JSON file for each image contains details of each annotated regions. This information includes class label assigned to each region, along with the coordinates (pixel location) of all points of the polygon used to mark the region. A sample file is shown below:

> "label": "greenery",
>      "line_color": null,
>      "fill_color": null,
>      "points": \[
        \[
          439,
          347
        ],
        \[
          453,
          343
     ],
     \[
          418,
          329
        ]
      ],
      "shape_type": "polygon"
    }







## Download: 
This dataset is made available for academic research purpose only, and should not be used for any commercial purpose. To download the dataset, please fill the [Google Form](https://docs.google.com/forms/d/e/1FAIpQLScGsutUkmxbZIaiJxsknezz-rd-OuhUfFZRML6RInolf9UlxA/viewform). The link to download the dataset shall be shared to your email address.

Please cite the following  article if you intend to use this dataset:
> S. Girisha, M. M. M. Pai, U. Verma and R. M. Pai, "Performance Analysis of Semantic Segmentation Algorithms for Finely Annotated New UAV Aerial Video Dataset (ManipalUAVid)," in IEEE Access, vol. 7, pp. 136239-136253, 2019.
doi: 10.1109/ACCESS.2019.2941026


## Reference:

B. C. Russell, A. Torralba, K. P. Murphy, W. T. Freeman. LabelMe: a Database and Web-based Tool for Image Annotation. International Journal of Computer Vision, 77(1-3):157-173, 2008



 
