# Okul Gider Takibi

Ücretsiz statik web uygulaması. GitHub Pages ile yayınlanabilir. Supabase Auth ve PostgreSQL kullanır.

## Kurulum
1. Supabase projesinin URL ve publishable key değerlerini `index.html` içindeki `createClient` satırında doğrulayın.
2. GitHub deposunda Settings → Pages → Deploy from a branch → `main` / `/ (root)` seçin.
3. İlk kullanıcı hesap oluşturur, okul oluşturur ve Ayarlar'dan davet kodu çıkarır. İkinci cihaz hesap açıp bu kodla katılır.

Fişler özel Supabase Storage bucket'ında tutulur. Tarayıcıya service-role anahtarı konulmaz.
