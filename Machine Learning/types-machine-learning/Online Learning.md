# Online learning

## Summary
In online learning, you train the system incrementally, by feeding it data instances, either individually or in small chunks called *mini batches*. This is fast and cheap, and our system can learn on the fly as the data arrives.

### Learning 
- Useful for extremely fast adaptation to changes.
	- And if your resources are limited. *Like training the model on a mobile device.*
- Can be trained on huge datasets that cannot fit on one machine's memory *(out-of-core learning)*.
	- Loads part of the data, do the training step, repeat.

### Important parameter
- Online learning has one parameter that tells it how fast it should adapt to changing data, this is called *learning rate*. 

- If you set a high learning rate, your system will adapt quickly to the new data, but also will tend to quickly forget the old data.

- By setting a low learning rate, your system will have more inertia: Meaning it will learn slowly, but will also be less sensitive to noise in the new data or outliers.

### Downsides
- If bad data is fed to the system, the performance will decline, possibly quickly. *(depending on the learning rate and data quality)*.

### Key points
1. To reduce the risk of performance decline, you will need to monitor your system closely.
2. If you notice a drop in performance, you may want to switch learning off and return to a stable state of the system.
3. You might also want to monitor the data input and abnormal data; for example, by using an anomaly detection algorithm.

> *"Out of core learning is usually done offline".*