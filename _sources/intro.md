# Welcome to Earth Data Science and Machine Learning Course Series

This is the online home for the summer 2025 courses:
- *Computing and Research Methods for Climate Data Science* (CLMT5405)
- *Machine Learning for Climate Science and Environmental Sustainability*

## History and Origins
Most of the content for CLMT5405, derives from pervious versions of this course, which can be found in [this online book](https://earth-env-data-science.github.io/) from 2021 by Ryan Abernathey. A more recent update can be found in [repo](https://github.com/yutianwuldeo/GR6901) from 2024 by Yutian Wu.


## Motivation and Scope

Computing has become an indispensable tool for nearly all Earth and Environmental Scientists, but it doesn't often appear in our curriculums.
This material focuses on _data analysis_, a subset of computing in which the data already exist, e.g.from observations or from the output of a simulation, but have to be transformed into understanding.
There are many different ways to gain understanding, but most workflows often boil down to:

- read data files
- perform some analysis operations, from very simple (e.g. take the mean) to very complex (e.g. train a deep neural network)
- visualize the output in a plot

CLMT5405 doesn't attempt to teach deep learning; its goal is to teach the basic foundations of Earth and Environmental Data Science which are often overlooked.
The material is designed to be accessible for Earth Science graduate students in any discipline, with little to no prerequisites.

This material is intended to introduce new graduate students to modern computing software, programming tools and best practices that are broadly applicable to the analysis and visualization of Earth and Environmental data.
This includes an introduction to Unix, version control, and basic programming in the open-source Python language.
The bulk of the content is devoted to in-depth exploration of the numerical analysis and visualization packages which comprise the modern Scientific Python ecosystem, including Numpy, Scipy, Matplotlib, Pandas, Xarray, using real Earth and Environmental datasets.

## Learning Goals

After completing all of the material, students should have the ability to:

- Use unix commands to work with files and directories
- Navigate the JupyterHub Environment effectively
- Identify common geoscience data formats and the python packages which can load them
- Perform basic exploratory data analysis on Earth and Environmental data, distinguishing between
  - _Tabular data_: rows and columns
  - _Gridded data_: multidimensional numerical arrays
- Use visualization to enhance interpretation of data, including maps and interactive visualizations
- Construct complete, well-structured programs in Python
- Practice reproducible research through version control and binder

## Course structure

For most weeks the general idea would be to complete one lecture and one homework assignment per week.
Generally, one of the weekly meetings would consist of a lecture in which the instructor presents the week's lecture, with students typing along.
The other should be used as "collaborative time," during which the students work on their assignments, ask questions, and interact with their peers.
A final project is an important capstone experience for a semester-long course.