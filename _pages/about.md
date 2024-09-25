---
permalink: /
title: "Summary"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr. Zhuoye Zhang is a Post-doctoral Fellow at the Department of Industrial and Manufacturing Systems Engineering at The University of Hong Kong. Dr. Zhang received his PhD degree in Transportation from University of Hong Kong, Master's degree from Shanghai Jiaotong University, and Bachelor’s degree from Tongji University, China. Dr. Zhuoye Zhang’s research covers a wide range of fundamental and emerging issues in transportation, including shared and automated transport management, multimodal transportation system modelling and optimization and network modeling and analysis. His research has been published in world-leading journals and conferences in the field, e.g., Transportation Research Part B/C, International Symposium of Transportation and Traffic Theory (ISTTT). He also servse as a visiting student in University College London in 2019 and University of Michigan in 2024, respecitvely. 


Research interests
======
-Shared transport and logistics systems

-Transport network modeling and optimization

-Transport economics

-Transport/urban data analytics



Publications
======
[1] Zhang, Z., Zhang, F.* (2024) Optimal operation strategies of an urban crowdshipping platform in
asset-light, asset-medium, or asset-heavy business format. Transportation Research Part B: Methodological,
102992. (Accepted to be presented in the 25th International Symposium on Transportation
and Traffic Theory, ISTTT25).

[2] Zhang, Z., Liu, W., Zhang, F.* (2023) On the joint network equilibrium of parking and travel
choices under mixed traffic of shared and private autonomous vehicles. Transportation Research Part
C: Emerging Technologies, 153, 104226. (Recipient of Qian Xuesen Urban Science Gold Award (Transportation)
Nomination Award)

[3] Zhang, Z., Zhang, F.* (2022) Ride-pooling services with differentiated pooling sizes under endogenous
congestion effect. Transportation Research Part C: Emerging Technologies, 144, 103883.

[4] Zhang, Z., Lu. L.*, Zhu, L., Zhang, W., Yang, J. (2020). Preference information incorporation for
decision making in the biobjective alignment optimization problem of river-crossing tunnels. Journal
of Transportation Engineering, Part A: Systems, 146(10), 04020121.


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
