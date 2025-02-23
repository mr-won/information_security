[정보보안기사 문제 풀이 사이트 cbt](https://www.kinz.kr/exam/419923)
![image](https://github.com/user-attachments/assets/2361cd39-1a88-493f-bcb5-9004fa2ae6e2)
(24.01.04 ~ 25.04)

snort, suricata, NetBios, zeekIDS, Log Parser, Elastic Search 사용가능툴
시그니처기반, 임계치기반 분석 
비업무시간 동안의 내부 시스템 통신 트래픽 수 조사
```
1. 윈도우 시스템의 사용자 계정 및 패스워드를 암호화하여 보관하고 있는 SAM(Security Account Manager)에 대한 설명으로 틀린 것은?
① HKEY_LOCAL_MACHINE\SAM에 저장된 키는 일반계정도 확인할 수 있다.
② 크래킹을 통해 패스워드를 얻을 수 있다.
③ 운영체제가 작동하는 한 접근할 수 없도록 잠겨져 있다.
④ 레지스트리 HKEY_LOCAL_MACHINE\SAM에 구체화된 자료들을 실제로 저장한다.

1번
```
```
2. 디스크 스케줄링 알고리즘 중 엘리베이터 알고리즘이라고 불리는 기법은?
① SCAN
② SSTF
③ C-SCAN
④ FCFS

SCAN
```

```
3. 윈도우에서 제공하는 BitLocker에 대한 설명으로 틀린 것은?
① 윈도우 7에서도 가능하다.
② exFAT 파일 시스템은 지원하지 않는다.
③ USB 저장매체도 지원 가능하다.
④ 텍스트 파일 형태의 복구키를 제공한다.

2번
```

```
4. EDR(Endpoint Detection Response) 솔루션의 주요 기능으로 옳지 않은 것은?
① 보안사고 탐지 영역
② 보안사고 통제 영역
③ 보안사고 확산 영역
④ 보안사고 치료 영역

3번
```
```
5. Window 서버의 보안 옵션 설정 중 보안 강화를 위한 설정으로 옳지 않은 것은?
① “로그온 하지 않고 시스템 종료 허용”을 “사용 안함”으로 설정하였다.
② 원격 관리를 위해 “원격 시스템에서 강제로 종료” 정책의 “Administrators” 외 서버에 등록된 계정을 모두 등록하였다.
③ “이동식 미디어 포맷 및 꺼내기 허용” 정책이 “Administrators” 로 되어 있다.
④ “SAM 계정과 공유의 익명 열거 허용 안함” 정책을 설정하였다.

정답은 **② 원격 관리를 위해 “원격 시스템에서 강제로 종료” 정책의 “Administrators” 외 서버에 등록된 계정을 모두 등록하였다.**입니다.

“원격 시스템에서 강제로 종료” 정책은 원격 시스템에서 다른 사용자의 로그온 없이 시스템을 강제로 종료할 수 있는 권한을 부여하는 정책입니다. 이 정책을 “Administrators” 외 서버에 등록된 계정을 모두 등록하면, 해당 계정을 가진 사용자는 다른 사용자의 로그온 없이 시스템을 강제로 종료할 수 있습니다. 이는 보안을 저해하는 설정입니다.
```


1. 개인정보보호위원회와 한국인터넷진흥원에서 발간한 "개인정보영향평가 수행 안내서"에 따르면 위험도 산정 공식을 다음과 같이 제시하고 있다. ( )에 들어갈 항목명을 기술하시오.  

[위험도 산정 공식]

위험도 = 자산가치(영향도) + ((A) * (B)) * (C) 

(답) 침해요인 발생 가능성, 법적 준거성, 2

* 해당 안내서를 보지 않았으면 맞추기 어려운 문제였습니다. 실무에 도움이 되는 사항이므로 아래 링크에서 안내서를 다운로드 받으신 후 112~114페이지 부분을 한번 읽어보시기 바랍니다. 최근에 개정된 신버전에서는 64페이지, 116페이지를 참조하시면 됩니다.

* 참조(구버전) https://www.privacy.go.kr/cmm/fms/FileDown.do?atchFileId=FILE_000000000841139&fileSn=1

​* 참조(신버전: 2024년 4월 개정)

https://www.privacy.go.kr/cmm/fms/FileDown.do?atchFileId=ATCH_000000000881356&fileSn=1

​

2. DB 암호화 기법에 대한 설명이다. ( )에 해당하는 기법의 명칭을 기술하시오.

( A ) : 암복호화 모듈이 API 라이브러리 형태로 각 애플리케이션 서버에 설치되고, 응용프로그램에서 암복화 모듈을 호출하는 방식

( B ) : 암복호화 모듈이 DB서버에 설치되고 DBMS에서 플러그인으로 연결된 암복화 모듈을 호출하는 방

( C ) : DBMS에 내장되어 있는 암호화 기능을 이용하여 암복호화 처리를 수행하는 방식

(답) API, Plug-in, TDE(Transparent Data Encryption)

* 수험서에 있는 내용이므로, 반드시 맞춰야 합니다.

* 참조 : http://wiki.hash.kr/index.php/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4_%EC%95%94%ED%98%B8%ED%99%94

​

3. LAN 스위칭 기법에 대한 설명이다. ( )에 해당하는 기법의 명칭을 기술하시오.

( A ) : 프레임의 헤더(목적지 주소)만을 보고 경로를 결정해 주는 방식

( B ) : 프레임의 앞 64바이트만을 읽어 에러를 처리하고, 목적지 프트로 포워드 하는 방식

( C ) : 전체 프레임을 다 받은 다음에 경로를 결정하는 방식

(답) Cut through, Modified Cut through (Fragment Free), Store and Forward

​* 수험서에 있는 내용입니다. 최소 2점 이상 획득이 필요합니다. 

​* 참조 : http://www.ktword.co.kr/test/view/view.php?no=2882

​

4. EAP를 통해 인증을 수행하고 AES-CCMP 기반 암호화를 지원하는 무선랜 보안 표준은?

(답) WPA2

* 수험서와 기출에서 모두 다루어진 문제입니다. 반드시 맞춰야 합니다.

​

5. VLAN(Virtual LAN) 의 주소 할당 방법에 대한 설명이다. ( ) 에 해당하는 방식명을 기술하시오.

 ( A ) : VLAN 할당을 관리자가 각 스위치에서 직접 할당하는 방식

 ( B ) : MAC주소 등을 기반으로 VLAN 할당이 자동으로 이루어지는 방식

(답) 정적 VLAN(포트 주소 기반), 동적 VLAN(MAC 주소 기반)

* 수험서에 VLAN은 포함되어 있으나, 주소 할당 방법에 대한 자세한 설명은 없으므로 정답을 맞히기 어려웠으리라 생각됩니다. 

* 참조 : http://www.ktword.co.kr/test/view/view.php?nav=2&no=2022&sh=VLAN

​

​

​6. 검색로봇에게 웹사이트의 페이지를 수집할 수 있도록 허용/제한하는 국제 권고안으로 웹사이트의 루트 디렉터리에 위치해야 하며, 로봇 배제 표준을 따르는 일반 텍스트 파일(text/plain)로 작성해야 하는 파일명은 무엇인가?

(답) robots.txt

* 13회, 15회에 출제된 문제이며, 수험서에도 포함되어 있으므로 반드시 맞춰야 합니다.

​

7.  ISO 31000 위험평가 방법론에 따른 위험평가 절차에 대한 설명이다. ( )에 들어갈 위험평가 단계명을 기술하시오.

( A ) : 운영 실패, 공급망 중단 또는 인재 격차와 같은 외부 및 내부 위험을 고려하여 잠재된 위험 식별

( B ) : 확인된 위험이 조직의 목표 및 운영에 미칠 가능성과 잠재적 영향을 분석

( C ) : 조직의 위험 감수성(Risk Appetite), 수용 능력, 위험과 보상 간의 균형을 고려하여 위험 허용 수준(DoA) 결정하고, 위험의 중요성에 따라 위험 처리 필요성을 결정

(답) 위험식별, 위험분석, 위험평가

* 위험평가 절차는 17회에 출제된 바 있습니다. 최소 2점 이상 획득해야 합니다.

* 참고 : https://www.boannews.com/media/news_print.asp?idx=50393

​

8. 다음과 같은 기능을 수행하는 정보보호 솔루션의 이름은 무엇인가? 

- PC에 설치된 에이전트, 네트워크 센서를 통하여, 이동식 디스크, 이메일, 메신저, 웹사이트 파일 업로드를 이용한 내부 문서 이동 탐지  

- HTTPS와 같은 암호화 통신에서도 중요 내부 문서 이동 탐지 가능

- 일부 솔루션에서는 파일 암호화, 파일 삭제와 같은 부가 기능 탑재​

(답) DLP(Data Loss Prevention)

* 수험서에 있는 내용으로 반드시 맞춰야 합니다.

 ​

9. 유닉스에서 현재 실행되고 있는 프로세스 정보가 기록되며, 숨겨진 프로세스를 찾기 위해 참조하는 경로는 /( A )이다.   

(답) proc

* 기출문제와 수험서에 포함된 내용으로 반드시 맞춰야 합니다. 

​

10. 다음 아파치 로그를 보고 물음에 답하시오

[아파치 로그]

200.3.1.4 - - [30/May/2023:01:20:01 +09:00] "(1) GET /bulletin/read.php?no=101&item=book (2) HTTP/1.1" 200 3549 (3) "http://test.co.kr/main.php" "Mozilla/5.0 (compatible;MSIE 10.0;Windows NT 6.1;WOW64;Trident/6.0)"

1) no=101&item=book 의 의미는?

2) http 상태코드는 무엇인가?

