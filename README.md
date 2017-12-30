veraPDF-model
=============
The veraPDF Validation model described using a Domain Specific Language developed in [XText](https://eclipse.org/Xtext/).

[![Build Status](https://travis-ci.org/veraPDF/veraPDF-model.svg?branch=integration)](https://travis-ci.org/veraPDF/veraPDF-model "Travis-CI")
[![Build Status](http://jenkins.openpreservation.org/buildStatus/icon?job=veraPDF-model)](http://jenkins.openpreservation.org/job/veraPDF-model/ "OPF Jenkins Release")
[![Build Status](http://jenkins.openpreservation.org/buildStatus/icon?job=veraPDF-model-dev)](http://jenkins.openpreservation.org/job/veraPDF-model-dev/ "OPF Jenkins Development")
[![Maven Central](https://img.shields.io/maven-central/v/org.verapdf/pdf-model.svg)](http://repo1.maven.org/maven2/org/verapdf/pdf-model/ "Maven central")

[![GitHub issues](https://img.shields.io/github/issues/veraPDF/veraPDF-model.svg)](https://github.com/veraPDF/veraPDF-model/issues "Open issues on GitHub")
[![GitHub issues](https://img.shields.io/github/issues-closed/veraPDF/veraPDF-model.svg)](https://github.com/veraPDF/veraPDF-model/issues-closed "Open issues on GitHub")
[![GitHub issues](https://img.shields.io/github/issues-pr/veraPDF/veraPDF-model.svg)](https://github.com/veraPDF/veraPDF-model/issues-pr "Open issues on GitHub")
[![GitHub issues](https://img.shields.io/github/issues-pr-closed/veraPDF/veraPDF-model.svg)](https://github.com/veraPDF/veraPDF-model/issues-pr-closed "Open issues on GitHub")

Licensing
---------
The veraPDF Validation model is dual-licensed, see:

 - [GPLv3+](LICENSE.GPL "GNU General Public License, version 3")
 - [MPLv2+](LICENSE.MPL "Mozilla Public License, version 2.0")

Pre-requisites
--------------
In order to generate the model classes you'll need:

 * Java 8, which can be downloaded [from Oracle](http://www.oracle.com/technetwork/java/javase/downloads/index.html), or for Linux users [OpenJDK](http://openjdk.java.net/install/index.html).
 * [Maven v3+](https://maven.apache.org/)

If you want to edit and regenerate the model you'll need:

 * The [veraPDF-model-syntax project](https://github.com/veraPDF/veraPDF-model-syntax), the [README](https://github.com/veraPDF/veraPDF-model-syntax/blob/master/README.md) gives instructions on how to install and use XText support in Eclipse.

Generating the veraPDF Model
----------------------------
 1. Download the veraPDF-model repository, either: `git clone https://github.com/veraPDF/veraPDF-model`
 or download the [latest tar archive](https://github.com/veraPDF/veraPDF-model/archive/master.tar.gz "veraPDF-Model latest GitHub tar archive") or [zip equivalent](https://github.com/veraPDF/veraPDF-model/archive/master.zip "veraPDF-Model latest GitHub zip archive") from GitHub.
 2. Move to the downloaded project directory, e.g. `cd veraPDF-model`
 3. Build and install using Maven: `mvn clean install`
