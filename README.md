# 🧠 Word Cloud Text Visualization of *Alice’s Adventures in Wonderland*

## 📌 Overview
This project shows how to take a piece of text (a classic novel) and turn it into a **word cloud** to see which words appear most often. It starts with a simple rectangular word cloud, then removes unimportant words (like “said”), and finally creates a **shaped word cloud** using an Alice-and-rabbit mask image.

This is a good example of text visualization for a **Data Analyst portfolio** — it shows you can load data, clean it, and present it visually.

---

## 🎯 What the notebook does

1. **Imports libraries**  
   - `wordcloud` (for creating word clouds)  
   - `matplotlib` (for displaying the image)  
   - `urllib` (to download the text)  
   - `numpy` and `Pillow` (to load and use the image mask)

2. **Downloads the text** of *Alice’s Adventures in Wonderland* from a public URL.

3. **Creates a stopword list** using `STOPWORDS` and adds extra words like `"said"` that are not meaningful.

4. **Generates a basic word cloud** from the novel text.

5. **Displays the word cloud** using Matplotlib.

6. **Downloads an Alice mask image**, converts it to a NumPy array, and shows it.

7. **Generates a shaped word cloud** using that mask so the words follow the outline of Alice and her rabbit.

---

## 🧰 Technologies Used
- Python
- `wordcloud`
- `matplotlib`
- `urllib`
- `numpy`
- `Pillow` (`from PIL import Image`)

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/alice-wordcloud-text-visualization.git
   cd alice-wordcloud-text-visualization
   
2. Install required libraries
   pip install wordcloud matplotlib pillow numpy

3.Open the notebook.
jupyter notebook Word_Clouds_Alice_in_Wonderland.ipynb

4.Run the cells in order
Step 1–4: setup and download text
Step 5–8: basic word cloud
Step 9: add extra stopwords (e.g. "said") and regenerate
Step 10–12: load mask image and create Alice-shaped word cloud

5.Why This Project Matters for a Data Analyst Role

📊 Demonstrates ability to work with text data (downloading, cleaning, visualizing).
🧹 Shows understanding of stopwords and text preprocessing.
🎨 Highlights skills in Python visualization libraries such as Matplotlib and WordCloud.
📘 Presents a clean, step-by-step notebook that’s easy to follow and replicate.

👤 Author

Vidya Vishnuvihar
Aspiring Data Analyst
Project: Word Cloud Analysis of Alice’s Adventures in Wonderland
