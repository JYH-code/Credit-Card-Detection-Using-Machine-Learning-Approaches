# Credit-Card-Detection-Using-Machine-Learning-Approaches
The documents contain all the programs and source datasets. The introduction can be seen in README.txt


REFERENCE:
    some parts are based on https://machinelearningmastery.com/imbalanced-classification-with-the-fraudulent-credit-card-transactions-dataset/
    The function plot_confusion_matrix is based on https://blog.csdn.net/wait_for_eva/article/details/82355038?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522160007532819725264661336%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=160007532819725264661336&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v3~pc_rank_v2-1-82355038.first_rank_ecpm_v3_pc_rank_v2&utm_term=%E7%94%BB%E6%B7%B7%E6%B7%86%E7%9F%A9%E9%98%B5
    The functions plot_roc, plot_prc are based on https://blog.csdn.net/qq_36887581/article/details/105624766?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522159848951119725219945532%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=159848951119725219945532&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v3~pc_rank_v2-2-105624766.first_rank_ecpm_v3_pc_rank_v2&utm_term=%E4%BF%A1%E7%94%A8%E5%8D%A1%E6%AC%BA%E8%AF%88SVM%E6%A3%80%E6%B5%8B
    The corelation coeficient matrix heat map is based on https://blog.csdn.net/qq_42898981/article/details/102836530?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522160007593819725247400985%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=160007593819725247400985&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v3~pc_rank_v2-1-102836530.first_rank_ecpm_v3_pc_rank_v2&utm_term=%E7%BB%98%E5%88%B6%E7%9B%B8%E5%85%B3%E7%B3%BB%E6%95%B0%E7%83%AD%E5%8A%9B%E5%9B%BE%E7%9F%A9%E9%98%B5


Documents Describtion:
DataPreparation.py is used to implement undersampling (extract 20000 legitemate transactions and 492 fraudulent transactions)
LRTest.py, CARTTest.py, KNNTest.py, RFTest.py, SVMTest.py and MLPTest.py are the models to optimize their parameters.
Comparations.py is used to evaluate the above six classifiers simultaneously
DataVisualization.py is used to plot the distribution histograms and corelation coeficient matrix heat maps. 
Best_Model_Test.py is used to evaluate the final selected model with best classification performance.

credit_newdataframe.csv  and  credit_newdataframe_old.csv are the simplified datasets;
creditcard.csv  and  creditcard_old.csv are the original datasets;
credit_newdataframe.csv   and   creditcard.csv are the datasets without the time column (30 columns).
credit_newdataframe_old.csv   and   creditcard_old.csv are the datasets with the time column (31 columns).













