# Dervish-Prototip

Kullanıcıların yatırım işlemlerini kullanıcılar için takip etmeyi kolaylaştırıyor ve kullanıcıların yatırımlarının otomatik olarak grafiklere dökülmesini sağlıyoruz. Yapılan işlemlerin parametrelerini ve güncel borsa verilerini kullanarak kolay anlaşılabilir ve pratik bir şekilde detaylı analizler ortaya koyuyoruz. Kullanıcıların yatırımlarını takip ve analizini otomatik ve güvenilir bir şekilde gerçekleştiriyoruz. Kullanıcı dostu arayüzümüz ile kullanım kolaylığı ve kolay anlaşılabilirlik sağlayarak geniş bir kullanıcı kitlesine ulaşmayı hedefliyoruz. Esnek ve kolay adapte edilebilir olan projemiz ile kullanıcıların finansal aygıtları daha verimli ve kolay kullanabilmeleri yönünde inovatif bir çözüm sunuyoruz.

## Yapılacaklar

### Genel
- **Gerekli Python Kütüphanelerini Bulmak**: Python içinde kullanılacak özellikle UI için kütüphaneleri bulmak gerek. Duruma göre sıfırdan kütüphane öğrenmek gerekebilir.
- **Site ve UI Tasarımı**: Site akış tasarımı ve UI tasarımının nerede ve nasıl yapılacağına karar vermek gerek. Canva vs. ne kullanılacak, bu tasarımlar nasıl yapılacak vb.

### Frontend ve UI
- **Site Tasarımı**: Kullanıcı siteye girince ne görecek. Özellikle ön prototip için tek bir yol oluşturulması gerek. Örneğin: 
	- Kod çalıştı site ana ekranı
	- Kullanıcı giriş sayfası
	- Kullanıcı ana ekranı
	- Yapılacak bir işlem ekranı etc.
- **Tema Belirlenmesi**: Site sayfalarının arasında alakalı renk paletleri ve simgeler belirlenmesi.
- **Asıl UI Tasarımı**: Tema ve site tasarımını birleştirilerek kullanıcının göreceği son halin hazırlanması.
- **UI Entegrasyonu**: Tasarımların kolaylıkla python içine aktarılabilmesi gerek. Özellikle kullanılacak python kütüphanesine bağlı olarak sıfırdan kütüphane öğrenmek gerekebilir. 

### API ve Veritabanı
- **Veritabanı Ortamı**: Ön prototip için verilerin çekileceği lokal dosyanın seçilmesi. Çok büyük ihtimalle .csv ya da .xlsm gibi bir dosya oluşturulacak.
- **Sahte Verilerin Üretilmesi**: Ön prototip için gerekli olan verilerin üretilmesi.
- **Verilerin Ön İşlenmesi**: Kullanılacak verilerin, veri doğasına göre ön işlenmeden geçirilip en sona hatasız ve boşluksuz, ön prototipi bozmayacak şekilde düzenlenmesi.
- **Verilerin Formatlanması**: Verilerin seçilen dosya formatına uygun olarak dosya içine kaydedilmesi.

### Backend ve Python
- **Standart Proje Hazırlıkları**: Basit bir proje için bile gerekli python ortamının kurulması ve git klasörü hazırlanması gibi yapılması gereken adımlar.
- **Sistem Mimarisinin Belirlenmesi**: Python içinde en azından ön prototipte ne göstereceğimize bağlı olarak gerekli hesaplamalar, akış kontrolleri, nesneler ve fonksiyonların mimarisi/ön planı yapılmalı.
- **Belirlenen Proje Mimarisine Göre Kod Yazımı**: Belirlenen mimariye göre kod yazılması.
- **UI Entegrasyonu**: Tuş tıklamaları, kutu (textbox) doldurmaları, seçilen örnek işleme bağlı olarak görselleştirilecek veriler gibi kullanıcının doğrudan veya dolaylı olarak etkileşime gireceği bölümlerin ve dinamik kod dönütlerinin UI ile entegre edilmesi. Kullanılacak kütüphaneye göre ve örnek işleme göre karmaşıklığı değişebilir.
- **API ve Veritabanı Entegrasyonu**: Ön prototip için yapılan çakma veritabanının python içine entegrasyonu. Kullanılacak kütüphaneye ve veritabanı dosyasına göre karmaşıklığı değişebilir.

### Testler
- **Test Case'lerin Bulunması**: Kod parçalarının ve kodun tüm olarak hangi durumlar, parametreler altında test edileceğinin bulunması.
- **Kodun Parçalı Testleri**: Kod içindeki fonksiyonların bağımsız olarak çalışmalarının test edilmesi.
- **Kodun Tüm Testi**: Kodun test case'ler altında tümleşik olarak test edilmesi.
- **Testlere Bağlı Debug ve Yeniden Kodlama**: Testler sonucunda ortaya çıkan beklenmeyen durumları (bug) düzeltmek gerek. Karşılaşılacak durumlara bağlı olarak kodun bazı kısımlarının sıfırdan yazılması gerekebilir.

----
