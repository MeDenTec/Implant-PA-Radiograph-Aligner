# Implant PA Radiograph Aligner

This project focuses on aligning periapical radiographs of dental implants to standardize them for further analysis. The main goal is to automate the process of radiograph alignment, enabling easier comparison and assessment of implant health over time.

## Features
- **Alignment of radiographs**: Automatic alignment of dental implant radiographs for consistent views.
- **Pre-trained model**: Includes a pre-trained Keras model, `implant_aligner_2371Withaug_WOrgb263epoch_cpu.keras`, for aligning radiographs.
- **Support for augmentation**: Integrated augmentation techniques to improve model robustness.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/MeDenTec/Implant-PA-Radiograph-Aligner.git
   cd Implant-PA-Radiograph-Aligner
   pip install -r requirements.txt
2. Navigate to the project directory:
   ```bash
   cd Implant-PA-Radiograph-Aligner
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
4. Download the pre-trained model and place it in the root directory of the project:
    https://github.com/MeDenTec/Implant-PA-Radiograph-Aligner/blob/main/implant_aligner_2371Withaug_WOrgb263epoch_cpu.keras
## Uasge
1. Prepare your radiographs as input and place them in the appropriate folder.
2. Run the alignment notebook:
    ```bash
    jupyter notebook align_radiographs.ipynb
3. Adjust alignment parameters in the notebook as necessary to fit your dataset.
4. The aligned images will be output for further analysis.
## Files

- **align_radiographs.ipynb**: The main notebook that performs radiograph alignment using the pre-trained model. It takes input images and aligns them based on the model’s predictions.
  
- **implant_aligner_2371Withaug_WOrgb263epoch_cpu.keras**: The pre-trained Keras model used for aligning the radiographs. This model has been trained specifically to identify the optimal alignment for dental implant radiographs.
  
- **requirements.txt**: Contains all the necessary dependencies required to run the project. You can install these dependencies with the following command:
## Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.
## License
This project is licensed under the MIT License. See the LICENSE file for details.
