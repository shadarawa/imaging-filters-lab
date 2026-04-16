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

<img width="1044" height="521" alt="image" src="https://github.com/user-attachments/assets/50361c42-2dac-41ab-8dc7-cc3cbeb343fa" />
<img width="1035" height="533" alt="image" src="https://github.com/user-attachments/assets/092c3dce-dc11-4806-b9d4-00fcb89ec4e6" />
<img width="1028" height="474" alt="image" src="https://github.com/user-attachments/assets/81abae39-3da5-4831-b6ea-47ea03a1e058" />
<img width="1007" height="543" alt="image" src="https://github.com/user-attachments/assets/c18050b5-5db4-4d74-bc38-188dec30df5f" />




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
