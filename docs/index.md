---
hide:
  - navigation
---

# CS479: Machine Learning for 3D Data

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Fall 2023
</b></h3>
<br />

![Teaser](assets/teaser.png){ width=97.5% }


## Time & Location
**Time**: Mon/Wed 10:30am - 11:45am (KST)   
**Location**: Online via Zoom

[Zoom Link](https://kaist.zoom.us/j/85920030773){:target="_blank" .md-button}


## Description
3D Data (both 3D scans captured by depth sensors and 3D models created by designers) are widely used in many applications in computer vision, computer graphics, and robotic, such as autonomous driving, AI-assisted 3D object/scene design, augmented reality, and physical robot interaction. Along with the recent increasing demands on processing and analyzing such 3D data, there has been tremendous progress in developing novel technologies, especially based on deep learning. In this course, we will cover the recent advances in machine learning techniques for 3D data and also discuss the remaining challenges. Most of the course material will be less-than-5-year-old research papers in CVPR/ICCV/ECCV (Vision), SIGGRAPH/SIGGRAPH Asia (Graphics), and NeurIPS/ICML (Machine Learning). The course will be project-oriented (no exam, no paper-and-pencil homework, but easy programming assignment), and it will combine pedagogical lectures and seminar-style reading group presentations (followed by interactive discussions). 


## Prerequisites
This course is intended for undergraduate/master students who have a basic background in deep learning and experience with PyTorch.


## Course Staff
**Instructor**: [Minhyuk Sung](https://mhsung.github.io/){:target="_blank"} ([mhsung@kaist.ac.kr](mailto:mhsung@kaist.ac.kr))

**Course Assistants:**

- Juil Koo ([63days@kaist.ac.kr](mailto:63days@kaist.ac.kr))
- Hyunjin Kim ([rlaguswls98@kaist.ac.kr](mailto:rlaguswls98@kaist.ac.kr))
- Kunho Kim ([kaist984@kaist.ac.kr](mailto:kaist984@kaist.ac.kr))
- Jaihoon Kim ([jh27kim@kaist.ac.kr](mailto:jh27kim@kaist.ac.kr))
- Seungwoo Yoo ([dreamy1534@kaist.ac.kr](mailto:dreamy1534@kaist.ac.kr))
- Yuseung Lee ([phillip0701@kaist.ac.kr](mailto:phillip0701@kaist.ac.kr))

**Office hours (Offline)**: Mon 7:00pm (KST). N1 Rm 601.


## Past Years
- [CS492(A): Machine Learning for 3D Data (Spring 2022)](https://mhsung.github.io/kaist-cs492a-spring-2022/){:target="_blank"}
- [CS492(H): Machine Learning for 3D Data (Spring 2021)](https://mhsung.github.io/courses/kaist-cs492h-spring-2021/){:target="_blank"}


## Grading
- Programming Assignments: 30%
- Project: 50%
- Paper/Project Reviews: 10%
- In-Class Participation: 10%



## AI Coding Assistant Tool Policy
**You are allowed (and even encouraged) to utilize AI coding assistant tools**, such as ChatGPT, Copilot, Codex, and Code Intelligence, for your programming assignments and projects. Utilizing AI coding assistant tools will not be deemed as plagiarism. However, it is still strictly prohibited to directly copy code from the Internet or from someone else. Doing so will lead to a score of zero and a report to the university.


## Important Dates
ALL ASSIGNMENTS ARE DUE 23:59 KST.
(Subject to Change)

- Project Sign-Up: ==Due Sep 8 (Fri)==
- 1st Programming Assignment: ==Due Sep 17 (Sun)==
- Project Proposal: ==Due Sep 24 (Sun)==
- 2nd Programming Assignment: ==Due Oct 9 (Mon)==
- Project Mockup: ==Due Oct 9 (Mon)==
- Project Pitch Video: ==Due Oct 20 (Fri)==
- Project Interim Report 1: ==Due Nov 5 (Sun)==
- Paper Review Questions: ==Due Nov 12 (Sun)==
- 3rd Programming Assignment: ==Due Nov 12 (Sun)==
- Project Interim Report 2: ==Due Nov 19 (Sun)==
- Paper Review Answers: ==Due Nov 26 (Sun)==
- Project Poster: ==Due Nov 29 (Wed)==
- Project Report/Code: ==Due Dec 3 (Sun)==
- Project Review: ==Due Dec 9 (Sat)==
- Project Rebuttal: ==Due Dec 13 (Wed)==


## Paper List
[Paper List Link]({{links.paper_list}}){:target="_blank" .md-button}


## Schedule
(Subject to Change) 

| Week | Mon | Topic | Wed | Topic |
| :----: | :----: | :----: | :----: | :----: |
| 1  | Aug 28 | **Course Introduction**<br>[**Slides**]({{links.lec01}}){:target="_blank"}<br>[**Recording**]({{links.rec01}}){:target="_blank"} | Aug 30 | **3D Representations 1**<br>[**Slides**]({{links.lec02}}){:target="_blank"}<br>[**Recording**]({{links.rec02}}){:target="_blank"} |
| 2  | Sep 04 | **3D Representations 2**<br>[**Slides**]({{links.lec03}}){:target="_blank"}<br>[**Recording**]({{links.rec03}}){:target="_blank"} | Sep 06 | **3D Representations 3**<br>[**Slides**]({{links.lec04}}){:target="_blank"}<br>[**Recording**]({{links.rec04}}){:target="_blank"} |
| 3  | Sep 11 | **Point Cloud Encoders**<br>[**Slides**]({{links.lec05}}){:target="_blank"}<br>[**Recording**]({{links.rec05}}){:target="_blank"} | Sep 13 | **Point Cloud Generation**<br>[**Slides**]({{links.lec06}}){:target="_blank"}<br>[**Recording**]({{links.rec06}}){:target="_blank"} |
| 4  | Sep 18 | **Implicit Neural Representations**<br>[**Slides**]({{links.lec07}}){:target="_blank"}<br>[**Recording**]({{links.rec07}}){:target="_blank"} | Sep 20 | **Structure from Motion 1**<br>[**Slides**]({{links.lec08}}){:target="_blank"}<br>[**Recording**]({{links.rec08}}){:target="_blank"} |
| 5  | Sep 25 | **Structure from Motion 2 /<br>Neural Rendering 1**<br>[**Slides**]({{links.lec09}}){:target="_blank"}<br>[**Recording**]({{links.rec09}}){:target="_blank"} | Sep 27 | **Neural Rendering 2**<br>[**Recording**]({{links.rec10}}){:target="_blank"} |
| 6  | Oct 02 | No Class (Substitute Holiday)  | Oct 04 | No Class (Conference Trip) |
| 7  | Oct 09 | No Class (Hangul Day) | Oct 10 | **Guest Lecture 1<br>[Niloy J. Mitra](guest-lecture-niloy-mitra/){:target="_blank"}<br>Professor at UCL<br>Oct 10 (Tue) 4:00 p.m.<br>Offline (E3-1, Rm 1101)** |
| 8  | Oct 16 | No Class (Midterm Week) | Oct 18 | No Class (Midterm Week) |
| 9  | Oct 23 | **Project Pitches**<br>[**Video Compilation**]({{links.pitch_videos}}){:target="_blank"} | Oct 25 | **Hybrid Representations 1**<br>[**Slides**]({{links.lec12}}){:target="_blank"}<br>[**Recording**]({{links.rec12}}){:target="_blank"} |
| 10 | Oct 30 | **Hybrid Representations 2**<br>[**Recording**]({{links.rec13}}){:target="_blank"} | Nov 01 | **Diffusion Models 1**<br>[**Slides**]({{links.lec14}}){:target="_blank"}<br>[**Recording**]({{links.rec14}}){:target="_blank"} |
| 12 | Nov 06 | **Diffusion Models 2**<br>[**Slides**]({{links.lec15}}){:target="_blank"}<br>[**Recording**]({{links.rec15}}){:target="_blank"} | Nov 08 | **Conditional Generation**<br>[**Slides**]({{links.lec16}}){:target="_blank"}<br>[**Recording**]({{links.rec16}}){:target="_blank"} |
| 11 | Nov 13 | **3D Generation**<br>[**Slides**]({{links.lec17}}){:target="_blank"}<br>[**Recording**]({{links.rec17}}){:target="_blank"} | Nov 15 | No Class (Break) |
| 13 | Nov 20 | **3D Detection/Segmentation**<br>[**Slides**]({{links.lec18}}){:target="_blank"}<br>[**Recording**]({{links.rec18}}){:target="_blank"} | Nov 22 | **Guest Lecture 2<br>[Jun Gao](guest-lecture-jun-gao/){:target="_blank"}<br>Research Scientist at<br>NVIDIA Toronto AI Lab<br>Nov 22 (Wed) 10:30 a.m.<br>Online (Zoom)** |
| 14 | Nov 27 | **Rotation Invariance/Equivariance**<br>[**Slides**]({{links.lec19}}){:target="_blank"}<br>[**Recording**]({{links.rec19}}){:target="_blank"} | Nov 29 | No Class (Undergraduate Admission Interviews) |
| 15 | Dec 04 | **Poster Presentations 1** | Dec 06 | **Poster Presentations 2** |
| 16 | Dec 11 | No Class (Final Week) | Dec 13 | No Class (Final Week) |




