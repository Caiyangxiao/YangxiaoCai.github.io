---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am Yangxiao Cai, a dedicated and enthusiastic graduate student currently pursuing a Master’s degree in Software Engineering at Wuhan University. I hold a Bachelor’s degree in Computer Science and Technology from the same institution, where I graduated in 2024 with a GPA of 3.84/4.0. My academic training has equipped me with a robust foundation in advanced programming, machine learning, and software development, fostering my passion for innovative technologies.

My research interests lie at the intersection of software engineering and artificial intelligence. I have authored two publications in reputable venues: one in the Journal of Systems and Software, exploring challenges and solutions in large language model (LLM) open-source projects, and another in arXiv, investigating security code review with LLMs. I'm the first author of the formal paper. These works reflect my commitment to advancing knowledge in cutting-edge domains.

Professionally, I interned at Beijing Dajia Internet Information Technology Co., Ltd. (Kuaishou) in 2023, where I contributed to the Beauty module, Face Stickers, and Special Effects Background Stickers, using C++ and QML. Additionally, I have led independent projects, such as an online taxi application built with Spring Boot microservices, and a research initiative employing a Dueling Deep Q-Network (DQN) to optimize microservice deployment by predicting user mobility patterns.

Beyond academics and research, I have engaged in leadership roles, serving as a Class Assistant at Wuhan University and a member of the Reasoning Society. These experiences have strengthened my organizational, communication, and teamwork skills. I am proficient in Python, C/C++, Java, and Swift, and I am fluent in Mandarin and English.

I invite you to explore my webpage to learn more about my projects, publications, and journey. Thank you for visiting!

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
