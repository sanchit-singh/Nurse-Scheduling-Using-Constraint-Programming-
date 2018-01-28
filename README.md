# Nurse-Scheduling (Constraint Programming demonstration)

1. This code is a demonstration of using Constraint Programming (CP) to a well knwon Nurse scheduling problem using Google OR-Tools solvers in Python.
2. Whereas a traditional mathematical programming approach is aimed at delivering good quality solution, CP is used when the user is interested in number of feasible solutions.
3. CP works well with combinatorial problems and can handle a non-linear or possibly even a blackbox type for evaluating constarints with relative ease both in terms of formulating the model as well its solution.

### Nurse scheduling problem

A hospital supervisor needs to create a weekly schedule for four nurses, subject to the following conditions:

- Each day is divided into three 8-hour shifts.
- On each day, all nurses are assigned to different shifts and one nurse has the day off.
- Each nurse works five or six days a week.
- No shift is staffed by more than two different nurses in a week.
- If a nurse works shifts 2 or 3 on a given day, he must also work the same shift either the previous day or the following day.

