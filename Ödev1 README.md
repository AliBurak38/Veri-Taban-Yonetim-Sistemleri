
1.Soru:Geleneksel Dosyalama Sistemlerinin Çalışma Şeklini açıklayarak bildiğiniz programlama dili ile txt dosyadan veri okuyan ve yazan bir program geliştiriniz ?

Cevap: Geleneksel Dosyalama Sistemlerinin Çalışma Şekli : 
Geleneksel dosyalama sistemleri veri tabanı yönetim sistemi kurulmadan önce kullanılırmış. Veri depolamaya yarar. Mesela bir okul için öğrenci verilerinin tutulması için bu bilgilerin öğrenci no ve ad soyad kısmı bir dosya,
Dersler ve Notları kısmı ayrı dosyalarda tutulması gerekir. Bu dosyaları okumak için de Sıralı erişimli dosyalar ve Doğrudan erişimli dosyalar olarak 2 kısıma ayrılır.

---- Geleneksel Dosyalama Sistemlerinin Çalışma Şekli ----
  
   1)Sıralı Erişimli Dosyalar
Herhangi bir dosyada okunması istenen veriye doğrudan erişilmez o veri hangi sırada ise o veriye kadar olan bütün veriler taranır ve istenen veriye sıra geldiğinde işlem yapılır bu yöntemle sistem gereksiz fazla çalışır ve hem zaman kaybı hem de sisteme yük binmiş olur. 

2)Doğrudan Erişimli Dosyalar
Sıralı dosyalardaki bu sorunun önüne geçmek için Doğrudan Erişimli Dosyalar çıkmış ve bu dosya içindeki satırlar indeks değerine sahiptir bu indeks sayesinde istenen bilgiye doğrudan erişilir.

---- TXT DOSYADAN VERİ OKUYAN VE YAZAN PROGRAM ----

              ---Programımın kod kısmı---
![ödev 1](https://github.com/user-attachments/assets/944cf4e3-7c9b-405e-aff0-07011187ac18)


      ---Programın Console Kısmının txt dosyadan alındığı---
      
![ödev 2](https://github.com/user-attachments/assets/3753ea18-6b05-47dd-a009-60f071e48491)


     ---Dosyaya Eklenmesi istenen bilgiyi Console Kısmına yazdık---
     
![ödev 3](https://github.com/user-attachments/assets/15b926a6-0ff3-4a3a-a750-c593fc43caf1)

  
   ---Eklenen Bilginin Txt Dosyasında da görünümü---
   
![ödev 4](https://github.com/user-attachments/assets/9916bf30-2d98-4e1a-96a0-2d690a4352fe)


2.SORU: Geleneksel dosyalama sistemleri ile veri tabanı yönetim sistemlerinin benzerlikleri ve farklılıkları nelerdir ?

Benzerlikleri : Her iki sistem de veri depolamak için kullanılır. Her iki sistemde de veri ekleme silme ve güncelleme işlemi mevcuttur. Kullanıcılar 2 sisteme de erişme yetkisine sahiptir.

Farklılıkları : Geleneksel dosyalama sistemlerinde veriler dosyalarda klasörlerde tutulurken veri tabanı yönetim sistemlerinde veriler tablolarda saklanır. Geleneksel dosyalama sistemlerinde birden fazla kullanıcı aynı anda dosylara erişmek istediğinde sıralı erişim olur ve aynı anda erişilemez, Ama veri tabanı yönetim sistemlerinde ise doğrudan erişim olduğu için aynı anda erişim mümkündür. Veri tabanı yönetim sistemleri daha karışık işler için kullanılır birden fazla veri tutar bunlar arasında ilişki kurulabilir. Daha güvenlidir program daha az yük içinde çalışır.

3.SORU: VTYS nin geleneksel sisteme göre üstün özellikleri nelerdir ?

Kullanıcılar bir veriye erişmek istediğinde yalnızca izin verilen yani yetkisi olan verilere erişebilirler. Şifreleme mekanizması sayesinde verilerin güvenliği üst düzeydedir. Birden fazla kullanıcının aynı anda verilere erişmesine ve işlem yapmasına izin verir. Anahtarlar (primary key, foreign key) sayesinde veriler arasında ilişki kurulabilir ve o veriye ait benzersiz bir kimlik kazandırılabilir. VTYS  programlar web siteleri mobil uygulamalar ile uyumu mevcuttur.

4.SORU: Veri tabanının görevini açıklayarak kullanıldığı alanlara örnek veriniz ? 

Veri tabanı görevini bir örnek ile açıklamak isterim ; Mesela biz bir hastanedeki hastaları kayıt eden bir program yapmış olalım bu hastaların adı soyadı hangi hastalığı olduğu doktoru kim olduğunu geçici olarak veri tabanı kulllanmadan kayıt edebiliriz ama biz programı kapatıp tekrar açtığımızda girilen hasta bilgileri silinmiş olacak çünkü bu veriler bir depoda tutulmuyo işte veri tabanı sayesinde girilen bilgiler kayıt edilir ve tablolarda istediğiniz kadar saklayabilirsiniz bu sayede program açıp kapandığında verilere tekrar erişmek mümkün olur. 

Kullanıldığı Alanlar: Hastanelerde hasta kayıt etmek için, Bankalarda müşteri kaydı para kaydı vs kullanılabilir, Araç Kiralama sisteminde kullanılabilir, Bir okul için Öğrenci kayıt etmek için ders kaydı için kullanılabilir. Daha sayısızca bir çok yerde karşımıza çıkar...


5.SORU: Tablo satır ve sütun kavramlarını açıklayınız ?

Tablolar sayesinde verilerimizi burada depolarız  Her Depolama için ayrı ayrı tablolar oluşturabiliriz Mesela öğrenci bilgiler için bir tablo dersler ve notları için birer tablo oluşturabiliriz.

Satır ve sütunlar: Satır ve sütunlar tabloların içinde bulunur bunlar arcılığıyla  verileri bir düzen içinde tutarız Sütınlar tablomuzdaki veri türünü belli ederken satırlar o veri türüne ait içerikleri belli eder 

                ---Burada SQL veri tabanına ait bir tablom var---
                
![VERİ](https://github.com/user-attachments/assets/8792bfc1-0939-465e-b474-1dbf10b6a9df)









