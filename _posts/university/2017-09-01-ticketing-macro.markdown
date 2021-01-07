---
title: 인터파크 티켓팅 매크로
subtitle: 인터파크 티켓에서 좌석 선택까지 자동으로 선택해주는 매크로
category: university
date: 2017-09-01
modal-id: 8
img: ticketing-macro.png
thumbnail: ticketing-macro.png
# github: 
project-date: 2017.09 ~ 2017.12
client: 개인 프로젝트
role: 프로젝트 기능 정의, 설계 및 프로그래밍
function: GUI, 캡차 OCR, 자동 로그인, 자동 좌석 선택
tech: python(tkinter, PIL, selenium, pytesseract)
description: 인터파크 티켓 사이트에서 좌석 선택까지 자동으로 실행되는 매크로입니다.<br>티켓팅 화면은 동적인 요소들이 많아 selenium을 사용하여 html의 element들을 읽어 정해진 절차대로 클릭하여 넘어가도록 설계하였습니다.<br>좌석 선택 전에 매크로 방지 문자인 captcha가 존재하여 구글에서 배포하는 OCR 라이브러리인 pytesseract와 이미지 처리 라이브러리인 PIL을 사용하여 텍스트를 입력하였습니다.<br>captcha 텍스트가 틀리는 경우 새로고침하여 새로운 이미지를 받아온 후 다시 OCR을 시도하였습니다.<br>티켓팅을 진행함에 필요한 데이터들은 GUI 라이브러리인 tkinter를 사용하여 쉽게 데이터를 입력하도록 하였습니다.
---
