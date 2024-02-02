<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>AWS-SageMaker Train_deployment_project</h1>


<p align="center">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
</p>
<img src="https://img.shields.io/github/license/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running AWS-Project](#-running-AWS-Project)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The roadmap delineated encompasses the structured progression of a machine learning project executed on AWS SageMaker. The journey begins with setting up the SageMaker environment and spans to deploying a  machine learning model. 
The tasks cover a spectrum of essential steps, including data preparation, model creation, script finalization, training, validation, and deployment, showcasing a systematic approach to machine learning projects.

---


## 📂 Repository Structure

```sh
└── Pre_trainmodel_image_analysis/
    ├── README.md
    └── Tensorflow Model in AWS.ipynb
    └── Tensorflow Model in AWS.html
    └── train.py
```
```sh
└── Deploy a Sentiment Analsyis Model/
    ├── README.md
    └── sagemaker project.ipynb
    └── index.html
    └── predict.py
    └── report.html
    └── train.py
```


---

## ⚙️ Modules

Project Structure
Prepare custom script for Amazon Sagemaker,
Train a pytorch an tenserflow model using Amazon Sagemaker,
Deploy a pytorch tenserflow model using Amazon Sagemaker.



| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [Sentiment Analsyis Model](https://github.com/QsingularityAi/AWS-Project/blob/main/sagemaker project.ipynb) | HTTPStatus Exception: 401 |

</details>

| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [Pre_trainmodel_image_analysis]((https://github.com/QsingularityAi/AWS-Project/blob/main/Tensorflow Model in AWS.ipynb) | HTTPStatus Exception: 401 |

</details>

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ pytorch`

`- ℹ️ numpy`

`- ℹ️ pandas`

`- ℹ️ sagemaker`

### 🔧 Installation

1. Clone the AWS-Project repository:
```sh
git clone https://github.com/QsingularityAi/AWS-Project
```

2. Change to the project directory:
```sh
cd AWS-Project
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🤖 Running AWS-Project

```sh
jupyter nbconvert --execute notebook.ipynb
```

### 🧪 Tests
```sh
pytest notebook_test.py
```

---


## 🛣 Roadmap
The hands on project on Using TensorFlow with Amazon Sagemaker is divided into following tasks:

> - [X] `ℹ️  Task 1: Introduction and Notebook Instance: Create a Notebook instance in Sagemaker.`
> - [X] `ℹ️  Task 2: Task 1: Download the Data:
Upload a starter notebook to the Sagemaker Notebook instance,.`
> - [X] `ℹ️  Task 3: Task 1: Prepare the Dataset:Create Training and Validation sets.`
> - [X] `ℹ️  Task 4: Create the Model: Create a custom training script.`
> - [X] `ℹ️  Task 5: Data Generators: In the custom training script, write a function to create data generators for training and validation sets.`
> - [X] `ℹ️  Task 6: Arguments: Write argument parser to parse the arguments sent by Sagemaker to the custom script.`
> - [X] `ℹ️  Task 7: Finalizing the Training Script: Create a model instance, Instantiate training and validation generators,Train the model,Export the trained model,`
> - [X] `ℹ️  Task 8:  Upload Dataset to S3: The dataset prepared in Task 3 is uploaded to S3.`
> - [X] `ℹ️  Task 9: pytorch Estimator: Create a pytorch anf tensorflow Estimator, Specify the entry point, execution role and other necessary arguments,
Using the fit method on the Estimator to launch the training job,`
> - [X] `ℹ️  Task 10: Deploy the Model: Deploy the trained model artifact using the Estimator.`
> - [X] `ℹ️  Task 11: Inference and Deleting Endpoint: Write a function to preprocess input and get predictions from the deployed model,
Deleting the deployed model endpoint.`

---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  LICENSE-TYPE` License. See the [LICENSE-Type](LICENSE) file for additional info.

---

## 👏 Acknowledgments

`- ℹ️ List any resources, contributors, inspiration, etc.`

[↑ Return](#Top)

---

