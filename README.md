# SDG-Analyzer AI 🌍

<div align="center">
  
  ### *Yapay Zeka ve Veri Madenciliği Destekli Sürdürülebilirlik Platformu*
  
  [![GitHub stars](https://img.shields.io/github/stars/suedaurkmez/sdg-analyzer-ai?style=social)](https://github.com/suedaurkmez/sdg-analyzer-ai/stargazers)
  [![GitHub forks](https://img.shields.io/github/forks/suedaurkmez/sdg-analyzer-ai?style=social)](https://github.com/suedaurkmez/sdg-analyzer-ai/network/members)
  [![GitHub license](https://img.shields.io/github/license/suedaurkmez/sdg-analyzer-ai)](https://github.com/suedaurkmez/sdg-analyzer-ai/blob/main/LICENSE)
  
</div>

---

## 📋 **Proje Hakkında**

Bu proje, kurumsal raporlar ve politika metinlerindeki karmaşık verileri **Doğal Dil İşleme (NLP)** teknikleriyle analiz ederek Birleşmiş Milletler **Sürdürülebilir Kalkınma Amaçları (SKA)** ile otomatik olarak eşleştiren yapay zeka destekli bir platformdur.

> 🎯 **Hedef:** Manuel raporlama süreçlerindeki zaman kaybını ve hata payını azaltmak, veriler arası anlamsal ilişkileri veri madenciliği yöntemleriyle ortaya koymak.

---

## ✨ **Temel Özellikler**

| Özellik | Açıklama |
|---------|----------|
| 📄 **Akıllı Doküman Analizi** | PDF, Word, metin dosyalarını otomatik analiz etme |
| 🤖 **Yapay Zeka Sınıflandırma** | BERT/RoBERTa tabanlı modellerle 17 SKA tespiti |
| 📊 **Web Dashboard** | Detaylı raporlama, görselleştirme ve arşivleme |
| 📱 **Mobil Uygulama** | OCR ile kamera üzerinden anlık analiz |
| 🔍 **Metin Karşılaştırma** | İki dokümanı yan yana karşılaştırma |
| 📈 **Veri Madenciliği** | SKA'lar arası ilişkileri keşfetme |


---

## 🎯 **Hedef Kullanıcılar**

- 🏢 **Kurumsal Sürdürülebilirlik Ofisleri** - Yıllık faaliyet raporlarını SKA'larla eşleştirme
- 🎓 **Akademik Araştırmacılar ve Öğrenciler** - Geniş metin yığınlarını hızlı sınıflandırma
- 🤝 **Sivil Toplum Kuruluşları (STK)** - Projelerin küresel amaçlarla uyumunu raporlama
- 👤 **Bireysel Denetçiler** - OCR ile fiziksel dokümanları dijital analiz etme

---

## 🛠 **Kullanılan Teknolojiler**

| Bileşen | Teknoloji |
|---------|-----------|
| **AI/Veri İşleme** | Python (Transformers, Pandas, Scikit-learn, PyTorch) |
| **Backend** | PHP/Laravel veya Python/FastAPI (Araştırma aşamasında) |
| **Veritabanı** | PostgreSQL veya MySQL |
| **Frontend/Mobil** | Flutter (Web + Mobil tek kod tabanı) |
| **Versiyon Kontrol** | Git & GitHub |
| **API** | RESTful API |
| **OCR** | Tesseract veya Google Vision API |

---

## 📊 **Veri Seti**

Proje, **OSDG Community Dataset (OSDG-CD)** üzerine inşa edilmiştir:

| Metrik | Değer |
|--------|-------|
| 📝 **Toplam Metin** | 43.210 |
| 🏷️ **Toplam Etiket** | 310.328 |
| 🎯 **SKA Hedefi** | 17 |
| 🌐 **Dil** | Çok dilli (İngilizce ağırlıklı) |

---

## 🏗️ **Proje Mimarisi**
┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐
│ Mobil Uygulama│ │ Web Dashboard │ │ 3. Parti API │
│ (Flutter) │ │ (Flutter) │ │ (Entegrasyon) │
└────────┬────────┘ └────────┬────────┘ └────────┬────────┘
└───────────────────────┼───────────────────────┘
│
┌───────▼───────┐
│ Backend API │
│(FastAPI/Laravel)│
└───────┬───────┘
│
┌──────────────────┼──────────────────┐
│ │ │
┌───────▼───────┐ ┌───────▼───────┐ ┌───────▼───────┐
│ AI Servisi │ │ Veritabanı │ │ Dosya │
│ (Python) │ │ (PostgreSQL) │ │ Depolama │
└────────────────┘ └───────────────┘ └───────────────┘

---

## 🚀 **Kurulum ve Başlangıç**

*(Kodlar yazıldıkça bu bölüm güncellenecektir)*

```bash
# Projeyi klonla
git clone https://github.com/suedaurkmez/sdg-analyzer-ai.git

# İlerleyen aşamalarda detaylı kurulum talimatları eklenecek...