3) http://test.co.kr/main.php 의 의미는?

 

(답)  

1) /bulletin/read.php 파일을 GET 방식으로 호출할 때 2개의 파라미터(no, item)에 값을 각각 할당하여(no=101 and item=book) 매칭되는 결과를 요청 

2) 200 (웹서버가 요청을 정상적으로 처리했음을 의미)

3) 현재 URL을 호출한 referer URL을 의미(즉, test.co.kr/main.php에서 GET 방식으로 현재 URL(/bulletin/read.php)를 호출하였음)

* 수험서에도 포함되어 있고, 23회 기출문제에서도 다루어진 내용으로, 최소 2점 이상 획득해야 합니다. 

​

11. 개인정보 가명처리 기법 중 수치 데이터를 임의의 수인 자리수, 실제 수 기준으로 올림 또는 내림 처리하는 기법의 명칭은 무엇인가? 

(답) 랜덤 라운딩

* 수험서에 없는 신규 문제로 맞추신 분은 거의 없을 것으로 보입니다. 아래 가명정보 처리 가이드라인의 85~92 페이지를 참조하시기 바랍니다.

* 참조 : https://www.pipc.go.kr/np/cop/bbs/selectBoardArticle.do?bbsId=BS217&mCode=D010030000&nttId=9900#LINK

