# 쿠키 러너 스프라이트 입력

캐릭터의 기준 이미지가 준비되면 `cookie.png`로 이 폴더에 넣고,
저장소 루트에서 `tools/sprite-gen/PROJECT_SETUP.md`의 `prepare` 명령을
실행합니다. 생성 결과는 `assets/sprite-runs/cookie/`에 저장됩니다.

현재 게임은 Canvas 도형으로 캐릭터를 그리고 있습니다. 스프라이트 생성 후
아틀라스와 `manifest.json`을 확인한 다음 게임 렌더러에 연결합니다.
