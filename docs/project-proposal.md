# CS479: Machine Learning for 3D Data

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Fall 2023
</b></h3>


## Project Proposal

^^Due^^: ==September 24 (Sunday), 23:59 KST==  
^^What to submit^^: ==A write-up (up to three A4 pages; shorter is preferred). No template provided.==  
^^Where to submit^^: ==OpenReview==  

Submit a project proposal for each **team**. Submit the proposal with the following information (no template provided):  

- Project title
- Project track (Refer to the [project track](#project-track) tab below)
- Submission ID (to be assigned by OpenReview)
- All teammate names
- Basic information about the baseline method (Refer to the [baseline method](#baseline-method) section below)
    - Author list
    - Paper title
    - Paper publication venue
    - arXiv link
    - Code GitHub repository link
- Problem definition of the baseline method (Refer to the [problem definition](#problem-definition) section below)

If your team is on the **novel problem solving** track:

- New problem definition (Refer to the [problem definition](#problem-definition) section below)
- The difference between the problem definition of the baseline method and the new problem definition
- Motivation of the new problem
- The main idea for solving the new problem
- Experiment setup and success criteria (Refer to the experiment setup and success criteria section below)

If your team is on the **performance improvement** track:

- The exact aspect of the “performance” to be improved.
- The main idea for improving the performance.
- Experiment setup and success criteria (Refer to the [experiment setup and success criteria](#experiment-setup-and-success-criteria) section below)


You are allowed to modify the project idea until the project pitch. However, a proposal with excessively random ideas will be deemed as an incomplete submission (TAs will make this determination).


### Project Topic
You can select any project idea related to **machine learning** and **3D**. The project idea does not necessarily have to be connected to deep learning and neural networks. If you are not certain whether the project idea aligns with the course, consult the instructor or TAs.


### Problem Definition
The definition of a research problem must include the following:

- **Input**: Input data type, data representation, etc. For a learning-based method, the input refers to the data provided during inference time, not during training.
- **Output**: Output data type, data representation, etc.
- **Training data / supervision**: The type and representation of the training data.
- **Assumptions / conditions**: For instance, ensuring the alignment of all 3D models in terms of rotation, or noting that point clouds are sparse.

Even subtle differences in the aspects mentioned above can significantly impact approaches and pose unique challenges. Be as specific as possible in defining these.


### Baseline Method
You first need to choose a baseline method that meets the following criteria:

- It should be the **state-of-the-art** method (providing the best performance) at the time of proposal.
- The paper associated with the method should be **published** on arXiv and/or presented at a conference.
- Both the **code and data** should be made available.

We recommend consulting the provided [paper list]({{links.paper_list}}){:target="_blank"}, but you're not restricted to selecting a method from that list.


### Regarding the State-of-the-Art
**You are responsible for identifying the current state-of-the-art (best performance) method for the problem you plan to tackle**. This will involve an offense-defense role-play scenario. If, after your proposal, the instructor, TAs, or other students determine that your selected baseline method isn't the state-of-the-art, you'll be required to switch the baseline method and adjust your project idea accordingly. For instance, PointNet is not the state-of-the-art method for now, and there are many follow-up techniques.

While you can consult the TAs to verify whether your chosen baseline method qualifies as the state-of-the-art, it's not permissible to ask the TAs to find the state-of-the-art method. Additionally, please be aware that it might take approximately 1 day for the TAs to respond to your query.


### Code and Data
Prior work that does not provide code and data will not be considered as the state-of-the-art work in our course project. You will need to build your project code on top of the baseline method code. Hence, **we recommend that you choose a baseline that provides code and data**. It is okay if you implement the baseline method yourself from scratch, but then the performance of your implementation must be similar to the performance reported in the paper.


### Experiment Setup and Success Criteria
Your experimental setup must include the following:

- **Datasets**: Describe the datasets used for training and testing. Provide details about data representation, dataset scale, diversity (such as the number of classes), and the training/validation/test splits.
- **Evaluation metrics**: Specify the quantitative evaluation metrics. Ensure you incorporate established evaluation metrics relevant to the specific problem. For instance, include metrics like coverage, minimum matching distance, and 1-Nearest Neighbor Average (1-NNA) for 3D generative models.
Baseline methods for comparison.

With the experiment setup defined, outline success criteria both qualitatively and quantitatively. Envision the qualitative outcomes of your approach and the anticipated distinctions from existing works. **Establish quantitative success criteria based on the specified evaluation metrics.**


### Computing Resource
We plan to provide GPUs in [KCLOUD](https://kcloud.kaist.ac.kr/){:target="_blank"}, and each team will have the option to choose either two GPUs with 24 GB VRAM each (RTX 3090 or Titan X), or one A100 GPU. By default, you will receive the 24 GB VRAM GPUs. A100 GPUs will be allocated to teams that require GPUs with larger VRAM.

It is crucial to propose a project idea that is achievable within the provided computational resources. For example, certain baseline methods might require multiple A100 GPUs and/or several days or weeks for training, which would not be feasible for your project.


### Grading
- **Late submission**: A 5% penalty for **each** late day in the project evaluation.
- A submission with any missing items will be considered as not submitted.

<br />
