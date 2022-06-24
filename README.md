# HYBRID Recommender System
![pexels-cottonbro-3945317](https://user-images.githubusercontent.com/101832704/175607063-4b49e616-7a93-4cf0-959e-0f0c07428c84.jpg)

# İŞ PROBLEMİ

ID'si verilen kullanıcı için item-based ve user-based recommender
yöntemlerini kullanarak 10 film önerisi yapınız.

# VERİ SETİ HİKAYESİ 

Veri seti, bir film tavsiye hizmeti olan MovieLens tarafından sağlanmıştır. İçerisinde filmler ile birlikte bu filmlere yapılan
derecelendirme puanlarını barındırmaktadır. 27.278 filmde 2.000.0263 derecelendirme içermektedir. Bu veri seti ise 17 Ekim 2016
tarihinde oluşturulmuştur. 138.493 kullanıcı ve 09 Ocak 1995 ile 31 Mart 2015 tarihleri arasında verileri içermektedir. Kullanıcılar
rastgele seçilmiştir. Seçilen tüm kullanıcıların en az 20 filme oy verdiği bilgisi mevcuttur.

# DEĞİŞKENLER

## movie.csv

MovieId = Eşsiz film numarası 

Title = Film adı

Genres = Tür

## rating.csv

Userid = Eşsiz kullanıcı numarası (UniqueID)

MovieId =  Eşsiz film numarası (UniqueID)

Rating = Kullanıcı tarafından filme verilen puan

Timestamp = Değerlendirme tarihi
