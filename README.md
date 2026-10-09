# 🦷 Big Data Dental LLM Benchmark: Gemma vs. Qwen

An empirical comparative evaluation of open-weight Large Language Models (LLMs), focusing on their performance when processing specialized dental and medical patient records containing mixed-script text, including Bangla and transliterated Bangla.

## 📌 Project Overview

This project explores the application of Large Language Models to dental and medical data analysis, with a particular focus on multilingual and mixed-script patient records.

The project compares **Gemma** and **Qwen** to investigate their suitability for processing healthcare-related text in challenging linguistic settings.

Bangla healthcare records may contain native Bangla, English medical terminology, and Bangla written using the Latin alphabet. These variations can make consistent text processing and interpretation challenging for language models.

This project provides an experimental framework for examining these challenges through data science and comparative model evaluation.

## 🎯 Objectives

* Compare Gemma and Qwen on specialized dental and medical text data.
* Explore the challenges of processing Bangla and transliterated Bangla records.
* Investigate the behavior of open-weight LLMs on healthcare-related textual data.
* Apply data science techniques to organize, analyze, and evaluate experimental results.
* Identify potential limitations and opportunities for multilingual healthcare NLP research.

## ✨ Key Features

* **Comparative LLM Evaluation:** Studies two open-weight model families, Gemma and Qwen.
* **Healthcare-Focused Data:** Focuses on dental and medical patient records.
* **Mixed-Script Text Analysis:** Addresses Bangla, English, and transliterated text.
* **Notebook-Based Workflow:** Provides an interactive environment for data analysis and experimentation.
* **Research Documentation:** Includes a project report and supporting project resources.

## 🤖 Models Under Study

| Model Family | Description                                            |
| ------------ | ------------------------------------------------------ |
| Gemma        | Open-weight language models developed by Google        |
| Qwen         | Open-weight language models developed by the Qwen team |

The specific model versions, experimental configurations, and evaluation procedures should be taken from the accompanying notebook and project report.

## 🛠️ Technologies and Tools

The project is organized around a Jupyter Notebook-based data science workflow.

* Python
* Jupyter Notebook
* Data Science and Exploratory Data Analysis
* Natural Language Processing (NLP)
* Large Language Models (LLMs)
* Gemma and Qwen

Additional Python libraries and model dependencies should be installed according to the imports and instructions in the notebook.

## 📂 Repository Structure

```text
Big-data-Dental-LLM-Benchmark-Gemma-Qwen-project/
│
├── Data_Science_lab.ipynb
├── project_report (1).pdf
├── images-20261009T165051Z-1-001.zip
└── README.md
```

**File descriptions**

* `Data_Science_lab.ipynb` — Main notebook for the project's data science and experimental workflow.
* `project_report (1).pdf` — Project report describing the research and its findings.
* `images-20261009T165051Z-1-001.zip` — Supporting image resources.
* `README.md` — Project overview, documentation, and setup guidance.

## ⚙️ Getting Started

### Prerequisites

Before running the project, ensure that you have:

* Python installed.
* Jupyter Notebook or JupyterLab.
* The Python packages required by the notebook.
* Access to the required datasets and model resources, where applicable.
* Sufficient computing resources for the selected LLMs.

### 1. Clone the Repository

```bash
git clone https://github.com/MdTaizol/Big-data-Dental-LLM-Benchmark-Gemma-Qwen-project.git
```

### 2. Navigate to the Project Directory

```bash
cd Big-data-Dental-LLM-Benchmark-Gemma-Qwen-project
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

On Linux or macOS:

```bash
source .venv/bin/activate
```

### 4. Install Jupyter Notebook

```bash
python -m pip install --upgrade pip
python -m pip install notebook
```

Install any additional libraries required by the notebook before running its cells.

### 5. Launch the Notebook

```bash
jupyter notebook
```

Open `Data_Science_lab.ipynb` in the browser and execute the cells in sequence.

**Note:** Model loading or inference may require additional dependencies, model downloads, authentication, GPU memory, or access to an appropriate execution environment. Follow the notebook's instructions for the exact requirements.

## 📊 Experimental Evaluation

The project is designed to investigate the comparative behavior of Gemma and Qwen on mixed-script dental and medical records.

The evaluation should be interpreted in the context of:

* Language and script variation.
* Healthcare-specific terminology.
* Input data quality and consistency.
* Model configuration and inference settings.
* The evaluation criteria and experimental results documented in the project report.

Actual performance scores, quantitative comparisons, and conclusions should be reported from the completed experiments rather than assumed in advance.

## 🩺 Potential Applications

This research may help inform future work on:

* Healthcare text processing in Bangla.
* Dental record analysis.
* Multilingual and code-mixed NLP.
* Evaluation of open-weight language models.
* Healthcare-oriented AI research.

**Important:** This project is for academic and research purposes. Its outputs should not be treated as medical advice, a diagnosis, or a substitute for evaluation by a qualified healthcare professional.

## ⚠️ Limitations and Responsible Use

* Language model outputs can contain inaccurate or misleading information.
* Performance on one dataset may not generalize to other healthcare settings.
* Transliteration, spelling variation, and mixed-language text may affect model behavior.
* Results depend on the dataset, model versions, prompts, and evaluation methodology.
* Patient data must be handled in accordance with applicable privacy, security, and ethical requirements.

Do not upload identifiable patient information or use experimental outputs to make clinical decisions without appropriate validation and professional oversight.

## 🔮 Future Improvements

Potential extensions of this project include:

* Expanding the evaluation dataset with appropriately de-identified and ethically sourced records.
* Adding more open-weight language models to the benchmark.
* Establishing standardized evaluation metrics and reproducible experimental settings.
* Evaluating robustness across Bangla, English, and transliterated Bangla.
* Improving documentation of model configurations and computational requirements.
* Developing reproducible evaluation pipelines and visual comparisons.

These are possible future directions, not claims that the features have already been implemented.

## 📚 Project Resources

* **GitHub Repository:** [Big-data-Dental-LLM-Benchmark-Gemma-Qwen-project](https://github.com/MdTaizol/Big-data-Dental-LLM-Benchmark-Gemma-Qwen-project)
* **Main Notebook:** [Data_Science_lab.ipynb](https://github.com/MdTaizol/Big-data-Dental-LLM-Benchmark-Gemma-Qwen-project/blob/main/Data_Science_lab.ipynb)
* **Project Report:** [View the PDF report](https://github.com/MdTaizol/Big-data-Dental-LLM-Benchmark-Gemma-Qwen-project/blob/main/project_report%20%281%29.pdf)

## 👨‍💻 Author

**Md Taizol Islam**

GitHub: [@MdTaizol](https://github.com/MdTaizol)

## 📄 License

No license has been specified in this README. If you intend to distribute or allow others to reuse this project, consider adding an appropriate open-source license after confirming that you have permission to share all included code, datasets, and other resources.

---

*An academic exploration of open-weight LLM evaluation for mixed-script dental and medical text.*


