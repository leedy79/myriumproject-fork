홈 페이지 이미지 넣을곳

<h1 align="center">📚 마이리움 팀 프로젝트</h1>
<p align="center">JSP와 Servlet 기반으로 구현된 동적 웹 프로젝트</p>
<br/>

## 📌 목차

- [개요](https://github.com/notuna87/noh_aladinJSP#-개요)
- [기술 스택](https://github.com/notuna87/noh_aladinJSP#-기술-스택)
- [프로젝트 설계](https://github.com/notuna87/noh_aladinJSP#-프로젝트-설계)
- [실행 화면](https://github.com/notuna87/noh_aladinJSP#-실행-화면)
- [PPT](https://github.com/notuna87/noh_aladinJSP#-PPT)
- [개선사항](https://github.com/notuna87/noh_aladinJSP#-개선사항)

## 📖 개요
- 프로젝트 목표 : 
- 개발 기간 :

## 🛠️ 기술 스택
- Language : `JAVA(11)`, `JavaScript(1.5)`
- Framework / Library: `JSP(JavaServer Pages)(2.3)`, `Servlet(4.0)`, `JSTL`, `JDBC`,`DBManager`,`EL`,`jQuery`
- Database : `Mysql(8.0)`
- Server : `Apache Tomcat(9.0.70)`
- Tool : `Eclipse IDE (4.29.0)`
- API : `Kakao Book Search API`
- ETC : `Git`

## 🧩 프로젝트 설계
<h3 align="center">Usecase Diagram</h3>

유스케이스 다이어그램 사진

<h3 align="center">ERD</h3>

erd 다이어그램 사진

<h3 align="center">Class Diagram</h3>

클래스 다이어그램 사진


## 🖥️ 실행 화면

  * **관리자 대쉬보드**    
    * **1 관리자로그인**
      * 관리자 권한이 있는 회원이 로그인 시 `관리자페이지 대쉬보드`로 이동합니다.
      ![1_관리자로그인_관리자페이지](https://github.com/user-attachments/assets/4d8a50c5-b7eb-4323-bdc1-7d02e6924ae1)
      <br>
      
  * **상품관리**
    * **2-1 상품등록, 이미지 업로드**
      * 상품목록 페이지에서 `등록`을 통해 새로운 상품을 등록할 수 있습니다.
      * 상품의 기본정보(카테고리, 전시영역, 상품명, 설명, 가격)와 할인정보, 재고량을 입력합니다.
      * 상품이미지(최대10개) 업로드 후 대표이미지 설정할 수 있으며 상품상세정보 이미지(최대2개)를 업로드 할 수 있습니다.
      * 입력 정보의 유효성 검사 후 DB에 저장됩니다.
      ![2-1_상품관리_상품등록+이미지업로드](https://github.com/user-attachments/assets/dbca452b-8ab4-47fb-adad-32781c025bf6)
      <br>
      
    * **2-2 필터, 검색, 페이징**
      * 상품목록에서 `필터와 검색`을 통해 원하는 상품을 찾을 수 있습니다.
      * `필터`는 조건을 중첩할 수 있으며, 조건에 해당하는 상품만 필터링되어 보여집니다. `초기화`는 모든 필터 조건을 초기화합니다.
      * `검색`은 상품명으로 원하는 상품을 검색할 수 있습니다.
      * `페이징` 처리를 통해 DB의 상품정보를 효율적으로 가져와 상품목록을 보여줍니다.
      ![2-2_상품관리_필터+검색+페이징](https://github.com/user-attachments/assets/0ab7384b-cd87-4365-9d95-57cca60f41e4)
      <br>
      
    * **2-3 비노출, 복구, 삭제**
      * 특정 상품을 사용자가 볼 수 없도록 `비노출` 할 수 있으며 비노출된 상품을 다시 `복구` 할 수 있습니다.
      * `삭제` 는 DB에 저장된 상품정보와 저장소에 저장된 이미지, 리뷰를 영구적으로 삭제하며, 복구되지 않습니다.
      ![2-3_상품관리_비노출+복구+삭제](https://github.com/user-attachments/assets/d4b2d4e6-5e89-49e4-ba24-3414ea540a06)
      <br>
      
    * **2-4 상품정보 수정, 이미지 변경(삭제, 대표이미지 변경, 신규 이미지 업로드)**
      * `수정`을 통해 기존에 등록된 상품의 기본정보, 할인정보, 상품이미지를 수정할 수 있습니다.
      * 상품이미지와 상품상세정보 이미지를 삭제하거나 새로운 이미지를 추가로 업로드 할 수 있습니다.
      * 전시영역에 보여질 대표이미지 설정을 변경할 수 있습니다.
      * 입력 정보의 유효성 검사 후 수정된 정보가 DB에 저장됩니다.
      ![2-4_상품관리_수정_이미지삭제+대표이미지변경+이미지업로드](https://github.com/user-attachments/assets/9b8d3b48-62e3-4486-a97a-8051e6a19ea1)
      <br>

  * **회원관리**    
    * **3-1 필터, 검색, 페이징**
      * 회원목록에서 `필터와 검색`을 통해 원하는 회원을 찾을 수 있습니다.
      * `필터`는 조건을 중첩할 수 있으며, 조건에 해당하는 회원만 필터링되어 보여집니다. `초기화`는 모든 필터 조건을 초기화합니다.
      * `검색`은 아이디, 이름으로 원하는 회원을 검색할 수 있습니다.
      * `페이징` 처리를 통해 DB의 회원정보를 효율적으로 가져와 회원목록을 보여줍니다.
      ![3-1_회원관리_필터+검색+페이징](https://github.com/user-attachments/assets/ca280170-4611-45c3-ba37-784f16f00e9e)
      <br>
      
    * **3-2 비활성, 활성, 삭제**
      * 계정활동을 정지해야 할 회원을 `비활성` 할 수 있으며 비활성된 회원을 다시 `활성` 할 수 있습니다.
      * `삭제` 는 DB에 저장된 회원정보와 회원과 연관된 모든 데이터(글, 주문 등)를 영구적으로 삭제하며, 복구되지 않습니다.
      ![3-2_회원관리_비활성+활성+삭제](https://github.com/user-attachments/assets/313b4aaf-8fba-4bf1-a79a-e7c0848ff994)
      <br>
      
    * **3-3 회원정보 수정**
      * `수정`을 통해 기존에 등록된 회원의 기본정보, 추가정보를 수정할 수 있습니다.
      * `비밀번호는 수정할 수 없습니다.`
      * 입력 정보의 유효성 검사 후 수정된 정보가 DB에 저장됩니다.
      ![3-3_회원관리_수정_유효성검사](https://github.com/user-attachments/assets/4d939f22-d0df-45e2-bb06-3f2f6ad829b5)
      <br>
    
  * **공지관리**
    * **4-1 공지등록, 파일 업로드**
      * 공지목록 페이지에서 `등록`을 통해 새로운 공지를 등록할 수 있습니다.
      * 공지의 제목, 내용을 입력합니다.
      * 첨부파일(최대3개) 업로드 할 수 있으며, 파일의 용량, 확장자의 제약이 있습니다. 이미지 파일의 경우 썸네일이 만들어 집니다.
      * 입력 정보의 유효성 검사 후 DB에 저장됩니다.
      ![4-1_공지관리_공지등록+파일업로드](https://github.com/user-attachments/assets/4b5f3e33-0f9d-4f8a-8471-c4a77ccd7e88)
      <br>
      
    * **4-2 필터, 검색, 페이징**
      * 공지목록에서 `필터와 검색`을 통해 원하는 공지를 찾을 수 있습니다.
      * `필터`는 조건을 중첩할 수 있으며, 조건에 해당하는 공지만 필터링되어 보여집니다. `초기화`는 모든 필터 조건을 초기화합니다.
      * `검색`은 제목, 내용, 작성자로 원하는 공지을 검색할 수 있습니다.
      * `페이징` 처리를 통해 DB의 공지정보를 효율적으로 가져와 공지목록을 보여줍니다.
      ![4-2_공지관리_검색+페이징](https://github.com/user-attachments/assets/8ae41132-59ea-4062-9f54-fb2462cfba61)
      <br>
      
    * **4-3 비노출, 복구, 삭제**
      * 특정 공지를 사용자가 볼 수 없도록 `비노출` 할 수 있으며 비노출된 공지를 다시 `복구` 할 수 있습니다.
      * `삭제` 는 DB에 저장된 공지정보와 저장소에 저장된 첨부파일를 영구적으로 삭제하며, 복구되지 않습니다.
      ![4-3_공지관리_비노출+복구+식제](https://github.com/user-attachments/assets/8a51e391-20ba-45fd-b616-31a79b6156c1)
      <br>
      
    * **4-4 공지내용 수정, 첨부파일 변경(삭제, 신규 파일 업로드)**
      * `수정`을 통해 기존에 등록된 공지의 제목, 내용, 첨부파일를 수정할 수 있습니다.
      * 첨부파일를 삭제하거나 새로운 파일를 추가로 업로드 할 수 있습니다.
      * 입력 정보의 유효성 검사 후 수정된 정보가 DB에 저장됩니다.
      ![4-4_공지관리_수정+업로드파일수정](https://github.com/user-attachments/assets/c9b8de1a-57e3-4ad4-b6c0-32648e964c0e)
      <br>

  * **FAQ관리**
    * **5-1 FAQ목록, 아코디언방식 내용보기**
      * 공지목록을 질문내용을 유형별로 구분하여 `아코디언 방식`으로 펼치기 접기로 내용을 보여줍니다.
      ![5-1_FAQ관리_아코디언방식내용보기](https://github.com/user-attachments/assets/dc5a51e1-bed3-405a-a7a7-27bf39fb086f)
      <br>
     
    * **5-2 FAQ등록, 파일 업로드**
      * FAQ목록 페이지에서 `등록`을 통해 새로운 FAQ를 등록할 수 있습니다.
      * FAQ의 질문, 답변내용을 입력합니다.
      * 입력 정보의 유효성 검사 후 DB에 저장됩니다.
      ![5-2_FAQ관리_FAQ등록](https://github.com/user-attachments/assets/0479b3c6-3baf-4d0c-8bc1-11dae44c0df5)
      <br>
      
    * **5-3 비노출, 복구, 삭제**
      * 특정 FAQ를 사용자가 볼 수 없도록 `비노출` 할 수 있으며 비노출된 FAQ를 다시 `복구` 할 수 있습니다.
      * `삭제` 는 DB에 저장된 FAQ정보를 영구적으로 삭제하며, 복구되지 않습니다.
      ![5-3_FAQ관리_비노출+복구+식제](https://github.com/user-attachments/assets/40b47169-f605-49d8-a560-bb70cc8e76ad)
      <br>
      
    * **5-4 FAQ내용 수정**
      * `수정`을 통해 기존에 등록된 FAQ의 질문, 답변내용를 수정할 수 있습니다.
      * 입력 정보의 유효성 검사 후 수정된 정보가 DB에 저장됩니다.
      ![5-4_FAQ관리_수정](https://github.com/user-attachments/assets/cfc15935-659b-425f-bbdc-464882b65cd4)
      <br>

  * **리뷰관리**
    * **6 검색, 페이징, 비노출, 복구, 삭제**
      * 리뷰목록은 상품별 리뷰현황을 보여주며 `검색`을 통해 원하는 상품의 리뷰를 찾을 수 있습니다.
      * `검색`은 상품명으로 원하는 리뷰를 검색할 수 있습니다.
      * `페이징` 처리를 통해 DB의 리뷰정보를 효율적으로 가져와 리뷰목록을 보여줍니다.
      * `보기`를 통해 해당 상품의 모든 리뷰를 볼 수 있습니다.(모달창)
      * 특정 리뷰를 사용자가 볼 수 없도록 `비노출` 할 수 있으며 비노출된 공지을 다시 `복구` 할 수 있습니다.
      * `삭제` 는 DB에 저장된 리뷰정보를 영구적으로 삭제하며, 복구되지 않습니다.
      ![6-1_리뷰관리_페이징+검색+상세보기+비노출+복구+삭제](https://github.com/user-attachments/assets/0d198da9-86d9-4ffa-a5b8-a77af2c21425)
      <br>
      
  * **문의관리**
    * **7-1 문의등록, 추가문의 등록(채팅)**
      * 일반 사용자는 문의목록 페이지에서 `등록`을 통해 새로운 문의를 등록할 수 있습니다. `미답변` 라벨이 생성됩니다.
      * `등록`은 사용자 전용으로 관리자에게는 노출되지 않습니다.
      * 사용자는 문의할 제목, 내용을 입력합니다.
      * 입력 정보의 유효성 검사 후 DB에 저장됩니다.
      * `추가문의`를 통해 채팅방식으로 등록하고 관리자와 대화형식으로 답변과 문의을 주고 받을 수 있습니다.
      ![7-1_문의관리_사용자문의등록+추가문의채팅](https://github.com/user-attachments/assets/5d2b59fb-d058-4524-9400-072f1171dba2)
      <br>
      
    * **7-2 검색, 페이징**
      * 문의목록에서 `검색`을 통해 원하는 문의를 찾을 수 있습니다.
      * `검색`은 제목, 내용, 작성자로 원하는 문의를 검색할 수 있습니다.
      * `페이징` 처리를 통해 DB의 문의정보를 효율적으로 가져와 문의목록을 보여줍니다.
      ![7-2_문의관리_페이징+검색](https://github.com/user-attachments/assets/3e47992b-36fc-43d4-b4de-4e71e80464f0)
      <br>
      
    * **7-3 답변등록**
      * `답변하기`로 사용자와 대화형식으로 답변과 문의을 주고 받을 수 있습니다.
      * `답변완료` 라벨이 생성됩니다.
      ![7-3_문의관리_답변등록](https://github.com/user-attachments/assets/bc1946d7-0f0d-4235-bebd-ff85459a4d0d)
     <br>

    * **7-4 비노출, 복구, 삭제**
      * 특정 문의를 사용자가 볼 수 없도록 `비노출` 할 수 있으며 비노출된 문의를 다시 `복구` 할 수 있습니다.
      * `삭제` 는 DB에 저장된 문의정보를 영구적으로 삭제하며, 복구되지 않습니다.
      ![7-4_문의관리_비노출+복구+삭제](https://github.com/user-attachments/assets/52cd9251-c640-4a73-abad-63c3e74ba9bd)
      <br>

    * **7-5 문의내용 수정**
      * `수정`을 통해 기존에 등록된 문의의 제목, 내용, 첨부파일를 수정할 수 있습니다.
      * 입력 정보의 유효성 검사 후 수정된 정보가 DB에 저장됩니다.
      ![7-5_문의관리_수정](https://github.com/user-attachments/assets/e8223fc2-6f46-430b-be45-0ba047504955)
      <br>

  * **주문관리**    
    * **8-1 필터, 검색, 페이징**
      * 주문목록에서 `필터와 검색`을 통해 원하는 주문을 찾을 수 있습니다. `초기화`는 필터 조건을 초기화합니다.
      * `검색`은 이름으로 원하는 주문을 검색할 수 있습니다.
      * `페이징` 처리를 통해 DB의 주문정보를 효율적으로 가져와 주문목록을 보여줍니다.
      ![8-1_주문관리_페이징+검색+상세보기](https://github.com/user-attachments/assets/be899846-87ba-441d-82ec-61d5c313e805)
      <br>
      
    * **8-2 주문상태 처리**
      * 주문목록은 주문번호별 현황을 보여주며 `자세히`을 통해 주문 세부내역(주문상품 목록)을 확인할 수 있습니다.(모달창)
      * 주문상품의 처리상태(배송, 취소, 교환, 반품 등)를 확인할 수 있으며 처리에 대한 상태를 변경할 수 있습니다. (예)상품발송 후 `배송중` 처리 
      ![8-2_주문관리_주문상태처리](https://github.com/user-attachments/assets/bc5c9ffb-64fc-4050-b20a-ed8c7d55c375)
      <br>
       
## 🗂️ PPT
<details><summary>PPT</summary>
  <div align="center">          

| ![2435652f4f5ea3df52921ad0e596fd45-0](https://github.com/user-attachments/assets/4a74b6a5-9fcb-4a2f-a23c-fc1bf548cd21) | ![2435652f4f5ea3df52921ad0e596fd45-1](https://github.com/user-attachments/assets/0d6ad712-d840-4e65-a64a-4c28edf5a184) |
| :------: |  :------: |
| ![2435652f4f5ea3df52921ad0e596fd45-2](https://github.com/user-attachments/assets/0e008f84-88ea-4884-8a93-a60d6a7beef8) | ![2435652f4f5ea3df52921ad0e596fd45-3](https://github.com/user-attachments/assets/018d0853-f35e-4d95-bcd5-208b8be11b77) |
| ![2435652f4f5ea3df52921ad0e596fd45-4](https://github.com/user-attachments/assets/70778810-ca36-4534-a0b8-cf5bf2a9f459) | ![2435652f4f5ea3df52921ad0e596fd45-5](https://github.com/user-attachments/assets/e3730cdc-ac06-4de4-96b6-6d14c6467a11) |
| ![2435652f4f5ea3df52921ad0e596fd45-6](https://github.com/user-attachments/assets/9dda287a-f8ad-4889-8594-67c2d5a961bc) | ![2435652f4f5ea3df52921ad0e596fd45-7](https://github.com/user-attachments/assets/985ba460-a749-4173-bfe4-9f3e8345af0e) |
| ![2435652f4f5ea3df52921ad0e596fd45-8](https://github.com/user-attachments/assets/2ba50660-b886-44a7-bbed-b488864e24f2) | ![2435652f4f5ea3df52921ad0e596fd45-9](https://github.com/user-attachments/assets/338e0274-dd8b-4012-bdc6-870d19e7d92b) |
| ![2435652f4f5ea3df52921ad0e596fd45-10](https://github.com/user-attachments/assets/5140f9d5-a96b-4ddb-81b8-c48ba6e2a329) | ![2435652f4f5ea3df52921ad0e596fd45-11](https://github.com/user-attachments/assets/b846d66e-8c8e-48c6-8462-b4e0f18fcb1d) |
| ![2435652f4f5ea3df52921ad0e596fd45-12](https://github.com/user-attachments/assets/a23d31e4-80d5-4960-bb69-f2a662d28e83) | ![2435652f4f5ea3df52921ad0e596fd45-13](https://github.com/user-attachments/assets/1b4fc9ff-b875-44c5-b963-75de63e20209) |
| ![2435652f4f5ea3df52921ad0e596fd45-14](https://github.com/user-attachments/assets/b7823234-e871-4f11-b276-87acfd27a0f4) | ![2435652f4f5ea3df52921ad0e596fd45-15](https://github.com/user-attachments/assets/01b13972-78b3-4730-8c61-fd549bbed706) |
| ![2435652f4f5ea3df52921ad0e596fd45-16](https://github.com/user-attachments/assets/8ef486a8-efe3-49dc-8fe4-fc6637d38e98) | ![2435652f4f5ea3df52921ad0e596fd45-17](https://github.com/user-attachments/assets/e5df7fdd-4749-4ddc-94c4-19f20e41fc9f) |
| ![2435652f4f5ea3df52921ad0e596fd45-18](https://github.com/user-attachments/assets/bcc85140-e676-4d4f-bd20-0931a4050c32) | ![2435652f4f5ea3df52921ad0e596fd45-19](https://github.com/user-attachments/assets/1d9f360c-9c57-4d41-be87-c2d8ca7f84b9) |
| ![2435652f4f5ea3df52921ad0e596fd45-20](https://github.com/user-attachments/assets/9f1e3d44-09a2-46aa-9a19-27b7e6512990) | ![2435652f4f5ea3df52921ad0e596fd45-21](https://github.com/user-attachments/assets/91002c9b-df2d-4708-a932-1fbd0fbb045c) |
| ![2435652f4f5ea3df52921ad0e596fd45-22](https://github.com/user-attachments/assets/cd80068f-6af8-4ea6-90f2-dc0f03d57656) | ![2435652f4f5ea3df52921ad0e596fd45-23](https://github.com/user-attachments/assets/728de973-b2b8-4e61-a433-86b5ae14602c) |
| ![2435652f4f5ea3df52921ad0e596fd45-24](https://github.com/user-attachments/assets/12b985b5-0307-4379-b88b-d006f775287a) | ![2435652f4f5ea3df52921ad0e596fd45-25](https://github.com/user-attachments/assets/30de806e-d713-4979-a24e-2d637ac0eb1d) |
| ![2435652f4f5ea3df52921ad0e596fd45-26](https://github.com/user-attachments/assets/6361216a-1bc8-4eda-98b0-a754b32d5d63) | ![2435652f4f5ea3df52921ad0e596fd45-27](https://github.com/user-attachments/assets/4cd77ced-0884-40f9-b953-63a675f3ac28) |
| ![2435652f4f5ea3df52921ad0e596fd45-28](https://github.com/user-attachments/assets/733de6e0-b1e0-4c91-98ab-3ff6dfcc1284) | ![2435652f4f5ea3df52921ad0e596fd45-29](https://github.com/user-attachments/assets/72ed854d-50c5-4532-b89e-cba562a27535) |
| ![2435652f4f5ea3df52921ad0e596fd45-30](https://github.com/user-attachments/assets/23342b80-0f13-45bf-ae66-54213afb04cd) | ![2435652f4f5ea3df52921ad0e596fd45-31](https://github.com/user-attachments/assets/cade5188-3bb4-4d87-887f-49ba085beae0) |
| ![2435652f4f5ea3df52921ad0e596fd45-32](https://github.com/user-attachments/assets/2f139104-b3f9-494e-a700-08aaab5da648) | ![2435652f4f5ea3df52921ad0e596fd45-33](https://github.com/user-attachments/assets/8ec04e63-9103-4ebf-8bed-c30f8aa5a2f5) |
| ![2435652f4f5ea3df52921ad0e596fd45-34](https://github.com/user-attachments/assets/145ac317-a681-4632-a5dd-65a16c34c5ed) | ![2435652f4f5ea3df52921ad0e596fd45-35](https://github.com/user-attachments/assets/22774951-623e-444a-83ad-901b3304ad66) |
| ![2435652f4f5ea3df52921ad0e596fd45-36](https://github.com/user-attachments/assets/b76b2420-27ce-4bfa-a47d-83c90adf5cdd) | ![2435652f4f5ea3df52921ad0e596fd45-37](https://github.com/user-attachments/assets/883e1866-227d-4f8e-931b-8bd34aa3d419) |
| ![2435652f4f5ea3df52921ad0e596fd45-38](https://github.com/user-attachments/assets/470c6938-0dd5-4335-92e2-28b7435a1d93) | ![2435652f4f5ea3df52921ad0e596fd45-39](https://github.com/user-attachments/assets/03d3b0b5-ac23-4bab-956a-191292afd665) |
| ![2435652f4f5ea3df52921ad0e596fd45-40](https://github.com/user-attachments/assets/5db00ac7-94da-4dfd-afe7-f63c6819b33c) | ![2435652f4f5ea3df52921ad0e596fd45-41](https://github.com/user-attachments/assets/f0972e37-716a-4600-85e7-dde0f9e79158) |
| ![2435652f4f5ea3df52921ad0e596fd45-42](https://github.com/user-attachments/assets/21dd479e-08e1-41b2-bcae-92a9967f7bc2) | ![2435652f4f5ea3df52921ad0e596fd45-43](https://github.com/user-attachments/assets/8102c9ac-79aa-4d0f-b430-db8d0d77ef7a) |
| ![2435652f4f5ea3df52921ad0e596fd45-44](https://github.com/user-attachments/assets/9767b4e6-4ab8-46d7-b81c-85da2096ae29) | ![2435652f4f5ea3df52921ad0e596fd45-45](https://github.com/user-attachments/assets/ef2abf27-d20a-4d34-aabd-82f63f32fd02) |
| ![2435652f4f5ea3df52921ad0e596fd45-46](https://github.com/user-attachments/assets/35276db4-012a-44bf-950a-a9875aa40770) | ![2435652f4f5ea3df52921ad0e596fd45-47](https://github.com/user-attachments/assets/2066eb84-0946-4b81-9abd-29d772f21b9b) |
| ![2435652f4f5ea3df52921ad0e596fd45-48](https://github.com/user-attachments/assets/8e734be9-899a-4c45-9259-e5c262da184b) | ![2435652f4f5ea3df52921ad0e596fd45-49](https://github.com/user-attachments/assets/213d1ef9-d279-45f5-958f-caea7dc38b72) |
| ![2435652f4f5ea3df52921ad0e596fd45-50](https://github.com/user-attachments/assets/4ba1b955-1cd5-4b66-8038-f53acfe2bf95) | ![2435652f4f5ea3df52921ad0e596fd45-51](https://github.com/user-attachments/assets/ec5c8d1e-8f17-40c9-a759-302e3ffb5c55) |
| ![2435652f4f5ea3df52921ad0e596fd45-52](https://github.com/user-attachments/assets/9d089c4c-8b6c-46e5-b42f-44b19e3601a6) | ![2435652f4f5ea3df52921ad0e596fd45-53](https://github.com/user-attachments/assets/96946991-6d77-49df-81a6-8b42fcdad603) |
| ![2435652f4f5ea3df52921ad0e596fd45-54](https://github.com/user-attachments/assets/36e68fee-4601-4d1b-a3a5-3e3eedcfd46e) | ![2435652f4f5ea3df52921ad0e596fd45-55](https://github.com/user-attachments/assets/cb931afa-bf81-4c7e-9ad3-6d7969f1d97d) |
| ![2435652f4f5ea3df52921ad0e596fd45-56](https://github.com/user-attachments/assets/d2ba953e-52c0-4573-a81d-244216d247ec) | ![2435652f4f5ea3df52921ad0e596fd45-57](https://github.com/user-attachments/assets/c2a3a893-578e-440c-ad9a-c636a11f2f04) |
| ![2435652f4f5ea3df52921ad0e596fd45-58](https://github.com/user-attachments/assets/c25d4790-0792-42a1-826e-42d4b53350d5) | ![2435652f4f5ea3df52921ad0e596fd45-59](https://github.com/user-attachments/assets/1cb1c332-9f58-4be2-bf74-9108c0004d23) |
| ![2435652f4f5ea3df52921ad0e596fd45-60](https://github.com/user-attachments/assets/9a47ccb9-7538-4986-b45f-c852248a076b) | ![2435652f4f5ea3df52921ad0e596fd45-61](https://github.com/user-attachments/assets/77ec9201-9bf1-4be0-bc11-efb101b9d4db) |
| ![2435652f4f5ea3df52921ad0e596fd45-62](https://github.com/user-attachments/assets/3b0e9003-e24b-4da9-a5ec-49affa5e2996) | ![2435652f4f5ea3df52921ad0e596fd45-63](https://github.com/user-attachments/assets/23ec40bd-a3bd-44a0-8c41-1ac6d0b63210) |
| ![2435652f4f5ea3df52921ad0e596fd45-64](https://github.com/user-attachments/assets/211706ea-9ad4-493d-be92-8fd694d67cbd) | ![2435652f4f5ea3df52921ad0e596fd45-65](https://github.com/user-attachments/assets/796ffbd9-0033-49be-8d8c-7f901176cf69) |
| ![2435652f4f5ea3df52921ad0e596fd45-66](https://github.com/user-attachments/assets/4a697333-6e20-4a0b-9b70-5d04586e6e22) | ![2435652f4f5ea3df52921ad0e596fd45-67](https://github.com/user-attachments/assets/7ca61954-d63d-4c5f-a933-529ba0af8d7a) |
| ![2435652f4f5ea3df52921ad0e596fd45-68](https://github.com/user-attachments/assets/09baef6c-4fa4-4e4e-9882-e4ef8de753f4) | ![2435652f4f5ea3df52921ad0e596fd45-69](https://github.com/user-attachments/assets/b2080d97-b1bf-4743-a772-ba99c6b8f65a) |
| ![2435652f4f5ea3df52921ad0e596fd45-70](https://github.com/user-attachments/assets/9d3078d1-c4e4-407a-827e-a8a63915f61e) | ![2435652f4f5ea3df52921ad0e596fd45-71](https://github.com/user-attachments/assets/76666fc9-27b8-4ead-99e9-5e5cfdc841d4) |
| ![2435652f4f5ea3df52921ad0e596fd45-72](https://github.com/user-attachments/assets/f22b514a-f151-4085-9060-4837fcce5c3e) | ![2435652f4f5ea3df52921ad0e596fd45-73](https://github.com/user-attachments/assets/1e7be4b6-3aba-4e90-84fa-9880e378918e) |
| ![2435652f4f5ea3df52921ad0e596fd45-74](https://github.com/user-attachments/assets/75167c5b-ee69-4abb-9941-9833fa7f83fd) | ![2435652f4f5ea3df52921ad0e596fd45-75](https://github.com/user-attachments/assets/5bd1ff9b-0383-43bb-9c54-d632c900575d) |
| ![2435652f4f5ea3df52921ad0e596fd45-76](https://github.com/user-attachments/assets/aa20db44-9d17-4fd5-b665-ccb57c809fba) | ![2435652f4f5ea3df52921ad0e596fd45-77](https://github.com/user-attachments/assets/1d429842-e8d0-4660-93b6-332d6d4049b0) |
| ![2435652f4f5ea3df52921ad0e596fd45-78](https://github.com/user-attachments/assets/2c9bbfbc-ee1e-4714-9bfc-5654a99db906) | ![2435652f4f5ea3df52921ad0e596fd45-79](https://github.com/user-attachments/assets/81b48815-e215-4489-982a-85a46ef61eaa) |
| ![2435652f4f5ea3df52921ad0e596fd45-80](https://github.com/user-attachments/assets/9bb6fce4-831b-40d4-b6de-f589c681bf32) | ![2435652f4f5ea3df52921ad0e596fd45-81](https://github.com/user-attachments/assets/b8763f5a-36fe-4716-8f35-8d490eabb802) |
| ![2435652f4f5ea3df52921ad0e596fd45-82](https://github.com/user-attachments/assets/50eb3229-f9a0-43c5-8046-6c3654fc6472) | ![2435652f4f5ea3df52921ad0e596fd45-83](https://github.com/user-attachments/assets/85ce08d4-143d-4984-9108-a98ebbf6dff6) |
| ![2435652f4f5ea3df52921ad0e596fd45-84](https://github.com/user-attachments/assets/c8bb1f7a-6da2-4a48-9c99-3314674662df) | ![2435652f4f5ea3df52921ad0e596fd45-85](https://github.com/user-attachments/assets/23ffedcd-1f7c-4c95-84ad-62954f0a5fbf) |
| ![2435652f4f5ea3df52921ad0e596fd45-86](https://github.com/user-attachments/assets/3ddfc2bb-4f5a-43fc-b78a-bcc24b9454da) | ![2435652f4f5ea3df52921ad0e596fd45-87](https://github.com/user-attachments/assets/b6cbaddb-defc-4233-b86a-68969600ecce) |
| ![2435652f4f5ea3df52921ad0e596fd45-88](https://github.com/user-attachments/assets/16d379f1-13ec-48c4-8b4c-dddedfe97e85) | ![2435652f4f5ea3df52921ad0e596fd45-89](https://github.com/user-attachments/assets/81c7d3fb-f4c5-4848-a35a-cee14911445b) |
| ![2435652f4f5ea3df52921ad0e596fd45-90](https://github.com/user-attachments/assets/138149d5-7911-47f4-a84d-448c8559e328) | ![2435652f4f5ea3df52921ad0e596fd45-91](https://github.com/user-attachments/assets/521354c9-69ae-4bc0-807f-869cc7485eeb) |
| ![2435652f4f5ea3df52921ad0e596fd45-92](https://github.com/user-attachments/assets/34e1c501-2ee8-4ab0-b2e5-1d756a7d77d7) | ![2435652f4f5ea3df52921ad0e596fd45-93](https://github.com/user-attachments/assets/f55138dc-bfb7-4d7d-aa0d-be8d62753579) |
| ![2435652f4f5ea3df52921ad0e596fd45-94](https://github.com/user-attachments/assets/cb892425-d049-42c6-8d85-8ba60e274a42) | ![2435652f4f5ea3df52921ad0e596fd45-95](https://github.com/user-attachments/assets/afe51e80-9315-40c2-b4b1-236cc9fcd022) |
| ![2435652f4f5ea3df52921ad0e596fd45-96](https://github.com/user-attachments/assets/4e39dc5f-026e-4e35-8d2e-66e0fc3c5a25) | ![2435652f4f5ea3df52921ad0e596fd45-97](https://github.com/user-attachments/assets/15f32216-1fec-4fb9-8b9a-a80f6ad71061) |
| ![2435652f4f5ea3df52921ad0e596fd45-98](https://github.com/user-attachments/assets/2d00d5b9-f609-4a6f-b02a-fcefc996ab1a) | 
| 










</details>


</br>

## 🚀 개선사항
</br>

