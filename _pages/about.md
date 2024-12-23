---
permalink: /
title: "About me ([CV](https://github.com/zjiaqi2018/academicpages.github.io/raw/master/files/CV-JQZHANG.pdf))"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I currently hold the position of Assistant Professor at Beijing Normal University at Zhuhai and at the Beijing Normal University-Hong Kong Baptist University United International College (UIC).
Prior to my current position, I was a postdoctoral fellow at Clemson University, where I had the privilege of collaborating closely with [Professor Timo Heister](http://www.math.clemson.edu/~heister/#home) in the development of open-source finite element libraries. I received my PhD in mathematics from Virginia Tech in 2020 under the guidance of [Professor Pengtao Yue](https://www.math.vt.edu/people/faculty/yue-pengtao.html). My research focuses on designing numerical algorithms to solve mathematical models derived from complex physical processes, developing efficient parallel solvers, and analyzing numerical results to explore underlying physics. The physical problems I am working on include dynamic wetting on (soft) solids, interfacial flows of a poroelastic hydrogel, brain concussion based on the hydrogel model, as well as three-phase (gas, liquid, solid) solidification with moving contact lines.



Research 
======
* Finite-element simulations of interfacial flows with moving contact lines. 
  * Level-set method
  * Phase-field method

* Simulating interfacial dynamics between a hydrogel and a fluid
  * Arbitrary Lagrangian-Eulerian method
  * Modeling of Rotation-induced Traumatic Brain Injury (TBI)

* Simulation of three-phase system with solidification and moving contact lines
  * Cahn-Hilliard model
  * Allen-Cahn model


* [deal.ii](https://www.dealii.org/) and [ASPECT](https://github.com/geodynamics/aspect)-Advanced Solver for Problems in Earth's ConvecTion
  * Matrix-free methods
  * Geometric multigrid
  * High performance computing


Current Research Funding
======
* 01/2025-12/2027: Modeling and numerical studies of wetting on soft solids. National Natural Science Foundation of China Youth Program, Principal Investigator, 300,000 RMB, Project Number: 12401511. 

* 11/2023-10/2026: Numerical simulations of dynamic wetting with fluid-structure interaction, and the development of a parallel solver. Guangdong Basic and Applied Basic Research Foundation, Principal Investigator, 10,000 RMB, Project Number: 2023A1515110861. 


Publications
======

* Zelai Xu, Jiaqi Zhang, Yuan-Nan Young, Pengtao Yue, and James J. Feng. "Comparison
  of four boundary conditions for the fluid-hydrogel interface". <i>Phys. Rev. Fluids</i>, 7:093301, Sep 2022. ([DOI](https://doi.org/10.1103/physrevfluids.7.093301))
* Lei Li, Jiaqi Zhang, Zelai Xu, Yuan-Nan Young, James J. Feng and Pengtao Yue. "An arbitrary Lagrangian-Eulerian method for simulating interfacial dynamics between a
hydrogel and a fluid". <i>Journal of Computational Physics</i>, page 110851, 2021. ([Preprint](https://github.com/zjiaqi2018/zjiaqi2018.github.io/blob/master/files/hydrogel_ver14.pdf))  
*  Daniel Arndt, Wolfgang Bangerth, Bruno Blais, Marc Fehling, Rene Gassmöller, Timo Heister, Luca Heltai, Uwe Köcher, Martin Kronbichler, Matthias Maier, Peter Munch, Jean-Paul Pelteret, Sebastian Proell, Konrad Simon, Bruno Turcksin, David Wells and Jiaqi Zhang . "The deal.II library, Version 9.3" <i>Journal of Numerical Mathematics</i>, vol. 29, no. 3, 2021, pp. 171-186. ([Preprint](https://www.dealii.org/deal93-preprint.pdf), [DOI](https://doi.org/10.1515/jnma-2021-0081)) 
* Jiaqi Zhang and Pengtao Yue. "A level-set method for moving contact lines with contact angle hysteresis". <i>Journal of Computational Physics</i>, 418:109636, 2020. ([Preprint](https://github.com/zjiaqi2018/academicpages.github.io/raw/master/files/contactLine_20.pdf), [DOI](https://doi.org/10.1016/j.jcp.2020.109636))
* Jiaqi Zhang and Pengtao Yue. "A high-order and interface-preserving discontinuous Galerkin method for level-set reinitialization". <i>Journal of Computational Physics</i>, 378:634–664, 2019. ([Preprint](https://github.com/zjiaqi2018/academicpages.github.io/raw/master/files/ls_reinit_19.pdf), [DOI](https://doi.org/10.1016/j.jcp.2018.11.029))

In revision
======
* A Fluid Mechanical Study of Rotation-induced Traumatic Brain Injury. (with Qifu Wang, David Bates, James J. Feng, Pengtao Yue, and Qianhong Wu)

Tutorial
======
The deal.II tutorial step-74: Symmetric interior penalty Galerkin method for Poisson's equation
([URL](https://www.dealii.org/current/doxygen/deal.II/step_74.html), [DOI](https://zenodo.org/record/5812174))


<!-- 
This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->
<!-- 
A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
