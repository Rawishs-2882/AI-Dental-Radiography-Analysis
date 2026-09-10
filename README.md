<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:F8BBD0,50:CE93D8,100:B39DDB&height=180&section=header&text=Dental%20Radiography%20Analysis&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=ANN%20%2B%20Association%20Rule%20Mining&descAlignY=58&descSize=15)

</div>

## Overview

An AI powered system for analyzing dental radiographs, combining an Artificial Neural Network for classification with association rule mining to surface relationships between findings, evaluated using support, confidence and lift.

## Key Features

### ANN based radiograph classification
A neural network trained on radiograph data identifies relevant dental findings from each image.

### Association rule mining
Beyond classification, the system mines relationships between findings, surfacing patterns that a single label per image would miss.

### Support, confidence and lift metrics
Discovered rules are evaluated using standard association rule metrics, so the most meaningful relationships can be prioritized over noise.


## Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=tensorflow,opencv,python" />
</div>

TensorFlow and Keras for the ANN classifier, OpenCV for radiograph preprocessing, and mlxtend for association rule mining.

## How It Works

Radiographs are preprocessed and passed through the ANN classifier to produce a set of findings per image. Findings across the dataset are then mined for association rules, with support, confidence and lift computed for each rule to rank their significance.

## Setup and Run

1. Install dependencies with `pip install -r requirements.txt`.
2. Place radiograph images and labels in `/data`.
3. Run `python train_classifier.py` to train the ANN.
4. Run `python mine_rules.py` to generate and rank association rules from the classifier's findings.

## Roadmap

- Expand the finding label set
- Add a visualization tool for the mined rules
- Validate the classifier against a larger external dataset

## Status

> **Status:** This repository was scaffolded from the project description on the author's resume. Source code is being migrated and added here in stages. Reach out using the contact links below if you would like early access to the implementation.

## Let's Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rawish0922@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rawishsarfraz)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rawishs-2882)
[![Phone](https://img.shields.io/badge/Call-+92--332--8747138-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+923328747138)

</div>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:B39DDB,50:CE93D8,100:F8BBD0&height=80&section=footer)

</div>
