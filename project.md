| [MATH60629A](main.md) | [Lectures](lectures.md) | [Lab](lab.md) | [Quizzes and Assignment](homework.md)  | [Project](project.md) | [Office hours](office_hr.md)
# Machine Learning for Large-Scale Data Analysis and Decision Making (MATH60629A): Winter 2025

This project will be worth 40% of your final grade. You must work in teams of three or four.

## Grading Scheme 
### Project Report (29%)
- Clarity/Relevance of problem statement and description of approach: 10%
- Discussion of relationship to previous work and references: 4%
- Design and execution of experiments: 10%
- Figures/Tables/Writing: easily readable, properly labeled, informative: 5%


### Project Presentation (10%)
- Clarity of presentation: 3%
- Slide or Poster quality: 2%
- Correctness: 2%
- Answers to questions: 3%
  
### Project Individual Report (1%)

## Timeline
- [Team Registration](https://hecmtl-my.sharepoint.com/:x:/g/personal/dena_firoozi_hec_ca/EYseVK_6EJdHtI3BRsh5r78BKR8RrGL-a_pUP3uHMEN9ow?e=RRMieo). Teams of 3 or 4 students. Due: **January 31, 2025, by the end of the day EDT.**  
- Study plan, due: **between February 14-28, 2025 by 11:55pm** The earlier you submit your study plan the earlier you can get feedback and start working on your project. Upload the PDF of the proposal to ZoneCours/Remise de travaux) by the head of the team (one upload per each team).
- Project meeting: **February 21 to March 7, 2025**. If you want to meet earlier than March 7, you must submit your study plan a week ahead of the meeting date. 
- Project Presentation, due: **April 8, 2025 (12:00 pm EDT)**. Upload the PDF version of your poster/slides to ZoneCours/Remise de travaux by the head of the team (*one upload per each team*).
- In-class Presentation, on **April 11, 2025**.
- Final group report, due: **April 18, 2025 by the end of the day EDT**. Upload the PDF of the final group report to ZoneCours/Remise de travaux by the head of the team (one upload per each team).
- Final code, due: **April 18, 2025, by the end of the day EDT**. Upload the zip file of the final project code to ZoneCours/Remise de travaux by the head of the team (*one upload per each team*).
- Final individual report, due: **April 18, 2025 by the end of the day EDT** . Upload the PDF of the final individual report to ZoneCours/Remise de travaux (*one upload per each student*). 

## Goals

The aim of this project is to allow you to learn about machine learning by trying to solve a task with it.

First, select a question that can be answered using machine learning. I expect that your question will be about a model/algorithm or about an application. Then design a study that will try to answer your question. Your study must have an element of novelty. For example the novelty could be an extension or a variation of an existing algorithm or results of an existing method on a new dataset.

Your study should involve reading and understanding some background material. Your study must involve running some experiments. You are free to use (or not) any of the tools or models we have seen in class.

<!--**Alternatively**: You could decide to participate in this open challenge: ML Reproducibility Challenge 2020. Let me know as soon as possible if you are interested in this.-->

**Study plan**: (1 upload per team) Please submit a one-page summary of your proposed research question and study to ZoneCours/Remise de travaux. I will meet with each group to discuss study plans during the lecture of **March 15, 2024**. I will send you a schedule the day before. We will probably only have about 15 minutes so please make sure that your study plan is clear and precise. In your study plan you must include: 
- The question you aim to answer,
- The source of the dataset you will be using,
- The tentative machine learning methods you plan to apply to answer your question,
- The questions or aspects you would like to discuss during our meeting,
- A sentence indicating if you would like to meet earlier than March 15th.  


**Presentation**: This is a group presentation, with a set of slides or a poster prepared. We will decide at random the order of the presentations.

*Requirements for the Presentation*: 
-	Give an overview of the task, and present statistical analysis of the data using visualization tools.
-	Present the method that you use for each data source/task.
-	Provide an overview of the prediction results you obtained by applying the machine learning methods on the public/private dataset.
-	Your approach should at least beat a baseline or be similar to the state-of-the-art (SOTA) approach for the chosen task.
-	Wrap up with a few concluding remarks.
-	The presentation length must be between 10-12 minutes followed by 3-5 minutes of questions, in total 15 minutes.
-	**All team members** should present. Students who do not present can not get credit for this part.

