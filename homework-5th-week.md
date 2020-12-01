### SQLite ve LocalDB kavramlarını karşılaştırınız.

Sqlite, bir veritabanı kütüphanesidir. Sqlite herhangi bir ana sunucu işlemi gerektirmez. Veritabanına erişmek için sunucuya istek göndermek ve sonuç almak için ara işlem iletişimi kurmak gerekmez. Bu program doğrudan diskteki veritabanı dosyalarını okur ve yazar. Bu durumun ana avantajı; kurma, yapılandırma, başlatma, yönetme ve sorun giderme işlemleri için ayrı bir sunucu işlemi yapmaya gerek olmamasıdır. Ancak bu durumun bir dezavantajı da vardır. Sunucu kullanan veritabanları genellikle daha güvenlidir.

Localdb Microsoft'un SQL Express'in yeni versiyonuna verdiği isimdir. SQL Express (localdb) veya SQLite gibi programlar genellikle bir veri dosyanı size SQL formatında sunar. Bu sayede bir SQL sunucusu (MSSQL, MySQL veya Oracle) kurmaya gerek kalmadan SQL üzerinde çalışabilinir. Bir sunucunun yeteneklerine sahip değildir fakat kod geliştirmeyi kolaylaştırır.

### Lazy Loading kavramı hakkında temel bir araştırma yapınız.

Lazy Load, görsel yoğunluğu ve sayfa uzunluğu (aşağı doğru) fazla olan sitelerde, sitenin geç açılmasını engellemek amacı ile ek bir Javascript dosyasının kullanılmasıdır. Bu özelliğin kullanıldığı bir web sayfası açıldığında ekranda henüz yer almayan resimlerin yüklenmesi önlenmektedir. Sayfada var olan tüm görsellerin aynı anda yüklenmesi engellenir ve sadece kullanıcının ekranında yer alan görseller yüklenir. Kısacası; herhangi bir görseli gerekli görmedikçe yaratmamayı öngörür.
