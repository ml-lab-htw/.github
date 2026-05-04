# KI Werkstatt der HTW Berlin

> Ein Ort zum gemeinsamen Forschen, Lehren und Anwenden von KI-Technologie.

## 👋 Willkommen auf der offiziellen GitHub-Seite der KI-Werkstatt der HTW Berlin!

Hier findet ihr eine Sammlung von Projekten, Code-Beispielen und Ressourcen, die im Rahmen unserer Aktivitäten in Forschung, Lehre und Praxis entstehen.

## 🚀 Über Uns

Die KI-Werkstatt der HTW Berlin ist ein zentraler Ort für das gemeinsame Lehren, Forschen und Anwenden von KI-Technologie auf aktuelle Praxisprobleme. Unser Ziel ist es, eine hochschulweite Infrastruktur zu schaffen, die es Studierenden, Lehrenden und Forschenden ermöglicht, KI-Algorithmen auf höchstem wissenschaftlichem Niveau zu nutzen und weiterzuentwickeln.

## 🔬 Was wir tun

Unsere Arbeit konzentriert sich auf drei Kernbereiche:

*   **🎓 Lehre:** Mit der KI-Lehr-Werkstatt Interdisziplinär (KIWI) schaffen wir einen Raum für das gemeinsame Lehren, Lernen und Anwenden von KI. Wir entwickeln einen KI-Modulbaukasten, um die KI-Lehre interdisziplinär zu fördern.
*   **🔬 Forschung:** Wir fördern die interdisziplinäre und gemeinsame Forschung zum Thema Künstliche Intelligenz an der HTW Berlin.
*   **💻 Service & Anwendung:** Wir stellen eine leistungsstarke Infrastruktur, wie unseren neuen Ollama Server mit 2x H100 GPUs, zur Verfügung und unterstützen bei der Umsetzung innovativer Projekte.

## 🧪 RamanBench — Benchmark für Raman-Spektroskopie-KI

RamanBench ist ein offenes Benchmark-Framework für das systematische Evaluieren von ML-Modellen auf Raman-Spektroskopiedaten — inklusive öffentlichem Leaderboard und einem kuratierten Datensatz-Paket.

