# AdressBook_SUNUM


PROJE HAKKINDA TEKNİK BİLGİLER:

 Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
 
 Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
 
 Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
 
 Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık.
 
-AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)

 Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
 
 Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor.
 
 Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
 
 Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34
 
 Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
 
 Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .
<img width="953" alt="219572540-abd005fc-65f3-4be0-b576-0d21f0902b80" src="https://user-images.githubusercontent.com/112180158/221548764-ed977625-b940-495c-807c-e477eccc9658.png">
<img width="960" alt="219572552-edf5e923-5112-4529-93b3-a99fe2b277b3" src="https://user-images.githubusercontent.com/112180158/221548778-ffd07972-5169-42fa-9eef-a2f8610fcc89.png">
<img width="960" alt="219572558-1bc3befc-494b-498a-95ce-6ee726aa3e69" src="https://user-images.githubusercontent.com/112180158/221548783-b4b36fdc-541d-43d4-9fd4-803b92b948f3.png">
<img width="956" alt="219574456-075c80bd-eb93-4e6e-813e-6fa4de9292f8" src="https://user-images.githubusercontent.com/112180158/221548788-472f2779-1129-4bcc-9561-b0095aa158a8.png">
<img width="959" alt="219574469-ec16aeee-8e9c-44ad-ac3d-0c7973c37eff" src="https://user-images.githubusercontent.com/112180158/221548798-ac9a8aa9-38c1-4701-99f3-1c5af2867b5c.png">
