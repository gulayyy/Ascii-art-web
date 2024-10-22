Proje Adı 

ascii-art-web

Proje Amacı 

Proje, terminalde aldığımız ascıı-art sanatı çıktısını html yardımı ile web sayfasına taşımak 

Yazarlar 

- Miray Çakır
- Gülay Yüceer
- Sümeyye Gül Güzel


Nasıl Çalıştırılır ? 

main.go dosyamızda go run main.go şeklinde terminalden çalıştırılarak ve tarayıcıda "http://localhost:8080" adresine giderek web sunucumuza erişebiliriz

Genel Çalışma Prensibi
1-İlk err kontrol fonksiyonunda index.html dosyamızı çekmemizi sağladı
2-HandleFunc fonksiyonumuzda sayfayı görüntüleme işlemlerini , 400-404-500 hata durumlarını işledik 
3-Ascıı fonksiyonunda da ascıı art sanatını oluşturduğumuz fonksiyon