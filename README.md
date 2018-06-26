# microservicios-netflixoss

## Overview

This repo contains many microservices projects

### Build
Use this way to build the entire project without tests, with sonarqube

```bash
$ mvn clean compile package -Dmaven.test.skip=true sonar:sonar
```

### Updates
microservice-demo-order/src/main/java/com/ewolff/microservice/order/Or
derApp.java

```bash
System.out.println(“Added by me in OrderApp ”);
```

microservice-demo-customer/src/main/java/com/ewolff/microservice/custo
mer/CustomerApp.java

```bash
System.out.println(“Added by me in CustomerApp ”);
```

microservice-demo-catalog/src/main/java/com/ewolff/microservice/catalog
/Item.java

```bash
System.out.println(“Added by me in Item ”);
```
