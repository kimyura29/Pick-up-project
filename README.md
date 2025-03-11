# 기업의 채용 어시스턴트 PICK UP <img src="big-project-front/public/images/logo.png" width="100" height="auto">


## 📌 프로젝트 소개
> KT AIVLE School 6기 빅 프로젝트 - 채용 어시스턴트 PICK UP
>
> 개발 기간 : 2024.12.30 ~ 2025.02.17

### 🌟 프로젝트 개요
- PICK UP은 기업의 채용 프로세스를 효율적으로 개선하기 위해 AI 기반의 이력서 분석 및 평가 시스템을 제공합니다.
- 자연어 처리(NLP)와 벡터 검색 기술을 활용하여 지원자의 역량을 정량적으로 분석하고, 맞춤형 면접 질문을 생성함으로써 채용 담당자의 업무 부담을 줄이고 평가의 객관성을 높이는 것을 목표로 합니다.

### 💡 PICK UP 기획 배경

#### 🔹 채용 프로세스의 비효율성 문제
- 현재 기업 채용에서는 수천 명의 지원서를 검토하고 일정 조율, 평가 진행 등의 과정에서  **높은 업무 부담**이 발생합니다.
- 평가 기준이 일관되지 않아 **객관적인 점수화 및 정량적 분석**이 어려운 문제가 존재합니다.
- 직무 적합성 평가에 시간이 소요되며, **우수한 인재가 적절한 시기에 채용되지 못하는 리스크**가 있습니다.

#### 🔹해결하고자 하는 문제
- AI를 활용하여 **서류 검토 자동화** 및 **지원자 평가 기준의 정량화**
- 자연어 처리 기반 **채용 공고 및 자기소개서 분석**을 통한 면접 질문 자동 생성
- **RAG 기반 검색 최적화**를 활용해 **정확한 평가 모델 구축** 및 일관된 채용 기준 적용


### 🔐 회원가입 시 인증 수단과 다양한 정보 입력
PICK UP은 회원가입 시, 회사 이메일 인증을 통해 보안을 강화하고, 같은 회사 사람들끼리만 공유할 수 있는 게시판 커뮤니티를 제공합니다.
- 회원가입 / 로그인
    - 이메일 인증으로 인한 본인 확인 기능을 추가했습니다.
    - 회원가입과 로그인 패널 간의 전환은 자연스럽도록 구성했습니다.
- 게시판
    - 같은 회사의 사람들끼리만 게시판의 내용을 볼 수 있도록 설정했습니다.


### 🔎 PICK UP 서비스의 주요 AI 기능
PICK UP은 기업의 직무 별 평가항목을 입력하고, 그에 따른 평가 점수를 부여해 서류 검토 시 채용 프로세스를 효율적인 경험을 제공합니다.
- **📝 이력서 분석 및 평가 페이지**
    - LangGraph 기반의 AI 워크플로우를 활용하여 PDF 이력서 및 자기소개서를 자동 분석.
    - **Zilliz 벡터DB**를 활용하여 채용 공고 및 지원자의 이력서 임베딩.
    - 평가 기준과 비교하여 **지원자의 직무 적합성을 자동 평가**.

- **📊 분석 결과 페이지**
    - LangGraph 기반 상태(State) 관리를 적용하여 기업의 평가 기준과 과거 데이터를 반영한 지원자 역량 분석.
    - RAG 기법을 적용해 공고, 인재상, 학력, 대외 경험/수상 내역/어학/자격증, 경력을 기준으로 정량화하여 점수화.
    - 지원자별 평가 점수 통계 및 서류 합격 여부 결정 가능.
    - 팩트 체크(Fact-Checking) 노드를 적용하여 생성된 평가 근거 검증.

- **🎯 합격자 명단 및 면접 질문 생성**
    - **RAG 기반 검색 최적화**를 통해 **경험 중심, 경력 중심, 기술 중심의 맞춤형 면접 질문 생성**.
    - **Retriever와 Agent를 기반으로 Node 워크플로우 설계**, 조건부 Edge 적용하여 평가 과정의 자동화 구현.
    - 면접 질문 최적화를 위해 Rewrite Query Node를 활용하여 **질문의 명확성과 검색 성능 향상**.
<br/>

### 📊 기대 효과

- 채용 담당자의 업무 부담 감소 ➡️ AI 기반 자동 평가 및 문서 요약
- 객관적인 지원자 평가 ➡️ 정량적 분석을 통한 일관된 기준 적용
- 우수 인재 확보 가속화 ➡️ 빠른 직무 적합성 분석 및 맞춤형 면접 질문 제공


