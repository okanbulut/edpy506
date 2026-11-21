# Datasets used by the recipe notebooks

| File | Used by | Source and licence |
|---|---|---|
| `oulad_bbb2013j.csv` | Recipes 1–6 and 9 (also built into each notebook) | Open University Learning Analytics Dataset (OULAD), module BBB, 2013J presentation, summarized to one row per student (2,237 students). Kuzilek, J., Hlosta, M., & Zdrahal, Z. (2017). Open University Learning Analytics dataset. *Scientific Data, 4*, 170171. https://doi.org/10.1038/sdata.2017.171. Licensed CC BY 4.0. |
| `sms_spam.tsv` | Recipes 7 and 8 | SMS Spam Collection (5,572 messages; tab-separated: label, text). Almeida, T. A., Gómez Hidalgo, J. M., & Yamakami, A. (2011). Contributions to the study of SMS spam filtering. *Proceedings of the 11th ACM Symposium on Document Engineering*, 259–262. UCI Machine Learning Repository, https://doi.org/10.24432/C5CC84. Licensed CC BY 4.0. |

Recipe 8 also downloads two pretrained models from Hugging Face the first time it runs (no account needed): `sentence-transformers/all-MiniLM-L6-v2` and `Qwen/Qwen2.5-0.5B-Instruct`.
