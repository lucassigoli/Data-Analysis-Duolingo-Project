# duolingo-project
This project aims to develop a Data Analyst Project, analyzing a database with 13 million lines that contains information from Duolingo users

.
**INTRODUCTION:**

I have been studying a lot of German and, having a streak of over 200 days on Duolingo, I decided to promote this study.

I downloaded a database from Kaggle with over 13 million rows, which contains 12 columns. 

The columns are as follows:

- p_recall - proportion of exercises from this lesson/practice where the word/lexeme was correctly recalled
- timestamp - UNIX timestamp of the current lesson/practice
- delta - time (in seconds) since the last lesson/practice that included this word/lexeme
- user_id - student user ID who did the lesson/practice (anonymized)
- learning_language - language being learned
- ui_language - user interface language (presumably native to the student)
- lexeme_id - system ID for the lexeme tag (i.e., word)
- lexeme_string - lexeme tag (see below)
- history_seen - total times user has seen the word/lexeme prior to this lesson/practice
- history_correct - total times user has been correct for the word/lexeme prior to this lesson/practice
- session_seen - times the user saw the word/lexeme during this lesson/practice
- session_correct - times the user got the word/lexeme correct during this lesson/practice

At the beginning, it looks complicated the columns, but with time it will be more understandable.

Since this is my first project, I decided to draw a lot of inspiration from an existing project. Reference: https://www.kaggle.com/datasets/aravinii/duolingo-spaced-repetition-data/data

.
**QUESTIONS TO ANSWER IN THIS STUDY:**

- Basic information (total users, total lerned languages, total words learned, correct practices rate) *- Completed*
- Most frequently learned languages *- Completed*
- Most difficult languages learned by english speakers *- Completed*
- What are the most challenging grammatical parts *- Completed*
- Strategies for Duolingo app usage growth *- Completed*
- Consecutive days engagement *- In progress*
- Deep diving into days usage behavior *- In progress*
- Does the time since the last practice imply a greater probability of failure? *- In progress*

.
**OBSERVATION:**
- This is my first big project using Kaggle and Python. I learned a lot from the project and I know I still have a long way to go, but I'm proud to have gotten this project off the ground.
