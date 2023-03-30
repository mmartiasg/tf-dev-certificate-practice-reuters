# tf-dev-certificate-practice-reuters

Type: Multiclassification problem

Dataset: Reuters datasets with 46 topics at least 10 samples for each one.

Baseline: random selection topics will give an accuracy around 19% on validation, thus this is the metric to beat

Conclusion:
 
Parameters:
- NUM_WORDS: 10000
- 1 layer with 64 units to avoid information bottleneck
- Give us an accuracy around 79.8% on validation but it will start to overfit after 10 or so epochs.
- By reducing the NUM_WORDS reduce ofcourse the overfit but if reduce too much (lets say to 100) the accuracy drops to 68%.
- The same happens fi the units are reduced.
