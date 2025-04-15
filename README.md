# 🛡️ CloudSec Docker Lab (Elastic Stack + Grafana)

Bu proje, Docker üzerinde Elasticsearch, Kibana ve Grafana bileşenlerini içeren hafif bir **cloud güvenliği log izleme ortamı** kurar. Geliştirme ve test ortamlarında güvenlik olaylarını görselleştirmek, merkezi log yönetimi yapmak için tasarlanmıştır.

---

## 📦 Bileşenler

- **Elasticsearch**: Log verilerinin saklandığı arama ve analiz motoru.
- **Kibana**: Elasticsearch verilerinin analiz edilmesi ve görselleştirilmesi için arayüz.
- **Grafana**: Gelişmiş görselleştirme ve uyarı sistemleri.

---

## 🚀 Başlatmak için

### 1. Gerekli kurulumlar

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### 2. Klonla

```bash
git clone https://github.com/youwerejailed/cloudsec-docker-lab.git
cd cloudsec-docker-lab

📊 Kibana Nasıl Kullanılır?
Tarayıcıdan http://localhost:5601 adresine gir.

İlk kez açılıyorsa Index Pattern oluştur:

logstash-* ya da verilerinizin index adına göre giriş yap.

Discover sekmesinden logları inceleyebilirsin.

Not: Log verisi alımı için Logstash, Filebeat ya da manuel veri gönderimi gerekir.


🧠 Gelecek Planlar
Falco veya Wazuh gibi gerçek zamanlı IDS entegrasyonu

Sysmon ile Windows logları toplamak

Sentinel / Suricata gibi SIEM/IDS araçları eklemek



