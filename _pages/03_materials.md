---
title: Materials
author: Simeon Nedelchev
date: 2022-01-03
category: outline
layout: post
permalink: /info/materials.html
---

This course is presented as a series of **interactive lectures** that combine basic Python code examples with theoretical discussion. Simply open the link in your browser to view the slides; we are also working on making the slides available in a code-free HTML format. If you want to follow along with the lectures interactively (with the ability to run the code), you'll need to install [Python's rise](https://rise.readthedocs.io/en/stable/) and download the jupyter-notebook version of the slides.


> ##### Format of Slides and Notes
>
>The majority of the slides also have accompanying notes that can be viewed online or downloaded as a pdf (though it should be noted that the pdf is automatically generated and may contain some errors). In addition, we have made the jupyter notebooks available on [google colab](https://colab.research.google.com/), so you can try out the interactive components of the course right in your browser without the need for any additional installations.
{: .block-tip }


<!-- ### Lectures -->

---- 

## **Part 1**: Introduction to Modeling, System Analysis and Control  
 
---- 

### **Lecture 1**: Modeling and State Space 
[1_slides_online]: https://simeon-ned.github.io/mcp/lectures/01_modeling/01_modeling.slides.html
[1_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/01_modeling/01_modeling.ipynb
[1_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/01_modeling/01_modeling.pdf
[1_notes_online]: https://simeon-ned.github.io/mcp/lectures/01_modeling/01_modeling.html

**Description:** The introduction to modeling and state space representation, the mechanical systems, several examples of state space models


<div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][1_slides_online], [jupyter notebook][1_slides_jupyter]|**Notes:** [online][1_notes_online], [pdf][1_notes_pdf]|

</div>


<!-- **Supplementary material:** 
python code, jupyter notebook and google colab on different aspects of simulation   -->

---- 


### **Lecture 2**: Basics of Analysis and Control
[2_slides_online]: https://simeon-ned.github.io/mcp/lectures/02_linear_analysis_and_fb/02_linear_analysis_and_fb.slides.html
[2_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/02_linear_analysis_and_fb/02_linear_analysis_and_fb.ipynb
[2_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/02_linear_analysis_and_fb/02_linear_analysis_and_fb.pdf
[2_notes_online]: https://simeon-ned.github.io/mcp/lectures/02_linear_analysis_and_fb/02_linear_analysis_and_fb.html
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** The basics of analysis and control of linear and nonlinear systems, stability, pole placement, linearization and lyapunov analysis


<div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][2_slides_online], [jupyter notebook][2_slides_jupyter]|**Notes:** [online][2_notes_online], [pdf][2_notes_pdf]|

</div>

**Supplementary material:** 
1. [Linearization based control of cart pole system](https://colab.research.google.com/drive/1F4FbgGSjZ-rxDbnQbZft2G6R_-MC18Ld) 
<!-- 2. Sampling based region of attraction: python code, jupyter notebook and [google colab](https://colab.research.google.com/drive/1F4FbgGSjZ-rxDbnQbZft2G6R_-MC18Ld)   -->


---- 

### **Lecture 3**: Lyapunov Stability Theory
[3_slides_online]: https://simeon-ned.github.io/mcp/lectures/03_lyapunov/03_lyapunov.slides.html
[3_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/03_lyapunov/03_lyapunov.ipynb
[3_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/03_lyapunov/03_lyapunov.pdf
[3_notes_online]: https://simeon-ned.github.io/mcp/lectures/03_lyapunov/03_lyapunov.html
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** Introduction to the stability analysis over nonlinear systems, Lyapunov direct method with applications to regional analysis (basin of attraction and invariant sets)

<div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][3_slides_online], [jupyter notebook][3_slides_jupyter]|**Notes:** [online][3_notes_online], [pdf][3_notes_pdf]|

</div>

<!-- **Supplementary material:** 
1. Linearization based control of cart pole system: python code, jupyter notebook and [google colab](https://colab.research.google.com/drive/1F4FbgGSjZ-rxDbnQbZft2G6R_-MC18Ld) 
2. Sampling based region of attraction: python code, jupyter notebook and [google colab](https://colab.research.google.com/drive/1F4FbgGSjZ-rxDbnQbZft2G6R_-MC18Ld)   -->


---- 

---- 

## **Part 2**: Optimization in Control
 
---- 

### **Lecture 4**: Optimal Control, LQR
[4_slides_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.slides.html
[4_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.ipynb
[4_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.pdf
[4_notes_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.html
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** The notion of Optimal Control. Bellman optimality, Linear case: LQR controller, Riccatti equations, relation between value and Lyapunov functions 

<div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][4_slides_online], [jupyter notebook][4_slides_jupyter]|**Notes:** [online][4_notes_online], [pdf][4_notes_pdf]|

</div>

**Supplementary material:** 
1. [Linearization based LQR control of cart pole system](https://colab.research.google.com/drive/1A5T-BBmXUtNmghc8Io1fr90KLEQw9PUO) 
2. [Example of LQR design for satellite maneuver](https://colab.research.google.com/drive/1HtwXMTESG5IDhD2Zo40m-ME3aJJxX9K-#scrollTo=Il8RG8NGQdtw)  


---- 



### **Lecture 5**: Model Predictive Control
[5_slides_online]: https://simeon-ned.github.io/mcp/lectures/05_mpc/05_mpc.slides.html
[5_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/05_mpc/05_mpc.ipynb
[5_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/05_mpc/05_mpc.pdf
[5_notes_online]: https://simeon-ned.github.io/mcp/lectures/05_mpc/05_mpc.html
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** Finite horizon LQR as leas squares. Incorporating constraints in to optimal linear control, quadratic programming, receding horizon and online planning as controller.

<div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][5_slides_online], [jupyter notebook][5_slides_jupyter]|**Notes:** [online][5_notes_online], [pdf][5_notes_pdf]|

</div>

**Supplementary material:**  
1. [CVXPY based linear MPC over linearized cart pole](https://colab.research.google.com/drive/1lxto-BktBLRuiLL_6SphZf4uZGAI-X-H) 


---- 

### **Lecture 6**: Trajectory Optimization
[6_slides_online]: https://simeon-ned.github.io/mcp/lectures/06_trajectory_optimization/06_trajectory_optimization.slides.html
[6_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/06_trajectory_optimization/06_trajectory_optimization.ipynb
[6_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/06_trajectory_optimization/06_trajectory_optimization.pdf
[6_notes_online]: https://simeon-ned.github.io/mcp/lectures/06_trajectory_optimization/06_trajectory_optimization.html
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** Trajectory optimization over nonlinear systems, finite horizon optimal control, nonlinear optimization. Differential flatness. 

<div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][6_slides_online], [jupyter notebook][6_slides_jupyter]|**Notes:** [online][6_notes_online], [pdf][6_notes_pdf]|

</div>

**Supplementary material:** 
1. [Swing-up for cart pole with trapezoidal collocation](https://colab.research.google.com/drive/1xEtJr_6wXQrS5yWPV9JwyIQtkcJdMnJz) 
2. [Soft landing trajectory for 1-DoF simplified model of Apollo 11, adding time to decision variables](https://colab.research.google.com/drive/15yK1DjHp5oh92NAdGjhbmQCN0iZqkh9p)


---- 
### **Lecture 7**: Linear Matrix Inequality in Control
<!-- [4_slides_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.slides.html
[4_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.ipynb
[4_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.pdf
[4_notes_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.html -->
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** Semi-definite programming, Lyapunov based control via linear matrix inequalities


<!-- <div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][6_slides_online], [jupyter notebook][6_slides_jupyter]|**Notes:** [online][6_notes_online], [pdf][6_notes_pdf]|

</div> -->

> The content of this lecture is in progress
{: .block-danger }

---- 
### **Lecture 8**: Control Lyapunov and Barrier Functions
<!-- [4_slides_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.slides.html
[4_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.ipynb
[4_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.pdf
[4_notes_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.html -->
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** The notion of Control Lyapunov Functions, Sontag Formula, Control as QP, Safety, Barrier Method and CBF


<!-- <div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][6_slides_online], [jupyter notebook][6_slides_jupyter]|**Notes:** [online][6_notes_online], [pdf][6_notes_pdf]|

</div> -->

> The content of this lecture is in progress
{: .block-danger }

---- 
## **Part 3**: System Identification, Model Reduction and Data Driven Control

---- 

### **Lecture 9**: Basics of System Identification and Parameter Estimation
<!-- [4_slides_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.slides.html
[4_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.ipynb
[4_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.pdf
[4_notes_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.html -->
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** The notion of System Identification


<!-- <div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][6_slides_online], [jupyter notebook][6_slides_jupyter]|**Notes:** [online][6_notes_online], [pdf][6_notes_pdf]|

</div> -->

> The content of this lecture is in progress
{: .block-danger }

---- 

### **Lecture 10**: System Identification Methods 
<!-- [4_slides_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.slides.html
[4_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.ipynb
[4_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.pdf
[4_notes_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.html -->
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** ERA, SINDY, ETC 


<!-- <div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][6_slides_online], [jupyter notebook][6_slides_jupyter]|**Notes:** [online][6_notes_online], [pdf][6_notes_pdf]|

</div> -->

> The content of this lecture is in progress
{: .block-danger }

---- 

### **Lecture 11**: Data Driven Linearization 
<!-- [4_slides_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.slides.html
[4_slides_jupyter]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.ipynb
[4_notes_pdf]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.pdf
[4_notes_online]: https://simeon-ned.github.io/mcp/lectures/04_lqr/04_lqr.html -->
<!-- [2_notes_colab]: https://simeon-ned.github.io/mcp/lectures/02_analysis_and_feedback/02_analysis_and_feedback.slides.html -->


**Description:** Koopman, Dual Faceted Linearization 


<!-- <div class="table-wrapper" markdown="block">

|:-:|:-:|
|**Slides:** [online][6_slides_online], [jupyter notebook][6_slides_jupyter]|**Notes:** [online][6_notes_online], [pdf][6_notes_pdf]|

</div> -->

> The content of this lecture is in progress
{: .block-danger }


---- 

<!-- > ##### NOTE -->
>
> The lecture material is continually revised and updated, and over time, additional information will be made available on this site that was not covered in class (primarily due to time constraints).
{: .block-warning }
