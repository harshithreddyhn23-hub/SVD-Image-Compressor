# SVD Image Compressor

A web-based tool that compresses images using **Singular Value Decomposition (SVD)**. Upload an image, adjust the compression rank, and see the visual and data-reduction results in real-time.

---

## ✨ Features

-   **Upload Image**: Load any image directly from your device.
-   **Adjustable Rank (k)**: Control the level of compression by setting the number of singular values to retain.
-   **Side-by-Side Comparison**: View the original and compressed images together.
-   **Compression Statistics**: See the data reduction percentage.
-   **Download**: Save the compressed image as a PNG file.

---

## 🛠️ Technologies Used

| Technology      | Purpose                                        |
| :-------------- | :--------------------------------------------- |
| **HTML5**       | Structure of the web page                      |
| **Tailwind CSS**| Styling and responsive design                  |
| **JavaScript**  | Application logic and SVD implementation       |
| **numeric.js**  | Library for matrix computations (SVD)          |

---

## 🚀 How to Use

1.  **Open the Application**: Double-click `svd_image_compressor.html` to open it in your web browser.
2.  **Upload an Image**: Click the "Upload Image" button and select a file.
3.  **Set Compression Rank**: Use the slider to choose a value for **k**. A lower value means more compression (and more quality loss).
4.  **Compress**: Click the "Compress" button to apply SVD compression.
5.  **Download**: Once compressed, click the "Download" button to save the result.

---

## 📚 How It Works

Singular Value Decomposition (SVD) is a matrix factorization technique. This tool applies SVD to the Red, Green, and Blue color channels of an image separately. By keeping only the top `k` singular values, the image data is approximated, resulting in a smaller data footprint while retaining visual similarity to the original.

---

## 📝 License

This project is open source and available for personal and educational use.
