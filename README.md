# Sleep Health and Lifestyle Clustering using Scikit-Learn
<hr>
<h2>Data</h2>
https://www.kaggle.com/datasets/informateur234/sleep-health-and-lifestyle-dataset<br>

<hr>
<h2>Data Distribution</h2>
<div align=center>
<img src = "https://github.com/user-attachments/assets/467eb0a1-a9cd-4499-907b-9ccbaa170839" width="32.6%" height="32.6%" title="LDA Applied">
<img src = "https://github.com/user-attachments/assets/2fd81b48-560a-4531-90ee-6e704a6dc8ad" width="63%" height="63%" title="Train, Test Dataset">
</div>

After preprocessing, the data distribution are shown in the images above. Applied linear discriminant analysis(LAD) for each class to be seperated which will be helpful for the algorithm to learn. Oversampling for train set is used.<br>

<hr>
<h2>Clustering Models</h2>
Selected Models are the following; <br><br>
1. KMeans Clustering <br>
2. MeanShift Clustering <br>
3. Gaussian Mixture Clustering <br>
4. DBSCAN Clustering <br>

<hr>
<h2>Clustering Result Before Hyper-Tuning</h2>
<div align=center>
<img src = "https://github.com/user-attachments/assets/6f031ef4-3c3d-4da2-8289-bc52781d7699" width="100%" height="100%">
</div>
<h2>Clustering Result After Hyper-Tuning</h2>
<div align=center>
<img src = "https://github.com/user-attachments/assets/c1549b2d-2681-46e9-b32a-5456affcbc61" width="98%" height="98%">
</div>

<hr>
<h2>Model Analysis</h2>
<h3>KMeans:</h3>
<img src = "https://github.com/user-attachments/assets/47233353-33ca-4abe-859a-d633b86ce592" width="60%" height="60%">
<img src = "https://github.com/user-attachments/assets/7f542928-fcda-4303-a32c-a059c202f0d7" width="30%" height="30%">


<h3>MeanShift:</h3>
<img src = "https://github.com/user-attachments/assets/f040eb5d-a7e5-45f2-9200-26947339e9b1" width="90%" height="90%">

<h3>Gaussian Mixture:</h3>
<img src = "https://github.com/user-attachments/assets/d4a98873-f1d9-4b35-a7eb-94227ad3823a" width="90%" height="90%">

<h3>DBSCAN:</h3>
<img src = "https://github.com/user-attachments/assets/91a686db-8d9f-4bae-8425-a692d2edde22" width="60%" height="60%">
<img src = "https://github.com/user-attachments/assets/dcfd8363-0083-4ba8-b553-b80023bacf4b" width="37%" height="37%">

