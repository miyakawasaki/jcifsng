JCIFS
=====

JCIFS is an Open Source client library that implements the CIFS/SMB networking protocol in 100% Java.
From version 2.x, this project is forked from [jcifs-ng](http://central.maven.org/maven2/org/codelibs/jcifs/).

## Version

[Versions in Maven Repository](https://github.com/asaokawasaki/jcifsngomitservlet/)

## Using Maven

Put the following block into pom.xml if using Maven:

    <dependency>
        <groupId>com.github.asaokawasaki</groupId>
        <artifactId>jcifsomitservlet</artifactId>
        <version>0.0.1</version>
    </dependency>

## Changes

 * SMB2 (2.02 protocol level) support, some SMB3 support
 * Remove global state
 * Allow per context configuration
 * Logging through SLF4J
 * Drop pre-java 1.7 support
 * Unify authentication subsystem, NTLMSSP/Kerberos support
 * Large ReadX/WriteX support
 * Streaming list operations
 * NtTransNotifyChange support
 * Google patches: various bugfixes, lastAccess support, retrying requests
 * A proper test suite
 * Various fixes

