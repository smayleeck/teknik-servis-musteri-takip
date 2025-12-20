# Teknik Servis Müşteri Takip Programı


Son zamanlarda kendi ihtiyaçlarım doğrultusunda ve mevcut kullandığımız programın hem eskiliğinden olsun hem de yetersizliğinden olsun boş vakitlerimde ChatGPT, Grok ve Gemini yapay zekalarının da yardımıyla bir teknik servis müşteri takip programı geliştirdim. 

Program açıldığında, kullanacağı musteriler.db dosyasını programın bulunduğu klasöre oluşturmakta. Demo olduğu için toplamda 10 müşteri ve 10 servis kaydı oluşturulabiliyor.

### Şimdilik eklediğim özellikler
1. Müşteriler paneli
   - Müşteri kaydı ekleme, düzenleme ve silme (ve bunları kısayol tuşları ile yapabilme)
     - İsim, telefon 1, telefon 2 ve adres bilgilerini kaydetme.
     - Ana ekranda, müşteriye eklenen son servis kaydının tarihini "Son İşlem Tarihi" olarak gösterme.
     - Arama çubuğunda İsim, telefon 1, telefon 2 ve adres bilgilerinden hangisi girilirse girilsin sonuç gösterme.
2. Servis kayıtları paneli (kayıtlı müşteriye çift tıklanıldığında açılır sol panelde gizli)
   - Servis kaydı ekleme, düzenleme, silme ve hatırlatıcı ekleme (ve bunları kısayol tuşları ile yapabilme)
     - Fiş no, cihaz, marka, model, çağrı tarihi, işlem tarihi, ücret bilgilerini kaydetme.
     - Ayrıca alt panelde müşteri şikayeti ve yapılan işlem bilgilerini gösterme.
3. Hatırlatıcılar paneli
   - Servis kayıtları panelinden eklenen hatırlatıcı bu panele eklenir. Hatırlatıcı günü geldiğinde Windows bildirimi hatırlatıcı silinene kadar her dakika tetiklenir.
      - Bu paneli yapmamın temel sebebi su arıtma müşterilerinin periyodik bakımlarını takip etmek içindi. Ama periyodik klima bakımlarının da takip edilmesi için ideal.
4. Ayarlar paneli
   - Genel ayarlar paneli
     - Program adı değiştirme, 220x100 logo ekleme, program ikonu değiştirme
   - Görünüm paneli
     - Programda kullanılan (neredeyse) bütün renklere erişebilme (varsayılan renklere toplu veya tek tek döndürebilme seçeneği)
   - Veritabanı yedekleme/geri yükleme
   - Excel'den müşteri aktarımı
5. Güncel döviz kuru paneli
   - Merkez bankası verilerini alıyor.
  

### Programdan görüntüler
<img width="902" height="512" alt="image" src="https://github.com/user-attachments/assets/3f7e3dc9-bbe6-417e-b282-9c63e17d3d84" />

<img width="902" height="512" alt="image" src="https://github.com/user-attachments/assets/c0c87a8d-689a-4e0b-8bdd-2b65aff64720" />

<img width="902" height="512" alt="image" src="https://github.com/user-attachments/assets/41541137-9312-44ca-835a-ba73ab62415c" />

