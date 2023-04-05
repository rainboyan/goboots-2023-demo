# GoBoots 2023

This is a GoBoots demo app, build with [GoBoots](https://github.com/rainboyan/GoBoots) `2023.0.0`.

### GoBoots Version

```bash
➜  ~ goboots -v

------------------------------------------------------------
GoBoots 2023.0.0-SNAPSHOT
------------------------------------------------------------

Build time:   2023-04-04 16:21:35 UTC
Revision:     6ad30bf0025b005664ffcb2e6c8658a6565cec2a

Spring Boot:  3.0.5
Gradle:       7.6.1
Groovy:       4.0.10
JVM:          17.0.6 (Azul Systems, Inc. 17.0.6+10-LTS)
OS:           Mac OS X 12.6.4 aarch64
```

### Running App

```bash
➜  goboots-2023-demo git:(main) ✗ ./gradlew bR

> Task :bootRun
2023-04-05 23:21:36.306  INFO --- [kground-preinit] o.h.validator.internal.util.Version      : HV000001: Hibernate Validator 8.0.0.Final
          _____       ____              _
   _     / ____|     |  _ \            | |
  (o)   | |  __  ___ | |_) | ___   ___ | |_ ___
 //^\\  | | |_ |/ _ \|  _ < / _ \ / _ \| __/ __|
(> - <) | |__| | (_) | |_) | (_) | (_) | |_\__ \
\=====/  \_____|\___/|____/ \___/ \___/ \__|___/
 ______________________________________________
 :: GoBoots ::             (v2023.0.0-SNAPSHOT)

2023-04-05 23:21:36.375  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Starting Application using Java 17.0.6 with PID 70026 (/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo/build/classes/groovy/main started by rain in /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo)
2023-04-05 23:21:36.375 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Running with Spring Boot v3.0.5, Spring v6.0.7
2023-04-05 23:21:36.375  INFO --- [  restartedMain] org.rainboyan.demo.Application           : The following 1 profile is active: "development"
2023-04-05 23:21:36.400  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : Devtools property defaults active! Set 'spring.devtools.add-properties' to 'false' to disable
2023-04-05 23:21:36.400  INFO --- [  restartedMain] .e.DevToolsPropertyDefaultsPostProcessor : For additional web related logging consider setting the 'logging.level.web' property to 'DEBUG'
2023-04-05 23:21:36.898  INFO --- [  restartedMain] g.plugins.DefaultGrailsPluginManager     : Total 17 plugins loaded successfully, take in 80 ms
2023-04-05 23:21:37.739  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2023-04-05 23:21:37.744  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Initializing ProtocolHandler ["http-nio-8080"]
2023-04-05 23:21:37.744  INFO --- [  restartedMain] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2023-04-05 23:21:37.744  INFO --- [  restartedMain] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.7]
2023-04-05 23:21:37.772  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2023-04-05 23:21:37.773  INFO --- [  restartedMain] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1372 ms
2023-04-05 23:21:37.807  INFO --- [  restartedMain] o.s.b.a.h2.H2ConsoleAutoConfiguration    : H2 console available at '/h2-console'. Database available at 'jdbc:h2:mem:devDb'
2023-04-05 23:21:38.268  INFO --- [  restartedMain] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2023-04-05 23:21:38.270  INFO --- [  restartedMain] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 15 endpoint(s) beneath base path '/actuator'
2023-04-05 23:21:38.433  INFO --- [  restartedMain] o.a.coyote.http11.Http11NioProtocol      : Starting ProtocolHandler ["http-nio-8080"]
2023-04-05 23:21:38.440  INFO --- [  restartedMain] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring GrailsDispatcherServlet 'dispatcherServlet'
2023-04-05 23:21:38.440  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Initializing Servlet 'dispatcherServlet'
2023-04-05 23:21:38.441  INFO --- [  restartedMain] o.g.w.s.mvc.GrailsDispatcherServlet      : Completed initialization in 1 ms
2023-04-05 23:21:38.441  INFO --- [  restartedMain] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2023-04-05 23:21:38.494  INFO --- [  restartedMain] org.rainboyan.demo.Application           : Started Application in 2.348 seconds (process running for 2.815)
2023-04-05 23:21:38.498  INFO --- [  restartedMain] PluginsInfoApplicationContextInitializer :
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
   11      ControllersAsync                         6.0.0-SNAPSHOT                           Y
   12      EventBus                                 6.0.0-SNAPSHOT                           Y
   13      DynamicModules                           2023.0.0-SNAPSHOT                        Y
   14      Services                                 2023.0.0-SNAPSHOT                        Y
   15      Cache                                    2023.0.0-SNAPSHOT                        Y
   16      GroovyPages                              2023.0.0-SNAPSHOT                        Y
   17      Scaffolding                              5.0.0-SNAPSHOT                           Y
----------------------------------------------------------------------------------------------

2023-04-05 23:21:38.501 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Application directory discovered as: /Users/rain/Development/github/grails/grails-demos/goboots-2023-demo
2023-04-05 23:21:38.501 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Current base directory is [.]. Reloading base directory is [/Users/rain/Development/github/grails/grails-demos/goboots-2023-demo]
2023-04-05 23:21:38.501 DEBUG --- [  restartedMain] org.rainboyan.demo.Application           : Reloading status: true
2023-04-05 23:21:39.021  INFO --- [  restartedMain] org.rainboyan.demo.Application           :
----------------------------------------------------------------------------------------------
        Application:   goboots-2023-demo
        Version:       0.1
        Environment:   development
        Local:         http://localhost:8080
        External:      http://192.168.31.127:8080
----------------------------------------------------------------------------------------------
```
