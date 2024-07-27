# Task
We have a large and complex workflow, made of tasks. And
have to decide who does what, when, so it all gets done on time.
All tasks have dependency on other tasks to complete
Each task(t) has a
D[t] = duration of task
EFT[t] = the earliest finish time for a task
LFT[t] = the latest finish time for a task
EST[t] = the earliest start time for a task
LST[t] = the last start time for a task
Assume
that “clock” starts at 0 (project starting time).
We are given the starting task T_START where the EST[t] = 0 and LST[t] = 0
You have to write a Python console application to answer the following questions
Earliest time all the tasks will be completed?
Latest time all tasks will be completed?
