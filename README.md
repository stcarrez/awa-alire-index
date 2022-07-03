# Ada Web Application

[![Build Status](https://img.shields.io/jenkins/s/https/jenkins.vacs.fr/Bionic-AWA.svg)](https://jenkins.vacs.fr/job/Bionic-AWA/)
[![Test Status](https://img.shields.io/jenkins/t/https/jenkins.vacs.fr/Bionic-AWA.svg)](https://jenkins.vacs.fr/job/Bionic-AWA/)
[![codecov](https://codecov.io/gh/stcarrez/ada-awa/branch/master/graph/badge.svg)](https://codecov.io/gh/stcarrez/ada-awa)
[![Documentation Status](https://readthedocs.org/projects/ada-awa/badge/?version=latest)](https://ada-awa.readthedocs.io/en/latest/?badge=latest)
[![License](https://img.shields.io/badge/license-APACHE2-blue.svg)](LICENSE)

Ada Web Application is a framework to build a Web Application in Ada 2012.
The framework provides several ready to use and extendable modules that are common
to many web application.  This includes the login, authentication, users, permissions,
managing comments, tags, votes, documents, images.  It provides a complete blog,
question and answers and a wiki module.

AWA simplifies the Web Application development by taking care of user management with
Google+, Facebook authentication and by providing the foundations on top of which you
can construct your own application.  AWA provides a powerful permission management
that gives flexibility to applications to grant access and protect your user's resources.

This is the Alire index to give access to the following projects:

* Ada Server Faces (https://github.com/stcarrez/ada-asf)
* Ada Servlet   (https://github.com/stcarrez/ada-servlet)
* OpenAPI Ada   (https://github.com/stcarrez/swagger-ada)
* ADO           (https://github.com/stcarrez/ada-ado)
* Ada Util      (https://github.com/stcarrez/ada-util)
* Ada Wiki      (https://github.com/stcarrez/ada-wiki)
* Ada EL        (https://github.com/stcarrez/ada-el)
* Ada Security  (https://github.com/stcarrez/ada-security)
* Ada Keystore  (https://github.com/stcarrez/ada-keystore)
* Ada LZMA      (https://github.com/stcarrez/ada-lzma)
* Dynamo        (https://github.com/stcarrez/dynamo)

These projects are distributed under the Apache License 2.0 or MIT license for Ada LZMA.

# Install

The AWA framework uses git submodules to integrate several other
projects.  To get all the sources, use the following commands:

```
   git clone https://github.com/scarrez/awa-alire-index.git
   alr index --reset-community
   alr index --add file://$PWD/awa-alire-index --name awa
```

