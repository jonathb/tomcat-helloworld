### 4 years ago this was a demo of tomcat in a docker engine

?TODO the same but stick it in a GKE cluster.

### Docker Tomcat  HedlloWorld

docker run -p 9080:8080 -v <host-folder>:<guest-folder>  -d --name tomcat  jonathb/tomcat:latest

Bang the front on http://localhost:9080/sample

or better set a host in dockerfile.

Then shelll into the guest and look at the access log.

On the host netstat shows :9080 LISTEN by a proc "docker_proxy"

