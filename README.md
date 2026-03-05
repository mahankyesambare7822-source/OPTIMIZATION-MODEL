# OPTIMIZATION-MODEL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MAHANK YESAMBARE

*INTERN ID*: CTIS6742

*DOMAIN*: DATA SCIENCE

*MENTOR*: NEELA SANTOSH

#DISCRIPTION#,

In this project, an optimization model was developed to solve a business production planning problem using Python and linear programming techniques. The main objective of the project was to determine the optimal number of products that a company should manufacture in order to maximize profit while considering the limitations of available machine resources. To implement this optimization model, several tools, libraries, and software environments were used.

The primary programming language used in this project is Python. Python is one of the most widely used programming languages in the fields of data science, machine learning, and optimization because of its simplicity, readability, and powerful libraries. Python allows developers to implement mathematical models and algorithms efficiently without requiring complex syntax. Its extensive ecosystem of libraries makes it a preferred language for solving analytical and computational problems.

To write and execute the Python code, the Visual Studio Code (VS Code) integrated development environment (IDE) was used. VS Code is a lightweight yet powerful code editor developed by Microsoft. It supports multiple programming languages and provides useful features such as syntax highlighting, debugging tools, integrated terminal, and extensions. For this project, the Python extension and the Jupyter extension in VS Code were installed. These extensions allow users to write and run Python code in an interactive notebook format, which makes it easier to organize code, explanations, and results in a single document.

The project was implemented in a Jupyter Notebook (.ipynb file) created inside VS Code. Jupyter notebooks are widely used in data science and research because they allow the combination of code, text explanations, and outputs in a single interactive environment. Each notebook contains multiple cells that can be executed individually. Code cells are used to run Python programs, while markdown cells are used to write explanations, documentation, and analysis. This structure makes it easier to present the problem setup, model implementation, and results in a clear and organized manner.

The optimization problem itself was solved using the PuLP library, which is a Python library specifically designed for linear programming. PuLP allows users to define optimization problems by specifying decision variables, objective functions, and constraints. It provides a simple interface for building mathematical models and solving them using built-in solvers. In this project, PuLP was installed using the Python package manager pip through the command pip install pulp. Once installed, the library was imported into the Python environment using the import pulp statement.

PuLP internally uses a solver to compute the optimal solution of the linear programming model. The solver analyzes the objective function and constraints to determine the best possible values for the decision variables. In this project, the solver evaluated different combinations of product quantities and identified the optimal production plan that maximizes profit while respecting machine hour limitations.

The optimization model created in this project consists of three key components: decision variables, objective function, and constraints. Decision variables represent the number of units of each product to be produced. The objective function defines the goal of the model, which in this case is maximizing profit. The constraints represent the real-world limitations of machine working hours available for production.

After defining these components, the PuLP solver calculates the optimal solution automatically. The results of the model show the best production strategy and the maximum achievable profit under the given conditions. The output is displayed directly in the notebook, allowing users to interpret the results easily.

Overall, the combination of Python, VS Code, Jupyter Notebook, and the PuLP optimization library provides a powerful environment for building and solving optimization problems. These tools are widely used in industries such as manufacturing, logistics, finance, and supply chain management to improve efficiency and support better decision-making. This project demonstrates how modern programming tools can be used to implement mathematical optimization models in a practical and user-friendly way.
