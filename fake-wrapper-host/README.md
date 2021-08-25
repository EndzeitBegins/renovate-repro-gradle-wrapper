This directory represents an arbitrary hosting location 
for a custom gradle wrapper distribution, 
e.g. a Sonatype Nexus Repository.

The custom gradle wrapper is hosted fashioned like a Maven resource.
That is, under a groupId, artifactId and version directory structure.

Renovate expects a version file similar to 
[the official one](https://services.gradle.org/versions/all) 
in order to extract available versions for the Gradle Wrapper.
This is mimicked by the 
[custom-gradle-wrapper-versions.json](tld/domain/custom-wrapper/custom-gradle-wrapper-versions.json) 
file. 

The example "custom" wrapper files included in this repository
are just the official Gradle Wrapper in version 7.2.