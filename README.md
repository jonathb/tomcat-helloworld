###  Docker Tomcat  HedlloWorld

docker run -p 9080:9080 -v <host-folder>:<guest-folder>  -d --name tomcat  jonathb/tomcat:latest

Bang the front on http://lcoalhost:8080/sample

or better set a host in dockerfile.

Then shelll into the guest and look at the access log.

