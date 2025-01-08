# 수주 정보 작업계획서 관리 시스템

### 팀명: 삼총사

## 개발 기간
2023.03.15 ~ 2023.05.24
<br/><br/>

## 웹 개발팀 소개
<table>
    <thead>
    <tr>
      <th align="center">웹 개발</th>
      <th align="center">프로젝트 총괄</th>
      <th align="center">자동화 알고리즘 구현</th>
      <th align="center">웹 디자인 및 UI 구현</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/ldh-dodo"><img src="https://avatars.githubusercontent.com/u/132376178?s=400&u=2fb03475b074231cf400fd228d572339b95003da&v=4" width="100px;" alt=""/><br /><sub><b> 이도현(Raccoon) </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/hsb0628"><img src="https://github.com/hsb0628.png" width="100px;" alt=""/><br/><sub><b> 홍성빈 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/nahcooy"><img src="https://github.com/nahcooy.png" width="100px;" alt=""/><br/><sub><b> 최유찬 </b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/KaiserLine"><img src="https://github.com/KaiserLine.png" width="100px;" alt=""/><br/><sub><b> 하태성 </b></sub></a><br /></td>
    </tr>
  </tbody>
</table>
<br/>


## 📚 STACKS

<div align=center> 
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> 
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <br>
</div>
<br/>

### 프로젝트 소개
\"수주 정보 작업계획서 관리 시스템\"은 키위와 고구마 같은 과실류를 전문적으로 유통하는 KKMC를 위한 작업계획서 생성, 관리 및 조회 과정을 간소화하는 것을 목표로 합니다.

### 기업 소개
KKMC는 과실류 도매를 전문으로 하는 영농조합으로, 주로 키위와 고구마를 구매, 가공, 유통하는 회사입니다.

### 기존 작업 방식
기존에는 수주 정보를 관리하기 위해 각 반별 작업 계획서를 수기 또는 엑셀 파일로 작성하였습니다.

### 기존 방식의 문제점
- 생산 누락 및 작업 중복 등으로 인한 업무 차질
- 각 작업반별 업무 불균형으로 인한 작업자 불만 증가
- 즉각적인 대응이 어려워 작업 지연 발생
- 수기 작성으로 인한 데이터 누락, 중복, 훼손 문제

### 프로젝트 요구사항 및 목표
- 기존 방식과 동일한 방향으로 작업 계획서 자동 생성 프로그램 개발
- 데스크탑, 핸드폰, 태블릿 PC 등 다양한 기기에서 사용 가능해야 함 -> PWA 도입
<table>
    <thead>
    <tr>
      <th colspan="2" align="center">
        PWA 앱
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="300" height="500" src="https://github.com/user-attachments/assets/89478b9c-25a4-458c-a7d1-9e9bac2df6db" style="max-width: 100%;"></img></td>
      <td align="center"><img width="300" src="https://github.com/user-attachments/assets/be1d2492-5ab6-4590-ad45-36b3540d459f" style="max-width: 100%;"</img></td>
    </tr>
</table>
- 사용자 친화적인 UI/UX 제공 -> 반응형 레이아웃을 통해, 모바일에서 조금이라도 더 편한 환경 제공

<table>
    <thead>
    <tr>
      <th colspan="2" align="center">
        반응형 레이아웃 구성
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/6fef0457-8ce6-48fa-b000-4858202b7beb" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/867f47fc-9270-4e33-ae24-9580b9af606e" style="max-width: 100%;"</img></td>
    </tr>
</table>

- 데이터 저장 및 열람 기능 강화

### 시스템 기능
#### 알고리즘
작업계획서 자동 생성을 위한 알고리즘 구현

#### 웹 기능
작업계획서 관리 및 조회를 위한 웹 기능 구현

#### 로그인 및 회원가입
안전한 시스템 사용을 위한 로그인 및 회원가입 기능

#### 작업계획서 관리
작업계획서 생성, 수정, 조회 기능 제공

# 화면 구성

<table>
  <thead>
    <tr>
      <th align="center">로그인 및 회원가입 페이지</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/45646864-a0ac-4600-803e-3fb726456e97" style="max-width: 100%;"></img></td>
    </tr>
</table>

<table>
    <thead>
    <tr>
      <th colspan="2" align="center">
        작업 계획서 생성 페이지
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/d0dd9094-5974-40b2-b1d8-1bfe24ad8745" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/13caa088-097c-4df2-b54e-e47489e48b78" style="max-width: 100%;"</img></td>
    </tr>
</table>

<table>
    <thead>
    <tr>
      <th colspan="2" align="center">
        작업 계획서 수정 페이지
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/dc770f9c-3170-411d-a00b-db340341ee65" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/0bff74e2-5700-4236-b1f1-e513c5f92050" style="max-width: 100%;"</img></td>
    </tr>
  <tr>
    <td align="center"><img width="400" src="https://github.com/user-attachments/assets/5d7509d5-76f5-4fca-93bb-2f9fb29b5335" style="max-width: 100%;"></img></td>
    <td align="center"><img width="400" src="https://github.com/user-attachments/assets/9509b8c4-badf-4148-8386-18687ff19f6b" style="max-width: 100%;"</img></td>
  </tr>
</table>

<table>
    <thead>
    <tr>
      <th colspan="2" align="center">
        작업 계획서 보기 페이지
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/1414f58b-ea37-4d6b-bb8b-76c144b55e77" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/fa20ec6b-2671-4668-9cd4-671f740ec55e" style="max-width: 100%;"</img></td>
    </tr>
  <tr>
    <td align="center"><img width="400" src="https://github.com/user-attachments/assets/aeb29d5b-ff53-421d-8403-012f0b117e3a" style="max-width: 100%;"></img></td>
  </tr>
</table>

<table>
    <thead>
    <tr>
      <th align="center">
        직원 프로필 수정 페이지
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="380" src="https://github.com/user-attachments/assets/74d9a002-d230-4943-96c8-e90eb038724b" style="max-width: 100%;"></img></td>
    </tr>
  <tr>
  </tr>
</table>

<table>
    <thead>
    <tr>
      <th align="center">
        직원 권한 수정 페이지(어드민 권한에 한정)
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img width="350" src="https://github.com/user-attachments/assets/138ca472-60f7-42b6-a9b1-f5e359de9db5" style="max-width: 100%;"></img></td>
    </tr>
  <tr>
  </tr>
</table>

### 기대효과와 발전 가능성
- 작업 계획서 작성 및 관리의 효율성 증가
- 작업 데이터의 정확성 및 보존성 향상
- 다양한 기기에서 접근 가능하여 작업 편의성 증대

### 실행시 유의사항
- 데모 버전이기 때문에, password 해쉬 및 SQL 인젝션 등 보안 상 고려되지 않은 부분이 많습니다. 따라서, 평상시 사용하는 ID 및 Password로 접속하지 않는 것을 '강력히' 권장합니다.

### 배포 URL
- https://kkmc.vercel.app/
    
### 감사의 말
본 프로젝트는 KKMC 영농조합법인 및 전북대학교 김진수 교수님의 협력과 팀원들의 노고로 완성되었습니다. 감사합니다.
