# OOG-Simulator

OOG(Out of Gauge) 화물 적재 시뮬레이터. 화물 치수와 중량을 입력하면 적합한 컨테이너를 추천하고, 중앙 적재 기준으로 얼마나 튀어나오는지 3D로 보여줍니다.

## 사용법

웹에서 바로 사용: https://jamesjang-gu.github.io/OOG-Simulator/

또는 `oog_simulator.html`을 브라우저로 열면 됩니다. 별도 설치는 필요 없습니다 (3D 표시에 Three.js CDN 사용, 인터넷 연결 필요).

## 기능

- 표준(20GP/40GP/40HC), Open Top, Flat Rack, Super Rack 중 추천 컨테이너 선정
- 표준 규격 대비 초과량(OH/OW/OL) 수치화
- Dead Space(선박 손실 슬롯) 계산: L·W·H 축별 손실 슬롯, 모서리 슬롯, TEU 환산, 정면·측면 슬롯 단면도
- 컨테이너별 규격 카드와 적재 가능 여부
- 3D 적재 뷰: 드래그 회전, 우클릭/Shift 드래그 이동, 휠/핀치 확대, 방향키, 프리셋 시점, 자동 회전

장비 내부 치수와 최대 적재 중량은 선사별로 다를 수 있으니 실제 부킹 전 선사 스펙을 확인하세요.
