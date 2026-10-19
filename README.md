# StockPin

> Windows용 바탕화면 위에 항상 떠 있는 관심종목 시세 위젯

[ReWorld](https://reworld.kr) 데스크톱 앱의 **release 배포 채널**입니다. 소스 코드는 별도 모노레포(`reworld-kr/ReWorld`)에서 관리되고, 이 repo는 빌드 산출물(`StockPin.exe`, NSIS installer, checksums)만 호스팅합니다.

## 다운로드

[**최신 버전 다운로드 ↓**](https://github.com/reworld-kr/StockPin/releases/latest/download/StockPin_Setup.exe) · [릴리즈 노트 / 포터블](https://github.com/reworld-kr/StockPin/releases/latest)

- `StockPin.exe` — bare 실행 파일 (압축/설치 없이 즉시 실행)
- `StockPin_Setup.exe` — NSIS 설치 마법사 (사용자 디렉터리에 설치, UAC 불필요)
- `checksums.txt` — SHA-256 무결성 검증

설치 후 자동 업데이트가 켜져 있어 새 버전 출시 시 다음 실행에 백그라운드 적용됩니다.

## 주요 기능

- 국내 · 미국 주식 실시간 시세 — 국내는 네이버 실시간, 해외는 야후
- 종목명 · 코드 · 초성 검색으로 추가 — 티커를 외울 필요 없음
- 평단가와 수량을 넣으면 평가손익 · 평가금액이 함께 표시
- 당일 시가 · 고가 · 저가 · 상하한가를 작은 봉으로 한눈에
- 배경 농도 · 밝기 · 등락 색상 조절, 항상 위 고정, 단축키(Ctrl+Alt+W)로 표시/숨김
- 트레이에 상주, Windows 시작 시 자동 실행

## 시스템 요구사항

- Windows 10 / 11 (x64)
- 사용자 디렉터리 설치 → 관리자 권한 / UAC 불필요
- 자동 업데이트 — GitHub Release 채널 모니터링

## 라이선스

- **무료 앱**입니다. ReWorld 계정으로 로그인만 하면 바로 사용할 수 있습니다.
- 계정 관리: [reworld.kr/account](https://reworld.kr/account)

데스크톱 + 모바일 + homepage 모두 **동일 ReWorld 계정**을 공유합니다.

## 문의 / 버그 리포트

- 일반 문의: [reworld.kr/contact](https://reworld.kr/contact)
- 버그 / 기능 요청: [Issues](https://github.com/reworld-kr/StockPin/issues)

## 관련 링크

- [StockPin 제품 페이지](https://reworld.kr/apps/stockpin)
- [ReWorld 앱 그리드](https://reworld.kr/apps)
- [이용약관](https://reworld.kr/legal/terms) / [개인정보처리방침](https://reworld.kr/legal/privacy)
