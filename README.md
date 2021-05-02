# Component Life Cycle
Component Life Cycle
Every React Component goes through three phases throughout its lifetime:
•	Mounting Phase
•	Updating Phase
•	Unmounting phase

![image](https://user-images.githubusercontent.com/46521639/116803722-d4ff8a80-ab37-11eb-8fe8-9b70e56f30c4.png)
![image](https://user-images.githubusercontent.com/46521639/116803667-63274100-ab37-11eb-8c71-28ac9447443b.png)
![image](https://user-images.githubusercontent.com/46521639/116803687-8651f080-ab37-11eb-84dd-c8f2a3428d5f.png)
![image](https://user-images.githubusercontent.com/46521639/116803695-97026680-ab37-11eb-8bea-30249b4b67f5.png)
![image](https://user-images.githubusercontent.com/46521639/116803701-a84b7300-ab37-11eb-8f60-29562cdee684.png)

-Mounting Phase
In this phase, the instance of a component is created and inserted into the DOM.
We mainly use the three methods. The three methods are called in the given order:
•	constructor()
•	render()
•	componentDidMount()
-constructor()
The constructor() method is used to set up the initial state and class variables

-Updating Phase
In this phase, the component is updated whenever there is a change in the component's state.
Method :-
render( ):-
The render() method is called whenever there is a change in the component's state.

-Unmounting Phase
In this phase, the component instance is removed from the DOM.
componentWillUnmount()
The componentWillUnmount() method is used to cleanup activities performed.
Example: clearing timers, cancelling API calls, etc.

The show-hide-clock-react example explains all these concepts 
