배운 것 : TCP서버의 윈속 초기화와 소켓 생성, 소켓 닫기, 윈속 종료를 배웠다.

1. WSAStartup(MAKEWORD(2,2), &wsa )!= 0 -> 2.2 버전의 윈속을 말하는 것
2. AF_INET = IPv4
3. SOCK_STREAM = TCP 통신