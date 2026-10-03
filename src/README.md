# IT313 REACT STATE&HOOKS

## Problem

this activity is a lab timer & practice tracker for students during laboraoty sessiions. it tracks the number of practice problems solved and the amount of time spent working.

## Approach

the activity uses react native state and hooks.

-useState manages the solved count and running state.

- useEffect manages the Stopwatch interval.
- A cleanup function clears the interval.
- Conditional rendering displays "Great Job!" and "Running" .
- Lifting state up allows Practice Tracker and Stopwatch to share state through LabScreen.
- useStowatch is a custom hook for the Stopwatch logic.

## how to run

1. open the activity in Vs code.
2. install the project dependencies.
3. start the expo development server.
4. open the project using expo go.
5. test the solve +1, reset ,start, and stop buttons.
