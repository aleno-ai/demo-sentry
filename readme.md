# Sentry Demo Setup Guide

## Introduction

This guide will walk you through setting up your Python environment to run Aleno's Sentry Demo in Jupyter Notebook within Visual Studio Code (VSCode).

## Prerequisites

Before you begin, ensure that you have the following installed:
- Python (3.x recommended)
- Visual Studio Code
- Python extension for VSCode (can be installed from the VSCode marketplace)

## Installation

### Step 1: Clone the Repository

Clone the project repository to your local machine. If the repository is located on GitHub, you can clone it using the following command:

```bash
git clone https://github.com/aleno-ai/demo-sentry
cd demo-sentry
```

### Step 2: Create a Virtual Environment

Navigate to the project directory and create a Python virtual environment by running:

```bash
python -m venv venv
```

### Step 3: Activate the Virtual Environment

Activate the virtual environment. On Windows, run:

```bash
venv\Scripts\activate
```

On macOS and Linux, run:

```bash
source venv/bin/activate
```

### Step 4: Install Dependencies

With the virtual environment activated, install the required Python packages listed in requirements.txt:

```bash
pip install -r requirements.txt
```

### Step 5: Install Jupyter

Install Jupyter within the virtual environment:

```bash
pip install notebook
```

## Running a Jupyter Notebook

### Step 1: Open VSCode
Open Visual Studio Code and ensure that the Python extension is installed and enabled.

### Step 2: Open the Project Folder
From the File menu, choose Open Folder and select your project directory.

### Step 3: Start Jupyter Server
Open the command palette in VSCode (using Ctrl+Shift+P or Cmd+Shift+P), and type Jupyter: Create New Blank Notebook, then hit Enter. This action will start a Jupyter server and open a new notebook.

### Step 4: Select the Correct Python Interpreter
Ensure that the notebook is using the correct Python interpreter (the one from your virtual environment). You can select the interpreter from the top-right corner of the notebook interface in VSCode.

