# OfisApp · Fişleri Çek, Klasörle, WhatsApp'tan Gönder

[![Son Sürüm](https://img.shields.io/github/v/release/muhasebeahmetozmen/OfisApp-Mobil?label=son%20s%C3%BCr%C3%BCm&color=0F766E)](https://github.com/muhasebeahmetozmen/OfisApp-Mobil/releases/latest)
[![Toplam İndirme](https://img.shields.io/github/downloads/muhasebeahmetozmen/OfisApp-Mobil/total?label=toplam%20indirme&color=115E59)](https://github.com/muhasebeahmetozmen/OfisApp-Mobil/releases)
![Platform](https://img.shields.io/badge/platform-Android%207.0%2B-2CB7A8)
![Boyut](https://img.shields.io/badge/boyut-~2%2C8%20MB-334155)

**Muhasebe bürosunda fiş ve fatura fotoğraflarını telefonla çekip klasörlere ayıran, bir klasörün tamamını tek bir ZIP ya da PDF hâline getirip ofisin WhatsApp'ına gönderen Android uygulaması.** Daha önce elle yapılan dört adımı — fotoğrafı çek, dosya yöneticisinde sıkıştır, gönder, sonra fotoğrafları tek tek sil — tek uygulamaya indiriyor. Belgeler telefondan çıkmaz, uygulama depolama izni istemez, reklam ve takip yoktur.

> ℹ️ Bu depo yalnızca **kurulum dosyalarını** (APK) ve **sürüm bilgisini** (`latest.json`) barındırır. Uygulamanın **kaynak kodu burada değildir** ve yayınlanmayacaktır. Depoda hiçbir fiş, belge veya müşteri bilgisi bulunmaz. Depo herkese açıktır; sebebi tekniktir, aşağıda anlatılıyor.

### [⬇️  Programı İndir](../../releases/latest)

<sub>Android 7.0 ve üzeri · Türkçe arayüz · Play Store'da değildir</sub>

---

## Eskiden nasıldı, şimdi nasıl?

| Adım | Eskiden | OfisApp ile |
| --- | --- | --- |
| 📷 Çekmek | Kamera uygulamasıyla çekersiniz; her fişten sonra ekrana dokunmanız gerekir | Fişi değiştirirsiniz, uygulama 3/5/8 saniyede bir kendi çeker |
| 📁 Ayırmak | Fotoğraflar galeriye karışır, sonradan ayıklarsınız | Fotoğraf doğrudan ilgili klasöre düşer |
| 🗜️ Tek dosya yapmak | Dosya yöneticisinde seçer, sıkıştırır, adını düzeltirsiniz | Klasörün tamamı tek adımda `.zip`, `.pdf` ya da ikisi birden |
| 📤 Göndermek | Dosyayı bulup paylaşırsınız | Üretilen dosyayı gönderirsiniz; Geçmiş'ten yeniden de gönderilebilir |
| 🧹 Temizlemek | Fotoğrafları galeriden tek tek silersiniz | Klasörü çöp kutusuna atarsınız, yanlışlıkla gidenler geri alınabilir |

## Ne işe yarar?

| Araç | Ne yapar |
| --- | --- |
| 📷 **Kamera** | Flaş, ızgara çizgileri, ön/arka kamera, dokunarak odak, çift parmakla yakınlaştırma, titreşimli geri bildirim |
| ⏱️ **Otomatik ve seri çekim** | 3, 5 ya da 8 saniyede bir kendiliğinden çeker; deklanşöre basılı tuttuğunuz sürece arka arkaya kare alır. Çekimden sonra kamerada kalmayı ya da klasöre dönmeyi siz seçersiniz |
| 📂 **Klasörler** | Klasörleri ve fotoğrafları tek tek, toplu ya da **parmağı sürükleyerek** seçme (telefon galerilerindeki gibi), kes/kopyala/yapıştır, klasör birleştirme, ad değiştirme, sıralama (yeniden eskiye, eskiden yeniye, ada göre) |
| ✂️ **Fotoğraf düzenleme** | Eğri çekilen fişin açısını düzeltme (hizalama ızgarasıyla), kenarlarını kırpma, sola/sağa çevirme ve aynalama. Yapılan hiçbir işlem fotoğrafın kendisine işlenmez: orijinal dosya olduğu gibi kalır, istediğiniz an "Aslına dön" diyebilirsiniz |
| 📦 **Çıktı** | Klasörün tamamı `.zip`, `.pdf` ya da ikisi birden — karşı taraf hangisini istiyorsa |
| 🖼️ **Fotoğraf kalitesi** | Orijinal (2–5 MB/belge), Yüksek 2400 px (600–800 KB), Orta 1600 px (250–400 KB): okunaklılık ile dosya boyutu arasında seçim |
| 🏷️ **Dosya adı** | Önek + tarih biçimi seçilir (örn. `OfisApp_2026-09-06_1430.zip`), gelen dosya karşı tarafta da anlaşılsın diye |
| 🗑️ **Çöp kutusu** | Silinen klasör ve fotoğraflar 3 / 7 / 14 / 30 gün saklanır ve geri alınabilir; "Asla" seçilirse süresiz saklanır, çöp kutusu kendiliğinden hiç boşalmaz |
| 🕘 **Geçmiş** | Üretilen ZIP/PDF dosyaları durur. Mesaj gitmediyse, yanlış sohbete gittiyse ya da biri "bir daha atar mısın" derse dosyayı yeniden üretmeye gerek yok, Geçmiş'ten tekrar gönderilir |
| 🎨 **Tema** | Açık, koyu ya da telefonun ayarına uyan görünüm |

---

## Nasıl kullanılır?

1. **Modüller** ekranından **Fiş & Fatura** modülüne girin.
2. Klasör listesinden bir klasör açın — içindeki fotoğraflar ızgara hâlinde görünür.
3. Kamerayı açıp fişleri çekin. Deklanşöre **basılı tutarsanız** seri çekim yapar. **Otomatik çekimi** açarsanız telefonu masaya dayarsınız ve sadece fişi değiştirirsiniz; ekrana hiç dokunmadan sıra sıra fiş çekilir.
4. Klasörü **ZIP** veya **PDF** olarak üretin ve WhatsApp'tan ofise gönderin.

Üstteki yol çubuğu (**Modüller > Fiş & Fatura > klasör > …**) ve soldan açılan menü, nerede olduğunuzu kaybetmeden gezinmenizi sağlar.

---

## Kurulum

İlk kurulum yalnızca bir kez yapılır; sonraki sürümler uygulamanın kendi güncelleme şeridiyle gelir. **Bütün işlemi telefonun kendisinden yapın**, bilgisayardan değil.

1. **İndirin.** Yukarıdaki **⬇️ Programı İndir** bağlantısına dokunun ve adı `.apk` ile biten dosyayı indirin.
2. **Tarayıcının sorusunu geçin.** "Bu tür dosyalar telefonunuza zarar verebilir" gibi bir uyarı çıkarsa **Yine de indir** deyin.
3. **Dosyayı açın.** İndirme bitince bildirime dokunun. Bildirimi kaçırdıysanız **Dosyalar > İndirilenler** içinden `.apk` dosyasına dokunun.
4. **İzni verin.** Android *"bu kaynaktan uygulama yüklenemiyor"* derse açılan ekrandan **Bu kaynaktan izin ver**'i açıp geri dönün. Bu izin yalnızca indirmeyi yaptığınız uygulamaya (tarayıcı ya da Dosyalar) verilir.
5. **Yükle > Aç.** Uygulama yalnızca **kamera** izni ister; depolama izni istemez.

> ⚠️ **Android "bilinmeyen kaynak" ya da "güvenli olmayabilir" uyarısı verirse:** APK imzalıdır, ancak ticari bir sertifikayla değil — o kurumsal ve ücretli bir hizmettir. Play Store dışından kurulan her uygulamada bu uyarı çıkar. Bu uyarı "dosyada zararlı bir şey bulundu" demek değildir; "bu yayıncıyı tanımıyorum, sorumluluk sende" demektir. **Yine de yükle** diyerek devam edebilirsiniz.

### Xiaomi / Redmi / POCO (MIUI) telefonlarda iki ek adım

1. "Bu kaynaktan izin verin" onayından sonra Xiaomi kendi **"Tehlike / Yine de kur"** ekranını gösterir — **Yine de kur**.
2. Google Play Protect **"Uygulamanın taranması öneriliyor"** derse: **Diğer ayrıntılar** > **Taramadan yükle**.

Bu iki adım genellikle yalnızca ilk kurulumda çıkar; sonraki güncellemelerde çoğunlukla karşınıza çıkmaz.

---

## Güncelleme nasıl geliyor?

Uygulama **her açıldığında ve arka plandan her dönüşünde** bu depodaki `latest.json` dosyasına bakar; iki denetim arasında en az **15 dakika** bırakılır. Yeni sürüm varsa ekranın üstünde bir şerit, klasörlerin içindeyken de yan menüde bir satır gösterir:

1. Şeride dokunursunuz, APK indirilir.
2. Uygulama dosyanın **SHA-256** özetini doğrular (yani indirilenin bozulmadığından emin olunur); tutmazsa kurulumu başlatmaz.
3. Android'in kendi kurulum ekranı açılır. Son **Yükle** dokunuşu her zaman sizindir — sessiz kurulum Android'de mümkün değildir.

Güncelleme mevcut kurulumun üzerine gelir: **fişleriniz ve ayarlarınız korunur.** Uygulamayı silip yeniden kurmak ise fişleri de siler; güncellerken **kaldırmayın, üzerine kurun.**

Bunu mümkün kılan şey her sürümün **aynı anahtarla** imzalanmasıdır. Aynı anahtarın ikinci bir sonucu daha var: başkasının ürettiği bir dosya, OfisApp'in güncellemesi gibi kurulamaz; Android imza uyuşmadığında kurulumu reddeder.

**Elle güncelleme:** İsterseniz **⬇️ Programı İndir** bağlantısından yeni APK'yı indirip kurabilirsiniz. O da mevcut kurulumun üzerine geçer, veriler korunur.

> **Güncelleme denetimini istemiyorsanız:** **Ayarlar > Güncelleme**'den kapatın. Kapalıyken uygulama **kendiliğinden** internete çıkmaz; yalnızca siz "Şimdi denetle" derseniz bakar. Yeni sürümü [Sürümler](../../releases) sayfasından elle indirip de kurabilirsiniz.

---

## Sorun giderme

**"Uygulama yüklenemedi" / kurulum ekranı açılmıyor**
İndirme yarım kalmış olabilir. **Dosyalar > İndirilenler** içindeki yarım APK dosyasını silin, bağlantı düzgünken yeniden indirin.

**"Bu kaynaktan uygulama yüklenemiyor" yazıyor**
Kurulumun 4. adımındaki izin verilmemiş demektir. Uyarı ekranından **Bu kaynaktan izin ver**'i açın, geri dönün ve `.apk` dosyasına tekrar dokunun.

**Güncelleme şeridi görünmüyor**
Sırayla kontrol edin: **Ayarlar > Güncelleme** ekranındaki "Son denetim" satırına bakın — denetimin gerçekten yapılıp yapılmadığını orada görürsünüz · telefonda internet bağlantısı var mı · **Ayarlar > Güncelleme** kapalı olabilir · zaten en son sürümde olabilirsiniz, buradaki [son sürüm](../../releases/latest) numarasıyla karşılaştırın. Acelesi varsa elle güncelleme her zaman çalışır.

**Kamera açılmıyor, siyah ekran**
Kamera izni reddedilmiş olabilir: **Telefon Ayarları > Uygulamalar > OfisApp > İzinler > Kamera > İzin ver.**

**Yanlışlıkla silinen klasör veya fotoğraf**
Uygulamanın **çöp kutusuna** bakın; silinenler seçtiğiniz süre boyunca (3 / 7 / 14 / 30 gün, ya da "Asla" seçiliyse süresiz) orada durur ve geri alınabilir.

---

## Gizlilik: ne telefonda kalır, ne dışarı çıkar?

Çektiğiniz belgeler ve üretilen ZIP/PDF dosyaları **yalnızca telefonda**, uygulamanın kendi alanında durur. Hiçbir sunucuya gönderilmez, reklam ve takip yoktur.

| İşlem | OfisApp internete çıkar mı? |
| --- | --- |
| 📷 Fiş çekmek, klasörlemek, silmek | Hayır |
| 📦 ZIP / PDF üretmek | Hayır |
| 🕘 Geçmişteki bir dosyayı yeniden göndermek | Hayır |
| 🔄 "Yeni sürüm var mı?" denetimi | Evet — dışarıya hiçbir bilgi göndermeden depodaki sürüm dosyası okunur |

**Ayarlar > Güncelleme**'den kapatırsanız uygulama **kendiliğinden** internete çıkmaz; bağlantı yalnızca siz "Şimdi denetle" dediğinizde kurulur.

### İzinler ve gerekçeleri

| İzin | Ne için |
| --- | --- |
| 📷 Kamera | Fiş fotoğrafını çekmek için |
| 🌐 İnternet | Yalnızca güncelleme denetimi ve yeni sürümün indirilmesi için |
| 📥 Bilinmeyen kaynaktan kurulum | Uygulama Play Store'da olmadığı için kurulumun ve güncellemenin yapılabilmesi adına |
| 🚫 Depolama | **İstenmez.** Uygulama kendi özel dizinini kullandığı için telefonun galerisine veya dosyalarına erişmesi gerekmez |

> ⚠️ **Uygulamayı kaldırmayın.** Belgeler yalnızca uygulamanın kendi alanında durduğu için, uygulamayı kaldırmak fişleri de siler. Kaldırmak zorunda kalırsanız önce klasörleri ZIP/PDF olarak üretip WhatsApp'tan kendinize gönderin.

---

## Bu depo neden herkese açık?

Teknik bir zorunluluk. Depo özel olsaydı, uygulamanın güncellemeyi indirebilmesi için içine bir erişim anahtarı gömülmesi gerekirdi ve APK'yı açan herkes o anahtarı okuyabilirdi. Depoyu açık tutmak bu yüzden daha güvenli; burada duran tek şey kurulum dosyaları ve sürüm bilgisidir.

## Kaynak kod neden burada değil?

Uygulama tek bir muhasebe bürosunun kendi işi için yazıldı ve iç kullanıma yöneliktir; kaynak kod yayınlanmıyor. Bu depoda katkı, hata kaydı veya kod inceleme süreci yoktur.

---

## Sürümler

En güncel sürüm numarası yukarıdaki **son sürüm** rozetinde görünür. Bütün kurulum dosyaları — eski sürümler de dahil — [Sürümler](../../releases) sayfasında durur; bir sorun çıkarsa önceki sürüme dönebilirsiniz.

<sub>Bu depo daha önce <code>muhasebeahmetozmen/ofisapp-surumler</code> adıyla yayındaydı; yeni adı <code>muhasebeahmetozmen/OfisApp-Mobil</code>'dir.</sub>