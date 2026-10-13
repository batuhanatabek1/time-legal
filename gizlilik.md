# TiMe — Gizlilik Politikası

**Son güncelleme:** 13 Ekim 2026
**Yürürlük tarihi:** 13 Ekim 2026

---

## Kısaca

TiMe bir adet döngüsü takip uygulamasıdır. Verileriniz **varsayılan olarak
yalnızca telefonunuzda saklanır.** Hesap açmanız gerekmez. Sunucularımızda
döngü verinizi tutmuyoruz. Reklam ağlarıyla veri paylaşmıyoruz. Uygulamada
analitik yazılımı bulunmuyor.

Verinin cihazınızdan çıktığı durumlar sınırlıdır ve her biri sizin açık
tercihinize bağlıdır:

1. **Yapay zekâ yorumu ve sohbeti** — cihaz üstü model kullanılamadığında
   ve siz açıkça onay verdiğinizde
2. **Apple Sağlık (HealthKit)** ile veri alışverişi — siz izin verdiğinizde
3. **Abonelik işlemleri** — satın alma yaptığınızda

Her birinin ayrıntısı aşağıdadır.

---

## 1. Veri sorumlusu

| | |
|---|---|
| Unvan | Batuhan Atabek |
| Adres | [ADRES — DOLDURULACAK] |
| E-posta | atabeksoft+privacy@gmail.com |
| VERBİS kaydı | [VERBİS DURUMU — DOLDURULACAK] |

Bu politika yalnızca TiMe iOS uygulaması için geçerlidir.

---

## 2. İşlenen veriler

### 2.1 Cihazınızda kalan veriler

Aşağıdaki veriler cihazınızın yerel veritabanında saklanır ve
**sunucularımıza gönderilmez:**

- Adet başlangıç ve bitiş tarihleri, döngü uzunlukları
- Kanama yoğunluğu
- Belirtiler (fiziksel, ruh hali, akıntı, cilt, sindirim, uyku, enerji)
- Cinsel aktivite kayıtları
- Bazal vücut sıcaklığı, kilo, ovülasyon testi sonuçları
- Serbest metin notlarınız
- Uygulama tercihleriniz (dil, birim, bildirim saatleri)
- Yapay zekâ sohbet geçmişiniz

Bu verilerin bir kısmı **özel nitelikli kişisel veri** (sağlık verisi ve
cinsel hayata ilişkin veri) niteliğindedir. Varsayılan mimarimiz bu
nedenle cihaz üstü saklamadır.

### 2.2 Cihazdan çıkabilecek veriler

**a) Yapay zekâ yorumu ve sohbeti**

TiMe, döngünüz hakkında yorum üretmek için önce **cihazınızın kendi yapay
zekâ modelini** kullanır. Bu durumda hiçbir veri cihazınızdan çıkmaz.

Cihazınız bu modeli desteklemiyorsa size bir kez sorulur ve **yalnızca
onay verirseniz** aşağıdaki veriler şifreli bağlantı üzerinden bir aracı
sunucuya ve oradan yapay zekâ sağlayıcısına iletilir:

Gönderilen:
- Döngü uzunluklarınız (yalnızca sayılar)
- İçinde bulunduğunuz döngü evresi
- Seçtiğiniz belirti etiketleri
- Sohbet ekranına **kendi yazdığınız mesajlar**
- Arayüz diliniz

Gönderilmeyen:
- Adınız, e-postanız, doğum tarihiniz
- Konum bilginiz
- Cihaz kimliğiniz veya reklam kimliğiniz
- Tam tarihler
- Günlük kayıtlarınızdaki serbest metin notlar

Bu onayı Ayarlar ekranından istediğiniz an geri alabilirsiniz. Geri
aldığınızda uygulama kural tabanlı yorumlamaya döner ve çalışmaya devam
eder.

