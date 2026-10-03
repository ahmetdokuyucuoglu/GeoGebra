MİMARİ ESERLERDEN GEOMETRİK MODELLERE
GitHub Pages için hazır arayüz

Bu paket bir tanıtım sayfası, kitapçıktaki sekiz mimari eser için model
kartları ve yapı/model karşılaştırma pencereleri içerir. Tüm görseller
index.html içine eklenmiştir. Sayfa ek bir kurulum gerektirmez.

ÖNİZLEME
index.html dosyasına çift tıklayın. Telefon görünümü ekran genişliğine
göre otomatik düzenlenir. Kartlardaki Modeli incele düğmesini kullanın.
Galata Kulesi gerçek etkileşimli model dosyası bu pakete eklenmiştir.
Galata kartında Etkinliği aç düğmesi görünür. Diğer eserler için
etkinlik dosyaları henüz eklenmediğinden Yakında yazısı görünür.

GITHUB'A YÜKLEME
1. GitHub'da mimari-modeller adında Public bir depo oluşturun.
2. ZIP paketini bilgisayarınızda açın.
3. index.html ve models klasörünü Add file > Upload files yoluyla yükleyin.
   index.html deponun ana seviyesinde bulunmalıdır.
   ZIP dosyasını doğrudan yüklemek sayfayı yayımlamaz; içeriğini yükleyin.
4. Settings > Pages bölümüne girin.
5. Source: Deploy from a branch, Branch: main, Folder: / (root) seçin.
6. Save düğmesine basın. Yayınlandıktan sonra Visit site ile sayfayı açın.
7. Yayımlanan adresi karekoda ekleyin ve telefonla kontrol edin.

GALATA KULESİ ETKİNLİĞİ
models/galata.html, kullanıcının gönderdiği .ggb dosyasını HTML içinde
barındırır. Ayrı model dosyası indirmeden modeli tarayıcıya yükler.
GeoGebra kütüphanesinin yüklenmesi için internet bağlantısı gerekir.
models/galata.ggb, özgün dosyanın değişmeden kopyalanmış halidir;
GeoGebra uygulamasında açmak için indirme bağlantısından erişilir.

Galata kartını açıp Etkinliği aç düğmesine basın. Bilgisayarda model
ve sürgüler görünür; telefonda ilk açılışta 3B model görünür.
Model ve sürgüler düğmesiyle kaydedilen 2B kontrolleri açabilirsiniz.

Galata sayfasına doğrudan karekod oluşturmak için şu adresi kullanın:
https://KULLANICI_ADIN.github.io/mimari-modeller/models/galata.html

MODEL DOSYALARINI BAĞLAMA
1. Hazır HTML etkinliklerinizi models klasörüne yerleştirin.
   HTML'in kullandığı ayrı .ggb, .glb, görsel, .js veya .css dosyaları
   varsa ilgili klasör yapısını ve bağlantı yollarını koruyun.
2. index.html dosyasını bir metin düzenleyicide açın.
3. ETKINLIKLER ifadesini arayın. Eserlerin yanındaki boş tırnaklara
   ilgili dosyanın yolunu yazın. Örneğin:

   'galata-kulesi': 'models/galata.html',
   'kabe': 'models/kabe.html',

4. Kaydedip güncel index.html ile model dosyalarını aynı depoya yükleyin.
   Bağlanan eserlerde Etkinliği aç düğmesi otomatik görünür.

ÖNERİLEN DOSYA ADLARI
tophane.html, kabe.html, galata.html, safranbolu.html,
kilicarslan.html, kolezyum.html, louvre.html, kubbetus-sahra.html
Dosya adlarında küçük harf ve boşluksuz adlar kullanmak kolaylık sağlar.

HER ESER İÇİN AYRI KAREKOD
Galeri yayın adresi:
https://KULLANICI_ADIN.github.io/mimari-modeller/

Belirli eserin penceresini doğrudan açmak için adresin sonuna
aşağıdaki değerlerden birini ekleyin. Bu adresleri karekoda dönüştürebilirsiniz:

?eser=tophane-saat-kulesi
?eser=kabe
?eser=galata-kulesi
?eser=safranbolu-saat-kulesi
?eser=kilicarslan-kumbeti
?eser=kolezyum
?eser=louvre-piramidi
?eser=kubbetus-sahra

Örnek:
https://KULLANICI_ADIN.github.io/mimari-modeller/?eser=galata-kulesi

DOSYA BOYUTU VE AR
GitHub'ın tarayıcı yükleme sınırı dosya başına 25 MiB'dir.
.ggb modelini HTML içine gömdüğünüzde son HTML dosyası daha büyük olabilir.
Bu arayüz karekodla erişimi ve etkinlik bağlantılarını düzenler.
AR özelliği, bağladığınız model/etkinlik dosyasının ve telefonun desteklemesine bağlıdır.

GÖRSELLER
Yapı fotoğrafları ve GeoGebra model görselleri, kullanıcının paylaştığı
Mimari Eserlerden Geometrik Modellere kitapçığından alınmıştır.
Bu sürümde tarihsel açıklamalar yerine modelde kullanılan geometrik
cisimler gösterilmiştir. Galata modelinin kendisi ve önizlemesi
kullanıcının gönderdiği Galata Kulesi_1.ggb dosyasından alınmıştır.

DOĞRULAMA
HTML/JavaScript yapısı, dosya yolları ve gömülü modelin özgün dosyayla
aynı olduğu kontrol edilmiştir. Canlı GeoGebra yüklemesi bu ortamda
tarayıcıyla doğrulanamamıştır; yayımladıktan sonra telefonda deneyin.
