# sonar-scanner
plain vanilla sonar scanner

---

See the [sonar-scanner documentation](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/) for configuration and usage.


## building


In order to specify the version of sonar scanner to use, set the
`SONAR_SCANNER_VERSION` build argument.

For example:

```bash
docker build -t raisepartner/sonar-scanner --build-arg SONAR_SCANNER_VERSION=4.0.0.1744-linux .
```


## running


```bash
docker run -it --rm raisepartner/sonar-scanner sonar-scanner -Dsonar.host.url=<YOUR_SONAR_HOST_URL>
```
