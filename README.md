# Nablarch Framework

Nablarch is a middleware pattern based Java application framework.
  
# Modules
The Nablarch Framework consists of features arganized into about 56 modules. These modules are grouped into Nablarch Core, Nablarch Framework, 
Nablarch Common Component, Nablarch Extension Component, Nablarch Adaptor, Misc, as shown in the following tables.

### Nablarch Core

|Module name|Description
|:-----|:-----
|[nablarch-core](https://github.com/nablarch/nablarch-core)|Nablarch Core
|[nablarch-core-beans	        ](https://github.com/nablarch/nablarch-core-beans	        )|JavaBeans Utilities
|[nablarch-core-repository	](https://github.com/nablarch/nablarch-core-repository	    )|Settings manager
|[nablarch-core-transaction	](https://github.com/nablarch/nablarch-core-transaction	)|Transaction managers
|[nablarch-core-jdbc	        ](https://github.com/nablarch/nablarch-core-jdbc	        )|JDBC Utilities
|[nablarch-core-message	    ](https://github.com/nablarch/nablarch-core-message	    )|Messages (Error Message, Warning, etc.)
|[nablarch-core-validation	](https://github.com/nablarch/nablarch-core-validation	    )|Input validation
|[nablarch-core-validation-ee	](https://github.com/nablarch/nablarch-core-validation-ee	)|JSR-303 Bean Validation API
|[nablarch-core-dataformat	](https://github.com/nablarch/nablarch-core-dataformat	    )|File manager
|[nablarch-core-applog	    ](https://github.com/nablarch/nablarch-core-applog	        )|Logging

### Nablarch Framework


|Module name|Description
|:-----|:-----
|[nablarch-fw	](https://github.com/nablarch/nablarch-fw	)|	Nablarch Handlers
|[nablarch-fw-web	](https://github.com/nablarch/nablarch-fw-web	)|	Basic web-oriented integration features
|[nablarch-fw-web-dbstore	](https://github.com/nablarch/nablarch-fw-web-dbstore	)|	Session store implementation using JDBC
|[nablarch-fw-web-tag	](https://github.com/nablarch/nablarch-fw-web-tag	)|	JSP Custom Tag Library for Nablarch
|[nablarch-fw-web-hotdeploy	](https://github.com/nablarch/nablarch-fw-web-hotdeploy	)|	Hot deploy
|[nablarch-fw-web-extension	](https://github.com/nablarch/nablarch-fw-web-extension	)|	Web File uploading and downloading
|[nablarch-fw-batch-ee	](https://github.com/nablarch/nablarch-fw-batch-ee	)|	JSR352 jBatch APIs
|[nablarch-fw-jaxrs	](https://github.com/nablarch/nablarch-fw-jaxrs	)|	RESTful Web Services
|[nablarch-fw-standalone	](https://github.com/nablarch/nablarch-fw-standalone	)|	Provide standalone application's entrypoint
|[nablarch-fw-batch	](https://github.com/nablarch/nablarch-fw-batch	)|	Basic handlers and actions for batch application
|[nablarch-fw-messaging	](https://github.com/nablarch/nablarch-fw-messaging	)|	Messaging architecture and protocols
|[nablarch-fw-messaging-http	](https://github.com/nablarch/nablarch-fw-messaging-http	)|	HTTP Messaging
|[nablarch-fw-messaging-mom	](https://github.com/nablarch/nablarch-fw-messaging-mom	)|	MOM Messaging

### Nablarch Common Component


|Module name|Description
|:-----|:-----
|[nablarch-common-dao	](https://github.com/nablarch/nablarch-common-dao	)|	Generating SQL from Entity classes
|[nablarch-common-idgenerator	](https://github.com/nablarch/nablarch-common-idgenerator	)|	ID generators
|[nablarch-common-idgenerator-jdbc	](https://github.com/nablarch/nablarch-common-idgenerator-jdbc	)|	ID generators implementation using JDBC
|[nablarch-common-jdbc	](https://github.com/nablarch/nablarch-common-jdbc	)|	Db connection handler
|[nablarch-common-code	](https://github.com/nablarch/nablarch-common-code	)|	Classification code manager
|[nablarch-common-code-jdbc	](https://github.com/nablarch/nablarch-common-code-jdbc	)|	Classification code manager using OTLT(One True Lookup Table)
|[nablarch-common-auth	](https://github.com/nablarch/nablarch-common-auth	)|	Authorization
|[nablarch-common-auth-jdbc	](https://github.com/nablarch/nablarch-common-auth-jdbc	)|	Authorization implementation using JDBC
|[nablarch-common-exclusivecontrol	](https://github.com/nablarch/nablarch-common-exclusivecontrol	)|	Locking
|[nablarch-common-exclusivecontrol-jdbc	](https://github.com/nablarch/nablarch-common-exclusivecontrol-jdbc	)|	Locking implementation using JDBC
|[nablarch-common-encryption	](https://github.com/nablarch/nablarch-common-encryption	)|	Encrypting
|[nablarch-common-date	](https://github.com/nablarch/nablarch-common-date	)|	Handling System Date and Business Date
|[nablarch-common-databind	](https://github.com/nablarch/nablarch-common-databind	)|	Supporting various data types in Java Beans, Collection Framework like Map, List, etc.
|[nablarch-mail-sender	](https://github.com/nablarch/nablarch-mail-sender	)|	E-mail

### Nablarch Extension Component


|Module name|Description
|:-----|:-----
|[nablarch-etl	](https://github.com/nablarch/nablarch-etl	)|	ETL processing
|[nablarch-etl-maven-plugin	](https://github.com/nablarch/nablarch-etl-maven-plugin	)|	Generating ETL processing config 


### Nablarch Adaptor


|Module name|Description
|:-----|:-----
|[nablarch-router-adaptor](https://github.com/nablarch/nablarch-router-adaptor)|Adaptor for http-request-router
|[nablarch-jaxrs-adaptor](https://github.com/nablarch/nablarch-jaxrs-adaptor)|Adaptor for Adaptors for JAX-RS impls
|[nablarch-wmq-adaptor](https://github.com/nablarch/nablarch-wmq-adaptor)|Adaptor for WebSphere MQ 
|[nablarch-log4j-adaptor](https://github.com/nablarch/nablarch-log4j-adaptor)|Adaptor for Log4j

### Misc


|Module name|Description
|:-----|:-----
|[nablarch-backward-compatibility	](https://github.com/nablarch/nablarch-backward-compatibility	)|	Assuring Nablarch's old version compatibility
|[master	](https://github.com/nablarch/master	)|	Integrating several Gradle projects for developers
|[nablarch-all-test	](https://github.com/nablarch/nablarch-all-test	)|	JUnit Tests for Nablarch
|[nablarch-test-support	](https://github.com/nablarch/nablarch-test-support	)|	Test support library for Nablarch framework
|[nablarch-test-support-hereis](https://github.com/nablarch/nablarch-test-support-hereis)|Test support library for Nablarch framework
|[nablarch-integration-test	](https://github.com/nablarch/nablarch-integration-test	)|	JUnit Test for handler queues
|[nablarch-testing	](https://github.com/nablarch/nablarch-testing	)|	Application testing
|[nablarch-toolbox](https://github.com/nablarch/nablarch-toolbox)|Development tools
|[nablarch-default-configuration](https://github.com/nablarch/nablarch-default-configuration)|Default configuration files
|[nablarch-module-version](https://github.com/nablarch/nablarch-module-version)|Nablarch version management
|[nablarch-profiles](https://github.com/nablarch/nablarch-profiles)|Dependency management
|[nablarch-single-module-archetype](https://github.com/nablarch/nablarch-single-module-archetype)|Maven archetype


# License
Nablarch is released under the terms of the Apache Software License Version 2.0 (see LICENSE.txt).
