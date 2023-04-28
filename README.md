# Predicting-Consumer-Spending

##Project Executive Summary


Customer personality analysis involves collecting and analyzing data about customers, such as their demographics, psychographics, and behaviors, in order to create customer profiles that represent different types of customers. By understanding the unique needs, preferences, and pain points of each customer segment, businesses can modify their products, marketing strategies, and customer service initiatives to better meet the needs of their target customers. This can ultimately lead to improved customer relationships, higher customer satisfaction, and increased revenue and profitability for the business.


The data source used is obtained from Kaggle, comprised of 2,240 observed tuples across 29 attributes. The objective of the study is to divide the target customers on the basis of their significant features which could help the company maintain stronger bond with those high-spending customers in less marketing expenses. Some potential questions to explore are how factors affect consumer spending and are product preferences differ among various segments?


Market segmentation is the process of dividing a broad target market of customers into smaller and more similar groups, and then designing marketing strategies tailored to each group’s specific needs and characteristics. The technique used here are KMeans clustering, in conjunction with PCA for dimension reduction, which involves analyzing data to automatically identify groups of customers with similar attributes or behaviors. Then, kNN and Decision Tree Classifiers are applied to the training set with hyperparameter tuning and cross validation. Finally, the better-performing classifier, Deicision Tree Classified, is rebuilt with target variable with two levels instead of three. A sophisticated evaluation using ROC plot, accuracy, precision, and recall metrics is performed on the final model.
