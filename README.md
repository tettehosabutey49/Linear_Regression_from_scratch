# Linear Regression Tutorial

This project explores different regression techniques and compares how well they fit a dataset using Python and scikit-learn.

The notebook includes:
- **Linear Regression**
- **RANSAC Regression** (robust to outliers)
- **Polynomial Regression** with:
  - Linear (degree 1)
  - Quadratic (degree 2)
  - Cubic (degree 3)

Visualizations are included to show the differences in fit and model behavior.

---

## 📁 Project Structure

linearregressiontutorial/
│
├── src/
│ └── linearregressiontutorial/
│ └── ... (your Python modules, if any)
│
├── notebooks/
│ └── linear_regression_analysis.ipynb
│
├── pyproject.toml
├── README.md
└── ...

yaml
Copy code

---

## 🛠 Requirements

This project uses [Poetry](https://python-poetry.org/) for dependency and environment management.

### Install Poetry (if you haven’t already)

```bash
curl -sSL https://install.python-poetry.org | python3 -
⚙️ Installation
After cloning the repository:

bash
Copy code
cd linearregressiontutorial
poetry install
🚀 Running the Notebook
To open the notebook:

bash
Copy code
poetry run jupyter notebook
Optional (recommended): To make the Poetry environment available as a Jupyter kernel:

bash
Copy code
poetry run python -m ipykernel install --user --name=linearregressiontutorial
Then select linearregressiontutorial as the kernel inside Jupyter.

🎯 Objectives
Understand how different regression models behave.

See the effect of outliers using RANSAC.

Compare linear vs. higher-degree polynomial fits.

Visualize regression performance on 2D data.

📦 Dependencies
All dependencies are managed via Poetry in pyproject.toml, including:

scikit-learn

matplotlib

pandas

numpy

mlxtend

ipykernel

👤 Author
Emmanuel Osabutey
📧 tettehosabutey49@gmail.com

📝 License
This project is open-source and available under the MIT License.