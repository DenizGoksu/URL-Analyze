# URL Güvenlik Analiz ve İstihbarat Aracı

Bu proje, şüpheli bağlantıların (URL) güvenlik yapısını incelemek ve hedef sunucular hakkında teknik bilgi toplamak amacıyla geliştirilmiş terminal tabanlı bir analiz aracıdır.

# Özellikler
- Güvenlik Denetimi: URL yapısındaki oltalama (phishing) belirtilerini ve protokol eksikliklerini analiz eder.
- Sunucu İstihbaratı: Hedef alan adının IP adresini, bulunduğu ülkeyi ve servis sağlayıcısını (ISP) anlık olarak sorgular.
- Modern CLI: `Rich` kütüphanesi kullanarak terminal üzerinde görselleştirilmiş tablolar ve süreç çubukları sunar.

# Kurulum ve Kullanım

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install rich requests
2. Uygulamayı Çalıştırın:
   ```bash
   python3 WebGuard.py
