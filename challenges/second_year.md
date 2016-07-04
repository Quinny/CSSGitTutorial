# Second year challenge - Event Driven Programming Framework

[Event driven programming](https://en.wikipedia.org/wiki/Event-driven_programming)
is a paradigm commonly used in graphical frameworks such as Java Swing.  The two
main primitives in event driven programming are Events and Handlers.  Each
event has an associated set of handlers which are invoked every time the event
is fired.  For example, if you create a submit button on a website, you would
define an event for it being clicked and a handler which carrys out the desired
functionality.


Your challenge is to define a simple event driven programming framework.  The
implementation details are left mostly up to you, but your framework must support
the following operations:

*Feel free to write the code in the language you are most comfortable with, but
the examples will be provided in Java.*

### Attaching multiple handlers to an event

Each event can be associated with zero or more handlers that will all be invoked
when the event is fired.

```java

EventManager eventManager = new EventManager();
eventManager.registerEvent(new Event("MouseClick"),
                           new ClickHandler(/* Do stuff */));

// This should attach a second handler in a way that both will be called when the
// event is fired.
eventManager.registerEvent(new Event("MouseClick"),
                            new ClickHandler(/* Do Stuff */));

```

The user of your interface should be able to easily define their own handlers
which carry out arbitrary work.

### Firing events

You should be able to manually fire events using your interface.

```java

// Invoke all handlers associated with MouseClick event
eventManager.fire(new Event("MouseClick"));

```

Your implementation need not resemble the above, but it should support
the two listed operations.

## Hints

* Decide how you will define an Event
* Decide how you will define a Handler
* Brainstorm which datastructure works best for maintaing the event-handler
relationship
