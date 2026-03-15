# Açık Araştırma — Ajan Destekli Akademik Yayın İnceleme

**Anadolu Üniversitesi Uzaktan Eğitim Araştırma Topluluğu**

Sistematik literatür taraması sürecini baştan sona yöneten, yapay zeka destekli, açık kaynaklı bir web uygulaması.

## Canlı Demo

**[https://[kullanıcı-adı].github.io/acik-arastirma/]()**

> `index.html` dosyasını doğrudan tarayıcınızda da açabilirsiniz — sunucu gerekmez.

## Özellikler

### 8 Adımlı Sistematik Derleme Süreci

| Adım | Açıklama |
|------|----------|
| 1. Kullanım Modu | Manuel (WebLLM) veya Agent (Claude) modu seçimi |
| 2. Araştırma Konusu | Detaylı konu tanımı (50-250 kelime) |
| 3. Sorgu / BibTeX | Boolean sorgu oluşturma + BibTeX dosyası yükleme |
| 4. Analiz | Tematik sınıflandırma, ilgililik puanlama, çalışma seçimi |
| 5. Kaynak Doğrulama | DOI bazlı kaynak doğrulama (Agent modu) |
| 6. Akademik Rapor | APA 7 formatında sistematik literatür taraması raporu |
| 7. Araştırma Tasarımı | Yöntem, desen, sorular, hipotezler |
| 8. Özet | Tüm çıktılar, algoritmik dergi önerisi, dışa aktarım |

### Temel Yetenekler

- **WebLLM Entegrasyonu:** Tarayıcıda yerel olarak çalışan AI modeli (Phi-3.5, Llama 3.2, Gemma 2, Qwen 2.5)
- **Claude Agent Modu:** Chrome extension üzerinden tam otomatik süreç yönetimi
- **BibTeX Parser:** WoS/Scopus dışa aktarım dosyalarını ayrıştırma
- **APA 7 Rapor Motoru:** Giriş, Yöntem, Bulgular, Tartışma ve Sonuç, Kaynakça bölümleri
- **PRISMA Akışı:** Sistematik derleme için PRISMA 2020 uyumlu tablo
- **Algoritmik Dergi Önerisi:** 65 dergili veritabanı ile kural tabanlı eşleştirme
- **Literatür Chatbotu:** Yüklenen çalışmalar üzerinde soru-cevap
- **Oturum Yönetimi:** Otomatik kaydetme, dışa/içe aktarma

## Kullanım

### Hızlı Başlangıç (Manuel Mod — Ücretsiz)

1. `index.html` dosyasını tarayıcınızda açın
2. **Manuel Mod** seçin
3. Araştırma konunuzu yazın (en az 50 kelime)
4. WoS/Scopus'tan indirdiğiniz BibTeX dosyasını yükleyin
5. WebLLM ile analiz yapın, rapor oluşturun

### Agent Modu (Claude Pro/Team gerektirir)

1. [Claude Desktop](https://claude.ai/download) uygulamasını indirin
2. [Claude in Chrome](https://chromewebstore.google.com/detail/claude-in-chrome/mhcmjhbbkpkjgecafhbopllcbmgbefao) extension'ını kurun
3. Uygulamayı açın, **Agent Modu** seçin
4. Cowork promptunu kopyalayıp Claude'a yapıştırın
5. Claude tüm adımları sizin için otomatik gerçekleştirecektir

## Teknoloji

- **Sıfır bağımlılık:** Tek HTML dosyası, sunucu gerektirmez
- **WebLLM:** Tarayıcıda yerel AI çıkarımı (WebGPU)
- **Vanilla JS:** Framework yok, doğrudan DOM manipülasyonu
- **Responsive:** Mobil, tablet, masaüstü uyumlu
- **Dark Mode:** Sistem tercihine göre otomatik
- **Print:** Yazdırma dostu düzen
- **Erişilebilirlik:** Touch-friendly hedefler, reduced motion desteği

## Maliyet

| Özellik | Maliyet |
|---------|---------|
| Manuel Mod (WebLLM ile tüm özellikler) | **Ücretsiz** |
| GitHub Pages hosting | **Ücretsiz** |
| Agent Modu (Claude ile otomatik süreç) | Claude Pro aboneliği gerektirir |

## Lisans

Bu proje, Anadolu Üniversitesi Uzaktan Eğitim Araştırma Topluluğu tarafından geliştirilmiştir.

## Katkıda Bulunma

Hata bildirimi ve öneriler için GitHub Issues kullanabilirsiniz.

---

*Yapay zeka çıktıları bilgilendirme amaçlıdır ve hatalı olabilir. Tüm akademik sorumluluk araştırmacıya aittir.*
