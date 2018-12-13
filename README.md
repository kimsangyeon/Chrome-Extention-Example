# Chrome-Extention-Example
Chrome Extention Example

manifest_version: 확장프로그램 매니페스트 버전
name: 확장프로그램 이름
description: 확장프로그램 상세 설명
version: 확장프로그램의 현재 버전
background: 확장프로그램이 실행될때 백그라운드로 실행될 파일
browser_action: 해당 프로그램을 크롬에 등록시, 주소창 아이콘 설정 및 아이콘 클릭 액션, html 정의
permisstions: 해당프로그램에서 사용할 퍼미션
- tabs: 클릭시 새로운 탭이 오픈되도록하는 권한
- contextMenus: 마우스 오른쪽 클릭시 동작
- <all_urls>: 모든 url에서 확장프로그램을 사용