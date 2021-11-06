# Network-
Network 


개인 공부 저장




gRPC란?
gRPC는 어디에서나 실행할 수 있는 현대적인 오픈소스 원격 프로시저 호출(RPC) 프레임워크다. 

클라이언트와 서버 응용프로그램이 투명하게 통신할 수 있도록 하고, 연결된 시스템을 쉽게 구축할 수 있도록 한다.

전송을 위해 HTTP/2를, 인터페이스 정의 언어로 프로토콜 버퍼를 사용하며 인증, 양방향 스트리밍 및 흐름 제어, 차단 및 비차단 바인딩, 취소 및 타임아웃 등의 기능을 제공한다.




주요 사용 시나리오:

-짧은 지연 시간, 확장성이 뛰어난 분산형 시스템.

-클라우드 서버와 통신하는 모바일 클라이언트 개발

-정확하고 효율적이며 언어에 독립적일 필요가 있는 새로운 프로토콜을 설계한다.

-인증, 로드 밸런싱, 로깅 및 모니터링 등과 같은 확장을 지원하는 계층형 설계



사용하는 기업:

-Dropbox

-Netflix



github 주소:https://github.com/grpc/


.NET Core 3.0에 포함되는 grpc 기능

-Grpc.AspNetCore – An ASP.NET Core framework for hosting gRPC services. gRPC on ASP.NET Core integrates with standard ASP.NET Core features like logging, dependency injection (DI), authentication and authorization.

-HttpClient. The client uses new HTTP/2 functionality in .NET Core.

-HttpClientFactory. The client factory allows gRPC clients to be centrally configured and injected into your app with DI.
