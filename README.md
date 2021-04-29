# Graph Theory Project 2021

## Due: last commit on or before 3<sup>rd</sup> May 2021


These are the instructions for the Graph Theory project in 2021.
There are several parts but overall, it is worth 100% of the marks for this module.
All aspects of the project will be covered during the semester.
You should complete the different parts of the project following the timelines indicated in video lectures during the semester.
As you complete various parts of the project, you should commit and push your work to a GitHub repository, as described below.
Please also read the **[Using git for assessments](https://github.com/ianmcloughlin/using-git-for-assessments/raw/master/using-git-for-assessments.pdf)** document which applies to this project.
As always, you must also follow [the code of student conduct and the policy on plagiarism](https://www.gmit.ie/general/quality-assurance-framework).


To start, you must create a new repository in GitHub.
You should take the URL of your repository and immediately submit it using the form on the Moodle page.
The URL should look something like `https://github.com/your-username/graph-theory-project`.
You must also set your repository to **private** and add `ianmcloughlin` as a **collaborator**.
You should then clone your repository to your own machine and start working on the project as described below.
You should make regular, appropriate commits to your repository and push these to GitHub.
The last commit you make and push to GitHub before the deadline will form your submission.
There is no problem if you want to keep working on your repository after the deadline, but there is no guarantee that that work will be graded.


## What to do

In this project you must write a program in the [Python 3](https://wiki.python.org/moin/BeginnersGuide) programming language to search a text file using a regular expression.
Your program must take a regular expression and the name or path of the file as command line arguments and output the lines of the file matching the regular expression.
You have a lot of freedom in how you interpret the term *regular expression*, as will be discussed in class.
It will likely be easier to limit yourself to [regular languages](https://en.wikipedia.org/wiki/Regular_language).

The program must be coded from scratch.
You cannot use any external libraries other than what is included in Python, and you cannot use the `re` package included there.
Any extra features added to your script must be your own work.
You must also include tests which run upon `python script.py --test` being called, as will be described in lectures.
The tests should ensure that your regular expression engine works on a sensible example list of inputs.


## Your README
You should include a README that contains at least the following items.

- A **description** of your repository and its contents pitched at a knowledgeable outsider.
- **Instructions** stating how to run and test your program.
- An **explanation** of your algorithm.
- **Answers** to each of the following three questions, up to 500 words each:
    - What is a regular expression?
    - How do regular expressions differ across implementations?
    - Can all formal languages be encoded as regular expressions?
    

## Marking scheme

The following marking scheme will be used to mark your submission out of 100%.
The examiner's overall impression of your submission may influence marks in each individual component.
It is important that your submission provides direct evidence of each of the items listed in each category.
For instance, your commit history should demonstrate and provide evidence that you had a pragmatic attitude to completing the assessment.
Likewise, your submission should have references in it to demonstrate that you considered the literature and the work of others.
  

| Weight | Category | Description |
|---|---|---|
|25% | Research | Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software or libraries used. |
|25% | Development | Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind. |
|25% | Consistency | Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others. |
|25% | Documentation | Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README. |


## Resources

Here is a list of resources you might review to complete this project.

1. [*Regular Expressions: Regexes in Python*, Real Python,<br> https://realpython.com/regex-python/](https://realpython.com/regex-python/)
2. [*Regular Expression Matching Can Be Simple And Fast*,Russ Cox,<br> https://swtch.com/~rsc/regexp/regexp1.html](https://swtch.com/~rsc/regexp/regexp1.html)
3. [*Python Command Line Arguments*, Real Python,<br>https://realpython.com/python-command-line-arguments/](https://realpython.com/python-command-line-arguments/)
4. [*Git Handbook*,GitHub,<br>https://guides.github.com/introduction/git-handbook/](https://guides.github.com/introduction/git-handbook/)
