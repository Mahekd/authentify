# Authentify

### Real vs Fake Face Image Classification using GANs

## Project Overview

Authentify is a deep learning project that uses **Generative Adversarial Networks (GANs)** to classify face images as real or fake. The system consists of a Generator that creates synthetic face images and a Discriminator that learns to distinguish between authentic and generated images.

This project demonstrates the application of GANs in image authentication and deepfake detection.

---

## Project Structure

```
app.ipynb                      # Main application notebook
final_image_syntesis_GAN.ipynb # GAN training notebook
model_testing.ipynb            # Model evaluation & testing
discriminator_model.h5         # Trained discriminator model (Not included)
FINAL_discriminator_model.h5   # Final trained model (Not included)
templates/                     # HTML templates (if using Flask)
uploads/                       # Uploaded test images
test_images_real/              # Real test images
test_images_fake/              # Fake test images
```

---

## Model Files

The trained `.h5` model files are not included in this repository due to GitHub file size limits.

---

## 🚀 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/authentify.git
```

2. Install required libraries:

```
pip install tensorflow numpy matplotlib flask
```

3. Download the trained model file and place it in the root directory.

4. Run:

```
python app.py
```

or open `app.ipynb`.

---

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* GAN Architecture

---

## Features

✔ GAN-based image generation
✔ Real vs Fake image classification
✔ Wasserstein loss for stable training
✔ CNN-based discriminator
✔ Image preprocessing pipeline


