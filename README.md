# Vue.js-Todo

소개
GUITAR는 GUI 기반의 웹 테스트를 자동화 Framework 입니다.
최초 PC 브라우저 기반으로 테스트 자동화 도구로 제작되었으나, 다양하게 확장되어 PC Client 프로그램 및 스마트폰의 모바일앱까지 테스트가 가능합니다.
GUITAR 소개 http://helloworld.naver.com/helloworld/1296
GUITAR 사용 예제 동영상 (네이버 검색) : http://www.youtube.com/watch?v=qlnF6mFeP4c
GUITAR 사용 예제 동영상 (PC Client + 아이폰앱 + 안드로이드앱 상호 연동) : http://www.youtube.com/watch?v=TKyB3DGH15g
시스템 구조
Overview

설치방법
releases에서 최신 설치파일을 받아 설치합니다.
설치후 실행시 일부백신프로그램에서 실행파일을 바이러스로 오진하는 경우가 있으나, 안심하고 사용하셔도 됩니다. (http://www.autoitscript.com/forum/topic/34658-are-my-autoit-exes-really-infected/)
WINDOWS 7 및 VISTA 이상의 OS에서는 제어판에서 "사용자계정컨트롤설정변경"을 최소로 설정해야 합니다.
설치 프로그램에 포함된 예제스크립트가 정상작동되지 않을수 있습니다.
프로그램 설치후 최신 버전의 예제스크립(https://github.com/ssmmhh/guitarsample/archive/master.zip) 를 "c:\guitar\data"에 덮어 쓴뒤 사용하시기 바랍니다.
개발관련 설정
Autoit 3.3.8.1의 기본 라이브러리의 일부 함수가 수정되어야 합니다. autoit3381_guirichedit_hotfix\GuiRichEdit.au3 -> Autoit설치폴더\include에 덮어쓴뒤 사용하면 됩니다.
autoit 편집기의 SciTE Config (CTRL+1) 에서 "General Settings > AutoIt3 Directory settings > User include" 위치를 checkout 받은 최상위 폴더로 지정해야 합니다. (하위에 _include_nhn 이 존재해야 합니다.)
사용법
자세한 사용방법은 releases의 사용자설명서를 참고하시기 바랍니다.
다운로드
https://github.com/naver/guitar/releases
Q&A
https://github.com/naver/guitar/issues
FAQ
https://github.com/naver/guitar/issues?utf8=%E2%9C%93&q=label%3ATip%20