​

12. 아파치 SW 재단에서 개발한 JAVA 기반의 오픈소스 프로그램으로 자바기반 프로그램을 개발할 때 로그를 쉽고 편하게 남기기 위한 목적으로 사용된다.  2021년말 이 프로그램의 JNDI Lookup 메소드를 호출할 때 입력값에 대한 검증 없이, 임의의 코드가 실행되는 취약점이 발견되어 전세계를 떠들썩하게 만들었던 프로그램의 이름은 무엇인가? 

(답) Log4J

* 수험서에는 없는 내용이나, 오프라인 강의 시 OWASP Top 10 취약점 설명할 때 말씀드렸던 프로그램입니다. 보안 뉴스와 같이 최신 보안 동향도 관심을 가지고 보시면 좋겠습니다. 

​

[서술형]

13. 다음의 두 가지 조치가 필요한 이유를 설명하시오.

1) chmod -s {파일명}

2) find / -user root -type f \( -perm -4000 -o -perm -2000 \) |xargs ls -al

(답) 

1. 두 가지 조치의 의미

 1) 특정 파일에 설정된 특수 비트(SetUID, SetGID) 를 제거함.

 2) / 경로 하위에 존재하는 root 가 소유주인 파일 중 특수비트(SetUID, SetGID)가 설정된 파일을 검색함.

2. 두가지 조치가 필요한 이유

 - 특수비트가 설정된 파일을 실행하는 경우 파일의 소유주(SetUID 설정시), 또는 소유그룹(SetGID 설정시) 권한으로 실행됨. 특히 root 가 소유주 또는 소유 그룹인 파일에 특수비트가 설정되면, 일반 사용자 계정으로 실행하더라도 root 권한으로 실행되어 악의적인 행위가 가능하기 때문임.

* 특수비트는 매우 중요하며, 시험에 자주출제된 토픽입니다. chmod -s 명령의 경우 정확한 의미를 모르시는 분들이 많으셨을 것 같습니다. 그래도 s권한을 마이너스하는 것으로 유추할 수 있었을 거라 생각됩니다. 두 가지 조치가 필요한 이유를 물어봤습니다. 두 가지 명령의 정확한 의미를 쓰지 못했더라도, 이유에 집중해서 잘 쓰셨으면 문제에 배정된 점수를 가져가시는데 큰 어려움은 없었을 거라 판단됩니다. 

 ​

14. rsh, rlogin, rexec 등은 인증 없이 관리자의 원격접속을 가능하게 하는 명령어들이므로 사용하지 않는 것이 안전하다. 불가피하게 사용하는 경우 /etc/hosts.equiv, $HOME/.rhosts 파일의 소유자, 권한, 파일 내 보안 설정을 어떻게 해야 안전한지 설명하시오.

(답) 

1) /etc/hosts.equiv 및 $HOME/.rhosts 파일의 소유자를 root 또는, 해당 계정으로 변경

 - chown root /etc/hosts.equiv

 - chown <해당 계정명> $HOME/.rhosts 

2) 두 개 파일의 권한을 600 이하로 변경

 - chmod 600 /etc/hosts.equiv

 - chmod 600 $HOME/.rhosts

3) 두 개 파일 내에서 "+"를 제거하고 허용할 호스트 및 계정만 등록

