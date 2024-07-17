# Mikio Kaji's Data Ingestion Project

This project focuses on developing a batch data ingest process to load ODI match results and ball-by-ball innings data into a SQLite database. The data is sourced from [cricsheet.org](https://cricsheet.org/) and includes a variety of cricket match information.

## Getting Started

To get started with this project, follow these instructions:

### Prerequisites

Ensure that you have Python installed on your machine. You can download Python from [python.org](https://www.python.org/).

Additionally, you will need to install the required Python packages. These can be found in the `requirements.txt` file included in this project.

### Installation

1. Download and extract the .zip file containing the project files.
2. Open a terminal or command prompt in the extracted project directory.
3. Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```

To run the project:

1. Open the cricket_data_ingestion_project.ipynb Jupyter notebook in a Jupyter environment. If you don't have Jupyter installed, you can install it using the following command:
```bash
pip install jupyterlab
```

2. Run the Jupyter notebook server using the following command:
```bash
jupyter notebook
```

3. In the Jupyter interface, navigate to and open the cricket_data_ingestion_project.ipynb notebook. Run the cells in order to execute the project.

### Expected Output

The output of the project will be displayed within the Jupyter notebook and will include the results of the data ingest process and the answers to the SQL queries specified in the project.