**Önemli:** Sohbet ekranına yazdığınız metin, yazdığınız şekilde
sağlayıcıya iletilir. Kimliğinizi belirleyebilecek bilgileri sohbete
yazmamanızı öneririz.

**b) Apple Sağlık (HealthKit)**

İzin verdiğinizde adet akışı, bazal vücut sıcaklığı ve ilgili kayıtlar
Apple Sağlık uygulamasıyla karşılıklı aktarılır. Bu veri cihazınızda
kalır, bize gönderilmez.

Apple Sağlık'tan aldığımız veriyi **reklam, pazarlama veya veri
madenciliği amacıyla kullanmayız ve üçüncü taraflarla paylaşmayız.** Bu,
Apple'ın geliştirici koşullarının da bir gereğidir.

**c) Abonelik ve satın alma**

Abonelik satın aldığınızda işlem Apple tarafından gerçekleştirilir. Ödeme
bilgilerinize (kart numarası vb.) **hiçbir şekilde erişimimiz yoktur.**
Abonelik durumunu takip etmek için RevenueCat hizmetini kullanıyoruz; bu
hizmete yalnızca anonim bir kullanıcı kimliği ve abonelik durumu iletilir,
döngü veriniz iletilmez.

**d) Kötüye kullanım önleme**

Yapay zekâ isteklerinin kötüye kullanılmasını önlemek için cihazınızda
rastgele üretilen bir kimlik (UUID) kullanılır. Bu kimlik sizinle
ilişkilendirilemez, yalnızca günlük istek sayısını saymak için kullanılır
ve uygulama silindiğinde sıfırlanır.

### 2.3 Toplamadığımız veriler

- Ad, soyad, e-posta, telefon numarası
- Konum bilgisi
- Reklam kimliği (IDFA)
- Kişi listesi, fotoğraflar, kamera, mikrofon
- Kullanım analitiği (uygulamada analitik yazılımı bulunmamaktadır)

### 2.4 Şu an sunulmayan özellikler

Uygulama **bulut eşitleme (iCloud) sunmamaktadır.** Verileriniz cihazlar
arasında eşitlenmez. Bu özellik ileride eklenirse bu politika güncellenir
ve rızanız ayrıca istenir.

---

## 3. İşleme amaçları ve hukuki sebep

| Amaç | Veri | Hukuki sebep |
|---|---|---|
| Döngü tahmini ve takip | Döngü ve belirti verileri | Açık rıza |
| Yapay zekâ yorumu (cihaz üstü) | Döngü ve belirti verileri | Açık rıza |
| Yapay zekâ yorumu (uzak sağlayıcı) | §2.2(a)'daki veriler | Ayrıca alınan açık rıza |
| Apple Sağlık entegrasyonu | Sağlık kayıtları | Açık rıza |
| Bildirim gönderimi | Tahmin tarihleri, seçtiğiniz saatler | Açık rıza |
| Abonelik yönetimi | Anonim kimlik, abonelik durumu | Sözleşmenin ifası |
| Kötüye kullanım önleme | Rastgele cihaz kimliği | Meşru menfaat |

Özel nitelikli kişisel veriler yalnızca **açık rızanız** ile işlenir.
Rızanızı istediğiniz an geri alabilirsiniz.

---

## 4. Yurt dışına aktarım

Yapay zekâ yorumu için uzak sağlayıcı kullanmayı onaylarsanız, §2.2(a)'da
listelenen veriler yurt dışında bulunan sunuculara aktarılır.

| Alıcı | Rol | Ülke |
|---|---|---|
| Cloudflare, Inc. | Aracı sunucu (proxy) | ABD |
| Google LLC | Yapay zekâ sağlayıcısı (Gemini) | ABD |

Bu aktarım, KVKK kapsamında **açık rızanıza** dayanmaktadır. Onay
vermezseniz hiçbir veriniz yurt dışına aktarılmaz ve uygulama cihaz üstü
ve kural tabanlı olarak çalışmaya devam eder.

