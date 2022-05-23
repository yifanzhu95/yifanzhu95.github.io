---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
My name is Yifan Zhu, and I am currently a 5th-year Ph.D. student at the <a href="https://cs.illinois.edu/">Computer Science department</a> at the <a href="https://illinois.edu/">University of Illinois at Urbana-Champaign</a>. I am a member of the <a href="https://motion.cs.illinois.edu/">Intelligent Motion Lab</a> and work with Prof. Kris Hauser on robotics. There are two fronts of my research. On one hand, I work on data-driven modeling of deformable objects and planning robot motions in deformable environments. On the other front, I have been developing a nursing assistant robot called TRINA with my colleagues, and enabling it with both tele-operation and autonomous capabilities. You are welcome to check out <a href="https://motion.cs.illinois.edu/efficientlearning/index.html">my research page</a> on the lab website.

News
======
October 2021: Our robot TRINA has been participating in the AVATAR XPRIZE competition as Team AVATRINA, and we just scored 4-th in the semi-finals and are advancing to the finals! [media](https://www.xprize.org/prizes/avatar/competing-teams)


Selected Publications
======
<body>
    <table style="max-width:1200px;border:0px;border-spacing:0px;border-collapse:separate;"><tbody>
          <tr style="padding:0px">
            <td style="padding:0px">  
                <td style="padding:0px;vertical-align:middle">
                    <!-- <td style="padding:0px;width:40%;vertical-align:left"> -->
                <div class="one">
                    <img src="images/grasp.gif" width=300px />
                </div>
                </td>
                <td style="min-width:300px;padding:20px;vertical-align:left">
                <h4>Meta-learning few-shot regrasping</h4>
                <p>This project is ongoing. In this project, we are currently investigating the problem of meta-learning surrogate scoring functions for the few-shot regrasping problem. This is a challenging task because in addition to the visual variations of real-world objects, they often present characteristics that are not directly observable, such as center of mass. Another challenge is the goal to successfully regrasping a novel object with feedback from a few failed attempts. We are currently looking into meta-learning to address these challenges.</p>
                </td>
            </td>
          </tr>
    
          <tr style="padding:0px">
            <td style="padding:0px">  
                <!-- <td style="padding:90px;width:40%;vertical-align:left"> -->
                <td style="padding:0px;vertical-align:middle">
                <div class="one">
                    <img src="Auscultation_full.gif" width=300px />
                </div>
                </td>
                <td style="min-width:300px;padding:20px;vertical-align:left">
                <h4>Automated Heart and Lung Auscultation in Robotic Physical Examinations</h4>
                <p> This paper presents the first implementation of autonomous robotic auscultation of heart and lung sounds. To
                    select auscultation locations that generate high-quality sounds,
                    a Bayesian Optimization (BO) formulation leverages visual
                    anatomical cues to predict where high-quality sounds might be
                    located, while using auditory feedback to adapt to patient-specific
                    anatomical qualities. Sound quality is estimated online using
                    machine learning models trained on a database of heart and lung
                    stethoscope recordings. Experiments on 4 human subjects show
                    that our system autonomously captures heart and lung sounds of
                    similar quality compared to tele-operation by a human trained in
                    clinical auscultation. Surprisingly, one of the subjects exhibited
                    a previously unknown cardiac pathology that was first identified
                    using our robot, which demonstrates the potential utility of
                    autonomous robotic auscultation for health screening.</p> <a href="../papers/RAL2022-Zhu-Ascultation-preprint.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a>
                    <a href="https://arxiv.org/abs/2201.09511"><img class="link"  src="../images/link_icon_tiny.gif" alt="link"></a>
                </td>
            </td>
          </tr>
   
        <tr style="padding:0px">
            <td style="padding:0px">  
                <td style="padding:0px;vertical-align:left">
                <div class="one">
                    <img src="poke.gif" width=400px/>
                </div>
                </td>
                <td style="min-width:300px;padding:20px;vertical-align:left">
                <h4>Semi-Empirical Simulation of Learned Force Response Models for Heterogeneous Elastic Objects</Object></h4>
                <p>This paper presents a semi-empirical method for
                    simulating contact with elastically deformable objects whose
                    force response is learned using entirely data-driven models.
                    A point-based surface representation and an inhomogeneous,
                    nonlinear force response model are learned from a robotic arm
                    acquiring force-displacement curves from a small number of
                    poking interactions. The simulator then estimates displacement
                    and force response when the deformable object is in contact
                    with an arbitrary rigid object. It does so by estimating displacements by solving a Hertzian contact model, and sums the
                    expected forces at individual surface points through querying
                    the learned point stiffness models as a function of their expected
                    displacements. Experiments on a variety of challenging objects
                    show that our approach learns force response with sufficient
                    accuracy to generate plausible contact response for novel rigid
                    objects.</p>
                    <a href="../papers/ICRA2020-Zhu-LearningElastic.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a>
                    <a href="https://youtu.be/-9sjiERznRc"><img class="mov" src="../images/mov_icon_tiny.gif"> Summary video</a>
                    <a href="https://youtu.be/xdrKUddJaEU"><img class="mov" src="../images/mov_icon_tiny.gif"> ICRA 10-minute talk video</a>
                </td>
            </td>
          </tr>


        <tr style="padding:0px">
            <td style="padding:0px">  
                <td style="padding:0px;vertical-align:left">
                <div class="one">
                    <img src="TO_both.gif" width=400px />
                </div>
                </td>
                <td style="min-width:300px;padding:20px;vertical-align:left">
                <h4>Contact-Implicit Trajectory Optimization with Learned Deformable Contacts Using Bilevel Optimization</h4>
                <p> Based on the previous project shown below, we present a bilevel, contact-implicit trajectory
                    optimization (TO) formulation that searches for robot trajectories with learned soft contact models. On the lower-level, contact
                    forces are solved via a quadratic program (QP) with the maximum dissipation principle (MDP), based on which the dynamics
                    constraints are formulated in the upper-level TO problem that
                    uses direct transcription. Our method uses a contact model
                    for granular media that is learned from physical experiments,
                    but is general to any contact model that is stick-slip, convex,
                    and smooth. We employ a primal interior-point method with
                    a pre-specified duality gap to solve the lower-level problem,
                    which provides robust gradient information to the upper-level
                    problem. We evaluate our method by optimizing locomotion
                    trajectories of a quadruped robot on various granular terrains
                    offline, and show that we can obtain long-horizon walking gaits
                    of high qualities.</p>
                    <a href="../papers/ICRA2019-Zhu-GranularMedia.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a> <a href="https://youtu.be/AVyvnFREed8"><img class="mov" src="../images/mov_icon_tiny.gif"> ICRA video</a>
                </td>
            </td>
          </tr>



      <tr style="padding:0px">
        <td style="padding:0px">  
            <td style="padding:0px;vertical-align:left">
            <div class="one">
               <img src="GM.gif" width=400px/>
            </div>
            </td>
            <td style="min-width:300px;padding:20px;vertical-align:left">
            <h4>A Data-driven Approach for Fast Simulation of Robot Locomotion on Granular Media</h4>
            <p>In this paper, we propose a semi-empirical approach for simulating robot locomotion on granular media. We
                first develop a contact model based on the stick-slip behavior
                between rigid objects and granular grains, which is then learned
                through running extensive experiments. The contact model
                represents all possible contact wrenches that the granular
                substrate can provide as a convex volume, which our method
                formulates as constraints in an optimization-based contact force
                solver. During simulation, granular substrates are treated as
                rigid objects that allow penetration and the contact solver solves
                for wrenches that maximize frictional dissipation. We show that
                our method is able to simulate plausible interaction response
                with several granular media at interactive rates.</p>
                <a href="../papers/ICRA2020-Zhu-LearningElastic.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a> <a href="https://youtu.be/-9sjiERznRc"><img class="mov" src="../images/mov_icon_tiny.gif"> Summary video</a> <a href="https://youtu.be/xdrKUddJaEU"><img class="mov" src="../images/mov_icon_tiny.gif"> ICRA 10-minute talk video</a>


            <!-- <a href="https://waymo.com/research/block-nerf/">
                <papertitle>NeRF-Supervision: Learning Dense Object Descriptors from Neural Radiance Fields</papertitle>
            </a>
            <br>
            <a href="https://yenchenlin.me/">Lin Yen-Chen</a>, 
            <a href="http://www.peteflorence.com/">Pete Florence</a>, 
            <strong>Jonathan T. Barron</strong>,  <br>
            <a href="https://scholar.google.com/citations?user=_BPdgV0AAAAJ&hl=en">Tsung-Yi Lin</a>, 
            <a href="https://meche.mit.edu/people/faculty/ALBERTOR@MIT.EDU">Alberto Rodriguez</a>,
            <a href="http://web.mit.edu/phillipi/">Phillip Isola</a>
            <br>
            <em>ICRA</em>, 2022  
            <br>
                            <a href="http://yenchenlin.me/nerf-supervision/">project page</a> / 
                            <a href="https://arxiv.org/abs/2203.01913">arXiv</a> / 
                            <a href="https://www.youtube.com/watch?v=_zN-wVwPH1s">video</a> /
                            <a href="https://github.com/yenchenlin/nerf-supervision-public">code</a> / 
                            <a href="https://colab.research.google.com/drive/13ISri5KD2XeEtsFs25hmZtKhxoDywB5y?usp=sharing">colab</a>				
            <p></p> -->
            </td>
        </td>
      </tr>
    </table>
  </body>
  


<!-- <div class="pubs">
<ul class="publications">
	<li>Y. Zhu, A. Smith, and K. Hauser. <i>Automated Heart and Lung Auscultation in Robotic Physical Examinations</i>. IEEE Robotics and Automation Letters, 2022.
        <span class="nw">
            <a href="../papers/RAL2022-Zhu-Ascultation-preprint.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a>
            <a href="https://arxiv.org/abs/2201.09511"><img class="link"  src="../images/link_icon_tiny.gif" alt="link"></a>
    </span></li>
    <li>Y. Zhu, K. Lu, and K. Hauser. <i>Semi-Empirical Simulation of Learned Force Response Models for Heterogeneous Elastic Objects</i>. IEEE International Conference on Robotics and Automation (ICRA), June 2020 	<span class="nw"><a href="../papers/ICRA2020-Zhu-LearningElastic.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a> <a href="https://youtu.be/-9sjiERznRc"><img class="mov" src="../images/mov_icon_tiny.gif"> Summary video</a> <a href="https://youtu.be/xdrKUddJaEU"><img class="mov" src="../images/mov_icon_tiny.gif"> ICRA 10-minute talk video</a></span>
    <li>Y. Zhu, L. Abdulmajeid, and K. Hauser. <i>Data-driven Approach for Fast Simulation of Robot Locomotion on Granular Media</i>. IEEE International Conference on Robotics and Automation, May, 2019. <span class="nw"><a href="../papers/ICRA2019-Zhu-GranularMedia.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a> <a href="https://youtu.be/AVyvnFREed8"><img class="mov" src="../images/mov_icon_tiny.gif"> ICRA video</a> </span></li>
    <li>Y. Zhu, K. Lu, and K. Hauser. <i>Semi-Empirical Simulation of Learned Force Response Models for Heterogeneous Elastic Objects</i>. IEEE International Conference on Robotics and Automation (ICRA), June 2020 	<span class="nw"><a href="../papers/ICRA2020-Zhu-LearningElastic.pdf"><img class="pdf"  src="../images/pdf_icon_tiny.gif" alt="pdf"></a> <a href="https://youtu.be/-9sjiERznRc"><img class="mov" src="../images/mov_icon_tiny.gif"> Summary video</a> <a href="https://youtu.be/xdrKUddJaEU"><img class="mov" src="../images/mov_icon_tiny.gif"> ICRA 10-minute talk video</a></span>
</ul>
</div> -->



Robots that I work with
======

|<img src="images/ur5.png" alt="drawing" width="200" /> UR5 |<img src="images/TRINA.JPG" alt="drawing" width="200" /> TRINA|<img src="images/robosimian.jpg" alt="drawing" width="200" /> Robosimian|<img src="images/franka.jpg" alt="drawing" width="200" /> Franka Panda|


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
