# SercanZurna - SS

Yayıncılar için canlı Türkçe altyazı. Oyundaki, videodaki ya da sohbetteki İngilizce konuşmayı (veya ekrandaki İngilizce altyazıyı) anında Türkçeye çevirip OBS'te yayına altyazı olarak ekler.

## İndir

👉 **[Son sürümü indir](https://github.com/fefbrk/sercanzurna-ss/releases/latest)** → `SercanZurna-SS-Setup-x.y.z.exe`

## Kurulum

1. İndirdiğin `SercanZurna-SS-Setup-...exe` dosyasını çalıştır.
2. Windows **"Windows bilgisayarınızı korudu"** derse: **"Ek bilgi"** → **"Yine de çalıştır"**.
   Uygulama henüz dijital imzalı olmadığı için bu uyarı çıkar; virüs değildir.
   Kurulum bitti ama uygulama hiç açılmıyorsa aşağıdaki [Kuruldu ama açılmıyor](#kuruldu-ama-açılmıyor-hiç-hata-vermiyor) bölümüne bak.
3. Sihirbazı izle (müziği sol alttaki **♪ Müzik** düğmesiyle kapatabilirsin).
4. Yönetici izni gerekmez. Uygulama `%LocalAppData%\Programs\SercanZurna-SS` içine kurulur; Başlat menüsünden ve (seçersen) masaüstünden açılır.
5. Kaldırmak için: Ayarlar → Uygulamalar → SercanZurna - SS → Kaldır.

### Kuruldu ama açılmıyor (hiç hata vermiyor)

Windows 11'deki **Akıllı Uygulama Denetimi** imzasız uygulamaları sessizce engelliyor. Bu uygulama henüz dijital imzalı olmadığı için açılmayabilir.

Kontrol: **Ayarlar → Gizlilik ve güvenlik → Windows Güvenliği → Uygulama ve tarayıcı denetimi → Akıllı Uygulama Denetimi ayarları**. "Açık" ise **Kapalı** yapın, sonra uygulamayı tekrar açın.

> Not: Ayarı kapattıktan sonra bilgisayarı yeniden başlatmanız gerekir.

Ayar "Kapalı" ise ve uygulama yine açılmıyorsa aşağıdaki [Sorun mu var?](#sorun-mu-var) bölümündeki adımları izleyin.

## İlk açılış

1. **Anahtarlar** sayfasına iki API anahtarını gir ve **Kaydet**:
   - **OpenRouter** (çeviri) — https://openrouter.ai/keys
   - **AssemblyAI** (ses tanıma; sadece Ses/Hibrit modunda gerekir) — https://www.assemblyai.com/dashboard
2. Modu seç:
   - **OBS Altyazı (OCR):** oyunda İngilizce altyazı varsa en iyisi (ses tanıma ücreti yok).
   - **Ses:** altyazı yoksa (video, sohbet).
3. **Başlat**'a bas. OBS açıksa altyazı kaynağı OBS'e otomatik eklenir; değilse Ayarlar'daki adresi OBS'te **Tarayıcı** kaynağı olarak ekle.

## Gereksinimler

- Windows 10/11 (64 bit)
- OBS Studio 28 veya üstü (OCR modu için: Araçlar → WebSocket Sunucu Ayarları → Etkinleştir)
- Microsoft Edge WebView2 (Windows 11'de hazır gelir)

## Sorun mu var?

Uygulamada **Ayarlar → Destek → Sorun bildir**'e bas. Masaüstüne bir zip kaydedilir (API anahtarların otomatik gizlenir). O dosyayı geliştiriciye gönder.
