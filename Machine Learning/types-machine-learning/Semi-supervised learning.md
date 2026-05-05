# Semi-supervised learning

Since labeling data can be time consuming and costly, you will sometimes work with plenty of unlabeled instances, and a few labeled. Some algorithms can deal with this partially labeled data. This is called *semi-supervised leaning*.

Some photo-hosting services, such as google photos are good examples for this. Once you upload all your family photos to the service, it automatically can recognize that a person appears in photos 3, 5, 8, while another person shows in photos 10, 1, 32. This is the unsupervised part of the algorithm (clustering). All you need to do is tell google who this people are giving them the names (labels) so now the service can name everyone in the photo.

Most semi-supervised learning algorithms are combinations of supervised and unsupervised algorithms, for example, a clustering algorithm may be used to group similar instances together, then every instance can be labeled with the most common label in its cluster. After all data is labeled, then its possible to use any supervised learning algorithm to deal with this data.