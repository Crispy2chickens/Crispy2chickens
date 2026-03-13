# Jolie Teo

**Stanford University · Intelligent Systems & Software**

I'm interested in intelligent systems — how models perceive, decide, and act in the real world.
I like building systems that connect machine learning with real deployment, from training models to shipping usable tools.

---

## Highlighted Projects

### Planet Satellite Data Workflow System _(In Development)_

A natural-language interface for satellite data analysis designed for conservation teams that need insights from Planet imagery without navigating complex APIs or documentation.

- Builds a **structured knowledge base** by scraping Planet documentation and Jupyter notebooks to extract workflow patterns, API endpoints, and satellite band relationships
- Uses **RAG** to retrieve relevant code blocks conditioned on user intent
- A **planning agent** generates and validates an analysis plan before assembling any code
- Produces executable `.ipynb` pipelines with normalized variables, shared imports, injected parameters, and markdown explanations
- Includes an **interactive assistant** for explaining, modifying, and debugging generated workflows

`Python` `RAG` `LLM Agents` `Jupyter` `Planet API`

---

### Handwritten Chinese Character Recognition (HCCR)

Custom implementation of **ResNet101** and **DenseNet121** with CBAM and SE attention modules, trained on the **CASIA HWDB1.1** dataset (200 classes).

- **96.2% test accuracy** with DenseNet121
- CBAM reduced convergence time by ~30% (epoch 23 vs 33) with near-identical accuracy
- Observed architecture-dependent effects: CBAM improved DenseNet convergence but degraded ResNet performance
- Built a full preprocessing pipeline (dataset extraction → resize → contrast enhancement)
- Includes a **GUI for real-time handwriting inference**

GUI:  
https://github.com/Crispy2chickens/hccr-gui

`Python` `PyTorch` `CNNs` `CBAM`

---

### Drone Heatmap — Resource Allocation Tool

Full-stack web application designed to help organizations allocate resources in **remote and underserved regions**.

- Processes drone imagery and generates **interactive geospatial heatmaps**
- Enables spatial data exploration through an intuitive Google Maps interface
- Designed around real-world decision workflows for field teams

`JavaScript` `Google Maps API` `Full-stack`

---

## Technical Stack

|                |                                       |
| -------------- | ------------------------------------- |
| **Languages**  | Python, C/C++, TypeScript, JavaScript |
| **ML / AI**    | PyTorch, CNNs, attention mechanisms   |
| **ML Systems** | RAG pipelines, LLM agents             |
| **Frontend**   | React, Next.js                        |
| **Backend**    | Node.js, SQL                          |

---

## Contact

Email: jteo0814@gmail.com
