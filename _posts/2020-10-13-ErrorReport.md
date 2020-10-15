---
layout: post
title: "[Error]개체가 'addEventListener' 속성이나 메서드를 지원하지 않습니다."
date:   2020-10-14
excerpt: "IE에서 웹사이트 실행 시 개체가 'addEventListener' 속성이나 메서드를 지원하지 않습니다. 에러 처리"
tag:
- error
- debug
- ie
- 호환성
- 속성
- 메서드
- addEventListener
- jQuery
comments: true
---
# Content 
갑자기 에러 접수로 해당 메시지의 이미지만 올라와 당황을 시켰던 오류 메시지이다.<br>
자체 테스트 시 해당 오류가 발생하지 않아 설정 문제라고 판단하여, <br>
구글링으로 해당 에러 메시지에 대한 부분을 찾아 적용하니 해결되었다.<br>
해당 오류는 주로 jQuery 사용 시 IE에서 '호환성 보기' 설정이 되있을 경우 발생한다고 한다.
## Error Message 
![ErrorMessage](/assets/img/posts/2020-10-13-ErrorReport_01.JPG)<br>
개체가 'addEventListener' 속성이나 메서드를 지원하지 않습니다.
## Debug 
'개체가 'addEventListener' 속성이나 메서드를 지원하지 않습니다.'로 구글링.
## Error Reslove 
![ErrorReslove](/assets/img/posts/2020-10-13-ErrorReport_02.JPG)<br>
IE 설정 중 '호환성 보기'에서 해당하는 웹사이트 제거.
## 참고
- [SonMan's IT BBS 블로그](http://son10001.blogspot.com/2017/05/ie-addeventlistener.html)
