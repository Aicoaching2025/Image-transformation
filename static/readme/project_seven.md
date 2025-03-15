# 🎨 Heart Image Transformation Project

Welcome to the **Heart Image Transformation Project**! ❤️  

This project demonstrates how to create, manipulate, and transform images using **NumPy arrays** and **linear algebra** in Python. By treating images as matrices, you’ll learn how to apply operations like rotations, color inversion, and random image generation.

---

## 🚀 **Project Features**

✅ Create colorful images using **NumPy arrays**  
✅ Rotate images without distorting colors  
✅ Invert image colors for creative effects  
✅ Generate random colorful images  
✅ Visualize transformations using **Matplotlib**  

---

## 📝 **Technologies Used**

- **Python 3**  
- **NumPy** – For matrix operations and image manipulation  
- **Matplotlib** – For visualizing images and transformations  

---

## 📂 **Project Structure**

```plaintext
heart_image_project/
├── heart_image.py      # Main Python script with all transformations
├── requirements.txt    # List of dependencies
└── README.md           # Project overview (this file)
```

---

## 🖥️ **How to Run the Project**

1. **Clone the Repository:**

```bash
git clone https://github.com/yourusername/heart_image_project.git
cd heart_image_project
```

2. **Install Dependencies:**

```bash
pip install -r requirements.txt
```

3. **Run the Script:**

```bash
python heart_image.py
```

---

## 🖼️ **Transformations Included**

### 🧡 Original Heart Image
A colorful heart created using an RGB matrix.

![Original Heart Image](https://via.placeholder.com/400x400?text=Original+Heart+Image)

---

### 🔄 Rotated Heart Image
Rotated 90° clockwise while preserving colors.

![Rotated Heart Image](https://via.placeholder.com/400x400?text=Rotated+Heart+Image)

---

### 🌈 Inverted Color Heart Image
Inverted colors to give a creative, negative effect.

![Inverted Heart Image](https://via.placeholder.com/400x400?text=Inverted+Heart+Image)

---

### 🎨 Random Colorful Image
Randomly generated image to show the versatility of NumPy arrays.

![Random Image](https://via.placeholder.com/400x400?text=Random+Colorful+Image)

---

## 🛠️ **Key Functions Explained**

- `show_image(image, title)`: Displays the image using Matplotlib.  
- `np.rot90(image, k=1, axes=(0, 1))`: Rotates the image without affecting colors.  
- `255 - image`: Inverts the colors of the image.  
- `np.random.randint(80, 180, (7, 7, 3))`: Generates a random colorful image with softer colors.  

---

## 💡 **What You’ll Learn**

✅ Basics of **image representation** using arrays  
✅ **Matrix operations** for image transformations  
✅ How to **invert colors** and **rotate images** correctly  
✅ Using **Matplotlib** to visualize image data  

---

## 📢 **Contributing**

Want to add more transformations or new features? Feel free to submit a pull request! 💪  

---

## 📄 **License**

This project is licensed under the [MIT License](LICENSE).  

---

## 🚀 **Let’s Make Coding Colorful!** 🌈✨

> *"Code is art, and with NumPy, you can literally paint with arrays!"* 🎨💻
