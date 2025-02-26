# MLPR_lab-

![Wandb Dashboard](https://github.com/manyamittal04/MLPR_lab-/blob/main/wandbdash.png)
![Faces Detected](https://github.com/manyamittal04/MLPR_lab-/blob/main/Faculty_faces_detected.png)
![Clustered Faces](https://github.com/manyamittal04/MLPR_lab-/blob/main/Clustered_faces_plot.png)
![Clustered Faces with Centroids](https://github.com/manyamittal04/MLPR_lab-/blob/main/centroid_cluster_plot.png)
![Shashi Tharoor Detected Face](https://github.com/manyamittal04/MLPR_lab-/blob/main/temp_image_detected.png)
![Clustered Faces with Template Image](https://github.com/manyamittal04/MLPR_lab-/blob/main/cluster_plot_template.png)
![Clustered Faces with Centroids and Template Image](https://github.com/manyamittal04/MLPR_lab-/blob/main/cluster_plot_temp_centroids.png)

## Report

#### 1. What are the common distance metrics used in distance-based classification algorithms? 
  - Euclidean  
  - Mahalanobis
  - Manhattan
  - Chebyshev  
  - Minkowski
  - Cosine
  - Hamming

#### 2. What are some real-world applications of distance-based classification algorithms? 
  - Recommendation systems: Suggests products or content based on user similarity.  
  - Image recognition: Classifies objects by comparing feature distances.  
  - Document classification: Groups texts by measuring similarity between word distributions.  
  - Medical diagnosis: Identifies diseases by comparing patient data to historical cases. 

#### 3. Explain various distance metrics. 
  - **Euclidean:** Direct spatial distance, used in KNN and clustering.  
  - **Manhattan:** Absolute differences, effective for grid-based movements.  
  - **Minkowski:** Adjustable distance metric combining Euclidean and Manhattan.  
  - **Hamming:** Measures character differences in categorical data.  
  - **Chebyshev:** Maximum absolute difference along any axis, useful in logistics.  
  - **Cosine:** Measures vector angle, common in text analysis.  
  - **Mahalanobis:** Considers variable correlations, useful for detecting outliers.

#### 4. What is the role of cross validation in model performance?
  - Divides data into multiple subsets to evaluate model performance.  
  - Helps detect overfitting by testing on unseen data.  
  - Assists in hyperparameter tuning, such as selecting the best k-value in KNN.  
  - Provides a more reliable estimate of real-world accuracy.   

#### 5. Explain variance and bias in terms of KNN? 
  - Bias: High when k is large, leading to oversimplified predictions and underfitting.  
  - Variance: High when k is small, making the model too sensitive to noise and overfitting.  
  - Goal: Choose an optimal k-value to balance bias and variance for better generalization.