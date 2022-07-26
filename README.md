# Week1Assignment

##	ARAŞTIRMA (10 puan)
Lazy Loading ve Eager Loading arasındaki farkları yazınız.

##	SYMFONY İLE REST API OLUŞTURMA (90 puan)
Symfony ile temel bir Rest API oluşturunuz. Bu Rest API ile bir Kullanıcı ürün objesiyle ilgili işlemler oluşturabilmelidir. Bir ürüne ait bu öznitelikler olmalıdır: 
- id
- urunAdi,
- urunAciklamasi, 
- urunAdedi,
- urunFiyati,
- urunKayitTarihi

Oluşturduğunuz bu Rest API içinde aşağıdaki endpointler olmalıdır:
-	/product: ürün ekleme işlemi yapılmalıdır. (POST)
-	/product/{id}: id’ye göre ürün bilgisi gösterilmelidir. (GET)
-	/product/{id}: id’ye göre ürün güncelleme işlemi yapılmalıdır. (PUT)
-	/product/{id}: id’ye göre ürün slime işlemi yapılmalıdır. (DELETE)

Koşullar:
-	Her endpoint işlem yapıldıktan sonra success mesajı döndürmelidir.
-	Rest API için tüm dönüş değerleri Json tipinde olmalıdır.
-	Rest API Postman ile çalıştırılabilir olmalıdır.

