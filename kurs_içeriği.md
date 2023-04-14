## Giriş ve Temel Kavramlar

- Sistem Programlama Nedir?
- İşletim Sistemlerinin Tarihsel Gelişimi
- Orijinal Kod Temeline Sahip Olan ve Olmayan İşletim Sistemleri
- Dağıtım (Distribution) Kavramı ve İşletim Sistemlerinin Dağıtımları
- Programlamadaki Katmanlı Yapılar
- API Kavramı
- Kütüphane ve Framework Kavramları
- CPU, Mikroişlemci, Mikrodenetleyici SOC (System on Chip) ve SBC (Single-Board Computer) Kavramları
- C'de Tanımsız Davranış, Derleyiciye Bağlı Davranış ve Belirsiz Davranış Kavramları
- C Derleyicilerinin Hata Mesajları ve Standartlara Uyum
- Kursta Kullanılacak Olan Nispeten Az Bilinen Bazı Standart C Fonksiyonları
- Geçici Dosya Kavramı ve Geçici Dosyaların Oluşturulması
- Windows, UNIX/Linux ve Mac OS X Sistemlerinde C Programlarının Derlenerek Çalıştırılması
- GNU Tarzı Komut Satırı Argümanları
- Komut Satırı Argümanlarının Ayrıştırılması
- İşletim Sistemlerinin Sistem Fonksiyonları, POSIX Fonksiyonları ve Windows API Fonksiyonları
- Proses Kavramı
- Değişkenlerin Harflandirilmesi 
- Macar Notasyonu ve Windows API Fonksiyonlarında Kullanılan typedef Tür İsimleri
- Fonksiyonlarda Hata Kontrolleri
- Windows API Fonksiyonlarının Başarısızlık Nedenlerinin Elde Edilmesi ve Rapor Edilmesi
- UNIX/Linux Sistemlerindeki POSIX Fonksiyonlarının Başarısızlık Nedenlerinin Elde Edilmesi ve Rapor Edilmesi
- C Programlarında Dosya Organizasyonu
- Handle Kavramı ve Handle Sistemleri
- Windows ve UNIX/Linux Sistemlerinde Fonksiyon Çağırma Biçimleri (Calling Conventions)
- C'de Fonksiyon Göstericilerinin Kullanımı
- Türden Bağımsız İşlem Yapabilen Fonksiyonların Tasarımı
- Göstericiyi Gösteren Göstericiler
- Dizi Göstericileri
- Göstericilere İlişkin Karmaşık Bildirimler
- Referans Yerelliği (Locality of Reference) Kavramı ve Programlamadaki Önemi

## İşletim Sistemlerinin Dosya Sistemleri 

- İşletim Sistemlerinin Dosya İşlemlerini Yapan Sistem Fonksiyonları
- Windows Sistemlerinde Temel Dosya İşlemlerini Yapan API Fonksiyonları
- UNIX/Linux Sistemlerinde Temel Dosya İşlemlerini Yapan POSIX Fonksiyonları
- Windows Sistemlerinde Dosya Özellikleri
- UNIX/Linux Sistemlerinde Dosya Özellikleri
- Windows Sistemlerinde Dosya Nesneleri ve Proseslerin Handle Tabloları
- UNIX/Linux Sistemlerinde Dosya Nesneleri ve Dosya Betimleyicilerin Anlamı
- Windows Sistemlerinde Dosya Sistemi İle İlgili Yardımcı API Fonksiyonları
- UNIX/Linux Sistemlerinde Dosya Sistemi İle İlgili Yardımcı POSIX Fonksiyonları
- Windows Sistemlerinde Dizin İçerisindeki Dosyaların Elde Edilmesi
- UNIX/Linux Sistemlerinde Dizin İçerisindeki Dosyaların Elde Edilmesi
- Dizin Değişiklerinin Otomatik Olarak İzlenmesi

## Özyinelemeli İşlemler

