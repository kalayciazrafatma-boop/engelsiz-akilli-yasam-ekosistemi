# 🏠 Engelsiz ve Güvenli Akıllı Yaşam Ekosistemi

Yaşlı, görme/yürüme engelli veya yatağa bağımlı bireylerin evde bağımsızlığını ve güvenliğini destekleyen akıllı yaşam sistemi prototipidir.

## 📂 Klasör Yapısı ve Sorumlular
- `ai_vision/` — Yapay Zekâ ve Bilgisayarlı Görü (**Azra**)
- `hardware_sensors/` — Donanım ve Sensör Veri Akışı (**Azra & Dilara**)
- `database/` — SQL Veritabanı Şeması ve Sorgular (**Heli**)
- `backend_api/` — REST API ve Telegram Test Bildirimleri (**Meryem**)
- `monitoring_panel/` — Kullanıcı ve İzleme Paneli (**Dilara**)
- `frontend/` — Son Kullanıcı Arayüzü (**Elif**)
- `security/` — Siber Güvenlik ve Gizlilik Kontrolleri (**Yusuf**)
- `tests/` — Test Senaryoları ve Doğrulama Raporları (**Feyza**)
- `docs/` — Ortak Olay Şeması (`event_schema.json`) ve Dokümanlar

## ⚠️ Önemli Kurallar
- Gerçek kişilere ait kamera/ses kaydı ve gerçek acil servis çağrısı yapılmaz.
- Simülasyon verileri `test_mode: true` ile işaretlenir.
- Şifre ve tokenlar kesinlikle repoya yüklenmez, yerel `.env` dosyasında tutulur.