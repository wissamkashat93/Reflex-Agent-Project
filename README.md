### Reflex Agent Project README

This README file provides an overview of the Reflex Agent project, outlining the steps involved in setting up and running the project.

---

### Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Getting Started](#getting-started)
4. [Running the Reflex Agent](#running-the-reflex-agent)
5. [Project Structure](#project-structure)
6. [Libraries Used](#libraries-used)
7. [Contact Information](#contact-information)

---

### Project Overview
The Reflex Agent project involves the implementation and analysis of a simple reflex agent within a vacuum world environment. This agent selects actions based on the current percept, ignoring the rest of the percept history. The project is designed to demonstrate the fundamentals of condition-action rules and their applications in artificial intelligence.

---

### Installation
To set up the environment for the Reflex Agent project, you need to install several libraries. The necessary installations can be done via `pip`. Below is the command to install all required libraries:

```bash
pip install numpy ipythonblocks ipywidgets matplotlib networkx pillow sortedcontainers qpsolvers
```

If you are using a Jupyter Notebook, you can install these libraries directly from a cell by prefixing the command with `!`:

```python
!pip install numpy ipythonblocks ipywidgets matplotlib networkx pillow sortedcontainers qpsolvers
```

---

### Getting Started
1. **Clone the Repository**: Clone the project repository to your local machine using:
    ```bash
    git clone <repository_url>
    ```
2. **Navigate to the Project Directory**: 
    ```bash
    cd <project_directory>
    ```
3. **Install Required Libraries**: Ensure all the required libraries are installed as per the [Installation](#installation) section.

---

### Running the Reflex Agent
1. **Load the Notebook**: Open the `Reflex_Agent.ipynb` notebook in Jupyter or Google Colab.
2. **Run All Cells**: Execute all the cells in the notebook sequentially. This includes cells for importing necessary libraries, defining utility functions, and implementing the agent.
3. **Execute the Environment**: Follow the steps provided in the notebook to initialize and run the vacuum environment with the reflex agent.

---

### Project Structure
- `Reflex_Agent.ipynb`: The main Jupyter notebook containing all the code for the project.
- `Utils.py`: Contains utility functions used throughout the project.
- `Agents.py`: Contains agent definitions and programs.

---

### Libraries Used
The following libraries are used in the Reflex Agent project:
- **copy**: For creating shallow and deep copies of objects.
- **itertools**: For efficient looping and creating iterators.
- **random**: For generating random numbers and making random choices.
- **collections**: For specialized container datatypes.
- **numpy**: For numerical operations.
- **statistics**: For statistical functions.
- **ipythonblocks**: For creating colored block grids in Jupyter Notebooks.
- **IPython.display**: For displaying HTML and controlling notebook output.
- **time**: For time-related functions.
- **bisect**: For array bisection algorithms.
- **functools**: For higher-order functions and operations on callable objects.
- **heapq**: For heap queue algorithms.
- **operator**: For functional-style operations on built-in operators.
- **os.path**: For common pathname manipulations.
- **ipywidgets**: For interactive widgets in Jupyter Notebooks.
- **matplotlib**: For plotting and visualization.
- **networkx**: For creating and analyzing complex networks.
- **PIL (pillow)**: For image processing.
- **re**: For regular expression operations.
- **string**: For common string operations.
- **sortedcontainers**: For sorted collections.
- **qpsolvers**: For quadratic programming solvers.
