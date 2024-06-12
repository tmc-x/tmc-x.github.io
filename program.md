---
layout: default
title: Task and Motion Coordination under <br/> Geometric, Dynamic and <br/> Temporal Constraints (TMC+X)
---

### Schedule (Tentative)

| 08:20 to 08:30 | Opening and introduction   |
| 08:30 to 09:00 | **Petter Ögren, Multi-agent Coordination using Behavior Trees**   |
| 09:00 to 09:30 | **Pedro U. Lima, Planning Task and Motion Coordinated Execution from User Requests in Service Robots**  |
| 09:30 to 10:00 | **Hector Garcia de Marina, Resilient Source Seeking with Robot Swarms**  |
| 10:00 to 10:30 | Coffee break |
| 10:30 to 11:00 | **Christos Verginis, Task and Motion Planning of Articulated Robots with Uncertain Dynamics**   |
| 11:00 to 11:30 | **Yulong Gao, Distribution-based CTL Model Checking and its Application to Multi-Agent Control**   |
| 11:30 to 11:50 | **Leonel Rozo, Riemannian Flow-based Robot Learning of Dynamic Motions with Stability Guarantees**   |
| 11:50 to 12:00 | Closing remark  |



### Keynote Talks


### Petter Ögren (Professor, KTH Sweden)

**Title**: **Multi-agent Coordination using Behavior Trees**

**Abstract**: A Behavior Tree (BT) is a hierarchical representation of a control policy that has been shown to be optimally modular. BTs were first used by computer game programmers to provide a convenient way of structuring the AI of so-called non-player characters, and have since gained popularity in robotics and control. Most work so far has been focussed on control of a single entity, but there is a growing interest in using BTs for coordination of larger groups of agents as well. In this talk we will give an overview of how BTs have been used in multi-agent coordination in general, and in particular look at combinations with both model based planners, and different learning approaches.

**Bio**: Petter Ögren was born in Stockholm, Sweden, in 1974. He received the M.S. degree in engineering physics and the Ph.D. degree in applied mathematics from the Royal Institute of Technology (KTH), Stockholm, Sweden, in 1998 and 2003, respectively. In the fall of 2001, he visited the Mechanical Engineering Department, Princeton University, Princeton, NJ. From 2003 to 2012 he worked as a senior scientist and deputy research director in Autonomous Systems at the Swedish Defence Research Agency (FOI). In 2013 he started as an Associate Professor at KTH, and since 2018, he is a Professor at the division of Robotics, Perception and Learning (RPL) at KTH.


### Pedro U. Lima (Professor, Universidade de Lisboa, Portugal)

**Title**: **Planning Task and Motion Coordinated Execution from User Requests in Service Robots**

**Abstract**: Service robots are increasingly expected to comprehend and carry out complex user instructions. This entails not only understanding spoken commands but also engaging in dialogue to clarify instructions when necessary. Once understood, these commands need to be translated into the specific tasks the robot must perform. In the context of speech-based interaction, this process involves multiple stages, including speech recognition, translation to text, capturing relevant facts and goals, asking for further information when necessary, and finally, planning the execution of corresponding task(s). An underlying assumption is that the planner will use as plan components functionalities corresponding to modules that the robot can execute. It's important to note that this pipeline's significance grows as robots become capable of comprehending a wider range of commands. Central to this pipeline is the representation of knowledge. In this presentation, Currently, we're using Petri net-based models for plan representation. This enables representing and reasoning over action duration uncertainty, through established algorithms used in Markov Decision Processes (MDPs), as these Petri net models can be transformed into equivalent MDPs. These MDPs can be solved using reinforcement learning or dynamic programming, producing a policy that maps states to functionalities. Tools we have designed for stochastic Petri net development allow synthesizing policies under this representation and executing them within the Robot Operating System (ROS). This involves coordinating subsystems required for task execution. An integral aspect of this presentation is elucidating knowledge representation in Petri nets and its dynamic update as the robot enacts its plan, informed by sensor inputs. To underscore these concepts, I will showcase their application in our domestic service robots. This will include demonstrations of task execution prompted by user commands, all set in realistic scenarios, e.g., apartments with furniture, different types of objects and humans, similar to those encountered in RoboCup@Home, a robot competition where the ISR/IST SocRob@Home team actively participates.

