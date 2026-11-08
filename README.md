# 🎵 AudioHub

**Spor salonu, kafe, mağaza gibi işletmeler için ortak müzik sistemi.**
Müşteriler Telegram'dan şarkı ister, sıraya girer ve oylayıp şarkı geçer; işletme her şeyi tek bir panelden yönetir.

[**⬇️ En son sürümü indir**](https://github.com/mythbuster61/audiohub-releases/releases/latest)

---

## Nasıl çalışır?

1. **Müşteri** Telegram botuna bir YouTube linki gönderir.
2. Şarkı **sıraya** eklenir, oy alan şarkı öne geçer.
3. İşletmedeki bilgisayardan müzik çalar. Sıra boşalırsa **otomatik şarkı havuzu** devreye girer, müzik hiç susmaz.

## Neler yapar?

- 🎤 **Telegram'dan şarkı isteği:** QR kodu okut, linki gönder, şarkı çalsın.
- 🗳️ **Oylama:** Beğenilen şarkı öne çıkar, sevilmeyen şarkı oy çokluğuyla geçilir.
- 🖥️ **Yönetim paneli:** Sırayı, havuzu, ayarları ve geçmişi tarayıcıdan yönet.
- 📺 **TV ekranı:** Çalan şarkıyı ve sırayı salon televizyonunda göster.
- 📢 **Anonslar:** Zamanlanmış duyurular, ezan vakti modu.
- 🔊 **Eşit ses seviyesi:** Şarkılar otomatik dengelenir, biri diğerinden yüksek çalmaz.
- 🛡️ **İçerik kontrolü:** Uygunsuz şarkıları yakalar, yasaklama listesi tutar.
- 🔐 **Erişim modları:** Herkese açık, onaylı, günlük kodlu veya konum doğrulamalı.
- 📱 **Çalışan kontrolü:** Yetkili kişiler PC'nin başına gitmeden Telegram'dan şarkıyı geçer, siler, engeller, sesi ayarlar.
- 💬 **Dilek / şikayet kutusu:** Müşteriler fotoğraflı geri bildirim gönderebilir.
- 🔄 **Otomatik güncelleme:** Yeni sürümler bu sayfadan alınır.

## Kurulum

1. [Releases](https://github.com/mythbuster61/audiohub-releases/releases/latest) sayfasından **`AudioHubKurulum.exe`** dosyasını indir.
2. Çalıştır ve kurulumu tamamla.
3. Program açılınca yönetim paneli tarayıcıda otomatik açılır, ayarlarını oradan yap.

**Gereksinimler:** Windows 10 / 11 ve internet bağlantısı.

### İndirdiğin dosyayı doğrulamak (isteğe bağlı)

Her sürümle birlikte bir `.sha256` dosyası yayınlanır. PowerShell'de şunu çalıştırıp çıkan değeri o dosyayla karşılaştırabilirsin:

```powershell
Get-FileHash AudioHubKurulum.exe -Algorithm SHA256
```
