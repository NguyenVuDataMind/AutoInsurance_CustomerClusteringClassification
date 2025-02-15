# AutoInsurance_CustomerClusteringClassification
The project is in the field of auto insurance in the US, utilizing three main algorithms: Linear Regression, K-means, and KNN.
First, the data will be preprocessed by removing duplicate entries and unnecessary order columns. The first algorithm used is Linear Regression to predict Customer Lifetime Value (CLV) based on the selected columns: Income, MonthlyPremiumAuto, NumberofOpenComplaints, NumberofPolicies, Response, Education, MaritalStatus, RenewOfferType.

Next, the K-means clustering algorithm is applied to segment customers into different groups, analyze the characteristics of each cluster to name them appropriately, and then implement suitable policies for each customer. After that, the cluster labels are assigned to the dataset and used in the KNN algorithm to predict the labels for new customers.

The KNN model achieves an accuracy of over 90%.

Note: In the code, both mathematical methods and library-based methods are used to implement the algorithms.
