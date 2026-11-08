# Görev kutusu: bulut ↔ media-manager (founder kararı 2026-11-08)

Bulut oturumları founder'ın bilgisayarındaki oturumlara doğrudan mesaj atmaz (bir kez atıldığında o bulut oturumunun zamanlanmış görevleri kalıcı olarak düştü). Bunun yerine bu klasör kullanılır:

- `media-manager.md` — bulut koordinatörünün yazdığı görevler. Her görevin bir kimliği vardır (`G-YYYYMMDD-N`), durumu `bekliyor` ile başlar.
- `media-manager-sonuc.md` — media-manager'ın sonuçları. Her sonuç görev kimliğiyle başlar.

media-manager (founder'ın bilgisayarı, Claude in Chrome):
1. 09:00–21:00 arasında 2 saatte bir `git pull` yapar, `media-manager.md`'de sonuç dosyasında olmayan `bekliyor` görevleri sırayla uygular.
2. Her görevin sonunda `media-manager-sonuc.md`'ye kimlik + özet yazar, `git commit` + `git push` yapar.
3. Kurallar görev dosyasının başındadır; Instagram/WhatsApp uyarısında durur ve yalnız bunu yazar.
