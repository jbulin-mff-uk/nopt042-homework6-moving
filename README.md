# Homework: moving

Generalize the moving problem from the tutorial to include:
* trolleys: some items require a one or more trolleys to be moved; we have a certain amount of trolleys
* precedence: some items need to be moved before other items (given as a list of pairs), `{item1,item2}` means that moving of item1 must be finished before moving of item2 starts.

See the `hw-instance.pi`. Your model should accept a filename, e.g.
```
picat moving.pi hw-instance.pi
```
The autograder will only test for the presence of the optimal time (in minutes), in this case `165`, in the output. But include also some reasonable description of the schedule.