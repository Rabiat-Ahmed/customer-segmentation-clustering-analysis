## Plan

This project applies K-Means clustering to a customer transaction dataset to discover groups using the behavioral and demographic features. The objective is to identify natural groupings within the data that can inform targeted strategies and customer understanding.

The dataset was gotten from Fares Ben Kacem on Kaggle.

## Analyze

The dataset consists of 10,000 rows and 14 columns. Each row contains information of a customer. The customers are based in 10 different countries. The annual income column is in USD. The dataset has no duplicates and no missing values. Two columns were changed to the appropriate data type. The categorical variables were encoded. 

## Contruct

Inertia and silhouette score were used to evaluate and determine the optimal number of clusters. 

<img width="1080" height="746" alt="IMG-20260609-WA0000" src="https://github.com/user-attachments/assets/7f335202-908d-4893-8415-e7ceeaf1ea15" />
The inertia plot seems to depict an elbow at seven clusters. It shows that models with more than 7 clusters do not seem to reduce inertia much at all.

<img width="1080" height="791" alt="IMG-20260609-WA0001" src="https://github.com/user-attachments/assets/2bca44a1-ec4b-4a67-a0ae-f4296a6de46a" />
The highest silhouette score shows that a 7-cluster model is optimal, this corroborates the findings from the assessment of inertia.

At this point, between the inertia and silhouette score analyses, with a reasonable degree of confidence, it makes the most sense to group the data into seven clusters. So, a 7-cluster model was instantiated and fitted into the data.

## Visualize

<img width="1499" height="1199" alt="Dashboard 1" src="https://github.com/user-attachments/assets/f9ba7b48-2a7f-4e7f-9cc1-14599bf1ad4b" />

<img width="1499" height="1199" alt="Dashboard 2" src="https://github.com/user-attachments/assets/20a5b6a3-ff78-43bc-8077-d52309ef77cd" />

<img width="1499" height="1199" alt="Dashboard 3" src="https://github.com/user-attachments/assets/69d6c601-94af-431a-bf04-343aac8d2c0a" />

<img width="1499" height="1199" alt="Dashboard 4" src="https://github.com/user-attachments/assets/ad49d273-d047-4e82-a299-d631fc715bb2" />

<img width="1499" height="1199" alt="Dashboard 5" src="https://github.com/user-attachments/assets/5ba1019a-ac65-4925-93d3-2c888fab63ce" />

## Findings

Gender, average age, average spending score, average membership years, average website visits and average cart abandon rate are relatively similar across clusters.

**Cluster 1**
1) Cluster 1 is the largest cluster, containing 3,799 customers (38% of the total) from USA (63% of the cluster, 2,389 customers), Canada (22% of the cluster, 828 customers) and Australia (15% of the cluster, 582 customers).

2) 1,896 female customers and 1903 male customers; roughly 50%-50% split.

3) Average annual income (~$100,000).

4) Average age is 44.

5) Average spending score is 51.

6) Average number of purchases is 24.

7) Average membership years is 6.

8) Average website visits per month is 15

9) Average cart abandon rate is 0.50.

**Cluster 2**
1) Cluster 2 has 1,008 customers (~10% of the total) from Germany.

2) 509 female customers and 499 male customers; roughly 50%-50% split.

3) Average annual income is (~$100,000).

4) Average age is 45.

5) Average spending score is 51.

6) Average number of purchases is 24.

7) Average membership years is 6.

8) Average website visits per month is 16.

9) Average cart abandon rate is 0.51.

**Cluster 3**
1) Cluster 3 has 1,025 customers (~10% of the total) from Brazil.

2) 500 female customers and 525 male customers; roughly 49%-51% split.

3) Average annual income is (~$50,000).

4) Average age is 44.

5) Average spending score is 50.

6) Average number of purchases is 21.

7) Average membership years is 6.

8) Average website visits per month is 16.

9) Average cart abandon rate is 0.50.

**Cluster 4**
1) Cluster 4 has 1,013 customers (~10% of the total) from the UK.

2) 473 female customers and 540 male customers; roughly 47%-53% split.

3) Average annual income is (~$100,000).

4) Average age is 43.

5) Average spending score is 51.

6) Average number of purchases is 23.

7) Average membership years is 6.

8) Average website visits per month is 15.

9) Average cart abandon rate is 0.49.

**Cluster 5**
1) Cluster 5 is the second largest cluster, containing 2,266 customers (23% of the total) from India (67% of the cluster, 1524 customers), France (28% of the cluster, 640 customers) and Australia (5% of the cluster, 102 customers).

2) 1113 female customers and 1153 male customers; roughly 49%-51% split.

3) Average annual income is (~$50,000).

4) Average age is 44.

5) Average spending score is 50.

6) Average number of purchases is 21.

7) Average membership years is 6.

8) Average website visits per month is 16.

9) Average cart abandon rate is 0.50.

**Cluster 6**
1) Cluster 6 has 494 customers (5% of the total) from Japan.

2) 250 female customers and 245 male customers; roughly 51%-49% split.

3) Average annual income is (~$100,000).

4) Average age is 44.

5) Average spending score is 52.

6) Average number of purchases is 23.

7) Average membership years is 6.

8) Average website visits per month is 16.

9) Average cart abandon rate is 0.49.

**Cluster 7**
1) Cluster 7 is the smallest cluster, containing 394 customers(4% of the total) from South Africa.

2) 196 female customers and 198 male customers; roughly ~50%-50% split.

3) Average annual income is (~$50,000).

4) Average age is 44.

5) Average spending score is 51.

6) Average number of purchases is 21.

7) Average membership years is 6.

8) Average website visits per month is 15.

9) Average cart abandon rate is 0.51.
