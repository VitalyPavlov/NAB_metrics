# Fork version of Numenta Anomaly Benchmark metrics #

Modified version Numenta Anomaly Benchmark <https://github.com/numenta/NAB>

Now it is very easy to use NAB-metrics for offline algorithms of anomaly detection.

```md
Parameters:
y_true:               (int)   Ground truth anomaly labels {0, 1}
y_predict:            (float) Probability from anomaly detection algorithm [0, 1]
probationaryPercent:  (float) Percent of each data file not to be considered during scoring
type_profile:         (str)   type of Cost matrix to weight the true positives, false negatives, and false positives during scoring (e.g. 'standard', ‘reward_low_FP_rate’, ‘reward_low_FN_rate’)
```
