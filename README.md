# Solar Challenge - Week 1

This repository contains the code for the Solar Challenge project (Week 1).

## How to reproduce the environment

1.  **Clone the repository:**

    ```cmd
    git clone <repository_url>
    cd solar-challenge-week1
    ```

2.  **Create a virtual environment:**

    * **Using `venv`:**

        ```bash
        python3 -m venv .venv
        source .venv/bin/activate  # On macOS/Linux
        .venv\Scripts\activate  # On Windows
        ```

    * **Using `conda`:**

        ```bash
        conda create -n solar-challenge-week1 python=3.9  # Or your preferred Python version
        conda activate solar-challenge-week1
        ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Folder Structure

```
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows
│       └── ci.yml
├── .gitignore
├── requirements.txt
├── README.md
│------ src/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md