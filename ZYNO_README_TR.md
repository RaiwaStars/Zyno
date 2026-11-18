# Zyno Launcher

Bu proje, Amethyst Android kaynak kodu temel alınarak hazırlanmış Zyno Launcher marka/tema başlangıç sürümüdür.

## Yapılan değişiklikler
- Uygulama adı Zyno Launcher olarak değiştirildi.
- Kısa uygulama adı Zyno olarak ayarlandı.
- Renk paleti açık gri/beyaz ve koyu metinlerden oluşan minimal temaya çevrildi.
- GitHub Actions iş akışı yalnızca debug APK üretip artifact olarak yükleyecek şekilde sadeleştirildi.
- Kaynak arşivinde bulunan imzalama anahtarı dosyaları çıkarıldı.

## APK oluşturma
1. Bu arşivi GitHub deposuna yükleyin veya kendi fork'unuzda commit edin.
2. GitHub > Actions bölümünde Android CI iş akışının çalışmasını bekleyin.
3. Başarılı çalışmanın Artifacts bölümünden `app-debug (recommended)` dosyasını indirin.
4. ZIP içindeki APK'yı Android cihazınıza kurun.

## Önemli
- Bu kaynak değişiklikleri burada Android SDK/NDK ile derlenip cihazda test edilmedi.
- İlk APK debug imzasıyla oluşturulur. Günlük kullanım veya dağıtım için kendi güvenli release anahtarınızla ayrıca imzalama yapılandırması gerekir.
- Uygulamanın paket kimliği ve oyun motoru/launcher mantığı değiştirilmedi.
- Amethyst'in orijinal lisansını, telif bildirimlerini ve üçüncü taraf lisanslarını koruyun.
- Submodule içerikleri GitHub'da recursive checkout gerektirir; arşiv tek başına tüm submodule kaynaklarını içermeyebilir.
