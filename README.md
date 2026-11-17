# Number Theory: Addition

In this lab, you’ve learned about One Hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name Kade Burback Kenny Shannon

## Summary
We implemented two different state machines in this lab, the One Hot and Binary state machines. 
## Lab Questions

### Compare and contrast One Hot and Binary encodings
One Hot assigns a dedicated flip-flop to every state while Binary packs states into the minimum possible number of 
registers. One Hot requires less combinational decoding logic while Binary requires more.

### Which method did your team find easier, and why?
We found the One Hot easier as the Binary took more thinking and we had to rewrite the Binary file multiple times.

### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.
The One Hot makes sense doing a smaller implementation quicker, but it does not scale very well. For larger scale implementations, the Binary make more sense to use.
