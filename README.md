# Feature-Engineering-Feature-Scaling

1. Standardization (Z-score Normalization)


**Formula :  X  - MEAN / S.D**
**Mean = 0 , S.D=1**

        We can use standardization in any of the case , there is no problem.
        
        Only the scale will change , distribution will remain same.
        
        There are certain algorithm which does not changes w.r.t to scaling such as decision tree , with or without scaling the accuracy will be same.
        
        Algorithm where scaling is required are k-means,KNN,PCA,ANN,Gradient Descent , because we have to calculate the distance.
        
        The Outliers will remain the same after applying scaling it cannot be handled using scaling option , the distribution will remain same.
        
        **Effect of outliers cannot be controlled**


2. Normalization

        
        Goal of Normalization is to change the values of numeric columns in dataset to use a common scale without distorting differences in range of values or losing  information

**Formula : xi-xmin/xmax-xmin**
**O/P will range in (0,1)**
