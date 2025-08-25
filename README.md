![babysbreath_detail](https://github.com/user-attachments/assets/9f1b8e1e-73c1-4067-b591-d0db3fb503de)
![Screenshot 2025-08-24 at 17 30 21](https://github.com/user-attachments/assets/9806a0a3-8eec-46a1-be65-47bafa622215)


<h1 align="center">📚 마이리움 팀 프로젝트</h1>
<p align="center">Spring MVC 기반 3인 협작 클론 사이트 프로젝트입니다.</p>
<br/>

## 📌 목차

- [개요](https://github.com/leedy79/myriumproject-fork?tab=readme-ov-file#-%EA%B0%9C%EC%9A%94)
- [기술 스택](https://github.com/leedy79/myriumproject-fork?tab=readme-ov-file#%EF%B8%8F-%EA%B8%B0%EC%88%A0-%EC%8A%A4%ED%83%9D)
- [프로젝트 설계](https://github.com/leedy79/myriumproject-fork#-프로젝트-설계)
- [실행 화면](https://github.com/leedy79/myriumproject-fork#-실행-화면)
- [실행 화면](https://github.com/leedy79/myriumproject-fork?tab=readme-ov-file#%EF%B8%8F-%EC%8B%A4%ED%96%89-%ED%99%94%EB%A9%B4)
- [PPT](https://github.com/leedy79/myriumproject-fork#-PPT)
- [개선사항](https://github.com/leedy79/myriumproject-fork#-개선사항)

## 📖 개요
- 프로젝트 목표 : Spring MVC 기반으로 마이리움 클론 사이트를 제작하여, 실제 전자상거래 환경에서 상품 조회, 장바구니, 주문 등의 기능을 구현
- 개발 기간 : 2025.07.16 ~ 2025.08.14

## 🛠️ 기술 스택
- Language : `JAVA(11)`, `JavaScript(1.5)`
- Framework / Library: `JSP(JavaServer Pages)(2.3)`, `JSTL`, `JDBC`,`DBManager`,`EL`,`jQuery`,`Lombok`
- Database : `Oracle 11g XE (11.2.0.2.0)`
- Server : `Apache Tomcat(9.0.70)`
- Tool : `Spring Tool Suite 3`
- API : `Daum postCode API`
- ETC : `Git`, `google Sheets`, `draw.io`, `erdCloud`, `sourcetree`

## 🧩 프로젝트 설계
# **🕵️‍♂️UseCase**  
![usecase_diagram](https://github.com/user-attachments/assets/bde25637-7452-48dc-a903-5487936d4b69)

# **💿ERD**
<img width="1010" height="740" alt="erd_member" src="https://github.com/user-attachments/assets/4842ca1f-3c1d-4876-bb7e-40673f1204d2" />
<img width="761" height="701" alt="erd_product" src="https://github.com/user-attachments/assets/53986546-615d-4320-b935-4dd93a427d37" />

# **🔗Class Diagram**

<details><summary><h2 align="center">Class Diagram(🖱클릭 : 보기)</h2></summary>
<h3>⛓UploadController</h3>
<img width="2200" height="1347" alt="Diagram_UploadController" src="https://github.com/user-attachments/assets/95f413e3-6508-44ee-bc83-0cdf7372487c" />
<h3>⛓TotalReviewController</h3>
<img width="1271" height="724" alt="Diagram_TotalReviewController" src="https://github.com/user-attachments/assets/dbb13257-40bb-40d2-9867-9bc67c14041d" />
<h3>⛓SubController</h3>
<img width="2234" height="1259" alt="Diagram_SubController" src="https://github.com/user-attachments/assets/63e078eb-4fbd-488d-b62b-bbbadb3b3a0e" />
<h3>⛓SearchController</h3>
<img width="1602" height="1185" alt="Diagram_SearchController" src="https://github.com/user-attachments/assets/c6a32127-e257-4edb-be40-6096fcae2cc1" />
<h3>⛓ReviewController</h3>
<img width="2082" height="2085" alt="Diagram_ReviewController" src="https://github.com/user-attachments/assets/72f3a7c4-f4ed-4ef5-9ad1-434e8f8edfd0" />
<h3>⛓ReplyController</h3>
<img width="1509" height="916" alt="Diagram_ReplyController" src="https://github.com/user-attachments/assets/4785b72d-5ece-4531-8113-1b72af856008" />
<h3>⛓PurchaseController</h3>
<img width="2314" height="2085" alt="Diagram_PurchaseController" src="https://github.com/user-attachments/assets/b667aba8-2544-4419-beee-f87191dc0e91" />
<h3>⛓OrderdetailController</h3>
<img width="1209" height="1138" alt="Diagram_OrderdetailController" src="https://github.com/user-attachments/assets/23629644-65fd-427a-ba63-0d745d10b7f2" />
<h3>⛓MypageController</h3>
<img width="1170" height="1208" alt="Diagram_MypageController" src="https://github.com/user-attachments/assets/b71c2c5b-5a30-4c6f-8943-7c2189cd4a99" />
<h3>⛓MemberupdateController</h3>
<img width="1475" height="1119" alt="Diagram_MemberupdateController" src="https://github.com/user-attachments/assets/c41d3ba2-3da9-4512-ba2e-96fe92999f52" />
<h3>⛓MemberRestController</h3>
<img width="1281" height="1069" alt="Diagram_MemberRestController" src="https://github.com/user-attachments/assets/6e85674c-c6fa-415b-b4f8-c66b8209d104" />
<h3>⛓MemberController</h3>
<img width="1932" height="747" alt="Diagram_MemberController" src="https://github.com/user-attachments/assets/a7885bfd-8a0a-465d-850c-6c44a521e04e" />
<h3>⛓JoinController</h3>
<img width="1410" height="851" alt="Diagram_JoinController" src="https://github.com/user-attachments/assets/354d0199-7771-4a95-b8bb-a7cfa15d1484" />
<h3>⛓HomeController</h3>
<img width="1614" height="1330" alt="Diagram_HomeController" src="https://github.com/user-attachments/assets/537ff07b-6190-41de-a97a-6acec7f8c7c4" />
<h3>⛓FindpwController</h3>
<img width="1380" height="927" alt="Diagram_FindpwController" src="https://github.com/user-attachments/assets/2c90fa72-2c4b-4850-a593-5b173c09bc97" />
<h3>⛓FindidController</h3>
<img width="1463" height="1016" alt="Diagram_FindidController" src="https://github.com/user-attachments/assets/d10db07d-b6d8-445e-9751-ff04e4a69b23" />
<h3>⛓EtcController</h3>
<img width="1156" height="576" alt="Diagram_EtcController" src="https://github.com/user-attachments/assets/0b5ba722-2752-456a-a183-6dac795fd5c6" />
<h3>⛓CategoryPageController</h3>
<img width="1675" height="1191" alt="Diagram_CategoryPageController" src="https://github.com/user-attachments/assets/6e3c099b-3f25-4cdb-a017-7d8247bb85a2" />
<h3>⛓CartController</h3>
<img width="1958" height="1352" alt="Diagram_CartController" src="https://github.com/user-attachments/assets/c6afbfb7-04d0-406c-a0e5-74f9bca70d57" />
<h3>⛓AdminReviewController</h3>
<img width="1356" height="978" alt="Diagram_AdminReviewController" src="https://github.com/user-attachments/assets/e189804b-4f76-479c-8d75-3074f949c0c0" />
<h3>⛓AdminProductController</h3>
<img width="1954" height="1348" alt="Diagram_AdminProductController" src="https://github.com/user-attachments/assets/c0eecd98-7b29-40da-9d70-9a2d2638dfb5" />
<h3>⛓AdminOrderController</h3>
<img width="1367" height="951" alt="Diagram_AdminOrderController" src="https://github.com/user-attachments/assets/9d46a3aa-d5d5-47a7-b880-102180798df2" />
<h3>⛓AdminNoticeController</h3>
<img width="1642" height="904" alt="Diagram_AdminNoticeController" src="https://github.com/user-attachments/assets/7f82b528-73ea-4612-afb5-d38c51c161df" />
<h3>⛓AdminMemberController</h3>
<img width="1656" height="991" alt="Diagram_AdminMemberController" src="https://github.com/user-attachments/assets/ed83d685-bea2-42ce-b190-471321abd429" />
<h3>⛓AdminFaqController</h3>
<img width="809" height="567" alt="Diagram_AdminFaqController" src="https://github.com/user-attachments/assets/c1c378c6-3086-4147-ab8e-f430d6b41a65" />
<h3>⛓AdminBoardController</h3>
<img width="2361" height="1100" alt="Diagram_AdminBoardController" src="https://github.com/user-attachments/assets/7edb5e8d-b6d8-443f-9a1f-3b4263d580ee" />
</details>


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
<details><summary><h2 align="center">PPT(🖱클릭 : 보기)</h2></summary>
<div align="center">
  
| ![슬라이드1](https://github.com/user-attachments/assets/a661b7a1-bef1-4f73-9eaa-199a6941794f) | ![슬라이드2](https://github.com/user-attachments/assets/2f4b8ff6-87b3-4823-906f-ac0796d7ce33) |
| :---: | :---: |
| ![슬라이드3](https://github.com/user-attachments/assets/a0461576-fadf-4eb2-bd13-fa96e374fadc) | ![슬라이드4](https://github.com/user-attachments/assets/33865d89-16d3-4f24-88ba-5a12f0ef57ac) |
| ![슬라이드5](https://github.com/user-attachments/assets/b7b311a0-b848-4ab0-985d-c21fabad2dff) | ![슬라이드6](https://github.com/user-attachments/assets/f4862103-6fbb-46ab-b580-b6bef6b77968) |
| ![슬라이드7](https://github.com/user-attachments/assets/d1d98d88-e420-48fc-b49d-e26bd8577ebe) | ![슬라이드8](https://github.com/user-attachments/assets/466da45f-827e-45b5-9846-0309fbde46a4) |
| ![슬라이드9](https://github.com/user-attachments/assets/775db930-1b1a-4be7-817d-1fa9d221a887) | ![슬라이드10](https://github.com/user-attachments/assets/990f6e2e-6b00-466e-98a9-804be468f0cc) |
| ![슬라이드11](https://github.com/user-attachments/assets/6fde377f-4ae4-47e0-9477-8748eabb9005) | ![슬라이드12](https://github.com/user-attachments/assets/9cf62e5d-4e4a-4e81-a96e-e1dfdd0481bd) |
| ![슬라이드13](https://github.com/user-attachments/assets/2ce80869-7868-416a-960f-64016880eb42) | ![슬라이드14](https://github.com/user-attachments/assets/eed42637-7ba8-43c7-96aa-d57e2ee41f5d) |
| ![슬라이드15](https://github.com/user-attachments/assets/3fe532a3-3615-419e-ae5b-ff0ee9a8dcc0) | ![슬라이드16](https://github.com/user-attachments/assets/11ca742a-8e7d-4867-a392-a54cfe3f807a) |
| ![슬라이드17](https://github.com/user-attachments/assets/4381b53f-0625-4760-a4f0-02917c111a8e) | ![슬라이드18](https://github.com/user-attachments/assets/74c2fc78-aabd-4ac7-9aa9-bd9c5bd49fea) |
| ![슬라이드19](https://github.com/user-attachments/assets/31467ef3-267c-4f85-b685-bd0a2a6ccf0b) | ![슬라이드20](https://github.com/user-attachments/assets/ed99fb42-150f-4095-be41-33d084a97949) |
| ![슬라이드21](https://github.com/user-attachments/assets/c920939f-0621-4095-abbc-2f80aa6c74fe) | ![슬라이드22](https://github.com/user-attachments/assets/a6b40aa9-8644-4a2e-9935-be6b44253fe3) |
| ![슬라이드23](https://github.com/user-attachments/assets/06355b0f-91d1-4c6e-b826-63fe4652a884) | ![슬라이드24](https://github.com/user-attachments/assets/806c063c-0014-4499-b520-983526548c02) |
| ![슬라이드25](https://github.com/user-attachments/assets/ba2e5ff1-7c20-47d2-9390-5293e1da40c9) | ![슬라이드26](https://github.com/user-attachments/assets/21d03041-d845-4a31-a9a6-1217142aa500) |
| ![슬라이드27](https://github.com/user-attachments/assets/dc87a541-26b0-4260-ae09-15d03b887431) | ![슬라이드28](https://github.com/user-attachments/assets/ec7ce523-ea15-4b05-aed1-769e97728373) |
| ![슬라이드29](https://github.com/user-attachments/assets/6069833e-2634-477e-a21e-11ed8066e476) | ![슬라이드30](https://github.com/user-attachments/assets/aaff6258-f230-4817-aed1-e5ff11522d4e) |
| ![슬라이드31](https://github.com/user-attachments/assets/f69ddde9-74f6-418f-bd93-0516bb0d2ea7) | ![슬라이드32](https://github.com/user-attachments/assets/8752f590-c11a-4cd0-b80f-07646ed5ed38) |
| ![슬라이드33](https://github.com/user-attachments/assets/fb70efdd-7edf-4b65-9335-2eacb63c7a2d) | ![슬라이드34](https://github.com/user-attachments/assets/b7351739-6a6a-40f6-847c-8186906ed488) |
| ![슬라이드35](https://github.com/user-attachments/assets/b125215a-389c-425f-9ecd-eb88d7b7ebe3) | ![슬라이드36](https://github.com/user-attachments/assets/d369ca41-6513-41c0-a090-1ec6b1d0b74c) |
| ![슬라이드37](https://github.com/user-attachments/assets/bb875d87-2d39-4908-8381-acf27a0ecf81) | ![슬라이드38](https://github.com/user-attachments/assets/bbc24102-407f-4dfd-9d28-1f7e7f3b757a) |
| ![슬라이드39](https://github.com/user-attachments/assets/2e45758d-ac3e-482e-bce9-d5c46e1555a0) | ![슬라이드40](https://github.com/user-attachments/assets/69c2bf7b-1f13-4109-953e-0a458c525358) |
| ![슬라이드41](https://github.com/user-attachments/assets/56fd4da7-7742-47df-b0a2-42c0d1bd6665) | ![슬라이드42](https://github.com/user-attachments/assets/57f294fb-204e-4370-bce9-f1d3fdf860f5) |
| ![슬라이드43](https://github.com/user-attachments/assets/d67ccb26-b334-463d-b870-3750132b0db9) | ![슬라이드44](https://github.com/user-attachments/assets/d204fd93-c12b-4ece-96b6-36234156a034) |
| ![슬라이드45](https://github.com/user-attachments/assets/1d2afcd4-f42d-4705-a611-a5269e88240a) | ![슬라이드46](https://github.com/user-attachments/assets/d2846c97-6917-4af8-b5c6-a41544c5f148) |
| ![슬라이드47](https://github.com/user-attachments/assets/d1e25852-ffe6-4d59-9df4-2f76966eaac1) | ![슬라이드48](https://github.com/user-attachments/assets/674a906d-3edc-46eb-b806-1a281d371b6b) |
| ![슬라이드49](https://github.com/user-attachments/assets/d1bc9a44-8d82-49ce-9b23-fbba31ce807b) | ![슬라이드50](https://github.com/user-attachments/assets/5de775c9-0c83-484b-9e73-a94230548d8c) |
| ![슬라이드51](https://github.com/user-attachments/assets/c7bf2be9-1e65-4630-a55f-685286c04d3e) | ![슬라이드52](https://github.com/user-attachments/assets/05f498be-ddfe-4af5-bec8-e6d7bdb1319a) |
| ![슬라이드53](https://github.com/user-attachments/assets/78376933-d8c2-4b47-ad34-220167454c30) | ![슬라이드54](https://github.com/user-attachments/assets/ea6c32f3-66f2-41f8-9c4f-f91098cc79bc) |
| ![슬라이드55](https://github.com/user-attachments/assets/57a08018-d263-43a4-bddf-7e5dc369251d) | ![슬라이드56](https://github.com/user-attachments/assets/32e886dd-fc3e-442f-afb2-d19eb0a6d0f5) |
| ![슬라이드57](https://github.com/user-attachments/assets/f222aa6d-50a5-4cea-a567-2b23218559ce) | ![슬라이드58](https://github.com/user-attachments/assets/36b7cb64-db6d-4e13-b23a-3a58a29d1ee8) |
| ![슬라이드59](https://github.com/user-attachments/assets/50a9cc77-be75-4fd3-a377-fb86229b9da9) | ![슬라이드60](https://github.com/user-attachments/assets/bff12359-fb9a-44fb-bf47-d4ce3e64544a) |
| ![슬라이드61](https://github.com/user-attachments/assets/36270ed7-6fdd-4160-bd3e-68a65365d5a4) | ![슬라이드62](https://github.com/user-attachments/assets/020de04d-4ee0-4f80-a822-06a38166a5dd) |
| ![슬라이드63](https://github.com/user-attachments/assets/c1df45dd-c490-4741-9597-5ecdc1e423b4) | ![슬라이드64](https://github.com/user-attachments/assets/4f4a0dc0-ba6d-4d53-96a6-cbb75f00dd89) |
| ![슬라이드65](https://github.com/user-attachments/assets/a2d2ed80-ab46-4022-b067-195623e749fa) | ![슬라이드66](https://github.com/user-attachments/assets/713c6652-ce70-4176-874a-9fe258bbe3cf) |
| ![슬라이드67](https://github.com/user-attachments/assets/ac101651-b00d-478a-9ab5-d5bf00fe9914) | ![슬라이드68](https://github.com/user-attachments/assets/23d6921f-f7e3-49b3-803f-5d3136497f6d) |
| ![슬라이드69](https://github.com/user-attachments/assets/5a59d452-fe2a-4c3e-affd-9dd59c5369cb) | ![슬라이드70](https://github.com/user-attachments/assets/b90f6e07-ac4c-4849-86db-a22853a633b1) |
| ![슬라이드71](https://github.com/user-attachments/assets/96900c85-e078-4b92-8cd8-190d2759030a) | ![슬라이드72](https://github.com/user-attachments/assets/77337706-26e8-477a-87cc-7cbb5bfbd2fe) |
| ![슬라이드73](https://github.com/user-attachments/assets/b45fa5cb-b5f3-484c-b877-80e4da60afca) | ![슬라이드74](https://github.com/user-attachments/assets/962a87be-df0e-4f25-8bc1-24121d537bdd) |
| ![슬라이드75](https://github.com/user-attachments/assets/6353ffb5-e417-45fc-90f9-d5afc8caa729) | ![슬라이드76](https://github.com/user-attachments/assets/323714b9-61ae-4a9f-8313-81f23565a097) |
| ![슬라이드77](https://github.com/user-attachments/assets/ec66b0ec-74eb-4b62-994e-7ca023377d44) | ![슬라이드78](https://github.com/user-attachments/assets/66c3b5c0-07d6-4292-9bb3-d93f0d2dcd84) |
| ![슬라이드79](https://github.com/user-attachments/assets/ec0d674d-0248-428a-aa99-38b7c9906bbe) | ![슬라이드80](https://github.com/user-attachments/assets/d5ecb41e-c907-45c9-80af-9354feefd676) |
| ![슬라이드81](https://github.com/user-attachments/assets/f101b531-cf98-43e7-887a-5118f7d1be5b) | ![슬라이드82](https://github.com/user-attachments/assets/4632f8b7-4a0d-4a19-a07e-d72b59aac2d1) |
| ![슬라이드83](https://github.com/user-attachments/assets/4b579774-89ff-466e-b1a9-dae1a2337006) | ![슬라이드84](https://github.com/user-attachments/assets/d08f3435-fc67-4e43-b4ab-4a3908f84488) |
| ![슬라이드85](https://github.com/user-attachments/assets/e01ce4e5-ed30-4ad6-91cc-eca8befc2f28) | ![슬라이드86](https://github.com/user-attachments/assets/904fac38-410f-4355-a156-6806156e0cd7) |
| ![슬라이드87](https://github.com/user-attachments/assets/31ad0389-6512-4d37-afc3-75cd53314b2e) | ![슬라이드88](https://github.com/user-attachments/assets/fba4c27f-bd0f-464f-93d8-5dbaee4662cc) |
| ![슬라이드89](https://github.com/user-attachments/assets/f8a76825-4699-4472-a675-24be8aa21e96) | ![슬라이드90](https://github.com/user-attachments/assets/cccb6e68-d771-492a-a6e1-e3e52f6e6b83) |
</div>
</details>
</br>

## 🚀 개선사항
</br>
<h3>1. 타임세일 기능 미구현</h3>
<p>- 아쉬운점 : 특정 시간에 상품이 자동 종료되는 기능을 구현하지 못함</p>
<p>- 개선점 : 스케쥴러를 활용하여 자동화 기능을 추가할 예정</p>

<h3>2. VO와 DTO를 깔끔하게 정리하지 못하였음</h3>
<p>- 아쉬운점 : VO와 DTO의 역할이 명확하지 않아 코드 구조가 혼란 스러움</p>
<p>- 개선점 : DTO는 데이터 전달, VO는 값 표현 객체로 일관성 있도록 조정</p>

<h3>3. 예외처리 미흡</h3>
<p>- 아쉬운점 : 오류 발생 시 사용자 친화적인 안내 부족</p>
<p>- 개선점 : 공통 에러 페이지 및 예외 처리 로직 강화</p>

<h3>4. 테스트 코드 부족</h3>
<p>- 아쉬운점 : 기능별 단위 테스트 및 통합 테스트가 충분하지 않음</p>
<p>- 개선점 : JUnit, Mockito 등을 활용하여 테스트 코드 보강</p>

<h3>5. 공통 모듈화 부족</h3>
<p>- 아쉬운점 : 일부 코드가 중복되어 유지 보수성이 떨어짐</p>
<p>- 개선점 : 공통 모듈 및 유틸 클래스로 중복 제거</p>

<h3>6. 쿠폰 시스템 미구현</h3>
<p>- 아쉬운점 : 할인 및 프로모션 기능이 제공되지 않음 </p>
<p>- 개선점 : 쿠폰 발급 및 적용 로직 추가 예정</p>

<h3>7. 결제 API 미적용</h3>
<p>- 아쉬운점 : 시간 부족으로 인하여 외부 결제 서비스와의 연동이 이루어지지 않음 </p>
<p>- 개선점 : 결제 API 연동 예정</p>
