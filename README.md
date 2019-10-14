# Spectral clustering for automated segmentation
While object detection has impacted several industries, much remains unanswered in cancer cell detection using Pap smear microscopy. This project focuses on exploring machine learning algorithms to detect blobs and crop ROI before scrutinizing cells for abnormal traits. Using digital images of cervical cells, our goal is to determine the location of nucleus, which exhibits a range of purple staining intensities. After non-local means preprocessing of 2D color micrographs, we ran the Felsenszwalb’s [1]. efficient graph-based image segmentation, which produced an over-segmentation of a RGB image using a fast, minimum spanning tree based clustering on the image grid. We also inspected the blob morphology.

See Poster in PDF
