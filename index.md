---
layout: default
title: ""
---

<p align="center">
 <img src="{{ '/images/Banner.jpg' | relative_url }}">
</p>

<div style="text-align: justify">
I am Bharath Raghavan, a Postdoctoral Research Associate at the Oak Ridge National Laboratory, one of the foremost supercomputing centers in the world, and my research mission is to accelerate the application of high performance computing to automate drug design and discovery.
<br>
<br>
I have a diverse work/education experience, having been involved with institutions in India, the United States and Germany. I also have a diverse training in computational chemistry, bio- & pharmaceutical chemistry, physical & materials chemistry, machine learning & data science, high performance computing, and the chemical industry.
<br>
<br>
I am involved in research activities dealing with quantum chemistry, machine/deep learning, computational drug design and high-performance computing to push pharmacology to the next generation. Highly scalable quantum simulations, coupled with complex deep learning neural networks, can give us intricate atomic-level insights of pharmaceutically relevant enzyme function. I believe that this deep quantum-level understanding of our biology can greatly streamline the drug design process by promoting the rational and scientific design of inhibitors. The wider promulgation of supercomputing technologies will allow the scientific community to unlock the huge potential of AI-accelerated quantum simulations for pharmacology.
<br>
<br>
Contact me if you wish to collaborate on these exciting ideas!
</div>
<br>
<br>
# My Portfolio

## Software for Highly-Scalable Biochemistry

<p align="center">
  <img src="{{ '/images/Research1.jpg' | relative_url }}" width="90%" height="65%"/>
</p>

<div style="text-align: justify">
I am involved in the <a href="https://mimic-project.org/en/latest/">MiMiC project</a> together with <a href="https://www.fz-juelich.de/profile/carloni_p">Prof. Dr. Paolo Carloni</a>, <a href="https://orbit.dtu.dk/en/persons/jógvan-magnus-haugaard-olsen">Dr. Jógvan Magnus Haugaard Olsen</a> and <a href="https://www.epfl.ch/labs/lcbc/roethlisberger/">Prof. Ursula Röthilsberger</a>. The MiMiC framework is an open-source, general platform that enables the implementation of multiscale computational (bio)chemistry simulation methods through coupling of multiple external programs, designed for massively parallel applications with a multiple-programs multiple-data model. The program is written in a combination of Fortran and C++, and parallelizaed with a hybrid MPI/OpenMP approach. Currently, MiMiC couples the CPMD and GROMACS codes to perform highly scalable QM/MM biomolecular simulations on HPC systems.
<br>
<br>
I am the lead developer of <a href="https://mimic-project.org/en/latest/mimicpy/overview.html">MiMiCPy</a>, an open-source Python toolkit as a companion to MiMiC. The code greatly simplifies the preparation and debugging of MiMiC-based QM/MM input files via a user-friendly interface. It provides an extensive list of command-line tools with an easy-to-use selection language to pick out the QM region. Plugins for PyMOL and VMD alow the selection of complex QM regions visually. MiMiCPy can also be used as a Python library, allowing one to develop complex workflows to set up MiMiC-based QM/MM simulations. The package has been designed with a modular and object-oriented approach. This allows one (i) to easily support new topology and coordinate file formats from different programs, when they become available in MiMiC; (ii) to develop new tools as MiMiC expands its functionalities.
<br>
<br>
I was involved in early efforts to couple MiMiC-QM/MM simulations with machine learning-based force fields. This was carried out as part of the Helmholtz GPU Hackathon 2020 in collaboration with Andrea Rizzi, Florian Schakerth and Viacheslav Bolynkh. I designed a MiMiC data reader for the <a href="https://pubs.acs.org/doi/10.1021/acs.jcim.9b00994">PiNN library</a>, and contributed to parallelization efforts of the tensorflow-based atomic neural network on multiple GPUs. I also contribute to testing, documentation and communication activities related to MiMiC. I spearheaded training activities at the <a href="https://www.cecam.org/workshop-details/1119">CECAM Flagship School on MiMiC</a> held at the École Polytechnique Fédérale de Lausanne (EPFL) on 18 to 22 July 2022 and the MiMiC workshop at the <a href="https://flagship.kip.uni-heidelberg.de/jss/HBPm?m=showAgenda&meetingID=242">Simulate with EBRAINS</a> event held by the Human Brian Project on 10th Nov 2022.
</div>
<br>

## High-Performance Computing & Quantum Chemistry Against Glioma

<p align="center">
  <img src="{{ '/images/Research2.jpg' | relative_url }}" width="90%" height="65%"/>
</p>

