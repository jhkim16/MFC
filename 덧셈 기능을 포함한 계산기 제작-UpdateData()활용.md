1. Visual Studio 실행후 새 프로젝트 만들기
![1](https://user-images.githubusercontent.com/50655965/65041005-be231900-d990-11e9-90df-dc63281d4258.PNG)

2. 검색창에 MFC 검색, MFC 앱 클릭 후 다음 선택
![2](https://user-images.githubusercontent.com/50655965/65041006-bf544600-d990-11e9-832e-7edf3f4974f1.PNG)

3. 프로젝트 이름을 자유롭게 수정 후 "솔루션 및 프로젝트를 같은 디렉터리에 배치" 체크 후 만들기 클릭
![3](https://user-images.githubusercontent.com/50655965/65041013-c1b6a000-d990-11e9-9bde-b4a70772fb23.PNG)

4. 애플리케이션 종류 - 대화 상자 기반 클릭 후 마침
![4](https://user-images.githubusercontent.com/50655965/65041014-c1b6a000-d990-11e9-9428-0d0901c0af3c.PNG)

5. 최초 실행이 된 화면입니다.
![5](https://user-images.githubusercontent.com/50655965/65041016-c1b6a000-d990-11e9-9f8b-fb846f9c219a.PNG)

6. 솔루션 탐색기 > 프로젝트 이름 > 리소스 파일 > 프로젝트 이름.rc 파일 더블 클릭
![6](https://user-images.githubusercontent.com/50655965/65041018-c24f3680-d990-11e9-8498-1365e97d0748.PNG)

7. 리소스 뷰로 이동한 모습입니다.
![7](https://user-images.githubusercontent.com/50655965/65041020-c24f3680-d990-11e9-8789-2cd829823e02.PNG)

8. 프로젝트 이름.rc > Dialog > IDD_프로젝트 이름_DIALOG 로 이동
![8](https://user-images.githubusercontent.com/50655965/65041021-c24f3680-d990-11e9-8dbc-87b7f7eaa3da.PNG)

9. 중간에 TODO, 하단부의 확인/취소를 지우고 시작하겠습니다.
![9](https://user-images.githubusercontent.com/50655965/65041022-c24f3680-d990-11e9-922d-b1650b2b08cf.PNG)

10. 좌측 도구 상자에서 Check Box 3개를 가져옵니다. 이후 우하단 속성탭에서 모양 > Align Text > Center 선택으로 정렬해줍니다. 
![10](https://user-images.githubusercontent.com/50655965/65041023-c2e7cd00-d990-11e9-9b0c-751a07dc466c.PNG)

11. 좌측 도구 상자에서 Button 1개를 가져온 후, 속성 탭에서 모양 > Caption 의 IDC_BUTTON1을 +로 변경해줍니다.
![11](https://user-images.githubusercontent.com/50655965/65041024-c2e7cd00-d990-11e9-84d5-2b793a7bb916.PNG)

12. 이후 각 Check Box마다 우클릭 > 변수 추가를 클릭한 후
![new1](https://user-images.githubusercontent.com/50655965/65043451-ec572780-d995-11e9-8795-e983d968f55c.PNG)

13. 범주 - 값, 이름 - 자유(실습에서는 m_a, m_b, m_c로 사용했습니다.), 변수 형식 - int 로 변경 후 마칩니다.
![new2](https://user-images.githubusercontent.com/50655965/65043452-ec572780-d995-11e9-8ec2-725de4a351a5.PNG)

14. 이후 버튼을 더블클릭한 후 OnBnClickedButton1()에 코드를 넣습니다.
![new3](https://user-images.githubusercontent.com/50655965/65043453-ecefbe00-d995-11e9-9b6b-37078c730b0f.PNG)

15. 구동된 계산기의 모습입니다.
![new4](https://user-images.githubusercontent.com/50655965/65043455-ecefbe00-d995-11e9-9aa7-353e449523ee.PNG)