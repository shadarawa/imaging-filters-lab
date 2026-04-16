# 🧪 Imaging Filters Lab (DIP)

An interactive **Digital Image Processing** lab built with **Python + OpenCV + Gradio**.  
Upload an image → pick a filter → tune parameters → visualize results.

---

## ✨ Features

- **Point operations:** Negative, Threshold, Log, Gamma, Contrast Stretch, Gray-level slicing
- **Histogram:** Equalization, CLAHE, Histogram Matching
- **Spatial filters:** Mean, Gaussian, Median, Laplacian sharpening, Unsharp/High-boost, Edge detection
- **Frequency domain (FFT):** Low/High/Band/Notch (Ideal / Gaussian / Butterworth)
- **Wavelets:** DWT subbands, Denoise, Wavelet Packet
- **Noise models & restoration**
- **Morphology & Skeletonization**
- **Binary set operations**

---

## ▶️ Demo Video

🎥 Watch the demo (Release v1.0.0):  
[Demo Video]
https://drive.google.com/file/d/18Q7s3Y5NGSeEnZP_Cug7dXXrcpmKN53J/view?usp=sharing

---

##🖼️ Screenshots
UI
<img width="1012" height="474" alt="image" src="https://github.com/user-attachments/assets/87797103-0644-45ce-bd62-fba67e66e9c7" />

Examples

<img width="1832" height="800" alt="image" src="https://github.com/user-attachments/assets/0d4c8cb4-8b96-4f19-b944-d3f171ddc93b" />

<img width="1822" height="781" alt="image" src="https://github.com/user-attachments/assets/5ed1ebdd-f412-475e-af52-839d416a5cd2" />
<img width="1832" height="797" alt="image" src="https://github.com/user-attachments/assets/0149c143-8bae-4f94-907f-67b03d599f49" />

<img width="1248" height="799" alt="image" src="https://github.com/user-attachments/assets/1870f430-ee18-4fe0-998c-26bd9be5ef4d" />





📁 Repository Structure
app.py — main Gradio application
requirements.txt — dependencies
assets/screenshots/ — UI + example screenshots
notebooks/DIP.ipynb — notebook version (optional)


✅ Notes
If you run on Colab, use --share to get a public Gradio link.
The full demo video is attached in Releases to keep the repository lightweight.


---

```md
## 🚀 Run Locally



```bash
pip install -r requirements.txt
python app.py

```md
## ▶️ Run on Google Colab

```python
!pip install -r requirements.txt
!python app.py --share
