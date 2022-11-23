Logging framework helps in:
- configurable (includes where, what and how to go)
- log levels
- log destination
- ...much more

`LoggerFactory` is default out of the box method, which returns object of `Logger` class, which has different kind of logging methods like info, error, warn, trace etc.

spring-boot-starter-web -> spring-boot-starter-logging -> spring-jcl (Spring Commons Logging Bridge)

Logback framework is default framework under the hood to implement logging from logging api.

### Configure log levels
- trace is not shown in console 
- - you can do `logging.level.root = TRACE` to show trace logs in console also
- - `logging.level.io.<package-name> = TRACE` if trace logs to show from specific package only
- logback-spring.xml to add the configuration for project level logs