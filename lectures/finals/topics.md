# Modern Control Paradigms: Term Project Topics and Guidelines

## Introduction

This document serves as a roadmap for students undertaking term projects in the domain of control systems engineering. It differentiates between two primary modes of engagement: **Technical Projects** and **Technical Talks**.

**Technical Projects** involve hands-on work where students are expected to develop, implement, and demonstrate control systems through coding, simulations, or experiments. These projects are typically more practical in nature and require students to produce tangible results that can be showcased.

**Technical Talks**, in contrast, are more theoretical and involve a comprehensive presentation on a specific topic within control systems. These talks require students to research, understand, and explain complex concepts, often reviewing the current state of the art, without necessarily including a practical demonstration or software development.

Students are encouraged to select an approach that aligns with their strengths and interests, and that complements their learning objectives.

## Technical Projects

Students are expected to design, develop, and demonstrate a control system based on the provided list of topics. Each project must be well-documented, illustrating the student's ability to apply control systems theory and principles in a practical setting. In order to facilitate modeling I suggest to use [DARLi](https://github.com/simeon-ned/darli). 

### Project Topics

### Technical Projects / Contribution to Examples

- **MPC/LQR with Highly Articulated Robot**: This project involves the application of model predictive control (MPC) and linear-quadratic regulator (LQR) in the stabilization and control of bipedal robots, which are examples of highly articulated systems.

- **CBF for Position Constraints**: For this project, implement control barrier functions (CBFs) to ensure safety constraints, such as position limits, are maintained in control systems. To gain a better understanding of CBFs, you can [Read about CBFs here](https://arxiv.org/abs/1903.11199).

- **Robust CLF-Based Control**: The goal of this project is to develop control strategies that are robust against uncertainties, using control Lyapunov functions (CLFs). For an introduction to robust CLFs, [Learn about Robust CLFs here](https://www.youtube.com/watch?v=_Tkn_Hzo4AA).

- **Time-Variant LQR**: This project aims to explore the concept of time-variant linear-quadratic regulators and their applications in various control systems. To understand time-varying LQRs, [Understand time-varying LQRs here](https://www.youtube.com/watch?v=S5LavPCJ5vw).

- **Linear Matrix Inequalities**: In this project, you would employ linear matrix inequalities (LMIs) in the design and analysis of feedback control systems, which are prevalent in control theory. To learn more about LMIs in system theory, [Discover LMIs in system theory here](https://www.youtube.com/watch?v=lQ_E0THFBuY).

- **LQR with Quaternions**: Implement LQR control for systems that utilize quaternion representations, such as quadrotors. Quaternions are often used in control applications that involve orientation and rotation. To see an example of LQR being used with quaternions in quadrotors, [Implement LQR with Quaternions and Quadrotors here](https://www.youtube.com/watch?v=AxmE2uTPglg&t=1s).

These projects and resources can serve as a foundation for practical applications in control theory and robotics.
### Grading Criteria for Technical Projects

- **Code Functionality (30%)**: The control system must perform as intended and meet the project objectives.
- **Code Efficiency & Readability (30%)**: Code should be well-structured, optimized, and easy to read, following standard coding conventions.
- **Implementation of Concepts (30%)**: Demonstrated understanding and application of control system theories and principles.
- **Documentation & Comments (10%)**: Comprehensive documentation and comments that explain the code and the design choices made.

## Technical Talks

Students who opt for Technical Talks are required to prepare an in-depth presentation on a chosen control systems topic, providing a theoretical exploration and critical analysis. The talks should be engaging and demonstrate a strong grasp of the subject matter.

### Talk Topics
- **HJ Reachability & CBF**: Hamilton-Jacobi (HJ) reachability analysis and Control Barrier Functions (CBF) are methodologies used to ensure that control systems stay within safe operational boundaries. For an explanation of their relationship, watch [this video](https://www.youtube.com/watch?v=-PzULKLB0D4).

- **Lyapunov Theory with Disturbances and Outputs**: This is a framework for determining the stability of a system, where a Lyapunov function's behavior is used to infer system stability. For systems with disturbances and outputs, check the [lecture slides](https://stanford.edu/class/ee363/lectures/io-lyap.pdf).

- **LQR, iLQR, DDP**: These are optimization strategies for control systems, where LQR is suitable for linear systems and iLQR and DDP cater to non-linear systems. For insights into DDP, view [this lecture](https://www.youtube.com/watch?v=hUf5YhSptLs&list=PLZnJoM76RM6KugDT9sw5zhAmqKnGeoLRa&index=18).

- **Optimizing Rotations**: Optimizing rotations involves calculating the most efficient rotational movements for applications like robotics and aerospace. To learn more, check out [this tutorial](https://www.youtube.com/watch?v=7t9HWMWBq70&t=1s).

- **Differential Flatness**: A property of some control systems that simplifies the planning of trajectories by expressing states and inputs in terms of outputs and their derivatives. See it applied in [this video](https://www.youtube.com/watch?v=5t6t1mA2vnU), with further examples [here](https://www.youtube.com/watch?v=KYdZQBVxYf0&t=2868s).

- **DMD, DMDc, SINDY**: These are techniques for extracting the dynamic patterns of complex systems from data, with DMD and DMDc focusing on linear dynamics and SINDY on nonlinear dynamics. For an introduction to DMD, view [this video](https://www.youtube.com/watch?v=K-7l0q920io) and for SINDY, see [this video](https://www.youtube.com/watch?v=vuJCOfdlN6Q&list=PLMrJAkhIeNNQkv98vuPjO2X2qJO_UPeWR&index=25).

- **Order Reduction in Linear Systems**: This involves simplifying complex linear systems to more manageable sizes while retaining their key characteristics, which is essential for control design and analysis. For a tutorial on this, watch [this video on Model Order Reduction](https://www.youtube.com/watch?v=FsLmBDfwQCY&list=PLMrJAkhIeNNQkv98vuPjO2X2qJO_UPeWR&index=3).

- **System Identification**: The process of building mathematical models based on measured data to design and validate control systems. For a comprehensive guide, visit [this video](https://www.youtube.com/watch?v=6F2YVsT9dOs) and [this lecture](https://underactuated.mit.edu/sysid.html).

- **Koopman Linearization**: A method to analyze nonlinear dynamics by representing them through a linear operator, allowing for the application of linear system theory. For more on this topic, consider the [Koopman playlist](https://www.youtube.com/watch?v=K5CRbC4yqnk&list=PLMrJAkhIeNNSVXUvppZTYNHKQUD-oWys9).

- **Convexifying Plans**: The practice of employing convex optimization for the simplification of planning problems, particularly in the field of aerospace. For an example watch [this video](https://www.youtube.com/watch?v=gwdcIxzp2N4&t=1s)

- **Presentations on Your Thesis**: Share insights from your thesis work, emphasizing the connection to control systems, and engage with your audience by presenting your research objectives, methodology, and findings.

## Additional Information
Students are encouraged to expand beyond these topics and explore other areas within control that pique their interest. Use these suggestions as a springboard to dive deeper into your chosen subject.

### Grading Criteria for Technical Talks

- **Content Mastery (40%)**: Depth of understanding of the chosen topic.
- **Presentation Quality (30%)**: Clarity, organization, and delivery of the presentation.
- **Engagement and Q&A Handling (20%)**: Ability to engage with the audience and respond to questions effectively.
- **Supporting Materials (10%)**: Quality of visuals, slides, and any other materials used to support the presentation.

## Submission Deadlines

- **Abstract Submission**: 20/12/2023
- **Presentation Dates**: 22/12/2023
- **Final Project Submission**: 23/12/2023