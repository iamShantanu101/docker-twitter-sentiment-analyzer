# docker-twitter-sentiment-analyzer
[![](https://images.microbadger.com/badges/image/ishantanu16/docker-twitter-sentiment-analyzer:1.6.2.svg)](https://microbadger.com/images/ishantanu16/docker-twitter-sentiment-analyzer:1.6.2 "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/ishantanu16/docker-twitter-sentiment-analyzer:1.6.2.svg)](https://microbadger.com/images/ishantanu16/docker-twitter-sentiment-analyzer:1.6.2 "Get your own version badge on microbadger.com")

Dockerfiles for ***Twitter sentiment analysis with Spark MLlib and visualization*** referenced by [https://github.com/iamShantanu101/Twitter-Sentiment-Analyzer-Apache-Spark-Mllib](https://github.com/iamShantanu101/Twitter-Sentiment-Analyzer-Apache-Spark-Mllib "» GitHub Repo").

The image is available directly from [https://index.docker.io](https://hub.docker.com/u/ishantanu16/ "» Docker Hub").


## Introduction
Docker image to analyse and visualize sentiment of tweets in real-time on a world map using Apache Spark ecosystem (Spark MLlib + Spark Streaming + Spark SQL).

For more details on this project and the code associated with it, please check the [blogpost](http://P7h.org/blog/2016/08/21/spark-twitter-sentiment/).<br>
Also, README of [https://github.com/iamShantanu101/Twitter-Sentiment-Analyzer-Apache-Spark-Mllib](https://github.com/iamShantanu101/Twitter-Sentiment-Analyzer-Apache-Spark-Mllib "» GitHub Repo") has details on how to execute this project.

## Get this Docker image
There are 2 ways of getting this image:

1. Build the image using Dockerfile
2. Pull the image from Docker Hub

### Build Docker image
Copy the [`Dockerfile`](https://github.com/iamShantanu101/docker-twitter-sentiment-analyzer/blob/master/Dockerfile) and the other 2 supporting files: [`bootstrap.sh`](https://github.com/iamShantanu101/docker-twitter-sentiment-analyzer/blob/master/bootstrap.sh) and [`run_spark_jobs.sh`](https://github.com/iamShantanu101/docker-twitter-sentiment-analyzer/blob/master/run_spark_jobs.sh) to a folder on your local machine and then invoke the following command.

    docker build -t ishantanu16/docker-twitter-sentiment-analyzer:1.6.2 .

This will build the docker image on your machine.

Please wait as this might take a bit of time depending on your internet speed.

### Pull the image from Docker Hub
With this approach, we are pulling the image hosted on Docker Hub instead of building it ourselves.

    docker pull ishantanu16/docker-twitter-sentiment-analyzer:1.6.2


## Executing the prototype
Please check the README of the [Twitter-Sentiment-Analyzer-Spark-MLlib project](https://github.com/iamShantanu101/Twitter-Sentiment-Analyzer-Apache-Spark-Mllib "» GitHub Repo") for detailed instructions on executing this prototype.


## Helpful links
2. Docker Image on Docker Hub Registry: [https://hub.docker.com/r/ishantanu16/docker-twitter-sentiment-analyzer/](https://hub.docker.com/r/ishantanu16/docker-twitter-sentiment-analyzer/).
3. GitHub URL for source code of the project: [https://github.com/iamShantanu101/Twitter-Sentiment-Analyzer-Apache-Spark-Mllib](https://github.com/iamShantanu101/Twitter-Sentiment-Analyzer-Apache-Spark-Mllib).
5. Dockerfile GitHub repo: [https://github.com/iamShantanu101/docker-twitter-sentiment-analyzer](https://github.com/iamShantanu101/docker-twitter-sentiment-analyzer).


## Problems? Questions? Contributions? [![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)]
If you find any issues or would like to discuss further, open a PR or open an issue.

## License [![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
Copyright &copy; 2016 Shantanu Deshpande.<br>
Licensed under the [Apache License, Version 2.0](LICENSE).

