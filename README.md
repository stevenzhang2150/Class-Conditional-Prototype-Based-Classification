Prototype-based classification methods are simple and interpretable, but their performance under class-conditional clustering strategies and across different decision mechanisms remains underexplored.

This project implements class-conditional K-means clustering and evaluates four classification strategies: nearest prototype, distance-weighted voting, KNN-based voting, and logistic regression on prototype distances.

Results show that soft decision methods—particularly logistic regression and distance-weighted classification—consistently yield higher accuracy and stability across different values of k.

We recommend adopting soft, distance-aware decision strategies for prototype-based classification when using class-conditional clustering, as they offer a strong balance between interpretability and predictive performance.
