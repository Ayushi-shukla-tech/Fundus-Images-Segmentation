# Eye Fundus-Images-Segmentation

This project focuses on segmenting eye fundus images to identify vessels, the optic disc, and the optic cup using advanced deep learning models. The models employed include UnetR and AttUnet, each designed to enhance segmentation accuracy through innovative architecture designs.

# Models Used
UnetR Architecture

UnetR is a 3D medical image segmentation model that combines a transformer-based encoder with a CNN-based decoder to predict segmentation masks. The architecture follows a contracting-expanding pattern, where a series of transformers form the encoder. These transformers are connected to a CNN-based decoder through skip connections, allowing the model to effectively capture and utilize spatial information from different layers.
![Screenshot 2024-04-27 155237](https://github.com/Ayushi-shukla-tech/Fundus-Images-Segmentation/assets/96163798/5be57693-7af0-4f18-8d92-2aa783d5144c)
                                          UnetR Architecture


AttUnet Architecture

AttUnet builds upon the traditional Unet architecture by integrating attention gates. In the Unet architecture, skip connections transfer spatial information from the downsampling path to the upsampling path, but this can introduce redundant low-level features. AttUnet addresses this issue by incorporating attention gates at the skip connections. These attention gates selectively focus on relevant regions, suppressing irrelevant features and enhancing the accuracy of the segmentation.
![Screenshot 2024-04-27 193757](https://github.com/Ayushi-shukla-tech/Fundus-Images-Segmentation/assets/96163798/05935975-cace-4dd3-95b2-89015ed7e5d1)
                                          AttUnet Architecture

