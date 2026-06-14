# Coptic Deacon Responses

A comprehensive reference collection of Coptic Orthodox deacon responses for liturgical services, presented in multiple languages: **English**, **Coptic**, **Arabic**, and **Coptic transliteration**.

## 📖 Overview

This repository contains structured documentation of deacon responses used in the Coptic Orthodox Church. Each response is provided with:

- **Response Name** – Title/identifier of the response
- **English** – English translation
- **Coptic** – Original Coptic text
- **Arabic** – Arabic translation
- **Coptic English Transliteration** – Phonetic pronunciation guide

## Font Note

The Coptic text in this repository is stored as **Unicode Coptic** in the Markdown source files.

The Word generator converts the Coptic column into the legacy **Avva Shenouda** encoding when it builds the `.docx` files, then assigns the **Avva_Shenouda** font to those runs automatically. This is necessary because the bundled Avva Shenouda fonts do not use Unicode Coptic code points directly.

If you edit the Markdown files, keep the source text in Unicode Coptic and regenerate the `.docx` files with `create_word_doc.py`.

## Coptic Reader Edition Font Note

The `copticreader/` edition uses the `Avva_Shenouda` font. The generator converts the Unicode Coptic column into the legacy Avva Shenouda encoding during Word export, matching the original deacon-reference files.

- Word generator: `create_word_doc_copticreader.py`
- Encoding: standard Unicode Coptic in Markdown, converted during Word export
- Font file: install `fonts/copticfonts/Avva_Shenouda.ttf` (or `Avva_ShenoudaNormal.TTF`) before opening the `.docx` files

## 📂 Contents

### Vespers & Matins (Evening & Morning Prayers)
| File | Description |
|------|-------------|
| [vesper-matins_deacon_responses_full.md](vesper-matins_deacon_responses_full.md) | Complete table with all response texts |
| [vesper-matins_deacon_responses_contents.md](vesper-matins_deacon_responses_contents.md) | Summary/index of responses |
| [vesper-matins_deacon_responses_requirements.md](vesper-matins_deacon_responses_requirements.md) | Documentation requirements |

### Divine Liturgy (القداس الإلهي)
| File | Description |
|------|-------------|
| [divine-liturgy_deacon_responses_full.md](divine-liturgy_deacon_responses_full.md) | Complete table with all response texts |
| [divine-liturgy_deacon_responses_contents.md](divine-liturgy_deacon_responses_contents.md) | Summary/index of responses |
| [divine-liturgy_deacon_responses_requirements.md](divine-liturgy_deacon_responses_requirements.md) | Documentation requirements |

### Coptic Reader Edition (St. Basil, Vespers, Matins)
| File | Description |
|------|-------------|
| [copticreader/divine-liturgy_deacon_responses_full.md](copticreader/divine-liturgy_deacon_responses_full.md) | St. Basil deacon responses with compact symbol markers |
| [copticreader/divine-liturgy_deacon_responses_contents.md](copticreader/divine-liturgy_deacon_responses_contents.md) | Contents summary for the St. Basil set |
| [copticreader/divine-liturgy_deacon_responses_requirements.md](copticreader/divine-liturgy_deacon_responses_requirements.md) | Requirements for compact St. Basil output |
| [copticreader/vesper-matins_deacon_responses_full.md](copticreader/vesper-matins_deacon_responses_full.md) | Vespers and Matins responses with compact symbol markers |
| [copticreader/vesper-matins_deacon_responses_contents.md](copticreader/vesper-matins_deacon_responses_contents.md) | Contents summary for Vespers and Matins |
| [copticreader/vesper-matins_deacon_responses_requirements.md](copticreader/vesper-matins_deacon_responses_requirements.md) | Requirements for compact Vespers and Matins output |
| [create_word_doc_copticreader.py](create_word_doc_copticreader.py) | Generates Coptic Reader Word documents |

### Source Snapshots (for future extraction)
| File | Description |
|------|-------------|
| [source_data/copticreader_liturgy_faithful_snapshot.txt](source_data/copticreader_liturgy_faithful_snapshot.txt) | Raw Liturgy of the Faithful snapshot |
| [source_data/copticreader_offering_snapshot.txt](source_data/copticreader_offering_snapshot.txt) | Raw Offering of the Lamb snapshot |
| [source_data/copticreader_vespers_snapshot.txt](source_data/copticreader_vespers_snapshot.txt) | Raw Vespers snapshot |
| [source_data/copticreader_matins_snapshot.txt](source_data/copticreader_matins_snapshot.txt) | Raw Matins snapshot |

## 🎯 Purpose

This resource is designed for:

- **Deacons** – Quick reference during services
- **Students** – Learning Coptic pronunciation and liturgical texts
- **Chanters** – Understanding the structure of responses
- **Educators** – Teaching materials for Sunday school or deacon training
- **Researchers** – Studying Coptic liturgical traditions

## 📋 Services Covered

- ✅ Vespers (Evening Prayer / صلاة المساء)
- ✅ Matins (Morning Prayer / صلاة باكر)
- ✅ Divine Liturgy – Offertory (رفع الحمل)
- ✅ Divine Liturgy – Liturgy of the Believers (قداس المؤمنين)

## 🔤 Transliteration Guide

The Coptic English transliteration follows standard conventions:

| Coptic | Transliteration | Sound |
|--------|-----------------|-------|
| Ⲁ/ⲁ | a | as in "father" |
| Ⲉ/ⲉ | e | as in "bet" |
| Ⲏ/ⲏ | ē/i | as in "see" |
| Ⲓ/ⲓ | i | as in "sit" |
| Ⲟ/ⲟ | o | as in "go" |
| Ⲩ/ⲩ | ou/u | as in "you" |
| Ⲱ/ⲱ | ō | as in "more" |
| Ϣ/ϣ | sh | as in "ship" |
| Ϧ/ϧ | kh | as in "Bach" |
| Ϩ/ϩ | h | as in "house" |
| Ϫ/ϫ | j | as in "judge" |
| Ϭ/ϭ | ch | as in "church" |
| Ϯ/ϯ | ti | as in "tip" |

## 📚 Data Source

Content is compiled from [Tasbeha.org Hymn Library](https://tasbeha.org/hymn_library/), a trusted resource for Coptic hymns and liturgical texts.

The Coptic Reader edition is compiled from [copticreader.org](https://copticreader.org/).

## Generate Word Files

1. Original Tasbeha edition:
	- `python create_word_doc.py`
2. Coptic Reader edition:
	- `python create_word_doc_copticreader.py`

## 🤝 Contributing

Contributions are welcome! If you find errors or want to add more services:

1. Fork this repository
2. Make your changes
3. Submit a pull request

Please ensure accuracy by cross-referencing with official Coptic Orthodox sources.

## 📜 License

This content is shared for educational and religious purposes. The liturgical texts belong to the Coptic Orthodox Church tradition.

## 🙏 Acknowledgments

- [Tasbeha.org](https://tasbeha.org/) for the comprehensive hymn library
- The Coptic Orthodox Church for preserving these ancient traditions

---

*Glory be to God forever. Amen.*

*ⲇⲟⲝⲁ ⲡⲁⲧⲣⲓ ⲕⲉ ⲩⲓⲱ ⲕⲉ ⲁⲅⲓⲱ ⲡⲛⲉⲩⲙⲁⲧⲓ*
