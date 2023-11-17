# Histogram_based_image_segmentation

This project focuses on image segmentation using histograms. The process involves dividing various regions with distinct gray levels by defining gray level ranges. The effectiveness of this technique relies on the ability to differentiate regions solely based on their histograms. However, if different regions share the same texture, conventional histogram-based segmentation becomes impractical. In such cases, a preprocessing step is necessary, such as utilizing texture-oriented methods like entropy filters or other similar filters to distinguish regions before applying histogram-based segmentation.

To run this program, download the image and code onto your local machine and replace the path to the image with the path of the image on your local machine. E.g. image = io.imread("/image_folder/image_for_segm.jpeg").
