# Awesome Backend [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](./LICENSE)

A curated list of awesome **Backend** frameworks and resources

All kinds of contributions(from single typos to large improvements) is welcomed! Just send a [new **pull request**](https://github.com/junhoyeo/awesome-backend/pull/new/master).

Most of the contents of this repo will prefer to be written in English because I want to see this repo famous for overseas someday! 👍👍👍
~~But since I can't speak English that much, I guess I'll use Korean for some sections.~~

# 🔙 Backend?
Backend means the data access layer of an application. 

Most of the core operating logic and data handling happens here; Such as managing authentication, interacting with the database or other services, and providing API to communicate with the client(which can be the frontend app).

# 📌 My goal & Roadmap
I made this repository to self-study more about backend development and to gain insight into trendy new frameworks and technologies. Also, I hope someone will see this useful when he/she begin to study backend too.

The overall goal of my life is contributing to the world in any kind; That's why I'm using GitHub - My projects are not that great, but I saw that some people can still find them helpful in any way. Idea, joy or my code or something.

<img alt="woowabros" src="./logos/woowabros.png" width="60%">

> One of my dreams is to work in Woowabros as a server/backend developer ~~or serve as an alternative for Korean military services~~. 

By the way, `Woowa` means `elegant` or `delicate`.

## 🌱 What kind of developer should I be?
현재 [우아한형제들의 개발직군 채용공고](https://www.woowahan.com/#/recruit/tech)를 보면, 우아한형제들이 원하는 개발자의 모습에 대해 알 수 있습니다.

### 우아하기 위해 노력하는 개발자
> 끊임 없이 노력하는 사람

저는 **트렌디한 개발자**가 되고 싶습니다. 트렌디한 개발자는 계속 쏟아져 나오는 기술들을 보다 빠르게 습득하고 활용할 수 있는 능력을 가진 개발자입니다. 물론 기초 없이 얉은 지식만으로 유행만을 쫓는 사람이 되고 싶지는 않습니다. 깊고 넓게, 유연하게 배우고 싶습니다. ~~그게 쉽냐~~

최근에 저는 교내 인트라넷 서비스 [디미고인](https://github.com/dimigoin/dimigoin-front)에서 프론트엔드 개발자로 일하게(?) 되었습니다.
디미고인은 이슈 중심으로 프로젝트가 관리되고 있습니다. 새로운 기능이나 버그 패치가 필요해질 때 이슈를 만들고 개인별로 할당한 뒤 PR을 올리는 방식입니다.
PR이 Merge되려면 1명 이상의 다른 개발자에게 Approve를 받아야 합니다. 다른 사람에게 코드를 리뷰 받고, 타인의 코드를 리뷰하는 과정에서 새로운 문법이나 설계에 대해서도 배우게 되고 네이밍부터 커밋 메세지까지 여러 가지 고민을 하게 됩니다.

사실 초반에는 `와, 고작 이 정도 바꾸는데 리뷰까지 받아야 해?`라는 생각이 들었지만, 이런 개발 프로세스가 양질의 코드를 양산하고 이슈 관리를 체계적으로 할 수 있게 해줌으로서 결국은 막 받는 것보다 더 효율적으로 프로젝트를 관리할 수 있게 해준다는 것을 알게 되었습니다. 생각보다 유연하게 처리하는 부분도 많이 있었고요.

이렇게 코드 품질을 중요하게 여기면서도 최신 트렌드를 반영하려는 노력을 하는 디미고인의 선배님들이야말로 진짜 트렌디한 개발자라고 할 수 있을 것 같습니다. 저도 현재 상황에 만족하고 안도하지 않고 끊임없이 고민하며 코드를 더 발전시켜 나가려고 노력하려는 자세를 가져야겠습니다.

입학 과제로 [**코딩을 지탱하는 기술** - 니시오 히로카즈](http://www.yes24.co.kr/Product/goods/11101558)라는 책을 읽은 적이 있습니다. 책에서는 Programming Perl의 저자 래리 윌(Larry Wall)이 말한 프로그래머의 3대 미덕(나태, 조바심, 자만심)을 인용했습니다. 물론 긍정적인 자세로 프로그래머가 지녀야 할 자세에 대해서 말하려는 것입니다. 그 중 첫 번째 미덕인 `나태`에 초점을 맞춰 봅시다. 프로그래머가 진정으로 나태하다면 **우아하기 위한 노력**을 할 수 없을 것입니다. 여기서의 나태는 `전체의 노력을 줄이기 위해 수고를 아끼지 않는 기질`을 말합니다. 코드 중복을 최소화하기 위해 컴포넌트를 만들어 재사용하고, 귀찮은 작업을 자동화하고, 결국 언젠가는 한꺼번에 업데이트해야 하기에 최신 트렌드를 따라 끊임없이 프로젝트를 유지보수하는, **발전하느라 바쁜** 부지런한 사람을 말하는 것이 아닐까 합니다.

개인 프로젝트를 진행하다가도 고치기 어려워 보이는 것, 구현하기 힘들어 보이는 것이 있으면 괜히 슬럼프라도 오는 것처럼 하기 싫어져 미루게 되는 경우가 있지만 실제로 마음을 굳게 먹고 **일단 시작하면** 생각보다 잘 되면서 금방 끝나는 경우가 많았습니다. 이런 느낌이 반복되면 좀 줄어들긴 할 것 같지만, 거부감이 든다고 해서 무작정 일을 미루는 습관을 고치도록 노력해야 하긴 해야 할 것 같습니다.

### 코드가 아닌 가치를 만드는 개발자
> 기술보다, 그 가치를 생각하고 구현하기 위해 노력하는 사람

### 우아한 형제/자매들
> 협력을 통해서 더한 가치를 만들 수 있는 사람

## 📖 What should I study more?
서버 개발자의 지원자격은 아래와 같습니다.

- [x] Git 사용 경험
- [x] 기본적인 Linux/Unix 사용 가능자 
- [ ] Java에 익숙하고 기타 언어 하나 이상을 습득한 사람
- [ ] Spring Boot를 이용한 웹 애플리케이션 개발 경험
- [ ] MVC framework 기반의 웹 서비스나 API 개발 경험
- [ ] RDBMS 경험
- [ ] CI/CD 자동화 경험
- [ ] 객체지향 개발 및 테스트 코드 작성 숙달자

# 📚 Contents
- [Frameworks](#frameworks)
  - [Python](#python): Awesome Backend frameworks in Python
  - [JavaScript](#Javascript): Awesome Backend frameworks in JavaScript
- [API documentation](#api-documentation)
- [DevOps](#devops)

# Frameworks

## Python
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://github.com/vinta/awesome-python)

### [Flask](https://github.com/pallets/flask)
<img alt="flask logo" src="./logos/flask.png" width="30%">

> The Python micro framework for building web applications.

#### Extensions
- flask-common
- flask-cors
- flask-jwt-extended
- flask-pymongo
- flask-restplus

#### PyTest

### [Sanic](https://github.com/huge-success/sanic)
<img alt="sanic logo" src="./logos/sanic.png" width="30%">

> Build fast. Run fast.

#### PyTest

### [Django](https://github.com/django/django)
> The Web framework for perfectionists with deadlines.

### Books
- [**파이썬 핵심 개발자들과의 인터뷰** - 마이크 드리스콜](http://www.yes24.com/Product/goods/67340568) (Python Interviews: Discussions with Python Experts by Michael Driscoll), 2019
- [**플라스크 웹 개발** - 미구엘 그린버그](http://www.yes24.com/Product/Goods/30669136) (Flask Web Development by Miguel Grinberg), ~~2014~~ 2018

### Resources
- [**백엔드가 이정도는 해줘야 함**(조민규)](https://velog.io/@city7310/series/백엔드가-이정도는-해줘야-함)

## JavaScript
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://github.com/sorrycc/awesome-javascript)

### [Express](https://github.com/expressjs/express)
> Fast, unopinionated, minimalist web framework for Node.js

### [NestJS](https://github.com/nestjs/nest)
<img alt="nestjs logo" src="./logos/nestjs.svg" width="30%">

> A progressive Node.js framework for building efficient, reliable and scalable server-side applications.

## Java
[![forthebadge](https://forthebadge.com/images/badges/made-with-java.svg)](https://github.com/akullpp/awesome-java)

### Spring Boot
<img alt="spring-boot logo" src="./logos/spring-boot.png" width="30%">

> Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run".

### Books
- [**처음 배우는 스프링 부트 2**(김영재)](http://www.yes24.com/Product/goods/64584833), 2018

# API Documentation
Specification and tools, services to provide better API documentation.

## [OpenAPI](https://github.com/OAI/OpenAPI-Specification)

## [Swagger](https://swagger.io/)
<img alt="swagger logo" src="./logos/swagger.svg" width="30%">

## [GitBook](https://legacy.gitbook.com/)
<img alt="gitbook logo" src="./logos/gitbook.png" width="30%">

# DevOps

## Docker
<img alt="docker logo" src="./logos/docker.png" width="30%">

> Build, Share, and Run Any App, Anywhere. 

## Continuous Integration

### TravisCI

### CircleCI
