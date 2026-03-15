#  UiPath Hava Durumu Asistanı

Bu proje, RPA (Robotik Süreç Otomasyonu) dünyasına adım atarken yaptığım, kullanıcı etkileşimli bir web otomasyonudur.

##  Bot Nasıl Çalışıyor?
* **Şehir Seçimi:** Kullanıcıdan bir şehir seçmesi bekleniyor.
* **Otomatik Sorgu:** Tarayıcıyı açıp Google üzerinden o şehrin hava durumunu aratıyor.
* **Veri Çekme:** Web sayfasındaki sıcaklık bilgisini "Data Scraping" yöntemiyle yakalıyor.
* **Geri Bildirim:** Elde edilen veriyi bir mesaj kutusuyla kullanıcıya sunuyor.

##  Teknik Özellikler
* **Platform:** UiPath Studio
* **Yöntem:** Web Automation & Web Scraping
* **Dosya Yapısı:** Modüler ve `.gitignore` ile optimize edilmiş yapı.

##  Nasıl Çalıştırılır?

Bu projeyi kendi bilgisayarınızda denemek isterseniz:

1. Depoyu bilgisayarınıza indirin veya klonlayın.
2. Bilgisayarınızda **UiPath Studio**'nun kurulu olduğundan emin olun.
3. Klasör içindeki `project.json` dosyasını UiPath Studio ile açın.
4. `Main.xaml` dosyasını açıp **"Run"** butonuna basarak botu başlatabilirsiniz.

*Not: Bot Google Chrome üzerinde çalıştığı için Chrome tarayıcınızın güncel olması ve UiPath uzantısının etkin olması önerilir.*
