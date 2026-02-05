# AI_Engineering_Projects

This repository contains Jupyter Notebooks and resources for AI engineering projects. The README contains both Turkish and English explanations.

---

# TR — Türkçe

## Açıklama
Bu depo, yapay zeka mühendisliği ve veri bilimi alanında geliştirilmiş Jupyter Notebook'lar ve ilgili dökümanları içerir. Notebook'ların çoğu Google Colab üzerinde oluşturulmuştur. Aşağıda depodaki ana dosyalar ve kısa açıklamaları verilmiştir.

## Dosyalar- DataScienceEcosystem-checkpoint.ipynb — Veri bilimi ekosistemi ile ilgili örnekler / kontrol noktası not defteri.
- FinalProject_AUSWeather(1).ipynb — Avustralya hava durumu verisi ile yapılmış final projesi (analiz, önişleme, modelleme).
- Final_Project_Classification_and_Captioning- v1.ipynb — Görüntü sınıflandırma ve otomatik başlık (captioning) uygulaması.
- ibm_ai_eng_3.ipynb — IBM AI Engineering kursuna ait çalışma notları / örnekler.
- imb_ai_engineer_2.ipynb — IBM AI Engineer ile ilgili başka bir çalışma notu (isimlendirmede küçük fark olabilir).
- Glossary.pdf — Terimler sözlüğü / kısa açıklamalar.
- README.md — (bu dosya) depoya genel bakış ve kullanım talimatları.

> Not: Eğer dosya isimlerinde farklılık veya yeni eklemeler varsa lütfen bildir; README'yi buna göre güncelleyeyim.

## Gereksinimler- Python 3.8+
- Jupyter / JupyterLab veya Google Colab
- Gerekli Python paketleri notebook başlıklarında veya requirements.txt / environment.yml içinde belirtilmelidir.

## Nasıl çalıştırılır
1. Yerelde: sanal ortam oluşturun ve bağımlılıkları yükleyin (örneğin requirements.txt varsa).

```bash
python -m venv .venv
source .venv/bin/activate   # Linux / macOS
.venv\Scripts\activate    # Windows
pip install -r requirements.txt
jupyter lab
```

2. Google Colab: GitHub üzerindeki notebook dosyasını açıp "Open in Colab" seçeneğini kullanabilirsiniz veya Colab'da şu formatı kullanın:

https://colab.research.google.com/github/Erencode27/AI_Engineering_Projects/blob/main/<NOTEBOOK_FILE>.ipynb

(örn: https://colab.research.google.com/github/Erencode27/AI_Engineering_Projects/blob/main/FinalProject_AUSWeather(1).ipynb)

## Veri ve Gizlilik- Büyük veri setleri repoda yer almıyor olabilir. Notebook içinde veri indirme / hazırlama adımları belirtilmişse onları takip edin.
- Eğer hassas veri kullanıldıysa, anonimleştirme ve erişim yönergeleri notebook içinde açıklanmalıdır.

## Katkıda Bulunma
1. Depoyu fork'layın.
2. Yeni bir branch oluşturun.
3. Değişikliklerinizi ekleyin ve PR açın.

Notebook katkıları için: çıktı hücrelerini temizleyin, açıklayıcı başlıklar ve kısa açıklamalar ekleyin.

## Lisans
Eğer bu proje için lisans belirtilmemişse lütfen uygun bir lisans (ör. MIT) ekleyin ve LICENSE dosyası oluşturun.

## İletişim
Herhangi bir soru ya da öneri için GitHub üzerinden Erencode27 ile iletişime geçin.

---

# EN — English

## Description
This repository contains Jupyter Notebooks and resources for AI engineering and data science projects. Most notebooks were created using Google Colab. Below is a short overview of the main files in the repo.

## Files- DataScienceEcosystem-checkpoint.ipynb — Examples and checkpoints about the data science ecosystem.
- FinalProject_AUSWeather(1).ipynb — Final project using Australian weather data (analysis, preprocessing, modeling).
- Final_Project_Classification_and_Captioning- v1.ipynb — Image classification and image captioning project.
- ibm_ai_eng_3.ipynb — Notes and exercises from the IBM AI Engineering course.
- imb_ai_engineer_2.ipynb — Another notebook related to IBM AI Engineer (naming may vary).
- Glossary.pdf — Glossary document with terms and short explanations.
- README.md — This file: overview and usage instructions.

> Note: If file names changed or you added new notebooks, tell me and I will update the README accordingly.

## Requirements- Python 3.8+
- Jupyter / JupyterLab or Google Colab
- Required Python packages are expected to be listed in each notebook or in a requirements.txt / environment.yml file.

## How to run
1. Locally: create a virtual environment and install dependencies (if requirements.txt exists).

```bash
python -m venv .venv
# Linux / macOS
source .venv/bin/activate
# Windows
.venv\Scripts\activate

pip install -r requirements.txt
jupyter lab
```

2. Google Colab: Open the notebook on GitHub and use the "Open in Colab" option, or open via:

https://colab.research.google.com/github/Erencode27/AI_Engineering_Projects/blob/main/<NOTEBOOK_FILE>.ipynb

(e.g. https://colab.research.google.com/github/Erencode27/AI_Engineering_Projects/blob/main/FinalProject_AUSWeather(1).ipynb)

## Data & Privacy- Large datasets may not be included in the repository. Follow the data download/preparation steps inside the notebooks.
- If sensitive data is used, document anonymization steps and access instructions.

## Contributing
1. Fork the repo.
2. Create a branch.
3. Make changes and open a Pull Request.

For notebooks: keep outputs cleared when possible, add descriptive headings and short explanations.

## License
If no license is present, consider adding a license such as MIT and include a LICENSE file.

## Contact
For questions or suggestions, reach out via GitHub: Erencode27
