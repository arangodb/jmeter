# jmeter
JMeter examples for ArangoDB

This repository includes an accumulation of ArangoDB and JMeter
examples.  The first example was posted in April 2019 for ArangoDB 3.4.  Over time the
examples may or may not continue to work with subsequent releases.
Post an issue to this repository if you find something that no longer
works and would like it fixed.

## Example 1:  JMeter, ArangoDB, Java Client simple setup

### Installation

1. Download and install JMeter : http://jmeter.apache.org/download_jmeter.cgi

2. Build (https://github.com/arangodb/arangodb-java-driver) or
download prebuilt (https://github.com/arangodb/jmeter) ArangoDB java driver jar
file.  You need the "standalone" version such as

<pre>
arangodb-java-driver-5.0.5-SNAPSHOT-standalone.jar
</pre>

3. Copy the ArangoDB jar file to JMeter's lib/ext folder

Installation is complete.
