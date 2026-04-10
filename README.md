# 🐾 Responsi Praktikum Kecerdasan Buatan 2026

## Deskripsi
Model klasifikasi hewan (kucing, anjing, hewan liar) menggunakan CNN dengan PyTorch.
Dataset: [Animal Faces - Kaggle](https://www.kaggle.com/datasets/andrewmvd/animal-faces)

## Demo Web
🌐 [Coba disini!](https://huggingface.co/spaces/zahra7272/animal-classifier)

## Hasil Optimasi
- Test Accuracy: **98.43%**
- Masalah awal: Overfitting (selisih train-val ~13%)
- Setelah optimasi: Good Fit (selisih train-val ~1-2%)

## Teknik Optimasi
- Data Augmentation
- Dropout (0.5 & 0.3)
- Batch Normalization
- Early Stopping
- ReduceLROnPlateau
- Weight Decay

## Cara Jalankan
Buka notebook `RESPONSI_AI.ipynb` di Google Colab
