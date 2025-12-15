# 🤖 Yapay Zeka (YZ) Kara Kutu Problemi / AI Black Box Problem

---

## 🇹🇷 Türkçe

### 🎬 Video Özeti
Kara Kutu Problemi, bir yapay zeka algoritmasının (özellikle Derin Öğrenme modelleri) nasıl çalıştığını tam olarak bilemememizi ifade eder. Model, karmaşık girdiler alır ve bir çıktı üretir; ancak bu süreç gizli kalır.  

**Video Önerisi:** [Yapay Zekada Kara Kutu Problemi Videosu](https://www.youtube.com/shorts/jOKMXPI1ano)

---

### 🔍 Problemin Tanımı ve Kökeni
- **Kara Kutu Problemi:** YZ algoritmaları girdileri alıp çıktı üretir, fakat bu çıktıya nasıl ulaştığı içeriden anlaşılamaz.  
- **Derin Öğrenme:** YSA’lar yüzlerce katman ve trilyonlarca ağırlık ile çalışır. Bu parametrelerin her biri karara katkıda bulunur; ancak tüm etkileşimi insan mantığıyla takip etmek mümkün değildir.  
- **Doğrusal Olmayan İlişkiler:** Model, veriler arasındaki karmaşık ilişkileri öğrenir; basit “eğer-o zaman” kurallarıyla açıklanamaz.

---

### ⚖️ Etik ve Pratik Riskler
- **Güven ve Sorumluluk:** Hatalı karar durumunda sistemin açıklama yapamaması, güven ve hukuki sorumluluk sorunları yaratır.  
- **Önyargı Tespiti:** Model eğitim verilerindeki önyargıları yansıtıyorsa, bu ayrımcı kararın nedenini tespit etmek zordur.  
- **Hata Ayıklama (Debugging):** Karmaşık ağ yapısı, yanlış çıktı durumunda sorunun kaynağını bulmayı zorlaştırır.

---

### ✅ 2025 Durumu: Çözüm Yolları (Açıklanabilir YZ - XAI)
Kara Kutu Problemi devam etse de, Açıklanabilir Yapay Zeka (eXplainable AI - XAI) ile kararlar daha anlaşılır hale gelmektedir.  

| Yöntem | Ne Yapar? | Örnek |
|--------|-----------|-------|
| **Özellik Önemi (SHAP/LIME)** | Modelin hangi girdi özelliklerine ağırlık verdiğini gösterir | Emlak YZ’si, fiyat tahmininde “okul puanı” ve “metrekare”ye %70 ağırlık verir |
| **Dikkat Haritaları (Attention Maps)** | Görsel/metinsel verilerde modelin hangi bölümlere odaklandığını gösterir | Yüz tanıma YZ’si, sadece “göz çevresi” ve “burun” kısmına odaklanır |
| **Post-Hoc Gerekçelendirme** | Model karar verdikten sonra basit, anlaşılır gerekçe sunar | YZ, hastanın riskli olduğunu bildirir ve gerekçe olarak “düşük tansiyon ve yüksek kolesterol” sunar |

---

