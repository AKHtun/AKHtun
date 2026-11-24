# Aung Khaing Htun

**Sovereign AI engineer — building WEcoS, the Wizaya Sovereign AI Ecosystem.**

WEcoS is a local-first, multilingual (Myanmar/English) AI platform that runs on
your own hardware: model inference, retrieval and every corpus stay local, and
cloud tiers are opt-in and off by default. It specialises in Burmese epigraphy
— palm-leaf manuscripts, lithic inscriptions, archaic orthography, formal
syllable segmentation — and in industrial tribology.

> **Disambiguation:** WEcoS here is a *software ecosystem*. It is unrelated to
> WECO Electrical Connectors (German industrial connectors), Weco Srl (Italian
> welding), WECO Elevator Products, or Western Electric Company.

**Canonical site → [akhtun.github.io](https://akhtun.github.io/)**
**Machine-readable map → [llms.txt](https://akhtun.github.io/llms.txt)**

## Public projects

| Project | What it is |
|---|---|
| [wecos-ocr](https://github.com/AKHtun/wecos-ocr) | Sovereign Myanmar OCR, historical epigraphical decipherment and syllable segmentation. `pip install wecos-ocr` |
| [wecos-myanmar-ocr-8b (GGUF)](https://huggingface.co/AKHtun/wecos-myanmar-ocr-8b-GGUF) | Quantised Myanmar OCR vision-language model for local Ollama / llama.cpp |
| [wecos-product-recommendar](https://github.com/AKHtun/wecos-product-recommendar) | Lubricant, fuel, DEF, coolant and grease recommendation, traced to manufacturer data sheets |
| [wecos-gemini-protocol](https://github.com/AKHtun/wecos-gemini-protocol) | Async message-passing protocol for Gemini Gems ↔ the Wizaya ecosystem |

## Working on it

The platform itself is private and deliberately so — it is a research system
under active development. The parts that are finished are released publicly
under Apache-2.0, with the interesting behaviour unit-tested: the MLC 2003
dictionary pass in `wecos-ocr` is opt-in precisely because a modern word list
silently corrupts archaic Burmese dates.

<!-- STAY IN TOUCH: github.com/AKHtun -->
