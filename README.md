# Java Harbor Debug Buildpack

This buildpack is a fork from the [Cloud Foundry Java Buildpack](https://github.com/cloudfoundry/java-buildpack) with a minor modification allowing the use of Java remote debugging on Stackato, using a Harbor service.

To debug an application with this buildpack, you will need to bind a harbor service to it named `${app-name}_debug`. You can ask the Stackato command line client to do this for you before pushing your application by adding the `-d` option to the push command.
