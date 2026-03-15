# 📊 Mühendisler İçin Olasılık

**Haydar Kılıç · Yapay Zeka Mühendisliği**

Bu repo, **Mühendisler İçin Olasılık** dersine ait interaktif Jupyter Notebook materyallerini içermektedir. Her ders; teorik altyapı, Python uygulamaları, görselleştirmeler ve alıştırmalardan oluşan kendi kendine yetkin bir notebook olarak sunulmaktadır.

---

## 📚 Ders İçerikleri

| # | Notebook | Konular | Temel Kavramlar |
|---|----------|---------|-----------------|
| 1 | `Bolum1_Kombinatoryal_Analiz.ipynb` | Temel Sayma Kuralı, Permütasyonlar, Kombinasyonlar, Çok Terimli Katsayılar | $n!$, $P(n,r)$, $\binom{n}{r}$, çok terimli teorem |
| 2 | `Bolum2_Olasilik_Aksiyomlari.ipynb` | Örneklem Uzayı ve Olaylar, Küme İşlemleri, DeMorgan Yasaları, Kolmogorov Aksiyomları, İçerme-Dışlama, Doğum Günü Problemi | $P(A)$, $A^c$, $A \cup B$, $A \cap B$ |
| 3 | `Bolum3_Kosullu_Olasilik.ipynb` | Koşullu Olasılık, Çarpma Kuralı, Toplam Olasılık Yasası, Bayes Teoremi, Bağımsız Olaylar, Karşılıklı Bağımsızlık | $P(A \mid B)$, $P(A \cap B)$, Bayes |
| 4 | `Bolum4_Kesikli_Rasgele_Degiskenler.ipynb` | Rasgele Değişken Tanımı, KDF, OKF, Beklenen Değer, Varyans, Bernoulli, Binom, Poisson, Geometrik, Negatif Binom | $E[X]$, $\text{Var}(X)$, $\text{Bin}(n,p)$, $\text{Poi}(\lambda)$ |
| 5 | `Bolum5_Surekli_Rastgele_Degiskenler.ipynb` | OYF, DDF, Beklenen Değer ve Varyans, Düzgün Dağılım, Normal Dağılım, z-Dönüşümü, Binom Yaklaşımı, Fonksiyon Dağılımı | $f(x)$, $F(x)$, $\mathcal{N}(\mu, \sigma^2)$, $z$-skoru |
| 6 | `Bolum6_BirlikteDagilimliRD.ipynb` | Birleşik DDF, Ayrık/Sürekli Birleşik Dağılım, Marjinal ve Koşullu Dağılımlar, Bağımsız RDV, Konvolüsyon | $F_{X,Y}(x,y)$, $f_{X \mid Y}$, konvolüsyon |
| 7 | `Bolum7_Beklenen_Deger_Ozellikleri.ipynb` | $g(X,Y)$'nin Beklentisi, Beklenti Doğrusallığı, Çarpım Beklentisi, Kovaryans, Korelasyon, Koşullu Beklenti, Koşullu Varyans, Moment Üreten Fonksiyonlar | $E[XY]$, $\text{Cov}(X,Y)$, $\rho$, MÜF |
---

## 🗂️ Repo Yapısı

```
olasilik/
│
├── README.md
├── requirements.txt
│
├── Bolum1_Kombinatoryal_Analiz.ipynb
├── Bolum2_Olasilik_Aksiyomlari.ipynb
├── Bolum3_Kosullu_Olasilik.ipynb
├── Bolum4_Kesikli_Rasgele_Degiskenler.ipynb
├── Bolum5_Surekli_Rastgele_Degiskenler.ipynb
├── Bolum6_BirlikteDagilimliRD.ipynb
└── Bolum7_Beklenen_Deger_Ozellikleri.ipynb
```

---

## ⚙️ Kurulum ve Çalıştırma

### Gereksinimler

- Python 3.10 veya üzeri
- JupyterLab veya Jupyter Notebook

### Ortam Kurulumu

```bash
# Repoyu klonla
git clone https://github.com/HAYDARKILIC/olasilik.git
cd olasilik

# Sanal ortam oluştur (önerilen)
python -m venv .venv
source .venv/bin/activate        # Linux / macOS
# .venv\Scripts\activate         # Windows

# Bağımlılıkları yükle
pip install -r requirements.txt

# JupyterLab'ı başlat
jupyter lab
```

---

## 📦 Kullanılan Kütüphaneler

| Kütüphane | Kullanım Amacı |
|-----------|----------------|
| `numpy` | Sayısal hesaplama, dizi işlemleri |
| `scipy` | İstatistiksel dağılımlar, özel fonksiyonlar |
| `sympy` | Sembolik matematik, türev/integral doğrulama |
| `matplotlib` | Grafik ve görselleştirme |
| `itertools` | Kombinatoryal üretim (permütasyon, kombinasyon) |
| `collections` | Frekans sayımı (`Counter`) |

---

*Haydar Kılıç, Yapay Zeka Mühendisliği*
