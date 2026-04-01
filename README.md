# creative_ai
AI-powered DeepDream project using InceptionV3 to generate surreal images by blending Mars and Eiffel Tower visuals.
# 🎨 Deep Dream Image Generator (Mars × Eiffel)

## 📌 Overview

This project uses **Deep Learning (InceptionV3)** to generate dream-like artistic images by enhancing patterns learned by a neural network.

We blend two images (**Mars + Eiffel Tower**) and apply the **DeepDream algorithm** to create surreal visuals.

---

## 🎯 Objective

* Understand feature extraction in CNNs
* Visualize learned patterns of deep networks
* Generate creative AI-based images

---

## 💡 Key Idea

Instead of training a model, we:

* Use a **pretrained InceptionV3 model**
* Extract intermediate layer activations
* Maximize these activations using gradients
* Modify the image iteratively → Dream effect 🎨

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* PIL

---

## ⚙️ Workflow

1. Load two images (Mars & Eiffel Tower)
2. Blend images using PIL
3. Preprocess image for model
4. Pass image through InceptionV3
5. Extract feature maps from layers:

   * `mixed3`
   * `mixed5`
   * `mixed7`
6. Calculate loss from activations
7. Apply gradient ascent on image
8. Generate dream-like output

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/deep-dream-project
cd deep-dream-project
pip install -r requirements.txt
jupyter notebook main.ipynb
```

---

## 📊 Output

* Dream-like artistic images
* Enhanced textures and patterns
* Abstract neural visualization

---

## 📄 Detailed Documentation

👉 [Click here](DOCUMENTATION.md)

---

## 🚀 Future Improvements

* Use different CNN architectures
* Apply style transfer
* Generate animations (video frames)
* Add UI for user inputs

---

## 👨‍💻 Author

Sahil Jagtap
