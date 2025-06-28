## Final Project Requirements

### Team size requirements
Work in groups of 2-4 people. However, each individual should be able to describe every single component of the project.

### Learning Goals

The goal of the final project is to assess your ability to combine and apply the skills you have learned in class in the context of a real-world research/data-analysis problem. Our class has mostly focused on tools for data analysis and visualization, so this must be the focus of your final project. Specifically, we seek to assess your ability to do the following tasks:

*   Discover and download real datasets in standard formats (e.g. CSV, netCDF, zarr etc)
*   Load the data into Pandas or Xarray, performing any necessary data cleanup (dealing with missing values, proper time encoding, etc.) along the way.
*   Perform realistic scientific calculation involving, for example tasks such as grouping, aggregating, and applying mathematical formulas.
*   Visualize your results in well-formatted plots.

### Dataset Requirements

Your datasets can involve data collected by yourself or your lab, or can come from a public data repository. Ideally, your choice of dataset should be driven by your own interests. It is acceptable (and encouraged) to have your final project for this class involve an ongoing research project. _However, it is not acceptable to have your final project overlap with the final project for another class._

For your datasets, you can get them from a few sources:
- We have already played around with a few datasets in class, and there are more are coming (look ahead at the material posted on course website). Feel free to base your project around one or few of these if they interest you.
- The material in our [original book](https://earth-env-data-science.github.io/intro.html) towards the end (section on Climate Model Data), which we won't have time to cover in this shorter course, contains examples of other datasets that you may be able to leverage. 
- There are [previous projects](https://earth-env-data-science.github.io/projects.html), which you can use as inspiration and even source of the datasets (if the links still work!)
- There are a number of interesting datasets on https://catalog.leap.columbia.edu/ 

Also here are a couple of other links that may also help:

*   [IRI Data Library](http://iridl.ldeo.columbia.edu/)
*   [USGS Data Catalog](https://data.usgs.gov/datacatalog/)
*   [NOAA National Climate Data Center](https://www.ncdc.noaa.gov/)
*   [NASA Earth Science Data](https://earthdata.nasa.gov/)

You may use just one dataset, or you may choose to combine multiple datasets, depending on your scientific question.

### Analysis Requirements

The goal here is the same as with any science/data analysis project: to use the data to investigate a question or hypothesis. In order to succeed on the project, you will have to draw on your experience _outside_ our class, from your other classes or independent research, in order to define an interesting question. It is also acceptable to use this project to reproduce the results from a published study that you find interesting, provided you have access to the original data.

Whatever you choose, you should _clearly define a hypothesis or scientific question that you aim to investigate with your analysis_. This will determine what you have to do.

The results of this analysis will be figures. Beautiful figures which clearly provide answers to your question / hypothesis. Your notebook should contain at least 4 and no more than 8 figures. If you have closer to 4, they should be complex, multi-panel figures. All figures must have titles, clearly labeled axes, informative colormaps / colorbars, and legends, where appropriate.

### Technical Requirements

Your final project must meet the following technical requirements

*   A _single jupyter notebook_
*   Stored in a standalone public github repo
*   All data is either stored in the repo itself or downloaded / accessed from within the notebook (no manual download steps)
*   Complete explanatory text / equations included in the notebook as markdown cells
*   Notebook must execute in sequence with no errors
*   The whole github repo must be configured to run on [Leap pangeo hub](https://leap.2i2c.cloud/)

You _must_ use either Pandas or Xarray (or both) in some part of your project. You _may_ use other scientific python libraries as well, if you wish, to facilitate some analysis that is not possible with Xarray / Pandas alone. 

Some other libraries you may wish to consider (but not required to) are:

*   [SciPy](https://docs.scipy.org/doc/scipy/reference/) for interpolation, signal processing, spectral analysis, linear algebra, and other general purpose scientific computing routines
*   [Statsmodels](https://github.com/statsmodels/statsmodels) for advanced statistical analysis
*   [Scikit-image](https://scikit-image.org/) for image processing
*   [Scikit-learn](https://scikit-learn.org/stable/) for machine learning
*   [XGCM](https://xgcm.readthedocs.io/en/latest/) for working with finite-volume data from general circulation models
*   [XESMF](https://xesmf.readthedocs.io/en/latest/) for regridding of gridded data
*   [Pyresample](https://pyresample.readthedocs.io/en/latest/) for resampling (reprojection) of satellite data
*   [EOFS](https://ajdawson.github.io/eofs/) for empirical orthogonal function analysis
*   [windspharm](https://ajdawson.github.io/windspharm/latest/) for spherical harmonic analysis of global atmospheric wind data
*   [metpy](https://unidata.github.io/MetPy/latest/index.html) a collection of tools in Python for reading, visualizing, and performing calculations with weather data

### Project Approval

You must have your dataset(s) and general scope for your project approved by the instructor. 

The approval process has two parts. 

For part 1: 
- List of your group members 
- A rough title and a very short informal description of what you are planning to do
- The deadline for this task is **26 June 2025** (note that similar to homeworks, a delay would lead to the standard 10% penalty per 2 days)

For part 2:
-  Create a new public github repo for your project
-  Add a `README.md` file which contains the question / hypothesis you plan to investigate, links to the relevant datasets, and a three sentence summary of the analysis you plan to do. (It is very important that you have identified the datasets and know where to get them at this stage).
-  Submit a link to your project repo via email to the instructor.
-  The deadline for doing this **1 July 2025** (note that similar to homeworks, a delay would lead to the standard 10% penalty per 2 days)

### In-Class Presentations

You are asked to give a 10-minute presentation about your project. This can be done by one team member or as a group where you take turns. 
Do not prepare any slides. Instead, make your presentation by opening your notebook from GitHub on the presentation computer and walking us through parts of it. 

The presentations would take place on **3 July 2025** during the class period. 

Your presentation should be concise and ideally cover the following topics:

*   What data did you analyze and how did you load it?
*   What is the most interesting figure you made? (Show us the figure.)
*   What was the biggest challenge you faced in completing your project.

_Don't forget to make your project repo **public**; otherwise we won't be able to see it._

> Note: Try to finish your projects to the best of your abilities before the class presentation. However, it is ok if you have not completed your project all the way (or to your heart's satisfaction) by 3 July 2025. Still prepare a presentation and walk us through what you have done so far, what challenges you are actively facing, and what you plan to do to wrap up the project. The deadline for the final submission of the code would be the following week (read next section). 


### Final submission confirmation and 1-1 in person discussion

To wrap up your project and this class, you will need to take 2 more steps after the presentation. Both these steps would need to be completed before end of the working day (5pm) on **10 July 2025**.

1. Confirm with the instructor and TA that you are happy with your submission (in your Github project repo), and you don't plan to do any more changes. This will let us know when to go in and grade.
2. Setup a meeting time to have a 1-1 discussion between the instructor and each group member.

Guidance for the 1-1 discussion: 
- This is a critical part of your evaluation for the project
- Schedule a time to meet the instructor on one of the following days: 3 July (sometime after the class), 8 July or 10 July. If possible, please find this time to meet with the instructor (via email or ask in class) with the whole group at once, and plan for each member spending about ~5 mins in 1-1 discussions.
- Ideally, this should be scheduled after you are have completed step 1 (confirming your final submission).
- During these meetings expect to be asked 2-3 questions about any part of the code or analysis, and be prepared to explain it in depth. (Each group member is expected to understand the entirety of the code, even if you had contributed to different parts of the work).

_Try to not wait till the last day to complete all these steps, as we will have finite time to do these 1-1 meetings and people will be served on first come first serve basis. So if you are unable to find a time to schedule this because all slots were taken, it would count as an incomplete submission._



