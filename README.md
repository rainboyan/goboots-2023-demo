# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.2`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.2
------------------------------------------------------------

Build time:   2023-09-08 03:20:18 UTC
Revision:     244581b09d70fa8997b1b9ce2155bd6546d46252

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
Plugins:            [core:2023.0.2], [dataSource:2023.0.2], [i18n:2023.0.2], [codecs:2023.0.2], [restResponder:2023.0.2], [controllers:2023.0.2], [converters:2023.0.2], [urlMappings:2023.0.2], [interceptors:2023.0.2], [domainClass:2023.0.2], [groovyPages:2023.0.2], [hibernate:2023.0.2], [databaseMigration:4.2.0], [scaffolding:6.0.2], [fields:6.0.2], [geb:6.0.2], [eventBus:6.0.2], [dynamicModules:2023.0.2], [assetPipeline:6.0.2], [controllersAsync:6.0.2], [services:2023.0.2], [cache:6.0.2]
Application root:   /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo
Environment:        development

Grails:             2023.0.2
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
|    1    |  Core                |  2023.0.2                     |
|    2    |  DataSource          |  2023.0.2                     |
|    3    |  I18n                |  2023.0.2                     |
|    4    |  Codecs              |  2023.0.2                     |
|    5    |  RestResponder       |  2023.0.2                     |
|    6    |  Controllers         |  2023.0.2                     |
|    7    |  Converters          |  2023.0.2                     |
|    8    |  UrlMappings         |  2023.0.2                     |
|    9    |  Interceptors        |  2023.0.2                     |
|   10    |  DomainClass         |  2023.0.2                     |
|   11    |  DynamicModules      |  2023.0.2                     |
|   12    |  Services            |  2023.0.2                     |
|   13    |  GroovyPages         |  2023.0.2                     |
|   14    |  Hibernate           |  2023.0.2                     |
|   15    |  AssetPipeline       |  6.0.2                        |
|   16    |  ControllersAsync    |  6.0.2                        |
|   17    |  EventBus            |  6.0.2                        |
|   18    |  Cache               |  6.0.2                        |
|   19    |  Fields              |  6.0.2                        |
|   20    |  Geb                 |  6.0.2                        |
|   21    |  Scaffolding         |  6.0.2                        |
|   22    |  DatabaseMigration   |  4.2.0                        |


### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-09-08 18:34:52.862  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.1.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::                      (v2023.0.2)

2023-09-08 18:34:52.927  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.8 with PID 59452 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-09-08 18:34:52.927 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.10, Spring v6.0.11
2023-09-08 18:34:52.927  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-09-08 18:34:52.954  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-09-08 18:34:52.954  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-09-08 18:34:53.508  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 22 plugins loaded successfully, take in 122 ms
2023-09-08 18:34:54.355  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-09-08 18:34:54.359  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-09-08 18:34:54.360  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-09-08 18:34:54.360  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.12]
2023-09-08 18:34:54.389  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-09-08 18:34:54.389  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1434 ms
2023-09-08 18:34:54.568  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-09-08 18:34:54.901  INFO --- [  restartedMain] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 5.6.15.Final
2023-09-08 18:34:55.011  INFO --- [  restartedMain] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.2.Final}
2023-09-08 18:34:55.062  INFO --- [  restartedMain] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2023-09-08 18:34:55.517  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-09-08 18:34:55.840  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-09-08 18:34:56.080  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-09-08 18:34:56.086  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-09-08 18:34:56.086  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-09-08 18:34:56.087  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 1 ms
2023-09-08 18:34:56.088  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-09-08 18:34:56.183  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 3.473 seconds (process running for 3.915)
2023-09-08 18:34:56.187  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
----------------------------------------------------------------------------------------------
Order      Plugin Name                              Plugin Version                     Enabled
----------------------------------------------------------------------------------------------
    1      Core                                     2023.0.2                                 Y
    2      DataSource                               2023.0.2                                 Y
    3      I18n                                     2023.0.2                                 Y
    4      Codecs                                   2023.0.2                                 Y
    5      RestResponder                            2023.0.2                                 Y
    6      Controllers                              2023.0.2                                 Y
    7      Converters                               2023.0.2                                 Y
    8      UrlMappings                              2023.0.2                                 Y
    9      Interceptors                             2023.0.2                                 Y
   10      DomainClass                              2023.0.2                                 Y
   11      GroovyPages                              2023.0.2                                 Y
   12      DatabaseMigration                        4.2.0                                    Y
   13      Hibernate                                2023.0.2                                 Y
   14      Fields                                   6.0.2                                    Y
   15      Geb                                      6.0.2                                    Y
   16      DynamicModules                           2023.0.2                                 Y
   17      Scaffolding                              6.0.2                                    Y
   18      ControllersAsync                         6.0.2                                    Y
   19      EventBus                                 6.0.2                                    Y
   20      AssetPipeline                            6.0.2                                    Y
   21      Services                                 2023.0.2                                 Y
   22      Cache                                    6.0.2                                    Y
----------------------------------------------------------------------------------------------

2023-09-08 18:34:56.209  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.128:8080
----------------------------------------------------------------------------------------------
```
