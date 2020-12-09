# Winning Jeopardy

Jeopardy is a popular TV show in the US where participants answer questions to win money.

In this project, I'll work with a dataset of Jeopardy questions to figure out some patterns in the questions that could help you win.

The dataset contains 20000 rows from the beginning of a full dataset of Jeopardy questions, which can be downloaded [here](https://www.reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/).

### Summary of results:
- There are about 6% of the answers are contained in the question itself. The percentage is really low, it means if there are 100 words in the answer, only in average 6 of them world appear in the question. It's not reasonable to find the answer in the question.
- There are about 69% of the terms in a question have been repeated. The percentage is quite hight and it affects the studying strategy for Jeopardy because most of the terms used in the past are likely to appear in the future questions.
- None of the terms had a significant difference in usage between high value and low value questions. Additionally, the frequencies were all lower than 5, so the chi-squared test isn't as valid. It would be better to run this test with only terms that have higher frequencies.