**The group report**: (1 upload per team) Your report must contain a description of the question you are trying to answer, a clear description of the model/algorithm you are studying, a survey of related work which proper references, an empirical section that reports your results, and a conclusion that summarizes your findings and (if pertinent) highlights possible future directions of investigation. <!--Your report should be no longer than 10 pages in length (plus references) for teams of 3 or 13 pages (plus references) for teams of 4.-->

Provide a write-up of your research in the form of an academic paper that could be submitted to a conference on data mining/machine learning. Your paper should be self-contained. Everyone who has read the assigned reading materials from the course should be able to read and understand your paper. That means that in your paper you can be brief about machine learning methods that are described in the assigned readings, but that you need to provide sufficient details about the problem domain, the dataset, as well as about any other machine learning methods that you used that were not covered in class. The reasons for this are:

1.	a description of the problem domain and the dataset will allow to share your paper with interested parties who have not taken the course but who have general knowledge of machine learning;
2.	a description of machine learning methods not covered in class will allow us to evaluate whether you truly understood those methods instead of treating them as a black box.

Your paper can for instance be divided into sections as follows (but if another structure works better for you, don’t feel restricted to the one below):
-	Introduction: a description of the problem, what the goals of the study are, a survey of related work, and a very brief description of the results.
-	Methodology: a brief description of the machine learning methods used.
-	Dataset and metrics: a description of the datasets and the evaluation measures used.
-	Results: an overview of the results you obtained by applying the methods from section 2 to the dataset from section 3 using the metrics from section 3. In addition to reporting numbers, your analysis of the results should also contain your insights into the results,
i.e. why did a particular method work well/did not work well?
-	Conclusion and future work: briefly summarize your results and list opportunities for future research that seem promising to you but for which you did not find the time within this term.

You must format your submission using the [NeurIPS 2024 LaTeX style file](lecture_files/Styles-Neurips-ML.zip) using the “preprint” option (\usepackage[preprint]{neurips_2024})  or the [NeurIPS 2024 Word template](lecture_files/neurips_2024-word-template.docx) for non-anonymous preprints posted online. Following the Neurips standard (one of the primary conferences in ML, see [here](https://neurips.cc/Conferences/2024/CallForPapers)), the main text of the report is limited to **nine content pages**, including all figures and tables. Additional pages containing references do not count as content pages. The main text and references may be followed by technical appendices (more details about the methods used and the ones that did not lead to good results), for which there is no page limit. *Do not forget to upload the zip file of the final project code*.

**The individual report**: (1 upload per student) You will also submit a brief individual report (at most one page), which will: (1) Describe the parts of the project you worked on (which machine learning methods you applied, which preprocessing steps you performed on the data, which parts of the term paper you wrote, who you worked with on what parts, etc.) and what parts of the project your teammates worked on. (2) What you learned from the project.
The purpose of the individual report is to facilitate fair grading and to allow the instructor to understand well what you learned from the project.

**Some advice** (mostly taken from csc2515 at UofT):

- **Be selective!** Don't choose a project that has nothing to do with machine learning. Don't investigate an algorithm that has a high chance of failing or being un-implementable. Don't attack a problem that is irrelevant, ill-defined or unsolvable. Spend most of your time doing machine learning and not related things such as pre-processing your data.
- **Be honest!** You are not being marked on how good the results are. It doesn't matter if your method is worse than the ones you compare to provided you implemented it properly. What matters is that you try something sensible and clearly describe the problem, your method, what you did, and what the results were.
Be modest! Don't pick a project that is way too hard. Usually, if you select the simplest thing you can think of to try, and do it carefully, it will take much longer than you think.
- **Be careful!** Don't do foolish things like test on your training data, set parameters by cheating, compare unfairly against other methods, include plots with unlabeled axes, use undefined symbols in equations, etc. Do sensible cross-checks like running your algorithms several times, leaving out small parts of your data, adding a few noisy points, etc. to make sure everything still works reasonably well. Make lots of pictures along the way.
- **Learn!** The point of the project is to give you a chance to "test drive" the process of doing machine learning. Consider this an opportunity to learn how to write code to run large experiments, make nice figures, layout readable equations, describe your work concisely to a smart but uninitiated reader, etc.
- **Have fun!** If you pick something you think is cool, that will make getting it to work less painful and writing up your results less boring.

**Samples of previuos projects**
- [Presentations](https://github.com/gfarnadi/gfarnadi.github.io/blob/master/courses/MLW2023/assignments/Machine_Learning_Presentation.pdf)

**Intresting dataset**

To find interesting datasets for your project, you can check: 
- [Kaggle](https://www.kaggle.com/competitions)
- [UCI: Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.php)
- [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)


