
Instructor

*  Sean Yuji Sylvia ([sean.sylvia@unc.edu](sean.sylvia@unc.edu)), Department of Health Policy and Management, UNC  
    
TA
*  Yumeng Du ([yumengdu@email.unc.edu](yumengdu@email.unc.edu)), Department of Health Policy and Management, UNC  

## Overview

HPM 883 is an advanced graduate-level course designed to equip PhD students in the Health Policy and Management program with sophisticated quantitative research skills. This course represents the third installment in the quantitative methods sequence, building on the foundational knowledge acquired in previous courses.

Throughout the term, students will delve into experimental methods pertinent to health services research, gaining a comprehensive understanding of how to design, conduct, and analyze experiments within this field. The course will also provide a thorough introduction to both supervised and unsupervised machine learning techniques, as well as explore the burgeoning domain of causal machine learning.

To facilitate a deep and practical understanding of these complex topics, HPM 883 employs a "flipped" classroom structure. Students will be expected to engage with recorded lectures and complete assigned readings at home. Classroom time will then be dedicated to hands-on data analysis using the R programming language, allowing for immediate application of theoretical concepts to real-world datasets.

This interactive approach not only fosters a collaborative learning environment but also ensures that students are well-prepared to employ advanced quantitative methods in their own research. By the end of the course, participants will have developed a robust skill set, enabling them to confidently tackle intricate analytical challenges in health policy and management research.

## Class Websites

