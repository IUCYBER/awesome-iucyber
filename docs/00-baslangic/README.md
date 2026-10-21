# 🚀 Yeni Başlayanlar: Başlangıç Paketi

> Siber Güvenlik 101 eğitiminde paylaştığımız "sıfırdan sektöre" başlangıç paketi. Bu sayfa,
> **"Ben şimdi ne yapacağım?"** sorusunun cevabı.

> [!NOTE]
> Her şeyi bir anda yapmaya çalışma. Bu sayfayı **yukarıdan aşağıya** takip et. Takıldığın yerde
> kulüp kanallarından soru sormaktan çekinme. Burada kimse her şeyi bilerek başlamadı.

**İçindekiler**
- [Önce bunu oku: Siber güvenlik nedir, hangi alanlar var?](#önce-bunu-oku)
- [İlk gece görevleri](#ilk-gece)
- [İlk 30 gün planı](#ilk-30-gun)
- [Kurulumlar](#kurulumlar)
- [Sık sorulan sorular](#sık-sorulan-sorular)
- [Sonra nereye?](#sonra-nereye)

---

## Önce bunu oku

Siber güvenlik tek bir meslek değil, birçok alanın birleşimidir. Kabaca:

| Alan | Ne yapar? | Detay |
| ---- | --------- | ----- |
| ⚔️ **Red Team / Pentest** | Sistemlere saldırarak açıkları bulur | [Ofansif Güvenlik](../03-ofansif-guvenlik/README.md) |
| 🛡️ **Blue Team / SOC** | Saldırıları tespit eder, müdahale eder | [Defansif Güvenlik](../04-defansif-guvenlik/README.md) |
| 🌐 **Web Güvenliği** | Web uygulamalarındaki açıkları bulur (Bug Bounty) | [Web Güvenliği](../02-web-guvenligi/README.md) |
| 🔬 **Tersine Mühendislik** | Programları/zararlıları söküp inceler | [Tersine Mühendislik](../06-tersine-muhendislik/README.md) |
| 🕵️ **OSINT** | Açık kaynaklardan bilgi toplar | [OSINT](../08-osint/README.md) |

Hangisini seçeceğini bilmiyorsan sorun değil. **Hepsinin temeli aynı:** Linux + Ağ + biraz programlama.

---

<a id="ilk-gece"></a>
## İlk Gece Görevleri

> Eve gidince doğrudan başlayabileceğin linkler. İlk hafta sadece bunlar yeter.

- [ ] ⭐ **[The Cyber Mentor: Ethical Hacking Kursu (Part 1)](https://youtu.be/3FNYvj2U0HM)**: Milyonlarca kişinin siber güvenliğe başlama sebebi olan 15 saatlik ücretsiz kurs. **Part 1'i kesinlikle izle.** `🟢 Başlangıç` `📺 Video` `🇬🇧 EN` `🆓 Ücretsiz`
  - [Part 2](https://www.youtube.com/watch?v=sH4JCwjybGs&list=PLLKT__MCUeixqHJ1TRqrHsEd6_EdEvo47&index=2)
- [ ] **[Network Eğitimi (Oynatma Listesi)](https://www.youtube.com/playlist?list=PLGWmuqrfJZRtQT4-OWQHFjGDO23rbNjMY)**: Ağ temelleri. `🟢 Başlangıç` `📺 Video` `🆓 Ücretsiz`
- [ ] ⭐ **[TryHackMe: Intro to Offensive Security](https://tryhackme.com/module/introduction-to-offensive-security)**: Tarayıcıdan, kurulum yapmadan ilk hack'in. `🟢 Başlangıç` `🧪 Lab` `🇬🇧 EN` `🆓/💰 Kısmen`
- [ ] **[Hack The Box: Starting Point](https://app.hackthebox.com/starting-point)**: Rehberli ilk makineler. `🟢 Başlangıç` `🧪 Lab` `🇬🇧 EN` `🆓/💰 Kısmen`
- [ ] **[Kali Linux VirtualBox Kurulumu](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/)**: Kendi saldırı makineni kur. `🟢 Başlangıç` `📚 Okuma` `🇬🇧 EN` `🆓 Ücretsiz`

### 🔥 Günün Görevi

Aşağıdakilerden **sadece birini** yap, yeter:
- TryHackMe'de **Linux Fundamentals** ya da **Intro to Offensive Security**'nin ücretsiz kısımlarını çöz,
- HackTheBox **Starting Point**'e başla,
- The Cyber Mentor'un giriş videosunu izle,
- ya da sadece bugün öğrendiklerine kendin bir göz at. **İlgilenmen ve araştırman yeterli.**

---

<a id="ilk-30-gun"></a>
## İlk 30 Gün Planı

> Kendine kopyalayıp kutucukları işaretleyerek ilerleyebilirsin.

<details>
<summary><b>📅 1. Hafta: Ortamı kur, terminalle tanış</b></summary>

- [ ] Kali Linux'u sanal makineye kur
- [ ] [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) seviye 0–10
- [ ] TryHackMe: Linux Fundamentals Part 1–3
- [ ] The Cyber Mentor Part 1'in ilk 3 saati

</details>

<details>
<summary><b>📅 2. Hafta: Ağ temelleri</b></summary>

- [ ] Network eğitimi oynatma listesinin ilk yarısı
- [ ] OSI modeli, TCP/IP, IP adresleme, portlar konularını anla
- [ ] Wireshark kur ve kendi trafiğini incele
- [ ] Bandit seviye 10–20

</details>

<details>
<summary><b>📅 3. Hafta: İlk saldırılar</b></summary>

- [ ] TryHackMe: Intro to Offensive Security modülü
- [ ] Hack The Box Starting Point: Tier 0 makineleri
- [ ] `nmap` ile tarama yapmayı öğren

</details>

<details>
<summary><b>📅 4. Hafta: Yön seç</b></summary>

- [ ] [Yol Haritaları](../roadmaps/README.md) sayfasını oku
- [ ] Web'e ilgi duyuyorsan: [PortSwigger Academy](https://portswigger.net/web-security) ilk konu
- [ ] Savunmaya ilgi duyuyorsan: [LetsDefend](https://letsdefend.io/) ilk eğitim
- [ ] Bir kulüp CTF'ine / etkinliğine katıl

</details>

---

## Kurulumlar

| Ne? | Neden? | Link |
| --- | ------ | ---- |
| VirtualBox / VMware Workstation | Sanal makine çalıştırmak için | [VirtualBox](https://www.virtualbox.org/) |
| Kali Linux | Hazır güvenlik araçlarıyla gelen dağıtım | [Kali VM kurulumu](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/) |
| VS Code | Not alma, script yazma | [code.visualstudio.com](https://code.visualstudio.com/) |
| Obsidian / Notion | Öğrendiklerini not almak (çok önemli!) | [obsidian.md](https://obsidian.md/) |

> [!TIP]
> **Not tut.** Çözdüğün her makine/oda için kısa bir not yaz. 3 ay sonra en değerli kaynağın kendi notların olacak.

---

## Sık Sorulan Sorular

<details>
<summary><b>Programlama bilmem gerekiyor mu?</b></summary>

Başlamak için hayır. Ama ilerledikçe **Python** ve **Bash** çok işine yarayacak. Bkz. [Temeller → Programlama](../01-temeller/README.md#programlama).

</details>

<details>
<summary><b>Ücretli platformlara para vermeli miyim?</b></summary>

İlk aylarda hayır. TryHackMe, HTB, PortSwigger ve OverTheWire'ın ücretsiz kısımları fazlasıyla yeterli.

</details>

<details>
<summary><b>İngilizcem iyi değil, ne yapmalıyım?</b></summary>

`🇹🇷 TR` etiketli kaynaklarla başla. Ama teknik İngilizce zamanla gelişir. Altyazılı izlemek iyi bir başlangıç.

</details>

<details>
<summary><b>Öğrendiklerimi bir yerde deneyebilir miyim?</b></summary>

**Sadece izinli ortamlarda!** (TryHackMe, HTB, kendi sanal makinelerin.) İzinsiz sistemlere saldırmak suçtur (TCK 243–245).

</details>

---

## Sonra Nereye?

- 🧱 Temeli sağlamlaştır → [Temeller](../01-temeller/README.md)
- 🗺️ Bir yol seç → [Yol Haritaları](../roadmaps/README.md)
- 🎯 Pratik yap → [CTF & Pratik Platformları](../05-ctf-ve-pratik/README.md)
- 📺 Takip et → [YouTube, blog, haber](../12-takip-edilecekler/README.md)
- 🍿 Mola ver → [Siber Kültür](../13-siber-kultur/README.md)
