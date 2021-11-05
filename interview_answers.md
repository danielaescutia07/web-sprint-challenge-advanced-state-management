# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
    It helps resolve props drilling.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Actions are functions that return an action. Reducers take state and action and return new state. Store is what hold the state of the application which begins in the reducer.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
    It evaluates the operation before reaching the reducer and dispatch action creator when certain conditions are met.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
    I really don't have a favorite, each is a bit different with pros and cons.