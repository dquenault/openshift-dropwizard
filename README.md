Dropwizard Cart for Openshift
-----------------------------

This is a (VERY) basic cartridge which creates an environment for deploying a standalone dropwizard jar. The templated application
gives you a basic hello-world dropwizard service and a yml file for additional configuration parameters.

To run!

> rhc create-app dw https://raw.githubusercontent.com/dquenault/openshift-dropwizard/master/metadata/manifest.yml -g small

Try

> http://server/hello-world
