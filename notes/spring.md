# Spring Framework

User -> (Request) Server
User <- (Response) Server

### Client Server Architecture

    Client -> (HTTP/HTTPS Request)  -> Server
    Client <- (HTTP/HTTPS Request)  <- Server
    Client(is Mobile app, React, Android/Ios, postman, server)

    HTTP(Hyper Text Transfer Protocol)
    -> Request Structure?
    -> Response Structure?
    -> GET, POST, DELETE, PUT, PATCH
    -> How data will be sent?

    Request:
    -> Method Name (Get,POST,..)
    -> URL/Path (www.amazon.in)
    -> Headers : (accept : application/json)
    -> Body ({} )
    Response :
    -> Status code(200 ok, 201, 503, ....)
    -> Hraders (ContenType : application/json)
    -> Body {
        message: "Login Successfull"
        }
    
## Java Compilation Process

    ```mermaid
    flowchart LR
        A[Main.java] -->|javac| B[Main.class<br/>Bytecode]
        B -->|JVM| C[Program Execution]
    ```