- Özyineleme Kavramı
- Özyinelemeli Fonksiyonlar
- Özyinelemeli Fonksiyonlara İlişkin Örnekler
- Dizin Ağacının Özyinelemeli Biçimde Dolaşılması

## Proseslerin Bellek Alanları

- Prosesin İşletim Sistemi Tarafından Yüklenmesi
- Stack Kavramı
- Proseslerin (Thread'lerin) Stack'leri
- Data ve BSS Bölümleri
- Kod (Text) Bölümleri
- Heap Kavramı ve Proseslerin Heap Organizasyonları
- Windows Sistemlerinde Heap Organizasyonı
- UNIX/Linux Sistemlerinde Heap Organizasyonu

## Bellek Sistemleri

- Birincil ve İkincil Bellekler
- RAM ve ROM Kavramları
- RAM ve ROM çeşitleri
- Hard Disklerin Genel Yapısı
- SSD Disklerin Genel Yapısı
- İkincil Belleklerden Veri Transferi
- Önbellek (Cache) Sistemleri
- Önbellek Terminolojisi
- Çok Karşılaşılan Önbellek Sistemleri
- Önbellek Sistemlerinin Tasarımı 
- C'nin Standart Dosya Fonksiyonlarınının Kullandığı Tampon (Önbellek) Mekanizması
- stdin, stdout ve stderr Dosyalarının Tamponlama Mekanizmaları

## İşlemcilerin Koruma ve Sayfalama Mekanizmaları ve Sanal Bellek Kullanımı

- İşlemcilerin Koruma Mekanizmasının Anlamı
- İşlemcilerin Bellek ve Komut Koruması
- Proseslerin Çekirdek Moduna Geçmesi ve Geri Dönmesi
- Çekirdek Modülleri ve Ayggıt Sürücülerin Anlamı
- İşlemcilerin Sayfalama Mekanizmasının Anlamı
- Sanal Bellek Kullanımı
- Proseslerarası Geçiş 

## Giriş Çıkış Yönlendirmeleri ve Boru İşlemleri

- Giriş/Çıkış Yönlendirmeleri (IO Redirection)
- Komut Satırında Boru İşlemleri

## Prosesler ve İşletim Sisteminin Proses Yönetimleri

- Zaman Paylaşımlı Çalışma Modeli
-İşletim Sistemlerinin Çizelgeleyici Alt Sistemleri
- Bloke Kavramı, Processlerin ve Thread'lerin Bloke Olması
- Çalışma Kuyrukları (Run Queues) ve Bekleme Kuyrukları (Wait Queues)
- Proseslerin Çevre Değişkenleri
- IO Yoğun ve CPU Yoğun Prosesler
- Windows'ta Proseslerin Yaratılması ve Sonlanması
- UNIX/Linux Sistemlerinde Proseslerin Yaratılması ve Sonlanması (fork ve exec işlemleri)
- Proseslerarasında Altlık-Üstlük (Parent-Child) İlişkileri
- Proseslerin Çıkış (Exit) Kodlarının Elde Edilmesi
- UNIX/Linux Sistemlerinde Hortlak (Zombie) Prosesler
- Windows ve UNIX/Linux Sistemlerinde Proses Listesinin Elde Edilmesi
- Proseslerin Kullandığı Kaynaklar

## Proseslerarası Haberleşme (Interprocess Communication)

- Proseslerarası Haberleşmenin Anlamı
- Aynı Makinenin Prosesleri Arasındaki Haberleşmelerde ve Farklı Makinelerin Prosesleri Arasındaki Haberleşmelerde Kullanılan Yöntemler
- Windows'ta Borular Yoluyla Proseslerarası Haberleşme
- UNIX/Linux Sistemlerinde Borular Yoluyla Proseslerarası Haberleşmeler
- İsimsiz ve İsimli Borular
- Windows Sistemlerinde Paylaşılan Bellek Alanları
- UNIX/Linux Sistemlerinde Paylaşılan Bellek Alanları
- Windows Sistemlerinde Bellek Tabanlı Dosyalar
- UNIX/Linux Sistemlerinde Bellek Tabanlk Dosyalar
- UNIX/Linux Sistemlerinde Mesaj Kuyrukları

## Thread'lerle İşlemler

- Thread Kavramı
- Thread'lerin Stack'leri
- Thread'lerin Birbirleriyle Haberleşme Biçimleri
- Windows Sistemlerinde Thread'lerin Yaratılması ve Sonlanması
- UNIX/Linux Sistemlerinde Thread'lerin Yaratılması ve Sonlanması
- Thread Senkronizasyonu
- Kritik Kod Blokları
- Windows Sistemlerinde CriticalSection Nesneleri İle Kritik Kodların Oluşturulması
- Windows Sistemlerinde Mutex Nesnelerinin Kullanımı
- UNIX/Linux Sistemlerinde Mutex Nesnelerinin Kullanımı
- Windows Sistemlerinde Semaphore Nesneleri
- UNIX/Linux Sistemlerinde Semaphore Nesneleri
- Üretici-Tüketici Probleminin Windows ve UNIX/Linux Sistemlerinde Çözümü
- Windows'ta Event Senkronizasyon Nesneleri
- UNIX/Linux Sistemlerinde Koşul Değişkenleri
- Windows Sistemlerinde Okuma/Yazma Kilitleri
- UNIX/Linux Sistemlerinde Okuma/Yazma Kilitleri
- Örnek Senkronizasyon Problemleri: Uyuyan Berber Problemi, Yemek Yiyen Filozoflar Problemi vs.
- Windows'ta Atomik İşlemler ve InterLocked Fonksiyonları
- UNIX/Linux Sistemlerinde Atomik İşlemler
- C ve C++'ta Atomik İşlemler
- Fonksiyonların Thread Güvenliliği
- Windows'ta Thread Local Storage Kullanımı
- UNIX/Linux Sistemlerinde Thread Specific Data Kullanımı
- Thread Havuzları
- Windows Sistemlerinde Thread'lerin Çizelgelenmesi
- UNIX/Linux Sistemlerinde Thread'lerin Çizelgelenmesi

## Veri Yapıları ve Algoritmalar

- Algoritma Kavramı
- Algoritmanın Karmaşıklığı
- Algoritma Karmaşıklığının Hesaplama Yöntemleri
- Asimtotik Notasyonlar 
- Big O Notasyonu
- Algoritmaların Sınıflandırılması
- Sayılar Teorisine Yönelik Algoritmalar
- Algoritmik Bulmacalar
- Veri Yapısı Kavramı ve Temel Veri Yapıları
- Dinamik Diziler, Kullanım Alanları ve Gerçekleştirimleri
- Bağlı Listeler, Kullanım Alanları ve Gerçekleştirimleri
- Kuyruk Veri Yapısı, Kullanım Alanları ve Gerçekleştirimleri
- Stack Veri Yapısı, Kullanım Alanları ve Gerçekleştirimleri
- Çift Yönlü Dinamik Diziler (Deque), Kullanım Alanları ve Gerçekleştirimleri
- Sıralama Algoritmaları
- Arama (Seraching) İşlemleri, İçsel ve Dışsal Arama Kavramları
- İkili Aramalar
- Üstel Aramalar
- Hash Tabloları, Kullanım Alanları, Varyasyonları ve Gerçekleştirimleri
- Tahsisat Algoritmaları Kullanım Alanları ve Gerçekleştirimleri
- Çöp Toplayıcı (Garbage Collector) Kavramı, Kullanım Alanları ve Gerçekleştirimleri
- Ağaç Kavramı, Özellikleri
- İkili Ağaçlar
- Ağaçlarda Dolaşım İşlemleri
- Arama Ağaçları
- İkili Arama Ağaçları, Kullanım Alanları ve Gerçekleştirimleri
- İkili Arama Ağaçlarında Dengeleme
- Heap Ağaçları, Heap Veri Yapısı ve Gerçekleştirimleri
- Heap Veri Yapısıyla Öncelik Kuyrukları 
- Heap Sort Yöntemi
- Dışsal (External) Aramalar
- B-Tree ve B+Tree Ağaçları ve Gerçekleştirimleri
- Veri Yapılarının Genelleştirilmeleri (Türden Bağımsız Veri Yapılarının Oluşturulması)
- Graf Veri Yapısı
- Graf Veri Yapısının Gerçekleştirimleri
- Graf Veri Yapısında Dolaşım İşlemleri
- Bazı Tipik Graf Problemlerinin Çözümüne İlişkin Algoritmalar

## TCP/IP Protokol Ailesi İle Proseslerarası Haberleşme

- Protokol Kavramı
- OSI Katmanlarının Anlamı
- IP Protokol Ailesine Genel Bakış
- IP Protokolü
- TCP ve UDP Protokolleri
- TCP Protokolü ile Client/Server Haberleşme
- Soket Kavramı BSD Soket Sistemi
- Windows Soket API'leri
- TCP Server Programlarının Yazımı
- TCP Client Programlarının Yazımı
- Client ile Server Arasında Haberleşme Teknikleri
- Çok Client'lı Server Uygulamaları
- IP Ailesinin Uygulama Katmanına İlişkin Protokoller (POP3, TELNET, HTTP, SSH Protokolleri)
- UDP Haberleşmesi 
- UDP Client ve Server Programları

## Kütüphanelerin Yaratılması ve Kullanılması

- Windows Sistemlerinde Statik Kütüphanelerin Yaratılması ve Kullanımı
- UNIX/Linux Sistemlerinde Statik Kütüphanelerin Yaratılması ve Kullanımı
- Windows Sistemlerinde Dinamik Kütüphanelerin Yaratılması ve Kullanımı
- UNIX/Linux Sistemlerinde Dinamik Kütüphanelerin Yaratılması ve Kullanımı
- Windows Sistemlerinde Dinamik Kütüphanelerim Dinamik Yüklenmesi
- UNIX/Linux Sistyemlerinde Dinamik Kütüphanelerin Dinamik Yüklenmesi

## Yazılımsal Araçların Kullanımı

- Versiyon Takip Sistemleri
- Git Aracının Kullanılması
- Github Kullanımı
- GNU Make, CMake ve QMake Build Araçlarının Kullanımı
- Valgrind ve Cppcheck Araçlarının Kullanımı
- Profiler'lar ve GNU gprof Araçlarının Kullanımı
- Visual Studio Debugger Kullanımı
- GDB Kullanımı

## Veritabanı İşlemleri

- Veritabanı Yönetim Sistemlerinin Genel Yapısı
- Gömülü Veritabanı Yönetim Sistemleri
- C'de Sqlite Kullanımı
- C'de MySql Kullanımı

## Yazılımlarda Test Süreci

- Genel Olarak Test Süreci
- Test Yöntemleri
- Test Otomasyon Araçları Hakkında Genel Bilgiler
- C'de Birim Testleri

## Aşağı Seviyeli Disk İşlemleri

- Hard Disklerin, DVD ROM'ların, SSD Disklerin ve Flash Disklerin Genel Yapısı
- Windows'ta Aşağı Seviyeli Disk İşlemleri
- UNIX/Linux Sistemlerinde Aşağı Seviyeli Disk İşlemleri
- Windows FAT Dosya Sistemlerinin Disk Organizasyonları
- Ext2 ve Ext3 Dosya Sistemlerinin Disk Organizasyonları
- Disk Bölümleme Tabloları 
- Klasik ve UEFI Boot Süreci

## Kesme Mekanizması

- Kesme Kavramı
- Yazılım ve Donanım Kesmeleri
- PC Mimarisinde Temel Kesmeler ve İşlevleri
- Kesmelerin Ele Alınması

+ [Kursumuza ön kayıt yaptırmak için bu bağlantıyı kullanabilirsiniz.]( https://us02web.zoom.us/meeting/register/tZcuceqqpz0oG9QL4swXJhLW8bIpxWRhmUF0)


