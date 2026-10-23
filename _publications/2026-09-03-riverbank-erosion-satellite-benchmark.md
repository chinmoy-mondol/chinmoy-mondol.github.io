---
title: "A Multi-Decade Satellite Benchmark for Forecasting Riverbank Erosion in Large Braided Rivers"
collection: publications
category: in_preparation
permalink: /publication/2026-riverbank-erosion-satellite-benchmark
excerpt: ''
date: 2026-09-03
venue: 'Manuscript in preparation'
---

**Abstract**

Riverbank erosion along Bangladesh's Jamuna (Brahmaputra) and Padma rivers destroys farmland and homes every year. Satellite archives now span almost four decades, and deep spatiotemporal networks have begun to forecast river planform, yet each published study uses its own reach, period, resolution and split, and none we found releases its data with a fixed protocol, so methods cannot be compared. We present an open benchmark built from public imagery: Landsat Collection 2 surface reflectance at 30 m for the dry seasons of 1988–2026, Sentinel-2 from 2017, and Sentinel-1 radar to fill cloud gaps. For each dry season we derive a water mask, an active channel belt and left and right banklines, and we check them by hand on a stratified sample. Three tasks are defined: next-year erosion maps, bankline displacement at fixed transects, and forecasts two to five years ahead. Splits are fixed in time (train up to 2014, validation 2015–2018, test 2019–2026) and in space (held-out reaches). Metrics cover overlap, ranking of rare erosion pixels, displacement error and probability calibration, with confidence intervals from a reach-level bootstrap. Baselines run from persistence, erosion climatology and linear bank-migration extrapolation to U-Net, ConvLSTM, Earthformer and a fine-tuned Prithvi-EO-2.0 foundation model. Data, splits and code will be released under open licences.
