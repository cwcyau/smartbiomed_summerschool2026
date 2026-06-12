
# SmartBiomed Summer School 2026 - Machine Learning

## Table of Contents

- [Instructors](#instructors)
- [Course Learning Outcomes](#course-learning-outcomes)
  - [Supervised Learning](#supervised-learning)
  - [Unsupervised Learning](#unsupervised-learning)
  - [Foundation Models](#foundation-models)
  - [General Skills Across the Course](#general-skills-across-the-course)
- [Coding and Software Requirements](#coding-and-software-requirements)
  - [Slack](#slack)
  - [Google Colab](#google-colab)
  - [Python Environment](#python-environment)
- [Timetable](#timetable)
- [Practical Materials](#practical-materials)
  - [Supervised Learning Materials](#supervised-learning-materials)
  - [Unsupervised Learning Materials](#unsupervised-learning-materials)
- [Additional Reading Materials](#additional-reading-materials)

## Instructors

- Professor Christopher Yau (Lead)
- Dr Hanwen Xing
- Moritz Gogl

## Course Learning Outcomes

This course provides an introduction to modern machine learning methods for high-dimensional biological and multi-omics data, spanning supervised learning, unsupervised representation learning and emerging foundation models. Participants will learn how to formulate predictive modelling problems, build and evaluate machine learning workflows, and interpret model outputs within a biological context. Through a combination of lectures and hands-on practical sessions, attendees will gain experience working with real omics datasets, implementing neural networks and variational autoencoders, and exploring state-of-the-art approaches based on self-supervised and foundation model paradigms. By the end of the course, participants will be equipped to select appropriate machine learning methodologies for a range of biomedical research questions, critically assess model performance and generalisability, and confidently engage with rapidly evolving AI technologies for future multi-omics analyses.

### Supervised Learning

By the end of this section participants will be able to:

- Describe the challenges and properties of high-dimensional omics datasets and how supervised models can address these issues.
- Pre-process omics data for predictive tasks, including managing sparsity, scaling and feature selection.
- Build, tune and evaluate supervised learning models using appropriate regularisation and model validation strategies.
- Interpret model performance and assess generalisability within a biological context.

### Unsupervised Learning

Participants will be able to:

- Explain the aims of unsupervised learning in omics, including structure discovery, denoising and latent variable modelling.
- Describe VAE architecture, latent space representations and the roles of reconstruction and KL-divergence losses.
- Build and train a simple variational autoencoder and utilise its latent space for interpretation or downstream analyses.
- Compare VAEs to traditional unsupervised approaches such as PCA, clustering and manifold learning techniques.

### Foundation Models

Participants will be able to:

- Explain the concept and motivation behind foundation models and how they differ from task-specific machine learning methods.
- Describe the structure and functioning of Large Language Models and how they may be adapted for biological data.
- Summarise current state-of-the-art applications of foundation models in omics, including multimodal integration, representation learning and generative modelling.
- Critically evaluate the opportunities, limitations and ethical considerations associated with applying foundation models to biological research.

### General Skills Across the Course

Participants will be able to:

- Implement end-to-end machine learning workflows for high-dimensional biological datasets.
- Apply best practices in reproducibility, model evaluation and clear scientific communication.
- Select appropriate machine learning approaches for different omics questions and data modalities.
- Confidently navigate emerging AI methodologies and assess their relevance to future multi-omics analyses.

## Coding and Software Requirements

It will be assumed that you are able to program in Python. We are unable to support other languages during the course.

### Slack

On-course communications will be through a dedicated [Slack](https://slack.com/intl/en-gb) channel. Please install and set up Slack on your device prior to the summer school. Details of the Slack channel will be given on arrival.

### Google Colab

We have created Python notebooks that can be edited and run in [Google Colab](https://colab.research.google.com/). You will need a valid Google account to use Colab.

### Python Environment

Alternatively, if you prefer to work locally, please install [Anaconda](https://www.anaconda.com/download) (or another Python environment) and ensure the following packages are available before the course:

- torch (>=2.0)
- pandas
- numpy
- scikit-learn
- matplotlib
- umap-learn

You can install these packages using:

```bash
pip install torch pandas numpy scikit-learn matplotlib umap-learn
```

To verify your installation, run the package-check notebook provided in the course materials. If all required packages are installed correctly, the notebook will report that your environment is ready.

## Timetable

| Day | Time | Instructor | Session |
|-----|------|---------|---------|
| 3 | 09:00–10:20 | Yau |  Introduction to Omics  | 
| 3 | 10:40–12:00 | Yau | Supervised Learning | 
| 3 | 13:00–13:30 | Gogl | Practical Lecture: Introduction to Omics-based Prediction | 
| 3 | 13:30–16:00 | All | Practical Exercises: Omics-based Prediction |
| 4 | 09:00–09:30 | Yau | Introduction to Unsupervised Learning for Omics | 
| 4 | 09:40–10:40 | Yau | Bayesian Latent Variable Modelling | 
| 4 | 11:00–12:00 | Yau | Variational inference and foundations of VAEs |
| 4 | 13:00–14:00 | Xing | Practical Lectures: VAEs for multi-omics |
| 4 | 14:00–16:00 | All | Practical Exercises: VAEs for multi-omics |
| 5 | 09:00–10:00 | Yau | Introduction to Self-Supervised Learning  |
| 5 | 10:15–11:00 | Xing | Case Study: MIND |
| 5 | 11:15–12:00 | Gogl | Case Study: Pathology Reports and TCGA |

## Practical Materials

### Supervised Learning Materials

- Omics-based prediction notebook
- Feature engineering exercises
- Multimodal modelling exercises

### Unsupervised Learning Materials

- Variational autoencoder notebook
- Latent space visualisation exercises
- Representation learning exercises
- Multimodal extension exercises

## Additional Reading Materials

Reading materials, papers and notebooks will be added throughout the course.
