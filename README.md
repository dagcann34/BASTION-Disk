<p align="center"><img src="img/ikon.png" width="96" alt="BASTION Disk"></p>

<h1 align="center">BASTION Disk</h1>
<p align="center"><b>Diskin dolmadan önce gör.</b><br>Mac'inin istediğin kenarında duran taktik disk paneli.</p>

<p align="center"><b>Türkçe</b> · <a href="README.en.md">English</a></p>

<p align="center">
  <a href="https://github.com/dagcann34/BASTION-Disk/releases/latest"><b>⬇️ Ücretsiz indir (macOS 14+, Apple Silicon)</b></a>
  &nbsp;·&nbsp; ⭐ Pro: Mac App Store sürümünde, uygulama içinden
</p>

<p align="center"><img src="img/kapak.png" width="420" alt="BASTION Disk kapak"></p>

## Ne yapar?

- **GÖR** — Boş alan, segmentli doluluk göstergesi ve menü çubuğunda canlı sayaç.
- **BUL** — TreeSize tarzı gezgin: klasörler boyuta göre sıralı, gizli klasörler (`~/Library`, `.cache`, paket önbellekleri) dahil.
- **TEMİZLE** — Çöp'e taşı (geri alınabilir) ya da Pro ile kalıcı sil. macOS ana klasörleri korunur, hassas yerlerde ek uyarı, her kalıcı işlem onay ister.
- **DÖRT KENAR, TEK PANEL** — Panel alt, üst, sol ya da sağ kenarda durur; diğer pencereler (büyütülenler dahil) onun kenarına kadar hizalanır.
- **39 TEMA, 7 AİLE** — Yazı tipini ve arka planı sen seç, istersen kendi görselini kullan.
- **AĞ YOK, TELEMETRİ YOK** — Uygulama hiçbir sunucuya bağlanmaz.

<p align="center"><img src="img/dort-kenar.png" width="380" alt="Dört kenar"> <img src="img/temalar.png" width="380" alt="Temalar"></p>

## Ücretsiz ve Pro

Bu sayfadan indirdiğin **BASTION Disk ücretsizdir**. Lisans anahtarı satılmıyor; uygulamadaki "PRO · 1.000 TL" bağlantısı artık kullanılmıyor.

Pro özellikler, Mac App Store'da ücretsiz indirilen ayrı uygulama **BASTION Disk Pro**'nun **içinden**, tek seferlik bir uygulama içi satın almayla açılır (App Store sürümü yayına hazırlanıyor):

| BASTION Disk Pro (Mac App Store) | Ücretsiz | Pro — uygulama içi, tek seferlik |
|---|---|---|
| Boş alan göstergesi, klasör gezgini, Çöp'e taşı | ✓ | ✓ |
| Ekran kenarı paneli, menü çubuğu sayacı | ✓ | ✓ |
| İzlenen klasörler, boyut geçmişi, "ne büyüdü" | — | ✓ |
| Düşük alan ve büyüme uyarıları | — | ✓ |
| Tüm temalar, yazı tipleri, arka planlar, kendi görselin | — | ✓ |

Satın alma ve geri yükleme Apple üzerinden yapılır (**Unlock Pro…** › **Restore Purchases**). Abonelik değildir; aynı Apple hesabındaki tüm Mac'lerinde geçerlidir.
## Kurulum

1. [Releases](https://github.com/dagcann34/BASTION-Disk/releases/latest) sayfasından **`BASTION.Disk.1.4.1.dmg`** dosyasını indir.
2. DMG'yi aç, **BASTION Disk**'i **Applications** klasörüne sürükle ve oradan aç. Uygulama Developer ID ile imzalı ve Apple noterliğinden (notarization) geçmiştir; ek onay adımı gerekmez.
3. **İzinler (bir kez):** Sistem Ayarları › Gizlilik ve Güvenlik:
   - **Erişilebilirlik** → BASTION Disk'i aç (pencere hizalama için).
   - **Tam Disk Erişimi** → BASTION Disk'i aç (klasörler için tek tek izin sorulmaz).

## Bütünlük doğrulama

İndirdiğin dosyaların değişmediğini Terminal'de doğrulayabilirsin (`SHA256SUMS` dosyasını DMG ile aynı klasöre indir):

```
shasum -a 256 -c SHA256SUMS
```

```
e0d0ab9c0e2c13eb87b6b52167b38155e2f7132fc46581ea280c979232c2cb94  BASTION.Disk.1.4.1.dmg
```

## Güvenlik notları

- Ağ erişimi yok; telemetri yok. Hardened Runtime açık; tek ek yetki Çöp Kutusu'nu boşaltmak için Finder'a komut (Apple Events).
- macOS ana klasörlerinin kendisi ve sistem bölümü silinemez; kalıcı her işlem ayrıca onay ister; yönetici silmesi yalnız macOS'un kendi parola penceresiyle yapılır.
- Developer ID ile imzalı, Apple noterliğinden geçmiş ve damgalıdır (stapled).

## Kaldırma

Releases'taki **`BASTION.Disk.i.Kaldir.command`** dosyasını çalıştır: uygulamayı Çöp'e taşır, açılış kaydını ve ayarları siler.

---

© 2026 Dağcan Nural · BASTION. Tüm hakları saklıdır. Bu depo yalnız kurulum dosyalarını ve belgeleri barındırır; kaynak kod yayımlanmaz. Uygulama ücretsiz sürüm olarak kişisel ve ticari kullanıma açıktır; Pro özellikler yalnız satın alınmış lisans anahtarıyla kullanılabilir. Yazılım "olduğu gibi" sunulur.
