# ROOT Advanced Course
[![SWAN](https://swan.web.cern.ch/sites/swan.web.cern.ch/files/pictures/open_in_swan.svg)](https://cern.ch/swanserver/cgi-bin/go?projurl=https://github.com/root-project/ROOTAdvancedCourse.git)
[![Github Codespace](https://img.shields.io/badge/open-GH_Codespaces-blue?logo=github)](https://codespaces.new/root-project/ROOTAdvancedCourse?quickstart=1)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/root-project/ROOTAdvancedCourse/main)

This is an extension of the [ROOT Student Course](https://github.com/root-project/student-course/tree/25.07) and the assumption is that you are familiar with the concepts explained in the student course before taking this advanced course. The goal is to make you at ease of conducting modern data analysis with tools and packages offered by the modern ROOT, including UHI, Roofit, RNTuples and RDataFrame.

In the `course/notebooks/` folder you will find 5 topical lessons. There is also an example of an Open Data analysis where you can test your understanding of the various concepts covered in the course.

The in-person course based on the material in this repository was recorded on the 25th March 2026. The recording is available [here](https://videos.cern.ch/record/3025341). We encourage you to watch the video and follow along with the notebooks.

## Note on ROOT version to be used
Please note, in order to be able to run all cells of this course, we recommend using ROOT version 6.38 or higher. Such version is available if you set up the course using one of the badges above - SWAN is recommended if you have CERN computing account, otherwise you can use GitHub Code Spaces or Binder.

## Local use

To install an environment and get running

1. Install [Pixi](https://pixi.prefix.dev/)
1. Clone this repository and navigate to the top level directory.
1. Run
```
pixi run start
```
