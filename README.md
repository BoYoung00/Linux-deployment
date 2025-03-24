# Github를 이용한 CI/CD 자동 배포하기

# 

## 배포 단계

[1\. Git과 Github를 이용해 서비스 중단없이 배포하기](https://docs.google.com/document/d/1YonAK2k8BDma7_5BzmDUc-ExPAvKQb-jmAU9V8csyj4/edit?usp=sharing)  
[2\. Nginx를 프락시 서버로 이용해서 80 포트로 서비스하기](https://docs.google.com/document/d/19XSmI-bU7q-edqFnMCxo3qeC3WRjCv21cTMVjwbOP9E/edit?usp=sharing)  
[3\. SSL 인증서 발급을 통해서 HTTPS(443포트)로 서비스하기](https://docs.google.com/document/d/1QqTcDVb6ltVXeVWtb_h-rfRlQJ6A3RzSX4G0_oWSF5U/edit?usp=sharing)  
[4\. 내 앱이 자동으로 시작될 수 있도록 서비스로 등록하기](https://docs.google.com/document/d/1f84oYWvyEvUkM3lJjNd0DmJolr96yUPg2LDiHul-sQk/edit?usp=sharing)  
[5\. CI/CD를 위한 bash 배포용 스크립트 작성하기](https://docs.google.com/document/d/1Y_xXODo35SkjAkf83giA9n0CpfWbpbjjV0ZC5kM5onA/edit?usp=sharing)  
[6\. Github Actions 기능을 이용해서 배포 자동화하기](https://docs.google.com/document/u/0/d/1rKZLrcx8ZMY0CIMZ-o_Ygx9h18S_SdrRNx2VgqwCk8A/edit)

# Terms

## Deployment(배포)란?

(서비스) 배포란 내 웹 서비스가 24시간 365일 실행될 수 있는 환경으로 옮겨 놓는 것.  
(앱) 배포란 내 앱이 사용자에게 전달(및 설치)될 수 있는 환경으로 옮겨 놓는 것.

## CI/CD 란?

CI/CD(Continuous Integration and Continuous Deployment)란 기존 서비스를 중단하지 않고 통합하고 배포할 수 있는 방법을 말한다.

**\[공지\]**  
내일 프로젝트 발표가 마무리 되면 서버 권한을 제한할 예정입니다.

다른 팀의 서비스를 중지하게 만드는 권한은 제거할 예정이므로, 혹시 자신의 팀 서비스를 관리하는데, 필요한 권한이 더 필요한 부분이 있다면 알려주시면 권한을 부여하겠습니다.

