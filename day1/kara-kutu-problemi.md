# 🤖 Yapay Zeka (YZ) Kara Kutu Problemi / AI Black Box Problem

---

## 🇹🇷 Türkçe

### 🎬 Video Özeti
Kara Kutu Problemi, bir yapay zeka algoritmasının (özellikle Derin Öğrenme modelleri) nasıl çalıştığını tam olarak bilemememizi ifade eder. Model, karmaşık girdiler alır ve bir çıktı üretir; ancak bu süreç gizli kalır.  

**Video Önerisi:** [Yapay Zekada Kara Kutu Problemi Videosu](#)

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

## 🇬🇧 English

### 🎬 Video Summary
The Black Box Problem refers to the lack of transparency in AI algorithms (especially Deep Learning models). The model takes complex inputs and produces an output, but the process remains hidden.  

**Video Suggestion:** [AI Black Box Problem Video](#)

---

### 🔍 Definition and Origin
- **Black Box Problem:** AI algorithms take inputs and produce outputs, but it’s impossible to understand internally how they reach that output.  
- **Deep Learning:** Neural networks work with hundreds of layers and trillions of parameters, each contributing to the decision; tracking all interactions with human logic is impossible.  
- **Non-Linear Relationships:** Models learn complex relationships between data that cannot be expressed as simple “if-then” rules.

---

### ⚖️ Ethical and Practical Risks
- **Trust and Responsibility:** When a system makes a wrong decision, lack of explanation reduces trust and raises legal issues.  
- **Bias Detection:** If a model reflects biases in training data, it is difficult to detect and correct discriminatory decisions.  
- **Debugging:** Complex network structures make it almost impossible to trace the source of unexpected outputs.

---

### ✅ 2025 Status: Solutions (Explainable AI - XAI)
Although the Black Box Problem continues, Explainable AI (XAI) makes AI decisions more interpretable.  

| Method | What It Does | Example |
|--------|-------------|--------|
| **Feature Importance (SHAP/LIME)** | Shows which input features the model emphasizes | Real estate AI gives 70% weight to “school rating” and “square meters” |
| **Attention Maps** | Visualizes which parts of input the model focuses on | Facial recognition AI focuses only on the “eye area” and “nose” |
| **Post-Hoc Explanation** | Provides a human-understandable justification after the decision | AI flags a patient as high-risk and cites “low blood pressure and high cholesterol” |
