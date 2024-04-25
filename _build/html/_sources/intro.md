# **k-Means Parallelization**

➡️ Objectives : 

1) Program the k-means algorithm from scratch. 
2) Apply it to 1 Million data.
3) Calculate the optimal value of k (computationally heaviest part as it requires to run the algorithm repeatedly). 
4) Parallelize point 3) with multiprocessing and multithreading. 
5) Analyze computation times and speedups with respect to the serial (non-parallelized) version. 

➡️ Conclusions: 

🔸 Computational intensity: the selection of the optimal value of k is the most computationally expensive of the program, consuming most (97%) of the execution time. 

🔸 Advantages of parallelisation: to cope with the computational load, parallelisation techniques that improve efficiency were employed. 

🔸 Starmap method: Among the various multiprocessing methods used, starmap() was the most effective in delivering superior results. 

🔸 Performance improvement: Parallelism significantly improves performance. The serial approach takes almost 4 minutes for 1 Million data, while the multiprocessing and threading approaches complete the task in less than 1 minute, achieving a speedup of more than 4 times.


```{tableofcontents}
```