* Canvas page [here](https://canvas.unc.edu/) See it for class lists, Zoom links, and announcements.
* Gradescope [here](https://www.gradescope.com/)  See it for assignments.
* Slack - We have a Slack workspace for the course which you should use to communicate both with us as instructors, and with your fellow students. You can sign up via this link [here](https://join.slack.com/t/hpm883/shared_invite/zt-2vvlfml0i-9_LL6M_rz416NeDMZT4Gqw)

###  Course Format

*  Flipped classroom – Recorded lectures and readings to be completed outside of class; in-class sessions focused on practical data analysis.

#### Lab exercise

Computer-based exercises will feature prominently in the course, especially in the lab sessions.  The use of all software tools will be explained in the sessions, including how to download and install them.  All of the class work will be done using R, using publicly available packages.

###  Main Textbook

The primary textbooks are:

* Garrett Grolemund and Hadley Wickham (2016) _R for Data Science_, O'Reilly Media. Note: Online version is available from the authors' page [here](http://r4ds.had.co.nz/index.html).

The following are supplemental texts which you may also find useful:

* Lantz, B. (2013). _Machine Learning with R_. Packt Publishing.
* Hastie et al. (2009) _The Elements of Statistical Learning: Data mining, inference, and prediction_. Springer. Note: The book is available from the authors' page [here](http://statweb.stanford.edu/~tibs/ElemStatLearn/).

### Assessment

Performance will be assessed through a combination of homework assignments, in-class exercises, a midterm project, and a final research paper wherein students apply the techniques learned to a health services research question of their choice.


**Evaluation Method**

| Component                                              | % of Grade |
|--------------------------------------------------------|------------|
| Combined Quizzes (Before and After Class)              | 10%        |
| Homework Assignments                                   | 25%        |
| In-Class Exercises                                     | 10%        |
| Midterm Project                                        | 25%        |
| Final Research Paper                                   | 30%        |
| **Total**                                              | 100%       |

---

**Assessment Details**

 **Quizzes** (10% of Grade)
- **Objective:** To assess students’ understanding of assigned readings, lecture material, and knowledge retention.
- **Structure**:
  - **Before Class Quizzes:** Focus on assigned readings and lecture preparation.
  - **After Class Quizzes:** Test comprehension of lecture material and identify areas for clarification.
- **Format:** Administered via GitHub Classroom.
- **Grading Criteria**:
  - Consistent effort.
  - Demonstrated understanding of key concepts.

---

 **Homework Assignments** (25% of Grade)
- **Objective:** To reinforce foundational concepts in **Experimental Design**, **Supervised/Unsupervised Machine Learning**, and **Causal Machine Learning**.
- **Structure**:
  - Includes replication exercises and analysis using simulated data.
  - Assignments are modeled on the HPM PhD comprehensive exam format to provide qualifying exam preparation.
- **Submission Format:** Via GitHub Classroom.
- **Grading Criteria**:
  - Accuracy and completeness of analysis.
  - Demonstrated understanding of class concepts.
  - Clarity in presenting results.

---

 **In-Class Exercises** (10% of Grade)
- **Objective:** To provide hands-on practice with theoretical concepts in a collaborative learning environment.
- **Structure**:
  - Short exercises conducted during lab sessions focusing on problem-solving and practical applications.
- **Grading Criteria**:
  - Participation and effort.
  - Accuracy and thoughtfulness in responses.

---

 **Midterm Project** (25% of Grade)
- **Objective:** A practical application of methods covered in the first half of the course.
- **Structure**:
  - Students will replicate a published study or analyze simulated data.
  - Emphasis on applying techniques in **Experiment Design** and **Supervised Machine Learning**.
  - Deliverables include a written report detailing methodology, results, and conclusions.
- **Grading Criteria**:
  - Depth of analysis and correct application of methods.
  - Clarity and organization in the written report.
  - Originality and engagement with the assigned task.

---

 **Final Research Paper** (30% of Grade)
- **Objective:** To apply the techniques learned throughout the course to a health services research question of the student’s choice.
- **Structure**:
  - Students will identify a health services research topic, apply methods learned from class, and write a comprehensive research paper.
  - The paper must include:
    - Introduction and research question.
    - Methodology and data description.
    - Analysis and results.
    - Discussion and conclusion.
  - Students are encouraged to select datasets relevant to their research interests, with instructor approval.
- **Grading Criteria**:
  - Creativity and relevance of the research question.
  - Correct and thorough application of methods.
  - Quality and clarity of writing.
  - Depth of discussion and interpretation of results.


## Pre-Class: Computer Setup (@Sean, tbd)** 

You will need R for this course. You will need to download and install 

- **Git**: [Install Git](https://git-scm.com/downloads)
- **VS Code**: [Install VS Code](https://code.visualstudio.com/)
- **Quarto**: [Install Quarto](https://quarto.org/docs/get-started/)
- **Jupyternotebook**: [Install Jupyternotebook](https://jupyter.org/install)
- **R**: [Install R](https://cran.r-project.org/)

To ensure a seamless learning experience, please complete the following setup tasks before the course begins. This setup will allow you to effectively participate in in-class exercises and complete after-class assignments.


 **Step 1: GitHub Codespaces Setup (for After-Class Assignments)**
1. **Create a GitHub Account** (if you don’t already have one):
   - Sign up for a free account at [GitHub](https://github.com).
2. **Enable GitHub Codespaces**:
   - Codespaces is a cloud-based development environment that you’ll use for assignments. To enable it:
     - Navigate to your GitHub repository dashboard.
     - Click on the “Codespaces” tab and follow the prompts to activate it.
3. **Clone the Course Repository**:
   - Click this link to access the course's GitHub repository [GitHub](https://github.com). Clone this repository into your Codespaces environment by following these steps:
     - Open the repository link.
     - Click the green “Code” button and select “Open with Codespaces.”
4. **Verify the Environment**:
   - Use template we provided in class

 **Step 2: Google Colab Notebook Setup (for In-Class Exercises)**
1. **Download the R packages needed for the exercises**:
   - Open this notebook first to download all the R packages needed in class [Before-Class](https://colab.research.google.com/github/Shuyi-Song/dhep-analysis-template/blob/master/Before_Class.ipynb).
    
2. **Load In-Class Notebook**:
   - Open In-Class Notebook to ensure it’s functioning correctly [In-Class](https://colab.research.google.com/github/Shuyi-Song/dhep-analysis-template/blob/master/In_class.ipynb).

 **Step 3: Recommended Software**
- **Text Editor** (optional but helpful):
  - Visual Studio Code (VS Code) with the Python extension is recommended for working on Python scripts or Jupyter notebooks locally.
  - Download it [here](https://code.visualstudio.com).
- **Data Visualization Tools**:
  - Ensure your environment supports plotting libraries like Matplotlib and Seaborn for visualizing experimental results.

 **Step 4: Verification and Support**
- **Test Your Setup**:
  - Complete the introductory lab provided in the course repository to verify your environment.
- **Support**:
  - If you encounter issues, refer to the provided setup guide in the course repository or reach out to the course instructor/TA for assistance.

This setup will allow you to:
- Use **Gradescope** for submitting after-class assignments.
- Engage effectively with **Google Colab Notebook** during in-class exercises.

