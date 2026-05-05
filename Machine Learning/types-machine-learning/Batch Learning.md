# Batch learning

## Summary
Batch learning systems, cant learn data incrementally, so they need to be trained with all the available data. This takes a lot of time and computing resources, so this is typically done offline. Once the model is trained it is launched, and it runs without learning anymore, it just applies what it has learning. this is called *offline learning*.

### Learning from new data
- Retraining the model from scratch with new and old data.
- Replace the old model with the new one.
- Automating can be fairly easy, so even this algorithm *can* adapt to change.

### Downsides
- Learning from a new full dataset can take many hours.
	- Training from scratch takes a lot of time and computing resources.
- Could be even impossible to use this algorithm in some use cases.
	- You may end up using an algorithm that can learn incrementally.

### Key points

1. This model's performance tends to decay slowly over time, because data evolves. This is called *data rot or data drifting.*
2. The solution is to regularly retrain the model with up to date data, the regularity to do this depends on the use case.

