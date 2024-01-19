# Coding a teacher's story problem generator

## Assigned

Friday, 19 Janurary 2024

## Due (Firm-deadline)

Friday, 19 January, 2024 by 11:30am (firm deadline)

## Goals

- To practice using basic constructs in Python programming
- To practice using GitHub to submit work
- To gain skill in implementing logical mechanisms in programming.

## Project Overview

This programming project invites you to implement a program that presents the user with a mathematical story problem, such as the type that might be found in a young person's mathematics textbook. The story problem will collect TWO numerical values from a _teacher_ user and ONE from a student. The program gives output to the student about the correctness of his or her inputted answer.

## Your Source Code

Please locate the edit the File: `src/storyProblem.py` which is located in your repository.

### Steps

- The story problem is incomplete and will ask  the _teacher_ to complete the story problem by inputting TWO numerical values.

- The program will insert these values into a string that the _student_ will see.

- The program presents the completed story problem to the _student_ and asks for a correct answer using the _teacher's_ inputted values.

- The program calculates the correct answer. This value is compared to the _student's_ inputted answer. A statement is then outputted to let the student know whether the answer was correct.

### Example output

```
(Program outputs)
Incomplete story problem:
"What value do you get with you raise FIRST_VALUE by the power of SECOND_VALUE?"

(Teacher's input)
Enter the FIRST_VALUE: 2
Enter the SECOND_VALUE: 7

(Program outputs)
Completed story problem:
"What value do you get with you raise 2 by the power of 7?"

(Student's input)
Enter the result of the above story problem: 127

(Program calculates correct results and outputs)
The correct value is 127. You answered the problem correctly!
```

In your own story problem and code, please be creative!

---

## GatorGrade Checking

You can also use `gatorgrade` to check the baseline requirements of this assignment by running the following command in your terminal:

`gatorgrade --config config/gatorgrade.yml`

If `gatorgrade` shows that all checks pass, you will know that you have met baseline requirements of this project.

## Submission

As you are working, you are to commit and push regularly. The commands are the following.

```bash
git add -A
git commit -m ``Your notes about commit here''
git push
```

After you have pushed your work to your repository, please visit the repository at the GitHub website (you may have to log-in using your browser) to verify that your files were correctly sent.

## Project Assessment

This is a check mark grade.

## Seeking Assistance

Students who have questions about this project outside of the class or lab times are invited to ask them in the course's Discord channel or during instructor's or TL's office hours.
