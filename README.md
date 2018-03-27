# Clustering algorithms and recommender systems analysis, a comparative Java framework

## Abstract
Nowadays, organizations are accumulating vast and growing amounts of data in different formats,
storing them in huge databases. This data can provide useful information through patterns, associ-
ations or relationships. Data mining has emerged as a powerful tool to analyze a huge amount of
data in automatic or semi-automatic way, in order to discover as much information and correlations
as possible within datasets. A key feature and one of the goals of these systems is to provide, by
personalized user recommender systems regards user’s interests, recommendations.
Recommender systems usually refers to methods of recommendations based on the information
of a single user. However the user’s way of thinking, the user’s choices and tastes are affected by
the user’s social life. Consequently new recommender systems approaches are being developed in
order to incorporates also user’s social parameters as recommender system features. For instance,
friend grouping recommendation is a recommender system approach that take into consideration
social information by creating groups personalized environments. Shortly, friend grouping refers to
groups of people, hidden or not from the user point of view, that has been grouped together, according
to some predefined parameters, in order to share the same resources and informations.
Clustering entities according to some entities’ features in order to create groups, is a well known
problem in computer science. There are many algorithms created in order to perform this operation.
However running different clustering algorithms lead to the achievement of different results i.e. differ-
ent groups. Each clustering algorithms has some predefined evaluations strictly based on the structure
of the algorithms. For example the distance mean of the cluster instances from the cluster centroid is
used as k-means evaluation, or the similarity means between the cluster instances and its exemplars
used in the Affinity propagation algorithm. However these evaluation methodologies are not directly
comparable each other, making hard the comparison between different algorithms performances. The
key problem we want to study, is how to produce general results, statistics and evaluations usable
for every cluster algorithm, in order to simplify the comparison of the cluster results and in order to
understand which algorithm produces the best groups according to the problem requirements.
The solution proposed in this thesis is a Java-oriented framework, able to run different clustering
algorithms, recommender systems and analysis of the outputs. The framework shall facilitate the
development of cluster algorithms and produces statistics about the created clusters, so we can compare
in a simpler way the different algorithms. More precisely, it contains methodologies designed to simplify
the creation and execution of clustering algorithms on a dataset, having as final output statistics about
the results achieved. Furthermore, it is able to compare the results with a given ground truth dataset,
returning different statistics and evaluations based on the comparison.
The framework has been designed to provide to developers and data analysts pattern analysis of
cluster algorithms and recommender systems, thus facilitating their choice on which algorithm will fit
better their requirements.
To test the framework we have been made testing on the domain of social groups and group
recommendations based on users’ preferences. The final part of this thesis presents some results of the
use of the proposed framework to show how to use it in order to make some algorithms comparisons
on given datasets.

For the whole thesis, please download the pdf file of this repository.
