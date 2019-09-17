1. Visual Studio 실행후 새 프로젝트 만들기
![1](https://user-images.githubusercontent.com/50655965/65044308-a0a57d80-d997-11e9-8e0e-57feabbf0f68.PNG)

2. 검색창에 MFC 검색, MFC 앱 클릭 후 다음 선택
![2](https://user-images.githubusercontent.com/50655965/65044309-a13e1400-d997-11e9-8a78-8b050c91280b.PNG)

3. 프로젝트 이름을 자유롭게 수정 후 "솔루션 및 프로젝트를 같은 디렉터리에 배치" 체크 후 만들기 클릭
![3](https://user-images.githubusercontent.com/50655965/65044310-a13e1400-d997-11e9-8b6b-e60b15fde999.PNG)

4. 애플리케이션 종류 - 대화 상자 기반 클릭 후 마침
![4](https://user-images.githubusercontent.com/50655965/65044311-a1d6aa80-d997-11e9-867c-ca8f1407f3f8.PNG)

5. 솔루션 탐색기 > 프로젝트 이름 > 리소스 파일 > 프로젝트 이름.rc 파일 더블 클릭
![5](https://user-images.githubusercontent.com/50655965/65044314-a1d6aa80-d997-11e9-8f8e-692b4b3c25dd.PNG)

6. 프로젝트 이름.rc > Dialog > IDD_프로젝트 이름_DIALOG 로 이동
![6](https://user-images.githubusercontent.com/50655965/65044315-a1d6aa80-d997-11e9-8644-b39800cb3e56.PNG)

7. Dialog의 창을 클릭한 후 우하단 메시지 탭 > WM_MOUSEMOVE의 화살표 박스 클릭 후 <Add> OnMouseMove 클릭
![7](https://user-images.githubusercontent.com/50655965/65044316-a1d6aa80-d997-11e9-846a-0df9f6e4556a.PNG)

8. OnMouseMove 함수에 코드를 넣습니다. 함수 밖에 size변수와 pnt변수를 미리 선언해둡니다.
![8](https://user-images.githubusercontent.com/50655965/65044318-a26f4100-d997-11e9-836a-c9d629875459.PNG)

9. 구동된 다이얼로그 기반의 펜 프로그램입니다.
![9](https://user-images.githubusercontent.com/50655965/65044319-a26f4100-d997-11e9-980c-e20f51461b60.PNG)
