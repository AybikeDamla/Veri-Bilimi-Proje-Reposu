# 🌙 Uyku Kalitesi ve Yaşam Tarzı Analizi (Makine Öğrenmesi Projesi)

Bu proje, 2025-2026 Bahar dönemi Veri Bilimi dersi final projesi kapsamında "Vibe Coding" metodolojisi kullanılarak geliştirilmiştir. Çalışmada bireylerin yaşam tarzı ve fizyolojik verileri incelenerek, uyku bozukluklarının (Sleep Apnea, Insomnia) tahmin edilmesine yönelik bir makine öğrenmesi modeli inşa edilmiştir.

## 👨‍💻 Proje Ekibi
* **Adı Soyadı:** Damla [Soyadını Buraya Yaz]
* **Öğrenci Numarası:** [Öğrenci Numaranı Buraya Yaz]
* **Bölüm:** Bilgisayar Mühendisliği

## 🗂️ Veri Kaynağı ve Lisans
* **Veri Seti Adı:** Sleep Health and Lifestyle Dataset
* **Kaynak:** Kaggle
* **Veri Seti Lisansı:** Kaggle CC0: Public Domain (Açık Kamu Malı Lisansı)
* **Kaynak Kod Lisansı:** MIT License - Bu repodaki veri ön işleme ve makine öğrenmesi kodları MIT lisansı altında açık kaynak olarak paylaşılmıştır.


## 🛠️ Kullanılan Kütüphaneler
Projenin geliştirilme sürecinde aşağıdaki Python kütüphanelerinden faydalanılmıştır:
* `pandas` (Veri manipülasyonu ve ön işleme)
* `numpy` (Matematiksel ve dizisel işlemler)
* `matplotlib` & `seaborn` (Keşifsel veri analizi ve çok boyutlu görselleştirme)
* `scikit-learn` (Makine öğrenmesi modellemesi ve performans ölçümü)

## 🚀 Projeyi Çalıştırma Talimatları
Projeyi yerel ortamınızda veya Google Colab üzerinde sorunsuz bir şekilde çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

### Seçenek A: Google Colab Üzerinde Çalıştırma (Önerilen)
1. Bu repoda bulunan `uyku_kalitesi_analizi.ipynb` (kendi dosya adını yazarsın) dosyasını indirin.
2. [Google Colab](https://colab.research.google.com/) adresine gidin ve `Dosya > Notebook Yükle` seçeneği ile indirdiğiniz dosyayı açın.
3. Repoda bulunan `sleep_data.csv` veri setini bilgisayarınıza indirin ve Colab'in sol tarafındaki klasör (Dosyalar) sekmesine sürükleyip bırakın.
4. Üst menüden `Çalışma Zamanı > Tümünü Çalıştır` seçeneğine tıklayarak tüm analizi baştan sona inceleyebilirsiniz.

### Seçenek B: Yerel Bilgisayarda (Jupyter Notebook) Çalıştırma
1. **Depoyu Klonlayın:**
   ```bash
   git clone https://github.com/AybikeDamla/Veri-Bilimi-Proje-Reposu.git

 Kütüphaneleri Yükleyin: Sisteminizde eksik kütüphane varsa terminal üzerinden yükleyin:

   ```Bash
   pip install pandas numpy matplotlib seaborn scikit-learn

Veri Seti Konumu: sleep_data.csv dosyasının .ipynb dosyası ile aynı dizinde olduğundan emin olun.

Notebook'u Başlatın: Terminale jupyter notebook yazarak projeyi tarayıcınızda açın ve hücreleri sırasıyla çalıştırın.