---
title: 영화관 매표 시뮬레이션
subtitle: micro C/OS-ii으로 개발한 영화관 매표 시뮬레이션 시스템
date: 2017-03-01
modal-id: 4
img: ticket-simulation.png
thumbnail: ticket-simulation-thumbnail.png
github: https://github.com/jsc2576/ticket_box
project-date: 2017.03 ~ 2017.06
client: 대학교 팀 프로젝트 (70%)
role: 프로젝트 설계 및 프로그래밍
function: message queue, semaphore
tech: micro C/OS-ii
description: 실시간 커널인 micro C/OS-ii 으로 개발한 영화관 매표 시뮬레이션 시스템입니다.<br>매표소에는 일반 고객과 vip 고객의 줄로 나뉘어서 vip가 줄을 선 경우 일반 손님보다 우선적으로 티켓을 나누어 주는 것을 시뮬레이션하였습니다.<br>micro C/OS-ii는 동일한 우선순위에 태스크를 할당할 수 없어서 각각의 고객 객체, 매표소 객체, gui 태스크로 나뉘어서 우선순위를 순차적으로 바꿔 동작하도록 설계하였습니다.
---
