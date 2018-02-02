# Template for Google Hash Code
to make it easier to deploy an incremental approach

Run a testinstance on the format ```in/$testcase.in``` with your own solver by:

```python main.py --nsspec $file:$score:$solve $testcase``` where 
- ```$file``` is the file with your functions ```$score``` and ```$solve```
- ```$score``` is the function name of your scoring function
- ```$solve``` is the function name of your solution function

```main.py``` will handle file-io, save the solution that gets maximal score, set up logging, set up randomization.
