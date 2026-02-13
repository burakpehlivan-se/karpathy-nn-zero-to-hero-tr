# 🧠 Neural Networks: Zero to Hero (Türkçe Açıklamalı)

Bu depo, Andrej Karpathy'nin efsanevi **"Neural Networks: Zero to Hero"** video serisi için hazırladığım detaylı Türkçe notları, kod açıklamalarını ve yeniden oluşturulmuş implementasyonları içerir.

Amacım, "Micrograd" ile başlayıp "GPT-2" ve "Reasoning Models"e kadar uzanan bu yolculuğu, Türkçe kaynak arayanlar için anlaşılır, kapsamlı ve eğitici bir rehber haline getirmektir.

## 🚀 İçerik ve İlerleme Durumu

Bu proje, orijinal oynatma listesindeki sırayı takip etmektedir.

| Bölüm | Konu | Orijinal Ders | Türkçe Notlar | Durum |
| :--- | :--- | :---: | :---: | :---: |
| **01** | **Micrograd:** Autograd Motoru ve Backpropagation | [Video](https://youtu.be/VMj-3S1tku0?si=5rrYqRZgOwv05eNt) | [İncele](./01_micrograd/) | ✅ Tamamlandı |
| **02** | **Makemore 1:** Bigram (İkili) Dil Modelleri | [Video](https://youtu.be/PaCmpygFfXo?si=u4T45UwGYyv1POIo) | - | ⏳ Bekleniyor |
| **03** | **Makemore 2:** MLP (Multi-Layer Perceptron) | [Video](https://youtu.be/TCH_1BHY58I?si=7rmvaSXQgIg3rBUj) | - | ⏳ Bekleniyor |
| **04** | **Makemore 3:** Batch Normalization & Internals | [Video](https://youtu.be/P6sfmUTpUmc?si=4e1Qp0iHsl90Mhay) | - | ⏳ Bekleniyor |
| **05** | **Makemore 4:** Backpropagation Ninja (Manuel Türev) | [Video](https://youtu.be/q8SA3rM6ckI?si=baT6jXkJpbyFTmYf) | - | ⏳ Bekleniyor |
| **06** | **Makemore 5:** WaveNet Mimarisi & CNN'ler | [Video](https://youtu.be/t3YJ5hKiMQ0?si=2mO9hxINaK3slCbG) | - | ⏳ Bekleniyor |
| **07** | **GPT:** Sıfırdan GPT Oluşturmak ve Transformer Mimarisi (Attention is all you need) | [Video](https://youtu.be/kCc8FmEb1nY?si=4uU7c16tJMximB_8) | - | ⏳ Bekleniyor |
| **08** | **GPT Eğitim Aşamaları:** Büyük Dil Modellerine Giriş (Teori) | [video](https://youtu.be/bZQun8Y4L2A?si=U5FYZfC43uwAESbG) | - | ⏳ Bekleniyor |
| **09** | **Tokenizer:** GPT Tokenizer (Kodlayıcı) Oluşturma | [Video](https://youtu.be/bZQun8Y4L2A?si=jf-k9GKnhfmfDaMM) | - | ⏳ Bekleniyor |
| **10** | **GPT-2:** GPT-2 (124M) Modelini Sıfırdan Eğitmek | [Video](https://youtu.be/l8pRSuU81PU) | - | ⏳ Bekleniyor |

---

## 📂 Proje Yapısı

Her bölüm, kendi klasörü altında organize edilmiştir. Bu klasörlerde Jupyter Notebook (`.ipynb`) dosyaları, ilgili veri setleri ve açıklamalar bulunur.

```text
karpathy-nn-zero-to-hero-tr/
├── 01_micrograd/          # Geriye yayılım ve türev motoru
├── 02_makemore_bigram/    # İstatistiksel dil modellemesi
├── ...
├── 09_gpt2_reproduction/  # Büyük ölçekli model eğitimi
└── requirements.txt       # Gerekli kütüphaneler

```

## 🛠️ Kurulum ve Kullanım

Notları kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz.

1. **Repoyu Klonlayın:**
```bash
git clone [https://github.com/KULLANICI_ADIN/REPO_ADIN.git](https://github.com/KULLANICI_ADIN/REPO_ADIN.git)
cd REPO_ADIN

```


2. **Gerekli Kütüphaneleri Yükleyin:**
Proje genelinde `pytorch`, `numpy`, `matplotlib`, `graphviz` ve `jupyter` kullanılmaktadır.
```bash
pip install -r requirements.txt

```


*(Not: `graphviz` için sisteminize ekstra binary kurulumu yapmanız gerekebilir.)*
3. **Notebook'u Başlatın:**
```bash
jupyter notebook

```



## 📚 Kaynakça ve Atıf

Bu çalışma tamamen **Andrej Karpathy**'nin eğitim serisine dayanmaktadır. Orijinal materyallere ve Karpathy'nin kendi repolarına aşağıdaki linklerden ulaşabilirsiniz:

* **YouTube Playlist:** [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
* **Micrograd Repo:** [github.com/karpathy/micrograd](https://github.com/karpathy/micrograd)
* **Makemore Repo:** [github.com/karpathy/makemore](https://github.com/karpathy/makemore)
* **NanoGPT Repo:** [github.com/karpathy/nanoGPT](https://github.com/karpathy/nanoGPT)
* **LLM.c Repo:** [github.com/karpathy/llm.c](https://github.com/karpathy/llm.c)

## 🤝 Katkıda Bulunma

Eğer notlarda bir hata fark ederseniz veya Türkçe çevirilerde düzeltme yapmak isterseniz, lütfen bir **Issue** açmaktan veya **Pull Request** göndermekten çekinmeyin.

---

*Hazırlayan: [Senin Adın]*

```

```
