# MP_homework1

This is the slightly modified version of our lab assignment. I apologize for not completing the homework by doing from the scratch, beacuse of shortage time I had, 
and finding out about the homework assignment too late (seems like I skipped the messages regarding it in the telegram chat).

I added stateful widgets to the project by introducing the MainPage widget which is a StatefulWidget (it exteds StatefulWidget class, it allows to change the state
of the widget during the interaction with the user), and it has associated State class - _MainPageState. Also,  the build method is overridden in the _MainPageState 
class. This method is responsible for building the widget's user interface based on its current state.

The setState method is used in the incrementNumber and decrementNumber methods to show that the internal state of the widget has changed. When setState is called, 
Flutter rebuilds the widget by calling the build method again with the updated state.

The stateful widget is needed to change the textfield with "Your secret number: " text, so when the user interacts with the 'Increment'/'Decrement' buttons, the text
of the textfield also changes respectively.

One more time, I apologize for my incomplete work, and will do my best to perform better in upcoming assignments. 
Thank you.
