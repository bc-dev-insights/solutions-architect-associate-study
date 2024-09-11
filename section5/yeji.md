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

