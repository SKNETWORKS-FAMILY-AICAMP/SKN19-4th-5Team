<div align="center" style="color: #A6C1A6;">

<h1><i><b>PLANNY</b></i></h1>
<img width="250" height="250" alt="icon2" src="https://github.com/user-attachments/assets/e5fad781-ba6c-4ecf-9209-c2011e576cff" />
<br>
<i>무인화원 AI 서비스</i>
</div>

<br>

## We are

<table>
  <tr>
    <td align="center"><a href="https://github.com/sosodoit"><img src="https://avatars.githubusercontent.com/sosodoit" width="150px;" alt="">
    <td align="center"><a href="https://github.com/deneb784"><img src="https://avatars.githubusercontent.com/deneb784" width="150px;" alt="">
    <td align="center"><a href="https://github.com/ahnsui"><img src="https://avatars.githubusercontent.com/ahnsui" width="150px;" alt="">
    <td align="center"><a href="https://github.com/ChocolateStrawberryYumYum"><img src="https://avatars.githubusercontent.com/ChocolateStrawberryYumYum" width="150px;" alt="">
    <td align="center"><a href="https://github.com/myem21"><img src="https://avatars.githubusercontent.com/myem21" width="150px;" alt="">
  </tr>
  <tr>     
    <td align="center"><strong>AI 서비스 기획</strong></td>
    <td align="center"><strong>AI/LLM 모델 개발</strong></td>
    <td align="center"><strong>AI/LLM 모델 개발</strong></td>
    <td align="center"><strong>UI 개발</strong></td>
    <td align="center"><strong>LLM 성능 평가</strong></td>
  </tr>
  <tr>
    <td align="center"><strong>김소희</strong></td>
    <td align="center"><strong>박준영</strong></td>
    <td align="center"><strong>안수이</strong></td>
    <td align="center"><strong>이상민</strong></td>
    <td align="center"><strong>정종현</strong></td>
  </tr>
    <tr>
    <td align="center"><a href="https://github.com/sosodoit"><b>@sosodoit</b></td>
    <td align="center"><a href="https://github.com/deneb784"><b>@deneb784</b></td>
    <td align="center"><a href="https://github.com/ahnsui"><b>@ahnsui</b></td>
    <td align="center"><a href="https://github.com/jjoggoddalgi"><b>@jjoggoddalgi</b></td>
    <td align="center"><a href="https://github.com/myem21"><b>@myem21</b></td>
  </tr>
</table>
<br>
  
| 이름     | 담당 업무 |    
|----------|-----------|    
| 김소희 | 전체 서비스 기획 및 총괄 / QnA 데이터 수집 및 로직 구현/ Vector DB 및 RAG 시스템 구축 / TTS-STT 시스템 구현 |
| 박준영 | LangGraph 기획 및 구현 / 데이터 색상 추출 및 병합 / 합성 이미지 생성 / 사용자 정보 수집 로직 구현 / 비동기 로직 구현 |    
| 안수이 | 추천 데이터 수집 및 로직 구현 / Vector DB 및 RAG 시스템 구축 / 이미지 유사도 계산 / 서버 구성 및 배포 |    
| 이상민 | 사용자 응답 정량화 / RAG 및 QnA 예상 응답–실제 응답 분석 / 사용자 정보 수집 로직 구현 / UI 구현 /  |    
| 정종현 | 사용 시스템 및 기존 서비스 조사 / 데이터셋을 이용한 테스트 / 응답 비교 |    

<br><br>


## Introduction
**Planny**는 단순히 식물을 추천하는 챗봇이 아니라, **'플랜테리어'**에 초점을 둔 인테리어를 기반으로 한 식물 추천과 식물의 관리에 관한 상담까지 통합하여 제공하는 무인화원 컨셉의 AI 서비스입니다.

<img width="1918" height="862" alt="page1" src="https://github.com/user-attachments/assets/389ddf01-347c-47fd-9db7-8acc96967d32" />


## 서비스의 배경과 목표
### 플랜테리어 트렌드
<br>
<div align="center"> 
<img src="https://github.com/user-attachments/assets/f7a5a87f-98c8-4d62-9342-0126b2b33cd9" width="33%" alt="플랜테리어 1" style="float: left; margin: 0; padding: 0;" />
<img src="https://github.com/user-attachments/assets/8168da8a-6099-4ea5-a45d-d61e8f76eefc" width="33%" alt="플랜테리어 2" style="float: left; margin: 0; padding: 0;" />
<br style="clear: both;" /> 
</div>

<br>

