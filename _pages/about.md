---
permalink: /
title: "About me"
# excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div style="text-align: justify;">
<p>
My name is Yifan Zhu, and I am a postdoctoral research scholar at the Yale <a href="https://www.eng.yale.edu/grablab/">GRAB Lab</a>, advised by Prof. Aaron Dollar. Previously, I obtained a Ph.D. at the <a href="https://cs.illinois.edu/">Computer Science department</a> at the <a href="https://illinois.edu/">University of Illinois at Urbana-Champaign</a>, where I was a member of the <a href="https://motion.cs.illinois.edu/">Intelligent Motion Lab</a> and advised by Prof. Kris Hauser on robotics. You are also welcome to check out <a href="https://motion.cs.illinois.edu/efficientlearning/index.html">my old research page</a> on the lab website.
</p>
<i>My research vision is to develop fundamental technologies that enable robots to understand their contacts with
the external world from proactive interactions and perform meaningful tasks.</i> My prior research lies at the intersection of physics modeling, optimization, machine learning, hardware design. I aim to develop representations for robots that facilitate tight integration of physics modeling and machine learning for predictive world modeling from visual-tactile perceptions, especially in the low-data regime. 
<p>
<span style="color: red;font-weight: bold;">I am currently on the faculty job market for the 2024-25 cycle!</span>
</p>
</div>
<!-- There are two fronts of my research. On one hand, I work on data-driven modeling of deformable objects and planning robot motions in deformable environments. On the other front, I have been developing a nursing assistant robot called TRINA with my colleagues, and enabling it with both tele-operation and autonomous capabilities.  -->

News
======
June 2023: I successfully defended on 06/20! 

April 2023: Our paper ``Few-shot Adaptation for Manipulating Granular Materials Under Domain Shift" is accepted to RSS 2023! We also release a scooping dataset with over 6,000 scoops on a diverse set of materials: [website](https://drillaway.github.io/scooping-dataset.html), [paper](https://arxiv.org/abs/2303.02893).

