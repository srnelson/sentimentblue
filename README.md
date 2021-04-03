# sentimentsblue

Alexa skill to use Microsoft Azure sentiment analysis in an interactive challenge

This repository contains the node.js code for a Lambda backend and a json interaction model that can be used to create Simple Sentiments, an interactive excercise challenging the user to match sentiment targets by speaking sentences which Azure will analyze and score.

The skill may be implemented by using the ask-sdk cli, or with the Lambda and Alexa consoles.

Note that the backend code makes use of three environment variables: Azure Key, Azure Endpoint, and s3 buckets where hiScores and sound files are kept.
