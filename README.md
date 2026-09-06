# OfisApp - surum deposu

Bu depo yalnizca **OfisApp** Android uygulamasinin kurulum dosyalarini ve surum
bilgisini tutar. Kaynak kod burada degildir.

- `latest.json` : uygulamanin baktigi surum bilgisi (versionCode, indirme adresi, SHA-256)
- **Releases**    : imzali APK dosyalari

## Elle kurulum

En son APK'yi [Releases](../../releases) bolumunden indirip telefonda dosyaya
dokunarak kurabilirsiniz. Uygulama kuruluysa uzerine kurulur, fotograflariniz
ve ayarlariniz korunur.

## Guncelleme

Uygulama acilista bu depodaki `latest.json` dosyasina bakar ve yeni surum varsa
bildirir. Denetim, uygulamanin Ayarlar > Guncelleme bolumunden kapatilabilir;
kapaliyken uygulama internete hic cikmaz.
