# Research Project Template

This template follows responsible practices for research projects in climate and weather using Python or R as a programming language. It is meant to help users incorporate good practices one by one by organising code, analysis, figures and documentation. 

[Copier](https://copier.readthedocs.io/en/latest/) is required to use this template. Copier is an open-source tool that hydrates projects from templates. This template was developed using Copier v9.15.0 and older versions haven't been tested. 

## Getting started

### On gadi

1. Load the copier module:

```bash
module use /g/data/gb02/public/modules
module load copier
```

2. Copy the template:

```bash
copier copy --trust gh:21centuryweather/research-project-template .
```

And answer the questions. Depending on the answers, the project using Python will look something like this:

```bash
{{project_name}}/
├── analysis
│   ├── example.ipynb
│   └── figures
├── .copier-answers.yml
├── data -> /g/data/{{nci_project}}/$USER/{{project_name}}/data
│   ├── derived
│   ├── raw
│   │   └── DO_NOT_EDIT
│   └── temp -> /scratch/{{nci_project}}/$USER/{{project_name}}/data/temp
├── .envrc
├── .git
├── .gitignore
├── README.md
├── requirements.txt
├── scripts/
├── src
│   ├── __init__.py
│   └── sample_fun.py
└── tests
    └── test_sample_fun.py
```

### Locally on your machine

The template is developed specifically to work on the gadi file systems. It's still possible to use it locally but it will have some limitations. 

1. Install copier following the [instructions in their documentation](https://copier.readthedocs.io/en/latest/).

2. Copy the template. 
    * when asked "Are you creating this project in your home directory on gadi?" Answer No or False. 

## Licence 

The content of this repository is shared under a [CC BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/). You can share and adapt the template for non-commercial purposes, provided you give appropriate credit and use the same licence. 

------------------------------------
This is a ![](/img/Logo_black_text.png) project.






