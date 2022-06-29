---
layout: default
title: Summer 2020 DREU Project Site
---

<style> 
    img {
        float: right;
        margin: 15px;
        height: auto;
    }

    #hiking-photo {
      max-width: 50%;
    }

    #dr-kavraki-photo {
      max-width: 35%;
    }
</style>

* TOC
{:toc}

## About Me

<img src="https://LexiShew.github.io/images/hiking.jpg" alt="hiking">

<p>
    Hello!<br><br>    
    My name is Alexandra Shewchuk, but I go by Lexi. I'm a rising junior at Tufts University, which is just outside of Boston, MA. I'm studying computer science and biology, and I plan to pursue a career in computational biology. This summer, I've been lucky enough to be paired with Dr. Lydia Kavraki's bioinformatics lab in Houston, TX, where I'll be assisting a research project.<br><br>
    Since starting at Tufts, I've listened in on two bioinformatics labs and become a TA for CS40: Machine Structure and Assembly Language Programming; these experiences have affirmed my interest in research and graduate school, so I'm thrilled to be a part of Dr. Kavraki's lab this summer.<br><br>
    Outside of research and school, I've joined the Tufts ski team, I've been exploring the Greater Boston Area, and I love to hike, read, and spend time outdoors. More recently, I've gotten into baking bread and pastries, which is likely because they're a little scientific and require some experimentation :)<br><br>
    I'm excited to explore Houston and meet the students and faculty at Rice here this summer!
</p>


## About My Mentor

<img src="https://LexiShew.github.io/images/dr-kavraki.jpg" alt="Dr. Lydia Kavraki">

<p>
    Lydia E. Kavraki is the Noah Harding Professor of Computer Science, professor of Bioengineering, professor of Electrical and Computer Engineering, and professor of Mechanical Engineering at Rice University. She is the Director of the Ken Kennedy Institute at Rice.
    Kavraki received her B.A. in Computer Science from the University of Crete in Greece and her Ph.D. in Computer Science from Stanford University working with Professor Jean-Claude Latombe.<br><br>
    Kavraki's research interests span robotics, AI, and biomedicine. In robotics and AI, she is interested in enabling robots to work with people and in support of people. Her research develops the underlying methodologies for achieving this goal: algorithms for motion planning for high-dimensional systems with kinematic and dynamic constraints, integrated frameworks for reasoning under sensing and control uncertainty, novel methods for learning and for using experiences, and ways to instruct robots at a high level and collaborate with them. Kavraki’s lab is inspired by a variety of applications: from robots that will assist people in their homes, to robots that assist in surgeries, to robots that would build space habitats. In biomedicine she develops computational methods and tools to model protein structure and function, understand biomolecular interactions, aid the process of medicinal drug discovery, analyze the molecular machinery of the cell, and help integrate biological and biomedical data for improving human health. Her work has applications, among others, in personalized immunotherapy. Kavraki’s research blends her extensive interdisciplinary background in computer science, artificial intelligence, machine learning, bioengineering and biomedical sciences promoting the convergence of these disciplines.<br><br>
    Please see <a href="https://www.cs.rice.edu/~kavraki/">Dr. Kavraki's personal site</a>.
</p>


## About My Project
<p>
    This summer, I've been working alongside Romanos, a PhD student in Dr. Kavraki's lab, to improve the functionality of a tool called APE-Gen, which models and predicts the binding of Major Histocompatibility Complexes (MHCs) and smaller peptides. This process is a core part of the body's immune response, as MHCs will present the peptides to T-cells at the cell surface to determine if the cell has been affected.<br><br>
    APE-Gen was originally developed in order to model these peptide-MHC bindings and predict their binding affinities, and the resulting structures have been used as a synthetic dataset. This version of APE-Gen, APE-Gen2.0, restructures the code, adds in post-translational modifications (such as phosphorylations or methylations of amino acids), and includes a web server that is more accessible to biologists and those who would prefer to not use command-line tools.<br><br>
    I have been focusing of fixing minor issues in the workflow and cleaning up the code in order to make it easily modifiable for those wishing to add or alter, and I hope to implement new features such as modelling hydrogens differently (including all, polar, or no hydrogen atoms) and looking into modeling Class II MHCs, which has a different structure from the better understood Class I MHCs.
</p>

[My Final Report](files/finalreport.pdf)


## My Blog

[My Blog](blog.html)
