MaDaF 0.41.1

MaDaF는 Windows 바탕화면에 Markdown 메모를 배치하는 포터블 프로그램입니다.
이 프로그램은 AI 코딩 도구를 활용해 개발했습니다.

실행 방법
1. Windows 10·11 x64용 Portable 폴더 전체를 복사하거나 압축을 풉니다.
2. Portable\MaDaF.exe를 실행합니다.
- .NET·WPF 런타임이 포함되어 있습니다. Portable 안의 DLL과 하위 폴더를 함께 유지하십시오.

업데이트
- v0.41.0부터 설정 → 업데이트에서 확인하고 설치할 수 있습니다.
- v0.40.2에서 처음 업그레이드할 때는 설정 → 일반 → 업데이트 확인을 사용합니다.
- 설치하면 프로그램 파일만 교체됩니다. 실행 중인 메모가 정상적으로 저장된 뒤 업데이트를 진행합니다.

사용자 데이터
- 메모와 설정은 Portable\Data, 로그는 Portable\Logs에 저장됩니다.
- 백업하거나 다른 PC로 옮길 때 앱을 정상 종료하고 Portable\Data 전체를 복사하십시오. Data\memo-files.json에는 메모 파일명 연결과 저장 형식 정보가 들어 있습니다.
- 수동으로 업데이트할 때도 Data와 Logs를 삭제하거나 덮어쓰지 마십시오.

버전별 변경 이력
- CHANGELOG.md
- https://github.com/sks05194/MaDaF/blob/main/CHANGELOG.md

이 저장소에는 사용자별 Data, Logs와 개발용 디버그 심볼이 포함되지 않습니다.
