# Araştırma Ödevi


1. Solid Prensiplerini Öğren.
2. Microsoft Build 'den 2 etkinlik araştır.
3. Microsoft Build 2020 yeniliklerini Araştır.
4. Takip Ettiğin 2 yazılımcıyı araştır.
5. Devler Azure'da araştır [Eğitim-Workshop]
6. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)


---

##  Solid Prensipleri

#### Single Responsibility Principle
Single responsibility prensibi sınıflarımızın iyi tanımlanmış tek bir sorumluluğu olması gerektiğini anlatmaktadır. Bir sınıf (nesne) 
yalnızca bir amaç uğruna değiştirilebilir, o amaçta o sınıfa yüklenen sorumluluktur, yani bir sınıfın yapması gereken yalnızca bir işi
olması gerekir.
Eğer geliştirdiğiniz sınıf ya da fonksiyon birden fazla amaca hizmet ediyorsa, bu kurala aykırı bir geliştirme sürecinde olduğunuz 
anlamına geliyor. Bunu farkettiğinizde amaçlara uygun olarak parçalamanız gerekmektedir.


#### Open / Closed Principle Principle
Sınıflarımız değişikliğe kapalı ancak yeni davranışların eklenmesine açık olmalı. Geliştirdiğimiz yazılıma/sınıfa varolan kodu 
değiştirmeden, yeni kod yazılarak yeni özellikler eklenebilmelidir. Yeni bir gereksinim geldiğinde mevcut kod üzerinde herhangi bir 
değişiklik yapıyorsanız, open/closed prensibine ters düşüp düşmediğinizi kontrol etmenizde yarar var. Yazılımı geliştirirken gelecekte
oluşabilecek özellikler ve geliştirmeleri her şeyiyle öngöremeyiz. O yüzden oluşabileceğini düşündüğümüz kodlarıda şimdiden 
geliştirmemeliyiz.

#### Liskov Substituon Principle 

Türeyen sınıf yani alt sınıflar ana(üst) sınıfın tüm özelliklerini ve metotlarını aynı işlevi gösterecek şekilde kullanabilme ve kendine 
ait yeni özellikler barındırabilmelidir

#### Interface Segregation Principle

Sorumlulukların hepsini tek bir arayüze toplamak yerine daha özelleştirilmiş birden fazla arayüz oluşturmayı tercih etmemizi söyleyen 
prensiptir. Tek bir interface yerine kullanımlarına göre parçalanmış birden fazla interface ile işlemleri yürütmeliyiz. Yani her farklı 
sorumluluğun kendine özgü bir arayüzü olması gerekmektedir. Böylece interface’i kullanan kişide sadece ihtiyacı olanlarla ilgilenmiş 
olur. 

#### Dependency Inversion Principle

Sınıflar arası bağımlılıklar olabildiğince az olmalıdır özellikle üst seviye sınıflar alt seviye sınıflara bağımlı olmamalıdır. Bir 
sınıfın, metodun ya da özelliğin, onu kullanan diğer sınıflara karşı olan bağımlılığı en aza indirgenmelidir. Bir alt sınıfta yapılan 
değişiklikler üst sınıfları etkilememelidir. Dependency Inversion, yani üst sınıflar, alt seviyeli sınıflara bağlı olmamalı, çözüm ise 
her ikisi de soyut kavramlar üzerinden yönetilebilmelidir.


###  Yazılım Yarışmalar 
USOM tarafından düzenlenen Siber Yıldız :
Ulusal Siber Olaylara Müdahale Merkezinin düzenlediği bir capture the flag siber güvenlik yarışması.Bizde 3 kişilik bir takım olarak 
katıldık daha sonrasında kazananlar Siber Talimhaneye davet edildi.Siber güvenlik alanıyla ilgilenen kişilerin keşfedilmesi ve 
desteklenmesini amaçlayan güzel bir yarışma.

TBV tarafından düzenlenen Kod Ödülleri: 
İlkokul,ortaokul ve lise eğitiminde Matematik veya Fen Bilimleri alanında eğitime destek amaçlı dijital oyun fikirlerinin yarıştığı bir 
proje.Başvurular Dijital içerik fikirleri ve Dijital içerik uygulamaları olarak ikiye ayrılıyor.Başvurular arasından seçilen 30 uygulama
daha sonrasında kullanıcılar ve jurinin karşısına çıkarılıyor ve kazanan 3 proje belirleniyor.Yarışmanın hoşuma giden özelliği genel 
olarak fikirlerin ilkokul ve ortaokul öğretmenlerinden çıkması.Fikirlerin üniversite öğrencileri tarafından kodlanıp uygulanması.


### Takip Ettiğim Yazılımcılar

Hem kodlamayı öğrendiğim hemde düşüncelerini benimsediğim kişiler.Bir şeyler üretirken,öğrenirken akıllarında hep insanlara için ne 
yapabiliriz bilgiyi nasıl daha çok insana ulaştırabiliriz diye düşünen harika iki insan.

Şadi Evren Şeker

Murat Yücedağ 


