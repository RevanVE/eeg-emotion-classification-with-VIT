# EEG Emotion Classification

## Deskripsi
Repository ini berisi implementasi sistem klasifikasi emosi berbasis sinyal **Electroencephalogram (EEG)** menggunakan pendekatan **deep learning** dengan framework **PyTorch**.  
Proses yang dilakukan meliputi preprocessing sinyal EEG menggunakan transformasi wavelet, pembentukan dataset, pelatihan model neural network, serta evaluasi performa model menggunakan metrik klasifikasi.

Project ini dikembangkan sebagai bagian dari kegiatan **Program Kreativitas Mahasiswa (PKM)** dan difokuskan pada eksperimen serta analisis performa model pembelajaran mesin.

---

## Fitur
- Preprocessing sinyal EEG menggunakan Wavelet Transform
- Pengelolaan dataset menggunakan PyTorch `Dataset` dan `DataLoader`
- Training model neural network berbasis PyTorch
- Optimizer dan learning rate scheduler yang dapat dikonfigurasi
- Evaluasi performa model (Accuracy, Confusion Matrix, Classification Report)
- Visualisasi hasil training dan evaluasi

---

## Persyaratan
- Python **3.8** atau lebih baru
- **Jupyter Notebook** (opsional)
- Sistem operasi **Windows / Linux / macOS**

---

## Instalasi dan Virtual Environment

```bash
git clone https://github.com/RevanVE/eeg-emotion-classification-with-VIT.git
cd eeg-emotion-classification-with-VIT

python -m venv .venv
# aktifkan virtual environment
# Windows: .\.venv\Scripts\Activate.ps1
# Linux/macOS: source .venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt
