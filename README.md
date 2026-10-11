# ⚡ Zabbix Ops

Bu depo; kurumsal ağ altyapıları, UPS/güç sistemleri, güvenlik duvarları, switch'ler ve kritik servisler için geliştirilmiş özel **Zabbix Şablonları (Templates)**, otomasyon script'leri ve operasyonel araçları tek bir merkezi çat altında toplamak için oluşturulmuştur.

---

## 📂 Depo Yapısı ve İçerikler

Depo genel olarak aşağıdaki modüler yapıyı barındırır:

- **`/templates`**: Farklı donanım ve yazılımlar için optimize edilmiş, üretim ortamına (Production) hazır YAML formatındaki Zabbix şablonları.
- **`/scripts`**: Zabbix dış kaynaklı yoklamalar (External checks), alert webhook'ları veya otomasyon betikleri.
- **`/docs`**: Kurulum rehberleri, OID haritaları ve operasyonel notlar.

---

## 🚀 Mevcut Şablonlar

### 1. Fortinet FortiSwitch SNMP (`FortiSwitchTemplate.yaml`)
- **Açıklama:** FortiSwitch cihazları için donanım sağlığı (fan, PSU, sıcaklık), CPU/RAM/Disk, SFP optik değerleri (DOM RX/TX güç) ve PSU sayısına göre akıllı arayüz keşfini içeren kapsamlı şablon.
- **Desteklenen Sürümler:** Zabbix 7.4+
- **Öne Çıkanlar:** Entegre Dashboard, gelişmiş LLD filtreleri ve PoE takibi.

### 2. Generic UPS SNMP (PowerWalker / Megatec / RFC 1628) (`GenericUPSTemplate.yaml`)
- **Açıklama:** Standart RFC 1628 ve özel Megatec enterprise OID'lerini hibrit kullanan, tek fazlı ve üç fazlı (R, S, T) yapıları otomatik algılayan (LLD) gelişmiş UPS izleme şablonu.
- **Desteklenen Sürümler:** Zabbix 7.4+
- **Öne Çıkanlar:** Akü kapasitesi/sıcaklığı, faz gerilimleri, bypass ve yük alarmları.

---

## 🛠️ Genel Standartlar

- **Format:** Tüm şablonlar modern Zabbix standartlarına uygun olarak **YAML** formatında dışarı aktarılmıştır.
- **Adlandırma Kuralı:** Servis/Donanım odaklı ve versiyon takipli isimlendirme.

---

## ✍️ Yazar & İletişim
**Burak Akbayrak**

---
*Yapay Zeka Gemini yardımıyla hazırlanmıştır.*
