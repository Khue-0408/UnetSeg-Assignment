# UnetSeg-Assignment

This project is a UNet-based image segmentation assignment.

## Checkpoint Weight
Download the checkpoint weight file from the following link:
[Google Drive Link](https://drive.google.com/drive/folders/16dhWITvgTHD-THTtQdT3c-M4RGCxxpM9?usp=sharing)

After downloading the `model.pth` file, place it into the same directory as the `infer.py` file.

## How to Run

1. Clone the repository, navigate to the project directory, and run the inference script:
   ```bash
   git clone https://github.com/Khue-0408/UnetSeg-Assignment
   cd UnetSeg-Assignment
   python3 infer.py --image_path image.jpeg
