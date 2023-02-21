# likelion html
## html : 정보에 집중

1. strong : 글씨 진하게
2. h1 : 제목 (굵고 큰 문자, 줄 바꿈)
3. h2 : 소제목
4. a : 주소
- href="주소" : 링크 걸기
- target ="_blank" : 새로운 창에 열기
- title ="제목" : 링크에 이름달기

5. li : list로 정리
- ui : 그룹핑 리스트들 묶어주기 (순서가 없는 리스트)
```
<ul>
    <li>기술소개</li>
    <li>기본 문법</li>
    <li>하이퍼텍스트와 속성</li>
    <li>리스트와 태그의 중첩</li>
</ul>
<ul>
    <li>최진혁</li>
    <li>최유빈</li>
    <li>한아람</li>
    <li>한이은</li>
</ul>
```

- ol : 그룹핑 리스트들 묶어주기 (순서가 있는 리스트) 
```
<ol>
    <li>기술소개</li>
    <li>기본 문법</li>
    <li>하이퍼텍스트와 속성</li>
    <li>리스트와 태그의 중첩</li>
</ol>
<ol>
    <li>최진혁</li>
    <li>최유빈</li>
    <li>한아람</li>
    <li>한이은</li>
</ol>
```
6. title: 탭의 제목 
7. ``` <meta charset="utf-8"> ``` : 글씨 깨지면 사용
8. ``` <DOCTYPE html> ``` : Documeny type 의 html
9. font color="색": 글씨 색 바꿈

## css : 디자인
1. li 글씨를 모두 빨간 색으
```
    <style>
        li{
            color:red;
        }
    </style>

    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
```
2. 선택자와 선언
- li- 선택자
- color:red; -선언
- color - 속성
- red -  속성값
- : 속성과 속성값을 구분해주 구분자
- ; 선언과 선언을 구분해주는 구분자
3. id선택자는 단 한번 클래스 선택자는 여러번 등장해서 그룹핑
