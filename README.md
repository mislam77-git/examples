This repository is still a work in progress.

This repository contains code examples for the book "Apache Oozie" by Mohammad Kamrul Islam and Aravind Srinivasan (O'Reilly).

# How to build the examples

Clone this repository on your local machine, move to the project root and run `mvn clean assembly:single`.

Example for chapter 1:

```
$ git clone https://github.com/oozie-book/examples.git
$ cd examples/chapter-01/identity-wf
$ mvn clean assembly:single
$ tree target/example
target/example
|-- ch01-identity
|   |-- app
|   |   `-- workflow.xml
|   `-- data
|       `-- input
|           `-- input.txt
`-- job.properties

4 directories, 3 files
```
