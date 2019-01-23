# API Project

### **파일 트리 구조**

```
**movie/**
​    ├─────images                            

​    │       └ *.jpg                            

​    │                                                       

​    ├─────    app.py                       

​    ├─────    boxoffice.csv

​    ├─────    movie.csv

​    ├─────    movie_naver.csv

​    └─────    README.md
```



### 폴더 및 파일 설명

**movie/**



**images/**    :   movie_naver.csv의 thumb_url 조회, jpg 파일이 저장된 폴더

- 영진위 영화 대표코드(movieCd.)jpg 형태 43개  ex) 20010291.jpg



**app.py**      : 

- #===을 구분으로 1번 : boxoffice.csv //  2번 : movie.csv //  3번 : movie_naver.csv //  4번 : 이미지 저장



**boxoffice.csv**    : 

- 영화 대표코드, 영화명, 해당일 누적관객수, 조회일



**movie.csv**    :

- 영화 대표코드, 영화명 (국문), 영화명 (영문), 개봉연도, 상영시간,장르, 감독명, 관람등급, 배우1,배우2,배우3



**movie_naver.csv**    :

- 영진위 영화 대표코드, 영화 썸네일 이미지의 URL,  하이퍼텍스트 link, 유저 평점



