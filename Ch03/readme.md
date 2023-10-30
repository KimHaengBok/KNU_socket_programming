배운 것 : 호스트에서는 리틀 엔디언, 네트워크에서는 빅 엔디언을 사용함

1. 호스트에서 네트워크 바이트 => 리틀 엔디언 -> 빅 엔디언; hton
2. 네트워크에서 호스트 바이트 => 빅 엔디언 -> 리틀 엔디언; ntoh
3. s 는 16비트 값, l은 32비트 값을 입력을 받는다
4. htons, htonl, ntohs, ntohl


배운 것 : ip 주소 변환 함수에 대해 배웠다.
1. inet_pton() : 문자열 -> 숫자(네트워크 바이트 정렬)
2. inet_ntop() : 숫자(네트워크 바이트 정렬) -> 문자열
3. inet_addr() : 문자열 -> 숫자(네트워크 바이트 정렬); IPv4만 지원
4. inet_ntoa() : 숫자(네트워크 바이트 정렬) -> 문자열; IPv4만 지원


배운 것 : 도메인 이름->IPv4, IPv4/IPv6->도메인 이름으로 주소 변환 함수에 대해 배웠다.
1. gethostbyname():도메인 이름->IPv4주소(네트워크 바이트 정렬)
2. gethostbyaddr():IPv4(네트워크 바이트 정렬)->도메인 이름
3. getaddrinfo() / freeaddrinfo():도메인 이름->IPv4/IPv6주소(네트워크 바이트 정렬
4. getnameinfo():IPv4/IPv6(네트워크 바이트 정렬) -> 도메인 이름