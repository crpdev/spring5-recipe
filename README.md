# spring5-recipe
Spring Framework 5 - Recipe Project

# Web Development with Spring MVC

`May 04, 2020`

#Take-aways

    - Introduction to Thymeleaf
    - HTTP Protocol
    - HTTP Request Methods
        - GET
        - HEAD [Metadata]
        - POST [CREATE]
        - PUT [CREATE or UPDATE]
        - DELETE
        - TRACE [ECHO THE REQUEST RECEIVED BY THE SERVER]
        - OPTIONS [RETURS METHODS SUPPORTED BY SERVER]
        - CONNECT [TCP Tunnel]
        - PATCH [Partial modification to the resource]
        - Safe Methods: Get, Head, Options and Trace - makes no changes to the resource
        - Idempotence: Repetitive actions on the resource makes no impact: Put and Delete
        - Safe Methods are also Idempotent
        - Post is not Idempotent, as it creates new resources
        - HTTP Status Codes
            - 100: Informational
            - 200: Success
            - 300: Redirects
            - 400: Client Errors
            - 500: Server Errors
            
`May 05, 2020`

        - Chrome Developer Tools
        - Firefox Firebug
        - Firefox Developer Edition
        - Safari Web Inspector
        - Axis TCP Monitor Plugin
        - Spring Boot Developer Tools
            - Automatic restart upon changes in Spring Context
            - Uses 2 classloaders: Application & Dependencies
            - Fast, because only application classes are refreshed
            - Templates are cached
            - Includes LiveReload server
            - Overriding IntelliJ config to auto-make and run via Registry
        
            
