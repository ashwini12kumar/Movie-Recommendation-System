# Movie-Recommendation-System
Mini project to recommend various similar movies based on a user interest.

# Description
Recommendation systems are becoming increasingly important in today’s extremely busy world. The purpose of a recommendation system basically is to search for content that would be interesting to an individual. These results are based on their profile, search/browsing history, what other people with similar traits/demographics are watching, and how likely are you to watch those movies.

# Concept used
This project uses content based recommendation, i.e., it recommends movies similar to movies that user might had watched earlier or searched for.
1. For each movie, a feature column is prepared that can represent the movie. It includes movie description, top casts, director of movie etc.
2. This feature is then vectorised. Now this vector will represent the corresponding movie in vector space.
3. The cosine similarity between these vectors are calculated, and top 'n' most similar vectors represent the 'n' most similar movies to the queried movie.
4. Movies corresponding to these similar vectors are recommended.

# Mathematical intuition
Cosine similarity is a metric used to measure the similarity of two vectors. Specifically, it measures the similarity in the direction or orientation of the vectors ignoring differences in their magnitude or scale. The similarity of two vectors is measured by the cosine of the angle between them.
Mathematically, it is calculated as the dot product of the vectors divided by their magnitude.
