---
layout: post
mathjax: true
title: "Note for DianNao"
author: "Chongxiao Li"
tags: ["accelerator", "diannao", "paper", "note"]
---

# Note for *DianNao: A Small-Footprint High-Throughput Accelerator for Ubiquitous Machine-Learning*

## BACKGROUNDS

- Broad application of machine learning algorithms needs speeding up.

- Current works either ignore memory transfers for simplicity, or directly plug their computational accelerator to memory via a sophisticated DMA.

- Memory transfers should be a first-order concern in the design of accelerators.
