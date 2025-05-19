# Proyek Klasifikasi Cats vs Dogs

## Latar Belakang
Model CNN ini dibuat untuk mengklasifikasikan gambar kucing dan anjing menggunakan dataset `cats_vs_dogs` dari TensorFlow Datasets.

## Tujuan
- Melatih model dengan augmentasi data agar akurasi lebih baik.
- Menyimpan model dalam format SavedModel, TFLite, dan TFJS untuk berbagai platform.

## Struktur Folder
submission
├───tfjs_model
| ├───group1-shard1of1.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───label.txt
├───saved_model
| └───assets
| ├───saved_model.pb
| └───variables
├───notebook.ipynb
├───README.md
└───requirements.txt


## Cara Install Dependencies
```bash
pip install -r requirements.txt
