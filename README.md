Sonar Demo
==========

How to use sonar to analysis a maven project.

Sonar Server
-------------

```
brew install sonar
sonar start
open http://localhost:9000
```

Scan the project
----------------

```
mvn sonar:sonar
```

Question
--------

Seems like the `sonar` plugin is a built-in plugin, but can't determine

Articles
--------

1. <http://docs.sonarqube.org/display/SCAN/Analyzing+with+SonarQube+Scanner+for+Maven#AnalyzingwithSonarQubeScannerforMaven-AnalyzingaMavenProject>


