---
layout: page-fullwidth
show_meta: false
title: "Lessons"
header:
   image_fullwidth: "wood_plank.jpg"
permalink: "/lessons/"
---

Based on the [Software Carpentry](http://software-carpentry.org) strategy of collaborative development
of hands-on, interactive lessons for workshops, we facilitate and
develop the lessons for Data Carpentry workshops.

[Interested in helping develop lessons?](/involved-lessons/)

These lessons are distributed under the [CC-BY](https://creativecommons.org/licenses/by/2.0/) and are free for re-use or adaptation, with attribution. We've had people use the lessons in courses, to build new lessons or use them for self-guided learning.

Data Carpentry workshops are domain-specific, so that we are teaching researchers the skills most relevant to their domain and using examples from their type of work. Therefore we have several types of workshops and lessons are ordered by topic.

- [Ecology materials](#ecology-workshop)
- [Genomics materials](#genomics-workshop)
- [Geospatial data materials](#geospatial-data-workshop)
- [Social science materials](#social-science-materials)
- [Biology semester long materials](#biology-semester-long-course)

<hr>

### Ecology Workshop

#### Overview

This workshop uses a [tabular ecology dataset](https://github.com/datacarpentry/ecology-workshop/blob/master/data.md) from the [Portal Project Teaching Database](https://figshare.com/articles/Portal_Project_Teaching_Database/1314459) and teaches data cleaning, management, analysis and visualization. *There are no pre-requisites, and the materials assume no prior knowledge about the tools.* We use a single dataset throughout the workshop to model the data management and analysis workflow that a researcher would use.

[More workshop details](https://github.com/datacarpentry/ecology-workshop)

The workshop can be taught using R or Python as the base language.

#### Lessons


<table class="table table-striped">
  <tr>
    <th>Lesson</th>
    <th>Site</th>
    <th>Repository</th>
    <th>Maintainer(s)</th>
  </tr>
  <tr>
    <td>Data Organization in Spreadsheets</td>
    <td><a href="{{site.dc_github_repo_url}}/spreadsheet-ecology-lesson/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td><a href="{{site.dc_github_site_url}}/spreadsheet-ecology-lesson/" target="_blank" class="icon-github" title="icon-github"></a></td>
    <td>Christie Bahlai, Tracy Teal</td>
  </tr>
  <tr>
    <td>Data Cleaning with OpenRefine</td>
    <td><a href="{{site.dc_github_repo_url}}/OpenRefine-ecology-lesson/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td><a href="{{site.dc_github_site_url}}/OpenRefine-ecology-lesson/" target="_blank" class="icon-github" title="icon-github"></a></td>
    <td>Deborah Paul, Cam Macdonell</td>
  </tr>
  <tr>
    <td>Data Management with SQL</td>
    <td><a href="{{site.dc_github_repo_url}}/sql-ecology-lesson/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td><a href="{{site.dc_github_site_url}}/sql-ecology-lesson/" target="_blank" class="icon-github" title="icon-github"></a></td>
    <td>Paula Andrea Martinez, Timothée Poisot</td>
  </tr>
  <tr>
    <td>Data Analysis and Visualization in R</td>
    <td><a href="{{site.dc_github_repo_url}}/R-ecology-lesson/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td><a href="{{site.dc_github_site_url}}/R-ecology-lesson/" target="_blank" class="icon-github" title="icon-github"></a></td>
    <td>François Michonneau, Auriel Fournier</td>
  </tr>
  <tr>
    <td>Data Analysis and Visualization in Python</td>
    <td><a href="{{site.dc_github_repo_url}}/python-ecology-lesson/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td><a href="{{site.dc_github_site_url}}/python-ecology-lesson/" target="_blank" class="icon-github" title="icon-github"></a></td>
    <td>John Gosset, April Wright, Mateusz Kuzak</td>
  </tr>
</table>

<hr>

### Genomics Workshop

#### Overview

The focus of this workshop is on working with genomics data and data management and analysis for genomics research. It covers metadata organization in spreadsheets, data organization, connecting to and using cloud computing, the command line for sequence quality control and bioinformatics workflows, and R for data analysis and visualization. The workshop does not teach any particular bioinformatics tools, but the foundational skills that will allow you to conduct any analysis and analyze the output of a genomics pipeline.

[More workshop details](http://www.datacarpentry.org/genomics-workshop/)

#### Lessons

<table class="table table-striped">
  <tr>
    <th>Lesson</th>
    <th>Material</th>
    <th>Maintainer(s)</th>
  </tr>
  <tr>
    <td>Introduction to the workshop and dataset</td>
    <td><a href="{{site.dc_website_url}}/introduction-genomics/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Tracy Teal</td>
  </tr>
  <tr>
    <td>Introduction to cloud computing for genomics</td>
    <td><a href="{{site.dc_github_repo_url}}/cloud-genomics/tree/gh-pages/lessons" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Bob Freeman</td>
  </tr>
  <tr>
    <td>Introduction to the command line</td>
    <td><a href="{{site.dc_github_repo_url}}/shell-genomics/tree/gh-pages/lessons" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Sheldon McKay, Karen Cranston</td>
  </tr>
  <tr>
    <td>Data wrangling and processing</td>
    <td><a href="{{site.dc_github_repo_url}}/wrangling-genomics/tree/gh-pages/lessons" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Sheldon McKay, Karen Cranston</td>
  </tr>
  <tr>
    <td>Data analysis in R</td>
    <td><a href="{{site.dc_website_url}}/R-genomics/04-dplyr.html" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Naupaka Zimmerman, Jason Williams</td>
  </tr>
  <tr>
    <td>Data visualization in R</td>
    <td><a href="{{site.dc_website_url}}/R-genomics/05-data-visualization.html" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Meeta Mistry</td>
  </tr>
</table>

<hr>

### Geospatial Data Workshop

#### Overview

This workshop is co-developed with the National Earth Observatory Network [(NEON)](http://www.neon.org). It focuses on working with geospatial data - managing and understanding spatial data formats, understanding coordinate reference systems, and working with Raster and Vector data in R for analysis and visualization.

#### Lessons

<table class="table table-striped">
  <tr>
    <th>Lesson</th>
    <th>Material</th>
    <th>Maintainer(s)</th>
  </tr>
  <tr>
    <td>Introduction to working with vector data in R</td>
    <td><a href="http://neondataskills.org/tutorial-series/vector-data-series/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Leah Wasser, Megan Jones</td>
  </tr>
  <tr>
    <td>Getting started with raster data in R</td>
    <td><a href="http://neondataskills.org/tutorial-series/raster-data-series/" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Leah Wasser, Megan Jones</td>
  </tr>
  </table>


<hr>

### Social Science Materials

This is not yet a full workshop, but we have a lesson focused on text mining in R

<table class="table table-striped">
  <tr>
    <th>Lesson</th>
    <th>Material</th>
    <th>Maintainer(s)</th>
  </tr>
  <tr>
    <td>Social sciences text mining</td>
    <td><a href="{{site.dc_github_repo_url}}/textmining-socialsci" target="_blank" class="icon-browser" title="icon-browser"></a></td>
    <td>Ben Marwick</td>
  </tr>
</table>

<hr>

### Biology Semester-long Course

The [Biology Semester-long Course](http://www.datacarpentry.org/semester-biology/)
was developed and piloted at the University of Florida in Fall 2015.
Course materials include, readings, lectures, exercises and assignments
that expand on the material presented at workshops focusing on SQL and R.
The course is accessible to:

- [Self-guided Students](http://www.datacarpentry.org/semester-biology/START-for-self-guided-students)
- [Instructors](http://www.datacarpentry.org/semester-biology/docs/)