Aracı sunucumuz sağlık verinizi **kayıt altına almaz (loglamaz).**

Google'ın veri işleme uygulamaları için:
https://ai.google.dev/gemini-api/terms

---

## 5. Saklama süresi

- **Cihazdaki veriler:** Siz silene kadar. Uygulamayı sildiğinizde
  cihazdaki tüm veriler de silinir.
- **Uzak sağlayıcıya gönderilen veriler:** Yanıt üretildikten sonra
  tarafımızca saklanmaz.
- **Kötüye kullanım önleme kimliği:** 24 saat.
- **Abonelik kayıtları:** Yasal saklama süresi boyunca, Apple ve
  RevenueCat nezdinde.

---

## 6. Haklarınız

KVKK m.11 ve GDPR kapsamında şu haklara sahipsiniz:

- Kişisel verilerinizin işlenip işlenmediğini öğrenme
- İşlenmişse bilgi talep etme
- İşlenme amacını ve amacına uygun kullanılıp kullanılmadığını öğrenme
- Yurt içinde veya yurt dışında aktarıldığı üçüncü kişileri bilme
- Eksik veya yanlış işlenmişse düzeltilmesini isteme
- Silinmesini veya yok edilmesini isteme
- Düzeltme ve silme işlemlerinin aktarılan üçüncü kişilere bildirilmesini
  isteme
- Otomatik sistemlerle analiz sonucu aleyhinize bir sonuç doğmasına itiraz
  etme
- Zarara uğramanız halinde zararın giderilmesini talep etme

**Pratikte:** Verilerinizin çoğu yalnızca cihazınızda olduğu için bu
hakların bir kısmını doğrudan uygulama içinden kullanabilirsiniz:

- **Görme ve taşınabilirlik:** Ayarlar → Veriyi dışa aktar
- **Silme:** Ayarlar → Tüm veriyi sil
- **Rıza geri alma:** Ayarlar → Yapay zekâ onayı

Diğer talepleriniz için: atabeksoft+privacy@gmail.com

Başvurularınız en geç 30 gün içinde yanıtlanır. Yanıttan memnun
kalmazsanız Kişisel Verileri Koruma Kurulu'na şikâyette bulunabilirsiniz.

---

## 7. Çocukların gizliliği

TiMe 13 yaş altı çocuklara yönelik değildir ve bilerek 13 yaş altı
kullanıcılardan veri toplamayız. Ebeveyn veya vasiyseniz ve çocuğunuzun
uygulamayı kullandığını düşünüyorsanız atabeksoft+privacy@gmail.com
adresinden bize ulaşın.

---

## 8. Güvenlik

- Veriler cihazınızda iOS'un standart uygulama sanal alanı içinde saklanır.
- İsteğe bağlı uygulama kilidi (Face ID / Touch ID) sunulur.
- Ağ üzerinden giden tüm veri TLS ile şifrelenir.
- Aracı sunucumuzda sağlık verisi loglanmaz.
- Yapay zekâ sağlayıcısına gönderilen veri asgari düzeyde tutulur.

Hiçbir sistem tamamen güvenli değildir. Cihazınızı güncel tutmanızı ve
ekran kilidi kullanmanızı öneririz.

---

## 9. Tıbbi uyarı

TiMe bilgilendirme ve kişisel takip amaçlıdır. **Tıbbi tanı, tedavi veya
doğum kontrolü yöntemi değildir.** Tahminler istatistikseldir ve
yanılabilir. Sağlığınızla ilgili kararlar için bir hekime danışın.

---

## 10. Değişiklikler

Bu politikada değişiklik yaparsak uygulama içinde bildirim gösterir ve bu
sayfanın üstündeki tarihi güncelleriz. Önemli değişikliklerde rızanızı
yeniden isteriz.

---

## 11. İletişim

**Batuhan Atabek**
[ADRES — DOLDURULACAK]
atabeksoft+privacy@gmail.com
