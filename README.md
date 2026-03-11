# 🧠 DeepVision-Cifar10: Image Classification with CNN

Bu proje, Bilgisayar Mühendisliği 3. sınıf "Haftalık Gelişim" serimizin ilk projesidir. 
CIFAR-10 veri setini kullanarak 10 farklı nesne sınıfını (uçak, otomobil, kedi vb.) 
tanıyabilen bir Evrişimli Sinir Ağı (CNN) modelidir.

## 🚀 Özellikler
* **Model:** Convolutional Neural Network (CNN)
* **Kütüphaneler:** TensorFlow, Keras, Matplotlib, NumPy
* **Veri Seti:** CIFAR-10 (60,000 görsel, 10 sınıf)
* **Ortam:** Google Colab (T4 GPU)

## 📊 Model Mimarisi
Model, özellik çıkarımı için 3 adet Evrişim (Conv2D) ve Havuzlama (MaxPooling) katmanından, 
karar mekanizması için ise Tam Bağlantılı (Dense) katmanlardan oluşmaktadır.

## 📈 Başarı Grafiği
Eğitim sürecindeki doğruluk (accuracy) ve hata (loss) değerleri:
![Training Accuracy](./dlgrafik.png) 


## 🛠️ Nasıl Çalıştırılır?
1. Repo'yu klonlayın: `git clone <repo-url>`
2. Gerekli kütüphaneleri kurun: `pip install tensorflow matplotlib numpy`
3. `main.py` dosyasını çalıştırın.


