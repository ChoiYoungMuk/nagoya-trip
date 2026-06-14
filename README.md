# 나고야 가족여행 사이트

## 이미지 이스터에그

비행기 아이콘을 클릭하면 `images` 폴더 안의 사진 중 하나가 랜덤으로 나타납니다.

현재 테스트 이미지:

- images/nagoya-castle-01.jpg

나중에 사진을 추가하려면:

1. images 폴더에 사진 추가
2. index.html의 `TRAVEL_PHOTOS` 배열에 아래처럼 추가

```javascript
{ src: "./images/nephew-01.jpg", title: "우리 조카", sub: "여행의 귀여운 주인공" }
```

파일명은 영문/숫자/하이픈 추천.
