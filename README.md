# Gieok_여행 명소 제공 서비스

![기억하자소개](https://github.com/gieokicu/Gieok/assets/74278791/1280440e-9760-4d42-8cb5-f4852874ea89)

![기억하자소개2](https://github.com/gieokicu/Gieok/assets/74278791/3c3bf713-d65f-43fe-9337-455c0d036ab5)


<br>

## 1. 주요 기능
- 등록된 여행 명소, 베스트 사진, 명소 순위 통함 검색
- 특정 지역 선택 시 해당 지역의 관광 명소 정보 제공
- 공지, 포토, 이벤트 등록 및 확인
- 여행을 위한 동행 신청 및 수락 기능 제공

<br>

## 2. 개발 환경

![개발환경](https://github.com/gieokicu/Gieok/assets/74278791/a4ff0cc6-5813-40c7-84d9-b543885b45f7)

<br>

## 3. 개발 기간 및 프로젝트 구조

**3-1. 개발 기간**
- 개발 인원 : 6명
- 개발 기간 : 2022.10.04 ~ 2022.11.10 (1개월)

**3-2. 프로젝트 구조**
- 구성도
![image](https://user-images.githubusercontent.com/108389588/212534580-b2549274-5547-45e0-8ded-98d56f29120e.png)

- UI 디자인  
  https://www.figma.com/file/PdyvJkfA6g5cS68hADXEFW/Project_KG?type=design&node-id=5-186&t=wQubGrQMMfkcTjZb-0 
  ![기억하자_피그마_1](https://github.com/gieokicu/Gieok/assets/74278791/1b11783e-2b7e-4755-8378-a505a867f5ec)
  
- ERD  
  https://www.erdcloud.com/d/mLF5wSFnyXe3udmJT
  ![image](https://user-images.githubusercontent.com/108389588/212534594-896393b3-75db-462b-a48d-15152f3e8882.png)
  

<br>

## 4. 팀원 소개

<table style="border: 1px solid white;">
    <tr>
        <th style="border-right: 1px solid white; text-align: center; width: 80px">
            이름
        </th>
        <th style="text-align: center; width: 500px;">
            담당 기능
        </th>
    </tr>
    <tr>
        <td style="border-right: 1px solid white; text-align: center;">이진혁</td>
        <td>
            - 지도 SVG <br>
            - 명소 (등록/수정/삭제) <br>
            - 명소 상세 (리뷰/별점/좋아요) <br>
            - 이메일 인증 <br>
            - 메세지 <br>
            - DB 설계/수정 <br>
        </td>
    </tr>
    <tr>
        <td style="border-right: 1px solid white; text-align: center;">김태홍</td>
        <td>
            - 공지 및 이벤트 (등록/수정/삭제) <br>
            - 통합 검색 <br>
            - 시큐리티 적용 <br>
            - 비밀번호 암호화 <br>
            - Summernote API 구현 <br>
            - About 페이지 <br>
        </td>
    </tr>
    <tr>
        <td style="border-right: 1px solid white; text-align: center;">오흥식</td>
        <td>
            - 회원가입 (정보수정/탈퇴) <br>
            - 회원관리 (관리자 권한 부여 및 삭제) <br>
            - 포토 이벤트 관리 (등록/수정/삭제) <br>
            - 포토 이벤트 (좋아요/신고) <br>
            - 여행 일정 관리 <br>
            - UI 디자인 <br>
        </td>
    </tr>
    <tr>
        <td style="border-right: 1px solid white; text-align: center;">조서진</td>
        <td>
            - 메인 페이지 (등록/검색/상세) <br>
            - 회원가입 상세 <br>
            - UI 디자인 <br>
        </td>
    </tr>
    <tr>
        <td style="border-right: 1px solid white; text-align: center;">허진영</td>
        <td>
            - 동행 목록 <br>
            - 동행 등록/삭제/신고 <br>
            - 신청한 동행 목록 <br>
            - Summernote API 구현 <br>
            - Favicon 제작 및 적용 <br>
            - 도메인 및 SSL 인증서 관리 <br>
            - Name Server 관리 <br>
            - 서버 방화벽 설정 <br>
            - 서버 세팅 및 배포 <br>
        </td>
    </tr>
    <tr>
        <td style="border-right: 1px solid white; text-align: center;">허현주</td>
        <td>
            - 명소 목록 <br>
            - 주변시설 (등록/수정/삭제) <br>
            - 나의 동행 목록 <br>
            - 동행 수락 <br>
            - 카카오 지도/주소 API 구현 <br>
            - DB 설계 / 수정 <br>
            - 서버 세팅 및 배포 <br>
        </td>
    </tr>

</table>

<br>

## 5. 주요 UI

**5-1. 메인화면**

![메인페이지](https://github.com/gieokicu/Gieok/assets/74278791/71e94351-1458-455d-8c24-07edeef179fa)

**5-2. 로그인**

![로그인](https://github.com/gieokicu/Gieok/assets/74278791/3d29424b-5ae5-42cd-8038-61e99a19935f)

**5-3. 여행 명소 제공**

![어디갈래](https://github.com/gieokicu/Gieok/assets/74278791/b9c81cb2-9776-43f4-b816-5c2f2ff308c8)


**5-4. 명소 / 주변시설 목록, 등록**

![명소등록](https://github.com/gieokicu/Gieok/assets/74278791/1ca6f0a7-a439-42a0-bbca-99c7d7299783)

**5-5. 여행 동행 신청**

![동행게시판](https://github.com/gieokicu/Gieok/assets/74278791/02f7f14d-c60a-48f1-9733-8e91c2dc1933)

![동행수락](https://github.com/gieokicu/Gieok/assets/74278791/61f49b4a-62c1-40b6-b8c1-946ca46bceef)

**5-6. 메세지**

![메세지보내기](https://github.com/gieokicu/Gieok/assets/74278791/caadecea-fd1d-4d9d-8dac-9b5eb3e5bdae)

![메세지확인](https://github.com/gieokicu/Gieok/assets/74278791/2c2f87b6-6558-49e7-9a96-5b71462942d6)

**5-7. 공지/이벤트**

![공지이벤트](https://github.com/gieokicu/Gieok/assets/74278791/0bf3c503-2596-40a4-9449-44339c5312ed)

**5-8. 포토이벤트**

![포토이벤트](https://github.com/gieokicu/Gieok/assets/74278791/cb8ff90f-9d37-447c-bd02-ba1da8d43136)

**5-9. 내가 쓴 리뷰**

![내가쓴리뷰](https://github.com/gieokicu/Gieok/assets/74278791/86c9e96a-0628-424e-b45b-41c8d7e2ffde)

**5-10. 회원관리(관리자)**

![회원관리자목록](https://github.com/gieokicu/Gieok/assets/74278791/3b2b824a-e5eb-41cd-875a-ea584f2bf53c)

**5-11. 이벤트 등록**

![이벤트등록](https://github.com/gieokicu/Gieok/assets/74278791/d0213400-3c0e-4a9a-9276-cbc115189b16)

**5-12. 신고목록**

![신고목록](https://github.com/gieokicu/Gieok/assets/74278791/569842a9-011e-40dc-acd2-ea16dd1aa962)

<br>

## 6. 배포

**6-1. 배포URL**

- gieok.icu

- www.gieok.icu

**6-2. 배포환경**

![서비스배포](https://github.com/gieokicu/Gieok/assets/74278791/9656eb01-f00a-46ff-8b25-dcc94e84597d)

![서비스배포2](https://github.com/gieokicu/Gieok/assets/74278791/e016d1f0-5a98-4124-83e1-9be82526d4e9)

<br>

## 7. 회고록

><b>이진혁</b> <br><br> 
느낀점 : <br>
나름 생각을 많이 하고 충분한 토의를 거쳐서 기획했다고 생각했는데 개발을 진행하면서 기획력이 많이 부족했고 처음 팀장을 맡아봤기에 많이 서툴어 팀원들이 많이 고생했을것 같습니다. 마지막으로 사람은 거짓말을 하지만 컴퓨터는 거짓말을 하지 않는다는 점을 다시 한번 깨달았습니다. <br><br> 
어려웠던 부분 : <br>
개인이 아닌 팀으로써 협업을 하면서 효율적으로 역할을 분담하고 공통 부분을 통일하는게 생각보다 어려웠습니다. 그리고 학원에서 배운것만으로는 원하는 기능을 갖춘 서비스를 만드데에는 한계가 있었습니다. <br><br> 
어떻게 해결? : <br>
협업이라는 과정을 거치는 부분에서 생기는 문제들은 모두 서로의 다른 의견과 관점을 받아드리고 존중하는 자세를 갖추자는 마음가짐을 가지고 꾸준한 소통을 통해서 해결했습니다. 배움에 있어 부족했던 부분은 주로 구글과 유튜브를 통한 학습 그리고 팀원들로부터 제가 잘 모르고 부족했던 부분을 채워나가며 해결했습니다. <br><br> 
앞으로 계획 : <br>
앞으로 기회가 된다면 이번에 진행했던 프로젝트를 보완하고 더 개발을 해서 사람들이 이용할 수 있는 서비스를 운영해보고 싶습니다. 또한 아직 접하지 못한 새로운 기술 스택을 쌓아서 개인적인 프로젝트도 진행해보고 다른 사람들과 새로운 프로젝트에 참여해서 다양한 서비스를 제공할 수 있는 사이트도 만들어볼 계획입니다.

<hr style="border-style:dotted;" />

><b>김태홍</b> <br><br> 
느낀점 : <br>
소통의 부족으로 프로젝트 기획 및 진행에 많은 영향을 받았습니다. 특히 각자 맡은 부분에서 진행에 대한 소통이 부족하여 진척률이 현저히 떨어지는 경우도 있었습니다. 이를 통하여 소통의 중요성을 다시 한번 경험했습니다. <br><br> 
어려웠던 부분 : <br>
학원의 교육만으로는 프로젝트의 완성시키는데 힘든 점이 있었고 개발에 대한 경험의 부족으로 다양한 상황에서의 대처 능력이 부족했습니다. <br><br> 
어떻게 해결? : <br>
실제로 프로젝트에서 다양한 기능을 추가하려고 하니 혼자서 해결하지 못하는 점이 많았습니다. 이런 점을 해결하기 위해 학원 교육 이외에도 추가적인 공부를 했고 팀원 및 다른 학우들과 스터디를 통하여 부족한 점을 채우면서 서로의 기량을 향상 시킬 수 있었습니다. <br><br> 
앞으로 계획 : <br>
비전공자로서 개발 공부를 시작하다보니 배워야하는 범위가 광범위한 걸 느꼈습니다. 개발쪽 공부만이 아니라 이에 도움을 줄 수 있는 서버 또는 보안쪽 공부도 같이 병행하여 저의 기량을 향상 시킬 예정입니다.
</p>

<hr style="border-style:dotted;" />

><b>오흥식</b> <br><br> 
느낀점 : <br>
개발은 혼자 할 수 없다는 것과 협업의 필요성을 다시 한번 상기하게 되었고 협업에 있어서 빠르게 내 능력을 파악하는 것, 그리고 내가 맡은 일과 그렇지 않은 일을 구분하는 것, 많은 경험과 반복 학습이 중요하다는 것 들을 느꼈습니다. <br><br>
어려웠던 부분 : <br>
많은 부분에서 어려움을 느꼈지만 제일 기억에 남는 점을 꼽자면 내 역할이 어디서부터 어디까지인지 파악하고, 이 프로젝트에서 내가 할 수 있는 것과 할 수 없는 일을 구분하고 무엇에 우선순위를 둘 지 선택하고 집중하는 것이었습니다. <br><br>
어떻게 해결? : <br>
좀 더 팀원을 의지하고 나눌 수 있는 것들은 나누었고 지금 제가 할 수 있는 것들에 좀 더 집중하였습니다. 부족한 부분은 공유하고 내가 채울 수 있는 부분은 채워가면서 좀 더 효율적으로 프로젝트를 진행 할 수 있었습니다. <br><br>
앞으로의 계획 : <br>
아직 구현하지 못했던 부분들과 해보지 못했던 부분들을 공부하고 채워나가면서 사이트를 완성시킬 것이며, 새로운 웹 애플리케이션을 계획하고 구현해보면서 더 많은 개발 과정을 경험할 것입니다.
</p>

<hr style="border-style:dotted;" />

><b>조서진</b> <br><br> 
느낀점 : <br>
무엇보다 어느 분야에서 일을 하고 프로젝트를 수행하더라도 중요한 것은 실력보다 여러 사람들과의 커뮤니케이션이라는 것을 다시금 톺아보았습니다. 본인과 타인을 수용 할 줄 아는 태도를 갖고 큰 그릇이 되어야 한다고 다짐했습니다 :) <br><br>
어려웠던 부분 : <br>
소통 및 협업 <br><br>
어떻게 해결? : <br>
솔직하고 건강한 발칙함으로 끊임없이 모두의 문을 두드렸습니다. <br><br>
앞으로 계획 : <br>
결국 우리는 모두 행복을 찾습니다. 삶이 일로써 소비된다면 일을 사랑하는 것이 삶을 사랑하는 가장 중요한 열쇠라고 생각합니다. 일에 도전하고 동기를 부여하고 보상을 얻는 것은 따분하고 평범한 작업을 하는 것보다 아침에 더 일어나고 싶게 만들었습니다. 이제야 방향성을 잡았고 제 결정에 대한 확신을 갖게 되었습니다. 항상 낮은 자세로 제너럴리스트로서 전방위적으로 배워 나가고, 먼 훗날엔 특정 분야에서 두각을 드러내는 스페셜리스트를 감히 꿈 꿔 봅니다 :) <br><br>
</p>

<hr style="border-style:dotted;" />

><b>허진영</b> <br><br> 
느낀점 : <br>
혼자 하는 것이 아니라 팀원들과 함께 하나의 프로젝트를 완성시킨다는 것은 결코 쉬운 일이 아니었습니다. <br><br>
어려웠던 부분 : <br>
개발 경험이 많지 않았고 기획이 구체적으로 결정되어 있지 않은 상태에서 모두가 의견을 조율하여 프로젝트를 진행한다는 것은 쉽지 않았습니다. 팀원들끼리 서로 의견이 다른 부분들이 많았는데 여러 의견들을 조율하면서 프로젝트를 진행해 나아가는 것이 다소 어렵게 느껴지는 순간들이 있었습니다. <br><br>
어떻게 해결? : <br>
의견이 다를 때마다 팀원들과 투표를 통하여 의견을 모아 결정할 수 있었고, 또 서로 다른 역할을 맡아 미흡한 부분들 또는 미처 생각하지 못했던 부분들을 함께 도와가며 프로젝트를 완성할 수 있었습니다. <br><br>
앞으로 계획 : <br>
취업을 하게 되더라도 꾸준히 공부하여 스스로의 개발 역량을 높여나갈 것이며, 그동안 프로젝트를 진행하면서 부족했던 부분들을 더 나은 결과물로 채워나갈 수 있도록 다양한 경험들을 쌓아 해결해나갈 계획입니다. 
</p>

<hr style="border-style:dotted;" />

><b>허현주</b> <br><br> 
>느낀점 : <br>
>기능 구현 시 테이블 설계, 구현 방법 등에 대해서 잘 기획해놓고 진행할수록 이슈를 최소화하고 개발 시간을 단축할 수 있다는 것을 느꼈습니다. <br><br>
>어려웠던 부분 : <br>
>초반 기능 개발 시 큰 기능에 대한 것만 논의 후 진행하였습니다. 그러다 보니 개발 진행 중 각 기능에 대해 수시로 논의하고 진행하는데 많은 시간이 소요되었습니다. <br><br>
>어떻게 해결? : <br>
>기능 구현 시 사전에 가능한 팀원들과 함께 정리하고 기획하며 진행한 결과 좀 더 꼼꼼하게 기능을 구현하며 개발 시간을 단축할 수 있었습니다. 또한 개발 QA 진행 시 해당 내용을 바탕으로 이슈를 확인하고 수정할 수 있었습니다. <br><br>
>앞으로 계획 : <br>
>프로젝트를 진행하며 부족하다고 느꼈던 부분에 대해 좀 더 공부하며 향상 시킬 계획입니다.
></p>



