# Face Mask Detection

A comprehensive machine learning project for detecting face masks in images or real-time video streams. This project is designed to aid in public safety efforts by identifying individuals wearing or not wearing masks using computer vision techniques.

---

## Setup Instructions

### Install Required Python Packages
```bash
pip install -r requirements.txt
```

### Dataset
The dataset is inside the dataset directory, it has two different daasets available to train with: with mask and without mask 


## How It Works
1. **Face Detection**: The system first detects faces in an image or video frame.
2. **Mask Classification**: Each detected face is classified as `with_mask` or `without_mask` using a trained deep learning model.
3. **Visual Output**: Results are displayed with bounding boxes around faces and corresponding labels.

---

## Custom Training

To train the model on a custom dataset:

1. Prepare the dataset in the `dataset/` folder, structured as:
   ```
   dataset/
   ├── with_mask/
   └── without_mask/
   ```

2. Run the training script:
   ```bash
   python scripts/train_mask_detector.py
   ```

---

## Technologies Used
- **Python**
- **OpenCV**: For image and video processing.
- **TensorFlow/Keras**: For building and training the deep learning model.
- **Git LFS**: To handle large files such as datasets or pre-trained models.

---

## Contributing
Contributions are welcome! Please create a pull request or open an issue to discuss your ideas.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments
- Open-source libraries and frameworks.
- Datasets and pre-trained models from the machine learning community.

---


## Contact
If you have any questions or feedback, feel free to contact me:
- **Email**: [manasvi.g.agrawal@gmail.com]
```
