# 민 율 [minyul]

## 기본 정보

-   깃헙 : https://github.com/minyul
-   현재 개발 블로그 : https://velog.io/@minyul 
-   과거 개발 블로그 : https://blog.naver.com/ggomjae

## 학력 & 경력 사항

- (14.03 - 20.08) [명지대학교](https://www.mju.ac.kr/sites/mjukr/intro/intro.html) - 컴퓨터공학과
- (20.07 - 20.09) [메가존 펜타클](https://www.pentacle.co.kr/#MAIN) - 웹 개발자 인턴
- (20.12 -  ~ING) [ZUMinternet](https://zum.com/) - 웹 개발자 

## 자격증 

- 정보처리기사 


## 경력 프로젝트

### ZUMInternet   :  2020.12.28 ~ ING
---

-   [ZUM 금융](https://finance.zum.com/) Finance Back-End API : 국내, 해외 구현 및 홈, 투자노트 서스테이닝
    -   기술 스택 : - Springboot + Jooq + Redis + Spring Batch + Mysql
    -   기간 : **2021.10 ~ ING** 
    -   참여인원 : 3명
    -   설명
        -    ZUM 에서의 금융 서비스. - ING
            

-   [ZUM 금융](https://finance.zum.com/) Finance CMS 
    -   기술 스택 : Vue + Element Ui + Springboot + Jooq + Aws s3 + Mysql 
    -   기간 : **2021.06 ~ ING** 
    -   참여인원 : 1명
    -   설명
        -    ZUM 에서 금융 서비스를 시작하였고 CMS를 맡았다. 노출되는 금융 뉴스에 대한 비활성/활성화 기능, 금융 영상에 대한 비활성/활성화 기능, 필진 리스트 CRUD, 필진에 대한 콘텐츠 CRUD,
             종목, 테마에 대한 CURD 상세페이지 그리고 이력페이지, 종목 토론에 대한 댓글 제재 및 제재 회원 관리 등등 을 구현하였습니다. 

-   [WhoWho 서비스](https://www.whowhocorp.com/ko/) 통계 외주 프로젝트 
    -   기술 스택 : FreeMarker + springboot + Quartz +SpringBatch + Aws s3 + QueryDSL + Mysql 
    -   기간 : **2021.02 ~ 2021.04 ( - ING )**
    -   참여인원 : 1명
    -   설명
        -   갤럭시 whowho 서비스 관리자 통계 서비스를 구현. Aws S3 에 .gz으로 수집되어 있는 사용자의 정보를 읽어드리고 Spring Batch를 이용하여 통계를 내었다.
            구현을 하면서 Spring Batch가 적합하지 않았다. 그 이유는 Chunk Size를 2이상으로 정할 수 없었고 하루의 통계기에 1로 고정시켜야했다. 즉, Chunk 지향 처리로 구현할 수 없었다.
            결과적으로 고치기에는 공수작업이 컸으므로 통계를 자바단으로 해결하여 Chunk Size 1로 Reader , Multi Writer를 이용하여 수 만건의 통계정보를 Bulk Insert로 처리하였다.
            이 프로젝트를 통해서 얻은 것은 Query DSL, Spring Batch, Quartz에 대한 낯선 기술들의 적용이었으며 DB 설계에 있었던 Index에 대해 많은 부분을 알수 있었다.
            2주 동안의 2백만건의 자료가 쌓이므로 Index가 중요했으며 Cluster Index에 대해서도 알아보고 공부하며 적용시킬 수 있었다.  

    - 프로젝트 얻은 것 :  1.[Cluster Index 성능 공부](https://velog.io/@minyul/Cluster-Index-vs-Non-Cluster-Index-%EC%9D%B4%EB%A1%A0-%EB%B0%8F-%EC%84%B1%EB%8A%A5-%EB%B9%84%EA%B5%90-JPA-MYSQL) , 2.[Between 과 >=, <= 성능 공부](https://velog.io/@minyul/Mysql-Query-Between-%EA%B3%BC-%EC%84%B1%EB%8A%A5-%EC%B0%A8%EC%9D%B4-%EB%B9%84%EA%B5%90-%EB%8D%94%EB%AF%B8%EB%8D%B0%EC%9D%B4%ED%84%B0-50%EB%A7%8C)



-   블라인드웹 [신입사원 프로젝트]
    -   기술 스택 : vue + vuetify + springboot + JPA +mysql + Aws s3 
    -   기간 : **2021.1 ~ 2021.01** 
    -   참여인원 : 1명
    -   설명
        -    블라인드 앱을 보고 익명성이 있는 블라인드 웹을 만드는 수습기간의 프로젝트 <br>
             프로젝트를 끝내고 코드리뷰를 하면서 깨달은 점이 많았던 부분은 글과 같은 등록 기능이 있고 s3와 같은 외부에 포함되어있을 때, <br>
             외부로 통신 하는 부분은 트랜잭션에서 제외하고 s3에 등록 후에 트랜잭션을 다시 걸어주는 부분이 가장 기억이 남는 부분이다.(Real Mysql) <br>
             또한, 암호화를 해주는 주체가 외부 클래스로 static 메소드로 암호화를 시켰다면, 좀 더 나아가 User에 암호화를 시키라는 메세지를 주며 주체적으로 
             User가 암호화를 하게끔 리팩토링한 것이 가장 기억이 남는다. <br>
        
    - 프로젝트 얻은 것 : [트랜잭션 공부 주소](https://blog.naver.com/ggomjae/222226571659) 
---
### Megazone - Pentacle   :  2020.07 ~ 2020.09
---
-   TypeGraphQL, TypeORM, TypeScript를 이용한 간단한 웹 프로젝트
    -   기간 : 10주
    -   참여인원 : 나 포함 외 1명 
    -   설명
        -   프로젝트 : ToDolist   <br>
            2주 : React + Node + MariaDB（Docker）<br>
            3주 : Node + Sequelize + Mysql（Docker） + GraphQL <br>
            5주 : TypeScript + Node + TypeORM + TypeGraphQL + Mysql（Docker）<br>
            인턴 기간 동안 처음 접해본 Express, graphQL, TypeGraphQL 등등 단기간에 여러 기술들을 접하는 경험을 했습니다. 인턴 기간 동안에 주마다 코드리뷰를 받았으며
            코드의 질보다도 얼마나 빠르게 새로운 기술에 적응할 수 있는지를 보았던 것 같습니다. 간단한 CRUD 임에도 불구하고 새로운 기술의 적용이었기 때문에 굉장히 힘든 경험이었고
            이 경험을 통해 배운 것은 **1. 우선은 책을 피는 것이 아닌 적용부터해보자**  **2. 복잡하게 생각할 필요가 없다. 간단하게 생각해보자.** 라는 개발의 마인드를 배웠습니다. 
            
    - 프로젝트 얻은 것 : [이전 GITHUB 주소](https://github.com/ggomjae/careerdirection2)
---

### 그 외

