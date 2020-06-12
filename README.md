# Araştırma Ödevi


1. Solid Prensiplerini Öğren.
2. Microsoft Build 'den 2 etkinlik araştır.
3. Microsoft Build 2020 yeniliklerini Araştır.
4. Takip Ettiğin 2 yazılımcıyı araştır.
5. Devler Azure'da araştır [Eğitim-Workshop]
6. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)






## Solid Prensipleri
- [Single Responsibility Principle](single-responsibility-principle)
- [Open / Closed Principle](Open-/-Closed-Principle)
- [Liskov Substitution Principle](Liskov-Substitution-Principle)
- [Interface Segregation Principle](Interface-Segregation-Principle)
- [Dependency Inversion Principle](Dependency-Inversion-Principle)




### Single Responsibility Principle
Single responsibility prensibi sınıflarımızın iyi tanımlanmış tek bir sorumluluğu olması gerektiğini anlatmaktadır. Bir sınıf (nesne) yalnızca bir amaç uğruna değiştirilebilir, o amaçta o sınıfa yüklenen sorumluluktur, yani bir sınıfın yapması gereken yalnızca bir işi olması gerekir.
Eğer geliştirdiğiniz sınıf ya da fonksiyon birden fazla amaca hizmet ediyorsa, bu kurala aykırı bir geliştirme sürecinde olduğunuz anlamına geliyor. Bunu farkettiğinizde amaçlara uygun olarak parçalamanız gerekmektedir.


### Open / Closed Principle Principle
Sınıflarımız değişikliğe kapalı ancak yeni davranışların eklenmesine açık olmalı. Geliştirdiğimiz yazılıma/sınıfa varolan kodu değiştirmeden, yeni kod yazılarak yeni özellikler eklenebilmelidir. Yeni bir gereksinim geldiğinde mevcut kod üzerinde herhangi bir değişiklik yapıyorsanız, open/closed prensibine ters düşüp düşmediğinizi kontrol etmenizde yarar var. Yazılımı geliştirirken gelecekte oluşabilecek özellikler ve geliştirmeleri her şeyiyle öngöremeyiz. O yüzden oluşabileceğini düşündüğümüz kodlarıda şimdiden geliştirmemeliyiz.

