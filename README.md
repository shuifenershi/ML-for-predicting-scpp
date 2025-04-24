# ML-for-predicting-scpp
##本研究所有模型训练过程均在 Google Colab 上完成，所有代码均已开源上传
##原始训练集中存在类别不平衡问题（重症组样本少于非重症组），因此在训练阶段使用SMOTE算法进行过采样，仅在训练集内执行，测试集未做任何平衡处理。
##模型选择包括支持向量机（SVM，RBF核）、随机森林、以及XGBoost，分别比较其在AUC、召回率（Recall）及准确率（Accuracy）上的表现，最终选择最优模型用于预后预测。
##English version
##All models training processes in this study were completed on Google Colab, and all codes have been open-sourced and uploaded.
##There was a class imbalance problem in the original training set (the number of samples in the severe group was less than that in the non-severe group), so the SMOTE algorithm was used for oversampling only in the training set during the training stage, and no balance processing was performed on the test set. 
##The model selection included Support Vector Machine (SVM, RBF kernel), Random Forest, and XGBoost. Their performances were compared in terms of AUC, recall rate (Recall), and accuracy (Accuracy), and the best model was finally selected for prognosis prediction.
