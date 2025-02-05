veraPDF-model
=============
The veraPDF Validation model described using a Domain Specific Language developed in [XText](https://eclipse.org/Xtext/).

[![Build Status](https://jenkins.openpreservation.org/job/veraPDF/job/1.28rc/job/model/badge/icon)](https://jenkins.openpreservation.org/job/veraPDF/job/1.28rc/job/model/ "OPF Jenkins")
[![Maven Central](https://img.shields.io/maven-central/v/org.verapdf/pdf-model.svg)](https://repo1.maven.org/maven2/org/verapdf/pdf-model/ "Maven central")
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/0b6a3e7f350c47d4a1ea1c5b500bbf68)](https://app.codacy.com/gh/veraPDF/veraPDF-model/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade "Codacy grade")

[![GitHub issues](https://img.shields.io/github/issues/veraPDF/veraPDF-library.svg)](https://github.com/veraPDF/veraPDF-library/issues "Open issues on GitHub")
[![GitHub issues](https://img.shields.io/github/issues-closed/veraPDF/veraPDF-library.svg)](https://github.com/veraPDF/veraPDF-library/issues?q=is%3Aissue+is%3Aclosed "Closed issues on GitHub")
[![GitHub issues](https://img.shields.io/github/issues-pr/veraPDF/veraPDF-model.svg)](https://github.com/veraPDF/veraPDF-model/pulls "Open pull requests on GitHub")
[![GitHub issues](https://img.shields.io/github/issues-pr-closed/veraPDF/veraPDF-model.svg)](https://github.com/veraPDF/veraPDF-model/pulls?q=is%3Apr+is%3Aclosed "Closed pull requests on GitHub")

Licensing
---------
The veraPDF Validation model is dual-licensed, see:

 - [GPLv3+](LICENSE.GPL "GNU General Public License, version 3")
 - [MPLv2+](LICENSE.MPL "Mozilla Public License, version 2.0")

Pre-requisites
--------------
In order to generate the model classes you'll need:

 * Java 11, 17 or 21, which can be downloaded [from Oracle](https://www.oracle.com/technetwork/java/javase/downloads/index.html), or for Linux users [OpenJDK](https://openjdk.java.net/install/index.html).
 * [Maven v3+](https://maven.apache.org/)

If you want to edit and regenerate the model you'll need:

 * The [veraPDF-model-syntax project](https://github.com/veraPDF/veraPDF-model-syntax), the [README](https://github.com/veraPDF/veraPDF-model-syntax/blob/master/README.md) gives instructions on how to install and use XText support in Eclipse.

Generating the veraPDF Model
----------------------------
 1. Download the veraPDF-model repository, either: `git clone https://github.com/veraPDF/veraPDF-model`
 or download the [latest tar archive](https://github.com/veraPDF/veraPDF-model/archive/master.tar.gz "veraPDF-Model latest GitHub tar archive") or [zip equivalent](https://github.com/veraPDF/veraPDF-model/archive/master.zip "veraPDF-Model latest GitHub zip archive") from GitHub.
 2. Move to the downloaded project directory, e.g. `cd veraPDF-model`
 3. Build and install using Maven: `mvn clean install`
