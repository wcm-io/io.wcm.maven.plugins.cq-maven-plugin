<img src="https://wcm.io/images/favicon-16@2x.png"/> cq-maven-plugin
======
[![Build](https://github.com/wcm-io/cq-maven-plugin/workflows/Build/badge.svg?branch=develop)](https://github.com/wcm-io/cq-maven-plugin/actions?query=workflow%3ABuild+branch%3Adevelop)

Convenience maven plugin for working with CQ/AEM maven projects.

Documentation: https://wcm.io/tooling/maven/plugins/cq-maven-plugin/<br/>
Issues: https://wcm-io.atlassian.net/browse/WTOOL<br/>
Wiki: https://wcm-io.atlassian.net/wiki/<br/>
Continuous Integration: https://github.com/wcm-io/cq-maven-plugin/actions<br/>
Commercial support: https://wcm.io/commercial-support.html


## Build from sources

If you want to build wcm.io from sources make sure you have configured all [Maven Repositories](https://wcm.io/maven.html) in your settings.xml.

See [Maven Settings](https://github.com/wcm-io/cq-maven-plugin/blob/develop/.maven-settings.xml) for an example with a full configuration.

Then you can build using

```
mvn clean install
```