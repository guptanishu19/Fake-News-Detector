Fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. This is often done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.

Built a model to accurately classify a piece of news as REAL or FAKE.
Using sklearn, built a TfidfVectorizer on the dataset. Then, initialized a PassiveAggressive Classifier and fit the model.

THE DATASET: The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE.

Accuracy: 94.69%

Confusion Matrix: 746 true positives, 754 true negatives, 41 false positives, and 43 false negatives.

Libraries Used: numpy, pandas, sklearn
