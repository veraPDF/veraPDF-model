veraPDF-model
=============

The veraPDF Validation model described using a Domain Specific Language developed in [XText](https://eclipse.org/Xtext/).

CI Status
---------

Travis: [![Build Status](https://travis-ci.org/veraPDF/veraPDF-model.svg?branch=master)](https://travis-ci.org/veraPDF/veraPDF-model)

Jenkins: [![Build Status](http://jenkins.opf-labs.org/view/veraPDF-jobs/job/veraPDF-model/badge/icon)](http://jenkins.opf-labs.org/view/veraPDF-jobs/job/veraPDF-model/)

Pre-requisites
--------------

In order to generate the model classes you'll need:

 * Java 7, which can be downloaded [from Oracle](http://www.oracle.com/technetwork/java/javase/downloads/index.html), or for Linux users [OpenJDK](http://openjdk.java.net/install/index.html).
 * [Maven v3+](https://maven.apache.org/)

If you want to edit and regenerate the model you'll need:

 * The [veraPDF-model-syntax project](https://github.com/veraPDF/veraPDF-model-syntax), the [README](https://github.com/veraPDF/veraPDF-model-syntax/blob/master/README.md) gives instructions on how to install and use XText support in Eclipse.

Generating the veraPDF Model
----------------------------

 1. Download the veraPDF-model repository, either cloning via Git
 `git clone https://github.com/veraPDF/veraPDF-model` or downloading the [latest zip archive from GitHub](https://github.com/veraPDF/veraPDF-model/archive/master.zip).

 2. Move to the downloaded project directory, e.g. `cd veraPDF-model`.

 3. Build and install using Maven, `mvn clean install`.
