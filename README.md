# HYBRID Recommender System
![pexels-cottonbro-3945313](https://user-images.githubusercontent.com/101832704/175605911-27d53786-a01a-435f-971f-fbe3b6167529.jpg)

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
