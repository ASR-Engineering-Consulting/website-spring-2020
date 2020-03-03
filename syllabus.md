---
layout: default
comments: false
keywords:

title: Syllabus
description: For all "Materials and Assignments", follow the deadlines listed on this page, not on Coursera! Assignments are usually due every Tuesday, 30min before the class starts.
buttons:
micro_nav: false
---

## Announcements
- Project meeting logistics have been updated. Each group will meet with their TA 3 times throughout the quarter. See the [project page](/project) for details.
- TA project mentors have been assigned. See [the piazza post](https://piazza.com/class/k533d6ufdfg5dv?cid=327).


## Syllabus

<table id="schedule" class="table table-bordered no-more-tables" style="width: 100%; font-size: 0.8em;">
    <colgroup>
        <col>
        <col>
        <col style="width: 25%;">
        <col style="width: 25%;">
        <col style="width: 50%;">
    </colgroup>
    <thead class="active" style="background-color:#f9f9f9" align="left">
        <th>Event</th>
        <th>Date</th>
        <th>In-class lecture</th>
        <th>Online modules to complete</th>
        <th>Materials and Assignments</th>
    </thead>
    <tbody>
        <tr>
            <td>Lecture&nbsp;1</td>
            <td> 01/07 </td>
            <td>
                <strong>Topics:</strong> <a href="/winter2020/lecture1.pdf">(slides)</a>
                <ul>
                    <li>Class introduction</li>
                    <li>Examples of deep learning projects</li>
                    <li>Course details</li>
                </ul>
            </td>
            <td>
                No online modules. If you are enrolled in CS230, you will receive an email on 01/07 to join Course 1 ("Neural Networks and Deep Learning") on Coursera with your Stanford email.
            </td>
            <td>
                No assignments.
            </td>
        </tr>
        <tr>
            <td id="Module_1" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Neural Networks and Deep Learning</strong> <a href="https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning">(Course 1)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;2</td>
            <td> 01/14 </td>
            <td>
                <strong>Topics: </strong>Deep Learning Intuition <a href="/winter2020/lecture2.pdf">(slides)</a>
            </td>
            <td><strong>Completed modules:</strong>
                <ul>
                    <li>C1M1: Introduction to deep learning <a href="/files/C1M1.pdf">(slides)</a></li>
                    <li>C1M2: Neural Network Basics <a href="/files/C1M2.pdf">(slides)</a></li>
                </ul>
                <strong>Optional Video</strong>
                <ul>
                    <li>Batch Normalization videos from C2M3 will be useful for the in-class lecture.</li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>Introduction to deep learning</li>
                    <li>Neural Networks Basics</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am)</strong>
                <ul>
                    <li>Python Basics with Numpy (Optional)</li>
                    <li>Logistic Regression with a neural network mindset</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;3</td>
            <td> 01/21 </td>
            <td>
                <strong>Topics: </strong>Full-cycle of a Deep Learning Project (no slides)
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C1M3: Shallow Neural Network <a href="/files/C1M3.pdf">(slides)</a></li>
                    <li>C1M4: Deep Neural Networks <a href="/files/C1M4.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Project TA meeting #1 deadline:</strong> meet with any TA to discuss proposal by Sun, 01/26
                <br>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>Shallow Neural Networks</li>
                    <li>Key concepts on Deep Neural Networks</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am):</strong>
                <ul>
                    <li>Planar data classification with a hidden layer</li>
                    <li>Building your Deep Neural Network: step by step</li>
                    <li>Deep Neural Network - Application</li>
                </ul>
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Project Proposal Due</strong></td>
            <td><strong>{{ site.course.project_timeline.proposal | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#proposal">Instructions</a></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td id="Module_2" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization</strong> <a href="https://www.coursera.org/learn/deep-neural-network?specialization=deep-learning">(Course 2)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;4</td>
            <td> 01/28 </td>
            <td>
                <strong>Topics:</strong> Adversarial examples - GANs <a href="/winter2020/lecture4.pdf">(slides)</a>
                <ul>
                    <li>Attacking neural networks with Adversarial Examples and Generative Adversarial Networks</li>
                </ul>
                <strong>Optional Readings:</strong>
                <a href="https://arxiv.org/pdf/1412.6572.pdf">Explaining and Harnessing Adversarial Examples</a>, <a href="https://arxiv.org/pdf/1406.2661.pdf">Generative Adversarial Nets</a>, <a href="https://arxiv.org/pdf/1611.07004.pdf">Conditional GAN</a>, <a href="https://arxiv.org/pdf/1609.04802.pdf">Super-Resolution GAN</a>, <a href="https://arxiv.org/pdf/1703.10593.pdf">CycleGAN</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C2M1: Practical aspects of deep learning <a href="/files/C2M1.pdf">(slides)</a></li>
                    <li>C2M2: Optimization algorithms <a href="/files/C2M2.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>Practical aspects of deep learning</li>
                    <li>Optimization Algorithms</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am):</strong>
                <ul>
                    <li>Initialization</li>
                    <li>Regularization</li>
                    <li>Gradient Checking</li>
                    <li>Optimization</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td id="Module_3" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Structuring Machine Learning Projects</strong> <a href="https://www.coursera.org/learn/machine-learning-projects?specialization=deep-learning">(Course 3)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;5</td>
            <td> 02/04 </td>
            <td>
                <strong>Topics:</strong> AI and Healthcare. Guest Speaker: Pranav Rajpurkar.
                <a href="/winter2020/lecture5_guest.pdf">(guest slides)</a>
                <a href="/winter2020/lecture5.pdf">(main slides)</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C2M3: Hyperparameter Tuning, Batch Normalization <a href="/files/C2M3.pdf">(slides)</a></li>
                    <li>C3M1: ML Strategy (1) <a href="/files/C3M1.pdf">(slides)</a></li>
                    <li>C3M2: ML Strategy (2) <a href="/files/C3M2.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>Hyperparameter tuning, Batch Normalization, Programming Frameworks</li>
                    <li>Bird recognition in the city of Peacetopia (case study)</li>
                    <li>Autonomous driving (case study)</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am):</strong>
                <ul>
                    <li>Tensorflow</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td id="Module_4" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Convolutional Neural Networks</strong> <a href="https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning">(Course 4)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture 6</td>
            <td> 02/11 </td>
            <td>
                <strong>Topics:</strong> Interpretability of Neural Networks
                <a href="/winter2020/lecture6.pdf">(slides)</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C4M1: Foundations of Convolutional Neural Network <a href="/files/C4M1.pdf">(slides)</a></li>
                    <li>C4M2: Deep Convolutional Models <a href="/files/C4M2.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>The basics of ConvNets</li>
                    <li>Deep convolutional models</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am):</strong>
                <ul>
                    <li>Convolutional Model: step by step</li>
                    <li>Convolutional Model: application</li>
                    <li>Keras Tutorial: This assignment is optional.</li>
                    <li>Residual Networks</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Midterm Review</td>
            <td>02/13</td>
            <td></td>
            <td>
                <strong>Midterm review details:</strong>
                <ul>
                    <li>Date & Time: Feb 13, 3:00-4:20pm</li>
                    <li>Location: Thornton 102</li>
                </ul>
            </td>
            <td>
              <strong>Past midterms:</strong>
                <ul>
                    <li>Winter 2018 Midterm (<a href="/files/cs230exam_win18.pdf">without solutions</a>, <a href="/files/cs230exam_win18_soln.pdf">with solutions</a>)</li>
                    <li>Spring 2018 Midterm (<a href="/files/cs230exam_spr18.pdf">without solutions</a>, <a href="/files/cs230exam_spr18_soln.pdf">with solutions</a>)</li>
                    <li>Fall 2018 Midterm (<a href="/files/cs230exam_fall18.pdf">without solutions</a>, <a href="/files/cs230exam_fall18_soln.pdf">with solutions</a>)</li>
                    <li>Winter 2019 Midterm (<a href="/files/cs230exam_win19.pdf">without solutions</a>, <a href="/files/cs230exam_win19_soln.pdf">with solutions</a>)</li>
                    <li>Fall 2019 Midterm (<a href="/files/cs230exam_fall19.pdf">without solutions</a>, <a href="/files/cs230exam_fall19_soln.pdf">with solutions</a>)</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;7</td>
            <td> 02/18 </td>
            <td>
                <strong>Topics:</strong> Deep Learning Strategy (no slides)
                <br>
                <br>
                <strong>Optional Reading:</strong> <a href="https://arxiv.org/pdf/1603.07285.pdf">A guide to convolution arithmetic for deep learning</a>, <a href="https://arxiv.org/ftp/arxiv/papers/1609/1609.07009.pdf">Is the deconvolution layer the same as a convolutional layer?</a>, <a href="https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf">Visualizing and Understanding Convolutional Networks</a>, <a href="https://arxiv.org/pdf/1312.6034.pdf">Deep Inside Convolutional Networks: Visualizing Image Classification Models and Saliency Maps</a>, <a href="https://arxiv.org/pdf/1506.06579.pdf">Understanding Neural Networks Through Deep Visualization</a>, <a href="http://cnnlocalization.csail.mit.edu/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf">Learning Deep Features for Discriminative Localization</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C4M3: ConvNets Applications (1) <a href="/files/C4M3.pdf">(slides)</a></li>
                    <li>C4M4: ConvNets Applications (2) <a href="/files/C4M4.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>Detection Algorithms</li>
                    <li>Special Applications: Face Recognition & Neural Style Transfer</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am):</strong>
                <ul>
                    <li>Car Detection with YOLO</li>
                    <li>Art Generation with Neural Style Transfer</li>
                    <li>Face Recognition</li>
                </ul>
            </td>
        </tr>
        <tr style="background-color:#ffcece" id="midterm">
            <td><strong>Midterm</strong></td>
            <td><strong>{{ site.course.midterm_time }}</strong></td>
            <td></td>
            <td>
                Midterm details
                <ul>
                    <li>Date: Wednesday, Feb 19th</li>
                    <li>Time: 6pm-9pm</li>
                    <li>Location: <a href="https://goo.gl/maps/5uqzXVQmro78421V8">CEMEX Auditorium</a> </li>
                </ul>
            </td>
            <td>
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Project Milestone Due</strong></td>
            <td><strong>{{ site.course.project_timeline.milestone | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td>
                <a href="/project/#milestone">Instructions</a></td>
            <td>
            </td>
            <td>
                <strong>Project TA meeting #2 deadline:</strong> meet with your assigned project TA any time up until the milestone deadline.
            </td>
        </tr>
        <tr>
            <td id="Module_5" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Sequence Models</strong>  <a href="https://www.coursera.org/learn/nlp-sequence-models">(Course 5)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;8</td>
            <td> 02/25 </td>
            <td>
                <strong>Topics:</strong>
                <ul>
                    <li>Career Advice</li>
                    <li>Reading Research Papers</li>
                </ul>
                <strong>Optional Reading</strong>
                <ul>
                    <li><a href="https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf">Dropout: A Simple Way to Prevent Neural Networks from Overfitting</a></li>
                    <li><a href="https://arxiv.org/abs/1608.06993">DenseNet: Densely Connected Convolutional Networks</a></li>
                </ul>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C5M1: Recurrent Neural Networks <a href="/files/C5M1.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>Recurrent Neural Networks</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am):</strong>
                <ul>
                    <li>Building a Recurrent Neural Network - Step by Step</li>
                    <li>Dinosaur Land -- Character-level Language Modeling</li>
                    <li>Jazz improvisation with LSTM</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;9</td>
            <td> 03/03 </td>
            <td>
                <strong>Topics:</strong>
                <a href="/winter2020/lecture9.pdf">(slides)</a>
                <ul>
                    <li>Deep Reinforcement Learning</li>
                </ul>
                <br>
                <strong>Optional Reading:</strong>
                <ul>
                    <li><a href="https://web.stanford.edu/class/psych209/Readings/MnihEtAlHassibis15NatureControlDeepRL.pdf">Human-level control through deep reinforcement learning</a></li>
                    <li><a href="https://deepmind.com/documents/119/agz_unformatted_nature.pdf">Mastering the Game of Go without Human Knowledge</a></li>
                </ul>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C5M2: Natural Language Processing and Word Embeddings <a href="/files/C5M2.pdf">(slides)</a></li>
                    <li>C5M3: Sequence-to-Sequence Models <a href="/files/C5M3.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 8:30am):</strong>
                <ul>
                    <li>Natural Language Processing and Word Embeddings</li>
                    <li>Sequence Models and Attention Mechanism</li>
                </ul>
                <strong>Programming Assignments (due at 8:30am):</strong>
                <ul>
                    <li>Operations on Word Vectors - Debiasing</li>
                    <li>Emojify!</li>
                    <li>Neural Machine Translation with Attention</li>
                    <li>Trigger Word Detection</li>
                </ul >
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;10</td>
            <td> 03/10 </td>
            <td>
                <strong>Topics:</strong>
                <ul>
                    <li>Class wrap-up</li>
                    <li>What's next?</li>
                </ul>
            </td>
            <td></td>
            <td>
                <strong>Optional:</strong>
                <ul>
                    <li>If you’re interested in testing your ML/DL skills or preparing for job interviews in AI, you can take the <a href="https://www.workera.ai/candidates">Workera assessment</a></li>
                </ul>
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Final Poster and Project Report Due</strong></td>
            <td><strong>{{ site.course.project_timeline.poster_and_report | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td>
                Instructions for <a href="/project/#poster">Poster</a> and <a href="/project/#final-report">Project Report</a>
            </td>
            <td>
            <strong>Note: Late days cannot be applied to the final poster and report.</strong>
            </td>
            <td>
                <strong>Project TA meeting #3 deadline:</strong> meet with your assigned project TA any time up until the final report deadline (we suggest as soon as possible).
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Poster Session</strong></td>
            <td><strong>{{ site.course.project_timeline.poster_session }}</strong></td>
            <td></td>
            <td>
                <strong>Poster Session</strong>
                <ul>
                <li> Location: TBD</li>
                </ul>
            </td>
            <td></td>
        </tr>
    </tbody>
</table>

