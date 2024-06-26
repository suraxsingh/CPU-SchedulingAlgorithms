# CPU-SchedulingAlgorithms
An implementation of various CPU scheduling algorithms in C++. The algorithms included are First Come First Serve (FCFS), Round Robin (RR), Shortest Process Next (SPN), Shortest Remaining Time (SRT), Highest Response Ratio Next (HRRN), Feedback (FB) and Aging.
# Input Format
Line 1: "trace" or "stats"
Line 2: A comma-separated list of CPU scheduling policies to analyze/visualize, with parameters if applicable. Each algorithm is represented by a number. Round Robin (2) and Aging (8) have a quantum parameter q (e.g., 2-4 means Round Robin with q=4, 8-1 means Aging with q=1).
1.FCFS (First Come First Serve)
2.RR (Round Robin)
3.SPN (Shortest Process Next)
4.SRT (Shortest Remaining Time)
5.HRRN (Highest Response Ratio Next)
6.FB-1, (Feedback where all queues have q=1)
7.FB-2i, (Feedback where q= 2i)
8.Aging
Line 3: An integer specifying the last instant to be used in your simulation and to be shown on the timeline.

Line 4: An integer specifying the number of processes to be simulated.

Line 5: Start of description of processes. Each process is to be described on a separate line. For algorithms 1 through 7, each process is described using a comma-separated list specifying:

1- String specifying a process name
2- Arrival Time
3- Service Time

Note: For Aging algorithm (algorithm 8), each process is described using a comma-separated list specifying:

1- String specifying a process name
2- Arrival Time
3- Priority
