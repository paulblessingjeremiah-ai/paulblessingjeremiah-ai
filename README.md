# Paul Blessing Jeremiah

Biomedical engineer (B.Eng., First Class Honours, University of Ilorin) working on medical image analysis and machine learning. I build small, tested tools, and I check my own results for mistakes.

## Projects

**[DICOM Toolkit](https://github.com/paulblessingjeremiah-ai/dicom-toolkit)** (Python, pydicom, pytest)
Reads and summarises DICOM metadata, anonymises a defined set of patient tags, converts CT data to Hounsfield Units with window presets, and loads slice series into sorted 3D volumes. 13 automated tests. Found and fixed a bug that changed the original data during anonymisation.

**[Lung Segmentation U-Net](https://github.com/paulblessingjeremiah-ai/lung-segmentation-unet)** (PyTorch)
A U-Net written from scratch, trained on 704 chest X-rays. Test Dice 0.96 and IoU 0.93 on 106 held-out images, with an analysis of the worst failures. 9 automated tests.

**[Chest X-ray Classification and Shortcut Audit](https://github.com/paulblessingjeremiah-ai/chest-xray-cnn-gradcam)** (PyTorch)
A ResNet18 classifier with Grad-CAM, and an audit of what it learned. I found that the four classes differ in image size, markers, redaction boxes and patient age, and that some test images had near-copies in the training set. After removing duplicates, mean test accuracy over three seeds was 98.2%. Masking everything outside the lungs lowered it to 94.2%.

## What I focus on

Honest evaluation: held-out validation sets, multiple seeds, failure analysis, and stating the limits of each result.

## Contact

[LinkedIn](https://www.linkedin.com/in/paul-blessing-)