| | |
|---|---|
| 🏆 **Leaderboard** | [huggingface.co/spaces/HTW-KI-Werkstatt/RamanBench](https://huggingface.co/spaces/HTW-KI-Werkstatt/RamanBench) |
| 📦 **RamanBench** | [![GitHub](https://img.shields.io/badge/GitHub-RamanBench-181717?logo=github)](https://github.com/ml-lab-htw/RamanBench) [![PyPI](https://img.shields.io/pypi/v/raman-bench?label=raman-bench)](https://pypi.org/project/raman-bench/) |
| 📊 **raman-data** | [![GitHub](https://img.shields.io/badge/GitHub-raman__data-181717?logo=github)](https://github.com/ml-lab-htw/raman_data) [![PyPI](https://img.shields.io/pypi/v/raman-data?label=raman-data)](https://pypi.org/project/raman-data/) |

```bash
pip install raman-bench raman-data
```

## 🌲 llm-trees — Zero-Shot Decision Trees mit LLMs

LLMs nutzen ihr komprimiertes Weltwissen, um intrinsisch interpretierbare Entscheidungsbäume ohne Trainingsdaten zu generieren. Zero-Shot-Bäume übertreffen auf kleinen tabellarischen Datensätzen teils datengetriebene Verfahren; Embeddings daraus liefern starke neue Baselines im Low-Data-Regime.

📄 Paper: [arXiv:2409.18594](https://arxiv.org/abs/2409.18594) — *"Oh LLM, I'm Asking Thee, Please Give Me a Decision Tree"*

| | |
|---|---|
| 📦 **llm-trees** | [![GitHub](https://img.shields.io/badge/GitHub-llm--trees-181717?logo=github)](https://github.com/ml-lab-htw/llm-trees) [![PyPI](https://img.shields.io/pypi/v/llm_trees?label=llm-trees)](https://pypi.org/project/llm_trees/) |

```bash
pip install llm_trees
```

## 🔍 concept-tracer — Konzeptbasierte Analyse von KI-Repräsentationen

Interaktives Werkzeug zur Analyse neuronaler Netzwerkrepräsentationen durch menschlich interpretierbare Konzepte. Zwei informationstheoretische Maße quantifizieren Konzeptsalienz und -selektivität; ein Web-Dashboard macht Ergebnisse explorierbar.

📄 Paper: [arXiv:2604.07019](https://arxiv.org/abs/2604.07019)

| | |
|---|---|
| 📦 **concept-tracer** | [![GitHub](https://img.shields.io/badge/GitHub-concept--tracer-181717?logo=github)](https://github.com/ml-lab-htw/concept-tracer) [![PyPI](https://img.shields.io/pypi/v/concept-tracer?label=concept-tracer)](https://pypi.org/project/concept-tracer/) |

```bash
pip install concept-tracer
```

## 🔢 tab-embeddings — LLM-Embeddings für Tabellendaten

Experimentelles Framework zum Training und zur Evaluation von ML-Modellen auf tabellarischen Daten, angereichert durch LLM-basierte Text-Embeddings. Unterstützt 16 LLM-Embedding-Quellen, Random Tree Embeddings und verschiedene Fusionsstrategien.

| | |
|---|---|
| 📦 **tab-embeddings** | [![GitHub](https://img.shields.io/badge/GitHub-tab--embeddings-181717?logo=github)](https://github.com/ml-lab-htw/tab-embeddings) |

## 📊 deepbench — Robustheitsbenchmark für Bildklassifikation

CLI-Tool zur systematischen Evaluation von Bildklassifikationsmodellen unter Bildaugmentierungen (Helligkeit, Blur, Rauschen, Wetterbedingungen u. v. m.). Unterstützt Hugging Face- und Ollama-Modelle (VLMs, CNNs, ViTs). Entwickelt im Rahmen des TAHAI-Projekts.

| | |
|---|---|
| 📦 **deepbench** | [![GitHub](https://img.shields.io/badge/GitHub-deepbench-181717?logo=github)](https://github.com/ml-lab-htw/deepbench) |

## 🏷️ iterative-annotate — Feedbackgetriebene Objektdetektion

Mono-Repo für iterative Modellanpassung durch menschliches Feedback bei der Objektdetektion. Kombiniert ein Next.js-Frontend und ein FastAPI-Backend (GPU-fähig) via Docker Compose.

| | |
|---|---|
| 📦 **iterative-annotate** | [![GitHub](https://img.shields.io/badge/GitHub-iterative--annotate-181717?logo=github)](https://github.com/ml-lab-htw/iterative-annotate) |

## 🩺 optical_mammography_analysis — KI-Analyse optischer Mammographiedaten

ML-Algorithmen zur Erkennung von Brustkrebs aus zeitaufgelösten optischen Mammographiedaten. Enthält Klassifikations- und AutoML-Experimente sowie eine Sparsifizierungssimulation reduzierter Hardwarekonfigurationen.

| | |
|---|---|
| 📦 **optical_mammography_analysis** | [![GitHub](https://img.shields.io/badge/GitHub-optical__mammography__analysis-181717?logo=github)](https://github.com/ml-lab-htw/optical_mammography_analysis) |

## 🤝 Mach mit!

Du möchtest ein KI-Projekt starten, hast eine Idee für eine Kooperation oder möchtest einfach mehr erfahren? Wir freuen uns immer über neue Gesichter und spannende Ideen.

## 📬 Kontakt

*   **Webseite:** [https://kiwerkstatt.f2.htw-berlin.de/](https://kiwerkstatt.f2.htw-berlin.de/)
*   **Kontakt:** [Kontaktiere Uns](https://kiwerkstatt.f2.htw-berlin.de/#/kontaktiere-uns)

---
