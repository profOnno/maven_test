# maven_test
Testing maven versions plugin

## Links
(Versions Plugin Introduction)[https://www.mojohaus.org/versions/versions-maven-plugin/examples/setaggregator.html]
(Set aggregator)[https://www.mojohaus.org/versions/versions-maven-plugin/examples/setaggregator.html]

## Example
`mvn versions:help`

`mvn versions:set -DnewVersion=1.6.3-SNAPSHOT -Doldversion=* -DgroupId=* -DartifactId=*`

`mvn versions:revert`
