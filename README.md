# ACM Research Tasks

This repository contains my work for the ACM Research Tasks. It has three main parts — a small Python task, a blog review, and a research paper summary.

## 📁 Folder Structure

```text
Radhika_Korade_ACMRResearchTasks/
│
├── README.md
│
├── task0/
│   └── transform_logs.py
│
├── task1/
│   └── blog_review.md
│
├── task2/
│   └── paper_summary.md
│
└── bonus/
    └── eda.ipynb
```

## Task 0 – Sneaky Log Cleaner

For this task, I made a small Python program that takes messy log-like text and cleans it up.

It can:

* Hide email addresses by replacing them with `[HIDDEN]`
* Convert date and time formats into a more readable form
* Add 🚨 before `ERROR`
* Remove unnecessary spaces

I used basic Python along with `re` and `datetime`. I also tested it in Google Colab to make sure the transformations were working properly.

## Task 1 – Blog Review

For this task, I read **“Can Your Camera Tell if You're Bored in Class?”**

The blog talks about using computer vision and facial landmarks to understand expressions and possibly detect things like boredom. I found the idea interesting because it shows how something as simple as a camera can be combined with AI to analyse facial movements.

**Blog:** [Can Your Camera Tell if You're Bored in Class?](https://medium.com/@samikshapatil486/can-your-camera-tell-if-youre-bored-in-class-bfece6871e58?utm_source=chatgpt.com)

My review is in `task1/blog_review.md`.

## Task 2 – Research Paper Summary

For this task, I read **“Ten Simple Rules for Reading a Scientific Paper.”**

The paper explains how to approach research papers without getting stuck trying to understand everything at once. The point I found most useful was to **read the abstract first and check if the paper is actually relevant**. After that, the introduction, methods, results, discussion, conclusion and references can be used to understand the research properly.

**Paper:** [Ten Simple Rules for Reading a Scientific Paper](https://www.researchgate.net/publication/343331371_Ten_simple_rules_for_reading_a_scientific_paper?utm_source=chatgpt.com)

My summary is in `task2/paper_summary.md`.

## Bonus

The `bonus/` folder contains `eda.ipynb` for the optional bonus task.

## Overall

These tasks were a nice mix of **coding and research**. I got to work with Python, read about a computer-vision application, and learn how to approach research papers more effectively. The main thing I took away is that research isn't just about finding information - it's also about knowing **what to look for, understanding it, and explaining it in your own words**.
