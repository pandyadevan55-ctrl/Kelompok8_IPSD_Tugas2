# Klasifikasi Foto Kulit Mpox dengan CNN

## Deskripsi
Proyek ini merupakan implementasi klasifikasi gambar kulit menggunakan metode **Convolutional Neural Network (CNN)** dengan PyTorch.

Model digunakan untuk mengklasifikasikan gambar ke dalam 6 kelas:
- Chickenpox
- Cowpox
- HFMD
- Healthy
- Measles
- Monkeypox

## Dataset
Dataset yang digunakan adalah Mpox Skin Lesion Dataset Version 2.0 (MSLD V2.0) dari Kaggle.

Link dataset: [Mpox Skin Lesion Dataset](https://www.kaggle.com/datasets/joydippaul/mpox-skin-lesion-dataset-version-20-msld-v20)

## Teknologi
- Python
- PyTorch
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Struktur Folder
```text
Praktikum_W10/
├── Dataset/
├── Models/
│   └── CNN.py
├── Utils/
│   └── getData.py
├── config.py
├── cek_dataset.py
├── cek_ukuran.py
├── train.py
└── test.py
```

## Cara Menjalankan

Install library:
```bash
pip install torch opencv-python scikit-learn numpy pandas matplotlib seaborn
```

Pemeriksaan dataset:
```bash
python cek_dataset.py
```

Pemeriksaan ukuran gambar:
```bash
python cek_ukuran.py
```

Training model:
```bash
python train.py
```

Pengujian model:
```bash
python test.py
```

## Konfigurasi
- Jumlah kelas: 6
- Ukuran gambar: 100 × 100
- Batch size: 32
- Epoch: 20
- Learning rate: 0.0001
- Fold: 1–5
- Data augmentation: True

## Output
Hasil praktikum berupa model CNN, grafik training, confusion matrix, log pelatihan, dan hasil evaluasi dalam format CSV.

## Penutup
Proyek ini dibuat untuk memenuhi kegiatan Praktikum Minggu 10 mata kuliah Infrastruktur dan Platform untuk Data Sains dengan topik klasifikasi foto kulit Mpox menggunakan CNN.