## 🧑 팀 구성
| [**강해찬**](https://github.com/ChaneHaDa) | [**최찬**](https://github.com/imchanchan) | [**박수민**](https://github.com/sueminPark) | [**유창현**](https://github.com/spaceOfSoul) | [**김성호**](https://github.com/sungho255) | [**김유라**](https://github.com/kimyura29) | [**심용훈**](https://github.com/yonghoon98) |
| :------: |  :------: | :------: | :------: | :------: | :------: | :------: |
|<img src="https://avatars.githubusercontent.com/u/140226331?v=4" width="150" height="auto"> |<img src="https://avatars.githubusercontent.com/u/105701334?v=4" width="150" height="auto"> | <img src="https://avatars.githubusercontent.com/u/139521789?s=96&v=4" width="150" height="auto"> | <img src="https://avatars.githubusercontent.com/u/85132981?v=4" width="150" height="auto"> | <img src = "https://avatars.githubusercontent.com/u/145109382?s=70&v=4" width="150" height="auto"> | <img src="https://avatars.githubusercontent.com/u/83355885?s=70&v=4" width="150" height="auto"> | <img src = "https://avatars.githubusercontent.com/u/102162601?v=4" width="150" height="auto"> |
| Leader, BE | BE | FE | FE | AI | AI | AI |
| RESTful api 구현 및 문서화 <br/> DB 구성 <br/> AWS 배포 | JWT 로그인 및 회원가입 구현 <br/> 게시판 CRUD <br/> spring security <br/> REST api 구현 및 문서화 | 전역 상태 관리 <br/> 회원가입, 로그인, 이력서 입력 및 결과 <br/> 페이지 구현 <br/> 게시판 CRUD <br/> 관련 api 통신 구현 | 메인 및 튜토리얼 페이지, pdf 모달, 평가 분석표 구현 <br/> 관련 api 구현 | ERD 설계 및 모델 api 작성<br/>(Fast API) <br/>langgraph 구현 <br/> RAG 구축 <br/>vectorDB 생성 및 연결 | 데이터 제작<br/> 프롬프트 엔지니어링<br/>langgraph 구현<br/>RAG 구축 | erd 설계 및 데이터 제작<br/> vectorDB <br/> 유지 보수 <br/> 모델 및 vectorDB <br/> api 작성 <br/> langgraph 구현 |


 
<br/>

## 🛠️ 기술 스택

**Front**
<br/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white" width="auto" height="25"/>
<img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" width="auto" height="25">
<img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" width="auto" height="25">



**Back**
<br/>
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" width="auto" height="25">
<img src="https://img.shields.io/badge/SPRING SECURITY-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" width="auto" height="25">

**Database**
<br/>
<img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" width="auto" height="25">
<img src="https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white" width="auto" height="25">

**Environment**
<br/>
<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" width="auto" height="25">
<img src="https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white" width="auto" height="25">


**Cooperation**
<br/>
<img src="https://img.shields.io/badge/gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" width="auto" height="25">
<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white" width="auto" height="25">

<br/>

## 🌐 website
[PICK UP 웹사이트 바로가기](https://picks-up.site/)

<br/>

## 🎨 아키텍처
![architecture](big-project-front/public/images/아키텍처.png)

<br/>

## 💡 주요 기능
|    회원가입 & 로그인    |
| :--------------: |
| <img src="big-project-front/public/images/회원가입_완료.png" width="200"> <img src="big-project-front/public/images/로그인1.png" width="200"> |
| - 회원가입 시, 이메일 인증을 통한 본인 확인<br/>- 회사명, 직무, 부서 등을 입력하여 회원가입 가능 |

<br/>

| 마이페이지 |
| :--------------: |
| <img src="big-project-front/public/images/마이페이지(평가처리 시작).png" width="200"> <img src="big-project-front/public/images/마이페이지(평가 처리중).png" width="200"> |
| <img src="big-project-front/public/images/마이페이지(PDF처리).png" width="200"> <img src="big-project-front/public/images/마이페이지(결과확인).png" width="200"> |
| - 나의 정보 : 회원가입 시 입력했던 정보 확인 가능 <br/>- 분석 및 평가 : 채용 담당자 본인이 등록한 공고에 대한 분석과 평가를 진행 |

<br/>

| 이력서 분석 및 평가 페이지 |
| :--------------: |
| <img src="big-project-front/public/images/이력서 업로드.png" width="200"> <img src="big-project-front/public/images/회사기준 등록중.png" width="200"> |
| - 이력서 업로드 : 지원자들의 이력서 파일을 업로드 <br/>- 평가 항목 입력 : 채용 공고에 대한 평가 항목 기준을 입력하여 평가 점수를 도출할 항목에 대한 자세한 내용 작성 가능 |

<br/>

| 분석 결과 페이지 |
| :--------------: |
| <mg src="big-project-front/public/images/분석결과.png" width="200"> <img src="big-project-front/public/images/평점리스트.png" width="200"> |
| - 본인이 입력한 평가 항목 요소들과 직무 확인 가능<br/> - 지원자 수 통계와 평가 점수 평균 확인 가능 <br/> 지원자들의 평가 기준 별 평가 점수와 지원자 합격 여부 결정 가능 |

<br/>

| 합격자 명단 및 상세 페이지 |
| :--------------: |
| <img src="big-project-front/public/images/합격명단.png" width="200"> <img src="big-project-front/public/images/지원자 상세페이지.png" width="200"> <img src="big-project-front/public/images/지원자 질문.png" width="200"> |
| - 합격자 명단 : 평점 및 개인의 평가 항목 별 분석 내용 확인 가능 <br/>- 면접 질문 : AI 모델을 통해 개인의 이력서를 분석해 개인별 맞춤 면접 질문을 생성 |


<br/>

| 게시판 |
| :--------------: |
| <img src="big-project-front/public/images/게시글 생성.png" width="200"> <img src="big-project-front/public/images/게시글 생성창.png" width="200"> |
| <img src="big-project-front/public/images/게시판 댓글.png" width="200"> <img src="big-project-front/public/images/게시판 댓글 작성.png" width="200"> |
| - 사내 커뮤니티 게시판으로 공지 및 글, 댓글 crud 가능<br/>- 글 작성 : 본인 글만 수정 및 삭제 가능<br/>- 댓글 작성 : 본인 댓글만 수정 및 삭제 가능<br/> |

<br/>
