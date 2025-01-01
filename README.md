# IPL Data Analysis Project (2008-2017)

## Overview
This project analyzes Indian Premier League (IPL) cricket data from 2008 to 2017 using AWS, Databricks, and PySpark. The analysis provides insights into match statistics, team performance, and player achievements throughout the IPL seasons.

## Technologies Used
- AWS (Amazon Web Services)
- Databricks
- PySpark
- Python
- Jupyter Notebook

## Dataset
The dataset used in this analysis is sourced from [data.world](https://data.world/raghu543/ipl-data-till-2017) and includes comprehensive IPL match data from 2008 to 2017.

## Project Structure
```
ipl-data-analysis/
├── notebooks/
│   └── IPL-Database-Analysis.ipynb
├── data/
│   └── raw/
├── README.md
└── requirements.txt
```

## Setup Instructions
1. Clone the repository:
```bash
git clone https://github.com/[your-username]/ipl-data-analysis.git
cd ipl-data-analysis
```

2. Set up your environment:
- Create a Databricks workspace
- Configure AWS credentials
- Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Data Processing:
- Upload the IPL dataset to your preferred storage (AWS S3 or Databricks FileStore)
- Update the data path in the notebook accordingly

## Analysis Features
- Match statistics analysis
- Team performance metrics
- Player statistics
- Season-wise analysis
- Trend analysis across seasons

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Dataset provided by data.world
- IPL for the fascinating cricket data
