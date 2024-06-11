# Drone-Based Object Detection and Tracking

## Project Overview

This project focuses on implementing and analyzing drone-based object detection and tracking using the Visdrone dataset. The primary goal is to train a model capable of detecting various objects from aerial images and videos, leveraging the Ultralytics framework.

![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/4e73495f-33ab-4737-ac54-3b6b0b270da2)

## Table of Contents
1. [Installation](#installation)
2. [Dataset](#dataset)
3. [Training the Model](#training-the-model)
4. [Visualization](#visualization)
5. [Prediction](#prediction)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Installation

To get started, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/drone-object-detection.git
cd drone-object-detection
pip install -r requirements.txt
```

## Dataset

The project uses the Visdrone dataset, a large-scale benchmark created by the AISKYEYE team at Tianjin University, China. The dataset includes:

- 288 video clips with 261,908 frames
- 10,209 still images
- Annotations for objects like pedestrians, vehicles, bicycles, etc.

You can download the dataset from [this link](https://github.com/ultralytics/ultralytics/blob/main/ultralytics/cfg/datasets/VisDrone.yaml).

## Training the Model

We utilize Google Colab for training due to its computational resources. To train the model, follow these steps:

1. Open a new notebook in Google Colab.
2. Install the Ultralytics package using the following code:
   
   ```python
   !pip install ultralytics
   ```

3. Set up the Visdrone dataset in your Colab environment.
4. Train the model using the provided configuration file and training script.

## Visualization

We use TensorBoard to visualize the training process. After training, you can visualize the results using the following command:

```python
%load_ext tensorboard
%tensorboard --logdir=runs
```
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/5df1fa8f-7a77-4ad0-95b9-50dfe94af8e1)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/a3e7727e-7925-472d-95f5-9e4ef56bdf41)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/2d2cfc9a-8a59-471d-adc8-cefafc18c87c)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/5e923865-90c7-4ed7-b4bf-2baeba70e29d)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/21408e45-0238-41ad-a7b9-267c1febe9e7)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/2bca182b-b7be-436e-aa62-cb22fd5d1719)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/4e9f82af-0fb2-4a07-bae8-3df09baf63f5)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/cdaf5c99-ef30-4e53-a246-f20c0354b917)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/e5eac06a-df4f-4a61-af23-d37e2683a615)



## Results

The trained model effectively detects and tracks objects from aerial footage. Here are some examples of the model's performance:

![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/5e0ff7e8-8857-4168-ad6d-50418f3d2fdd)
![image](https://github.com/amirhosseineslami/CarDetecting_Yolov8/assets/95607919/fb512c53-b1aa-490a-a3fa-c1b2d2928e7e)


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out with any questions or suggestions!
