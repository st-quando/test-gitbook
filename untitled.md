# page 2

## Thunk and Saga comparison 2

| Aspect / type of Redux | Reduct Thunk | Redux Saga |
| :--- | :--- | :--- |
| github stars | 14.6k | 20.3k |
| concept | a thunk is a function that acts as a wrapper in that it wraps an expression to delay its evaluation | a saga is similar to a separate thread in your application that’s solely responsible for side effects |
| utilization | utilizes callback functions | utilizes a new ES6 feature called generators |
| access Actions, State | access to the full Redux application state and it can dispatch Redux actions as well | access to the full Redux application state and it can dispatch Redux actions as well |
| Threads | isolation | started, paused and cancelled from the main application with normal Redux actions. |
| Props | - great for small use cases and for beginners | - Avoid callback hell - Easy to test |
|  |  |  |

