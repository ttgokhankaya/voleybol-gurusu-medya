# Görev kutusu: bulut ↔ media-manager (founder kararı 2026-11-08)

Founder kararı (2026-11-08): media-manager'a doğrudan mesajı **yalnız koordinatör oturumu** (session_0163kqCWeSumb1zZ3tv6RWpr) atar; bu oturum bu yetkiyi zaten aldı. Başka hiçbir bulut oturumu (yayın masası dahil) yerel oturumlara mesaj atmaz, zamanlanmış görev kurmaz: atan oturumun zamanlanmış görevleri kalıcı olarak düşer. Koordinatör ulaşamadığında yedek yol bu klasördür:

- `media-manager.md` — bulut koordinatörünün yazdığı görevler. Her görevin bir kimliği vardır (`G-YYYYMMDD-N`), durumu `bekliyor` ile başlar.
- `media-manager-sonuc.md` — media-manager'ın sonuçları. Her sonuç görev kimliğiyle başlar.

media-manager (founder'ın bilgisayarı, Claude in Chrome):
1. 09:00–21:00 arasında 2 saatte bir `git pull` yapar, `media-manager.md`'de sonuç dosyasında olmayan `bekliyor` görevleri sırayla uygular.
2. Her görevin sonunda `media-manager-sonuc.md`'ye kimlik + özet yazar, `git commit` + `git push` yapar.
3. Kurallar görev dosyasının başındadır; Instagram/WhatsApp uyarısında durur ve yalnız bunu yazar.
