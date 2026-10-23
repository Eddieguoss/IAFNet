# Terms of Use and License

## Note

MOD is a visible–infrared bimodal obstacle detection dataset designed for complex maritime environments. The dataset contains 2,904 visible–infrared image pairs covering typical maritime scenes, including harbors, docks, nearshore waters, and open waters, under five environmental conditions: sunny (1,162 pairs), nighttime (930 pairs), rainy (465 pairs), foggy (232 pairs), and backlit (115 pairs). MOD uses a single category, “Obstacle”, and contains 16,792 annotated object instances, covering common maritime obstacles such as buoys, fishing boats, cargo ships, and floating debris. All horizontal bounding boxes are annotated in a shared coordinate system and provided in YOLO format. The same annotation files can be used for visible-only, infrared-only, and visible–infrared multimodal training. To prevent temporal leakage between neighboring frames arising from continuous acquisition, the dataset is randomly partitioned at the acquisition-sequence level, with 2,439 image pairs in the training set and 465 image pairs in the test set.

## License

The MOD dataset is freely available to academic and non-academic entities for non-commercial purposes, including academic research, teaching, scientific publications, and personal experimentation. Use of this dataset is subject to the following terms:

1. Any work using the MOD dataset must acknowledge the data source. For research papers, please cite our preferred publication listed on our website; for other forms of work, you must cite that publication or provide a link to the dataset homepage.
2. If you publish new annotations or a derivative dataset based on MOD, you must clearly describe their relationship to the original MOD dataset and annotations on the corresponding homepage or in the accompanying documentation, and inform users that they should also cite the original MOD paper. In addition, you agree that we may publish your new annotations on the original MOD homepage, with acknowledgment of your contributions.
3. You must not use this dataset or any derivative works for commercial purposes, including selling the data, licensing the data commercially, or using the data to obtain commercial gain.
4. All rights not expressly granted under this license are reserved by us.

## Privacy and Ethics

The MOD dataset was collected using shipborne visible and infrared imaging devices in real maritime environments for research on maritime obstacle detection. It is not intended to identify individuals or collect personally identifiable information. Considering that some images may contain sensitive harbor infrastructure or other restricted information, we will review the dataset before public release and exclude images deemed unsuitable for public disclosure. The release and sharing of the dataset will comply with applicable data security requirements and relevant institutional regulations.

Users must not use this dataset to identify individuals, track specific individuals, or otherwise infringe upon anyone’s privacy. If you have any privacy concerns regarding the dataset, or wish to request the removal of information relating to you, please contact us by email at guoss812@163.com.
