# Capstone Final Report
### NLP Model to Identify Math Student Misconceptions
![](image.png)

Students’ written explanations of their mathematical reasoning provide valuable insight into their thinking and can reveal systematic misconceptions, such as applying whole-number logic to decimals (e.g., reasoning that 0.355 is greater than 0.8 because 355 > 8). These misconceptions arise when students misapply prior knowledge or misunderstand new concepts, and while tagging such responses is useful for diagnostic feedback, the process is labor-intensive and difficult to scale. The Misconception Annotation Project (MAP), a Kaggle competition hosted by Vanderbilt University and The Learning Agency, was designed to address this challenge by encouraging the development of Natural Language Processing (NLP) models capable of identifying student misconceptions across diverse math problems. By leveraging machine learning to automate this process, the project aimed to predict when a student’s answer contains a misconception, and what type of misconception they have, thus improving feedback and supporting more effective learning experiences for students.

### Results
A LightGBM model that predicted whether a student had a misconception and the type of misconception with an F1 score = 0.75. 