**Bio**: Pedro U. Lima got his Ph.D. (1994) in Electrical Engineering at RPI, NY, USA. Currently, he is a Professor at Instituto Superior Técnico, Universidade de Lisboa, and a researcher of the Institute for Systems and Robotics, where he is the coordinator of the Intelligent Robots and Systems group and Deputy Vice-President for Scientific Affairs. He is the co-author of two books, and member of the Editorial Board of the Elsevier’s Journal of Robotics and Autonomous Systems. His research interests lie in the areas of discrete event models of robot tasks and planning under uncertainty, with applications to networked robot systems. Pedro Lima was a Trustee of the RoboCup Federation (2003-2012), and was the General Chair of RoboCup2004, held in Lisbon. He was President and founding member of the Portuguese Robotics Society, was National Delegate to EU and ESA Space Robotics programs and was awarded a 6-month Chair of Excellence at the Universidad Carlos III de Madrid, Spain in 2010. He has also been very active in the promotion of Science and Technology to the society, through the organization of Robotics events in Portugal, including the Portuguese Robotics Open since 2001.


### Hector Garcia de Marina (Assistant Professor, Universidad de Granada, Spain)

**Title**: **Resilient Source Seeking with Robot Swarms**


**Abstract**: We present a solution for locating the source, or maximum, of an unknown scalar field using a swarm of mobile robots. Unlike relying on the traditional gradient information, the swarm determines an ascending direction to approach the source with arbitrary precision. The ascending direction is calculated from field strength measurements at the robot locations and their relative positions concerning the swarm centroid. Rather than focusing on individual robots, we focus the analysis on the density of robots per unit area to guarantee a more resilient swarm, i.e., the functionality remains even if individuals go missing or are misplaced during the mission. We reinforce the algorithm's robustness by providing sufficient conditions for the swarm shape so that the ascending direction is almost parallel to the gradient. The swarm can respond to an unexpected environment by morphing its shape and exploiting the existence of multiple ascending directions. Finally, we validate our approach numerically with hundreds of robots. The fact that a large number of robots with a generic formation always calculate an ascending direction compensates for the potential loss of individuals.


**Bio**: Héctor García de Marina received the Ph.D. degree in systems and control from the University of Groningen, The Netherlands, in 2016.,He was a Postdoctoral Research Associate with the Ecole Nationale de l'viation Civile, Toulouse, France, and an Assistant Professor with the Unmanned Aerial Systems Center, University of Southern Denmark, Odense, Denmark. Since 2022, he has been a Ramán y Cajal Researcher with the Department of Computer Engineering, Automation and Robotics, and with CITIC, Universidad de Granada, Spain. He is an Associate Editor for IEEE Transactions on Robotics. His current research interests include multiagent systems and the design of guidance navigation and control systems for autonomous vehicles.


### Christos Verginis (Assistant Professor, Uppsala Uni., Sweden)

**Title**: **Task and Motion Planning of Articulated Robots with Uncertain Dynamics**

**Abstract**: Motion and task planning constitutes fundamental problems when it comes to control of autonomous systems. Algorithms often operate at different levels of abstractions, reasoning about high-level task plans as well as collision-free motion control schemes. The problem is significantly complicated when taking into account articulated systems with uncertain dynamics. Articulated systems, such as robotic manipulators, often have to navigate among narrow passages in obstacle-cluttered workspaces. At the same time, such systems usually evolve subject to highly nonlinear dynamics that cannot be accurately modelled, contain a large variety of uncertain dynamic parameters, and suffer from unknown exogenous disturbances. In this talk, I will talk about how we can overcome such issues and develop motion planners that solve the motion-planning problem for articulated systems with uncertain dynamics. I will further elaborate on how we can use such results on task-planning subject to tasks expressed as timed temporal logic specifications.

**Bio**: Christos Verginis is an assistant Department of Electrical Engineering, Uppsala University, Sweden. He received the MEng degree in Electrical and Computer Engineering and the MSc degree in Automatic Control Systems and Robotics both from National Technical University of Athens (NTUA) in 2013 and 2015, respectively. He received the PhD in Electrical Engineering from KTH Royal Institute of Technology (Stockholm) under the guidance of Prof. Dimos Dimarogonas and Prof. Danica Kragic. His PhD Thesis involved planning and control of multi-robot manipulator-endowed systems. His PhD thesis was awarded the EECI PhD award on Control for Complex and Heterogeneous Systems 2021 and was selected to be one of the finalists for the EuRobotics Georges Giralt PhD award 2021.


