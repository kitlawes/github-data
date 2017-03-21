# github-data

src/github/

* GithubData.java
  * Finds all Github repositories with id between two values (inclusive)
  * Finds the topics of repositories that have at least 1,000 stars and have most recently been updated
  * Finds how many repositories have used each topic, and orders the topics based on this
* github\_topics.txt - The topics of repositories that have at least 1,000 stars and have most recently been updated
* github\_popularity.txt - The topics in github\_topics.txt ordered by how many repositories have used each topic

src/stack/overflow/

* StackOverflowData.java - Finds how many questions have used each tag, and orders the tags based on this
* stack\_overflow\_popularity.txt - The tags ordered by how many questions have used each tag

src/

* ComparePopularity.java - Compares the popularity order of topics and tags
* popularity\_comparison.txt - The comparison of the popularity order of topics and tags