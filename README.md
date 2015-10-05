== README

This is a demo project to replicate an issue with OpenShift 3 STI artifact
saving/restoring.

* It contains a heavy load of gems and bower assets as taken from a real-world project.
* It uses the STI official `openshift/ruby-22-centos7` image from docker hub,
  along with customized assemble/save-artifacts scripts (since the default
  ones do not yet support artifact saving).
* Without restoring artifacts the project should build in __8-10 minutes__
* With restored artifacts the project should build in about __4 minutes__

The build configuration and sample log outputs are included in the `extra` directory.
