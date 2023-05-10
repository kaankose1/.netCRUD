# .netCRUD

Bu bir C# ASP.NET Core Web API projesidir. Bu kodda "ProductController" adında bir controller tanımlanmıştır. Bu controller, "MyDbContext" adlı bir veritabanı bağlantısı kullanarak "Product" adlı bir nesne modeline erişir.

Controller'ın metotları, HTTP isteklerine yanıt olarak çeşitli işlemler gerçekleştirir.

"GetProducts" metodu, tüm ürünleri veritabanından alır ve bunları bir koleksiyon içinde döndürür.
"GetProduct" metodu, belirli bir ürünü almak için bir kimlik değeri alır ve bu kimlik değeri ile eşleşen ürünü döndürür.
"CreateProduct" metodu, yeni bir ürün eklemek için bir POST isteği alır. Bu metod, veritabanına yeni bir ürün ekler ve yeni ürünün bilgilerini içeren bir yanıt döndürür.
"DeleteProduct" metodu, belirli bir ürünü silmek için bir DELETE isteği alır. Bu metod, belirli bir ürünü veritabanından siler ve başarılı bir şekilde silindiğine dair bir yanıt döndürür.
