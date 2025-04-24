This internship project with Wells Fargo's Risk Modeling group explored dynamic learning methodologies for fraud detection in Zelle transactions. 

Fraudsters continuously evolve their tactics in financial transactions, and traditional machine learning models often fail to adapt to these rapidly evolving patterns, creating a need for more adaptive approaches. 

Three neural network models with identical architecture were developed and compared: a static model (baseline) trained once on historical data, an incremental model updated monthly while preserving previous knowledge, and a full train model (optimum) retrained monthly using all available historical data. 

The dynamic learning approaches significantly outperformed the static model across all metrics, including AUC, PR-AUC, detection rate, and false positive rate. While the full train model achieved the best results overall, the incremental model offered a strong balance between performance and computational efficiency, approaching the performance of the full train model while requiring significantly fewer computational resources.

The project successfully demonstrated how dynamic learning methodologies can improve fraud detection in financial transactions and provided recommendations for future implementations at Wells Fargo.
