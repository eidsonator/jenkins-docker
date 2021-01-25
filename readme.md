
Set up env varaibles for `JENKINS_USER` and `JENKINS_PASS`

```bash
docker build -t jenkins .
docker run -dp 8080:8080 jenkins
```