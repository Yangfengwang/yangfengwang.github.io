---
permalink: /
title: "Yangfeng Wang"
redirect_from: 
  - /about/
  - /about.html
---


_Master's Student at Huazhong University of Science and Technology_

Wang Yangfeng obtained a Bachelor of Engineering degree in Mechanical Engineering from China Agricultural University (CAU) in 2020. During his undergraduate studies, his research focused on food control, intelligent sensing, and machine vision. Subsequently, he was recommended for admission to the School of Mechanical Science and Engineering at Huazhong University of Science and Technology (HUST) in 2024, where he studied under the supervision of Dr. Yu Wenyong.

His current research work focuses on machine vision, data fusion and industrial diagnostics. He has published **7** academic papers with a cumulative impact factor of **47.4** and **29** citations. He has been awarded the Innovation and Entrepreneurship Scholarship, Academic Scholarship, Special Prize of Beijing Engineering Training Competition, and the Third Prize of China Agricultural Robotics Competition.

His current research interests include:
* **Machine vision**: Research on Multi-task and Comparative Learning
* **Multimodal information fusion**: Algorithms and Systems


Publications
======

**_First/co-first Author_**

* **[_COMPAG '23_ ]** **Wang, Y.**, Jin, X., Zheng, J., Zhang, X., Wang, X., He, X., & Polovka, M. (2023). An energy-efficient classification system for peach ripeness using YOLOv4 and flexible piezoelectric sensor. Computers and Electronics in Agriculture, 210, 107909. http://doi.org/https://doi.org/10.1016/j.compag.2023.107909
* **[_Foods '23_ ]** **Wang, Y.**, Jin, X., Yang, L., He, X., & Wang, X. (2023). Predictive Modeling Analysis for the Quality Indicators of Matsutake Mushrooms in Different Transport Environments Foods 12(18), 3372. https://doi.org/10.3390/foods12183372
* **[_COMPAG '24_ ]** Huang, W.^1^, **Wang, Y.^1^**, Xia, J., Jin, X., Zhu, H., Glamuzina, B., Yu, W., & Zhang, X. (2024). Non-destructive classification of sturgeon stress using cross-modal data fusion and multi-input deep learning models. Computers and Electronics in Agriculture, 220, 108903. http://doi.org/https://doi.org/10.1016/j.compag.2024.108903

**_Other Author_**

* **[_CEJ '25_ ]** Jin, X., Guo, L., **Wang, Y**., Huang, W., & Wang, X. (2025). Flexible PEI functionalized CO2 sensing system designed for climacteric fruit cold chain quality monitoring. Chemical Engineering Journal, 505, 159680. http://doi.org/https://doi.org/10.1016/j.cej.2025.159680
* **[_Sensor Actuat A-phys '25_ ]** Huang, W., Yang, H., **Wang, Y**., Ding, P., Nawi, N. M., & Zhang, X. (2025). In-situ precision sensing for smart agriculture using multi-electrode sensor array systems in orchards. Sensors and Actuators a: Physical, 382, 116134. http://doi.org/https://doi.org/10.1016/j.sna.2024.116134
* **[_J. Food Process Eng '24_ ]** Huang, W., **Wang, Y**., Wang, Y., & Zhang, X. (2024). Non-destructive grading technique for mangoes using a flexible impedance sensing system and YOLOv5s_CBAM. Journal of Food Process Engineering, 47(5), e14631. http://doi.org/https://doi.org/10.1111/jfpe.14631
* **[_Mater. Today Sustainability '24_ ]** Huang, W., Xia, J., **Wang, Y**., Jin, X., Zhu, H., & Zhang, X. (2024). Flexible multimode sensors based on hierarchical microstructures enable non-destructive grading of fruits in cold chain logistics. Materials Today Sustainability, 25, 100691. http://doi.org/https://doi.org/10.1016/j.mtsust.2024.100691

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
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
