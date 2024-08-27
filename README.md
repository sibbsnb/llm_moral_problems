# README for "Universals and Variations in Moral Decisions Made by Large Language Models" Paper

## Introduction

This repository contains the code and data used in the paper titled "Universals and Variations in Moral Decisions Made by Large Language Models." The study examines the moral decision-making capabilities of large language models (LLMs) using classic sacrificial dilemmas and introduces a novel scenario to explore the influence of personal relationships on AI ethics.

## Repository Contents

- **moral_3_questions.ipynb**: The Jupyter notebook containing all the code used for running the experiments and analyzing the results.
- **Figures**: A directory containing all the figures used in the paper.
- **requirements.txt**: A file listing all the Python libraries required to run the code in the Jupyter notebook.

## Requirements

- Python 3.11.9
- Jupyter Notebook
- Required Python libraries listed in `requirements.txt`

## Setup Instructions

1. Clone the repository to your local machine.
2. Install the required Python libraries:
    ```sh
    pip install -r requirements.txt
    ```
3. Create a file named `.env` in the root directory of the repository and add your API keys for OpenAI, Claude, and Gemini in the following format:
    ```sh
    openai_key="YOUR_OPENAI_KEY"
    claude_key="YOUR_CLAUDE_KEY"
    google_key="YOUR_GEMINI_KEY"
    ```

## Running the Code

1. Open the `moral_3_questions.ipynb` Jupyter notebook.
2. Run the notebook cells to execute the experiments and generate the results. The notebook is organized into sections corresponding to the different scenarios analyzed in the study (Switch, Loop, Footbridge, and Friend scenarios).

## Notes

- Ensure that your API keys are valid and have sufficient quota to run the experiments.
- The notebook is designed to be run sequentially, with each cell building on the results of the previous ones.

## Contact

For any questions or issues, please contact Sibish Neelikattil Basheer Ahammed at sibbsnb@gmail.com.

## Published Paper link
https://www.ijmra.us/project%20doc/2024/IJME_SEPTEMBER2024/IJMIE5_Sep24_66232.pdf

---

Thank you for your interest in our work. Your feedback and contributions are highly appreciated.
