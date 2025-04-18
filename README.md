# 🧠 Discord Atık Türü Tanıma Yapay Zekası

Bu proje, bir yapay zeka modeli kullanarak **atık türlerini ayırt etmeyi** amaçlamaktadır. Model, dört farklı sınıfa ait atıkları tanımlayabilir:

- 🧴 Plastik  
- 📰 Kağıt  
- 🍾 Cam  
- 🔋 Pil  

Model, `keras_model.h5` dosyasında yer almakta olup, sınıf isimleri `labels.txt` dosyasında sıralanmıştır.

## 🚀 Projeyi Çalıştırmak İçin

### Gereksinimler

Aşağıdaki Python kütüphanelerinin kurulu olması gerekir:

```bash
pip install keras pillow numpy
