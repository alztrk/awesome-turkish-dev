# 🇹🇷 Awesome Turkish Dev

> Türk yazılım geliştiricileri için küratörlü kaynak listesi.
> Datasetler, modeller, araçlar, topluluklar, iş ilanları, eğitimler ve daha fazlası.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## İçindekiler

- [Türkçe Datasetler (HuggingFace)](#türkçe-datasetler-huggingface)
- [Türkçe NLP & AI Modelleri](#türkçe-nlp--ai-modelleri)
- [Türkçe LLM'ler](#türkçe-llmler)
- [Türkçe Yazılım Kaynakları](#türkçe-yazılım-kaynakları)
- [Türk Geliştirici Toplulukları](#türk-geliştirici-toplulukları)
- [Blog & Podcast & YouTube](#blog--podcast--youtube)
- [İş & Kariyer](#iş--kariyer)
- [Açık Kaynak Projeler](#açık-kaynak-projeler)
- [Türkçe Kütüphaneler & Araçlar](#türkçe-kütüphaneler--araçlar)
- [Finans & Ekonomi Araçları](#finans--ekonomi-aracları)
- [Eğitim & Kurslar](#eğitim--kurslar)
- [Türkçe Dokümantasyon Çevirileri](#türkçe-dokümantasyon-çevirileri)
- [Katkıda Bulunma](#katkıda-bulunma)

---

## Türkçe Datasetler (HuggingFace)

### Büyük Türkçe Corpus'lar

| Veri Seti | Token/Örnek | İndirme | Link |
|---|---|---|---|
| Lumees Turkish Corpus 100B | 105B token | 760+ | [HF](https://huggingface.co/datasets/lumees/turkish-corpus-100b) |
| BellaTurca | 30B kelime (245GB) | 1K+ | [HF](https://huggingface.co/datasets/turkish-nlp-suite/BellaTurca) |
| FineWeb-2 Turkish Categorized | 10M-100M örnek | 3.9K+ | [HF](https://huggingface.co/datasets/altaidevorg/fineweb-2-turkish-categorized) |
| Cosmos Turkish Corpus v1.0 | ~15B token | 540+ | [HF](https://huggingface.co/datasets/ytu-ce-cosmos/Cosmos-Turkish-Corpus-v1.0) |
| Turkish LLM Dataset (tascib) | 100M-1B token | 2.7K+ | [HF](https://huggingface.co/datasets/tascib/turkish-llm-dataset) |
| Turkish Corpus (Ethosoft) | 1M-10M örnek | 1.2K+ | [HF](https://huggingface.co/datasets/Ethosoft/Turkish_corpus) |
| AkademikDerlem | 100K+ makale | 539+ | [HF](https://huggingface.co/datasets/turkish-nlp-suite/AkademikDerlem) |

### NLP & Sınıflandırma

| Veri Seti | Açıklama | İndirme | Link |
|---|---|---|---|
| Turkish Sentiment Dataset (3-class) | pozitif/negatif/nötr | 631+ | [HF](https://huggingface.co/datasets/winvoker/turkish-sentiment-analysis-dataset) |
| Turkish Instructions | 50k+ talimat verisi | 502+ | [HF](https://huggingface.co/datasets/merve/turkish_instructions) |
| TurkishMMLU | Çoktan seçmeli Türkçe sınav | 475+ | [HF](https://huggingface.co/datasets/AYueksel/TurkishMMLU) |
| Turkish Parliament Data (GNACT) | 100 yıllık meclis tutanakları | 1.3K+ | [HF](https://huggingface.co/datasets/boun-tabilab/turkish_parliamentary_data) |
| Turkish Law Documents 700k | Hukuk belgeleri | 1.3K+ | [HF](https://huggingface.co/datasets/erdem-erdem/Turkish-Law-Documents-700k-clustered) |
| Turkish Finance Instructions | Finans soru-cevap | 1.1K+ | [HF](https://huggingface.co/datasets/Dbmaxwell/turkish-finance-instruction-dataset) |
| Bilge Turkish CoT 50K | Chain-of-Thought reasoning | 587+ | [HF](https://huggingface.co/datasets/bugrabilge/Bilge-Turkish-CoT-50K) |
| Turkish Synthetic Corpus | 1.8M sentetik belge | 472+ | [HF](https://huggingface.co/datasets/cturan/turkish-synthetic-corpus) |

### Ses & Konuşma

| Veri Seti | Açıklama | İndirme | Link |
|---|---|---|---|
| Common Voice Turkish | Mozilla (100+ saat, CC-0) | - | [Site](https://commonvoice.mozilla.org/tr) |
| Wav2Vec2 Turkish ASR | 620K+ indirme | 620K+ | [HF](https://huggingface.co/mpoyraz/wav2vec2-xls-r-300m-cv7-turkish) |
| Turkish TTS Combined | 81.5k örnek, 7 kaynak | 967+ | [HF](https://huggingface.co/datasets/afkfatih/turkish-tts-combined-raw) |
| Turkish TTS Data (Anilosan15) | 10K-100K örnek | 664+ | [HF](https://huggingface.co/datasets/Anilosan15/Turkish_TTS_Data) |
| Turkish OCR Noise Corpus | OCR gürültü verisi | 2K+ | [HF](https://huggingface.co/datasets/sfidan42/turkish-ocr-noise-corpus) |

### Görüntü & Multimodal

| Veri Seti | Açıklama | İndirme | Link |
|---|---|---|---|
| Turkish Image Captioning | BLIP3o çevirisi, 1M+ | 921+ | [HF](https://huggingface.co/datasets/ituperceptron/image-captioning-turkish) |
| Turkish Image VQA | Görsel soru-cevap | 568+ | [HF](https://huggingface.co/datasets/ituperceptron/image-vqa-turkish) |

---

## Türkçe NLP & AI Modelleri

### Metin Sınıflandırma & Duygu Analizi

| Model | İndirme | Link |
|---|---|---|
| BERT-base Turkish Sentiment (savasy) | 13K+ | [HF](https://huggingface.co/savasy/bert-base-turkish-sentiment-cased) |
| BERT Turkish Emotion Analysis | 20K+ | [HF](https://huggingface.co/maymuni/bert-base-turkish-cased-emotion-analysis) |
| Turkish Sentiment (kaixkhazaki) | 1.2K+ | [HF](https://huggingface.co/kaixkhazaki/turkish-sentiment) |

### Varlık İsmi Tanıma (NER)

| Model | İndirme | Link |
|---|---|---|
| BERT Turkish NER (akdeniz27) | 70K+ | [HF](https://huggingface.co/akdeniz27/bert-base-turkish-cased-ner) |
| BERT Turkish NER (savasy) | 3K+ | [HF](https://huggingface.co/savasy/bert-base-turkish-ner-cased) |

### Soru Cevaplama (QA)

| Model | İndirme | Link |
|---|---|---|
| BERT Turkish SQuAD (savasy) | 3.7K+ | [HF](https://huggingface.co/savasy/bert-base-turkish-squad) |

### Embedding & Cümle Benzerliği

| Model | İndirme | Link |
|---|---|---|
| Turkish Embedding Model (trmteb) | 154K+ | [HF](https://huggingface.co/trmteb/turkish-embedding-model) |
| BERT Mean NLI STS (emrecan) | 75K+ | [HF](https://huggingface.co/emrecan/bert-base-turkish-cased-mean-nli-stsb-tr) |
| Turkish E5 Large (YTÜ) | 3.9K+ | [HF](https://huggingface.co/ytu-ce-cosmos/turkish-e5-large) |
| BGE Reranker Turkish (seroe) | 1K+ | [HF](https://huggingface.co/seroe/bge-reranker-v2-m3-turkish-triplet) |

### Base Modeller (dbmdz / YTÜ)

| Model | İndirme | Link |
|---|---|---|
| BERT-base Turkish cased (dbmdz) | 62K+ | [HF](https://huggingface.co/dbmdz/bert-base-turkish-cased) |
| BERT-base Turkish uncased (dbmdz) | 29K+ | [HF](https://huggingface.co/dbmdz/bert-base-turkish-uncased) |
| BERT-base Turkish 128k uncased (dbmdz) | 35K+ | [HF](https://huggingface.co/dbmdz/bert-base-turkish-128k-uncased) |
| Turkish Base BERT uncased (YTÜ) | 1.3K+ | [HF](https://huggingface.co/ytu-ce-cosmos/turkish-base-bert-uncased) |
| ConvBERT Turkish (dbmdz) | 1.5K+ | [HF](https://huggingface.co/dbmdz/convbert-base-turkish-cased) |
| DistilBERT Turkish (dbmdz) | 1.5K+ | [HF](https://huggingface.co/dbmdz/distilbert-base-turkish-cased) |
| ELECTRA Turkish (dbmdz) | 1.5K+ | [HF](https://huggingface.co/dbmdz/electra-base-turkish-cased-discriminator) |

---

## Türkçe LLM'ler

| Model | Açıklama | İndirme | Link |
|---|---|---|---|
| Turkish-Gemma-9b-T1 (YTÜ) | 9B param, SFT+DPO | 2K+ | [HF](https://huggingface.co/ytu-ce-cosmos/Turkish-Gemma-9b-T1) |
| Turkish-Llama-8b-Instruct (YTÜ) | LLaMA 3 tabanlı | 889+ | [HF](https://huggingface.co/ytu-ce-cosmos/Turkish-Llama-8b-Instruct-v0.1) |
| Turkish-Llama-8b v0.1 (YTÜ) | Base model | 242+ | [HF](https://huggingface.co/ytu-ce-cosmos/Turkish-Llama-8b-v0.1) |
| Turkish-Gemma-9b v0.1 (YTÜ) | Gemma 2 tabanlı | 422+ | [HF](https://huggingface.co/ytu-ce-cosmos/Turkish-Gemma-9b-v0.1) |
| Turkish-Gemma-4b-T1-Scout (YTÜ) | Gemma 3 + agent | 112+ | [HF](https://huggingface.co/ytu-ce-cosmos/Turkish-Gemma-4b-T1-Scout) |
| GPT-2 Turkish (hakanbogan) | GPT-2 small | 2.3K+ | [HF](https://huggingface.co/hakanbogan/gpt2-turkish-cased) |
| GPT-2 Turkish (YTÜ) | GPT-2 small | 1.8K+ | [HF](https://huggingface.co/ytu-ce-cosmos/turkish-gpt2) |
| GPT-2 Turkish Medium (YTÜ) | GPT-2 medium | 1K+ | [HF](https://huggingface.co/ytu-ce-cosmos/turkish-gpt2-medium) |
| GPT-2 Turkish Large (YTÜ) | GPT-2 large | 590+ | [HF](https://huggingface.co/ytu-ce-cosmos/turkish-gpt2-large) |
| GPT-2 Turkish Small (gorkem) | GPT-2 small | 1.3K+ | [HF](https://huggingface.co/gorkemgoknar/gpt2-small-turkish) |
| GPT-2 Turkish 900M (cenker) | 900M param | 434+ | [HF](https://huggingface.co/cenkersisman/gpt2-turkish-900m) |
| Mihenk LLM v2 35B (finans) | Finans odaklı 35B | 400+ | [HF](https://huggingface.co/AlicanKiraz0/Mihenk-LLM-v2-35B-A3B-Turkish-Financial-Model) |
| Kızagan E4B (reasoning) | Gemma 4 + muhakeme | 253+ | [HF](https://huggingface.co/AlicanKiraz0/Kizagan-E4B-Turkish-Reasoning-Model) |
| Kızagan E4B FunctionCalling | Agent + tool use | 1.5K+ | [HF](https://huggingface.co/Tuguberk/Kizagan-E4B-Turkish-Agent-FunctionCalling-Hermes) |
| Turkish LLM 14B Instruct | 14B instruction-tuned | 198+ | [HF](https://huggingface.co/ogulcanaydogan/Turkish-LLM-14B-Instruct-GGUF) |
| Turkish LLM 7B Instruct | 7B SFT (Çağrı) | 148+ | [HF](https://huggingface.co/ogulcanaydogan/Turkish-LLM-7B-Instruct) |
| WiroAI Turkish LLM 9B | Gemma 2 + Türkçe | 184+ | [HF](https://huggingface.co/WiroAI/wiroai-turkish-llm-9b) |

---

## Türkçe Yazılım Kaynakları

| Kaynak | Açıklama | ⭐ | Link |
|---|---|---|---|
| Türkçe Kaynaklar | Özenle seçilmiş Türkçe kaynaklar listesi | ⭐2522 | [GitHub](https://github.com/turkcekaynaklar-com) |
| Tasarım Desenleri (Türkçe) | Çoklu dilde tasarım desenleri | ⭐3346 | [GitHub](https://github.com/tasarim-desenleri-turkce-kaynak) |
| React Türkçe Kaynak | React.js Türkçe öğrenme kaynağı | ⭐689 | [GitHub](https://github.com/react-turkce-kaynak) |
| Python Notlarım | Türkçe Python ders notları | ⭐373 | [GitHub](https://github.com/python-notlarim) |
| Python Belgeleri | YazBel Türkçe Python dokümantasyonu | ⭐551 | [GitHub](https://github.com/python) |
| Flutter Full Learn | Sıfırdan Flutter (Türkçe video) | ⭐303 | [GitHub](https://github.com/Flutter-Full-Learn) |
| KIP Programlama Dili | Türkçe gramer tabanlı programlama dili | ⭐882 | [GitHub](https://github.com/kip) |
| Jargon.ist | Bilgisayar bilimleri jargon sözlüğü | ⭐300 | [GitHub](https://github.com/jargon.ist) |

---

## Türk Geliştirici Toplulukları

| Platform | Açıklama | Link |
|---|---|---|
| **r/veYakinMonitör** | Türkçe yazılım subredditi (5k+ üye) | [Reddit](https://reddit.com/r/veYakinMonitör) |
| **r/CodingTR** | Türkçe kodlama topluluğu | [Reddit](https://reddit.com/r/CodingTR) |
| **Yazılım Geliştiricileri** | Telegram: 15k+ üye | [Telegram](https://t.me/yazilimcilar) |
| **Frontend Türkiye** | Telegram: 5k+ üye | [Telegram](https://t.me/frontendturkiye) |
| **Devs Türkiye** | Discord topluluğu | [Discord](https://discord.gg/devsturkiye) |
| **Türkiye Yazılım Topluluğu** | Discord | [Discord](https://discord.gg/turkiyeyazilim) |
| **Kodluyoruz Topluluk** | Discord + etkinlikler | [Discord](https://discord.gg/kodluyoruz) |
| **Patika.dev Topluluk** | Discord + mentorluk | [Discord](https://discord.gg/patikadev) |
| **Yazılım Mimarileri** | Telegram: 3k+ üye | [Telegram](https://t.me/yazilimmimarileri) |
| **Veri Bilimi Türkiye** | Telegram: 5k+ üye | [Telegram](https://t.me/veribilimiturkiye) |

---

## Blog & Podcast & YouTube

| İsim | Tür | Açıklama | Link |
|---|---|---|---|
| **Fatih Kadir Akın** | Blog | JavaScript, Node.js, React, açık kaynak | [Blog](https://f.kafalı.org/) |
| **Eser Özvataf** | Blog | Full-stack, açık kaynak, girişim | [Blog](https://eser.live/) |
| **Arda Kılıçdağı** | Blog | Python, DevOps, mimari | [Blog](https://arda.kilicdagi.com/) |
| **Kodluyoruz Podcast** | Podcast | Türkçe yazılım sohbetleri | [Site](https://podcast.kodluyoruz.org/) |
| **DevPod** | Podcast | Geliştirici röportajları | [Site](https://devpod.com.tr/) |
| **Patika.dev Topluluk Blog** | Blog | Türkçe teknik makaleler | [Site](https://community.patika.dev/) |
| **Arin Yazılım** | YouTube | Yazılım eğitimleri (500K+ abone) | [YouTube](https://youtube.com/@arinyazilim) |
| **Prototurk** | YouTube | Web geliştirme (400K+ abone) | [YouTube](https://youtube.com/@prototurk) |
| **Adem Ilter** | YouTube | Backend, sistem (200K+ abone) | [YouTube](https://youtube.com/@ademilter) |
| **Sadık Turan** | YouTube | Yazılım eğitimleri (300K+ abone) | [YouTube](https://youtube.com/@SadikTuran) |

---

## İş & Kariyer

| Platform | Açıklama | Link |
|---|---|---|
| **Kodluyoruz** | Bootcamp + iş bulma desteği | [Site](https://kodluyoruz.org/) |
| **Patika.dev** | Ücretsiz eğitim + iş garantisi | [Site](https://patika.dev/) |
| **Türkçe Remote İşler** | Uzaktan çalışma ilanları | [Site](https://trremote.com/) |
| **İşin Olsun** | Türkiye yazılım iş ilanları | [Site](https://isinolsun.com/) |
| **Türk Startup Jobs** | Girişim iş ilanları | [Site](https://turkstartupjobs.com/) |
| **Indeed Türkiye** | Türkiye iş ilanları | [Site](https://tr.indeed.com/) |
| **LinkedIn Türkiye** | Profesyonel ağ | [Site](https://linkedin.com/) |
| **Kariyer.net** | Türkiye'nin en büyük iş platformu | [Site](https://kariyer.net/) |

---

## Açık Kaynak Projeler

| Proje | Açıklama | ⭐ | Link |
|---|---|---|---|
| **Zemberek-NLP** | Türkçe doğal dil işleme kütüphanesi | ⭐1332 | [GitHub](https://github.com/andrewkiluk/tr-zemberek) |
| **Yargı MCP** | Türk hukuk veritabanları için MCP sunucusu | ⭐990 | [GitHub](https://github.com/yargi-mcp) |
| **KIP** | Türkçe gramer tabanlı programlama dili | ⭐882 | [GitHub](https://github.com/kip) |
| **BorsaPy** | Türkiye finans piyasaları Python kütüphanesi | ⭐660 | [GitHub](https://github.com/borsapy) |
| **Borsa MCP** | BIST + ABD borsa verileri MCP sunucusu | ⭐601 | [GitHub](https://github.com/borsa-mcp) |
| **Turkish BERT** | DBMDZ Türkçe BERT modelleri | ⭐576 | [GitHub](https://github.com/turkish-bert) |
| **SplitWire-Turkey** | İnternet kısıt aşma aracı | ⭐568 | [GitHub](https://github.com/SplitWire-Turkey) |
| **Tasarım Desenleri** | Çoklu dilde tasarım desenleri (Türkçe) | ⭐3346 | [GitHub](https://github.com/tasarim-desenleri-turkce-kaynak) |
| **TurkishNLP** | İTÜ Türkçe NLP pipeline'ı | ⭐300+ | [GitHub](https://github.com/olcaytaner/TurkishNLP) |
| **Tengra** | Cross-platform AI workspace | ⭐8 | [GitHub](https://github.com/TengraStudio/tengra) |
| **xfilter** | X.com onaylı hesap filtreleme eklentisi | - | [GitHub](https://github.com/alztrk/xfilter) |

---

## Türkçe Kütüphaneler & Araçlar

| Araç | Açıklama | Dil | Link |
|---|---|---|---|
| **Zemberek-NLP** | Türkçe morfoloji, imla, kök bulma | Java | [GitHub](https://github.com/andrewkiluk/tr-zemberek) |
| **TurkishStemmer** | Türkçe kök bulma algoritması | Python | [GitHub](https://github.com/otus-io/TurkishStemmer) |
| **BorsaPy** | BIST, forex, kripto, fon verileri | Python | [GitHub](https://github.com/borsapy) |
| **Borsa MCP** | MCP üzerinden borsa verileri | Python | [GitHub](https://github.com/borsa-mcp) |
| **Yargı MCP** | Türk hukuk veritabanları MCP | Python | [GitHub](https://github.com/yargi-mcp) |
| **Autocorrect** | Türkçe yazım düzeltme | Python | [GitHub](https://github.com/autocorrect) |
| **Türkçe Dil Bilgisi Düzeltici** | mBART50 ile grammar correction | Python | [HF](https://huggingface.co/yeniguno/mbart50-turkish-grammar-corrector) |

---

## Finans & Ekonomi Araçları

| Araç | Açıklama | Link |
|---|---|---|
| **BorsaPy** | BIST hisse, forex, kripto, enflasyon verileri (660★) | [GitHub](https://github.com/borsapy) |
| **Borsa MCP** | MCP ile borsa verileri (601★) | [GitHub](https://github.com/borsa-mcp) |
| **Mihenk LLM v2 35B** | Türkçe finansal model | [HF](https://huggingface.co/AlicanKiraz0/Mihenk-LLM-v2-35B-A3B-Turkish-Financial-Model) |
| **Turkish Finance Instructions** | Finans soru-cevap dataseti | [HF](https://huggingface.co/datasets/Dbmaxwell/turkish-finance-instruction-dataset) |

---

## Eğitim & Kurslar

| Platform | Açıklama | Ücret | Link |
|---|---|---|---|
| **Patika.dev** | Türkçe interaktif dersler + iş garantisi | Ücretsiz | [Site](https://patika.dev/) |
| **Kodluyoruz** | Bootcamp + mentorluk + iş bulma | Ücretsiz | [Site](https://kodluyoruz.org/) |
| **BTK Akademi** | Türkçe teknik eğitimler (100+ kurs) | Ücretsiz | [Site](https://btkakademi.gov.tr/) |
| **Akbank Gençlik Akademisi** | Yazılım, finans, girişim eğitimleri | Ücretsiz | [Site](https://akbankgenclikakademisi.com/) |
| **Turkcell Geleceği Yazanlar** | Mobil, web, siber güvenlik eğitimleri | Ücretsiz | [Site](https://gelecegiyazanlar.turkcell.com.tr/) |
| **İstanbul Kodluyor** | Üniversite öğrencilerine kodlama atölyeleri | Ücretsiz | [Site](https://istanbulkodluyor.istanbul/) |
| **Arin Yazılım** | YouTube üzerinden yazılım eğitimleri | Ücretsiz | [YouTube](https://youtube.com/@arinyazilim) |

---

## Türkçe Dokümantasyon Çevirileri

| Proje | Açıklama | ⭐ | Link |
|---|---|---|---|
| **React Türkçe Çeviri** | React dokümantasyon çevirisi | ⭐541 | [GitHub](https://github.com/react) |
| **JavaScript.info Türkçe** | Modern JavaScript Tutorial | ⭐365 | [GitHub](https://github.com/tr.javascript.info) |
| **Python Belgeleri** | YazBel Python dokümantasyonu | ⭐551 | [GitHub](https://github.com/python) |

---

## Katkıda Bulunma

Bu liste herkese açıktır. Eklemek istediğiniz kaynaklar varsa PR gönderin veya issue açın.

[Katkı kuralları](CONTRIBUTING.md)

---

## Lisans

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
