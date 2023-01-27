<h1>WTA/TLA: A UAV-captured Dataset for Semantic Segmentation of Energy Infrastructure</h1>

WTA (Wind Turbine Aerial) and TLA (Transmission Line Aerial) are public datasets which contain a set of RGB images from wind turbine farms and transmission towers and power lines, along with semantic ground truth for relevant classes. This is the official repository of the paper: WTA/TLA: A UAV-captured Dataset for Semantic Segmentation of Energy Infrastructure (link coming soon).

<table><tr>
<td> <img src="https://user-images.githubusercontent.com/11805918/155500938-6dbba64b-c769-4e1b-9365-37ea0adb0937.jpg" width="500" height="300">  </td>
<td> <img src="https://user-images.githubusercontent.com/11805918/155500964-309ddda1-d186-478e-88ac-f5938aaf2af7.jpg" width="500" height="300">  </td>
</tr></table>


Contents:
Please find and download the datasets with their annotations:
- WTA Dataset: https://drive.google.com/file/d/16k1lGQ1veMgXauzmakV2A1Y_C0StnsNn/view?usp=sharing
- TLA Dataset: https://drive.google.com/file/d/1wNCyy4UT3fMRu5z6XBlrLPBVhwRp9uTO/view?usp=sharing


<h5>Format</h5>



Each dataset contains multiple locations. For each location:
- images/ directory contains RGB images
- multi_masks/ directory contains semantic image masks, with each class encoded in a different color (0:background, 1:blade, 2:tower).
- annotations/ directory contains semantic image masks, for visual inspection.

<h5>Training/Testing</h5>

train.txt/test.txt and train_gt.txt/test_gt.txt contain images and masks for training and testing respectively

<h5>Code</h5>

Coming soon.

<h5>Citation:</h5>
```
@inproceedings{za2022wtatla,
  author={Zampokas, Georgios and Skartados, Evangelos and Alexiou, Dimitrios and Tsiakas, Kosmas and Tzanakis, Ioannis and Roussos, Nikolaos and Giakoumis,   Dimitrios and Kostavelis, Ioannis and Bouganis, Christos-Savvas and Tzovaras, Dimitrios},
  booktitle={2022 International Conference on Unmanned Aircraft Systems (ICUAS)}, 
  title={WTA/TLA: A UAV-captured Dataset for Semantic Segmentation of Energy Infrastructure}, 
  year={2022}
```

<h5>Contact:</h5>

For information/questions about the paper or code, please contact [Giorgos Zampokas](mailto:gzampokas@iti.gr).
