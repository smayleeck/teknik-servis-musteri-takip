# Teknik Servis Müşteri Takip Programı


Son zamanlarda kendi ihtiyaçlarım doğrultusunda ve mevcut kullandığımız programın hem eskiliğinden olsun hem de yetersizliğinden olsun boş vakitlerimde ChatGPT, Grok ve Gemini yapay zekalarının da yardımıyla bir teknik servis müşteri takip programı geliştirdim. 

Program açıldığında, kullanacağı musteriler.db dosyasını programın bulunduğu klasöre oluşturmakta. Hem yaptığım çeşitli geliştirmeleri takip etmek için hem de bir şekilde işine yarayanların kullanımına sunmak için burayı kullanmayı düşünüyorum.

### Şimdilik eklediğim özellikler
1. Müşteriler paneli
   - Müşteri kaydı ekleme, düzenleme ve silme (ve bunları kısayol tuşları ile yapabilme)
     - İsim, telefon 1, telefon 2 ve adres bilgilerini kaydetme.
2. Servis kayıtları paneli (kayıtlı müşteriye çift tıklanıldığında açılır sol panelde gizli)
   - Servis kaydı ekleme, düzenleme, silme ve hatırlatıcı ekleme (ve bunları kısayol tuşları ile yapabilme)
     - Fiş no, cihaz, marka, model, çağrı tarihi, işlem tarihi, ücret bilgilerini kaydetme.
     - Ayrıca alt panelde müşteri şikayeti ve yapılan işlem bilgilerini gösterme.
3. Hatırlatıcılar paneli
   - Servis kayıtları panelinden eklenen hatırlatıcı bu panele eklenir. Hatırlatıcı günü geldiğinde Windows bildirimi hatırlatıcı silinene kadar her dakika tetiklenir.
      - Bu paneli yapmamın temel sebebi su arıtma müşterilerinin periyodik bakımlarını takip etmek içindi. Ama periyodik klima bakımlarının da takip edilmesi için ideal.
4. Ayarlar paneli
   - Genel ayarlar panelinden program adı değiştirme, 220x100 logo ekleme, programda ve açılan pencerelerdeki ikonu değiştirme
   - Görünüm panelinden programda kullanılan bütün renklere erişebilme (varsayılan renklere toplu veya tek tek döndürebilme seçeneği)
   - Veritabanı yedekleme/geri yükleme
   - (Eğer yedeğiniz var ise) Excel'den müşteri aktarımı
5. Güncel döviz kuru paneli
   - Merkez bankası verilerini alıyor.
