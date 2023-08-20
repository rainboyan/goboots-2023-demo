# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.0`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.0-RC1
------------------------------------------------------------

Build time:   2023-08-19 18:52:09 UTC
Revision:     deadcc4eed411750d475429218b46811e8411e85

Spring Boot:  3.0.9
Gradle:       7.6.2
Groovy:       4.0.13
JVM:          17.0.8 (Azul Systems, Inc. 17.0.8+7-LTS)
OS:           Mac OS X 12.6.8 aarch64
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

### Compatible Plugins

| Order   |   Plugin Name        |  Plugin Version               |
|---------|----------------------|-------------------------------|
|    1    |  Core                |  2023.0.0-RC1                 |
|    2    |  DataSource          |  2023.0.0-RC1                 |
|    3    |  I18n                |  2023.0.0-RC1                 |
|    4    |  Codecs              |  2023.0.0-RC1                 |
|    5    |  RestResponder       |  2023.0.0-RC1                 |
|    6    |  Controllers         |  2023.0.0-RC1                 |
|    7    |  Converters          |  2023.0.0-RC1                 |
|    8    |  UrlMappings         |  2023.0.0-RC1                 |
|    9    |  Interceptors        |  2023.0.0-RC1                 |
|   10    |  DomainClass         |  2023.0.0-RC1                 |
|   11    |  DynamicModules      |  2023.0.0-RC1                 |
|   12    |  Services            |  2023.0.0-RC1                 |
|   13    |  GroovyPages         |  2023.0.0-RC1                 |
|   14    |  Hibernate           |  2023.0.0-RC1                 |
|   15    |  AssetPipeline       |  6.0.0-M1                     |
|   16    |  ControllersAsync    |  6.0.0-RC1                    |
|   17    |  EventBus            |  6.0.0-RC1                    |
|   18    |  Cache               |  6.0.0-RC1                    |
|   19    |  Fields              |  6.0.0-RC1                    |
|   20    |  Geb                 |  6.0.0-RC1                    |
|   21    |  Scaffolding         |  6.0.0-RC1                    |


### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-08-20 13:12:36.777  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.1.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::                   (v2023.0.0-RC1)

2023-08-20 13:12:36.841  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.8 with PID 89796 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-08-20 13:12:36.841 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.9, Spring v6.0.11
2023-08-20 13:12:36.841  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-08-20 13:12:36.867  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-08-20 13:12:36.867  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-08-20 13:12:37.403  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 21 plugins loaded successfully, take in 110 ms
2023-08-20 13:12:38.168  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-08-20 13:12:38.172  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-08-20 13:12:38.173  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-08-20 13:12:38.173  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.11]
2023-08-20 13:12:38.198  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-08-20 13:12:38.199  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1332 ms
2023-08-20 13:12:38.361  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-08-20 13:12:38.649  INFO --- [  restartedMain] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 5.6.15.Final
2023-08-20 13:12:38.780  INFO --- [  restartedMain] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.2.Final}
2023-08-20 13:12:38.829  INFO --- [  restartedMain] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2023-08-20 13:12:39.271  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-08-20 13:12:39.567  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-08-20 13:12:39.781  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-08-20 13:12:39.787  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-08-20 13:12:39.787  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-08-20 13:12:39.788  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 1 ms
2023-08-20 13:12:39.788  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-08-20 13:12:39.875  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 3.249 seconds (process running for 3.714)
2023-08-20 13:12:39.878  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
----------------------------------------------------------------------------------------------
Order      Plugin Name                              Plugin Version                     Enabled
----------------------------------------------------------------------------------------------
    1      Core                                     2023.0.0-RC1                             Y
    2      DataSource                               2023.0.0-RC1                             Y
    3      I18n                                     2023.0.0-RC1                             Y
    4      Codecs                                   2023.0.0-RC1                             Y
    5      RestResponder                            2023.0.0-RC1                             Y
    6      Controllers                              2023.0.0-RC1                             Y
    7      Converters                               2023.0.0-RC1                             Y
    8      UrlMappings                              2023.0.0-RC1                             Y
    9      Interceptors                             2023.0.0-RC1                             Y
   10      DomainClass                              2023.0.0-RC1                             Y
   11      GroovyPages                              2023.0.0-RC1                             Y
   12      DynamicModules                           2023.0.0-RC1                             Y
   13      Fields                                   6.0.0-RC1                                Y
   14      EventBus                                 6.0.0-RC1                                Y
   15      Geb                                      6.0.0-RC1                                Y
   16      Hibernate                                2023.0.0-RC1                             Y
   17      Scaffolding                              6.0.0-RC1                                Y
   18      ControllersAsync                         6.0.0-RC1                                Y
   19      AssetPipeline                            6.0.0-M1                                 Y
   20      Services                                 2023.0.0-RC1                             Y
   21      Cache                                    6.0.0-RC1                                Y
----------------------------------------------------------------------------------------------

2023-08-20 13:12:39.905  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.128:8080
----------------------------------------------------------------------------------------------
```
