# Kira Takip — Gizlilik Politikası

Son güncelleme: 29 Ekim 2026

Kira Takip ("uygulama"), Türkiye'deki kiracı ve ev sahipleri için yasal kira artışı hesaplayan ve hatırlatma kuran bir mobil uygulamadır. Bu politika, uygulamanın hangi veriyi nasıl işlediğini açıklar.

## Kısaca

- **Hesap yok, sunucu yok.** Girdiğin konut, kira, ödeme ve dekont bilgileri yalnızca telefonunda saklanır. Geliştiriciye veya üçüncü kişilere gönderilmez.
- **Reklam yok, analitik yok, takip yok.** Uygulamada reklam SDK'sı, analitik ya da kullanıcı takibi bulunmaz.

## Cihazda saklanan veriler

| Veri | Neden | Nerede |
|---|---|---|
| Konut adı, kira tutarı, sözleşme tarihi, zam ayı, kira günü, aidat, il, kullanım türü | Zam hesabı ve hatırlatmalar | Telefonun uygulama alanı (yerel veritabanı) |
| Ödeme kayıtları ve not | Ödeme geçmişi ve PDF ekstre | Aynı yerel veritabanı |
| Dekont fotoğrafları | Ödeme kanıtı | Uygulamanın kendi klasörü |
| Ayarlar (tema, dil, hatırlatma günü, premium durumu) | Uygulama tercihleri | Yerel veritabanı |

Bu verileri Ayarlar → "Tüm verileri sil" ile istediğin an silebilir, "Verileri dışa aktar" ile JSON olarak alabilirsin. Uygulamayı kaldırmak da tüm verileri siler. Android'in sistem yedeklemesi açıksa veriler, Google hesabına ait şifreli cihaz yedeğine dahil olabilir; bu, işletim sisteminin özelliğidir.

## İnternet bağlantısı

Uygulama yalnızca şu durumlarda internete çıkar:

1. **TÜFE verisi:** Herkese açık bir JSON dosyası (`raw.githubusercontent.com/Denizsinankaya/kira-takip-data`) indirilir. Bu istekte kişisel veri gönderilmez; GitHub, her web isteğinde olduğu gibi IP adresini teknik olarak görür.
2. **Satın alma:** Premium satın alma ve geri yükleme işlemleri Google Play veya App Store üzerinden yapılır. Ödeme bilgilerin uygulamaya gelmez; ilgili mağazanın gizlilik politikası geçerlidir.
3. **Bağlantılar:** Bu sayfa gibi dış bağlantıları açtığında tarayıcın kullanılır.

## İzinler

- **Bildirim:** Zam ayı, yazılı bildirim süresi, kira günü ve TÜFE açıklama hatırlatmaları. Hepsi cihazda planlanır.
- **Tam zamanlı alarm (Android):** Hatırlatmaların doğru saatte gelmesi için. Verilmezse hatırlatma birkaç dakika kayabilir.
- **Kamera / fotoğraflar:** Yalnızca sen dekont eklemek istediğinde. Seçilen fotoğraf uygulamanın klasörüne kopyalanır, başka yere gönderilmez.

## Paylaşım

"Zam kartı" veya PDF paylaştığında içerik, senin seçtiğin uygulamaya (WhatsApp, e-posta vb.) senin isteğinle gönderilir. Paylaşım bağlantısı yalnızca kira tutarı, zam ayı ve sözleşme başlangıcını içerir; konut adı ve kişisel bilgi içermez.

## Çocuklar

Uygulama 18 yaş altına yönelik değildir ve bilerek çocuklardan veri toplamaz.

## KVKK

Geliştirici kişisel verilerine erişmediği için veri sorumlusu sıfatıyla işlem yapmaz. Verilerin tamamen senin cihazındadır ve kontrolü sendedir.

## Değişiklikler ve iletişim

Bu politika değişirse bu sayfa güncellenir ve tarih değişir. Soruların için: <https://github.com/Denizsinankaya/kira-takip-data/issues>

---

# Kira Takip — Privacy Policy (English)

Last updated: 29 October 2026

- **No account, no server.** Properties, rents, payments and receipt photos are stored only on your device and are never sent to the developer or third parties.
- **No ads, no analytics, no tracking.**
- **Network use:** the app downloads a public CPI data file from GitHub (no personal data is sent; GitHub technically sees your IP address), and purchases are processed by Google Play / App Store under their own privacy policies.
- **Permissions:** notifications (local reminders), exact alarms on Android (on-time reminders), camera/photos only when you attach a receipt.
- **Your control:** delete everything in Settings → "Delete all data", export as JSON, or uninstall the app.
- **Children:** not directed at children under 18.
- **Contact:** <https://github.com/Denizsinankaya/kira-takip-data/issues>
