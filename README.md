# ProjectRuby2

-Program Input
  The program should prompt the user with a question an appropriate responses.

-Program Calculation
  The program will calculate the number of correct and incorrect responses and will display a
  message to the user indicating the percentage of correct responses.

-Program Output
  Sample output for this program is displayed on the next page.


""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
Welcome to the Question and Answer Program
Please select the correct answer for each question
1. Ruby syntax is similar to Python?
(a) True
(b) False
(c) They are identical
(d) Ruby does not have syntax
Answer: c
Oops - the correct answer is a
2. What text editor can you use to create a Ruby Program?
(a) Microsoft Word
(b) Microsoft Paint
(c) Rich Text Editor
(d) Komodo
Answer: d
Correct
3. In the following for loop, how many times will I love cheese
print? for num in 0..5 puts 'I love cheese' end (a) 0
(b) 3
(c) 4
(d) 5
Answer: c
Correct
4. Ruby allows for the if/elsif?
(a) Only if the the if/else is used first
(b) Only if the the if/then is used first
(c) True
(d) False
Answer: c
Correct
5. Ruby only allows lower case variable names
(a) True
(b) False
Answer: b
Correct
You correctly answered 4 out of 5 questions which is 80.0%

"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""

The program should initialize 2 arrays:
• questions array should be similar to the following - questions =
[“Question ...?\n(a) Ans A\n(b) Ans B\n(c) Ans C\n(d) Ans D\n”, ... ]
• answers array should be similar to the following – answers = [“c”, ...]
The program should loop through all the questions and check the user answers against the answers
array. You may use any loop you like. Ruby has a each_with_index method which will allow
you to iterate through the questions.
The question numbers must not be stored in the questions array. These numbers are generated
when you loop through the array.
