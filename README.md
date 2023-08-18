# 직원 리스트 관리 서비스

## 개요

간단하게 직원을 추가, 삭제, 수정할 수 있는 웹 어플리케이션입니다.

## 배포링크

https://yamyam-code.github.io/listJS/

## 개발기간

2023.08.08 ~ 2023.08.18

## 유저플로우

![유저플로우](https://github.com/Yamyam-code/intro/assets/121215024/611d3eef-2871-44f2-9b6a-0aa6c0223ecc)

## 세부사항

![리스트](https://github.com/Yamyam-code/intro/assets/121215024/9f05e47a-1b11-4f57-8f19-934baeb6c904)

### 데이터 관리

- firebase를 통해 img파일을 보관하고 text-data는 localstorage에 보관합니다. <br />
- 기본으로 생성되는 4명의 직원 데이터는 type: defalt를 가지며 개인이 추가한 직원의 경우
  type: add를 가지고 localhost에 저장됩니다. <br />
- 각 직원의 데이터는 공통적으로 id, name, email, phone 값을 가집니다. <br />
- type: defalt의 직원의 사진을 변경할 경우 해당 직원의 type이 add로 변경됩니다. <br />
- localstorage의 data를 통해 firebase의 img를 불러오거나 삭제합니다. <br />
- type: defalt인 직원은 삭제하더라도 firebase에 있는 해당 img파일이 삭제되지 않습니다. <br />
- firebase에서 각 img는 등록 시 입력한 이름이 폴더몀이 되어 개인별로 관리됩니다.

### 이용

- 첫 접속 시 회원등록 페이지로 접속하게 되며 등록 시 메인 페이지로 이동됩니다.
- 한 번 등록한 인원은 접속 시 메인 페이지로 바로 이동됩니다.
- 직원의 추가 제거 시 현재 직원 수가 바로 업데이트 됩니다.
- 각 직원의 목록을 클릭하면 수정을 할 수 있는 프로필 페이지로 이동합니다.

### 애니메이션

- 헤더에 글씨마다 각각 다른 속력으로 움직이는 클래스 3개를 교차부여하여 효과를 주었습니다.
- 직원 등록을 클릭할 경우 데이터 입력을 위해 나타나는 폼에 효과를 주었습니다.

---

## 느낀 점
