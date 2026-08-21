# Onrcvndev CloudStream Eklentileri

Türkçe içerik sağlayıcıları için derlenmiş CloudStream eklenti deposu.

Bu depoda kaynak kodu bulunmaz. Yalnızca CloudStream tarafından indirilen `.cs3` dosyaları, `plugins.json` ve depo manifesti yayınlanır.

## Kurulum

1. CloudStream uygulamasını cihazınıza kurun.
2. Aşağıdaki bağlantıyı cihazınızda açarak depoyu CloudStream'e ekleyin:

   [Depoyu CloudStream'e ekle](http-protocol-redirector?r=cloudstreamrepo://raw.githubusercontent.com/onrcvndev/onrcvndev-cs3/main/repo.json)

Alternatif olarak CloudStream depo ekleme ekranına şu adresi yazabilirsiniz:

```text
https://raw.githubusercontent.com/onrcvndev/onrcvndev-cs3/main/repo.json
```

## Yayınlanan eklentiler

- AnimeciX
- AsyaAnimeleri
- BelgeselX
- CizgiMax
- Ddizi
- DiziBox
- DiziKorea
- DiziMom
- DiziPal
- DiziPalOriginal
- Dizilla
- FilmMakinesi
- FullHDFilmizlesene
- HDFilmCehennemi
- KultFilmler
- RareFilmm
- SezonlukDizi
- SinemaCX
- TRasyalog
- WebteIzle

Eklenti sürümleri ve erişilebilirlik bilgileri `plugins.json` dosyasından otomatik olarak okunur.

## Sorun bildirimi

Eklenti çalışmıyor, bir provider güncel değil veya depo eklenemiyorsa [issue açabilirsiniz](https://github.com/onrcvndev/onrcvndev-cs3/issues). Bildirime eklenti adını, CloudStream sürümünü ve mümkünse hata bilgisini ekleyin.

## Dağıtım modeli

- Kaynak proje ayrı ve özel bir depoda tutulur.
- Derleme işlemi sonucunda yalnızca `.cs3` paketleri public depoya gönderilir.
- CloudStream güncellemeleri `plugins.json` içindeki dosya adreslerinden alır.

## Lisans

Dağıtılan eklentiler, ilgili kaynak ve sağlayıcıların lisans koşullarına tabidir.
