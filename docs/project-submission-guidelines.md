# CS479: Machine Learning for 3D Data

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Fall 2023
</b></h3>


## Project Submission Guidelines

<!-- (Last updated: May 29, 2022. Subject to change.) -->

^^Poster Submission Due^^: ==November 29 (Wed), 23:59 KST==   
^^Report/Code Submission Due^^: ==December 3 (Sun), 23:59 KST==    
^^Where to submit^^: ==OpenReview==   
[https://openreview.net/group?id=kaist.ac.kr/KAIST/Fall2023/CS479](https://openreview.net/group?id=kaist.ac.kr/KAIST/Fall2023/CS479){:target="_blank"}


### Submission Guidelines

- A submission must include a **poster**, a **report**, and a **code repository link**. (Supplementary materials are optional.)
- Submission with the **wrong format** or any **missing items** may receive a **zero** score.
- Add the team ID and all team members' names in the poster and the report.
- In the OpenReview webpage, the deadline ie written as `Jun 06 2022 02:59PM UTC-0`, which is the same as `Jun 06 2022, 23:59 KST`.
- Even in the case when OpenReview does not block the submission after the deadline (due to some system errors), **any submissions after the due date will NOT be accepted**.


### ^^[IMPORTANT] Plagiarism / Academic Misconduct^^
**Plagiarism consists of appropriating someone else's ideas or any texts, figures, or results of the other work, without sharing credit or correctly citing or mentioning the work.
If plagiarism or other academic misconduct is discovered in your submission (in any of your report, poster, code, or supplementary), you will receive an F grade, and also it will be reported to the university.**

==Be careful not to commit plagiarism by mistake==. Do not forget to add citations properly. Consult the instructor or TAs if you have any concerns about plagiarism before you submit your report/poster/code.

**DO NOT COPY the texts or figures in the baseline paper (except for figures and tables in the *result* section) — it will be considered plagiarism.** Write the report in your own words. **It is allowed to use qualitative result figures and the numbers in the quantitative result tables in the original paper only for comparisons, but ==CLEARLY MENTION that the figures and numbers are from the original paper.==**


### Infeasible Experiments

In the report, you can argue the **infeasibility** of experiments that are expected to be shown in the results.
For example,

- Some experiments in the original work (Performance Improvement Track) may not be reproducible if the experiments require more than two GPUs *(note that only two GPUs are provided to each team)* or some important details about the experiments are missing.
- An exact comparison with the original work (Performance Improvement Track) or previous work (Novel Problem Solving Track) may not be possible when the data used in the experiment is not released.

For such infeasible experiments, the authors must consider **substituting** them with similar but feasible experiments (or, also argue why it is even not possible to substitute them).
For example,

- If an experiment is computationally infeasible, try to simplify the experiment (use a smaller dataset, use a simplified neural network, reduce the batch size, etc).
- If data for replication is not provided, consider using the other similar data.
- If some experiment details for replication are not provided, use any common parameters or approaches.

As a **reviewer**, you need to judge whether the argument about infeasibility is valid or not and whether the authors tried to substitute the infeasible experiments.

For the experiments considered infeasible, do not take them into account in the evaluation.


### Report Guidelines

#### Format

- A **single PDF** file (maximum 20MB). Supplementary materials are allowed.
- Must be in **CVPR** format:<br>
[Overleaf template (CVPR 2022 format)](https://www.overleaf.com/latex/templates/cvpr-2022-author-kit/qbmjsdxryffn){:target="_blank"}
- Add the **project type** (Novel Problem Solving / Performance Improvement) in the **second line** of the report title. Using LaTex, you can add like this: `\title{Project Title \\ {Novel Problem Solving / Performance Improvement} Track}`.
- The review will be **single-blind**. Add all the **author names** in the report (use `\usepackage[pagenumbers]{cvpr}` in the CVPR template).
- Must be up to **four**-page long, including figures, and tables, but not acknowledgments and references. Additional pages including **only acknowledgments and references** are allowed.

#### Structure
Please use the **same section names** below to facilitate the review process. Additional sections/subsections are allowed. ==The highlighted parts are mandatory.== Missing or violating the highlighted parts may lead to a penalty. **The other instructions are just recommended guidelines**; you do not need to exactly follow them.

#### Novel Problem Solving

- **Abstract**
    - one-sentence **TL;DR**,
    - 2-3 sentences for the **motivation** and **key ideas** of the **baseline work** ==(add a citation)==,
    - a few sentences summary of the **problem statement and key contributions**, and
    - 1-2 sentences summary of the **experimental results**.
    - In the end, add **"Code is available at: {link}."**

- **Introduction**
    - What is the **motivation** for the work? Why is it important to solve the problem? What would be the potential impacts of this work in the research field, or what would be the potential applications?
    - What are the **challenges** in the problem? How has previous work including the **baseline work** approached this problem, and what are the limitations (add citations)? Or, why hasn't the problem been addressed while it is important?
    - What is the **problem statement**? What are the input and desired output? What are the given information in the training time and the given assumptions? A **teaser figure** that effectively illustrates the problem setup or the desired output would be great. (E.g., show the best result.)
    - What are your **key ideas** for solving the challenges? It would be also great if your teaser image also describes the key ideas. (E.g. how do your key ideas make differences in the results?)
    - Briefly describe the **experimental setup**. Which datasets/benchmarks do you use? How do you evaluate the results? What is the conclusion? (E.g. our method outperformed SotA methods by huge margins.)
    - **A summary of contributions** at the end is also recommended (in a bullet point list). You can start the summary with (for example) 'In summary, our contributions are:'.

- **Related Work**:
    - Consider making **two or three** groups of related papers and writing a short paragraph for each of them, which a **paragraph title**. An intro sentence briefly describing the groups is recommended (but not necessary).
    - Summarize each work with 1-2 sentences while focusing on describing in which aspects your work is **different** or **overcoming the limitations**.

- **Method**
    - Describe the **problem setup** again, but in detail and also in a formal way. Introduce **essential math notations** for the following formulations. A **figure** describing the overall method is recommended.
    - The report needs to be **self-contained**; the readers must be able to understand the ideas without reading the other papers. If needed, provide **background knowledge** (the 'minimal' background to understand your work).
    - Think about the most effective way to explain the **key ideas**. One option would be **prioritizing** components in your method not based on the order in the method but based on the **importance**. Less important details can go to the end or to the supplementary.
    - Use **visual aids** in your exposition. More would be better.
    - Make the exposition as **clear** and **specific** as possible. **Formulations** can make the exposition clearer and more concise.

- **Experimental Results**
    - Clearly describe the **experimental setup**, including **benchmarks/datasets**, **evaluation metrics**, and **baseline methods**.
    - Provide both **quantitative results (tables)** and **qualitative results (figures)**. Provide **comparisons** with the baseline methods. Explain in which aspects your method is better. Think about the best way to demonstrate the advantages of your method over the baseline methods.
    - Conduct the **ablation study** and show the results. If you have multiple technical contributions, demonstrate how each component affects the results.
    - **Do not miss** any well-known benchmarks/datasets, standard evaluation metrics, or previous methods. Any **lack of experiments, evaluations, or comparisons** will be penalized in the evaluation.
    - Make **fair and reasonable** (apples-to-apples) comparisons. (Or, if the baseline methods take some advantages such as stronger supervision, describe clearly.) Unfair benefits to the proposed method in the experiments will also be penalized.
    - In here or in the conclusion, consider showing some **remarkable failure cases** explaining the limitation of the proposed method or motivating some future works.

- **Conclusion**
    - Briefly **summarize** the project, particularly the **key ideas** and the **experimental results**.
    - Describe the **limitation** of the proposed work and **potential future research** directions (if you have space in the report).

- **Acknowledgments**
    - ==Acknowledgments section is required.== Make acknowledgments as a subsection without a section number or as a paragraph.
    - ==Describe the **role** of each team member.==
    - ==Describe any data/codes you borrowed from the other places.==

#### Performance Improvement

- **Abstract**
    - one-sentence **TL;DR**,
    - 2-3 sentences for the **motivation** and **key ideas** of the **baseline work** ==(add a citation)==,
    - a few sentences summary of the **implementation challenges** and **your approaches**, and
    - 1-2 sentences summary of the **experimental results**.
    - In the end, add **“Code is available at: {link}.”**

- **Introduction**
    - What is the **motivation** for the baseline work? Why is it important to solve the problem? What would be the potential impacts of this work in the research field, or what would be the potential applications?
    - What is the **problem setup** the baseline work introduces? (Add a citation of the baseline work.)  What are the input and desired output? What are the given information in the training time and the given assumptions? What are the *main ideas* of the baseline work to solve the problem?
    - What are the **key challenges** in implementing the proposed method? Does the framework include some components that are not implemented in public libraries (e.g., PyTorch, PyTorch3D)? Do you implement some components from scratch without the public libraries? (Using CUDA?) Is the framework complicated with lots of components? Are there technical details hidden in the paper/code? Doesn't the authors provide their code or datasets? Does the authors' code even not reproduce the results in the paper? Is the network training tricky or unstable? Or, do you improve the baseline work?
    - Summarize the **implementation details**. **Clearly differentiate** the parts you implemented and the parts you borrowed existing code or got some help from the external collaborators. How do you implement each part, and how do you handle the challenges? A **teaser** figure that illustrates the parts you focused on in the implementation would be great.
    - Briefly describe the **experimental setup**. Which datasets/benchmarks do you use? How do you evaluate the results? Do you make any changes in the experimental setup of the baseline work? If yes, why? How good are your results compared with the results reported in the original paper (or the results of the authors' code)? Do you improve the original method, or do you conduct additional experiments not shown in the baseline work?
    - A **summary of achievements** at the end is also recommended (in a bullet point list). You can start the summary with (for example) ‘In summary, our achievements are:’.

- **Method Summary**
    - Describe the **problem setup** again, but in detail and also in a formal way. Introduce essential math notations for the following formulations. ==DO NOT COPY the texts or figures in the original paper==, but use the **same math notations** in the baseline work.
    - Briefly **summarize** the method proposed in the baseline work, while focusing on the parts that you implemented (if you used existing codes for some parts). The report needs to be **self-contained**; the readers must be able to understand the main ideas of the baseline work without reading the paper.

- **Implementation Details**
    - First, briefly but clearly state **which parts you implemented** in the framework. If you used some existing codes, describe in detail **how you also adopted the existing codes**. Add **references** for the existing codes. ==Hiding the use of existing codes will be considered plagiarism==.
    - **Data generation/preprocessing** and **evaluations** are also parts of the implementation. If you implemented these yourself, illustrate the details.
    - Consider as you explain the implementation details to help readers reproduce the results (like providing a **recipe in cooking**). Make the exposition **easy to follow**, but also **clear** and **specific** as much as possible.
    - ==**Do not explain your code** but the algorithm, and pseudocode if needed.== The readers should be able to understand what you implemented without any code-level description.
    - Use **visual aids** in your exposition. More would be better. But ==DO NOT COPY figures in the original paper.== Formulations are fine (but ==do not copy and paste an image but write them yourself==).

- **Experimental Results**
    - Clearly describe the **experimental setup**, including **benchmarks/datasets** and **evaluation metrics**. If you change or simplify the experimental setup of the baseline work, explain why.
    - Provide **comparisons** with the baseline work. Use the **exact results** reported in the original paper for comparison. If you test the authors' code in new datasets, explain why. Provide both **quantitative results (tables)** and **qualitative results (figures)**. Explain in which aspects the results of your method is better or comparable.
    - Try to reproduce **all the results** in the original paper. Any **lack of experiments, evaluations, or comparisons** (without any appropriate reasons) will be penalized in the evaluation.
    - Make **fair and reasonable** (apples-to-apples) comparisons. Unfair benefits to your implementation in the experiments will also be penalized.
    - If you achieve **better performance** than the baseline work, if you **improve** the proposed algorithm, or if you conduct some **additional experiments** not performed in the original paper, **emphasize** the results.
    - Here or in the conclusion, consider showing some **remarkable failure cases** explaining the limitation of the proposed method or your implementation, or motivating some future works.

- **Conclusion**
    - Briefly **summarize** the project, particularly the main parts you implemented and the experimental results.
    - Describe the **limitation** of the proposed work or your implementation and **potential future research directions** (if you have space in the report).

- **Acknowledgments**
    - ==Acknowledgments section is required.== Make acknowledgments as a subsection without a section number or as a paragraph.
    - ==Describe the **role** of each team member.==
    - ==Describe any data/codes you borrowed from the other places.==

### Poster Guidelines

#### Format

[Poster Template]({{links.poster_template}}){:target="_blank" .md-button}

- A **single PDF** file (maximum 10MB).
- Use the provided poster template above, which is adapted from [Zoya Bylinskii](https://web.mit.edu/zoya/www/docs.html){:target="_blank"}.
- Feel free to modify the poster template, but ensure that it includes the **project title**, **project track**, **team member names**, and **acknowledgments**.
- Note that the poster will be printed in **A0 size** with a **portrait** orientation.


#### Resources
- [<b>How to Make a More Effiective Research Poster (Zoya Bylinskii)</b>](https://web.mit.edu/zoya/www/posterRecommendations.pdf){:target="_blank"}


### Code Submission
- Create a **public** code repository in GitHub or Bitbucket and submit the link.
- Add the link in the **abstract** of the report (see [Report Guidelines](#report-guidelines)).
- <h>All the results shown in the report must be reproducible with your code.</h> In the code repository, ==provide **links of the pretrained models** (stored in Google Drive or any other places) and also **datasets you created**==, so that anyone can easily check the reproducibility.


### Supplementary Materials
- Supplementary materials are optional.
- Any formats (PDF document, video, web page) are allowed (maximum 100MB).
- Submit as a **ZIP** file.


### Penalty
^^There is no late day. Submit on time.^^

- **Late submission**: ==Zero score==.
- **Missing any of report/poster/code**: ==Zero score==.
- **Missing components or violations of policies in the report**: ==10% penalty for each==.

<br />
