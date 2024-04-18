This project aims to identify a specific web user, known as "Alice," based on the browsing behavior on the Internet. The goal is to develop an algorithm that can predict whether a given webpage session belongs to Alice or to someone else. The dataset used in this project comes from the proxy servers at Blaise Pascal University (Kaggle competition "Catch me if you can ("Alice"), https://www.kaggle.com/competitions/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2/overview ).

Typically, the algorithm will analyze the sequence of web pages visited in a single browsing session by a person and determine if that session is indicative of Alice's behavior. This task falls within the realm of sequential pattern mining and behavioral psychology, as it involves analyzing patterns in the sequence of visited web pages to make predictions.

The ultimate aim is to build a model that can distinguish between Alice's browsing patterns and those of unauthorized individuals (e.g., hackers). By leveraging the sequential data of webpage visits, the algorithm can identify irregular behaviors that may indicate someone other than Alice is using a particular browsing session.

The project's success is evaluated based on the ROC AUC metric, which measures the model's ability to discriminate between Alice's web browsing behavior and that of other users.


WHAT IS SPM?

Sequential Pattern Mining (SPM) is a data mining technique used to discover sequential patterns and relationships in sequential data. It involves identifying patterns in data where the order of items or events is important.

In the context of web user identification and behavior analysis, SPM can be utilized to analyze the sequence of web pages visited by individuals to uncover patterns in their browsing behavior. This technique helps in understanding the sequential nature of user actions and can be valuable in various fields such as e-commerce, recommendation systems, and fraud detection
