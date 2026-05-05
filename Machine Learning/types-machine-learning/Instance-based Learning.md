# Instance-based Learning

## Summary
The system learns the examples by heart, then generalizes to new cases by using a similarity measure, to compare them to the learned examples.
We don't create a model here and don't make any calculations at all, the system will compare new instances with the data in training, because its stored in memory.

### Example
Instead of just flagging emails as a spam that are identical to known spam emails, you could flag emails that are very similar to other known spam emails.

### Measure of similarity
To perform the example above, we would use a *measure of similarity* between to emails. A basic example could be counting the words in common between the two emails, and flag the email if they have many words in common with a known spam email. 

### Advantages
- Can be trained on smaller datasets.

### Downsides
- Less accuracy.
- Slower.
