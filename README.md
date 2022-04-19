| **대외활동**      |                                                              |
| ----------------- | ------------------------------------------------------------ |
| 2014.03 - 2015.03 | 정보보호 동아리, 전국정보보호동아리 연합  대학교 내 정보보호 동아리 회장  전국정보보호동아리 연합(KUCIS) 부회장 |
| 2018.07 - 2018.07 | CodeEngn   스태프                                            |
| 2018.11 - 2018.11 | PoC Security Conference  PoC 컨퍼런스 스태프 및 벨루미나(CTF) 운영진 |
| 2018.06 - 2019.03 | Best of the Best (BoB)  7기 – KITRI  보안제품개발트랙 수료   |
| 2021.03 - 2021.03 | 해킹캠프   발표자      -     발표주제 : 네트워크 및 웹 프로토콜 분석 기초  -     발표내용 : 개발자도구를 이용한 웹 프르토콜의 네트워크 분석 방법과 안드로이드와 IOS환경에서의  Burp Suite를 이용한 간단한 어플리케이션 네트워크 프로토콜 분석 방법을 발표함. 또한, 분석 방법을 통해 발생할 수 있는 취약점을 가진 어플리케이션으로 취약점 시연 |

 

 

 

 



 

| **취약점 제보 이력** |                                                              |
| -------------------- | ------------------------------------------------------------ |
| 2018.07              | Genie (음악스트리밍 서비스)  인가받지 않은 사용자의 콘텐츠 (MP3) 다운로드 취약점 발견 및 제보      Genie의 음악 스트리밍서비스에서는 월별 요금제를 통해 음악을 스트리밍 하는데 스트리밍을  위해 전달된 URL을 프로토콜 분석을 통해 음악 스트리밍을 위한 음원(MP3)파일을 사용자가 제한없이 저장할 수 있었음. 또한, 이전 버전의 어플리케이션에서  사용하는 낮은 버전의 API를 이용하는 경우  요금제 없이도 특정 ID 값 (e.g., 2387129)을 이용하면 로그인과 월별 요금제를 통한 서비스 가입 없이도 음악을 스트리밍, 저장할 수 있는 취약점을 발견하고 제보 |
| 2020.03              | 국내 5대 택배사 (대한통운, 우체국, 롯데, 로젠, 한진)     Unmask 된 이용자의 개인정보 (이름, 상세주소, 전화번호, 배달 물품) 유출 취약점 발견 및 KISA 제보 |
| 2020.09              | 우체국 택배      우체국 택배의 온라인 결제 시스템 파라미터 변경 취약점 KISA  제보 |
| 2020.09              | 보건복지부 어플리케이션 [전자출입명부]      API 파라미터  변경을 이용해서 사업장의 방문자와 사업자 정보가 조회 가능한 취약점과  HMAC을 사용하는 QR코드에서  야기될 수 있는 문제 (대칭키 사용  시 인가된 사용자가 발급되었음을 증명할 수 없는 문제)를 대응 방안과 함께 제보 |
| 2022.01              | wavve (OTT 서비스)  DRM 콘텐츠의 다운로드 취약점 발견 및 제보     MPEG-DASH에서 이용하는  Widevine의 경우  chrome 80.0.3987.149버전 이하의 DLL에 취약점이  있어 DRM에 사용되는  KID:KEY를 얻을 수 있음. 이를 이용해서  wavve에서 취약한 DLL을 이용해서 DRM  콘텐츠를 재생할 경우 암호화에 사용되는 key를 얻어  init.mp4 파일과 각  segment.m4s 파일을  merge 한 후 복호화를 진행하면 암호화(DRM)되지 않은  콘텐츠를 획득·저장 할 수 있는 문제를 발견하고 제보 |

 