Nov 2022: Our robot TRINA has been participating in the AVATAR XPRIZE competition as Team AVATRINA, and we just scored 4-th in the finals, one of the only 4 teams that completed all 10 tasks: [media](https://www.xprize.org/prizes/avatar/competing-teams).



<style>
.publications-section {
    margin: 40px 0;
}

.publication-container {
    display: flex;
    align-items: flex-start;
    gap: 20px;
    margin-bottom: 40px;
}

.publication-image {
    flex: 0 0 200px;
}

.publication-image img {
    width: 100%;
    height: auto;
    border-radius: 4px;
}

.publication-content {
    flex: 1;
}

.publication-title {
    font-style: italic;
    margin: 0;
}

.publication-venue {
    margin: 5px 0;
}

.publication-link {
    margin-left: 5px;
    text-decoration: none;
}

.video-link {
    margin-left: 5px;
    text-decoration: none;
    color: inherit;
}
</style>

<h1>Selected Publications</h1>
  <div class="publications-section">
    <div class="publication-container">
        <div class="publication-image">
            <img src="images/TRINA.PNG" alt="TRINA Publication Image">
        </div>
        <div class="publication-content">
            J. Marques*, P. Naughton*, J. C. Peng*, <u><b>Y. Zhu*</b></u>, J. S. Nam, Q. Kong, X. Zhang, A. Penmetcha, R. Ji, N. Fu, V. Ravibaskar, R. Yan, N. Malhotra, and K. Hauser, "Immersive Commodity Telepresence with the TRINA Robot Avatar," International Journal of Social Robots, 2024. <a href="https://link.springer.com/article/10.1007/s12369-023-01090-1" class="publication-link"><img src="images/pdf_icon_tiny.gif" alt="PDF link"></a> (* Denotes equal contribution)
        </div>
    </div>

    <div class="publication-container">
        <div class="publication-image">
            <img src="images/animation-datacollection.gif" alt="Scooping Publication Image">
        </div>
        <div class="publication-content">
            <u><b>Y. Zhu*</b></u>, P. Thangeda\*, M. Ornik and K. Hauser., "Few-shot Adaptation for Manipulating Granular Materials Under Domain Shift," Robotics: Science and Systems (RSS), 2023. <a href="https://arxiv.org/abs/2303.02893" class="publication-link"><img src="images/pdf_icon_tiny.gif" alt="PDF link"></a> <a href="https://drillaway.github.io/scooping-dataset.html" class="publication-link"><img src="images/link_icon_tiny.gif" alt="Website&Dataset"></a>(* Denotes equal contribution)
        </div>
    </div>

    <div class="publication-container">
        <div class="publication-image">
            <img src="images/Auscultation_full.gif" alt="Auscultation Publication Image">
        </div>
        <div class="publication-content">
            <u><b>Y. Zhu</b></u>, A. Smith, and K. Hauser, "Automated Heart and Lung Auscultation in Robotic Physical Examinations," IEEE Robotics and Automation Letters (RA-L), 2022. <a href="https://arxiv.org/abs/2201.09511" class="publication-link"><img src="images/pdf_icon_tiny.gif" alt="PDF link"></a> 
        </div>
    </div>

    <!-- First Publication -->
    <div class="publication-container">
        <div class="publication-image">
            <img src="images/poke.gif" alt="Poke Research">
        </div>
        <div class="publication-content">
            <u><b>Y. Zhu</b></u>, K. Lu, and K. Hauser. <i>Semi-Empirical Simulation of Learned Force Response Models for Heterogeneous Elastic Objects</i>. IEEE International Conference on Robotics and Automation (ICRA), June 2020
            <a href="files/Zhu_Poke_2020.pdf" class="publication-link"><img src="images/pdf_icon_tiny.gif" alt="PDF"></a>
            <a href="https://youtu.be/-9sjiERznRc" class="video-link"><img src="images/mov_icon_tiny.gif" alt="Video"> Summary video</a>
            <a href="https://youtu.be/xdrKUddJaEU" class="video-link"><img src="images/mov_icon_tiny.gif" alt="Video"> ICRA 10-minute talk video</a>
        </div>
    </div>

    <div class="publication-container">
        <div class="publication-image">
            <img src="images/TO_both.gif" alt="TO Research">
        </div>
        <div class="publication-content">
            <u><b>Y. Zhu</b></u>, Z. Pan, and K. Hauser. <i>Contact-Implicit Trajectory Optimization with Learned Deformable Contacts Using Bilevel Optimization</i>. IEEE International Conference on Robotics and Automation (ICRA), May 2021.
            <a href="files/Zhu_TO_2021.pdf" class="publication-link"><img src="images/pdf_icon_tiny.gif" alt="PDF"></a>
            <a href="https://youtu.be/cgMl3bAGfqc" class="video-link"><img src="images/mov_icon_tiny.gif" alt="Video"> Supplemental video</a>
        </div>
    </div>

    <!-- Third Publication -->
    <div class="publication-container">
        <div class="publication-image">
            <img src="images/GM.gif" alt="Granular Media Research">
        </div>
        <div class="publication-content">
            <u><b>Y. Zhu</b></u>, L. Abdulmajeid, and K. Hauser. <i>Data-driven Approach for Fast Simulation of Robot Locomotion on Granular Media</i>. IEEE International Conference on Robotics and Automation, May, 2019.
            <a href="files/Zhu_GranularMedia_2019.pdf" class="publication-link"><img src="images/pdf_icon_tiny.gif" alt="PDF"></a>
            <a href="https://youtu.be/-9sjiERznRc" class="video-link"><img src="images/mov_icon_tiny.gif" alt="Video"> Summary video</a>
            <a href="https://youtu.be/xdrKUddJaEU" class="video-link"><img src="images/mov_icon_tiny.gif" alt="Video"> ICRA 10-minute talk video</a>
        </div>
    </div>
</div>


Robots that I work with
======

|<img src="images/ur5.png" alt="drawing" width="200" /> UR5 |<img src="images/TRINA.JPG" alt="drawing" width="200" /> TRINA|<img src="images/robosimian.jpg" alt="drawing" width="200" /> Robosimian|<img src="images/franka.jpg" alt="drawing" width="200" /> Franka Panda|

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-VK97Q9SJHP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-VK97Q9SJHP');
</script>

<!-- 
This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

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

