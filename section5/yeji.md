# section5: EC2 기초


2. 보안그룹

- 기본포트
```
22 = SSH (Secure Shell) - 리눅스에서 EC2 인스턴스에 로그인 가능
21 = FTP (File Transfer Protocal) - 파일 전송 프로토콜
22 = SFTP (Secure File Transfer Protocal) - 안전한 파일 전송 프로토콜
80 = HTTP - 보안되지 않은 웹사이트 접속
443 = HTTPS - 보안 웹사이트에 엑세스
3389 = RDP (Remote Desktop Protocal) - 윈도우 인스턴스 로그인 시 사용
```

3. SSH 개요

putty > 뿌띠가 아니라 퍼티..

![image](https://github.com/user-attachments/assets/942f3dfd-a4d1-4ff1-a87e-10a76540a43e)

> SSH는 터미널이나 명령줄을 이용해서 원격 머신이나 서버를 제어 할 수 있게 해줌.

ppk의 약자는 Putty Private Key이다. putty프로그램에서 사용하기 위한 키파일 확장자이고, pem은 Privacy Enhanced Mail의 약어로 범용성이 높은 키파일확장자이다.

*pem 파일 쓰도록

- EC2 Instance Connect

브라우저 상에서 EcInstance를 바로 연결할 수 있음

4. EC2 인스턴스 역할 데모

5. 인스턴스 구매 옵션

- 온디맨드 인스턴스 (On-demand Instances) : 필요한만큼 인스턴스를 실행 할 수 있음. 단기적인 워크로드에 사용하기 좋음. 비용을 예측할 수 있고 초 단위로 요금 지불
- 예약 인스턴스 (Reserved Instances) : 1년또는 3년 기간으로 장기적인 워크로드 용. 오랫동안 데이터베이스를 실행계획인 경우 예약 인스턴스가 좋음
- 유연한 인스턴스 (Convertible Reserved Instances) : 시간이 지나 인스턴스 타입을 변경하길 원하는 경우 전환형 예약 인스턴스가 적절.
- 절약 플랜 (Saving Plans) : 1년 또는 3년 기간. 달러 단위로 특정한 사용량을 약정하여 사용하는 방식. (장기 워크로드용)
- 스팟 인스턴스 (Spot Instances) : 아주 짧은 워크로드를 위한 것. 인스턴스들이 언제라도 손실 될 수 있어서 신뢰성이 낮음.
- 용량 예약 (Capacity Reservations) : 원하는 기간동안 특정한 AZ에 용량을 예약할 수 있음.

 
