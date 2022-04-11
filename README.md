# Wordle Answer

This python package allows you to get today, yesterday and tomorrow's Wordle answer!

## Install

To install, run the following line in the command prompt / terminal:

```
pip install wordleanswer
```

## Code Example

```
import wordleanswer

# Answers

todaysAnswer = wordleanswer.getAnswer()
yesterdaysAnswer = wordleanswer.getYesterdayAnswer()
tomorrowsAnswer = wordleanswer.getTomorrowAnswer()

# Getting answers in the past and future

# Answer for 100 days ago

print(wordleanswer.getPastAnswer(100))

# Answer in 100 days

print(wordleanswer.getFutureAnswer(100))
```
