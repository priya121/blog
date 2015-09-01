title:  Throwing Exceptions
___

Throwing an exception is a way of handling an error that a method may produce for a specific reason that was expected by the programmer who wrote it.

In java a complier will not let you compile a method if an exception is written that has not been handled or specifically declared.

Even though it is possible to declare that the main method throws the exception, it is always nicer to pass the declaration to another method and print a message to the user after another method has caught the exception. It is also good practice to tell the user how to address the error if at all possible.
