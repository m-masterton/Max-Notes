202301041546
Status: #Note
Tags: [[Computer Science]] [[Operating Systems]]

___

The CPU must be able to react to events as they occur, regardless of what it is doing at the time. For example when a key press is registered, the character must be typed in and the screen must be updated accordingly.

There are 2 methods of handling this, **polling** and **interrupts**.

### Polling

>[!defi] Definition (Polling)
>**Polling** is the regular checking of an event to see whether or not it has occurred.

>[!eg] Example
>Imagine parents driving somewhere with an impatient child in the back seat. The child keeps asking "Are we there yet, Are we there yet, Are there yet". The child is 'polling' the parent over and over again. This works, but is inefficient as most of the time the answer is 'No' and yet time is taken up answering the question.

It is similar in the CPU where the program currently running will be checking regularly to see if any related peripherals or events require additional action. The **advantage of polling** is that is very simple and predictable, as polling only occurs at specific points while the software runs. The **disadvantage of polling** is that it may be inefficient in terms of eating up CPU processing time

### Interrupts

>[!defi] Definition (Interrupt)
>An **Interrupt** is a signal for the CPU to stop doing what it is doing and instead carry out the interrupt task. Once the task is complete, the CPU goes back to doing whatever it was doing before.

The CPU is running its current program an interrupt arrives.
___
### References