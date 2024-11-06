# handwriting-recognizer
The study of the existing system for the handwriting recognition project involves a comprehensive review of the current approaches, techniques, and technologies employed in the field of Optical Character Recognition (OCR) and handwriting recognition. This study aims to identify the strengths, limitations, and gaps in the existing systems to inform the development of an improved recognition model.
Existing systems for handwriting recognition typically rely on a combination of traditional image processing techniques and machine learning algorithms. These systems often involve preprocessing steps such as binarization, noise reduction, and feature extraction to enhance the quality of handwritten images before classification. Machine learning models, including Support Vector Machines (SVMs), k-Nearest Neighbors (k-NN), and decision trees, are commonly used for digit recognition tasks.
While traditional approaches have achieved some success in recognizing handwritten digits, they often struggle with variability in writing styles, sizes, and orientations. Additionally, these systems may lack scalability and generalization ability when faced with large and diverse datasets. Moreover, they may require manual feature engineering and tuning, making them less adaptable to different writing styles and languages.
In recent years, deep learning techniques, particularly Convolutional Neural Networks (CNNs), have emerged as a promising approach for handwriting recognition. CNNs excel at learning hierarchical features directly from raw pixel data, eliminating the need for manual feature engineering. They can capture complex patterns and variations in handwriting, leading to more accurate and robust recognition performance.
Despite the advancements enabled by deep learning, challenges remain in optimizing model architectures, training strategies, and data augmentation techniques for handwriting recognition. Furthermore, there is a need for benchmark datasets and evaluation metrics to facilitate fair comparisons between different recognition systems.
In summary, the study of the existing system highlights the evolution of handwriting recognition techniques from traditional image processing methods to deep learning approaches. It underscores the importance of leveraging the strengths of deep learning while addressing the limitations of existing systems to develop a more effective and reliable handwriting recognition model.

#requirements
cycler==0.10.0
decorator==4.4.0
imageio==2.5.0
kiwisolver==1.0.1
mahotas==1.4.5
matplotlib==3.0.3
networkx==2.3
numpy==1.16.2
opencv-contrib-python==4.1.0.25
Pillow==6.0.0
pyparsing==2.4.0
python-dateutil==2.8.0
PyWavelets==1.0.3
scikit-image==0.15.0
scikit-learn==0.20.3
scipy==1.2.1
six==1.12.0
