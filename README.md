# ⚡ Zabbix Ops

Bu depo; kurumsal ağ altyapıları, UPS/güç sistemleri, sanallaştırma katmanları ve kritik servisler için geliştirilmiş özel **Zabbix Şablonları (Templates)**, otomasyon script'leri ve operasyonel araçları tek bir merkezi çat altında toplamak için oluşturulmuştur.

---

## 📂 Depo Yapısı ve İçerikler

Depo genel olarak aşağıdaki modüler yapıyı ve bileşenleri barındırır:

- **`/templates`**: Farklı donanım ve yazılımlar için optimize edilmiş, üretim ortamına (Production) hazır YAML formatındaki Zabbix şablonları.
- **`/scripts`**: Zabbix dış kaynaklı yoklamalar (External checks), alert webhook'ları veya otomasyon betikleri.
- **`/docs`**: Kurulum rehberleri, OID haritaları ve operasyonel notlar.

---

## 🚀 Öne Çıkan Şablonlar

### 1. Generic UPS SNMP (PowerWalker / Megatec / RFC 1628)
- **Açıklama:** Standart RFC 1628 ve özel Megatec enterprise OID'lerini hibrit kullanan, tek fazlı ve üç fazlı (R, S, T) yapıları otomatik algılayan (LLD) gelişmiş UPS izleme şablonu.
- **Desteklenen Sürümler:** Zabbix 7.4+
- **Detaylar:** Akü durumu, sıcaklık, faz gerilimleri, frekanslar, bypass ve yük alarmları dahildir.

---

## 🛠️ Genel Kullanım & Standartlar

- **Format:** Tüm şablonlar modern Zabbix standartlarına uygun olarak **YAML** formatında dışarı aktarılmıştır.
- **Adlandırma Kuralı:** Servis/Donanım odaklı ve versiyon takipli isimlendirme (`[Kategori]-[Cihaz/Servis]-[Protokol]`).

---

## ✍️ Yazar & İletişim
**Burak Akbayrak**

---
*Yapay Zeka Gemini yardımıyla hazırlanmıştır.*
