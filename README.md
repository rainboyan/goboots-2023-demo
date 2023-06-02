# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.0`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.0-M7
------------------------------------------------------------

Build time:   2023-06-02 14:55:58 UTC
Revision:     855d87c5dc1f3d14ff93fcc968e5965c89b739b2

Spring Boot:  3.0.7
Gradle:       7.6.1
Groovy:       4.0.12
JVM:          17.0.6 (Azul Systems, Inc. 17.0.6+10-LTS)
OS:           Mac OS X 12.6.6 aarch64
```

### Compatible Plugins

| Order   |   Plugin Name        |  Plugin Version               |
|---------|----------------------|-------------------------------|
|    1    |  Core                |  2023.0.0-M7                  |
|    2    |  DataSource          |  2023.0.0-M7                  |
|    3    |  I18n                |  2023.0.0-M7                  |
|    4    |  Codecs              |  2023.0.0-M7                  |
|    5    |  RestResponder       |  2023.0.0-M7                  |
|    6    |  Controllers         |  2023.0.0-M7                  |
|    7    |  Converters          |  2023.0.0-M7                  |
|    8    |  UrlMappings         |  2023.0.0-M7                  |
|    9    |  Interceptors        |  2023.0.0-M7                  |
|   10    |  DomainClass         |  2023.0.0-M7                  |
|   11    |  DynamicModules      |  2023.0.0-M7                  |
|   12    |  Services            |  2023.0.0-M7                  |
|   13    |  GroovyPages         |  2023.0.0-M7                  |
|   14    |  Hibernate           |  2023.0.0-M4                  |
|   15    |  AssetPipeline       |  6.0.0-M1                     |
|   16    |  ControllersAsync    |  6.0.0-M4                     |
|   17    |  EventBus            |  6.0.0-M4                     |
|   18    |  Cache               |  6.0.0-M4                     |
|   19    |  Fields              |  6.0.0-M4                     |
|   20    |  Scaffolding         |  6.0.0-M4                     |


### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-06-02 23:05:26.619  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.0.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::                   (v2023.0.0-M7)

2023-06-02 23:05:26.690  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.6 with PID 67111 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-06-02 23:05:26.690 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.7, Spring v6.0.9
2023-06-02 23:05:26.690  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-06-02 23:05:26.713  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-06-02 23:05:26.715  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-06-02 23:05:27.234  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 20 plugins loaded successfully, take in 91 ms
2023-06-02 23:05:28.018  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-06-02 23:05:28.023  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-06-02 23:05:28.023  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-06-02 23:05:28.023  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.8]
2023-06-02 23:05:28.050  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-06-02 23:05:28.050  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1335 ms
2023-06-02 23:05:28.239  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-06-02 23:05:28.523  INFO --- [  restartedMain] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 5.6.15.Final
2023-06-02 23:05:28.663  INFO --- [  restartedMain] o.hibernate.annotations.common.Version   : HCANN000001: Hibernate Commons Annotations {5.1.2.Final}
2023-06-02 23:05:28.720  INFO --- [  restartedMain] org.hibernate.dialect.Dialect            : HHH000400: Using dialect: org.hibernate.dialect.H2Dialect
2023-06-02 23:05:29.098  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-06-02 23:05:29.410  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-06-02 23:05:29.602  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-06-02 23:05:29.608  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-06-02 23:05:29.608  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-06-02 23:05:29.609  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 1 ms
2023-06-02 23:05:29.610  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-06-02 23:05:29.724  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 3.264 seconds (process running for 3.745)
2023-06-02 23:05:29.724 DEBUG --- [  restartedMain] ntModeWatchApplicationContextInitializer : Application reloading status: true, base directory is [/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo]
2023-06-02 23:05:30.024  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
----------------------------------------------------------------------------------------------
Order      Plugin Name                              Plugin Version                     Enabled
----------------------------------------------------------------------------------------------
    1      Core                                     2023.0.0-M7                              Y
    2      DataSource                               2023.0.0-M7                              Y
    3      I18n                                     2023.0.0-M7                              Y
    4      Codecs                                   2023.0.0-M7                              Y
    5      RestResponder                            2023.0.0-M7                              Y
    6      Controllers                              2023.0.0-M7                              Y
    7      Converters                               2023.0.0-M7                              Y
    8      UrlMappings                              2023.0.0-M7                              Y
    9      Interceptors                             2023.0.0-M7                              Y
   10      DomainClass                              2023.0.0-M7                              Y
   11      GroovyPages                              2023.0.0-M7                              Y
   12      AssetPipeline                            6.0.0-M1                                 Y
   13      Fields                                   6.0.0-M4                                 Y
   14      DynamicModules                           2023.0.0-M7                              Y
   15      Scaffolding                              6.0.0-M4                                 Y
   16      ControllersAsync                         6.0.0-M4                                 Y
   17      EventBus                                 6.0.0-M4                                 Y
   18      Hibernate                                2023.0.0-M4                              Y
   19      Services                                 2023.0.0-M7                              Y
   20      Cache                                    6.0.0-M4                                 Y
----------------------------------------------------------------------------------------------

2023-06-02 23:05:30.032  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.128:8080
----------------------------------------------------------------------------------------------
```
