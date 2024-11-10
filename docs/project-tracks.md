# CS479: Machine Learning for 3D Data

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Fall 2023
</b></h3>


## Project Tracks

You can choose either of the following two project tracks:

- [Novel Problem Solving](#novel-problem-solving)
- [Performance Improvement](#performance-improvement)

### Novel Problem Solving

Propose a new problem based on the baseline method. For instance, you can consider

- changing either the input or output of the problem,
- using more or less information in training,
- employing much more diverse or significantly sparser training data,
- addressing multiple known problems using a single unified framework,
- utilizing existing techniques to solve the other problems, or
- suggesting a completely novel problem!

Here is an example: Given a supervised method for point cloud semantic segmentation, such as PointNet, you can propose:

- Taking a pair of images and point clouds as inputs.
- Shifting the focus from semantic segmentation to instance segmentation.
- Approaching the segmentation task in an unsupervised manner or through a few-shot learning approach.

If there is existing work that addresses the same problem, you need to take that existing work as your baseline and brainstorm yet another new problem. For example, there are already works that explore:

- Taking images and point clouds as inputs (e.g., Frustum PointNet).
- Addressing point cloud instance segmentation (e.g., SoftGroup).
- Approaching the segmentation problem through unsupervised learning or few-shot learning techniques (e.g., BST-Net).

**Exploring the existing literature and identifying a new problem is a critical aspect of the project, which requires a significant amount of time.**

#### Motivation
If you choose to tackle a new problem, elucidate the significance of solving this problem and how it effectively addresses real-world issues. Your proposal could be rejected if TAs perceive that the reasoning behind introducing the new problem does not make sense and lacks practical significance or impact.

#### Experiment Setup and Success Criteria
Define the experimental setup and success criteria based on those of the baseline method. You might need to modify the datasets or evaluation metrics slightly. If you propose a method that utilizes more information or more data during training, your goal should be to surpass the baseline by a significant margin. Conversely, if you suggest a method that employs less information or fewer training data, you can aim to achieve comparable (albeit potentially slightly lower) performance than the baseline method.


### Performance Improvement
The performance improvement track is much simpler. You aim to address the same problem as the baseline method but propose ideas to enhance its performance.

#### Experiment Setup and Success Criteria
Adopt the identical experimental setup as the baseline method, then suggest new success criteria derived from it. **Your proposed approach should exhibit superior performance in comparison to the baseline method.** Clearly outline specific objectives for surpassing the baseline method using the evaluation metrics.

<br />
