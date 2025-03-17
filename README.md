# Network Traffic Anomaly Classifier using ML  
Open in kaggle for better expierence https://www.kaggle.com/code/arayawat/network-traffic-anomaly-detection-using-ml/notebook  
## Objective  
- Develop a Machine Learning model for automatically detecting network traffic anomalies.
- Analyze and compare different Machine Learning models to identify the most effective approach.
- Enhance network security by preventing threats types such as DoS, Brute-force, and Mirai.
## Dataset  
https://www.kaggle.com/datasets/daniaherzalla/tii-ssrc-23  
Using TII-SSRC-23. a comprehensive collection of network traffic patterns, meticulously compiled to support the development and research of Intrusion Detection Systems (IDS).
## Datasets Breakdown (Type)
![image](https://github.com/user-attachments/assets/4c93eb66-fe0b-4dda-8016-f3676bccbcdb)  
### Benign
### Malicious
**Bruteforce**  
- A brute force attack involves repeatedly trying different passwords or keys until the correct one is found.

**DoS**   
- A DoS attack is an attempt to make a network resource unavailable by overwhelming it with excessive requests.

**Information Gathering**  
- an attacker attempts to collect sensitive data about a network, its devices, and potential vulnerabilities

**Mirai(Malware)**  
-  is a botnet that infects IoT devices and uses them to launch large-scale DDoS attacks.  

### Feature Categories Breakdown:
- Basic Network Flow Identifiers
- Flow Duration and Packet Statistics
- Packet Length Statistics
- Flow Rate Features
- Inter-Arrival Time (IAT) Features
- TCP Flag Features
- Window Size and Segment Features
- Bulk Data Transfer Features
- Active and Idle Time Features
- Labels for Traffic Type Classification
## Model including
- Random Forest
- Decision Tree
- Logistic Regression
- Gaussian Naive Bayes
- XGBoost
- K-Nearest Neighbor
- LightGBM
- Adaptive Boosting
- Categorical Boosting
## Result
**Model:** https://o365cmu-my.sharepoint.com/:f:/g/personal/arayawat_h_cmu_ac_th/EsAp97f3VQZNvEPadiO3ProBvNFS5pZfAlbNPmfarC8hCg?e=5s7b7K  
Consist of Accuracy, F1 Score, ROC AUC, Confusion Matrix, and Feature Importance  
Time of training process will also be considered  
![__results___192_0](https://github.com/user-attachments/assets/daa960d2-7b49-400c-9854-533aad0ecfae)  
![__results___193_0](https://github.com/user-attachments/assets/51eba6ba-bacc-4732-b288-24b4e0439721)  
![__results___194_0](https://github.com/user-attachments/assets/4144a113-4653-4f93-9dc5-65219df1c7d7)  
![image](https://github.com/user-attachments/assets/2ba3ced2-b0b1-46c4-9450-9490550c528f)  




