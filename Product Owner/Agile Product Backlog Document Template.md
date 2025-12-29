# **Product Backlog Item (PBI) / Kullanıcı Hikayesi Şablonu**
## **Temel Kimlik ve Takip**
- **PBI ID:** `PB-001` (Otomatik veya El ile)
- **Başlık:** [Kullanıcı perspektifinden, anlaşılır ve kısa bir cümle. Örn: "Müşteri olarak, ürünü sepete ekleyebilmeliyim."]
- **Tür:** [Özellik / Bug / Teknik Borç / İyileştirme / Araştırma]
- **Durum:** [Fikir → Backlog → Hazır → Yapılıyor → Test → Tamamlandı]
- **İlgili Epic:** [Varsa, bağlı olduğu büyük özelliğin adı veya ID'si]
- **Bağlantılar / Referans:** [İlgili tasarım, analiz dokümanı veya ticket bağlantısı]

## **Değer ve Planlama**
- **İş Değeri (Business Value):** [1-10 arası, ürüne/stratejiye katkısı]
- **Öncelik (Priority):** [1 (En Yüksek) - 10 (En Düşük) veya "Yüksek/Orta/Düşük"]
- **Tahmin (Estimate):** [Story Point (1,2,3,5,8,13...) veya Gün cinsinden]
- **Planlanan Sprint:** [Sprint #X veya "Belirsiz"]

## **Açıklama ve Kriterler**
### **Açıklama (Description):**  
    _"Bir [Kullanıcı Rolü] olarak, [Bir İhtiyacım / Amacım] sayesinde [Bir Fayda / Değer] elde etmek istiyorum."_  
    [İş ve kullanıcı bağlamını özetleyen bir veya iki paragraf.]
    
### **Kabul Kriterleri (Acceptance Criteria - AC):** [**ZORUNLU**]  
    _Bu madde ne zaman "Tamamlandı" kabul edilir?_
    1. Kriter 1: [Ölçülebilir ve test edilebilir bir koşul].
    2. Kriter 2: [Örn: "Sepetteki ürün sayısı artmalı", "Hata mesajı gösterilmeli"].
    3. Kriter 3: [Performans, güvenlik veya tasarımla ilgili bir gereklilik].
- **Bağımlılıklar (Dependencies):** [**ÖNEMLİ EKLEME**]  
    _Bu madde başlamadan veya tamamlanmadan önce ne gerekiyor?_
    - [Örn: "PB-015'in tamamlanması gerekiyor", "API dokümantasyonu hazır olmalı", "Tasarım onayı bekleniyor"].
        

## **Geliştirme ve Test Detayları**
- **Notlar / Teknik Detaylar:** [Geliştirici için gereken API endpoint'leri, veri modelleri veya mimari kararlar].
- **Test Senaryosu Özeti:** [Testçi için; hangi senaryoların test edileceğinin ana hatları].
- **Demo Talimatı:** [Bu özellik Sprint Review'de nasıl demo edilecek? 1-2 cümle].

---

## **Değişiklik Günlüğü (Changelog)**

|Tarih|Versiyon|Değişiklik Yapan|Açıklama|
|---|---|---|---|
|[Tarih]|1.0|[İsim]|İlk oluşturulma|
|[Tarih]|1.1|[İsim]|Kabul kriterleri eklendi|