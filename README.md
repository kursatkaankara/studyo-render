# studyo-render

Bu repo, bilgisayardaki **Sağlık Videosu Stüdyosu** uygulamasının video render'larını GitHub Actions'ta almak için
kullanılır. Dosyaları uygulama yazar; elle değiştirmeyin.

- Render'a giden ve dönen dosyalar şifrelidir (AES-256). Anahtar yalnız uygulamada ve bu reponun gizli ayarında
  (Actions secret) durur.
- Dosyalar herkese görünmeyen taslak sürümlere (draft release) yüklenir ve iş bitince silinir.
- Repo herkese açıktır; çünkü GitHub, herkese açık repolarda standart Actions dakikalarını ücretsiz verir.
