# STL 넣는 곳

1. STL 파일 이름을 영문·숫자·하이픈으로 바꿔 이 폴더에 올립니다. (예: `skin-panel-patch.stl`)
2. `models.json`의 `models`에 한 줄 추가합니다.

```json
{
  "models": [
    { "id": "skin-patch", "name": "외판 패치", "file": "skin-panel-patch.stl" }
  ],
  "links": []
}
```

3. 1~2분 뒤 앱의 **관리** 화면에서 Step에 모델을 연결하고, 시점과 표시 핀을 맞춘 다음 **[models.json 내보내기]**로 받은 파일을 이 폴더의 `models.json`에 덮어씁니다.

- 권장 크기: 파일당 20MB 이하, 삼각형 50만 개 이하 (GitHub 상한은 100MB)
- 다운로드한 모델은 라이선스상 재배포가 허용되는지 확인한 뒤 올리세요.
- 회사 내부 도면은 공개 저장소에 올리지 마세요.
