# Doozles-The-Jumpy-Boi
# Bursa Teknik Üniversitesi 3. Sınıf Güz Dönemi Oyun Programlama Dersi Vize Projesi

Oyunumuz hepimizin gençlik yıllarında oynamış olduğu Doodle Jump oyununun benzeri şekilde oluşturulmuş olup amacı eski nostaljik duyguyu tekrar yaşatmaktır. 
Oyunumuzda A ve D tuşlarını kullanarak hareket edilmektedir. Oyunumuzun amacı hiç durmadan zıplayan oyunumuzun ana karakteri Doozles'ın platformdan aşağı düşmeden elde edebileceği maksimum puanı elde etmesine dayanmaktadır. Oyunda bulunan Menu içerisinde Play ve Resume butonları bulunmaktadır. 
Play tuşu oyunumuzu başa sararak Score durumunu sıfırlamaktadır. Play butonuna tıkladıktan sonra Resume ve ESC tuşuna basarak oynamaya devam edebilirsiniz.
Resume tuşu oyunumuza kaldığımız yerden aynı Score ile devam etmemizi sağlamaktadır.Menu içerisinde ister ESC tuşuna basarak istersenizde Resume tuşuna basarak kaldığınız yerden devam edebilirsiniz.
Oyun içerisinde anlık oyunu durdurmanız gerekmesi durumunda "Escape" tuşuna basarak oyununuzu Menu'ye geçirebilir ve dondurabilirsiniz.

# OYUNUN GÖRSELLERİ



![image](https://user-images.githubusercontent.com/74237991/204635127-96a21771-c149-4c7b-a3ee-21981aa76f45.png)
![image](https://user-images.githubusercontent.com/74237991/204635185-1f73da2b-4f97-40b4-90ed-779aabdc6f33.png)

# OYUNDA KENDİ GELİŞTİRDİĞİM YERLER VE KODLADIĞIM SCRİPTLER


Oyunun Menusünü Canvas kullanarak oluşturdum ve geliştirdim. Oyunda bulunan Controller , Destroy ve Bounce Scriptlerini yazarak gelistirdim. Controller.cs scripti Doozles karakterinin hareket girdilerini içermektedir. Hareket esnasında aldığı girdiye göre sağa veya sola dönmesini içermektedir. Bunun yanı sıra Doozles karakter platformlar üstünde atlar iken çıkabildiği maksimum yükselik baz alınarak puan kazanmaktadır. 
Destroy.cs scipti Doozles karakteri ile bağdaşık olan bir GameObject ile alakalı script içermektedir. Bu GameObject dokunduğu her bir Platform ögesi için oyunun ilerleyen yüksekliğinde random olarak bir başka platform oluşturmaktadır. Bu sayede gereğinden fazla sayıda platform oluşturmamıza gerek kalmadan bir recursive fonksiyon açmış olduk.
Bounce.cs scripti Doozles karakterinin etkileşime girdiği Platformlar üzerinde belirli bir kuvvet ile zıplamasını sağlamaktadır.
Oluşturduğum Scripler ile oyun ögelerini birbirlerine bağdaştırmış ve uyumlu bir şekilde herhangi bir sorun çıkarmadan çalışmasını sağladım.

# OYUNDA EKİP ARKADAŞIMIN GELİŞTİRDİĞİ YERLER VE KODLADIĞI SCRİPTLER
