
<h><img src="https://media.giphy.com/media/LRIsHhCPOcTW0w8DEq/giphy.gif" align="centre"></h>
<h1 align="center"> Netflix Movies and TV Shows - Clustering </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p>Netflix Recommender models are based on a user's favorite movie or TV show. It uses a Natural Language Processing (NLP) model and a K-Means Clustering model to make these recommendations. These models use information about movies and TV shows such as their plot descriptions and genres to make suggestions. The motivation behind this project is to develop a deeper understanding of recommender systems and create a model that can perform Clustering on comparable material by matching text-based attributes. Specifically, thinking about how Netflix create algorithms to tailor content based on user interests and behavior..</p>

<h2> :floppy_disk: Data Description</h2>

<p>The dataset contained over 25 variables and they are listed below</p>

**show_id**           -    Unique ID for every Movie / Tv Show

**type**              -     A Movie or TV Show

**director**          -     Director of the Movie 

**cast**              -     Actors involved in the movie / show

**country**           -     Country where the movie / show was produced

**date_added**        -     Date it was added on Netflix

**release_year**      -     Actual Release year of the movie /show

**rating**            -     TV Rating of the movie / show

**listed_in**         -     Genres



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Data Pipeline</h2>

● Data Processing : We checked for missing values, column type, column name, duplicate records, identified outliers, numerical categorical data and cleaned the dataset

● Exploratory Data Analysis (EDA): Exploratory data analysis using tables and graphs to derive the observations from the data 

● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 1 executable files, 2 text files as well as 1 directories as follows:</p>
<h4>Executable Files:</h4>

<ul>
  <li><b>Netflix Movies and TV Shows Clustering.ipynb</b> - Google Colab notebook with all the output visible</li>
  <li><b>Summary of Netflix Movies and TV shows.docx</b> - Contains the summary of the project.</li>
  <li><b>Technical Document.docx</b> - Contains whole analysis strategy and analysis methodology followed for the project.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>https://www.kaggle.com/datasets/shivamb/netflix-shows</b> - Includes all the required data.</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Model Implementation </h2>
<li>Silhouette score </li>
<li> Elbow Method</li>
<li>DBSCAN</li>
<li>Dendrogram</li>
<li> Agglomerative Clustering</li>

<p>Implemented different clustering models like K-means clustering, Hierarchical clustering, DBSCAN and evaluated the optimal clusters using the Silhouette score and Elbow method and found k=3 as best cluster</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Future Work</h2>
<li> Topic modelling can be done Further.</li>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2>:floppy_disk: Conclusion</h2>
<p>In text analysis (NLP) we used stopwords, removed punctuations, stemming & TFIDF vectorizer and other functions of NLP. Applied different clustering models like Kmeans, hierarchical, Agglomerative clustering, DBSCAN on data we got the best cluster arrangements. By applying the silhouette score method for n range clusters on dataset we got best score which is 0.3746 for 3 clusters it means content explained well on their own clusters, by using elbow method after k = 3 is the best cluster.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Sharaffin B | Data Science | Machine Learning | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations and Data Science related job roles</i></p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>Clustering Algorithms </p>
      <p>Available: https://www.freecodecamp.org/news/8-clustering-algorithms-in-machine-learning-that-all-data-scientists-should-know/</p>
  </li>
 
  <li><p>K Means Algorithm </p>
      <p>Available:https://youtu.be/4jv1pUrG0Zk</p>
  </li>
 
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)



