---
title: "Sanskrit Word Sense Disambiguation Based on Lexicographic Definitions"
collection: publications
permalink: /publication/2026-sanskrit-wsd
excerpt: "A word sense disambiguation system for Vedic and Classical Sanskrit that extends the gloss reader architecture of Blevins and Zettlemoyer (2020), trained on the Monier-Williams Sanskrit-English dictionary. The paper studies how semantic inventory choice affects WSD accuracy and identifies alignment-based and LLM-based augmentation as promising strategies for increasing coverage of underrepresented senses."
date: 2026-03-01
venue: "Proceedings of the 8th International Sanskrit Computational Linguistics Symposium (ISCLS)"
paperurl: "/files/sanskrit-wsd-iscls2026.pdf"
citation: "Hellwig, O., Sellmer, S., Nehrdich, S., Widmer, P., & Sennrich, R. (2026). &quot;Sanskrit Word Sense Disambiguation Based on Lexicographic Definitions.&quot; In <i>Proceedings of the 8th International Sanskrit Computational Linguistics Symposium</i>, IIT Roorkee, India."
---

We present a word sense disambiguation (WSD) system for Vedic and Classical Sanskrit that extends the gloss reader architecture of Blevins and Zettlemoyer (2020). Our work addresses two key questions: how semantic inventory choice affects WSD accuracy, and which data augmentation strategies can improve performance. Using the Sanskrit-English dictionary of Monier-Williams as a test case, we explore whether traditional lexicographic resources with overlapping and periphrastic definitions can be used to train a WSD system. Our model achieves high accuracy on dominant senses but struggles with secondary senses, a pattern confirmed by statistical error analysis. While model architecture has limited impact, the granularity of the semantic inventory substantially affects performance. For augmentation, we identify alignment-based and LLM-based methods as promising approaches, particularly for increasing coverage of underrepresented senses across genres and time periods.

Presented at the 8th International Sanskrit Computational Linguistics Symposium (ISCLS 2026), held March 9–11, 2026 at IIT Roorkee, India. [Conference announcement](https://iscls.github.io/papers) · [Code on GitHub](https://github.com/OliverHellwig/sanskrit/tree/master/papers/2026iscls)
