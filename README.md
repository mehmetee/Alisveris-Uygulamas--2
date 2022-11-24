# Alisveris-Uygulamas--2
React native ile olusturduğumuz bu uygulamamizda bir login ekranı bulunmakta ve ürünlerimizi görüntülediğimiz bir anasayfa ve ürün detaylarını gösteren ayrı bir sayfa bulunmakta.
Login giriş ekranımızda react native community tarafınfan geliştirilmiş olan kullanım işlevselliği nedeniyle formik patketiyle oluşturldu,
login ekranımızda API'dan istekte bulunduğumuz  kullanıcı istekleri ile giriş yapılmakta şayet öyle bir kullanıcı bulunmadığı taktirde ekrana hata msjı basmakta,
Post işlemi doğrulandığı taktirde kullanıcı adı şifre cihaz belleğine kaydolmakta uygulamamızı kapatıp açtığımızda bir giriş işlemi gerçekleşmez bizi direk ana sayfamıza
aktarır.Tüm bu işlemlerimizi Redux yapısı kullanılarak gerçekleştiriyoruz.
Uygulama projemizde kendi custom hook yapımızı oluşturduk.
Sayfalar arası geçişlerde Stack yapısı kullandım tekrardan revize edilebilir tab veya drawer kullanılabilir.
Sayfa geçişlerinde işlemin durumuna göre Loading-error işlemleri gerçekleşir.
Son olarak uygulamdan çıkış butonuna tıkladığımız anda bizi login ekranına yönlendirmekte ve tekrardan giriş işlemi için kullanıcı girişi ister.


https://user-images.githubusercontent.com/44464636/203796381-35e320e5-ba5d-43d5-a970-9d3976e09336.mp4

