Download nexus professional 2.0 and unpack the distribution to a local empty directory, NEXUS_HOME from here on.

Download nexus-unpack-plugin bundle and unzip it to NEXUS_HOME/nexus/WEB-INF/plugin-repository.

Disable security.

Create 'sites' hosted Maven Site repository.

From build01 directory, execute

  mvn clean install -Ppublish-site
  
p2 repository is published under http://localhost:8081/nexus/content/sites/sites/build01/1.0.0/N/<buildid>
 