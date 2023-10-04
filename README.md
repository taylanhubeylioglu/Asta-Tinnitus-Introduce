# Asta-Tinnitus-Introduce
Kulak Çınlaması Tedavisi Kapsamında Bir Uzman İçin Geliştirdiğim Uygulama

Kulak çınlaması tedavisinde akıllı telefon uygulaması desteği kapsamında Erciyes Üniversitesi Sağlık Bilimleri Fakültesinde görev yapmakta olan bir hocanın tez çalışması için mobil uygulama geliştirdim.

Uygulamanın geliştiriminde 
- Flutter
- Firebase teknolojilerini kullandım.

Uygulama iOS, Android ve Web üzerinde çalışıyor.


Uygulama iki kullanıcı tipi içeriyor.
- Danışan Kullanıcı
- Uzman Kullanıcı

Danışan kullanıcı aşağıdaki fonksiyonlara sahip.
-	Giriş Yap
-	Kayıt ol
-	Şifremi Unuttum
-	Hesabımı sil
Üyelik sisteminde E-Posta doğrulama mevcut, bu fonksiyonların kullanımında e-posta’ya doğrulama maili gitmekte.

Danışan kullanıcı kayıt olup giriş yaptıktan sonra ana sayfaya yönlendirilecek. Ana sayfada değerlendirme, eğitim, başa çıkma stratejileri, destek hattı kısımları mevcut.
-	Değerlendirme kısmına girdiğinde karşısına 4 adet test çıkıyor. Bu testlerin bir kısmı 3 kere çözülüyor. Her bir kere çözüldükten sonra veritabanına çözdüğü tarih kaydedilip 2 hafta sonra tekrar aktif olacak şekilde test pasif oluyor. 2 hafta sonra vakti geldiğinde uygulama tarihi kontrol edip hem testi aktif yapıyor hem de ekrana bildirim basıp testin vaktinin geldiğini hatırlatıyor.
-	Eğitim ve başa çıkma stratejileri kısımlarında videolar var. Danışan kullanıcıya bilgilendirici videolar gösteriliyor.
-	Destek hattı kısmında uzmana mesaj yazabiliyor. Mesaj smtp ile uygulamanın içine gömülü default mail’den uzman mailine gönderiliyor. Mailin içeriğinde danışanın bilgileri iletiliyor.

Uzman kullanıcı aşağıdaki fonksiyonlara sahip.
-	Danışanları listeleme
-	Danışanları silme
-	Danışanların çözdüğü testleri görüntüleme
-	Danışanların çözdüğü testler üzerinde değişiklik yapma
-	(Sadece web sürüm) Danışanların çözdüğü testi ve testleri tek olarak veya toplu olarak Excel dosyası olarak indirme. Tüm danışanların bilgileri istatistik çalışma yapılabilinecek formatta tek excelde indirilebiliyor.

iOS ve Android sürümünde iki kullanıcı tipi de aktifken Web sürümünde sadece uzman kullanıcı tipi aktif.
