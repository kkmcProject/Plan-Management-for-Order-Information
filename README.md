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
      <td align="center"><img width="300" height="500" src="https://github.com/user-attachments/assets/31e3ee0d-0f70-410a-98b1-b4355e5359d3" style="max-width: 100%;"></img></td>
      <td align="center"><img width="300" src="https://github.com/user-attachments/assets/9a90b925-ce5f-4293-8b6c-c0af04f1f042" style="max-width: 100%;"</img></td>
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
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/f924fc09-880c-4e03-8827-5be28209c72f" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/user-attachments/assets/bc71e6b1-1071-432d-ad6a-efc9f5777704" style="max-width: 100%;"</img></td>
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
      <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/dbcec6cf-9a41-4d06-a5ec-6b980bf2af01" style="max-width: 100%;"></img></td>
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
      <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/af45eb1a-99d8-4546-96d2-47bf8d3afaad" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/3d482c85-9dee-4c07-bbbc-6698b19cbdf4" style="max-width: 100%;"</img></td>
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
      <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/21214958-c034-47b4-9632-50e1c61e98bd" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/8e3cc507-683f-4f56-bf04-2f6bc2c627f7" style="max-width: 100%;"</img></td>
    </tr>
  <tr>
    <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/61892533-d57f-40c2-907d-7277f29f74b5" style="max-width: 100%;"></img></td>
    <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/ef3b4a23-299c-4510-8653-450ba3a3849c" style="max-width: 100%;"</img></td>
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
      <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/da4b6064-1222-4d5f-9f49-2dad6fddebf9" style="max-width: 100%;"></img></td>
      <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/2517dd95-8fe1-4341-afce-d91cbc2279d6" style="max-width: 100%;"</img></td>
    </tr>
  <tr>
    <td align="center"><img width="400" src="https://github.com/kkmcProject/Web/assets/132376178/541d038b-e68e-486c-a6c6-cc782a4e5c40" style="max-width: 100%;"></img></td>
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
      <td align="center"><img width="380" src="https://github.com/kkmcProject/Web/assets/132376178/9e2ec1c8-1cdd-4177-aa1c-864cec43861e" style="max-width: 100%;"></img></td>
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
      <td align="center"><img width="350" src="https://github.com/kkmcProject/Web/assets/132376178/f9b2aabb-3acf-420c-86e9-3ff7fbf6484c" style="max-width: 100%;"></img></td>
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
본 프로젝트는 KKMC 영농조합법인 및 전북대학교 김진수 교수님의 협력과 팀원들의 노고로 완성되었습니다. 감사합니다."
