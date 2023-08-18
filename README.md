# 직원 리스트 관리 서비스

## 개요

간단하게 직원을 추가, 삭제, 수정할 수 있는 웹 어플리케이션입니다.

## 배포링크

https://yamyam-code.github.io/listJS/

## 유저플로우

![유저플로우](https://github.com/Yamyam-code/intro/assets/121215024/611d3eef-2871-44f2-9b6a-0aa6c0223ecc)

## 세부사항

### 데이터 관리

firebase를 통해 img파일을 보관하고 text-data는 localstorage에 보관합니다. <br />
기본으로 생성되는 4명의 직원 데이터는 type: defalt를 가지며 개인이 추가한 직원의 경우
type: add를 가지고 localhost에 저장됩니다.
type: defalt의 직원의 사진을 변경할 경우 해당 직원의 type이 add로 변경됩니다.
localstorage의 data를 통해 firebase의 img를 불러오거나 삭제합니다.
type: defalt인 직원은 삭제하더라도 firebase에 있는 해당 img파일이 삭제되지 않습니다.

### 이용
