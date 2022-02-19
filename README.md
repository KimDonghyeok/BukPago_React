# 북파고 | BukPago

> ### 본 레포지토리는 북파고 프로젝트의 프론트엔드 레포지토리입니다.
> ### 현재 백엔드 서버는 작동하지 않고 있으므로 서버와의 통신은 불가능 합니다.
> ### 아래의 실행방법을 참고하여 브라우저에서 프론트엔드만 시연이 가능합니다.
<br>

- [북파고 | BukPago](#북파고--bukpago)
  - [개요](#개요)
  - [지원기능](#지원기능)
- [Screenshots](#screenshots)
- [실행방법](#실행방법)
- [서버 레포지토리](#서버-레포지토리)

## 개요

북파고는 금오공과대학교 2021년 여름방학 ~ 2학기동안 컴퓨터소프트웨어공학과 전공설계과목인 창의융합설계2의 일환으로 진행된 프로젝트입니다.

Transformer 구조를 이용한 기계번역으로 북한어를 남한어로 자연스럽게 변환하는 것을 목표로 하고있으며 제공되는 기능들을 통해 다양한 방법으로 변환을 지원합니다.

## 지원기능

- Plain-text 를 이용한 일반텍스트 변환

  - Transformer 구조를 이용한 변환

  - 맞춤법 검사를 이용한 변환

- 로컬 .txt 파일을 업로드 하여 변환하는 파일번역

- 북한말과 1:1 도 대치되는 남한말을 검색할 수 있는 북한말 사전

- Transformer 모델의 성능향상을 위해 변환 문장을 평가

# Screenshots

![bukPagoMain](https://user-images.githubusercontent.com/47496422/124358652-36d59100-dc5c-11eb-98b4-2b3193f68de4.png)
![bukPagoFile](https://user-images.githubusercontent.com/47496422/124358663-41902600-dc5c-11eb-9a9b-8b65648de2af.png)
![bukPagoTrain](https://user-images.githubusercontent.com/47496422/124358662-3fc66280-dc5c-11eb-9a52-9b979828f28f.png)

# 실행방법

> ### _node.js 최신 LTS 버전이 필요합니다. ( require latest node.js LTS version )_

1. clone the repository
   ```shell
   git clone https://github.com/KimDonghyeok/BukPago_React.git
   ```

2. change directory to project folder
   ```shell
   cd BukPago_React
   ```

3. install node_modules
   ```shell
   npm install
   ```

4. start react project
   ```shell
   npm start
   ```

# 서버 레포지토리

> ### https://github.com/Blackstarez/bukpago_server  

시연 시 서버는 local_host:12050 으로 열어서 실행해야 합니다.  
`python manage.py runserver 12050` 명령어로 실행해주세요.  
자세한 것은 서버 레포지토리를 참고
