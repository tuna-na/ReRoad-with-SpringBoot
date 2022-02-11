# ReRoad


# 프로젝트 개발 환경
  ## 하드웨어 구성과 배포 환경 및 DB
   ![reroadHard2](https://user-images.githubusercontent.com/92851213/153542721-4e24b98f-d972-48a2-92fe-071fc2556fb9.png)
   ### 하드웨어
   * 2개의 AWS EC2 인스턴스를 사용하여 REST API 서버와 REST API 클라이언트로 구분되는 환경을 구성하였습니다.
   
   ### 배포 환경
   * WAS로 tomcat 9을 사용했으며, Jenkins를 이용해 2개의 EC2 인스턴스에 존재하는 각 WAS로 배포하는 CI/CD환경을 구축 하였습니다.
    
   ### DB
   * MySQL 5.7을 사용하여 DATABASE 계층을 구성하였습니다.

 ## 시스템 구성과 개발환경
 ![reroadSystem](https://user-images.githubusercontent.com/92851213/153538650-bf6de9fb-9d50-4126-a540-a0e92b6caffb.png)
 
# 담당기능

 * 전국의 고속버스 터미널 및 기차역 목록과 고속버스와 열차의 스케줄 정보를 제공하는 REST API 개발

 ![image](https://user-images.githubusercontent.com/92851213/153548068-821452a2-ac2a-4972-a506-4935a3ea769a.png)
---
 * 스케줄 조회를 위해 필요한 정보들을 선택하는 기능
 
 ![select](https://user-images.githubusercontent.com/92851213/153553799-b26469c1-8fcb-42de-baaf-e9da562ecc50.gif)
---
 * 사용자가 선택한 정보로 스케줄을 조회

 ![sc](https://user-images.githubusercontent.com/92851213/153556570-78c6c6da-0dfc-4320-b6e7-5b65d84bab53.png)
---

 

 
 

   