<div style="text-align: justify">
I am involved in the Helmholtz European Partnering Project between Forschungszentrum Juelich and Italian Institute of Technology, directly working with Prof. Dr. Paolo Carloni and Dr. Marco De Vivo, and involving Prof. Michele Parrinello, Prof. Guilia Rossetti, and Prof. Bernd Neumaier. The main goal is to apply high performance computing approaches to tackle neurological diseases. I am specifically involved in applying scalable Quantum Mechanics/Molecular Mechanics (QM/MM)-based dynamics to study the IDH1 enzyme catalysis. Variants of IDH1 are involved in glioma and glioblastoma. QM/MM simulations of IDH1 are hoped to lead to an understanding of the catalytic mechanism, and an accurate map of the transition state. This information can be used to suggest transition state analogs, which may be a million times more effective compared to current glioma inhibitors. This will be especially useful in suggesting radiotracers for non-invasive detection of early-stage glioma, an avenue being investigated with our experimental collaborator Prof. Bernd Neumaier.
<br>
<br>
We apply the MiMiC-QM/MM interface (developed within the project mentioned above) to study the dynamics of the IDH1 enzyme. This is the first application of MiMiC to a large, biologically-relavant enzyme. We have showed that system scales efficiently up to an incredible of almost 40,000 cores with Density Function Theory-B3LYP dynamics. This level of scaling has not been reached before for biological simulations at <i>ab-initio</i> level of theory. We hope that this could serve as strong proof of the potential of highly scalable QM/MM to uncover enzyme function, and to design enzyme inhibitors. We are currently working on the simulation of the mutant-IDH1 catalysis, to understand the disease-causing pathway and design transition state analogs against this.
 </div>
<br>
<br>
# My Experience
<br>
<img src="{{ '/images/ornl.png' | relative_url }}"  width="30%" height="15%"/>\
\
**Postdoctoral Research Associate**\
**Duration:** Nov 2024 – Current\
**Location:** Oak Ridge, United States of America\
**Work:** Performed Research on Generative AI and Highly Scalable Quantum Simulations for Biophysics and Computational Drug Design in the National Center for Computational Sciences Division

---

<img src="{{ '/images/fzj.png' | relative_url }}"  width="30%" height="15%"/>\
\
**Doctoral Student**\
**Duration:** Feb 2020 – Feb 2024\
**Location:** Jülich, Germany\
**Advisor:** [Prof. Dr. Paolo Carloni](https://www.fz-juelich.de/profile/carloni_p)\
**Work:** Performed Research Towards Doctoral Thesis within the Computational Biomedicine Institute

---

<img src="{{ '/images/ril.png' | relative_url }}"  width="25%" height="12%"/>\
\
**Graduate Engineering Trainee**\
**Duration:** July 2017 – May 2018\
**Location:** Dahej, India\
**Work:** Process Engineer at the Ethylene Oxide/Ethylene Glycol (EO/EG) Sub-divsion

---

<img src="{{ '/images/hri.png' | relative_url }}"  width="40%" height="20%"/>\
\
**Visiting Student in Physics**\
**Duration:** May – June 2018\
**Location:** Prayagraj, India\
**Advisor:** [Prof. Pinaki Majumdar](https://www.hri.res.in/people/Physics/pinaki)\
**Work:** Tight Binding Simulations of Condensed Matter Systems
<br>
<br>
# My Education
<br>
<img src="{{ '/images/rwth.png' | relative_url }}"  width="40%" height="22%"/>\
\
**Doctor rerum naturalium (Dr. rer. nat.) in Physics**\
**Duration:** Oct 2020 – Aug 2024\
**Location:** Aachen, Germany\
**Advisor:** [Prof. Dr. Paolo Carloni](https://www.fz-juelich.de/profile/carloni_p)\
**Thesis:** High performance Computing-Based QM/MM Simulations for Drug Design: Application to the Non-Invasive Diagnosis of IDH1-Associated Glioma

---

<img src="{{ '/images/cmu.png' | relative_url }}"  width="28%" height="14%"/>\
\
**Master of Science (MS) in Colloids, Polymers and Surfaces**\
**Duration:** Aug 2018 – Dec 2019\
**Location:** Pittsburg, United States of America\
**Advisor:** [Prof. Hyung Kim](https://www.cmu.edu/chemistry/people/faculty/kim.html)\
**Thesis:** Theoretical Study of Transesterification of Cellulose Biopolymer in Ionic Liquids

---

<img src="{{ '/images/rv.png' | relative_url }}"  width="16%" height="8%"/>\
\
**Bachelor of Engineering (B.E.) in Chemical Engineering**\
**Duration:** Aug 2013 – April 2017\
**Location:** Bengaluru, India\
**Advisor:** [Dr. Tribikram Gupta](https://www.rvce.edu.in/ph-faculty-tg)\
**Thesis:** Molecular Dynamics of H<sub>2</sub>/CH<sub>4</sub> Gas Permeation in Nanoporous Graphene
