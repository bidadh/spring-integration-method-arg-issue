This repo is created to show how to reproduce an issue with **Spring Integration** version **6.0**  which results in
```Caused by: java.lang.ClassCastException: class org.springframework.messaging.handler.HandlerMethod$HandlerMethodParameter cannot be cast to class java.lang.reflect.Type (org.springframework.messaging.handler.HandlerMethod$HandlerMethodParameter is in unnamed module of loader 'app'; java.lang.reflect.Type is in module java.base of loader 'bootstrap')```
in some scenarios
