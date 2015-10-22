# ACL-API-client-java
Client written in Java for Globo ACL API.


## To release a new version

    mvn clean release:prepare -Dgpg.passphrase='XXX'
    mvn release:perform -Dgpg.passphrase='XXX'
