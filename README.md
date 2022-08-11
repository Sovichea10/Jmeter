# Jmeter
Apache JMeter is an Apache project that can be used as a load testing tool for analyzing and measuring the performance of a variety of services, with a focus on web applications.

## Jmeter installation
1. Go to https://jmeter.apache.org/download_jmeter.cgi
2. On Binaries, click download "apache-jmeter-5.5.zip	sha512	pgp"

## Jmeter usage
1. Create test plan : set any name you want
2. Add Thread group user to test plan
3. Config thread delay
4. Create HTTP request 
5. Right-click HTTP request, go to listener to create |View Results Tree, View Results in Table, Summary Report|
6. Generate report by creating "Simple Data Writer"
7. In Simple Data Writer, set filename with extension 'csv' in directory bin
8. Go to terminal, genrate from an existing sample CSV log file using command : 
``sh
   jmeter -g <log file> -o <Path to output folder>
```
