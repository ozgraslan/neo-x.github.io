# Course in Robot learning

<div align="center">     <table align="center">        <tr>    
<td width="33%">   <img width="100%" src="/assets/projects/SMiRL/vizdoom/vizdoom_dtl.gif"> </td>  
<td width="33%">   <img width="100%" src="/assets/projects/DiscoRL/DisCoRL.png"> </td>
<td width="33%">   <img width="100%" src="/assets/projects/ReLMM/complex_room_short.gif"> </td>
</tr>

<tr>    

<td width="33%">   Learning from images </td>
<td width="33%"> Learning reward functions </td>
<td width="33%">   Learning in the real world </td>

</tr> </table></div>

I teach a course on robot learning! This course focuses on deep reinforcement learning methods and their application to robotics. <a href="https://diro.umontreal.ca/public/FAS/diro/Documents/1-Programmes-cours/Horaires/cours2022Hiver2Cyc.html">Here</a> is a link to where you can find the course offered on the DIRO web page as IFT 6163. 

Learning methods such as deep reinforcement learning have shown success in solving simulated planning and control problems but struggle to produce diverse, intelligent behaviour, on robots. This class aims to discuss these limitations and study methods to overcome them and enable agents capable of training autonomously, becoming learning and adapting systems that require little supervision. By the end of the course, each student should have a solid grasp of different techniques to train robots to accomplish tasks in the real world. These techniques covered in the course include but are not limited to reinforcement learning, batch RL, multi-task RL, model-based RL, Sim2Real, hierarchical RL, goal conditioned RL, multi-Agent RL, the fragility of RL, meta-level decision making and learning reward functions.

##Target and objectives of the course

Learn the fundamental concepts of machine learning for robotics applications. Such concepts are considered advanced and require a good foundation in machine learning, deep learning and reinforcement learning. This involves: 

- Becoming familiar with the main types of machine learning models for a control policy (from model-based to model-free)
- Developing the ability to read research articles, contextualize them and develop a critical mind;
- Develop presentation skills;
- Develop their research autonomy in machine learning.
- Develop skills related to the strengths and weaknesses of current machine learning methods when being applied to real-world problems.

## Prerequisites of the course

You must have completed the following courses before taking my course.
-  <a href="https://mitliagkas.github.io/ift6390-ml-class/">IFT 6390, Fundamentals of machine learning</a>

The course will also use Python heavily. I will assume familiarity with linear algebra, probability, statistics, planning, optimization, and operating systems (e.g. multi-threading and memory management). You also need to be able to read and understand research papers from NeurIPS, RSS, ICRA, CoRL, and ICLR.  

## Lectures covering topics related to learning robots as well as programming assignments and a final project.

The objectives of the assignments and final projects will be: 

- Software knowledge: Learning about the available software that is used for deep reinforcement learning.
- Analysis skills: Collecting proper statistics of results and using server computers and docker to reproduce experiments and validate results.
- Proposal of a new idea to explore for the final project based on the lectures;
- Learn how to understand the potential of a method in the real world (positive or negative, social and environmental);
- Exploration with final project: More free-form investigation of advanced topics from class that produces reusable code, reproducible results and a written report.
- Estimation of the impact that the new idea could have in an industrial context;

The final project will be achieved as a team of two. Research in academia and industry involves working with others to achieve research goals. This project will evaluate the students’ ideas, research process understanding, teamwork, and presentation.

Regarding the lectures, the instructor will provide live lectures on the topics each week, focusing on their understanding, application, and limitations.

## EVALUATIVE APPROACH AND WEIGHTING (indicative only)
- 40%: Programming assignments. (This is needed to provide skills necessary to perform a good final project in the class)
- 10%: Class participation and discussing readings.
- 15%: Midterm on concepts
- 35%: Final project

### Programming Assignments

The programming assignments cover topics that are important to perform research on combining machine learning and robots. They will cover:

- Behaviour cloning and imitation learning
- Model-free (PPO) and model-based RL methods (DDPG or PETS).
- Exploration and pretraining methods, such as HRL and Goal conditioned RL.
- Learning reward functions (VICE, un/smi-supervised RL)

The assignments are also designed to familiarize students with the software needed to perform research:

- Deep learning libraries, such as pytorch or tensorflow
- Hardware constraints when working with real robots (power, compute, mechanical limits)
- Distributed computing for running proper experiments
- Visualization and analysis (the most important part)

### Final Project

The final project is designed to let students spread there wings and apply the learn skills in an area of interest of the students while digging deeper into the concepts. Your project does not need to use real robot hardware but there are options to get hardware for this class. Each project will start with a proposal that will ensure the right scope for each project. However, to provide some ideas on the scope a few examples are given below.

- Re-implement a method in a new deep learning framework
- Re-implement a method in a paper that did not release code (shame on them)
- Choose a robot to get and train a model to make it solve a task, like walk.
- Investigate a new method that improves exploration
- Investigate a new method for learning an improved representation for learning on robots.
- Study Sim2Real by learning and transferring policies to another simulation or real robot hardware.
- Perform a literature review of Sim2Real papers.

Some robot ideas for projects

- [Hexapod](https://www.trossenrobotics.com/phantomx-ax-hexapod.aspx) 
- [iRobot](https://edu.irobot.com/what-we-offer/create-robot)
- [PiCrwaler](https://www.sunfounder.com/products/picrawler-robot-kit)
- [RobotKity](https://www.robotshop.com/en/petoi-nybble-open-source-robotic-cat.html)


## Resources

Some content related to the course that will be helpful to review.

### Other Related Courses

- <a href="http://rail.eecs.berkeley.edu/deeprlcourse/">Deep reinforcement learning with Sergey Levine</a>
- <a href="https://www.coursera.org/learn/machine-learning">Machine learning with Andrew Ng</a>
- <a href="https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/">Machine learning with Nando de Freitas</a>
- <a href="https://cs231n.github.io/">Neural networks with Andrej Karpathy</a>
- <a href="https://www.davidsilver.uk/teaching/">Reinforcement learning with David Silver</a>
- <a href="https://cs330.stanford.edu/">Deep multi-task and meta learning with Chelsea Finn</a>  

### Relevant Textbooks

               
- <a href="http://www.deeplearningbook.org/">Ian Goodfellow and Yoshua Bengio and Aaron Courville, Deep Learning</a>
- <a href="http://incompleteideas.net/book/the-book-2nd.html">Sutton & Barto, Reinforcement Learning: An Introduction (2nd edition)</a>
- <a href="http://www.ualberta.ca/~szepesva/RLBook.html">Szepesvari, Algorithms for Reinforcement Learning</a>
- <a href="http://www.athenasc.com/dpbook.html">Bertsekas, Dynamic Programming and Optimal Control, Vols I and II</a>
- <a href="http://www.wiley.com/WileyCDA/WileyTitle/productCd-0471727822.html">Puterman, Markov Decision Processes: Discrete Stochastic Dynamic Programming</a>
- <a href="http://adp.princeton.edu/">Powell, Approximate Dynamic Programming</a>
