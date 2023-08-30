# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.1`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.1
------------------------------------------------------------

Build time:   2023-08-30 06:50:19 UTC
Revision:     7a534de64018b2b478ecadb2acce4d8a917ad34b

Spring Boot:  3.0.10
Gradle:       7.6.2
Groovy:       4.0.14
JVM:          17.0.8 (Azul Systems, Inc. 17.0.8+7-LTS)
OS:           Mac OS X 12.6.8 aarch64
```

### App Environment

```bash
➜  goboots-2023-demo git:(main) ✗ grails about
| About your application's environment

Name:               goboots-2023-demo
Version:            0.1
Plugins:            [core:2023.0.1], [dataSource:2023.0.1], [i18n:2023.0.1], [codecs:2023.0.1], [restResponder:2023.0.1], [controllers:2023.0.1], [converters:2023.0.1], [urlMappings:2023.0.1], [interceptors:2023.0.1], [domainClass:2023.0.1], [groovyPages:2023.0.1], [controllersAsync:6.0.1], [databaseMigration:4.2.0], [hibernate:2023.0.1], [eventBus:6.0.1], [geb:6.0.1], [assetPipeline:6.0.1], [fields:6.0.1], [dynamicModules:2023.0.1], [scaffolding:6.0.1], [services:2023.0.1], [cache:6.0.1]
Application root:   /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo
Environment:        development

Grails:             2023.0.1
Groovy:             4.0.14
Gradle:             7.6.2
Spring Boot:        3.0.10
JVM:                17.0.8 (Azul Systems, Inc. 17.0.8+7-LTS)
OS:                 Mac OS X 12.6.8 aarch64

| EXECUTE SUCCESSFUL
```

### App Directory

```bash
.
├── app
│   ├── assets
│   ├── conf
│   ├── controllers
│   ├── domain
│   ├── i18n
│   ├── init
│   ├── services
│   ├── taglib
│   ├── utils
│   └── views
├── gradle
│   └── wrapper
├── src
│   ├── integration-test
│   ├── main
│   └── test
├── README.md
├── build.gradle
├── gradle.properties
├── gradlew
├── gradlew.bat
└── settings.gradle
```

### Installed Plugins

| Order   |   Plugin Name        |  Plugin Version               |
|---------|----------------------|-------------------------------|
|    1    |  Core                |  2023.0.1                     |
|    2    |  DataSource          |  2023.0.1                     |
|    3    |  I18n                |  2023.0.1                     |
|    4    |  Codecs              |  2023.0.1                     |
|    5    |  RestResponder       |  2023.0.1                     |
|    6    |  Controllers         |  2023.0.1                     |
|    7    |  Converters          |  2023.0.1                     |
|    8    |  UrlMappings         |  2023.0.1                     |
|    9    |  Interceptors        |  2023.0.1                     |
|   10    |  DomainClass         |  2023.0.1                     |
|   11    |  DynamicModules      |  2023.0.1                     |
|   12    |  Services            |  2023.0.1                     |
|   13    |  GroovyPages         |  2023.0.1                     |
|   14    |  Hibernate           |  2023.0.1                     |
|   15    |  AssetPipeline       |  6.0.1                        |
|   16    |  ControllersAsync    |  6.0.1                        |
|   17    |  EventBus            |  6.0.1                        |
|   18    |  Cache               |  6.0.1                        |
|   19    |  Fields              |  6.0.1                        |
|   20    |  Geb                 |  6.0.1                        |
|   21    |  Scaffolding         |  6.0.1                        |
|   22    |  DatabaseMigration   |  4.2.0                        |


### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-08-30 16:36:31.990  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.1.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::                      (v2023.0.1)

2023-08-30 16:36:32.110  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.8 with PID 93395 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-08-30 16:36:32.110 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.10, Spring v6.0.11
2023-08-30 16:36:32.111  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-08-30 16:36:32.216  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-08-30 16:36:32.216  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-08-30 16:36:33.118  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 22 plugins loaded successfully, take in 138 ms
2023-08-30 16:36:33.983  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-08-30 16:36:33.987  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-08-30 16:36:33.988  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-08-30 16:36:33.988  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.12]
2023-08-30 16:36:34.013  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-08-30 16:36:34.013  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1796 ms
2023-08-30 16:36:34.192  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-08-30 16:36:34.521  INFO --- [  restartedMain] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 5.6.15.Final
2023-08-30 16:36:34.645  INFO --- [  restartedMain] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.2.Final}
2023-08-30 16:36:34.700  INFO --- [  restartedMain] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2023-08-30 16:36:35.168  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-08-30 16:36:35.513  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-08-30 16:36:35.739  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-08-30 16:36:35.745  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-08-30 16:36:35.745  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-08-30 16:36:35.746  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 1 ms
2023-08-30 16:36:35.746  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-08-30 16:36:35.845  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 4.206 seconds (process running for 5.18)
2023-08-30 16:36:35.849  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
----------------------------------------------------------------------------------------------
Order      Plugin Name                              Plugin Version                     Enabled
----------------------------------------------------------------------------------------------
    1      Core                                     2023.0.1                                 Y
    2      DataSource                               2023.0.1                                 Y
    3      I18n                                     2023.0.1                                 Y
    4      Codecs                                   2023.0.1                                 Y
    5      RestResponder                            2023.0.1                                 Y
    6      Controllers                              2023.0.1                                 Y
    7      Converters                               2023.0.1                                 Y
    8      UrlMappings                              2023.0.1                                 Y
    9      Interceptors                             2023.0.1                                 Y
   10      DomainClass                              2023.0.1                                 Y
   11      GroovyPages                              2023.0.1                                 Y
   12      Geb                                      6.0.1                                    Y
   13      Scaffolding                              6.0.1                                    Y
   14      AssetPipeline                            6.0.1                                    Y
   15      DatabaseMigration                        4.2.0                                    Y
   16      EventBus                                 6.0.1                                    Y
   17      Fields                                   6.0.1                                    Y
   18      DynamicModules                           2023.0.1                                 Y
   19      ControllersAsync                         6.0.1                                    Y
   20      Hibernate                                2023.0.1                                 Y
   21      Services                                 2023.0.1                                 Y
   22      Cache                                    6.0.1                                    Y
----------------------------------------------------------------------------------------------

2023-08-30 16:36:35.861  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.128:8080
---------------------------------------------------------------------------------------------
```
