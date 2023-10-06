# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.3`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.3
------------------------------------------------------------

Build time:   2023-09-26 18:22:46 UTC
Revision:     d698ad91b6aa99213a99e78e88df2717970cdfc2

Spring Boot:  3.0.11
Gradle:       7.6.2
Groovy:       4.0.15
JVM:          17.0.8 (Azul Systems, Inc. 17.0.8+7-LTS)
OS:           Mac OS X 12.6.9 aarch64
```

### App Environment

```bash
➜  goboots-2023-demo git:(main) ✗ goboots about
| About your application's environment

Name:               goboots-2023-demo
Version:            0.1
Plugins:            [core:2023.0.3], [dataSource:2023.0.3], [i18n:2023.0.3], [codecs:2023.0.3], [restResponder:2023.0.3], [controllers:2023.0.3], [converters:2023.0.3], [urlMappings:2023.0.3], [interceptors:2023.0.3], [domainClass:2023.0.3], [services:2023.0.3], [groovyPages:2023.0.3], [hibernate:2023.0.3], [fields:6.0.3], [cache:6.0.3], [dynamicModules:2023.0.3], [scaffolding:6.0.3], [assetPipeline:6.0.3], [geb:6.0.3], [controllersAsync:6.0.3], [databaseMigration:4.2.0], [eventBus:6.0.3]
Application root:   /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo
Environment:        development

Grails:             2023.0.3
Groovy:             4.0.15
Gradle:             8.4
Spring Boot:        3.0.11
JVM:                17.0.8 (Azul Systems, Inc. 17.0.8+7-LTS)
OS:                 Mac OS X 12.6.9 aarch64
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
|    1    |  Core                |  2023.0.3                     |
|    2    |  DataSource          |  2023.0.3                     |
|    3    |  I18n                |  2023.0.3                     |
|    4    |  Codecs              |  2023.0.3                     |
|    5    |  RestResponder       |  2023.0.3                     |
|    6    |  Controllers         |  2023.0.3                     |
|    7    |  Converters          |  2023.0.3                     |
|    8    |  UrlMappings         |  2023.0.3                     |
|    9    |  Interceptors        |  2023.0.3                     |
|   10    |  DomainClass         |  2023.0.3                     |
|   11    |  DynamicModules      |  2023.0.3                     |
|   12    |  Services            |  2023.0.3                     |
|   13    |  GroovyPages         |  2023.0.3                     |
|   14    |  Hibernate           |  2023.0.3                     |
|   15    |  AssetPipeline       |  6.0.3                        |
|   16    |  ControllersAsync    |  6.0.3                        |
|   17    |  EventBus            |  6.0.3                        |
|   18    |  Cache               |  6.0.3                        |
|   19    |  Fields              |  6.0.3                        |
|   20    |  Geb                 |  6.0.3                        |
|   21    |  Scaffolding         |  6.0.3                        |
|   22    |  DatabaseMigration   |  4.2.0                        |


### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-10-06 17:34:03.278  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.1.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::                      (v2023.0.3)

2023-10-06 17:34:03.340  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.8 with PID 52406 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-10-06 17:34:03.341 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.11, Spring v6.0.12
2023-10-06 17:34:03.341  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-10-06 17:34:03.367  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-10-06 17:34:03.367  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-10-06 17:34:03.869  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 22 plugins loaded successfully, take in 112 ms
2023-10-06 17:34:04.610  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-10-06 17:34:04.613  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-10-06 17:34:04.614  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-10-06 17:34:04.614  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.13]
2023-10-06 17:34:04.639  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-10-06 17:34:04.639  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1272 ms
2023-10-06 17:34:04.796  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-10-06 17:34:05.101  INFO --- [  restartedMain] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 5.6.15.Final
2023-10-06 17:34:05.201  INFO --- [  restartedMain] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.2.Final}
2023-10-06 17:34:05.248  INFO --- [  restartedMain] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2023-10-06 17:34:05.678  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-10-06 17:34:05.974  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-10-06 17:34:06.200  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-10-06 17:34:06.206  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-10-06 17:34:06.206  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-10-06 17:34:06.207  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 1 ms
2023-10-06 17:34:06.207  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-10-06 17:34:06.297  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 3.158 seconds (process running for 3.56)
2023-10-06 17:34:06.300  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
----------------------------------------------------------------------------------------------
Order      Plugin Name                              Plugin Version                     Enabled
----------------------------------------------------------------------------------------------
    1      Core                                     2023.0.3                                 Y
    2      DataSource                               2023.0.3                                 Y
    3      I18n                                     2023.0.3                                 Y
    4      Codecs                                   2023.0.3                                 Y
    5      RestResponder                            2023.0.3                                 Y
    6      Controllers                              2023.0.3                                 Y
    7      Converters                               2023.0.3                                 Y
    8      UrlMappings                              2023.0.3                                 Y
    9      Interceptors                             2023.0.3                                 Y
   10      DomainClass                              2023.0.3                                 Y
   11      GroovyPages                              2023.0.3                                 Y
   12      DynamicModules                           2023.0.3                                 Y
   13      Fields                                   6.0.3                                    Y
   14      ControllersAsync                         6.0.3                                    Y
   15      Hibernate                                2023.0.3                                 Y
   16      Scaffolding                              6.0.3                                    Y
   17      DatabaseMigration                        4.2.0                                    Y
   18      AssetPipeline                            6.0.3                                    Y
   19      Geb                                      6.0.3                                    Y
   20      EventBus                                 6.0.3                                    Y
   21      Services                                 2023.0.3                                 Y
   22      Cache                                    6.0.3                                    Y
----------------------------------------------------------------------------------------------

2023-10-06 17:34:06.397  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.127:8080
----------------------------------------------------------------------------------------------
```

### Links

* [GoBoots 2022 Demo](https://github.com/rainboyan/goboots-2022-demo)
* [GoBoots 2023 Demo](https://github.com/rainboyan/goboots-2023-demo)
* [GoBoots 2024 Demo](https://github.com/rainboyan/goboots-2024-demo)
