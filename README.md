# Example CASified Java Web Application

This is a sample java web application that exercises the CAS protocol features via the Java CAS Client.
This repo is a fork of the [official sample app](https://github.com/cas-projects/cas-sample-java-webapp),
with small tweaks to be a more effective example of configuration for apps at Cru.

Configure
---------

- Adjust the url endpoints of the CAS server and 
the application server in the [`web.xml`](https://github.com/UniconLabs/cas-sample-java-webapp/blob/master/src/main/webapp/WEB-INF/web.xml) file.

## Build

```bash
mvn clean package jetty:run-forked
```

The application will be available on:
```bash
http://localhost:8080/sample
```

 
