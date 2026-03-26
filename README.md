# 🖥️ Özel Bilgisayar Toplama ve Stok Otomasyonu

![Status](https://img.shields.io/badge/Durum-Aktif_Geliştirme_Aşamasında-success?style=for-the-badge)

Kullanıcıların donanım uyumluluğu kurallarına (örn. anakart soket tipi ile işlemci uyumu) katı bir şekilde bağlı kalarak kendi bilgisayarlarını toplayabildiği, modüler bir sistem otomasyonudur. Geliştirme sürecinde "Temiz Kod" (Clean Code) ve Gelişmiş Tasarım Kalıpları (Design Patterns) merkeze alınarak tasarlanmıştır.

### 🏗️ Mimari ve Tasarım Kalıpları (Design Patterns)
* **Factory Method Pattern:** İşlemci, Ekran Kartı, RAM gibi farklı donanım parçalarının nesne üretim süreçlerini soyutlamak ve merkezi bir yapıdan yönetmek için sisteme entegre edilmiştir.
* **Decorator Pattern:** Seçilen temel PC bileşenlerinin üzerine eklenen ekstra donanımların (örn. ekstra RGB fan, sıvı soğutma) fiyat ve özellik hesaplamalarının dinamik olarak yapılması sağlanır.
* **Strategy Pattern:** Farklı kargo veya indirim hesaplama algoritmalarının sistem çalışırken (runtime) esnek bir şekilde değiştirilebilmesi için kurgulanmıştır.

### 🛠️ Kullanılan Teknolojiler
* **Programlama Dili:** Java
* **Kavramlar:** Nesneye Yönelik Yazılım Mühendisliği (OOSE), UML Modelleme, Sürdürülebilir Mimari
