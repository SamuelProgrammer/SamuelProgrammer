1. Display the question along with the available answer choices.

2. Disable the check button by default.

3. Add event listeners to the answer choices.

4. When an answer choice is selected, enable the check button.

5. Add an event listener to the check button.

6. if the 'Check' button is clicked,

7. if the selected answer choice is correct.

1. Set the trial to 0.
2. Display a message indicating that the answer is correct and an explanation with active tooltips for the question, answer choices, and explanation.
3. If the current question is not the last question:
  1. Replace the check button with a continue button.
  2. if the continue is pressed, open the next question
4. If the current question is the last question:
  1. Remove the continue button and display nothing.

1. If the selected answer choice is incorrect and trial is less than or equal to 2:
  1. Increase the trial count by 1.
  2. Display a message indicating that the answer is incorrect, and a message "try again" and how many trials are left.
  3. Disable the selected incorrect answer and the check button
  4. When another answer is selected, enable the check button
  5. If the check button is clicked,
    1. Increase the trial count by 1.
    2. check if the selected choice is correct
    3. if the selected answer choice is correct

1. Highlight the correct answer
2. Set the trial count to 0.
3. Display a message indicating that the answer is correct and an explanation with active tooltips for the question, answer choices, and explanation.
4. If the current question is not the last question:

    1. Replace the check button with a continue button.
    2. if the continue is pressed, open the next question

1. If the current question is the last question:

    1. Remove the continue button and display nothing.

1. disable all previous question choices

    1. if the choice is incorrect
      1. Display a message indicating that the answer is incorrect, and a message "try again" and they have left only one chance.
      2. Disable the selected incorrect answers and the check button
      3. When another answer is selected, enable the check button
      4. If the check button is clicked,
        1. Increase the trial count by 1.
        2. check if the selected choice is correct
        3. if the selected choice is correct and trials === 2,
          1. set trial = == 0
          2. Display a message indicating that the answer is correct and an explanation with active tooltips for the question, answer choices, and explanation.
        4. if the selected choice is incorrect
          1. set trial === 0
          2. Display a message indicating that the answer is incorrect and an explanation with active tooltips for the question, answer choices, and explanation.
        5. if the current question is not the last question
          1. replace the check button with continue button
          2. if the continue button is pressed, open the next question
        6. if the current question is the last question
          1. remove continue button and display nothing
