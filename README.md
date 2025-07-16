# Skin_Cancer_Detection

Skin cancer is the most common human malignancy and is primarily diagnosed through visual inspection—starting with clinical screening and potentially followed by dermoscopic analysis, biopsy, and histopathological examination. However, the global shortage of dermatologists, especially in resource-limited settings, has encouraged the development of computer-aided diagnosis (CAD) systems. These systems, leveraging advances in artificial intelligence, aim to support clinicians in detecting patterns in dermatoscopic images and guiding the diagnostic process.

While ethical considerations emphasize the irreplaceable role of human judgment—particularly in the final decision-making stages—CAD tools can provide valuable assistance by highlighting salient features and offering objective, reproducible interpretations based on pattern recognition.

The HAM10000 ("Human Against Machine with 10,000 training images") dataset is a curated collection of dermatoscopic images representing seven types of pigmented skin lesions. It has become a benchmark for developing machine learning models in dermatology.

In this project, we aim to develop a deep learning pipeline for multiclass classification of skin lesions using the HAM10000 dataset. Our approach includes:

Careful image preprocessing, aiming to enhance feature quality, reduce noise, and minimize computational cost;

Segmentation of dermatoscopic images to isolate the lesion region, thereby providing a more focused input for classification;

The use of convolutional neural networks (CNNs) and efficient architectures for classification;

Integration of statistical and unsupervised techniques, including clustering and dimensionality reduction, to support feature extraction and analysis.

This project stands at the intersection of data mining and machine learning, combining rigorous data analysis with powerful predictive modeling, with the overarching goal of contributing to interpretable, accurate, and reproducible skin lesion classification systems.

Note:
The project was developed and evaluated in under a month. For more robust and reliable results, it would require a significantly longer and more dedicated effort.