| **연구 논문** |                                                              |
| ------------- | ------------------------------------------------------------ |
| 2020.03       | WWW (World Wide Web)  Conference 2020  공동 1저자     -      논문 제목 : I’ve Got Your Packages: Harvesting  Customers’ Delivery Order Information using Package Tracking Number  Enumeration Attacks (https://dl.acm.org/doi/10.1145/3366423.3380062)  -      논문 내용 : 국제 택배 회사 3사(UPS, DHL, FedEx)를 대상으로 네트워크 프로토콜 분석을 통한 API 운송장 번호 순차 대입 공격을 이용한 개인정보 유출 위험성 및 해결방안 제시 |
| 2020.08       | ACISP ( Australasian Conference on Information Security and  Privacy) 2020  1저자     -      논문 제목 : Design and Evaluation of Enumeration  Attacks on Package Tracking Systems (https://link.springer.com/chapter/10.1007/978-3-030-55304-3_28) -      논문 내용 : 국내  택배 회사 5사(대한통운, 우체국, 롯데, 로젠, 한진)를 대상으로 네트워크 프로토콜 분석을 통한 API 운송장  번호 순차대입 공격을 이용해 마스킹 되지 않은 사용자 개인정보 유출 취약점 확인 및 해결방안 제시 |

 

 

 



 

| **개발 및 프로젝트 이력** |                                                              |
| ------------------------- | ------------------------------------------------------------ |
| 2017                      | 네트워크 기본 개발  OS:  Ubuntu Language: C++     pcap library 라이브러리를 이용한 패킷 캡쳐   ARP Packet에 대한 이해와 응용을 위한 ARP Spoofing Tool 제작   네트워크 In-path를  통한 패킷의 변조 및 차단  (Netfilter와 windivert 사용)  무선 네트워크 (802.11)의  구조 분석 및 캡쳐를 위한 airodump-ng copy project |
| 2017.04 - 2017.10 | 국내 통신사 과금 정책 취약점을 이용한 LTE 데이터 무제한 사용  OS:  Ubuntu Language: C++     2014년 NDSS 발표 논문   Gaining Control of Cellular Traffic Accounting by Spurious TCP  Retransmission 을 implementation 한 것으로, 국내 통신사가 TCP retransmission 패킷에 대하여 데이터 이용을 차감하지 않는 점을 이용해 단말기에서 발생하는 모든  패킷을 TCP retransmission 패킷으로 encapsulation 하여 셀룰러 데이터를 통신할 수 있도록 함. 모든  패킷을 TCP Retransmission으로 만들기 위해 모든 패킷이 개발한 프로그램으로 control 할 수 있는 in-path 환경으로 구성이 되어야  했으며, in-path를 위해 가상 인터페이스(TUN)를  만들고 모든 패킷이 TUN 인터페이스로 전달되도록 라우팅 테이블을 설정함. 기존 패킷에 Fake IP, TCP 헤더를 encapsulation을 하게 되면 MTU를 초과하여 fragmentation이 발생하므로 이를 방지하기 위해 TUN 인터페이스의 MTU size를  1500 미만으로 하여 fake header (IP+TCP)의 사이즈와 기존의 패킷 사이즈가 1500이  넘지 않도록 설정함. Fake header를 encapsulation 하게 되면 정상적인  통신이 불가능하므로 가상의 proxy 서버를 만들어 fake header를 decapsulation하고 원래 목적 서버로 통신을 대신하여 다시 TCP retransmission 패킷으로 단말기로 정상적인 서버로부터의 응답을 다시 전달 |
| 2018.01 | 802.11 (무선랜) 환경에서의 Monitor Mode Cookie Sniffing  OS:  Ubuntu Language: C++     2018년 당시 네이버 웹사이트에서 개인정보가 들어가지 않는 페이지 (뉴스, 웹툰 등)은  보안통신을 이용하지 않아 기존에 로그인이 되어있는 상태라면 로그인 정보와 관련된 cookie가 평문으로 전송 됨. 이를 무선랜 환경에서 모니터 모드로 로그인과 관련된 cookie 정보를 얻기 위해 모니터 모드를 지원하는 랜카드와 C++, LibTins를 이용해 WPA2 환경에서 로그인 세션 탈취를 시연한  바 있음. WPA2 환경에서 패킷을 복호화 하기 위해 AP join시에 발생하는 4-wayhandshaking(EAPOL) 패킷을  모니터 모드로 수집하여 AP와 station간의 패킷을 복호화 할 수 있도록 함.  이 경우 기존에 연결한 station의 패킷을 복호화 할 수 없기 때문에 Deauth packet을 broadcast로 전송하여 모든 station의 연결을 잠시 끊고 EAPOL이 발생하도록 함 |
| 2018.04 | 유무선 환경에서의 네트워크 프린터 프로토콜  (LPR RAW)을 이용한 Replay   OS:  Ubuntu Language: C++     네트워크 프린터 프로토콜은 보안 프로토콜인 IPP를 제외하고는 평문 통신을 이용하므로, 네트워크  환경에서 프린터에 프린터를 요구하는 패킷을 캡쳐 가능 한 경우 (무선 모니터 모드, ARP스푸핑을 이용한 MITM 등) 해당 패킷을 프린터에 그대로 replay attack 하거나, 프로토콜 분석을 통해 출력한 문서나  이미지 등을 알아낼 수 있는 취약점으로 이 프로젝트의 경우 무선 모니터 모드를 이용해 out-of-path로 패킷을 스니핑 하여 패킷 reply  attack을 통해 스니핑 된 출력물의 내용을 볼 수  있었음 |
| 2018.06 | PXE(Preboot Execution  Environment) 부팅 프로토콜 분석   OS:  Ubuntu Language: C++      PXE 부팅은 OS 이미지를  부팅 시에 네트워크 레벨에서 전해주는 환경으로,  DHCP(UDP) 프로토콜을 이용해 PXE 부팅 서버를 찾게 되는데 이때, 서버에  대한 인증 절차가 없어 DHCP Discover  패킷에 대해 먼저 응답을 하거나, PXE 부팅 서버에 in-path로 DHCP offer 패킷에 대해 drop을 하게 되면 다른 사용자가 임의로  다른 OS 이미지를 줄 수 있는 취약점을 프로토콜 분석을 통해 발견하고 프로젝트로 발표함 |
| Others  | URL  https://github.com/janghanbin    https://gitlab.com/janghanbin       이외의 다른 프로젝트는 github, gitlab에 업로드되어있으며 취약점과 관련된 모든 repository는 private로 설정되었음 |



