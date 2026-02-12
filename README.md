# CEN434 – Deep Neural Networks Project

## Topic
Comparative Analysis of CNN Architectures using Grad-CAM Visualization

## Authors
Xhuljano Agalliu  
Endri Hala  

---

## Project Description
This project compares two pretrained convolutional neural networks:
- MobileNetV2
- ResNet50

We analyze their behavior on two images of cats with different background complexity.

---

## Experiments Conducted

1. Image classification using MobileNetV2
2. Image classification using ResNet50
3. Grad-CAM visualization for interpretability
4. Multi-model comparison
5. Analysis of confidence levels
6. Background influence study

---

## Key Findings

- Complex backgrounds significantly influence classification.
- ResNet50 produces higher confidence even when incorrect.
- MobileNetV2 shows more balanced probability distribution.
- Grad-CAM helps interpret model decisions and detect failure cases.

---

## Technologies Used

- TensorFlow / Keras
- MobileNetV2
- ResNet50
- OpenCV
- Matplotlib
- Google Colab

---

## Conclusion

Model interpretability techniques such as Grad-CAM are essential to understand decision-making processes in deep learning systems.
