METRICS

Inertia and silhouette score were used to evaluate and determine the optimal number of clusters. 

<img width="1080" height="746" alt="IMG-20260609-WA0000" src="https://github.com/user-attachments/assets/7f335202-908d-4893-8415-e7ceeaf1ea15" />
The inertia plot seems to depict an elbow at seven clusters. It shows that models with more than 7 clusters do not seem to reduce inertia much at all.

<img width="1080" height="791" alt="IMG-20260609-WA0001" src="https://github.com/user-attachments/assets/2bca44a1-ec4b-4a67-a0ae-f4296a6de46a" />
The highest silhouette score shows that a 7-cluster model is optimal, this corroborates the findings from the assessment of inertia.

At this point, between the inertia and silhouette score analyses, with a reasonable degree of confidence, it makes the most sense to group the data into seven clusters. So, a 7-cluster model was instantiated and fitted into the data.
