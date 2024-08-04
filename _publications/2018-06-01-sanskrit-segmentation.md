---
title: "Sanskrit Word Segmentation Using Character-level Recurrent and Convolutional Neural Networks"
collection: publications
permalink: /publication/2018-sanskrit-word-segmentation
excerpt: 'This paper presents end-to-end neural network models for Sanskrit tokenization, jointly handling compound splitting and Sandhi resolution. The language-agnostic models outperform previous approaches for Sanskrit and also excel in German compound splitting.'
date: 2018-01-01
venue: "Conference on Empirical Methods in Natural Language Processing"
paperurl: "https://api.semanticscholar.org/CorpusID:53081590"
citation: "Hellwig, O., & Nehrdich, S. (2018). &quot;Sanskrit Word Segmentation Using Character-level Recurrent and Convolutional Neural Networks.&quot; In <i>Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP)</i>."
---

The paper introduces end-to-end neural network models that tokenize Sanskrit by jointly splitting compounds and resolving phonetic merges (Sandhi). Tokenization of Sanskrit depends on local phonetic and distant semantic features that are incorporated using convolutional and recurrent elements. Contrary to most previous systems, our models do not require feature engineering or extern linguistic resources, but operate solely on parallel versions of raw and segmented text. The models discussed in this paper clearly improve over previous approaches to Sanskrit word segmentation. As they are language agnostic, we will demonstrate that they also outperform the state of the art for the related task of German compound splitting.