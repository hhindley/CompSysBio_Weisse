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

## 📓 Option 2: Jupyter Notebook/Lab

#### Setup Steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hhindley/CompSysBio_Weisse.git
   cd CompSysBio_Weisse
   ```

2. **Create and activate virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # macOS/Linux
   # OR
   venv\Scripts\activate     # Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   pip install jupyter  # if not already installed on your machine
   ```

4. **Launch Jupyter:**
   ```bash
   jupyter notebook  # Classic interface
   # OR
   jupyter lab      # Modern interface
   ```

5. **Navigate to `tutorials/` folder** and open any tutorial notebook.

---

## 💻 Option 3: VS Code or Other IDE

#### Setup Steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hhindley/CompSysBio_Weisse.git
   cd CompSysBio_Weisse
   ```

2. **Create virtual environment:**
   ```bash
   python3 -m venv venv
   ```

3. **Activate virtual environment:**
   
   **macOS/Linux:**
   ```bash
   source venv/bin/activate
   ```
   
   **Windows:**
   ```bash
   venv\Scripts\activate
   ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Open in your IDE:**
   ```bash
   code .  # For VS Code
   ```
   
   Or open the project folder in your preferred IDE and start working with the notebooks in the `tutorials/` directory.

---

## 📁 Repository Structure

```
CompSysBio_Weisse/
├── tutorials/           # Interactive tutorial notebooks
├── solutions/          # Complete solution notebooks
├── imgs/              # Images and figures
├── requirements.txt   # Python dependencies
└── README.md         # This file
```

