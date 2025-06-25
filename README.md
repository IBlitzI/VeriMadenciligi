# Tarımsal Ürün Tavsiye Sistemi

Bu proje, tarımsal alanlarda ekilecek en uygun ürünü tahmin etmek için makine öğrenimi tabanlı bir öneri sistemi sunar. Proje kapsamında veri analizi, modelleme, çapraz doğrulama, hiperparametre optimizasyonu ve modelin son kullanıcıya sunulması adımları yer almaktadır.

## İçerik

- Veri analizi ve görselleştirme
- Veri ön işleme
- Farklı makine öğrenimi algoritmaları ile modelleme
- K-Fold çapraz doğrulama ve hiperparametre optimizasyonu
- Model kaydetme ve yükleme
- Streamlit ile kullanıcı arayüzü

## Dosya ve Klasörler

- `app.py`: Streamlit tabanlı kullanıcı arayüzü
- `Crop_Recommendation_End2End_Modeling.ipynb`: Uçtan uca modelleme, analiz ve validasyon adımlarını içeren Jupyter Notebook
- `Crop_Recommendation.ipynb`: Alternatif veya ek analizler içeren Jupyter Notebook
- `requirements.txt`: Gerekli Python paketleri
- `data/Crop_recommendation.csv`: Modelde kullanılan veri seti
- `model/`: Eğitilmiş modellerin kayıtlı halleri (`.pkl` dosyaları)

## Kurulum

1. Gerekli paketleri yükleyin:
   ```
   pip install -r requirements.txt
   ```

2. Notebook üzerinde çalışmak için Jupyter veya VS Code kullanabilirsiniz.

3. Uygulamayı başlatmak için:
   ```
   streamlit run app.py
   ```

## Kullanım

- `Crop_Recommendation_End2End_Modeling.ipynb` veya `Crop_Recommendation.ipynb` dosyası üzerinden veri analizi ve modelleme adımlarını takip edebilirsiniz.
- `app.py` dosyasını çalıştırarak kullanıcı arayüzü üzerinden toprak ve iklim parametrelerini girip öneri alabilirsiniz.

