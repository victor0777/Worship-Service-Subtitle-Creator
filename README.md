# Worship-Service-Subtitle-Creator

교회 자막 생성 프로그램
# log info
20250114 release 0.3
1. 새벽 예배 프로그램 추가
2. 바탕화면에 주일 예배와 새벽 예배 아이콘 추가

20250113 release 0.2
1. RPC error fix (rpc call이 너무 빠르게, 너무 자주 발생해서 delay 추가)

# Prerequisites
1. .NET framework 4.8(ndp48-web.exe)
2. Microsoft PowerPoint 2013 이상
3. Windows

# install 방법
1. .NET framework 4.8을 먼저 설치한다.
2. setup.exe를 실행시킨다.
3. 설치 위치는 default를 사용한다.
   
# 간단한 설명
0. 프로그램 저장 위치(default): C:\Applications\NewSongMacro1
1. 실행파일: new_song_macro1.exe
2. Text 편집: ./input/Subtitle_Template.txt
3. PPT template: ./input/Subtitle_Template.pptx
4. 결과: ./output/[YYYYMMDD]_Subtitle.pptx 
   <p> [YYYYMMDD]는 현재 날짜로 저장이 됨
5. 에러 발생시 로그: ./log


