# Math Quiz

A simple quiz tool that generates random math questions. Pick a topic, a level and the number of questions, answer them one by one, and see your score with a review of the mistakes.

It is a single `index.html` file with no libraries and no internet connection needed. Built with HTML, CSS and JavaScript.

## Features

- 8 topics: addition, subtraction, multiplication, division, percentages, solving for x, squares/cubes/roots, and mixed review
- 3 levels (easy, medium, hard) and 5, 10, 15 or 20 questions per quiz
- The correct answer is shown after every question
- Final score, time taken, and a list of the questions you missed
- Accepts Arabic-Indic digits (٠-٩) as well as 0-9
- Works on phones and computers, and can be used with the keyboard only

## How to use

1. Open `index.html` in any browser, or visit the live page (see below).
2. Choose a topic, level and number of questions, then press **Start quiz**.
3. Type your answer and press Enter to check it. Press Enter again for the next question.

## Run it online with GitHub Pages

In the repository go to **Settings → Pages**, choose the `main` branch and the root folder, then save. The page will be available at `https://GrandMaster-samer.github.io/<repository-name>/`.

## How it works

Each topic has a generator function in `index.html` that builds a question and its answer using random numbers. Division and percentage questions are built from the answer backwards, so every answer is a whole number. To add a new topic, write a new function in the `GEN` object, add it to `TOPIC_NAMES`, and add an option to the topic menu.

## License

MIT. See the `LICENSE` file.
