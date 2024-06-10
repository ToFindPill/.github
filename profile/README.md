# ToFindPill

## 프로젝트 소개
**ToFindPill**는 의료진이 환자의 복약 상태를 신속하고 정확하게 파악할 수 있도록 돕는 모바일 애플리케이션입니다. 이 앱은 약물 인식과 관련 정보를 제공하여 의료 서비스의 효율성과 정확성을 크게 향상시키는 것을 목표로 하고 있습니다.

## 목차
- [프로젝트 소개](#프로젝트-소개)
- [기능](#기능)
- [시스템 아키텍처](#시스템-아키텍처)
- [설치 방법](#설치-방법)
- [사용 방법](#사용-방법)
- [모든 산출물 및 URL](#모든-산출물-및-url)
- [기여 방법](#기여-방법)
- [MyYak 팀 소개](#myyak-팀-소개)

## 기능
- **약물 이미지 인식**: 사용자가 촬영한 약물 이미지를 분석하고, 관련 정보를 실시간으로 제공
- **약물 정보 제공**: 약물의 성분, 복용 방법, 부작용 등 상세한 정보를 제공
- **사용자 인터페이스**: 직관적이고 사용하기 쉬운 모바일 애플리케이션 인터페이스
- **데이터 저장**: 인식된 약물 정보와 사용자 히스토리를 데이터베이스에 안전하게 저장

## 시스템 아키텍처
ToFindPill은 다음과 같은 주요 구성 요소로 이루어져 있습니다:

- **Frontend**: 사용자가 약물 사진을 촬영하고 결과를 확인하는 모바일 애플리케이션
- **Backend**: Node.js 서버가 클라이언트로부터 데이터를 받아 분석하고, 결과를 반환
- **Model Server**: YOLO VISION을 이용한 약물 이미지 분석 및 인식
- **Database**: MongoDB를 사용하여 사용자 정보와 약물 인식 결과를 저장


![System Architecture](https://github.com/ToFindPill/images/system.png)

## 설치 방법
1. **Node.js 설치**: [Node.js](https://nodejs.org) 웹사이트에서 설치.
2. **MongoDB 설치**: [MongoDB](https://www.mongodb.com) 웹사이트에서 설치.
3. **리포지토리 클론**:
    ```bash
    git clone https://github.com/your-repo/ToFindPill.git
    cd ToFindPill
    ```
4. **필요한 패키지 설치**:
    ```bash
    npm install
    ```

## 사용 방법
1. **애플리케이션 시작**:
    ```bash
    npm start
    ```
2. **모바일 디바이스에서 ToFindPill 앱 다운로드 및 설치**.
3. **앱 실행 및 약물 사진 촬영**.
4. **결과 화면에서 인식된 약물 정보를 확인**.

## 모든 산출물 및 URL
- **Notion 페이지**: 모든 산출물은 [Notion](https://acelab-welcome-docs.notion.site/93af934c5e3a40d9a3a321c4cd68e47f?pvs=4)에서 확인할 수 있습니다.
- **최종산출물.zip**: 교수님의 피드백을 반영하여 한 학기 동안 제출한 수정된 산출물 [다운로드](https://acelab-welcome-docs.notion.site/93af934c5e3a40d9a3a321c4cd68e47f?pvs=4).
- **JIRA**: 프로젝트 타임라인과 작업 현황을 확인할 수 있는 [JIRA 페이지](https://hanyang-team-myyak.atlassian.net/jira/software/projects/TFP/boards/1/timeline).
- **GitHub**: 프로젝트 소스 코드는 [GitHub 리포지토리](https://github.com/ToFindPill)에서 확인 가능합니다.
- **API 문서**: Postman에서 API 문서를 [확인](https://documenter.getpostman.com/view/35312530/2sA3XJkQGG#af7bf4fd-8223-46b8-b159-9cee17417e38)할 수 있습니다.
- **시연 영상**: ToFindPill의 데모 영상은 [여기](https://drive.google.com/file/d/1vfltQ23fjjwnockom5ljljJHykYkm9DI/view?usp=drive_link)에서 확인할 수 있습니다.

## 기여 방법
ToFindPill 프로젝트에 기여하려면 다음 절차를 따라주세요:

1. **포크(Fork) 리포지토리**.
2. **새로운 브랜치 생성**:
    ```bash
    git checkout -b feature/새로운기능
    ```
3. **변경 사항 커밋**:
    ```bash
    git commit -m "새로운 기능 추가"
    ```
4. **브랜치 푸시**:
    ```bash
    git push origin feature/새로운기능
    ```
5. **Pull Request 생성**.
## MyYak 팀 소개
MyYak 팀은 의료 기술 혁신을 목표로 하는 열정적인 개발자 그룹입니다. 우리의 목표는 최신 기술을 이용하여 의료진의 업무를 효율화하고, 환자들의 복약 관리에 도움을 주는 것입니다.

- **강민재** - 
- **김나현** - 
- **지훈** - 
- **이정민** -



