# Sunucular Sağlık Kontrol Scripti | Servers Health Check Script

Bu script, belirli aralıklarla bir veya birden fazla sunucunun sağlık durumunu kontrol eder ve sonuçları bir rapor dosyasına yazar. Ayrıca, raporu belirtilen e-posta adresine gönderir.
This script periodically checks the health status of one or more servers and writes the results to a report file. It also sends the report to the specified email address.

## Kurulum ve Kullanım | Setup and Usage

### Gereksinimler | Requirements

- mailx veya mutt gibi bir e-posta gönderim aracının kurulu olması gerekmektedir.
- The system should have a mail sending utility like mailx or mutt installed.

### Kullanım | Usage

```bash
./script_name.sh

# Sunucu Sağlık Kontrol Scripti | Server Health Check Script

Bu script, belirli bir sunucunun sağlık durumunu kontrol etmek için ping komutunu kullanır ve yanıt süresini ölçer.
This script uses the ping command to check the health status of a specified server and measures the response time.

## Kullanım | Usage

```bash
./script_name.sh <sunucu_ip_adresi_veya_url> | ./script_name.sh <server_ip_or_url>
