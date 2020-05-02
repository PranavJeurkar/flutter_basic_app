# flutter_basic_app

A new Flutter application.

The BLoC pattern uses Reactive Programming to handle the flow of data within an app.It receives streams of events/data from the source, handles any required business logic and publishes streams of data changes to widgets that are interested in them.Theis my first app built using bloc pattern which i have learnt through online tutorials.

This a basic flutter app that i have built using bloc pattern.
This is a just basic app that increments and decrements the counter.
The bloc takes in events and which state it should output.
We are inputting the numbers in the sink and outputting in stream.
We could take input in sink output will through stream and then listen that event and map that event to a new state.
In the function of map event to state we increment or decrement counter the next step is important where we add the value of counter to the sink of counter state controller and further output through stream.
The function dispose is used to close stream controllers so that there will be no memory leaks.
The bloc pattern is very useful when we have a large no of states in our application.
The strem builder is used to manage the streams.
