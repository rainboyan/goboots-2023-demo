# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.0`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.0-M6
------------------------------------------------------------

Build time:   2023-05-20 10:34:11 UTC
Revision:     f0a5a58744aa42adeb57c9ba387c0ffef6c21c09

Spring Boot:  3.0.6
Gradle:       7.6.1
Groovy:       4.0.11
JVM:          17.0.6 (Azul Systems, Inc. 17.0.6+10-LTS)
OS:           Mac OS X 12.6.5 aarch64
```

### Compatible Plugins

| Order   |   Plugin Name        |  Plugin Version               |
|---------|----------------------|-------------------------------|
|    1    |  Core                |  2023.0.0-M6                  |
|    2    |  DataSource          |  2023.0.0-M6                  |
|    3    |  I18n                |  2023.0.0-M6                  |
|    4    |  Codecs              |  2023.0.0-M6                  |
|    5    |  RestResponder       |  2023.0.0-M6                  |
|    6    |  Controllers         |  2023.0.0-M6                  |
|    7    |  Converters          |  2023.0.0-M6                  |
|    8    |  UrlMappings         |  2023.0.0-M6                  |
|    9    |  Interceptors        |  2023.0.0-M6                  |
|   10    |  DomainClass         |  2023.0.0-M6                  |
|   11    |  DynamicModules      |  2023.0.0-M6                  |
|   12    |  Services            |  2023.0.0-M6                  |
|   13    |  GroovyPages         |  2023.0.0-M6                  |
|   14    |  Hibernate           |  2023.0.0-M3                  |
|   15    |  ControllersAsync    |  6.0.0-M3                     |
|   16    |  EventBus            |  6.0.0-M3                     |
|   17    |  Cache               |  6.0.0-M3                     |
|   18    |  Fields              |  6.0.0-M3                     |
|   19    |  Scaffolding         |  6.0.0-M3                     |


### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-05-20 18:41:17.853  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.0.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::                   (v2023.0.0-M6)

2023-05-20 18:41:17.919  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.6 with PID 94587 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-05-20 18:41:17.919 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.6, Spring v6.0.8
2023-05-20 18:41:17.919  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-05-20 18:41:17.941  INFO --- [  restartedMain] o.s.b.devtools.restart.ChangeableUrls    : The Class-Path manifest attribute in /Users/rain/.gradle/caches/modules-2/files-2.1/com.sun.xml.bind/jaxb-impl/4.0.2/20050c9054eb0e6cf8568c2ca83739d71df731d4/jaxb-impl-4.0.2.jar referenced one or more files that do not exist: file:/Users/rain/.gradle/caches/modules-2/files-2.1/com.sun.xml.bind/jaxb-impl/4.0.2/20050c9054eb0e6cf8568c2ca83739d71df731d4/jaxb-core.jar,file:/Users/rain/.gradle/caches/modules-2/files-2.1/com.sun.xml.bind/jaxb-impl/4.0.2/20050c9054eb0e6cf8568c2ca83739d71df731d4/angus-activation.jar
2023-05-20 18:41:17.941  INFO --- [  restartedMain] o.s.b.devtools.restart.ChangeableUrls    : The Class-Path manifest attribute in /Users/rain/.gradle/caches/modules-2/files-2.1/com.sun.xml.bind/jaxb-core/4.0.2/b93945e547a8b0d6ab34d0c93e30255b8bda9fc0/jaxb-core-4.0.2.jar referenced one or more files that do not exist: file:/Users/rain/.gradle/caches/modules-2/files-2.1/com.sun.xml.bind/jaxb-core/4.0.2/b93945e547a8b0d6ab34d0c93e30255b8bda9fc0/jakarta.activation-api.jar,file:/Users/rain/.gradle/caches/modules-2/files-2.1/com.sun.xml.bind/jaxb-core/4.0.2/b93945e547a8b0d6ab34d0c93e30255b8bda9fc0/jakarta.xml.bind-api.jar
2023-05-20 18:41:17.941  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-05-20 18:41:17.941  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-05-20 18:41:18.448  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 19 plugins loaded successfully, take in 83 ms
2023-05-20 18:41:19.161  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-05-20 18:41:19.167  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-05-20 18:41:19.167  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-05-20 18:41:19.167  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.8]
2023-05-20 18:41:19.193  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-05-20 18:41:19.194  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1252 ms
2023-05-20 18:41:19.375  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-05-20 18:41:19.674  INFO --- [  restartedMain] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 5.6.15.Final
2023-05-20 18:41:19.815  INFO --- [  restartedMain] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.2.Final}
2023-05-20 18:41:19.873  INFO --- [  restartedMain] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2023-05-20 18:41:20.250  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-05-20 18:41:20.416  WARN --- [  restartedMain] ocalVariableTableParameterNameDiscoverer : Using deprecated '-debug' fallback for parameter name resolution. Compile the affected code with '-parameters' instead or avoid its introspection: org.grails.scaffolding.model.DomainModelServiceImpl
2023-05-20 18:41:20.551  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-05-20 18:41:20.731  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-05-20 18:41:20.737  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-05-20 18:41:20.737  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-05-20 18:41:20.738  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 0 ms
2023-05-20 18:41:20.739  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-05-20 18:41:20.801  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 3.103 seconds (process running for 3.575)
2023-05-20 18:41:20.802 DEBUG --- [  restartedMain] ntModeWatchApplicationContextInitializer : Application reloading status: true, base directory is [/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo]
2023-05-20 18:41:21.142  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
----------------------------------------------------------------------------------------------
Order      Plugin Name                              Plugin Version                     Enabled
----------------------------------------------------------------------------------------------
    1      Core                                     2023.0.0-M6                              Y
    2      DataSource                               2023.0.0-M6                              Y
    3      I18n                                     2023.0.0-M6                              Y
    4      Codecs                                   2023.0.0-M6                              Y
    5      RestResponder                            2023.0.0-M6                              Y
    6      Controllers                              2023.0.0-M6                              Y
    7      Converters                               2023.0.0-M6                              Y
    8      UrlMappings                              2023.0.0-M6                              Y
    9      Interceptors                             2023.0.0-M6                              Y
   10      DomainClass                              2023.0.0-M6                              Y
   11      GroovyPages                              2023.0.0-M6                              Y
   12      DynamicModules                           2023.0.0-M6                              Y
   13      Hibernate                                2023.0.0-M3                              Y
   14      ControllersAsync                         6.0.0-M3                                 Y
   15      Fields                                   6.0.0-M3                                 Y
   16      Scaffolding                              6.0.0-M3                                 Y
   17      EventBus                                 6.0.0-M3                                 Y
   18      Services                                 2023.0.0-M6                              Y
   19      Cache                                    6.0.0-M3                                 Y
----------------------------------------------------------------------------------------------

2023-05-20 18:41:21.153  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.128:8080
----------------------------------------------------------------------------------------------
```