### 반려식물 시장 규모 증가
<br>
<div align="center"> 
<img src="https://github.com/user-attachments/assets/e5d46340-e188-4a70-bb37-36336ddfbd88" width="33%" alt="플랜테리어 2" style="float: left; margin: 0; padding: 0;" />
<img src="https://github.com/user-attachments/assets/0e4a788f-5433-42dc-86d9-524ba057c606" width="33%" alt="플랜테리어 2" style="float: left; margin: 0; padding: 0;" />
<br style="clear: both;" /> 
</div>

<br>

<div align="center"> 
<img src="https://github.com/user-attachments/assets/d946391d-66ec-401e-9238-9e746c2276aa" width="50%" alt="플랜테리어 3" style="float: left; margin: 0; padding: 0;" />
<br style="clear: both;" /> 
</div>

<br>

#### **'플랜테리어' 소비의 대중화** 
집을 나를 표현하는 공간' 으로 인식하는 소비가 증가하며, 식물을 활용한 플랜테리어(Plant + Interior) 시장이 성장하고 있습니다. 허나 대부분의 매장에서는 우리 집 인테리어에 어울리는 Plant과 같은 감성적인 인테리어 기반의 복합적인 추천과 더불어 구체적인 예시를 제공하지 못합니다.    
Planny에서는 사용자 성향과 상황을 고려하여 이에 최적화된 식물을 추천해주고, 이를 AI 이미지 생성 기술을 통해 보여주어 고객의 만족도와 경험 다양성을 높이고자 하였습니다.

#### **'24시간 식물 주치의'**
식물을 구매하는 소비자의 입장에서, 구매 후 해당 식물을 어떻게 기르고 관리해야 하는지 역시 구매를 결정하는 데에 큰 영향을 미칩니다.    
Planny에서는 '24시간 AI 식물 주치의' 시스템을 통해 반려식물의 생장, 관리법 등에 대한 전문적인 정보를 즉각 제공하고, 구매 후 궁금증을 직원 웞이 24시간 해소하여 고객 만족도를 극대화 하였습니다.

<br><br>

## Our project is

*Repository*

