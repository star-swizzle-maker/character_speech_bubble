# character_speech_bubble  
Speech bubble code for Obsidian Notes and web pages.  

<img width="500" alt="Screenshot 2025-03-15 at 4 15 31 PM" src="https://github.com/user-attachments/assets/03abfbc2-2b57-4b4f-aa47-a9beb8c9374f" />
<img width="500" alt="Screenshot 2025-03-15 at 1 22 09 AM" src="https://github.com/user-attachments/assets/04b882e7-7b65-4ff9-acb1-e08f870b7255" />


This code can be used in your Obsidian note app or personal website.  

Please update the image URL as needed.  

---

# 캐릭터 말풍선 코드  
## 소개
Obsidian 노트 앱과 웹 페이지에서 사용할 수 있는 말풍선 코드입니다.  

이 코드는 Obsidian 노트 앱이나 개인 웹사이트에서 사용할 수 있습니다.  

실제 사용시엔 이미지 URL을 변경해 주세요.  

## 설정방법

1. web_speech_bubble.css안의 코드를 웹페이지 css 설정 아래에 붙여 넣는다.

2. web_speech_bubble.html 안의 

```html
<div class="chat-container">
	<div class="chat-header">
		<img class="character-avatar" src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fblfn5u%2FbtsMLxjGKNN%2F9Iab123BsKKKqjrSHxCNT1%2Fimg.jpg" alt="트와일라잇" />   <!-- input image addres -->
		<span class="character-name">트와일라잇</span>  <!-- input character's name -->
	</div>
	<div class="speech-bubble">  <!-- input character's speech -->
	참 간단하죠?
	</div>
</div>
```

이 부분을 글 작성시 html 편집기에 붙여넣여 넣는다.

3. `src=""` 여기 큰따옴표 안에 이미지 주소를 넣는다.
4. `<span class="character-name">트와일라잇</span>` tag 사이에 캐릭터 이름을 기입한다.
5. `<div class="speech-bubble">참 간단하죠?</div>` tag 사이에 대사를 기입한다.
6. 끝


