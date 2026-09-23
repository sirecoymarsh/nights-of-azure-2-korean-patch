# 밤이 없는 나라 2 ~신월의 신부~ 한국어 패치

최신 누적 패치는 **2026.09.24 RC4 공개 시험판**입니다. 원본 파일의 버전별 해시가 달라도 자동 백업 후 덮어쓰고, 런처에서 설치 직전 상태로 복원할 수 있습니다.

## 다운로드·설치

- [RC4 릴리스](https://github.com/sirecoymarsh/nights-of-azure-2-korean-patch/releases/tag/v2026.09.24-rc4) · [패치 ZIP](https://github.com/sirecoymarsh/nights-of-azure-2-korean-patch/releases/download/v2026.09.24-rc4/Nights_of_Azure_2_Korean_Patch_2026-09-24_RC4.zip)
- [사용법](README_KO.txt) · [SHA-256](SHA256SUMS.txt) · [검증 요약](qa-summary.json)

게임을 종료하고 ZIP 전체를 게임 폴더 밖에 압축 해제한 뒤 **밤이 없는 나라 2 한국어 패치.exe**를 실행하세요.
자동으로 찾은 게임 폴더를 확인하고 ‘패치 설치’를 누르면 기존 파일을 모두 백업·검증한 뒤 덮어씁니다.
‘패치 복원’은 가장 최근 설치 직전 상태로 되돌리며 그때 없던 패치 추가 파일은 제거합니다.
같은 상태의 재설치는 최초 백업을 보존하고, 업데이트 후 재설치는 이전 백업을 별도 보존합니다.
백업 위치는 `%LOCALAPPDATA%\Noa2KoreanPatch\backups`이며 설치 완료 창에서도 확인할 수 있습니다.

## 내용·지원 범위

일본어 원문 대조 교정, 이름 표기, 전투 잡담 물음표, 대사 개행, 동영상 자막, 튜토리얼·메뉴 이미지와 마루부리 글꼴 등 누적 파일 1,257개를 포함합니다. 비타판과 스위치판은 설치할 수 없습니다.
Windows 64비트 / .NET Framework 4.x, CHT 슬롯용입니다. 저장 데이터와 화면 설정은 패치 설치·복원 대상에서 제외됩니다.
게임 실행파일도 교체하므로 **최신 Steam판 실행 호환성을 보장하지 않습니다.** 파일 버전과 무관하게 설치할 수 있다는 것과 실행 호환성은 별개입니다.
자동 백업·설치·복원·중단 복구와 최종 ZIP 검사는 통과했으며 실제 창 조작·플레이 검수는 남아 있습니다.

## 버그 제보 및 오역 수정

[GitHub 이슈](https://github.com/sirecoymarsh/nights-of-azure-2-korean-patch/issues/new/choose)에 장·장소, 실제 문구, 기대한 동작이나 수정 의견을 알려 주세요.
런처의 ‘읽어주세요’와 ‘버그 제보 및 오역 수정’ 메뉴에서도 안내와 제보 화면을 열 수 있습니다.

RC3와 v1.0.1은 이전 배포본입니다. 저장소 루트의 v1.0.1 ZIP 대신 위 RC4 릴리스를 이용하세요.
게임 설치본은 별도로 필요합니다. 원작 이미지·브랜드의 권리는 각 권리자에게 있습니다.
글꼴 라이선스: [LICENSE_MaruBuri.txt](LICENSE_MaruBuri.txt). 번역 및 UI 문구: Codex internal.
