# FingersTrainingProgram

Summary
---
  A program to help user improve fingers flexibility and coordination.

(v1.0.0) Development Process
---
  ### Requirements
    > Generate some marks like '*' in different columns and check user hit keyboard at correct position.
    > That's fine that run the program in terminal first.
  
  ### Design
    > Start running program.
    > Generate 10 rows each row has one '*' and at different columns randomly then wait for user's input.
    > Get user's input then check if user hit correct position.
    > if user hit correct, pop bottom rows and generate a new row with one '*' at random column to the top.
    >> else user's fault increase.
    > if user's fault more than 3 times, exit program.
