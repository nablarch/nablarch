# Nablarch Framework

Nablarch is a middleware pattern based Java application framework.

## Issue Tracking

Report issues via the [Nablarch JIRA](https://nablarch.atlassian.net).
  
## Modules

The Nablarch Framework consists of features organized into about 83 modules. These modules are grouped into [Nablarch Core](#link1), [Nablarch Framework](#link2),
[Nablarch Common Component](#link3), [Nablarch Adaptor](#link4), [Nablarch Framework Examples](#link5), [Nablarch ETL Foundation](#link6), [Nablarch Workflow](#link7),
[Nablarch Report](#link8), [Nablarch Example Implementations](#link9), [Misc](#link10), as shown in the following tables.

### <a name ="link1">Nablarch Core

|Module name|Description
|:-----|:-----
|[nablarch-core](https://github.com/nablarch/nablarch-core)|Nablarch Core
|[nablarch-core-beans](https://github.com/nablarch/nablarch-core-beans         )|JavaBeans Utilities
|[nablarch-core-repository](https://github.com/nablarch/nablarch-core-repository     )|Settings manager
|[nablarch-core-transaction](https://github.com/nablarch/nablarch-core-transaction )|Transaction managers
|[nablarch-core-jdbc](https://github.com/nablarch/nablarch-core-jdbc         )|JDBC Utilities
|[nablarch-core-message](https://github.com/nablarch/nablarch-core-message     )|Messages (Error Message, Warning, etc.)
|[nablarch-core-validation](https://github.com/nablarch/nablarch-core-validation     )|Input validation
|[nablarch-core-validation-ee](https://github.com/nablarch/nablarch-core-validation-ee )|JSR-303 Bean Validation API
|[nablarch-core-dataformat](https://github.com/nablarch/nablarch-core-dataformat     )|File manager
|[nablarch-core-applog](https://github.com/nablarch/nablarch-core-applog         )|Logging

### <a name ="link2">Nablarch Framework

|Module name|Description
|:-----|:-----
|[nablarch-fw](https://github.com/nablarch/nablarch-fw )| Nablarch Handlers
|[nablarch-fw-web](https://github.com/nablarch/nablarch-fw-web )| Basic web-oriented integration features
|[nablarch-fw-web-dbstore](https://github.com/nablarch/nablarch-fw-web-dbstore )| Session store implementation using JDBC
|[nablarch-fw-web-redisstore](https://github.com/nablarch/nablarch-fw-web-redisstore )| Session store implementation using Redis
|[nablarch-fw-web-tag](https://github.com/nablarch/nablarch-fw-web-tag )| JSP Custom Tag Library for Nablarch
|[nablarch-fw-web-hotdeploy](https://github.com/nablarch/nablarch-fw-web-hotdeploy )| Hot deploy
|[nablarch-fw-web-extension](https://github.com/nablarch/nablarch-fw-web-extension )| Web File uploading and downloading
|[nablarch-fw-web-doublesubmit-jdbc](https://github.com/nablarch/nablarch-fw-web-doublesubmit-jdbc )| Token manager  implementation using JDBC
|[nablarch-fw-web-doublesubmit-redis](https://github.com/nablarch/nablarch-fw-web-doublesubmit-redis )| Token manager  implementation using Redis
|[nablarch-fw-batch-ee](https://github.com/nablarch/nablarch-fw-batch-ee )| JSR352 jBatch APIs
|[nablarch-fw-jaxrs](https://github.com/nablarch/nablarch-fw-jaxrs )| RESTful Web Services
|[nablarch-fw-standalone](https://github.com/nablarch/nablarch-fw-standalone )| Provide standalone application's entrypoint
|[nablarch-fw-batch](https://github.com/nablarch/nablarch-fw-batch )| Basic handlers and actions for batch application
|[nablarch-fw-messaging](https://github.com/nablarch/nablarch-fw-messaging )| Messaging architecture and protocols
|[nablarch-fw-messaging-http](https://github.com/nablarch/nablarch-fw-messaging-http )| HTTP Messaging
|[nablarch-fw-messaging-mom](https://github.com/nablarch/nablarch-fw-messaging-mom )| MOM(Message Oriented Middleware) Messaging

### <a name ="link3">Nablarch Common Component

|Module name|Description
|:-----|:-----
|[nablarch-common-dao](https://github.com/nablarch/nablarch-common-dao )| Generating SQL from Entity classes
|[nablarch-common-idgenerator](https://github.com/nablarch/nablarch-common-idgenerator )| ID generators
|[nablarch-common-idgenerator-jdbc](https://github.com/nablarch/nablarch-common-idgenerator-jdbc )| ID generators implementation using JDBC
|[nablarch-common-jdbc](https://github.com/nablarch/nablarch-common-jdbc )| Db connection handler
|[nablarch-common-code](https://github.com/nablarch/nablarch-common-code )| Classification code manager
|[nablarch-common-code-jdbc](https://github.com/nablarch/nablarch-common-code-jdbc )| Classification code manager using OTLT(One True Lookup Table)
|[nablarch-common-auth](https://github.com/nablarch/nablarch-common-auth )| Authorization
|[nablarch-common-auth-jdbc](https://github.com/nablarch/nablarch-common-auth-jdbc )| Authorization implementation using JDBC
|[nablarch-common-exclusivecontrol](https://github.com/nablarch/nablarch-common-exclusivecontrol )| Locking
|[nablarch-common-exclusivecontrol-jdbc](https://github.com/nablarch/nablarch-common-exclusivecontrol-jdbc )| Locking implementation using JDBC
|[nablarch-common-encryption](https://github.com/nablarch/nablarch-common-encryption )| Encrypting
|[nablarch-common-date](https://github.com/nablarch/nablarch-common-date )| Handling System Date and Business Date
|[nablarch-common-databind](https://github.com/nablarch/nablarch-common-databind )| Supporting various data types in Java Beans, Collection Framework like Map, List, etc.
|[nablarch-mail-sender](https://github.com/nablarch/nablarch-mail-sender )| E-mail

### <a name ="link4">Nablarch Adaptor

| Module name                                                                                                    | Description                                 |
| :-----                                                                                                         | :-----                                      |
| [nablarch-router-adaptor](https://github.com/nablarch/nablarch-router-adaptor)                                 | Adaptor for http-request-router             |
| [nablarch-jaxrs-adaptor](https://github.com/nablarch/nablarch-jaxrs-adaptor)                                   | Adaptors for JAX-RS impls                   |
| [nablarch-wmq-adaptor](https://github.com/nablarch/nablarch-wmq-adaptor)                                       | Adaptor for WebSphere MQ                    |
| [nablarch-log4j-adaptor](https://github.com/nablarch/nablarch-log4j-adaptor)                                   | Adaptor for Log4j                           |
| [nablarch-slf4j-adaptor](https://github.com/nablarch/nablarch-slf4j-adaptor)                                   | Adaptor for SLF4J                           |
| [nablarch-jboss-logging-adaptor](https://github.com/nablarch/nablarch-jboss-logging-adaptor)                   | Adaptor for JBoss Logging                   |
| [nablarch-doma-adaptor](https://github.com/nablarch/nablarch-doma-adaptor)                                     | Adaptor for Doma                            |
| [nablarch-mail-sender-freemarker-adaptor](https://github.com/nablarch/nablarch-mail-sender-freemarker-adaptor) | Adaptor for FreeMarker (E-mail Template)    |
| [nablarch-mail-sender-thymeleaf-adaptor](https://github.com/nablarch/nablarch-mail-sender-thymeleaf-adaptor)   | Adaptor for Thymeleaf (E-mail Template)     |
| [nablarch-mail-sender-velocity-adaptor](https://github.com/nablarch/nablarch-mail-sender-velocity-adaptor)     | Adaptor for Velocity (E-mail Template)      |
| [nablarch-web-thymeleaf-adaptor](https://github.com/nablarch/nablarch-web-thymeleaf-adaptor)                   | Adaptor for Thymeleaf (for Web Application) |
| [nablarch-redisstore-lettuce-adaptor](https://github.com/nablarch/nablarch-redisstore-lettuce-adaptor)         | Adaptor for Lettuce (for Redis session store) |
| [nablarch-micrometer-adaptor](https://github.com/nablarch/nablarch-micrometer-adaptor)                         | Adaptor for Micrometer                      |
| [slf4j-nablarch-adaptor](https://github.com/nablarch/slf4j-nablarch-adaptor)                                   | Adapter to use Nablarch Logger via SLF4J    |

### <a name ="link5">Nablarch Framework Examples

|Module name|Description
|:-----|:-----
|[nablarch-example-web](https://github.com/nablarch/nablarch-example-web)|Example of web application
|[nablarch-example-batch-ee](https://github.com/nablarch/nablarch-example-batch-ee)|Example of JSR352 jBatch APIs
|[nablarch-example-batch](https://github.com/nablarch/nablarch-example-batch)|Example code of batch application
|[nablarch-example-mom-sync-receive](https://github.com/nablarch/nablarch-example-mom-sync-receive)|Example of MOM (synchronous messaging receiving)
|[nablarch-example-mom-sync-send-batch](https://github.com/nablarch/nablarch-example-mom-sync-send-batch)|Example of MOM (synchronous messaging sending)
|[nablarch-example-mom-delayed-send](https://github.com/nablarch/nablarch-example-mom-delayed-send)|Example of MOM (asynchronous messaging sending)
|[nablarch-example-mom-delayed-receive](https://github.com/nablarch/nablarch-example-mom-delayed-receive)|Example of MOM (asynchronous messaging receiving)
|[nablarch-example-mom-testing-common](https://github.com/nablarch/nablarch-example-mom-testing-common)|Example of MOM (common function)
|[nablarch-example-http-messaging](https://github.com/nablarch/nablarch-example-http-messaging)|Example of HTTP Messaging (receiving)
|[nablarch-example-http-messaging-send](https://github.com/nablarch/nablarch-example-http-messaging-send)|Example of HTTP Messaging (sending)
|[nablarch-example-rest](https://github.com/nablarch/nablarch-example-rest)|Example of RESTful Web Services
|[nablarch-example-db-queue](https://github.com/nablarch/nablarch-example-db-queue)|Example of database as queue

### <a name ="link6">Nablarch ETL Foundation

|Module name|Description
|:-----|:-----
|[nablarch-etl](https://github.com/nablarch/nablarch-etl)|ETL(Extract, transform, load) processing
|[nablarch-etl-maven-plugin](https://github.com/nablarch/nablarch-etl-maven-plugin)|Generator of ETL processing config file

### <a name ="link7">Nablarch Workflow

|Module name|Description
|:-----|:-----
|[nablarch-workflow](https://github.com/nablarch/nablarch-workflow)|Providing workflow functions
|[nablarch-workflow-tool](https://github.com/nablarch/nablarch-workflow-tool)|Tool to convert from BPMN2.0 definition to workflow data
|[nablarch-workflow-sample](https://github.com/nablarch/nablarch-workflow-sample)|Sample of workflow

### <a name ="link8">Nablarch Report

|Module name|Description
|:-----|:-----
|[nablarch-report](https://github.com/nablarch/nablarch-report)|Generate pdf files
|[nablarch-report-sample](https://github.com/nablarch/nablarch-report-sample)|Example of generating pdf

### <a name ="link9">Nablarch Example Implementations

|Module name|Description
|:-----|:-----
|[nablarch-biz-sample-all](https://github.com/nablarch/nablarch-biz-sample-all)|Sample applications as follows <br>  *Password authentication <br>* Extension of Validation <br>  *Search result <br>* Extension of Data Formatter <br>  *File management with database <br>* Captcha <br>  *Prepare user agent <br>* HTML mail sending
|[nablarch-smime-integration](https://github.com/nablarch/nablarch-smime-integration)|Example of smime mail sending
|[nablarch-statistics-report](https://github.com/nablarch/nablarch-statistics-report)|Example of Log Aggregation
|[nablarch-messaging-simulator](https://github.com/nablarch/nablarch-messaging-simulator)|Example of messaging simulator (stub or driver)

### <a name ="link10">Misc

|Module name|Description
|:-----|:-----
|[nablarch-document](https://github.com/nablarch/nablarch-document)|Nablarch document sourcecode(sphinx)
|[nablarch-plugins-bundle](https://github.com/nablarch/nablarch-plugins-bundle)|Framework for web application with easy development
|[nablarch-ui-build-test-pj](https://github.com/nablarch/nablarch-ui-build-test-pj)|Test project for nablarch-plugins-bundle
|[nablarch-plugins-bundle-test](https://github.com/nablarch/nablarch-plugins-bundle-test)|Test cases for nablarch-plugins-bundle
|[nablarch-ui-development-template](https://github.com/nablarch/nablarch-ui-development-template)|Template for using nablarch-plugins-bundle
|[nablarch-intellij-plugin](https://github.com/nablarch/nablarch-intellij-plugin)|Nablarch support plugin in IntelliJ IDEA
|[nablarch-toolbox](https://github.com/nablarch/nablarch-toolbox)|Development tools
|[sql-executor](https://github.com/nablarch/sql-executor)|SQL Executor tools
|[nablarch-testing](https://github.com/nablarch/nablarch-testing )| Application testing
|[nablarch-testing-jetty6](https://github.com/nablarch/nablarch-testing-jetty6 )| Application testing with jetty6
|[nablarch-testing-jetty9](https://github.com/nablarch/nablarch-testing-jetty9 )| Application testing with jetty9
|[nablarch-testing-rest](https://github.com/nablarch/nablarch-testing-rest)| Application testing for RESTful web service
|[nablarch-testing-junit5](https://github.com/nablarch/nablarch-testing-junit5)| Extensions for using the JUnit5 in the application testing
|[nablarch-single-module-archetype](https://github.com/nablarch/nablarch-single-module-archetype)|Maven archetype
|[nablarch-profiles](https://github.com/nablarch/nablarch-profiles)|Maven pom
|[nablarch-default-configuration](https://github.com/nablarch/nablarch-default-configuration)|Default configuration files
|[nablarch-backward-compatibility](https://github.com/nablarch/nablarch-backward-compatibility )| Assuring Nablarch's old version compatibility
|[master](https://github.com/nablarch/master )| Integrating several Gradle projects for developers
|[nablarch-test-support](https://github.com/nablarch/nablarch-test-support )| Test support library for Nablarch framework
|[nablarch-test-support-hereis](https://github.com/nablarch/nablarch-test-support-hereis)|Test support library for Nablarch framework
|[nablarch-integration-test](https://github.com/nablarch/nablarch-integration-test )| JUnit Test for handler queues
|[nablarch-module-version](https://github.com/nablarch/nablarch-module-version)|Nablarch version management
|[nablarch-gradle-plugin](https://github.com/nablarch/nablarch-gradle-plugin)|Gradle plugin for projects using Nablarch
|[nablarch-unpublished-api-checker-findbugs](https://github.com/nablarch/nablarch-unpublished-api-checker-findbugs)|Detector plugin for FindBugs
|[nablarch-unpublished-api-checker](https://github.com/nablarch/nablarch-unpublished-api-checker)|Detector plugin for SpotBugs

# License

Nablarch is released under the terms of the Apache Software License Version 2.0 (see [LICENSE.txt](https://github.com/nablarch/nablarch/blob/master/LICENSE.txt)).
