# maven_test
Testing maven versions plugin

## Links
[Versions Plugin Introduction](https://www.mojohaus.org/versions/versions-maven-plugin/examples/setaggregator.html)

[Set aggregator](https://www.mojohaus.org/versions/versions-maven-plugin/examples/setaggregator.html)

## Example
Make sure to be in the `build_scripts` folder.

`mvn versions:help`

`mvn versions:set -DnewVersion=1.6.3-SNAPSHOT -DoldVersion=* -DgroupId=* -DartifactId=*`

If it works commit, so a future revert will use this version
`mvn versions:commit`

`mvn versions:revert`
