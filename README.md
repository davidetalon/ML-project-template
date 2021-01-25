# ML-project-template
A simple and flexible template to structure a Machine Learning project.
```
  pytorch-template/
  │
  ├── data/
  │   ├── processed/            <- Processed data via data scripts
  │   └── raw/                  <- Data as downloaded from the source
  │       └── README.md         <- Data details, e.g., URL, date of download, name, etc.
  │
  ├── saved/
  │   ├── log/                  <- Log information
  │   └── models/               <- Checkpoints and final models
  │
  ├── src/
  │   ├── logger/               <- Source code for logging
  │   ├── model/                <- Source code for your own model
  │   └── scripts/
  │   │    ├── data/            <- scripts and programs to process data
  │   │    ├── visualization/   <- Scripts for visualisation of your outputs
  │   │    └── test/            <- The results of your analysis
  │   │
  │   └── utils/                <- Helpers and utilities used
  │
  ├── README.md                 <- description and how to use the project
  ├── requirements.txt          <- requirements for the dedicated environmnet, e.g. pip freeze > requirements.txt
  ├── LICENSE                   <- license details
  └── .gitignore                

# TODO
- [] Implementation of a logger
- [] Similar to rails to create the project template and associated environment: `project new <project-new>`
- [] Docker containers for servers?

# License
This project is licensed under the MIT License. See LICENSE for more details

# Acknowledgements
Thanks to [Cookiecutter Data Science project ](http://drivendata.github.io/cookiecutter-data-science/) and [Pytorch project template](https://github.com/victoresque/pytorch-template)