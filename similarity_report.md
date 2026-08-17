# Python Code Similarity & Plagiarism Report

## Executive Summary

- **Total Python Implementations Analyzed:** 175 (148 Lab 1, 27 Lab 2)
- **Total Pairwise Comparisons Executed:** 11,229
- **🔴 High Similarity Pairs (≥ 80%):** 5
- **🟡 Moderate Similarity Pairs (65% – 79%):** 109
- **Lab 1 Plagiarism Clusters (≥ 80%):** 4 groups
- **Lab 2 Plagiarism Clusters (≥ 80%):** 1 groups

---

## Plagiarism Clusters (Identical / Shared Logic Rings ≥ 80%)

### Lab 1 (`grade-evaluator.py`) Clusters
- **Group 1 (2 students):** `Ashton_Sacha_Cyubahiro`, `Sarah_Esther_Wendo`
- **Group 2 (2 students):** `David_Lael_Nziza`, `Esther_Habimana`
- **Group 3 (2 students):** `Gerard_Kaberuka`, `Liliose_Muhimpundu_Gashugi`
- **Group 4 (2 students):** `Nissi_Ishema`, `Ntwali_Axel_Omega`

### Lab 2 (`data-detective.py`) Clusters
- **Group 1 (2 students):** `Derrick_Mugire`, `Gabriel_Agaba`

---

## Top Suspect Pairs (Similarity ≥ 65.0%)

