# spark-corenlp-java

This package wraps [Stanford CoreNLP](http://stanfordnlp.github.io/CoreNLP/) annotators as Spark
DataFrame functions following the [simple APIs](http://stanfordnlp.github.io/CoreNLP/simple.html)
introduced in Stanford CoreNLP 3.6.0.

This package requires [Java 8](https://www.oracle.com/java/technologies/java8.html) and [CoreNLP 3.6.0](https://stanfordnlp.github.io/CoreNLP/download.html) to run.
Users must include CoreNLP model jars as dependencies to use language models.
