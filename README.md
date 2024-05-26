# ↬ Курсовая работа на тему "Оценка грамматических способностей больших языковых моделей на основе набора данных CoLА"
Далия Гимадиева, НИУ ВШЭ, Фундаментельная и компьютерная лингвистика, 2023-2024 уч. год

науч. рук. - Сериков Олег Алексеевич, науч. конс. - Артемова Екатерина Леонидовна, Никишина Ирина Александровна

**Цель исследования** — изучение способности больших языковых моделей Llama2 и Vicuna выносить суждения о лингвистической приемлемости и предоставлять объяснения ошибок при нарушении языковых норм.

## Список файлов в репозитории
- data tsv - файлы ответов моделей в формате tsv
- data txt - файлы ответов моделей в формате txt
- разметка объяснений - папка с ручной разметки ответов моделей
- feeding_llama2.ipynb - код с подключением к Llama2 и прогоном сценариев
- vicuna_13B_v1_5.ipynb - код с подключением к Vicuna
- in_domain_dev.tsv - набор данных датасета CoLА
- промпты.docx - файл с промтами для прогона
- постер.pdf - постер для защиты курсовой работы
- текст курсовой.docx - полный текст курсовой работы

![Image alt](https://github.com/dduend/lingdata/raw/main/1.png)

**Список литературы**

Орешков 2023 — В. Орешков. Метрики качества моделей бинарной классификации. [Электронный ресурс]. URL: https://loginom.ru/blog/classification-quality (Дата обращения: 25.05.2024)

Студеникина 2022 — К. А. Студеникина. Оценка языковой способности нейронных моделей на материале предикативного согласования в русском языке (электронный документ). Труды ИСП РАН, 34 (6), 2022. С. 179-184. 

Хомский 1972 — Н. Хомский. Аспекты теории синтаксиса. М.: Издательство Московского университета, 1972.

Dentella 2023 — V. Dentella et al. Systematic testing of three Language Models reveals low language accuracy, absence of response stability, and a yes-response bias. PNAS, 120 (51), 2023.

Mikhailov 2022 — V. Mikhailov et al. RuCoLA: Russian Corpus of Linguistic Acceptability. In Proc. of the 2022 Conference on Empirical Methods in Natural Language Processing, 2022, P. 5207-5227.

Ortega-Martín 2023 — M. Ortega-Martín et al. Linguistic ambiguity analysis in ChatGPT // arXiv preprint arXiv:2302.06426, 2023.

Sun 2023 — S. Sun et al. Battle of the Large Language Models: Dolly vs LLaMA vs Vicuna vs Guanaco vs Bard vs ChatGPT - A Text-to-SQL Parsing Comparison // arXiv preprint arxiv-2310.10190, 2023.

Touvron 2023 — H. Touvron et al.  Llama 2: Open Foundation and Fine-Tuned Chat Models // arXiv preprint arXiv.2307.09288, 2023.

Warstadt 2019 — A. Warstadt et al. Neural Network Acceptability Judgments // Transactions of the Association for Computational Linguistics. 7. 10.1162/tacl_a_00290, 2019. P. 625-641.

Zhong 2023  — Q. Zhong et al. Can ChatGPT Understand Too? A Comparative Study on ChatGPT and Fine-tuned BERT // arXiv preprint arXiv:2302.10198, 2023.

URL: https://www.promptingguide.ai/ru/techniques/zeroshot (Дата обращения: 25.05.2024).