> ⚙️ **[Data Crawling Repository](https://github.com/SKN19-5Team-3rd-4th/data)**
> 데이터 수집
<br>

> ⚙️ **[AI/LLM Repository](https://github.com/SKN19-5Team-3rd-4th/llm)**
> RAG 기반 LLM 질의응답 모델 개발
<br>

> ⚙️ **[Django Repository](https://github.com/SKN19-5Team-3rd-4th/django)**
> Django 기반 UI 및 기능 개발
<br>

> ⚙️ **[Team Notion](https://www.notion.so/5-A-P-T-AI-Plant-Teller-2a989a4c664e8075befbce39a463d80a?source=copy_link)**
> 최종 문서 및 WBS 관리

<br>

>⚙️ **[Excel](https://docs.google.com/spreadsheets/d/13b3qwXVqY04CR4WB1-dZEttGEs4U-OtSjZUon8fjFeM/edit?usp=sharing)**
> 프롬프트 및 LLM 통합테스트
<br>

> ⚙️ **[Team Miro](https://miro.com/app/board/uXjVJsUw2as=/?share_link_id=35194761242)**
> 아이디에이션, 의견 공유, 시각적 산출물 정리

<br>

*collaboration process*
- Notion, Miro 기반의 자유로운 소통과 의견 교환
- Github Issue & Pull Request(PR) & Project & Discussion 을 적극적으로 활용한 체계적인 협업 시스템

<br>

## WBS

![SKN19-3rd-5Team_공유시트 - WBS_4차-이미지-0](https://github.com/user-attachments/assets/245e5a23-b0c8-4757-b01f-83ab86bdf29d)

![SKN19-3rd-5Team_공유시트 - WBS_4차-이미지-1](https://github.com/user-attachments/assets/eab73c3b-0ad2-48ff-bb3e-794914299c0a)

<br><br>

<br><br>

## 기술 스택
<i>본 프로젝트는 Python Langgraph을 기반으로, AI 에이전트 개발에 최적화된 기술 스택을 활용하였습니다.</i>

|구분|라이브러리|
|---|---|
|Language|![Python](https://img.shields.io/badge/python_3.10-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)|
|LLM Framework & Model| ![LangChain](https://img.shields.io/badge/langchain_1.0.8-%231C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/langgraph_1.0.3-%231C3C3C.svg?style=for-the-badge&logo=langgraph&logoColor=white) ![ChatGPT](https://img.shields.io/badge/OPENAI_API_GPT--5.1-74aa9c?style=for-the-badge&logo=openai&logoColor=white) ![HuggingFace](https://img.shields.io/badge/huggingface-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=white)|
|Database|![Static Badge](https://img.shields.io/badge/PINECONE-red?style=for-the-badge) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)|
|Embedding Model| ![ChatGPT](https://img.shields.io/badge/OPENAI_EMBEDDING-gray?style=for-the-badge&logo=openai&logoColor=white)|
|Library|![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)|
|Front & Server| ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) |
|Collaboration Tool|![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Miro](https://img.shields.io/badge/Miro-%23F2CA02.svg?style=for-the-badge&logo=miro&logoColor=black) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)|

*Hugging Face Model*
 - RAG 데이터 Reranking : **[Dongjin-kr/ko-reranker](https://huggingface.co/Dongjin-kr/ko-reranker)**
 - Image Segmentation : **[nvidia/segformer-b0-finetuned-ade-512-512](https://huggingface.co/nvidia/segformer-b0-finetuned-ade-512-512)**

<br><br>

## 시스템 구성도


![3차프로젝트 - (AI 서비스 운영) 시스템 아키텍처 v0 2의 사본](https://github.com/user-attachments/assets/c4080972-6ce0-44b4-977c-0d67de05aedb)



<br><br>

## 요구사항 명세서
<img width="1077" height="758" alt="스크린샷 2025-12-17 오후 12 19 15" src="https://github.com/user-attachments/assets/a9ced845-6115-4d23-8216-2a7a0f271304" />
<img width="1078" height="733" alt="스크린샷 2025-12-17 오후 12 19 30" src="https://github.com/user-attachments/assets/1b371081-d58e-418d-a3d2-14e02cae31c1" />
<img width="1078" height="732" alt="스크린샷 2025-12-17 오후 12 19 38" src="https://github.com/user-attachments/assets/28a82840-2d82-4c03-9191-a00b5c1d26bd" />
<img width="1078" height="732" alt="스크린샷 2025-12-17 오후 12 19 48" src="https://github.com/user-attachments/assets/cc336cc5-5482-4551-920e-bbf6a44b7ceb" />


<br><br>

## 화면 설계서

<img width="1000" alt="화면 설계서" src="#" />
**[화면 설계서](https://docs.google.com/presentation/d/1e-I648hJdcaXPNDTfmSLPdfmDvMyZGAN/edit?usp=sharing&ouid=115443250380758652577&rtpof=true&sd=true)**

<br><br>

## 테스트 계획 및 결과 보고서

<img width="1626" height="703" alt="스크린샷 2025-12-17 오후 3 23 48" src="https://github.com/user-attachments/assets/c886753c-5d44-4160-9720-8f071c5f3106" />
<img width="1627" height="486" alt="스크린샷 2025-12-17 오후 3 23 54" src="https://github.com/user-attachments/assets/238be84d-29d1-4945-8cf7-82cf4d86000b" />


<br><br>

## 수행 결과

<br><br>

<img width="1920" height="3213" alt="index" src="https://github.com/user-attachments/assets/e3d0c3e4-d5d2-4861-9b02-0758d5e1467a" />
<img width="1920" height="3652" alt="ref" src="https://github.com/user-attachments/assets/34dbff27-a6de-438c-bfba-3e0cc386772b" />


<br><br>

## 한줄 회고
- **`김소희`**
> 
- **`박준영`**
> 4차 프로젝트에서 이미지 분석 및 생성, fastapi를 통한 LLM 모델과 프론트 연결을 담당했습니다. 해당 기능의 구현을 위해 전체적인 프론트-백엔드 간의 연결 과정에 대해 공부하며 좋은 코드, 효율적인 코드란 무엇인가에 대하여 돌아볼 수 있었던 프로젝트였습니다.
- **`안수이`**
> fastapi를 이용한 이미지 생성 관련 백엔드 구현과 EC2, Docker, S3, 권한 관리 경험을 통해 웹 서비스의 전체 동작 흐름을 이해할 수 있었다. 화면 설계서를 작성하며 사용자 흐름을 고려한 화면 구성과 실제 구현 간의 연결성을 고민해보는 계기가 되었다.
- **`이상민`**
> 4차 프로젝트에서는 프론트엔드 개발을 담당했습니다. 페이지의 크기가 커질수록, 그리고 js를 다룰 때마다 어려움이 있었지만 각각의 디자인 항목을 어떻게 바꾸는지 하나하나 직접 찾아가보며 페이지의 완성도가 높아지는 것은 성취감이 느껴겼습니다.  자신감이 생겨서 다음에 기회가 된다면 백엔드도 도전해보고 싶습니다.
- **`정종현`**
> 



