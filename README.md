# GovLLM Project

## Overview
This repository contains a comprehensive toolkit for operationalizing Government Technology (GovTech) benchmarks using Large Language Models (LLMs). It spans the full lifecycle of GovTech framework benchmarking, from data scraping and cleaning to generating prompts and operationalizing benchmarks with LLMs.

## Installation
To set up the project, ensure you have Python installed, then run the following commands:
```bash
git clone https://github.com/bierend/LLM4GovTracking
cd LLM4GovTracking-main
pip install -r requirements.txt
```

## Usage
Each document in the repo includes specific guidelines on its use. 

## Directory Structure
- **Data Scraping:** Scripts to extract data from various sources like the Dutch Government Open Data Portal, Tendernet, Woogle, and iBestuur.
- **Data Processing:** Converts raw data into a structured format suitable for retrieval-augmented generation, using ChromaDB vector databases.
- **Model Finetuning:** Uses transformers to finetune the model.
- **Model:** Run the LLM with different configurations to operationalize the GTMI benchmark.
- **Results:** Contains the data of model operationalizations across different configurations.
- **Evaluation:** Analyzes outcomes and generates visualizations to demonstrate the model's accuracy in applying the GTMI-benchmark.

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests.

## License
This project is open and freely usable by everyone. There is no specific license associated with it, allowing for unrestricted use, modification, and distribution.

## Authors
This project was carried out by B. Nieuwschepen and C. Snoeij as part of their master thesis project for the Master of Engineering and Policy Analysis at TU Delft, from October 2023 to June 2024.

## Contact
For more information about this project, please send an email to [C. Snoeij](mailto:cornesnoeij+github@gmail.com).