| Rank | Student A | Student B | Lab | Overall Match | AST Match | Token Match | Variable Match | Matched Lines | Shared Unique Variables |
|---|---|---|---|---|---|---|---|---|---|
| 1 | `David_Lael_Nziza` | `Esther_Habimana` | LAB1 | 🔴 **100.0%** | 100.0% | 100.0% | 100.0% | 37 lines | `None` |
| 2 | `Gerard_Kaberuka` | `Liliose_Muhimpundu_Gashugi` | LAB1 | 🔴 **100.0%** | 100.0% | 100.0% | 100.0% | 123 lines | `entry, failed_formatives, formative_earned, formative_max, formative_pct (+16 more)` |
| 3 | `Nissi_Ishema` | `Ntwali_Axel_Omega` | LAB1 | 🔴 **100.0%** | 100.0% | 100.0% | 100.0% | 96 lines | `failed_lst, final_grade, formative_marks, formative_percentage, formative_weight (+8 more)` |
| 4 | `Derrick_Mugire` | `Gabriel_Agaba` | LAB2 | 🔴 **99.6%** | 99.3% | 99.1% | 100.0% | 87 lines | `clean_feed, dropped, entry, fixed, highest_pos (+16 more)` |
| 5 | `Ashton_Sacha_Cyubahiro` | `Sarah_Esther_Wendo` | LAB1 | 🔴 **87.4%** | 96.4% | 94.4% | 84.4% | 44 lines | `errors, failed_formatives, formative_pct, formative_points, formative_weight (+10 more)` |
| 6 | `Fiinsi_Laïla_Hulda_Kabore` | `Rebecca_Mokeira_Isaboke` | LAB1 | 🟡 **79.6%** | 86.5% | 83.8% | 84.2% | 42 lines | `formative_pct, formative_points, formative_weight, gpa, max_weight (+8 more)` |
| 7 | `Lemuel_Mpaka_Sano` | `Rayan_Imanzi_Muganga` | LAB1 | 🟡 **79.3%** | 85.1% | 79.6% | 86.6% | 39 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+6 more)` |
| 8 | `Abdikarim_Abdikheir_Mohamed` | `Rayan_Imanzi_Muganga` | LAB1 | 🟡 **78.7%** | 87.7% | 79.0% | 86.0% | 32 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+7 more)` |
| 9 | `Kotana_Allan` | `Teta_Kayitare_Soumaya` | LAB1 | 🟡 **77.8%** | 88.4% | 77.9% | 79.7% | 37 lines | `formative_grade, formative_percent, formative_weight, gpa, summative_grade (+4 more)` |
| 10 | `Joshua_Gasasira` | `Mucyo_Murara_Lyan` | LAB1 | 🟡 **77.3%** | 80.3% | 70.7% | 94.3% | 57 lines | `failed_formative, formative_grade, formative_weight, gpa, highest_weight (+5 more)` |
| 11 | `Abigail_Ama_Opoo_Cobbina` | `Joshua_Gasasira` | LAB1 | 🟡 **77.2%** | 82.4% | 73.8% | 94.7% | 44 lines | `failed_formative, formative_grade, formative_weight, gpa, highest_weight (+6 more)` |
| 12 | `Abigail_Ama_Opoo_Cobbina` | `Mucyo_Murara_Lyan` | LAB1 | 🟡 **76.4%** | 79.6% | 72.1% | 89.3% | 56 lines | `failed_formative, formative_grade, formative_weight, gpa, highest_weight (+5 more)` |
| 13 | `Adedotun_Oyinola_Taiwo` | `Nixon_Bruno_Kami` | LAB1 | 🟡 **76.2%** | 90.8% | 87.6% | 64.6% | 42 lines | `failed_formatives, final_grade, formative_weight, gpa, max_weight (+4 more)` |
| 14 | `Ashton_Sacha_Cyubahiro` | `Favour_Ndelle_Kebei` | LAB1 | 🟡 **75.8%** | 84.7% | 80.5% | 77.4% | 51 lines | `errors, formative_pct, formative_weight, gpa, invalid_scores (+7 more)` |
| 15 | `Annualite_Muhimpundu` | `SITUMA_EZRA_Prince` | LAB1 | 🟡 **75.5%** | 86.7% | 82.0% | 75.0% | 48 lines | `failed_formative, formative_score, formative_weight, gpa, highest_weight (+5 more)` |
| 16 | `Hana_Nouh_Fadlalla_Idriss` | `Portia_Mbiya_Kamuala` | LAB1 | 🟡 **74.8%** | 75.8% | 70.6% | 92.9% | 41 lines | `failed_formative, final_grade, formative_grade, formative_weight, gpa (+5 more)` |
| 17 | `Favour_Ndelle_Kebei` | `Landry_Rwema_Irakoze_Rwema` | LAB1 | 🟡 **74.2%** | 88.5% | 85.4% | 71.2% | 36 lines | `failed_formative, formative_pct, formative_weight, gpa, passed (+5 more)` |
| 18 | `Paradis_Ange_Keza` | `SITUMA_EZRA_Prince` | LAB1 | 🟡 **73.9%** | 83.5% | 81.9% | 76.6% | 52 lines | `failed_formative, formative_score, formative_weight, gpa, highest_weight (+4 more)` |
| 19 | `Lemuel_Mpaka_Sano` | `Nicia_Greta_Agasaro` | LAB1 | 🟡 **73.5%** | 79.6% | 79.5% | 84.2% | 32 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+6 more)` |
| 20 | `Abigail_Ama_Opoo_Cobbina` | `Rebecca_Umuragwa_Benegusenga` | LAB1 | 🟡 **73.4%** | 86.7% | 80.3% | 68.4% | 43 lines | `failed_formative, formative_weight, gpa, highest_weight, status (+4 more)` |
| 21 | `Ashton_Sacha_Cyubahiro` | `Nicia_Greta_Agasaro` | LAB1 | 🟡 **73.2%** | 84.8% | 84.2% | 69.1% | 50 lines | `errors, failed_formatives, formative_weight, gpa, invalid_scores (+6 more)` |
| 22 | `Kayitare_Anakin_Libery` | `Rayan_Imanzi_Muganga` | LAB1 | 🟡 **72.2%** | 83.7% | 80.6% | 72.5% | 37 lines | `failed_formatives, formative_weight, gpa, highest_weight, name (+6 more)` |
| 23 | `Rebecca_Mokeira_Isaboke` | `Sarah_Esther_Wendo` | LAB1 | 🟡 **72.0%** | 76.0% | 73.8% | 83.7% | 40 lines | `failed_formatives, formative_pct, formative_points, formative_weight, gpa (+9 more)` |
| 24 | `Favour_Ndelle_Kebei` | `Nicia_Greta_Agasaro` | LAB1 | 🟡 **71.7%** | 85.3% | 80.9% | 66.2% | 42 lines | `errors, formative_weight, gpa, invalid_scores, passed (+4 more)` |
| 25 | `Noah_Muyango` | `Raul_Junior_Irakiza_Ruzigana` | LAB1 | 🟡 **71.4%** | 77.2% | 74.8% | 82.6% | 42 lines | `failed_formatives, final_grade, formative_pct, formative_score, formative_weight (+8 more)` |
| 26 | `Favour_Ndelle_Kebei` | `Sarah_Esther_Wendo` | LAB1 | 🟡 **71.2%** | 85.3% | 80.6% | 64.8% | 38 lines | `errors, formative_pct, formative_weight, gpa, max_weight (+5 more)` |
| 27 | `Adedotun_Oyinola_Taiwo` | `Rebecca_Mokeira_Isaboke` | LAB1 | 🟡 **71.0%** | 83.9% | 80.1% | 69.8% | 41 lines | `failed_formatives, formative_pct, formative_weight, gpa, max_weight (+6 more)` |
| 28 | `Annualite_Muhimpundu` | `Paradis_Ange_Keza` | LAB1 | 🟡 **70.9%** | 83.4% | 79.6% | 72.2% | 35 lines | `failed_formative, formative_score, formative_weight, gpa, highest_weight (+5 more)` |
| 29 | `Ashton_Sacha_Cyubahiro` | `Rebecca_Mokeira_Isaboke` | LAB1 | 🟡 **70.7%** | 75.1% | 72.8% | 82.2% | 35 lines | `failed_formatives, formative_pct, formative_points, formative_weight, gpa (+9 more)` |
| 30 | `Fiinsi_Laïla_Hulda_Kabore` | `Landry_Rwema_Irakoze_Rwema` | LAB1 | 🟡 **70.4%** | 83.3% | 81.4% | 66.8% | 41 lines | `failed_formative, formative_pct, formative_weight, gpa, passed (+5 more)` |
| 31 | `Joshua_Gasasira` | `Rebecca_Umuragwa_Benegusenga` | LAB1 | 🟡 **70.4%** | 81.1% | 72.6% | 70.8% | 58 lines | `failed_formative, formative_weight, gpa, highest_weight, status (+4 more)` |
| 32 | `Rayan_Imanzi_Muganga` | `Rebecca_Mokeira_Isaboke` | LAB1 | 🟡 **70.2%** | 84.3% | 84.4% | 63.2% | 46 lines | `failed_formatives, formative_weight, gpa, name, passed (+4 more)` |
| 33 | `Joshua_Stanley_Hotay` | `Testimony_Chukwuamaka_Ikenwe` | LAB1 | 🟡 **70.0%** | 80.2% | 78.1% | 68.7% | 51 lines | `failed_formatives, formative_rows, formative_weight, gpa, highest_weight (+6 more)` |
| 34 | `Nicia_Greta_Agasaro` | `Noah_Muyango` | LAB1 | 🟡 **70.0%** | 84.4% | 77.4% | 68.9% | 31 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+6 more)` |
| 35 | `Belin_Sammy_Igiraneza` | `Kaze_Bernice_Samuella` | LAB1 | 🟡 **69.9%** | 80.5% | 76.5% | 69.7% | 37 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+5 more)` |
| 36 | `Landry_Rwema_Irakoze_Rwema` | `Rebecca_Mokeira_Isaboke` | LAB1 | 🟡 **69.9%** | 86.3% | 82.6% | 61.4% | 40 lines | `formative_pct, formative_weight, gpa, passed, status (+4 more)` |
| 37 | `Hana_Nouh_Fadlalla_Idriss` | `Muragwa_Hirwa_Christian` | LAB1 | 🟡 **69.7%** | 79.5% | 75.4% | 72.1% | 43 lines | `failed_formative, final_grade, formative_weight, gpa, highest_weight (+3 more)` |
| 38 | `Anaise_Umugwaneza` | `Ashton_Sacha_Cyubahiro` | LAB1 | 🟡 **69.4%** | 79.2% | 69.7% | 74.6% | 41 lines | `failed_formatives, formative_pct, formative_weight, gpa, invalid_scores (+8 more)` |
| 39 | `Hana_Nouh_Fadlalla_Idriss` | `Promis_Shema_Ihirwe` | LAB1 | 🟡 **68.8%** | 74.5% | 66.9% | 78.0% | 46 lines | `failed_formative, formative_grade, formative_weight, gpa, highest_weight (+4 more)` |
| 40 | `Kaze_Bernice_Samuella` | `SITUMA_EZRA_Prince` | LAB1 | 🟡 **68.7%** | 80.6% | 75.8% | 73.5% | 36 lines | `formative_score, formative_weight, gpa, highest_weight, status (+4 more)` |
| 41 | `Joshua_Stanley_Hotay` | `Nicia_Greta_Agasaro` | LAB1 | 🟡 **68.6%** | 70.8% | 70.0% | 85.8% | 39 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+8 more)` |
| 42 | `Elnathan_Mulugeta_Tenna` | `Sandra_Jepkosgei` | LAB1 | 🟡 **68.5%** | 78.8% | 72.3% | 76.3% | 36 lines | `formative_passed, formative_percentage, formative_score, formative_weight, gpa (+7 more)` |
| 43 | `Adit_Tong_Akeen` | `Ephrem_Nziza` | LAB2 | 🟡 **68.5%** | 83.0% | 79.7% | 58.5% | 43 lines | `cleaned_tweets, current_likes, keyword, likes_next, matches (+4 more)` |
| 44 | `Beryl_Pat_Rwagatare` | `Testimony_Chukwuamaka_Ikenwe` | LAB1 | 🟡 **68.4%** | 83.9% | 83.6% | 64.0% | 31 lines | `formative_pct, formative_points, formative_weight, gpa, highest_weight (+6 more)` |
| 45 | `Abdikarim_Abdikheir_Mohamed` | `Lemuel_Mpaka_Sano` | LAB1 | 🟡 **68.2%** | 76.8% | 68.2% | 79.5% | 34 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+5 more)` |
| 46 | `Elnathan_Mulugeta_Tenna` | `Paradis_Ange_Keza` | LAB1 | 🟡 **68.2%** | 77.7% | 74.5% | 75.0% | 44 lines | `failed_formative, formative_score, formative_weight, gpa, highest_weight (+5 more)` |
| 47 | `Hana_Nouh_Fadlalla_Idriss` | `Lana_Lysley_Keza` | LAB1 | 🟡 **68.2%** | 79.2% | 72.1% | 71.0% | 41 lines | `formative_grade, formative_weight, gpa, highest_weight, status (+3 more)` |
| 48 | `Nicia_Greta_Agasaro` | `Rayan_Imanzi_Muganga` | LAB1 | 🟡 **68.1%** | 72.1% | 69.0% | 82.4% | 35 lines | `failed_formatives, formative_score, formative_weight, gpa, highest_weight (+7 more)` |
| 49 | `Calvin_Rugwiro` | `Joshua_Gasasira` | LAB1 | 🟡 **68.0%** | 76.9% | 70.3% | 76.8% | 33 lines | `failed_formative, formative_grade, formative_weight, highest_weight, summative_grade (+4 more)` |
| 50 | `Favour_Ndelle_Kebei` | `Noah_Muyango` | LAB1 | 🟡 **68.0%** | 85.8% | 82.1% | 60.1% | 43 lines | `formative_pct, formative_weight, gpa, invalid_scores, passed (+4 more)` |
| 51 | `Mucyo_Murara_Lyan` | `SITUMA_EZRA_Prince` | LAB1 | 🟡 **68.0%** | 76.6% | 69.9% | 75.1% | 55 lines | `failed_formative, formative_weight, gpa, highest_weight, status (+3 more)` |
| 52 | `Adedotun_Oyinola_Taiwo` | `Kayitare_Anakin_Libery` | LAB1 | 🟡 **67.9%** | 82.4% | 78.9% | 64.3% | 37 lines | `failed_formatives, formative_pct, formative_weight, gpa, name (+5 more)` |
| 53 | `Alvin_Mudaheranwa` | `Regan_Odhiambo_Ayiecho` | LAB1 | 🟡 **67.9%** | 85.3% | 82.4% | 59.3% | 42 lines | `failed_formatives, formative_percent, formative_weight, gpa, highest_weight (+4 more)` |
| 54 | `Adedotun_Oyinola_Taiwo` | `Fiinsi_Laïla_Hulda_Kabore` | LAB1 | 🟡 **67.7%** | 83.9% | 77.8% | 64.3% | 38 lines | `formative_pct, formative_weight, gpa, max_weight, name (+5 more)` |
| 55 | `Alvin_Mudaheranwa` | `Musaedi_Mbongo_Isaac` | LAB1 | 🟡 **67.4%** | 86.3% | 83.0% | 55.2% | 34 lines | `failed_formatives, formative_percent, formative_weight, gpa, passed (+3 more)` |
| 56 | `Kayitare_Anakin_Libery` | `Rebecca_Mokeira_Isaboke` | LAB1 | 🟡 **67.4%** | 77.7% | 75.2% | 68.9% | 42 lines | `failed_formatives, formative_pct, formative_weight, gpa, name (+6 more)` |
| 57 | `Lana_Lysley_Keza` | `Promis_Shema_Ihirwe` | LAB1 | 🟡 **67.3%** | 70.9% | 66.3% | 83.4% | 34 lines | `formative_grade, formative_percentage, formative_weight, gpa, highest_weight (+6 more)` |
| 58 | `Quentin_Sheja_Ntabwoba` | `Rebecca_Mokeira_Isaboke` | LAB1 | 🟡 **67.3%** | 80.7% | 79.1% | 61.7% | 40 lines | `failed_formatives, formative_pct, formative_weight, gpa, max_weight (+5 more)` |
| 59 | `Adedotun_Oyinola_Taiwo` | `Quentin_Sheja_Ntabwoba` | LAB1 | 🟡 **67.1%** | 83.8% | 78.8% | 57.7% | 36 lines | `failed_formatives, formative_pct, formative_weight, gpa, max_weight (+4 more)` |
| 60 | `Abigail_Ama_Opoo_Cobbina` | `Portia_Mbiya_Kamuala` | LAB1 | 🟡 **67.0%** | 70.2% | 63.5% | 78.0% | 45 lines | `failed_formative, formative_grade, formative_weight, gpa, highest_weight (+5 more)` |

*... and 54 additional pairs. See `similarity_report.csv` or `similarity_report.html` for complete list.*

---

## Methodology & Detection Weights

1. **AST Structural Similarity (35%)**: Traverses the Python Abstract Syntax Tree in pre-order, extracting language construct sequences (loops, conditionals, assignments, exceptions) independent of renamed identifiers.
2. **Normalized Token Winnowing (30%)**: Lexical token fingerprinting with comments, whitespace, and variable names normalized into generic tokens.
3. **Identifier Vocabulary Overlap (20%)**: Jaccard similarity across unique student-defined variable, function, and parameter names (excluding template boilerplate).
4. **Text Line Alignment (15%)**: Sequence matcher on sanitized non-empty code lines.
5. **Template-Isolated Logic Adjustment**: Filters out starter template boilerplate to ensure similarity reflects custom written logic rather than provided starter code.

Generated by `code_similarity.py`.
