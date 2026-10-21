# 🤝 Katkı Rehberi

Bu repoya katkı vermenin iki yolu var. **Git bilmene gerek yok.**

## 1️⃣ Kolay Yol: Form ile Öner (herkes için)

1. Reponun **Issues** sekmesine git → **New issue**
2. **"➕ Kaynak Öner"** formunu seç
3. Alanları doldur ve gönder

Ekip kaynağı inceler ve uygun bulursa ekler. Bu kadar.

## 2️⃣ Doğrudan Ekle (Git / GitHub bilenler için)

1. Repoyu **fork**'la (veya kulüp ekibindeysen yeni bir **branch** aç)
2. İlgili kategori dosyasını düzenle: `docs/<kategori>/README.md`
   > Küçük bir ekleme için tarayıcıda dosyayı açıp ✏️ (Edit) butonuna basman yeterli. GitHub fork ve PR'ı senin için otomatik açar.
3. **Pull Request** aç; PR şablonundaki kontrol listesini doldur

---

## ✍️ Kaynak Ekleme Formatı

Her kaynak **tek satır** ve şu formatta olmalı:

```markdown
- **[Kaynak Adı](https://link)**: Bir cümlelik, neden faydalı olduğunu anlatan açıklama. `🟢 Başlangıç` `🧪 Lab` `🇬🇧 EN` `🆓 Ücretsiz`
```

Etiket sırası her zaman: **Seviye → Tür → Dil → Ücret**

| Seviye | Tür | Dil | Ücret |
| ------ | --- | --- | ----- |
| `🟢 Başlangıç` | `📺 Video` | `🇹🇷 TR` | `🆓 Ücretsiz` |
| `🟡 Orta`      | `📚 Okuma` | `🇬🇧 EN` | `💰 Ücretli` |
| `🔴 İleri`     | `🧪 Lab`   |          | `🆓/💰 Kısmen` |
|                | `🎓 Kurs`  |          |  |
|                | `🛠️ Araç`  |          |  |

- Kulübün özellikle önerdiği kaynaklar için başa `⭐` koy (bunu genelde ekip belirler).
- Bir kaynak birden fazla seviyeye hitap ediyorsa: `🟢 Başlangıç` → `🔴 İleri`

## ✅ Kurallar

- **Kaynağı kendin kullanmış ol** ya da güvenilir olduğundan emin ol.
- **Korsan içerik yok.** Telif hakkı ihlali olan PDF, kurs vb. linkler eklenmez.
- **Etik dışı içerik yok.** Hazır zararlı yazılım, "hack satan" siteler vb. eklenmez.
- **Tekrar etme.** Eklemeden önce `Ctrl + F` ile repoda olup olmadığını kontrol et.
- **Doğru kategori.** Emin değilsen PR/Issue açıklamasında belirt, ekip taşır.
- Açıklamalar **Türkçe**, kaynak adı **orijinal adıyla**.

## 📁 Yeni Kategori / Yol Haritası Eklemek

Repo kökündeki `sablonlar/` klasöründe hazır şablonlar var:

- `sablonlar/kategori-sablonu.md`: Yeni kategori sayfası
- `sablonlar/roadmap-sablonu.md`: Yeni yol haritası

Yeni bir sayfa eklediysen `mkdocs.yml` içindeki `nav` bölümüne ve ana `README.md` tablosuna da eklemeyi unutma.
