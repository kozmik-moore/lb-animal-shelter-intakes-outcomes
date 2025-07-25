<!-- omit from toc -->
# Long Beach Animal Shelter Intakes and Outcomes

<!-- omit from toc -->
## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Data Source(s)](#data-sources)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Install dependencies](#install-dependencies)
- [Usage](#usage)
  - [Run a Jupyter Notebook](#run-a-jupyter-notebook)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This project performs exploratory data analysis on a dataset of animal shelter intakes and outcomes using the Python libraries `pandas` and `seaborn`. The goal is to uncover trends, detect anomalies, and visualize key insights to support data-driven decision-making for various city shareholders including shelter managers, animal welfare advocates, government officials, local citizens, and internal analysts.

This is a portfolio project created to demonstrate my proficiency in data analysis, data cleaning, and data visualization using Python. It highlights my ability to work with real-world datasets, derive meaningful insights, and communicate results clearly through code and visualizations.

## Project Structure

```
└── 📁lb-animal-shelter-intakes-outcomes
    └── 📁assets
    └── 📁code
        └── 📁utilities
            ├── __init__.py
            ├── config.py
        ├── notebook.ipynb
    └── 📁data
        └── 📁variable counts
            ├── animal_type.csv
            ├── crossing.csv
            ├── date_of_birth.csv
            ├── geopoint.csv
            ├── intake_condition.csv
            ├── intake_date.csv
            ├── intake_duration.csv
            ├── intake_is_dead.csv
            ├── intake_subtype.csv
            ├── intake_type.csv
            ├── is_current_month.csv
            ├── jurisdiction.csv
            ├── latitude.csv
            ├── longitude.csv
            ├── outcome_date.csv
            ├── outcome_is_dead.csv
            ├── outcome_subtype.csv
            ├── outcome_type.csv
            ├── primary_color.csv
            ├── reason_for_intake.csv
            ├── secondary_color.csv
            ├── sex.csv
            ├── was_outcome_alive.csv
        ├── processed_animal_names.csv
        ├── processed_crossings_unique.csv
        ├── processed_data.csv
        ├── processed_dead_by_name.csv
        ├── raw_animal_names.csv
        ├── raw_crossing_wo_zip.csv
        ├── raw_data.csv
        ├── raw_number_names.csv
    └── 📁products
        └── 📁images
        ├── report.md
    ├── .gitignore
    ├── LICENSE
    ├── README.md
    └── requirements.txt
```

## Data Source(s)

- **File**: [`raw_data.csv`](./data/raw_data.csv)
- **Source**: [Long Beach Data Portal](https://data.longbeach.gov/explore/dataset/animal-shelter-intakes-and-outcomes/)
- **Description**: Contains intake and outcome data for Long Beach, CA, starting in 2017.

## Installation

### Prerequisites

- Python 3.11+
- pip (Python package manager)

### Install dependencies

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
pip install -r requirements.txt
```

Clone the repository and install required packages:

```bash
git clone https://github.com/kozmik-moore/lb-animal-shelter-intakes-outcomes.git
cd lb-animal-shelter-intakes-outcomes
pip install -r requirements.txt
```

## Usage

### Run a Jupyter Notebook

Start the Jupyter server:

```bash
jupyter notebook
```

Open and run notebooks from the [`/code`](/code/) directory to explore data and generate visualizations.

## Conclusions

See full visual report in [`/products/report.md`](/products/report.md).

## Technologies Used

- Python 3.11+
- [pandas](https://pandas.pydata.org/) – for data manipulation
- [seaborn](https://seaborn.pydata.org/) – for statistical data visualization
- [matplotlib](https://matplotlib.org/) – for low-level plotting
- [Jupyter Notebook](https://jupyter.org/) – for interactive analysis

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m "Add feature"`)
5. Push to your branch (`git push origin feature-branch`)
6. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Kozmik Moore\
Email: koz.moore@gmail.com\
GitHub: [@kozmik-moore](https://github.com/kozmik-moore)\
LinkedIn: [@kozmik-moore](www.linkedin.com/in/kozmik-moore)
