# LFUD: Logical Fallacy Understanding Dataset

LFUD contains 4,020 (QA) instances in total, involving 5 LFU tasks and 12 logical fallacy types, which stem from the 67 propositions and 804 sentences with logical fallacies.

## Data Format
Each line in the file contains the original propositions, logical fallacy sentences and corresponding task instances. 

- proposition: Original propositions used for generating logical fallacy sentences.
- sentence: Sentences with specific type of logical fallacy.
- fallacy_type: The specific type of logical fallacy in the sentence.
- task1:
  - Identify whether the given sentence has logical fallacy.
  - Task1 contains questions and corresponding answers.
- task2:
  - Select the sentence belonging to a certain type of logical fallacy.
  - Task2 contains questions, options and corresponding answers.
- task3:
  - Derive the conclusion from the premise according to a certain type of logical fallacy.
  - Task3 contains questions, options and corresponding answers.
- task4:
  - Infer the premise from the conclusion according to a certain type of logical fallacy.
  - Task4 contains questions, options and corresponding answers.
- task5:
  - Correct the logical fallacy in the given sentence.
  - Task5 is a generation task with no fixed answers. So task5 only contains questions.

More details on the dataset, results and analyses can be found in our paper.
