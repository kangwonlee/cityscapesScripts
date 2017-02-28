# Call for Abstracts and Participation


Deep learning, and in particular convolutional neural networks, has become the main component of many intelligent vehicle algorithms. Jointly with the explosive growth in the available amount of driving data these data-driven algorithms have certainly enabled the next generation of platforms for reliable autonomous driving as evidenced by the algorithms used by a large number of companies like MobilEye, AutoX, Zoox, Toyota Research, General Motors, Volkswagen, and Daimler among many others. The goal of this workshop on deep learning for vehicle perception (as a second edition of the Deep-Driving workshop held in conjunction with IV2016 for further information) is to foster discussion and to accelerate the study of deep architectures in autonomous driving problems with a focus on the efficiency of the algorithms.

More precisely, the goal of the second edition of the Deep-Driving workshop is two fold. First, to foster discussion and to accelerate the study of the use of deep architectures in autonomous driving problems. Deep learning has become the main component of many computer vision algorithms. However, efficient algorithms working on real-world driving environments have specific challenges (e.g., varying acquisition conditions or hardware constraints) that still need to be addressed. The second goal of the workshop is to foster progress on network efficiency which is a current necessity for practical intelligent vehicles and robotics in general. To achieve this second goal a scene labeling challenge will be organized along the workshop to emphasize this specific. Interested participants will receive video snippets from several European cities for processing. Details will be announced soon.

The workshop program will include invited talks from different areas within industry and academia to highlight address the main challenges within this topic and will also invite the presentation of extended abstracts to encourage discussion related to the last advances in this area. Moreover, following with the experience of the first edition of the workshop, we will provide hands-on-experience towards the use of deep learning algorithms. Finally, during the workshop, the winners of the challenge will be announced.

In summary, with the second edition of this workshop on learning representations for autonomous driving we aim at providing basic theoretical and practical knowledge to understanding the potential of deep learning architectures as well as to encourage discussions on the specific challenges within the field of intelligent vehicles and advance the current status of efficient algorithms by proposing a challenge in this particular topic.

* Efficient inference with deep neural networks
* Deep learning for reinforcement learning
* Uncertainty propagation in deep neural networks
* Deep neural networks for perception systems in intelligent vehicles
* DataSets for autonomous driving
* Low-level vision tasks for Intelligent Vehicles (pedestrian detection, semantic segmentation, instance segmentation...)

The idea of the poster session is to support discussions between participants, not to provide "yet another publication venue".

# Challenge: Efficient Neural Networks

The recent advances in computer vision have been mainly driven by deep learning, with no end in sight. Autonomous driving is a very exciting application domain for a lot of computer vision problems. In a vehicle, energy resources are very limited. At the same time, there is a trend towards more sensors with higher resolutions. This exposes a contradiction in autonomous driving: huge amounts of data have to be processed as fast, accurate and with as little power consumption as possible.

This workshop will encourage work on efficient neural networks in the context of autonomous driving. We challenge the IV community to participate in a semantic segmentation challenge, offering a prize for the winner. The workshop program will include invited talks, presentations of the top 3 challenge winners and a poster session of submitted work.

## Challenge Details
The prize for the winning team is awarded by a jury. The prize will be given to the team showing the best compromise between high accuracy, high speed in frames/second and low power consumption. The winner team is required to give a detailed presentation (with reproducible results) at the workshop. Papers about the work are optional but highly welcome to a special issue in IEEE T-IV.

The accuracy of the system will be measured following the Cityscapes1,2 benchmark for class segmentation. Testing will be done using unpublished data taken with the same car and camera system that was used for the Cityscapes sequences. As a consequence, you have to process 2048x1024px RGB images and output 2048x1024px maps of labels according to the Cityscapes label set3. Prior to the deadline, a sequence of roughly one minute will be supplied to interested teams. The results (whole sequence) have to be submitted within a day, using the same labels and format as known from the standard Cityscapes benchmark.

For a fair comparison, submitting teams have to measure the speed of their solution and to specify the used HW.

The deadline for submissions is May, 1st. Participants are requested to render a video of the entire sequence and to show the results during their presentation at the workshop.

References:<br>

[1] Cityscapes Dataset: M. Cordts, M. Omran, S. Ramos, T. Rehfeld, M. Enzweiler, R. Benenson, U. Franke, S. Roth, and B. Schiele, "The Cityscapes Dataset for Semantic Urban Scene Understanding," in Proc. of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016. https://arxiv.org/abs/1604.01685<br>
[2] Cityscapes Homepage: https://www.cityscapes-dataset.com/<br>
[3] Cityscapes Github: https://github.com/mcordts/cityscapesScripts<br>
      For the labelset see: https://github.com/mcordts/cityscapesScripts/blob/master/cityscapesscripts/helpers/labels.py

# Important Dates

Deadline for extended abstract submissions: **1st of May, 2017**
Acceptance notification: 8th of May, 2017
Workshop: 11th of June, 2017
Extended abstracts need to be submitted by email to [Jose Alvarez](jose.alvarezlopez@data61.csiro.au)
**We will not use the PaperCept system.**

Formatting guidelines and submission rules:

1. Maximum of four pages including references
2. [IEEE format](http://iv2016.org/authors/authors-2/)
3. The extended abstracts will not be published in the proceedings. However they will be published on this website if the authors agree.
4. The submitted abstract should present recent results, but not necessarily novel ones.
5. All accepted abstracts will be presented as posters at the workshop. We will select a single abstract which will be additionally given the opportunity for an oral presentation.
6. All abstracts will be reviewed by the organizers.

# Organizers

* [Trevor Darrell (EECS UC Berkeley, United States)](http://www.eecs.berkeley.edu/~trevor/)
* [Jose M. Alvarez (Dat61 @ CSIRO, Australia)](http://www.josemalvarez.net/)
* [Uwe Franke (Daimler AG, Germany)](http://www.uwe-franke.de/)
* Fiete Botschen (Daimler AG, Germany)