### Yulong Gao (Assistant Professor, Imperial College London, UK)

**Title**: **Distribution-based CTL Model Checking and its Application to Multi-Agent Control**

**Abstract**: In this talk, we will discuss the computation tree logic (CTL) model checking for finite-state Markov decision processes (MDPs) over the space of their distributions. Unlike the standard probabilistic CTL (PCTL), we use CTL to specify properties over the space of distributions, which provides an alternative way to express probabilistic requirements and in particular enables to express distinctive semantics. We then propose reachability-based CTL model checking algorithms over distribution spaces, as well as computationally tractable, sampling-based procedures for computing the relevant reachable sets. We finally apply our algorithm to synthesize control strategy to multi-agent swarm system.

**Bio**: Bio: Yulong Gao is a Lecturer (Assistant Professor) at the Department of Electrical and Electronic Engineering, Imperial College London. He received the B.E. degree in Automation in 2013, the M.E. degree in Control Science and Engineering in 2016, both from Beijing Institute of Technology, and the joint Ph.D. degree in Electrical Engineering in 2021 from KTH Royal Institute of Technology and Nanyang Technological University. He was a Researcher at KTH from 2021 to 2022 and a postdoctoral researcher at Oxford from 2022 to 2023. His research interests include formal verification and control, machine learning, and applications to safety-critical systems.

### Leonel Rozo (Lead Scientist, Bosch center for AI; Universität Tübingen, Germany)

**Title**: **Riemannian Flow-based Robot Learning of Dynamic Motions with Stability Guarantees**

**Abstract**: Unstructured environments and intricate robot maneuvers pose challenges for traditional robot learning models. This talk explores the potential of generative models, particularly continuous normalizing flows, to capture the complexities of desired robot behaviors (e.g., high-dimensionality, multimodal actions, etc). These powerful models are expressive enough to learn complex robot motion skills, including movements on Riemannian manifolds. We will delve into how flow-based models can be leveraged to learn these dynamic skills while introducing strong stability guarantees. This approach enhances controlled generalization capabilities in robot learning frameworks.

**Bio**: Leonel Rozo received the B.Sc. degree in mechatronics engineering from the Nueva Granada Military University Bogotá, Colombia, in 2005, the M.Sc. degree in automatic control and robotics, and the Ph.D. degree in robotics from the Polytechnical University of Catalonia, Barcelona, Spain, in 2007 and 2013, respectively.,He is a Team Leader with the Department of Advanced Robotics, Istituto Italiano di Tecnologia since 2016, where he was a Postdoctoral Researcher from 2013 to 2016. From 2007 to 2012 he carried out his research on force-based manipulation tasks learning at the Institut de Robòtica i Informàtica Industrial (CSIC-UPC). From 2016 to 2018 he led the Learning and Interaction Group at the department of Advanced Robotics in the Italian Institute of Technology (IIT). He joined IIT in 2012, first as a research fellow and then as postdoctoral researcher in 2013 under the mentorship of Sylvain Calinon. In 2017 he was awarded an individual fellowship from the highly-competitive call Marie Skłodowska-Curie actions for his project proposal DRAPer. He is currently a lead research scientist in the Bosch Center for Artificial Intelligence (BCAI) and leader of Industry-on-Campus group on Geometric Machine Learning for Motion and Interaction at the University of Tübingen. His research interests include robot programming by demonstration, physical human-robot interaction, machine learning, and optimal control for robotics.

<style>
    h1,h2 {
        line-height:1.2;
    }
    header {
      margin:0px;
    }
    .btn {
      margin-top:0em;
      margin-bottom:-1em;
    }
    .project-tagline {
      margin-top:0.5em;
      margin-bottom:0.8em;
    }
    @media screen and (min-width: 64em) { .page-header { padding: 2.5rem 0rem; } }
    @media screen and (min-width: 42em) and (max-width: 64em) { .page-header { padding: 1.5rem 0rem; } }
    @media screen and (max-width: 42em) { .page-header { padding: 1rem 0rem; } }
</style>
