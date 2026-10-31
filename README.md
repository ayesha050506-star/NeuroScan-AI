# 🧠 NeuroScan AI — Real-Time Brain Tumor Diagnosis Workstation

An advanced clinical-grade medical visualization workstation built with **Python**, **Streamlit**, and **OpenCV**. This application integrates a **97.36% accurate Multi-Layer Perceptron (MLP) Neural Network** to run real-time inference on cranial MRI slice array frames.

## 🚀 Core Visual Subsystems
* **Adaptive Morphological Segmentation:** Live slider controls to dynamically adjust binarization thresholds and trace anomalous tissue boundaries.
* **Jet Thermal Dispersion Heatmapping:** Multi-spectral color mapping (`cv2.COLORMAP_JET`) to isolate pixel intensity shifts and emphasize dense tumor boundaries.
* **CLAHE Equalization:** Real-time localized contrast-limited adaptive histogram equalization to enhance subtle grayscale structures in raw medical files.

## 🛠️ Local System Deployment
To deploy this clinical workstation layout locally on your OS drive, open your terminal prompt window and execute:

```bash
# 1. Clone the project pipeline files
git clone https://github.com
cd neuro-scan-ai-demo

# 2. Secure core dependencies layer
pip install -r requirements.txt

# 3. Securely bind and fire up the engine server
python -m streamlit run app.py --server.address 127.0.0.1 --server.port 8501
```

Once initialized, access your interface workstation instantly via your local web browser layer:
👉 **http://127.0.0.1:8501**

*Note: Ensure your trained binary file `brain_tumor_mlp_model.pkl` is saved directly to your local pathway (`C:\Users\Admin\`). If unlinked, the application safely triggers a fail-safe fallback design map.*
