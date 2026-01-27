# Teknik Servis Müşteri Takip Programı


Son zamanlarda kendi ihtiyaçlarım doğrultusunda ve mevcut kullandığımız programın hem eskiliğinden olsun hem de yetersizliğinden olsun boş vakitlerimde ChatGPT, Grok, Gemini ve özellikle Antigravity yapay zekalarının da yardımıyla bir teknik servis müşteri takip programı geliştirdim. 

Program açıldığında, kullanacağı dosyalar TSMTP klasörünün içine oluşturulmakta. Demo olduğu için toplamda 10 müşteri, 10 servis kaydı ve 10 ürün kaydı oluşturulabiliyor.

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
    
3. Stok Yönetimi paneli
   - Ürün kaydı ekleme, düzenleme ve silme
     - Barkod (otomatik barkod oluşturma), ürün adı, marka (listeye ekleme yapılabilir), cihaz (listeye ekleme yapılabilir), satış fiyatı bilgilerini kaydetme.
   - Stok giriş, stok çıkış, stok düzenleme ve stok silme
   - Depo Yönetimi (listeye ekleme yapılabilir)
   - Etiket Bas'tan etiket basılabilir. (Ayarlar panelinden ölçüleri ayarlanabiliyor.)
     

4. Kasa paneli
   - Güncel bakiye, günlük para giriş-çıkış kaydı ekleme.
   - Tarihler arası para giriş-çıkış kayıtlarını görme.
     
6. Hatırlatıcılar paneli
   - Servis kayıtları panelinden eklenen hatırlatıcı bu panele eklenir. Hatırlatıcı günü geldiğinde Windows bildirimi hatırlatıcı silinene kadar her dakika tetiklenir.
      - Bu paneli yapmamın temel sebebi su arıtma müşterilerinin periyodik bakımlarını takip etmek içindi. Ama periyodik klima bakımlarının da takip edilmesi için ideal.
        
7. Ayarlar paneli
   - Genel ayarlar paneli
     - Program adı değiştirme, 220x100 logo ekleme, program ikonu değiştirme
   - Görünüm paneli
     - Programda kullanılan (neredeyse) bütün renklere erişebilme (varsayılan renklere toplu veya tek tek döndürebilme seçeneği)
   - Etiket ayar paneli
     - Etiket genişliği ve yüksekliği ayarlayabilme.
     - Etikette kullanılan barkod çizgi yüksekliği ayarlayabilme.
   - Veritabanı yedekleme/geri yükleme
   - Excel'den müşteri aktarımı
   - Lisans paneli
     - Programı demo sürümden çıkarmak için gereken Makine ID ve Lisans anahtarları bölümleri bulunmakta.
   - Güncelleme paneli
     - Güncelleme geldiğinde programın exe'sini değiştirmeye gerek kalmadan, güncelleme paneli ile son sürüme yükseltme.
     
8. Güncel döviz kuru paneli
   - Merkez bankası verilerini alıyor.
  

### Programdan görüntüler

<img width="1202" height="732" alt="image" src="https://github.com/user-attachments/assets/20128301-c633-4b85-87bb-b651765edd9c" />

<img width="1202" height="732" alt="image" src="https://github.com/user-attachments/assets/3870efc6-9f92-4059-81c1-8568f1876564" />

<img width="1202" height="732" alt="image" src="https://github.com/user-attachments/assets/31d504ea-7227-475f-be2e-62edbdf8ef5e" />

<img width="1202" height="732" alt="image" src="https://github.com/user-attachments/assets/b4d15d6b-14c1-4c35-a191-123451129b67" />

<img width="1202" height="732" alt="image" src="https://github.com/user-attachments/assets/677b4041-7b31-412b-88bb-6a52e2e4dca2" />

<img width="1202" height="732" alt="image" src="https://github.com/user-attachments/assets/9859cb17-da78-4244-8de6-172d8bed7850" />

<img width="1202" height="732" alt="image" src="https://github.com/user-attachments/assets/9ca55e42-a3aa-4da4-ad14-1871dc9936ee" />







