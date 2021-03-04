# ReCapProject - Araç Kiralama Sistemi
![cizimbanner2](https://raw.githubusercontent.com/furkanpasaoglu/githubImages/main/Yaz%C4%B1l%C4%B1m%20Geli%C5%9Ftirici%20Yeti%C5%9Ftirme%20kamp%C4%B1.png?token=AD62TVKL2AYUKI5MCRC4LYTAID6D6) 

## :pushpin:Getting Started
![layers](https://raw.githubusercontent.com/furkanpasaoglu/githubImages/main/About.png?token=AD62TVKYTY7OB2C3Q2HYQHTAID66S)
<br>
## :books:Layers  
![entities](https://raw.githubusercontent.com/furkanpasaoglu/githubImages/main/Entities%20Layer.png?token=AD62TVOVAADVWQBM5GP7BDTAID6KA)
### Entities Layer
Veritabanı nesneleri için oluşturulmuş **Entities Katmanı**'nda **Abstract** ve **Concrete** olmak üzere iki adet klasör bulunmaktadır.Abstract klasörü soyut nesneleri, Concrete klasörü somut nesneleri tutmak için oluşturulmuştur.  
![business](https://raw.githubusercontent.com/furkanpasaoglu/githubImages/main/Business%20Layer.png?token=AD62TVOWRM7X47IVPV5FRO3AID6N2)
<br>
###  Business Layer
Sunum katmanından gelen bilgileri gerekli koşullara göre işlemek veya denetlemek için oluşturulan **Business Katmanı**'nda **Abstract**,**Concrete**,**Utilities** ve **ValidationRules** olmak üzere dört adet klasör bulunmaktadır.Abstract klasörü soyut nesneleri, Concrete klasörü somut nesneleri tutmak için oluşturulmuştur.Utilities ve ValidationRules klasörlerinde validation işlemlerinin gerçekleştiği classlar mevcuttur.  
<br>
![dal](https://raw.githubusercontent.com/furkanpasaoglu/githubImages/main/Data%20Access%20Layer.png?token=AD62TVL5JZVXSXTRYNBIYRLAID6TE)
###  Data Access Layer
Veritabanı CRUD işlemleri gerçekleştirmek için oluşturulan **Data Access Katmanı**'nda **Abstract** ve **Concrete** olmak üzere iki adet klasör bulunmaktadır.Abstract klasörü soyut nesneleri, Concrete klasörü somut nesneleri tutmak için oluşturulmuştur.  
<br>

![core](https://user-images.githubusercontent.com/77868230/107870091-c42f6900-6ea6-11eb-863e-63d30fa2128c.png)
###  Core Layer
Bir framework katmanı olan **Core Katmanı**'nda **DataAccess**, **Entities**, **Utilities** olmak üzere 3 adet klasör bulunmaktadır.DataAccess klasörü DataAccess Katmanı ile ilgili nesneleri, Entities klasörü Entities katmanı ile ilgili nesneleri tutmak için oluşturulmuştur. Core katmanının .Net Core ile hiçbir bağlantısı yoktur.Oluşturulan core katmanında ortak kodlar tutulur. Core katmanı ile, kurumsal bir yapıda, alt yapı ekibi ilgilenir.  
> **⚠ DİKKAT: .**  
> Core Katmanı, diğer katmanları referans almaz.


![ssms](https://raw.githubusercontent.com/furkanpasaoglu/githubImages/main/Database%20and%20Tables.png?token=AD62TVLL5CRZOWI6UQG7XCLAID7EO)
###  Veritabanı Oluşturma 
Araba Kiralama Projemiz localdb ile çalışmaktadır. **LocalDb**'de veritabanı oluşturmak için **Visual Studio 2019** için *View > SQL Server Object Explorer* menü yolunu takip edebilirsiniz.Pencere açıldıktan sonra *SQL Server > (localdb)MSSQLLocalDB* altındaki **Databases** klasörüne sağ tıklayıp Add **New Database** seçeneğini ile veritabanınızı oluşturabilirsiniz. Veritabanı oluşturulduktan sonra **New Query** seçerek aşağıda bulunan Sql File ile veritabanınızda olması gereken tabloları oluşturabilirsiniz.  
- [SqlQuery.sql](https://github.com/furkanpasaoglu/ReCapProject/blob/master/SQLQuery.sql) *(Tablonuzu linkde gördüğünüz şekilde oluşturun)*
<br>

## Araba Kiralama Projesi ile ilgili Notlar
- [SqlQuery.sql](https://github.com/furkanpasaoglu/ReCapProject/blob/master/SQLQuery.sql) *(Tablonuzu linkde gördüğünüz   şekilde oluşturun)*
- *7.Haftadaki DataAccess katmanında bulunan Abstract kısım Generic Repository Design Pattern ile güncellendi.*
- *7.Haftadaki DataAccess katmanında bulunan InMemoryCarDal güncellendi. (LINQ kodları eklenmiştir.)*
- *8.Hafta ödevine ilişkin EntityFramework kodları yazıldı.*
- *9.Hafta ödevine ilişkin Core Katmanı kodları yazıldı.*
- *ConsoleUI' da yapılacan Add, Update, Delete işlemlerini ilgili fonksiyonlardan güncelleyebilirsiniz.*
- *10.Hafta ödevine ilişkin Business Katmanın'da Constant Eklendi ve Messages Kodları Yazıldı.* 
- *10.Hafta ödevine ilişkin Core Katmanın'da Utilities Eklendi ve Result ve DataResult Kodları Yazıldı..* 
- *11.Hafta WebAPI Eklendi ve Kodları Yazıldı.*
- *12.Hafta Autofac ve FluentValidation Kodları Yazıldı.*
- *12.Hafta Artık projede AOP ve IoC yapıları kullanılıyor.*
- *13.Hafta Veritabanına CarImages Tablosu Eklendi.*
- *13.Hafta Projeye Dosya Yükleme (File Helper) Sistemi Yazıldı.*
- *14.Hafta Veritabanı Güncellendi.*
- *14.Hafta JWT Entegrasyonu Yapıldı.*
- *15.Hafta Cache, Transaction ve Performance Entegrasyonu Yapıldı.*

<br>
## :pencil2:Authors
* **Furkan Paşaoğlu** - [furkanpasaoglu](https://github.com/furkanpasaoglu)
