# Flask Without Deploy

This repository contains two projects: **Iris** and **Titanic**. Each project is implemented using Flask and includes Jupyter Notebooks for data analysis.

## Projects Overview

### 1. Iris

- **Description**:  Flask application that analyzes the Iris dataset.- **Contents**:
  - `app.py`: ain Flask application file.  - `iris_analysis.ipynb`: upyter Notebook containing data analysis of the Iris dataset.  - `templates/`: TML templates for the web application.  - `static/`: tatic files (CSS, JS, images).
### 2. Titanic

- **Description**:  Flask application that analyzes the Titanic dataset.- **Contents**:
  - `app.py`: ain Flask application file.  - `titanic_analysis.ipynb`: upyter Notebook containing data analysis of the Titanic dataset.  - `templates/`: TML templates for the web application.  - `static/`: tatic files (CSS, JS, images).
## Getting Started

To run either of the Flask applications locally:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Adarsh-fg/Flask.WIthout.Deploy.git
   cd Flask.WIthout.Deploy
   ```

2. **Navigate to the project directory**:

   For Iris:

   ```bash
   cd Iris
   ```

   For Titanic:

   ```bash
   cd Titanic
   ```

3. **Set up a virtual environment**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

4. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Flask application**:

   ```bash
   python app.py
   ```

6. **Access the application**:

   Open your browser and navigate to `http://localhost:5000`.

## Jupyter Notebooks

he Jupyter Notebooks (`.ipynb` files) in each project directory provide detailed data analysis.o view or edit them:
1. **Ensure Jupyter is installed**:

   If not installed, you can add it to your environment:

   ```bash
   pip install jupyter
   ```

2. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

3. **Open the respective notebook**:

   Navigate to `iris_analysis.ipynb` or `titanic_analysis.ipynb` in the Jupyter interface.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
