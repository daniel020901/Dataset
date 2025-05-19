# Proyek Klasifikasi Cats vs Dogs

## Latar Belakang
Model CNN ini dibuat untuk mengklasifikasikan gambar kucing dan anjing menggunakan dataset `cats_vs_dogs` dari TensorFlow Datasets.

## Tujuan
- Melatih model dengan augmentasi data agar akurasi lebih baik.
- Menyimpan model dalam format SavedModel, TFLite, dan TFJS untuk berbagai platform.

## Struktur Folder
submission <br>
├───tfjs_model <br>
| ├───group1-shard1of1.bin <br>
| └───model.json <br>
├───tflite <br>
| ├───model.tflite <br>
| └───label.txt <br>
├───saved_model <br>
| └───assets <br>
| ├───saved_model.pb <br>
| └───variables <br>
├───notebook.ipynb <br>
├───README.md <br>
└───requirements.txt <br>
<br>

## Cara Install Dependencies
```bash
pip install -r requirements.txt
