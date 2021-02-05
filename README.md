🔎Multiclass Multilabel Prediction for Stack Overflow Questions
This notebook builds an end-to-end multi class multi label prediction for stack overflow questions.

1. Problem
Given text for the Questions , predict tags associated with them

2. Data
The data we're using is from Kaggle's StackSample: 10% of Stack Overflow Q&A.

https://www.kaggle.com/stackoverflow/stacksample

3. Features
Some information about the data:

This is organized as three tables:
* **Questions:** contains the title, body, creation date, closed date (if applicable), score, and owner ID for all non-deleted Stack Overflow questions whose Id is a multiple of 10.
* **Answers:** contains the body, creation date, score, and owner ID for each of the answers to these questions. The ParentId column links back to the Questions table.
* **Tags:** contains the tags on each of these questions.