(설정 예시) 

  +    +      # 모든 호스트의 모든 유저가 내 서버로 인증 없이 접속가능

hostA      # 2번째 필드가 없다면 hostA의 현재 사용 중인 유저 접속가능

hostA   +     # hostA 의 모든 유저가 인증없이 접속 가능

hostA user01   # hostA 의 user01 사용자만 인증없이 접속가능.

* 수험서에 없는 신규 토픽이라 맞추기 어려웠으리라 생각됩니다. 주요정보통신기반시설 기술적 취약점 분석/평가 방법 상세 가이드(Page 34~35)에 있는 내용입니다. 잘 모르더라도 최대한 물고 늘어져야 합니다. 그래야 부분 점수를 4점~6점이라도 획득할 수 있습니다.  

​

15. IPTables와 관련하여 다음 물음에 답하시오.

1) IPTables의 3가지 Chain 설명

2) 다음 IPTables 룰의 의미 설명

  iptables -A INPUT -p tcp ! --syn -m state --state NEW -j LOG --log-prefix "[Faked NEW request]"

(답) 

1-1) INPUT Chain : 방화벽이 최종 목적지인 룰이 등록되는 체인

1-2) FORWARD Chain : 방화벽을 경유하는 룰이 등록되는 체인

1-3) OUTPUT Chain : 방화벽이 최초 출발지인 룰이 등록되는 체인

2) TCP 연결을 신규(NEW)로 맺는 패킷의 TCP Flag값이 SYN이 아닌 경우 "[Faked NEW request]"을 접두어로 하여 로그에 남기라는 의미

​* IPTables는 기본 토픽이며 시험에도 자주 출제됩니다. 이번 회차 합격을 위해서는 12점 모두 획득해야 합니다.  

​

16. SNMP 서비스 사용 시 적용되어야 하는 보안 설정 4가지를 설명하시오. 

(답) 

1) 커뮤니티 스트링을 default 값이 아닌 유추하기 어려운 값으로 변경한다. 

2) 암호화가 지원되는 SNMP 버전 3을 사용한다

3) ACL을 적용하여 SNMP를 이용할 수 있는 호스트를 제한한다.

4) RW(Read-Write)모드는 삭제하고 가급적 RO(Read-Only)모드를 사용한다.

* SNMP는 수험서에 포함된 내용입니다. 4개를 모두 정확히 기억해 내긴 어려웠을 것으로 보입니다만 이번 회차 합격을 위해서는 부분점수 8점 이상(2개는 확실히 맞추고 나머지는 유사하게) 획득해야 합니다.

​

[실무형]

17. A기업에서는 다양한 유닉스 계열 서버를 운영하고 있다. Solaris, Linux, AIX, HP-UX 서버에서 패스워드 최소 길이를 8자리 이상으로 강화하기 위한 설정 방법을 기술하시오.

(답) 

1) Solaris

   - 설정대상 파일 : /etc/default/passwd 

   - 설정값 : PASSLENGTH = 8

2) Linux

   - 설정대상 파일 : /etc/login.defs

   - 설정값 : PASS_MIN_LEN 8

3) AIX

  - 설정대상 파일 : /etc/security/user

  - 설정값 : minlen = 8

4) HP-UX

  - 설정대상 파일 : /etc/default/security

  - 설정값 : MIN_PASSWORD_LENGTH = 8​

​* 수험서에 있는 내용이나, 리눅스를 제외한 나머지 OS까지 외우고 준비하신 분은 많지 않으리라 생각됩니다. 주요정보통신기반시설 기술적 취약점 분석/평가 방법 상세 가이드에도 4개 OS에 대한 설정 방법이 담겨 있습니다.

​

18. xinetd 서비스에 대한 환경설정 파일에서 (1) ~(4)에 적절한 값을 기술하시오.

#  cd /etc/xinetd.d/

# cat telnet

service telnet

{

        flags  = REUSE   # 서비스 포트가 사용중인 경우 해당포트 재사용허용

        socket_type  = stream  #TCP 프로토콜 선택

        wait  = no               # 한번에 다중사용자에게 서비스 제공

        user  = root           #  root 권한으로 실행 

        server  = /usr/sbin/in.telnetd  #실행할 데몬 파일

        log_on_failure  += USERID    #서버 접속 실패시 USERID를 로그에 기록

        disable        = no                       # 서비스 사용

        (    1    ) = 10.0.0.0/8              # 10.0.0.0/8 대역은 서비스 미허용

        (    2    ) = 192.168.10.0/24  # 192.168.10.0/24 대역은 서비스 허용

        (    3    ) = 3                               # 동시에 접속가능한 최대 세션 수 3개

        access_time =  (    4    )          #접속을 허용할 시간 (9시 ~ 18시)

}

(답) 

1) no_access

2) only_from

3) instances

4) 09:00-18:00
