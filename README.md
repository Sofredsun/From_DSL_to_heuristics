# From_DSL_to_heuristics
# Results of the scientific research work  
**"From DSL to heuristics: generating priority rules for basic GA/SGS with minimum dialogue cost"**

This repository contains the results of my scientific research dedicated to **automatic generation of heuristics for schedule building** using **Large Language Models (LLMs)**.

---

## Project Description

This work explores the capabilities of LLMs for generating effective heuristics used in scheduling algorithms. The process of heuristic generation is based on two types of input data:

- **DSL Description.json**: A structured description of the project written in a Domain-Specific Language (DSL). This file includes project metadata that is incorporated into LLM prompts for heuristic code generation.
- **Text Description.txt**: A natural language description of the project. This format is used to evaluate the LLM's performance in code generation when provided with more flexible, human-readable input.

---

## Repository Structure

- **Cases**: Contains initial datasets representing different projects for which heuristics are generated.
- **Experiments**: Contains the results of heuristic generation. Each test script includes Jupyter Notebooks demonstrating successful implementations of the generated code.

---

## Files for Each Case

For each project case, you will find:

1. **`<Case Name> DSL.ipynb`**  
   Jupyter Notebook with one of the successful realizations of a heuristic generated based on the DSL prompt.

2. **`<Case Name> text.ipynb`**  
   Jupyter Notebook with one of the successful realizations of a heuristic generated based on the text prompt.

---

## Author

**Sofya Mikhaleva**  
Email: [sofyamikhaljova@yandex.ru](mailto:sofyamikhaljova@yandex.ru)

---

