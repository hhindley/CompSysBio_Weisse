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

## 🌐 Option 1: Google Colab (No Local Installation Required)

#### 📚 Tutorial Notebooks
Click on any of the following links to open the tutorials directly in Google Colab:

| Tutorial | Description | Launch |
|----------|-------------|---------|
| **Competition Tutorial** | Learn about cellular competition dynamics | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/tutorials/competition_tutorial.ipynb) |
| **Growth Model with Antibiotics** | Explore bacterial growth under antibiotic stress | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/tutorials/growth_model_inc_abx_tutorial.ipynb) |
| **Growth Model ODE** | Mathematical modeling with differential equations | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/tutorials/growth_model_ode_tutorial.ipynb) |

#### ✅ Solution Notebooks
Access the completed solutions for reference:

| Solution | Launch |
|----------|---------|
| **Competition Tutorial (Complete)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/solutions/competition_tutorial_complete.ipynb) |
| **Growth Model with Antibiotics (Complete)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/solutions/growth_model_inc_abx_tutorial_complete.ipynb) |
| **Growth Model ODE (Complete)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hhindley/CompSysBio_Weisse/blob/main/solutions/growth_model_ode_tutorial_complete.ipynb) |

> **💡 Note:** When using Google Colab, all required packages are installed automatically in the cloud environment.

---

## Local Setup (Required for Options 2 & 3)

If you're planning to use **Option 2 (Jupyter)** or **Option 3 (VS Code/IDE)**, start with these shared setup steps:

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

> **Prerequisites:** Complete the [Local Setup](#-local-setup-required-for-options-2--3) steps above first.

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

> **Prerequisites:** Complete the [Local Setup](#-local-setup-required-for-options-2--3) steps above first.

#### Additional Steps:

4. **Open in your IDE:**
   ```bash
   code .  # For VS Code
   ```
   
   Or open the project folder in your preferred IDE and start working with the notebooks in the `tutorials/` directory.

---

