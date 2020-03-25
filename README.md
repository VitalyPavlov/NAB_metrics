# Fork version of Numenta Anomaly Benchmark metrics #

Modified version Numenta Anomaly Benchmark <https://github.com/numenta/NAB>

Now it is very easy to use NAB-metrics for offline algorithms of anomaly detection.

Parametrs:

```
y_true - numpy array int {0,1}
y_predict - numpy array float [0, 1]
probationaryPercent - float [0, 1]
type_profile (type CostMatrix): 'standard', ‘reward_low_FP_rate’, ‘reward_low_FN_rate’
```
