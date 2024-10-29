# project1-2024
2024-2학기 캡스톤 프로젝트 수업
OpenAPI를 사용한 인공지능 시스템 실습

# openweathermap
지정된 장소의 현재 날씨를 표시
http://api.openweathermap.org/data/2.5/weather?q=Seoul&units=metric&appid=7d96bc5108f52b80e2d9075a369b9f35
  [실습해보기]('http://api.openweathermap.org/data/2.5/weather?q=Seoul&units=metric&appid=7d96bc5108f52b80e2d9075a369b9f35)

```javascript
$.ajax({
			type: "GET",
			url: 'http://api.openweathermap.org/data/2.5/weather?q=Seoul&units=metric&appid=7d96bc5108f52b80e2d9075a369b9f35',
		}).done(function(response) {
         
            console.log(response)
        
		}).fail(function(error) {
			alert("!/js/user.js에서 에러발생: " + error.statusText);
		});
```
# openai

# google cloud vision

개발순서
1. 소스수정
2. 소스 저장
3. 스테이지
4. 커밋앤 푸쉬
5. 커밋메세지







2024sus-9-19 깃허브 연동 실습
로컬에서 편집함
