---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
**Bangladesh University of Engineering and Technology (BUET)** \
*B.Sc. in Computer Science and Engineering* \
April 2018 - May 2023


<style> 
    table { 
        border: none; 
        border-collapse: collapse; 
    } 
    td, th, tr { 
        border: none; 
    }
</style>

Notable Courses:
<table>
  <tr>
      <td>
        <b>CSE 305: Computer Architecture</b>
        <br>
        Information & Instructions Representation, Processor & Control Unit Design, Memory, Cache
      </td>
      <td>
        <b>CSE 309: Compiler</b>
        <br>
        Lexical, Syntax, Semantic Analysis, Intermediate Code Generation, Code Optimazation
      </td>
  </tr>
  <tr>
    <td>
      <b>CSE 321: Computer Networks</b>
      <br>
      Transport Protocols, Routing Algorithm, Domain Name System, Cryptography
    </td>
    <td>
      <b>CSE 471: Machine Learning</b>
      <br>
      Supervised, Unsupervised, Reinforcement Learning, Neural Networks, Deep Learning
    </td>
  </tr>
  <tr>
    <td>
      <b>CSE 409: Computer Graphics</b>
      <br>
      Raster Graphics, 3D Modeling & Rendering, Illumination, Shading & Textures
    </td>
    <td>
      <b>CSE 461: Algorithm Engineering</b>
      <br>
      Computational Complexity, Approximation Algorithms, Randomized Algorithms
    </td>
  </tr>
  <tr>
    <td>
      <b>CSE 313: Operating System</b>
      <br>
      Process, Inter-Process Communication, Scheduling, Memory Management, File Systems
    </td>
    <td>
      <b>CSE 405: Computer Security</b>
      <br>
      Cryptography, Applications Securtiy, Network Security, Security Attacks
    </td>
  </tr>
  <tr>
    <td>
      <b>CSE 423: Fault Tolerance Systems</b>
      <br>
      Fault Tolerant Architectures, Fault Detection, Fault Modeling, Faults in Memory, Performance Monitoring
    </td>
    <td>
      <b>HUM 477: Sociology for Science and Technology</b>
      <br>
      Social Research Methods, Social Impact Assessment, Globalization
    </td>
  </tr>
  <tr>
    <td>
      <b>MATH 247: Linear Algebra</b>
      <br>
      Gaussian Elimination, Euclidean n-space, Linear Transformations, Laplace & Fourier Analysis
    </td>
    <td>
      <b>MATH 145: Calculus</b>
      <br>
      Differential Calculus, Integral Calculus, Ordinary Differential Equations
    </td>
  </tr>
</table>


Work experience
======
**Therap Bd Ltd** \
*Database Engineer* \
August 2023 - Current

Therap delivers Software as a Service (SaaS) to government and private organizations worldwide, specifically across the USA and Canada, that support individuals with intellectual and developmental disabilities. In this role, I carry out the following responsibilities:

- **Custom Reports:** I created SQL queries to produce health data reports and optimized and tuned their performance by reviewing and analyzing user requirements.
- **Patching:** I applied the latest patches to single Instance, container oracle databases, and RAC systems.
- **R&D:** I conducted extensive research and development on the latest versions of Goldengate, SQLTxplain, and DBSAT. I also performed R&D improving the performance, security, and functionality of Oracle’s database products and tools such as TDE, database partitioning, in-memory processing and oracle audit vault.
- **Scripting:** I designed and implemented scripts in Shell, Python, and Java to automate various DBA tasks.
- **Training:** I mentored junior engineers by thoroughly explaining different modules of the software and visually illustrating the database structure and functionality.

  
Conferences & Talks
=====
**[EAI MobiQuitous 2023 - 20th EAI International Conference on Mobile and Ubiquitous Systems: Computing, Networking and Services](https://mobiquitous.eai-conferences.org/2023/)** \
*RMIT University, Melbourne, Australia* \
November 14-17, 2023

Presented our research accepted in the conference alongside my co-author

**[NSysS 2023 - 10th International Conference on Networking, Systems and Security](https://cse.buet.ac.bd/nsyss2023/)** \
*BUET, Dhaka, Bangladesh* \
December 21-23, 2023

Presented our poster accepted in the conference alongside my co-author

**1st International Science Conference for Women - 2023** \
*Pan Pacific Sonargaon, Dhaka, Bangladesh* \
February 15-16, 2023

Presented my poster accepted in the conference


Honors & Awards
=====
- [2018] **BUET Admission Test Merit Scholarship**
- [2017] **National Higher Secondary School Merit Scholarship by the Government of Bangladesh** \
*Stood 2nd among the girls in Dhaka Board. Talent Pool Scholarship, a scholarship for excellent result in Bangladesh’s higher secondary school exams*
- [2015] **National Secondary School Merit Scholarship by the Government of Bangladesh** \
*Stood 5th among the girls in Dhaka Board. Talent Pool Scholarship, a scholarship for excellent result in Bangladesh's secondary school exams.*
- [2009] **Primary School Merit Scholarship by the Government of Bangladesh** \
*Talent Pool Scholarship*

Other Experiences
=====
- Active Member of [Bangladeshi Women in Computer Science and Engineering (BWCSE)](https://bwcse.wordpress.com/)
- Participated in Bangladesh Math Olympiad (BDMO) several times
- Mentored two undergraduate students in research projects
- Tutored 9th to 12th grades students for six years


Technical Skills
======
- **Languages:** C/C++, Python, Java, Javascript, MySQL, x86 Assembly, Bison/Flex, Bash
- **Frameworks:** Oracle DBMS, PyTorch, TensorFlow, Docker, Django, NodeJs, React, React-Native, JavaFx, Firebase,  NS3, xv6, Git, LaTeX, Wireshark
- **Libraries:** Sklearn, Pandas, Matplotlib, Seaborn


Publications
======
  <ul>
  {% for post in site.publications reversed %}
    <li> {{ post.title }} </li>
  {% endfor %}
  </ul>


Research Experience
======
  <ul>
  {% for post in site.teaching reversed %}
    <li> {{ post.title }} </li>
  {% endfor %}
  </ul>

