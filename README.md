# ScriptableKakaoBot
### 쓰는법?
0) 카톡 알림 키세요<br>
1) kbot 디렉토리를 /sdcard-directory/ 에 생성합니다.<br>
2) response.js를 /sdcard-directory/kbot/ 에 생성합니다.<br>
3) response 함수를 정의합니다.<br>
```js
function response(room, msg, sender) {
  /* room - 방 이름
     msg - 메세지 내용
     sender - 발신자 이름 */
}
```
이 함수는 카톡 알림이 오면 호출됩니다.<br>
4) 앱을 엽니다.<br>
5) 온/오프 버튼을 통해 봇을 작동시킬지 안할지 결정합니다.<br>
6) 권한 설정하러 가기 버튼을 통해 알림 권한을 활성화 할 수 있습니다.<br>
7) 스크립트 리로드 버튼을 통해 적용된 스크립트를 업데이트 할 수 있습니다.<br>

### API
`Kakaotalk` - 봇 API를 제공하는 전역 객체<br>
`Kakaotalk.replyLast` - 가장 최근 알림에 대해 답장합니다
