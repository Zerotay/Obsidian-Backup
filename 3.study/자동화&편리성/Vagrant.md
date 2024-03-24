# 개요
![[vagrant.png]]
https://www.vagrantup.com/
바그란트, 내지는 베이그런트.
가상화 소프트웨어 개발 환경을 다루는 도구이다.
가상화 소프트웨어에 대한 [[프로비저닝]] 툴인 것이다.
[[VirtualBox]], [[VMWare]], [[Hyper-V]]와 같은 가상 머신 세팅을 간편하게 관리하고 공유할 수 있게 된다.(버츄얼박스만이 라이센스 없이 사용가능하다.) 
설정 스크립트 기반으로 생성 및 유지보수를 관리할 수 있다.
메모리, 사용할 이미지 등을 미리 전부 지정할 수 있다. 

[[HashiCorp]]에서 루비 언어로 개발된 오픈소스

# 설치
https://developer.hashicorp.com/vagrant/install?product_intent=vagrant#windows
## 윈도우
![[Pasted image 20240324212216.png]]
본인의 맞는 파일을 다운로드한다.
msi 파일을 다운받게 된다.
![[Pasted image 20240324220601.png]]
약관만 동의하면 바로 설치가 가능하다.
![[Pasted image 20240324220652.png]]
성공적으로 설치된다면 자동으로 환경변수에 명령어가 등록되어 사용 가능해진다.

# 명령어

# 기본 사용법
- 박스 이미지 다운로드하고 프로젝트 생성
- 프로젝트 루트 디렉토리에 Vagrantfile 생성
- Vagrant 가상 인스턴스 시작
