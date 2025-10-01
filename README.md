# CompSysBio2025: Modeling adaptative cellular growth

This repository contains tutorial notebooks for modeling adaptive cellular growth. You can run these tutorials in three different ways depending on your setup and preferences.

## Getting Started

Choose one of the following options based on your preferred environment:

| Option | Description | Best For |
|--------|-------------|----------|
| 🌐 **Google Colab** | No installation required | Users without Python installed |
| 📓 **Jupyter Notebook/Lab** | Must have Python installed locally | Users comfortable with Jupyter |
| 💻 **VS Code/IDE** | Must have Python installed locally | Users with preferred IDE setup |

---

## 🌐 Option 1: Google Colab (no local installation required)

#### 📚 Tutorial Notebooks
Click on any of the following links to open the tutorials directly in Google Colab (right click to open in a new tab):

| Tutorial | Launch |
|----------|---------|
| **Growth Model ODE**  | <a href="https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/tutorials/growth_model_ode_tutorial.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| **Growth Model with Antibiotics** | <a href="https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/tutorials/growth_model_inc_abx_tutorial.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| **Competition Tutorial** | <a href="https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/tutorials/competition_tutorial.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

#### ✅ Solution Notebooks
Access the completed solutions for reference:

| Solution | Launch |
|----------|---------|
| **Growth Model ODE (Complete)** | <a href="https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/solutions/growth_model_ode_tutorial_complete.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| **Growth Model with Antibiotics (Complete)** | <a href="https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/solutions/growth_model_inc_abx_tutorial_complete.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |
| **Competition Tutorial (Complete)** | <a href="https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/solutions/competition_tutorial_complete.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> |

> **💡 Note:** When using Google Colab, all required packages are installed automatically in the cloud environment.

---

## Local Setup (Required for Options 2 & 3)

If you're planning to use **Option 2 (Jupyter)** or **Option 3 (VS Code/IDE)**, start with these shared setup steps to clone this repo and create a virtual environment in Python:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hhindley/CompSysBio_Weisse.git
   cd CompSysBio_Weisse
   ```

2. **Create and activate virtual environment:**
   ```bash
   python3 -m venv venv
   ```
   
   **macOS/Linux:**
   ```bash
   source venv/bin/activate
   ```
   
   **Windows:**
   ```bash
   venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

*Once you've completed these steps, proceed to your preferred option below.*

---

## 📓 Option 2: Jupyter Notebook/Lab

> **Prerequisites:** Have Python3 downloaded and complete the [Local Setup](#local-setup-required-for-options-2--3) steps above first.

#### Additional Steps:

4. **Install Jupyter (if not already installed):**
   ```bash
   pip install jupyter
   ```

5. **Launch Jupyter:**
   ```bash
   jupyter notebook  # Classic interface
   # OR
   jupyter lab      # Modern interface
   ```

6. **Navigate to `tutorials/` folder** and open any tutorial notebook.

---

## 💻 Option 3: VS Code or Other IDE

> **Prerequisites:** Have Python3 downloaded and complete the [Local Setup](#local-setup-required-for-options-2--3) steps above first.

#### Additional Steps:

4. **Open in your IDE:**
   ```bash
   code .  # For VS Code
   ```
   
   Or open the project folder in your preferred IDE and start working with the notebooks in the `tutorials/` directory.

---

