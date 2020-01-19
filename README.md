# UnsupervisedLearning
Customer Segmentation for Germany based Arvato Finance Solution: Mail-Order Sales Company 

# Project Overview:  
I have worked with real-life data provided to me by **Bertelsmann partners AZ Direct and Arvato Finance Solution**. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. 

# Goal:  
Each row of the demographics files represents a single person, but also includes information outside of individuals, including information about their household, building, and neighborhood. This information will be used to cluster the general population into groups with similar demographic properties. Then, I will see how the people in the customers dataset fit into those created clusters. The hope here is that certain clusters are over-represented in the customers data, as compared to the general population; those over-represented clusters will be assumed to be part of the core userbase. This information can then be used for further applications, such as targeting for a marketing campaign.

# My Work Scope:  
Used unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, I will be assessing and cleaning the data in order to convert the data into a usable form. 

# Why this project?  
- The unsupervised learning branch of machine learning is key in the organization of large and complex datasets. While unsupervised learning lies in contrast to supervised learning in the fact that unsupervised learning lacks objective output classes or values, it can still be important in converting the data into a form that can be used in a supervised learning task. Dimensionality reduction techniques can help surface the main signals and associations in our data, providing supervised learning techniques a more focused set of features upon which to apply their work.  
- Clustering techniques are useful for understanding how the data points themselves are organized. These clusters might themselves be a useful feature in a directed supervised learning task. This project will gave me a hands-on experience with a real-life task that makes use of these techniques, focusing on the unsupervised work that goes into understanding a dataset.  
- In addition, the dataset presented in this project requires a number of assessment and cleaning steps before I can apply any machine learning methods.  
- In workplace contexts, One frequently needs to work with data that is untidy or needs preprocessing before standard algorithms and models can be applied. The ability to perform data wrangling and the ability to make decisions on data that I work with are both valuable skills that I have practiced in this project.  

# Libraries Used:  
NumPy  
pandas  
Sklearn / scikit-learn  
Matplotlib (for data visualization)  
Seaborn (for data visualization)
