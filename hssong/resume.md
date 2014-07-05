# 경력

## [알티베이스](http://www.altibase.com/) ( 2009.8 ~ 재직 중 )

Altibase는 HDB라는 Database 제품을 개발하는 회사입니다. HDB는 In-memory Database와 Disk Database를 동시에 제공합니다.

### Altibase ADI(Altibase Data Integrator) 제품 개발 참여

이기종 DB 간에 통합하기 위한 제품으로 DB의 로그 기반 데이터 분석하여 내용을 반영하는 제품이었습니다.

 * 유지 보수 업무
 * 설정 파일 개선 작업 ( C, Bison, Flex )
     * 설정 파일에 사용되는 문법의 한계를 극복하기 위해 새로운 설정 파일 문법으로 개선하였습니다.
 
### Altibase HDB(Hybrid DataBase) 제품 개발 참여

 * Altibase HDB Replication 유지 보수 ( C/C++ )

 * Altibase HDB OraAdapter 개발 ( C )
    * Altibase HDB의 이중화 기능을 이용하여 변경된 내용을 Oracle에 반영하는 제품입니다.
    * 단독으로 진행하였으며, 요구 사항 수집부터 구현까지 진행하였습니다. 이후 테스트, 매뉴얼을 포함하는 제품화는 다른 분이 이어서 진행하였습니다.

 * Altibase HDB Heterogeneous Database Link 개발 참여 ( C/C++, Bison, Flex )
    * JDBC를 이용하여 이기종 DB에 접근 가능하게 하는 기능입니다.
    * 설정 파일 부분 구현
    * 기능은 별도의 독립 부분으로 구현이 진행되었고, 이 부분이 Altibase HDB에 연동될 수 있게 이 모듈의 외부 인터페이스 설계 및 구현
    * 새로 추가되는 SQL 인터페이스 구현
    
 * Altibase HDB Cluster 개발 참여 ( C/C++ )
    * Altibase HDB 사이에 RPC를 제공하기 위한 모듈 개발에 참여하였습니다.
        * RPC를 위한 프로토콜을 설계 및 구현하였습니다.

## 티맥스 코어(현 [S-core](http://www.s-core.co.kr/home.xhtml)) ( 2008.5 ~ 2009.7 )

티맥스 OS라는 제품을 개발하는 티맥스소프트의 자회사였습니다. 티맥스 OS의 커널에 포함되는 USB 스택 쪽 구현을 담당했습니다.

개발 기간 및 지원해야 할 수많은 USB 장치를 고려하여 라이선스 문제가 안 되는 Free BSD의 USB Stack을 티맥스 OS에 이식하였습니다. ( C )

 * UHCI, EHCI Host Controller Driver
 * USB Driver
 * USB Class Driver
    * HUB, HID, Mass Storage

## 에이엘테크 ( 2005.10 ~ 2008.4 )

AnyGate라는 유무선 공유기 제품을 비롯해 MediaGate라는 Divx 플레이어 등을 개발하는 회사였습니다. AnyGate 제품은 Linux 기반의 유무선 공유기였습니다.

AnyGate 제품의 시스템 부분에서 일하였습니다. 

 * Linux Kernel 유지 보수 및 이식 업무 담당 ( C )
    * 새로운 보드가 개발되면 해당 보드에 Linux Kernel 이식
 * ALTech Bootloader 유지 보수 및 이식 업무 담당 ( C, ASM for ARM )
    * 새로운 보드가 개발되면 해당 보드에 맞게 Bootloader 이식하였습니다.
 * AnyGate 제품에 포함된 각종 장치 드라이버 유지 보수 및 개발 업무 담당 ( C )
    * 유선 Network Switch Driver
    * 무선 Lan Card Driver
    * LED 제어 Driver
 * 공장 양산시 사용하는 Windows XP 기반 Test 자동화 소프트웨어 유지 보수 담당 ( C/C++ )

## [엠스톤](http://www.emstone.com) ( 2002.9 ~ 2005.9 )

( 실제 근무는 2002년 9월부터 하였으나, 퇴사할 당시 알게 되었는데 의료보험상에는 11월부터 보험료를 납부한 것으로 나옵니다. )

DVR 제품의 H/W와 S/W을 개발하여 판매하는 회사입니다.

 * DVR Linux Client 개발 참여 ( C, Gtk+, FFMpeg )
    * DVR Server에 접속해서 실시간 영상과 저장된 영상을 볼 수 있는 Linux용 소프트웨어입니다.
 * DVR Server와 Client 사이에 통신을 위한 네트워크 모듈 개발 참여 ( C )
    * 큰 설계와 구현은 연구소장님이 진행하셨고, 이후 유지 보수 및 기능 추가를 담당하였습니다.
 * DynDNS 와 유사한 동적 도메인 서비스 개발 ( Python )
    * 유동 IP를 사용하는 DVR Server에 접근할 수 있게 DynDNS와 유사한 서비스를 제공
    * Python의 Web Server 클래스를 이용하여 웹 포트 및 HTTP 프로토콜을 사용하여 구현하였습니다.
 * 내부 자재 관리 시스템 개발 ( HTML, Javascrip, Apach, PHP, MySQL )
    * 회사 내부에서 사용하는 자재관리 시스템을 개발하였습니다. 부수적인 업무로 진행했던 것이라 기능은 많이 부족했던 것으로 기억합니다.
 
## 두리네트워크 ( 2000.4 ~ 2001.2 )

ISP 업체로서 인터넷 회선 제공 및 호스팅 서비스를 제공하였습니다. 부설 연구소에서는 굿모닝 서버라는 제품 개발에 참여하였습니다. 운영체제를 담뱃갑 크기의 플래시 메모리에 탑재하는 방식의 서버였습니다.

 * 웹 기반 서버 관리 도구 개발 참여 ( PHP, Java, HTML, Javascript )
    * Debian 기반 리눅스가 탑재되는 굿모닝 서버의 웹 기반 서버 관리 도구에서 패키지 관리 부분 담당
        * Java Applet으로 패키지 설치, 삭제, 업데이트시 터미널과 유사한 환경 제공

# 개인 웹사이트

집에 오래된 노트북을 서버로 사용 중입니다.

 * [C급 개발자](http://www.thewhiterock.net/)
    * 어떤 생각을 하고 있는지 살짝 볼 수 있습니다.
 * [C급 개발자의 서재](http://book.thewhiterock.net/)
    * 작년 5월 이후 업데이트가 없었으나, 관심사를 엿볼 수 있습니다.

"C급 개발자"인 이유는 번역 및 블로그에 글을 잘 쓰시는 [박재호 님](http://jhrogue.blogspot.kr)이 B급 프로그래머라는 지칭하는 것을 본 것과 [“1인분 인생”](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788996632078&orderClick=LEA&Kc=)이라는 책에 다음 글을 보고 정했습니다.

> A급은 이론을 만드는 사람
>
> B급은 이론을 수정하는 사람
>
> C급은 이론을 적용하는 사람

# 교육

 * 숭실대학교 컴퓨터 학부 ( 1995.3 ~ 2003.2 )

# 군복무

 * 공군 병장 만기 제대 ( 1997.10 ~ 2000.4 )
    * 자대는 공군 중앙전산소였으나, 공군본부 전산과에서 전산행정병으로 파견되어 복무했습니다.
    
