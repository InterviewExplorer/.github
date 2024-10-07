# 🕴️InterviewExplorer
심화_생성형 AI활용 인재양성과정 (조별멘토) 2회차 파이널 프로젝트 입니다.
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

## 👨‍🏫프로젝트 소개
#### 저희 InterviewExplorer은(는) 첨단 AI 기술을 활용하여 면접 준비의 패러다임을 변화시키는 혁신적인 가상 면접 플랫폼입니다.
#### 단순한 모의 면접을 넘어서, AI가 직접 여러분의 면접 준비를 분석하고 개인 맞춤형 피드백을 제공합니다.
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

면접 준비가 어렵고 지루하게 느껴지셨나요?</br>
단순히 준비하는 것만으로는 부족하고, 실전 같은 연습이 필요하다고 느끼셨나요?</br>
이제 AI가 함께하는 면접 준비의 새로운 시대가 열립니다!
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

<div style="padding: 20px; font-family: Arial, sans-serif;">
  <h2>🕰️ 개발기간</h2>
  <p><strong>2024.08.23 ~ 2024.10.14</strong></p>
  <ul style="list-style-type: none; padding: 0;">
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.08.21 ~ 23:</span> 아이디어 기획
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.08.23 ~ 29:</span> 자료 조사
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.08.26 ~ 30:</span> 역할 분담
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.08.26 ~ 10.04:</span> 개발
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.08.27:</span> 기획 발표
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.08.30 ~ 09.03:</span> 면접관 추가
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.09.06 ~ 10.04:</span> 고도화 작업
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.09.13:</span> 중간 발표
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.09.07 ~ 10.13:</span> 테스팅, 로깅, 디버깅
    </li>
    <li style="margin-bottom: 10px;">
      <span style="font-weight: bold;">2024.10.14:</span> 발표
    </li>
  </ul>
</div>
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

## 🧑‍🤝‍🧑팀원 소개 및 담당 기능

<div>
  <table border="1" style="width: 100%; border-collapse: collapse;">
    <thead>
      <tr>
        <th style="text-align: center;">역할</th>
        <th style="text-align: center;">이름</th>
        <th style="text-align: center;">담당 기능</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;">팀장</td>
        <td style="text-align: center;"><a href="https://github.com/LXXDJ">이다정</a></td>
        <td>
          1. STT(Whisper-medium)로 영상에서 면접자의 답변을 텍스트로 추출<br>
          2. RAG(Elasticsearch)로 최신 기술 및 이슈에 대한 질문 생성 및 답변 평가<br>
          3. Prompt Engineering & LLM(GPT-4o mini)으로 맞춤형 답변 평가 및 이력서별 요약 정보 추출
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">팀원</td>
        <td style="text-align: center;"><a href="https://github.com/KUYESUNG">구예성</a></td>
        <td>
          1. LLM(GPT-4o mini)을 이용한 기본 기술 질문 및 이력서 기반 질문 생성
          2. RAG(Retrieval-Augmented Generation)을 이용해 생성된 최신 뉴스 기반 질문 및 기본 질문에 대한 꼬리 질문 생성
          3. OpenCV + MediaPipe를 이용한 면접 시작전 캠 가이드 제작
          4. 마이크 테스트 기능 제작
          5. Selenium + Scheduler를 이용한 동적 사이트 크롤링 자동화 데이터 파이프라인 구축
          6. 면접관(ver) 이력서 전처리후 저장 및 이력서별 요약 정보 추출
        </td>
      </tr>
      <tr>
        <td style="text-align: center;">팀원</td>
        <td style="text-align: center;"><a href="https://github.com/duri22">김아연</a></td>
        <td>(기능 내용 추가)</td>
      </tr>
      <tr>
        <td style="text-align: center;">팀원</td>
        <td style="text-align: center;"><a href="https://github.com/sunguh0904">성우현</a></td>
        <td>
          1. MediaPipe Pose를 사용하여 영상에서 사용자의 포즈를 추적하고 피드백 생성<br>
          2. LLM(OpenAI)과 Elasticsearch를 사용해 RAG 기법과 하이브리드 서치 방식으로 최신 뉴스의 인성 면접 질문 생성 및 평가<br>
          3. 기본적으로 LLM(OpenAI)을 활용해 기본 인성 질문 생성
        </td>
      </tr>
    </tbody>
  </table>
</div>
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

## 📚Stacks

<div>
  <table border="1" style="width: 100%; border-collapse: collapse;">
    <thead>
      <tr>
        <th style="text-align: center;">Category</th>
        <th style="text-align: center;">Skills</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;"><strong>FrontEnd</strong></td>
        <td style="text-align: center;">
          HTML5, CSS3, JavaScript
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>FrontEnd Library</strong></td>
        <td style="text-align: center;">
          React.js
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>BackEnd Framework</strong></td>
        <td style="text-align: center;">
          FastAPI
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>Server</strong></td>
        <td style="text-align: center;">
          Uvicorn
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>Build Tools</strong></td>
        <td style="text-align: center;">
          Node.js (NPM)
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>Database</strong></td>
        <td style="text-align: center;">
          Elasticsearch
        </td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>Machine Learning Models</strong></td>
        <td style="text-align: center;">
          Whisper (STT), LLM (OpenAI), GPT-4o-mini
        </td>
      </tr>
    </tbody>
  </table>
</div>
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// -->

## ⚙️개발 환경

<div>
  <table border="1" style="width: 100%; border-collapse: collapse;">
    <thead>
      <tr>
        <th style="text-align: center;">항목</th>
        <th style="text-align: center;">내용</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: center;"><strong>운영체제 (OS)</strong></td>
        <td style="text-align: center;">Windows, macOS</td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>개발도구</strong></td>
        <td style="text-align: center;">VS Code (Visual Studio Code), Git, GitHub, Notion</td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>환경 & 패키지 관리도구</strong></td>
        <td style="text-align: center;">Miniforge, Conda</td>
      </tr>
      <tr>
        <td style="text-align: center;"><strong>하드웨어 가속기</strong></td>
        <td style="text-align: center;">GPU (NVIDIA CUDA)</td>
      </tr>
    </tbody>
  </table>
</div>
