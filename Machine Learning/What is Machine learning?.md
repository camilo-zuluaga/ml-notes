# Machine learning

Machine learning is the science (and art) of programming computers so that they can learn from data.

A more engineering-oriented one:
- *"A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E."*

Your e-mail spam filter is actually Machine learning, that given spam emails (flagged by the users) and examples of regular emails (non spam, or ham) can learn to flag a spam email. The examples the system uses to learn is called *training set*. The part of a machine learning system that learns and make predictions is called *model*.

In this case our task T is to flag the spam emails, the experience E is the training data, and the performance measure P needs to be defined; for example, the radio of correct classified emails. This particular performance is also called *accuracy*, often used in classification tasks.

# Why use Machine learning?

Lets stick with the e-mail spam classification task, if we think it about how we traditionally would do it, using programming techniques, we would write a program that analyses the email, searching for words that are often used in these type of emails like ("free", "amazing", "4U", "credit card").
After that, we would examine further like the email body, or the sender's name, identifying patterns, etc. Leading to a pretty much, a complex program with a lot of rules, before launching it you would do a lot of tests until its good enough.

In contrast, a spam filter Machine learning system will automatically learn what words and phrases are good predictors of of spam by detecting unusually frequent patterns of words in the spam examples compared to ham examples, and will be actually easier to maintain. *Why?* Let's say the spammers notices all of their emails containing words like "4U" are getting blocked, they just will change it to "For U", this meaning our classic programming approach is becoming obsolete, we would need to manually add new rules forever.

This would not happen with a Machine learning system, it can identify that "For U", is unusually becoming frequent in spam emails flagged by users, and it will be flagging them without your intervention.

Another area where machine learning shines its when it comes to complex algorithms approaches or have no known algorithm.
For example, consider a speech program recognition. Say you want to distinguish between "One" and "Two". You hear that "Two" starts with a high pitch "T" sound, so you would hardcode a program that identifies this high pitch sound so you can distinguish between One and Two-- but obviously this technique wont scale to thousands of words spoken by millions of different people on different environments.
You will rather use a Machine learning system that can learns by itself, given a training set of many examples of voice recordings for each word.

Finally, machine learning can help humans learn. ML models can be inspected to see what have they learnt (there are some tricky ones). For example, our spam filter, we can inspect what are the words on combinations that it thinks are the best predictors to flag an email as spam. Sometimes it will reveal unexpected correlations or new trends, and this making us understand better whats the problem. *Digging into large amounts of data to discover hidden patterns is called data mining*.

To summarize, machine learning is great for:
1. Problems for which existing solutions require a lot of fine-tuning or long lists of rules (a machine learning model can often simplify code and perform better than an additional approach).
2. Complex problems which traditional approaches yields no good solution.
3. Fluctuating environments (a machine learning model can easily be updated with data and keep up to date).
4. Getting insights of large amounts of data or complex problems.

