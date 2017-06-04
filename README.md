# my-company-adminserver-backingservice [![CircleCI](https://circleci.com/gh/ivans-innovation-lab/my-company-adminserver-backingservice.svg?style=svg)](https://circleci.com/gh/ivans-innovation-lab/my-company-adminserver-backingservice)
A simple application to manage and monitor microservices

## Running instructions

Make sure that services are running:

 - my-company-configuration-backingservice
 - my-company-registry-backingservice
 

```bash
$ cd my-company-adminserver-backingservice
$ ./mvnw spring-boot:run
```

Application will be available on port 9998 (http://localhost:9998)
