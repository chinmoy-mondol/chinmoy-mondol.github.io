---
title: "Shaping Matters: Benchmarking and Fixing Visual Text Rendering for Indic Scripts in Diffusion Models"
collection: publications
category: in_preparation
permalink: /publication/2026-indic-visual-text-rendering
excerpt: ''
date: 2026-09-02
venue: 'Manuscript in preparation'
---

**Abstract**

Text-to-image models now render legible text in several languages, but scripts that require complex shaping, such as Bengali and Devanagari, combine consonants into conjuncts and reorder or split vowel signs. We introduce IndicTextBench, a benchmark for visual text rendering in Bengali, Devanagari and Tamil, with an English control. Prompts embed target strings drawn from Wikipedia vocabulary and stratified by length, conjunct density and vowel-sign type; ground truth is a Unicode NFC string with its grapheme-cluster segmentation and a HarfBuzz-shaped reference rendering. We score open and API models with OCR exact-match accuracy, character and grapheme-cluster error rates using Tesseract's Indic models, a shaping-error taxonomy, and a native-reader transcription study that also validates the OCR metric. We further propose shaping-aware conditioning, which conditions a renderer on shaped glyph clusters rather than code points.
