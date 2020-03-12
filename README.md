# Exam Review 2020

A workspace for solving selected Python coding questions from this [Final Exam](EXAM.pdf).

## Instructions

Review the final exam PDF. When you reach question _____________, ____, and ___, use the data provided in the "data" directory to answer each of the questions about that dataset.

Write Python code to process the data provided in each script in the app directory.

Each file contains commented-out questions to guide you.

When you solve one or more questions, make a commit to save your work, and then push back up to GitHub at least once before you're done.

## Setup

First, [fork this starter repo](__________) under your own control, then clone or download your repo onto your local computer. Make sure to navigate there from the desktop:

```sh
cd exam-solutions-starter-py/
```

It is not necessary to leverage modules or third-party packages, but it may be helpful to do so. If you don't use any packages, you can use the Anaconda "base" environment with Python 3.7, otherwise setup a new virtual environment and install any packages you may want to use:

```sh
conda create -n exam-env python=3.7
conda activate exam-env

pip install pandas # for example, only if you want to use the pandas package
```

## Usage

Process library data:

```sh
python data/library.py
```


Process rideshare data:

```sh
python data/rideshare.py
```

Process social media data:

```sh
python data/social.py
```
