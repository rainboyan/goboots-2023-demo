# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.0`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.0-SNAPSHOT
------------------------------------------------------------

Build time:   2023-04-06 03:31:44 UTC
Revision:     a5b276a57f8554edaf106205a334bae5c000825a

Spring Boot:  3.0.5
Gradle:       7.6.1
Groovy:       4.0.10
JVM:          17.0.6 (Azul Systems, Inc. 17.0.6+10-LTS)
OS:           Mac OS X 12.6.4 aarch64
```

### Compatible Plugins

| Order   |   Plugin Name        |  Plugin Version               |
|---------|----------------------|-------------------------------|
|    1    |  Core                |  2023.0.0-SNAPSHOT            |
|    2    |  DataSource          |  2023.0.0-SNAPSHOT            |
|    3    |  I18n                |  2023.0.0-SNAPSHOT            |
|    4    |  Codecs              |  2023.0.0-SNAPSHOT            |
|    5    |  RestResponder       |  2023.0.0-SNAPSHOT            |
|    6    |  Controllers         |  2023.0.0-SNAPSHOT            |
|    7    |  Converters          |  2023.0.0-SNAPSHOT            |
|    8    |  UrlMappings         |  2023.0.0-SNAPSHOT            |
|    9    |  Interceptors        |  2023.0.0-SNAPSHOT            |
|   10    |  DomainClass         |  2023.0.0-SNAPSHOT            |
|   11    |  DynamicModules      |  2023.0.0-SNAPSHOT            |
|   12    |  Services            |  2023.0.0-SNAPSHOT            |
|   13    |  GroovyPages         |  2023.0.0-SNAPSHOT            |
|   14    |  ControllersAsync    |  6.0.0-SNAPSHOT               |
|   15    |  EventBus            |  6.0.0-SNAPSHOT               |
|   16    |  Cache               |  6.0.0-SNAPSHOT               |
|   17    |  Fields              |  6.0.0-SNAPSHOT               |
|   18    |  Scaffolding         |  6.0.0-SNAPSHOT               |


### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-04-06 11:37:24.276  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.0.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::             (v2023.0.0-SNAPSHOT)

2023-04-06 11:37:24.337  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.6 with PID 74084 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-04-06 11:37:24.337 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.5, Spring v6.0.7
2023-04-06 11:37:24.338  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-04-06 11:37:24.360  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-04-06 11:37:24.360  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-04-06 11:37:24.844  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 18 plugins loaded successfully, take in 83 ms
2023-04-06 11:37:25.696  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-04-06 11:37:25.701  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-04-06 11:37:25.701  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-04-06 11:37:25.701  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.7]
2023-04-06 11:37:25.729  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-04-06 11:37:25.729  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1368 ms
2023-04-06 11:37:25.765  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-04-06 11:37:26.217  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-04-06 11:37:26.219  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-04-06 11:37:26.397  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-04-06 11:37:26.404  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-04-06 11:37:26.404  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-04-06 11:37:26.405  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 1 ms
2023-04-06 11:37:26.405  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-04-06 11:37:26.436  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 2.311 seconds (process running for 2.773)
2023-04-06 11:37:26.440  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
----------------------------------------------------------------------------------------------
Order      Plugin Name                              Plugin Version                     Enabled
----------------------------------------------------------------------------------------------
    1      Core                                     2023.0.0-SNAPSHOT                        Y
    2      DataSource                               2023.0.0-SNAPSHOT                        Y
    3      I18n                                     2023.0.0-SNAPSHOT                        Y
    4      Codecs                                   2023.0.0-SNAPSHOT                        Y
    5      RestResponder                            2023.0.0-SNAPSHOT                        Y
    6      Controllers                              2023.0.0-SNAPSHOT                        Y
    7      Converters                               2023.0.0-SNAPSHOT                        Y
    8      UrlMappings                              2023.0.0-SNAPSHOT                        Y
    9      Interceptors                             2023.0.0-SNAPSHOT                        Y
   10      DomainClass                              2023.0.0-SNAPSHOT                        Y
   11      DynamicModules                           2023.0.0-SNAPSHOT                        Y
   12      EventBus                                 6.0.0-SNAPSHOT                           Y
   13      ControllersAsync                         6.0.0-SNAPSHOT                           Y
   14      Fields                                   6.0.0-SNAPSHOT                           Y
   15      Services                                 2023.0.0-SNAPSHOT                        Y
   16      GroovyPages                              2023.0.0-SNAPSHOT                        Y
   17      Scaffolding                              6.0.0-SNAPSHOT                           Y
   18      Cache                                    6.0.0-SNAPSHOT                           Y
----------------------------------------------------------------------------------------------

2023-04-06 11:37:26.444 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Application directory discovered as: /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo
2023-04-06 11:37:26.444 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Current base directory is [.]. Reloading base directory is [/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo]
2023-04-06 11:37:26.444 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Reloading status: true
2023-04-06 11:37:27.039  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.127:8080
----------------------------------------------------------------------------------------------
```
