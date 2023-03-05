# Association-Rule
Prepare rules for the all the data sets 
1) Try different values of support and confidence. Observe the change in number of rules for different support,confidence values
--> Book dataset:
    metric="support",min_threshold=0.1 --> Number of rules= 100
    metric="support",min_threshold=0.15 --> Number of rules= 21
    metric="support",min_threshold=0.2 --> Number of rules= 2
    metric="confidence",min_threshold=0.1 --> Number of rules= 100
    metric="confidence",min_threshold=0.3 --> Number of rules= 89
    metric="confidence",min_threshold=0.4 --> Number of rules= 70

    Movie dataset:
    metric="support",min_threshold=0.4 --> Number of rules= 11
    metric="support",min_threshold=0.5 --> Number of rules= 4
    metric="support",min_threshold=0.6 --> Number of rules= 2
    metric="confidence",min_threshold=0.8 --> Number of rules= 51
    metric="confidence",min_threshold=0.9 --> Number of rules= 49
    metric="confidence",min_threshold=1 --> Number of rules= 49
    
2) Change the maximum length in apriori algorithm
--> Book dataset:
    min_support=0.1 max_len=1 --> Frequent item= 8
    min_support=0.1 max_len=2 --> Frequent item= 29
    min_support=0.1 max_len=3 --> Frequent item= 39
    
    Movie dataset:
    min_support=0.1 max_len=1 --> Frequent item= 10
    min_support=0.1 max_len=2 --> Frequent item= 30
    min_support=0.1 max_len=3 --> Frequent item= 46

3) Visulize the obtained rules using different plots 
--> Visualisation of frequent items is done using: LinePlot, DistPlot
