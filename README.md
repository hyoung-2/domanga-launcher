# 도망가 서버 실행 프로그램

**Windows용 1.0.0 RC2 · 공개 시험판**

처음 한 번 설치·연결한 뒤, 바탕화면 **도망가 서버** 아이콘으로 모드팩 업데이트를 받습니다. 업데이트 후 공식 Minecraft Launcher가 열리면 도망가 Fabric 프로필에서 **플레이**를 누릅니다. 게임 자동 시작·서버 자동 접속은 포함하지 않습니다.

## 다운로드

### [RC2 설치 ZIP 받기](https://github.com/hyoung-2/domanga-launcher/releases/download/launcher-v1.0.0-rc2/DomangaLauncher-RC2-Windows.zip)

[처음 설치하는 친구용 한국어 안내](https://github.com/hyoung-2/domanga-launcher/releases/download/launcher-v1.0.0-rc2/START_HERE_KO.html) · [RC2 배포 페이지](https://github.com/hyoung-2/domanga-launcher/releases/tag/launcher-v1.0.0-rc2) · [SHA-256](https://github.com/hyoung-2/domanga-launcher/releases/download/launcher-v1.0.0-rc2/SHA256SUMS.txt)

GitHub 로그인 없이 받을 수 있습니다. **Source code (zip)**이 아니라 `DomangaLauncher-RC2-Windows.zip`을 선택하세요. 안내 HTML은 다운로드 후 더블클릭해 브라우저로 읽을 수 있습니다.

## 처음 한 번

1. Java 21과 공식 Minecraft Launcher를 준비하고 본인 계정으로 로그인합니다.
2. 설치 ZIP을 새 폴더에 전체 압축 해제한 뒤 `DomangaFriend_RC2\Install.cmd`를 실행합니다. 게임·공식 런처·다른 Java 프로그램은 닫아 둡니다.
3. 바탕화면 `도망가 서버` 아이콘에서 새 게임 폴더를 설치하거나 기존 도망가 게임 폴더를 연결합니다.
4. 공식 Fabric 1.21.11 프로필의 게임 디렉터리를 도망가 게임 폴더와 맞춘 후 `연결 검사 및 저장`을 누릅니다. 제공된 최초 모드팩의 Fabric Loader 기준은 0.19.5입니다.

기본 프로그램 위치는 `%LOCALAPPDATA%\DomangaServer\Launcher`, 기본 권장 게임 위치는 `%LOCALAPPDATA%\DomangaServer\game`입니다. 두 폴더를 혼동하지 마세요. 새 게임 폴더는 미리 만들지 않습니다. 자세한 경로 선택은 한국어 안내를 따르세요.

## 다음부터

`바탕화면 아이콘 → 최신 확인·필요한 파일 적용 → 공식 런처 → 플레이`

최신 상태에서는 모드 자산을 다시 다운로드하지 않습니다. 최신 여부 조회에는 인터넷이 필요합니다. 모드팩이 갱신될 때마다 설치 ZIP을 다시 받을 필요는 없습니다.

## 저장소 역할

이 저장소는 **친구용 실행 프로그램 설치 파일**을 배포합니다. 모드팩 업데이트는 기존 [hyoung-2/domanga-client-release](https://github.com/hyoung-2/domanga-client-release)의 서명된 배포를 그대로 사용합니다. RC2 설치 파일의 업데이트 주소·공개키를 변경하지 않았습니다. 프로그램 자체의 새 버전은 별도 전체 설치 ZIP으로 안내하며, RC2가 자신의 JAR를 자동 교체하는 기능은 없습니다.

## 시험 상태와 한계

운영자는 자기 Windows PC에서 설치·바탕화면 아이콘·v3-1 최초 다운로드·공식 런처 실행·Fabric 게임 실행·서버 접속·최신 상태의 불필요한 재다운로드 없음까지 확인했다고 보고했습니다. Windows 격리 로그는 564개 중 통과 544개, 실패 0개, 미검증 20개입니다. 링크·정션 관련 환경 제한과 일부 수동 확인 항목은 통과로 바꾸지 않았습니다. 모든 친구 PC·재부팅·모든 Windows 조합의 검증을 의미하지 않습니다.

ZIP 안의 기존 안내서와 프로그램에는 제작 당시의 “Windows 실검증 대기” 문구가 남아 있습니다. 바이너리와 내부 해시를 보존하기 위해 바꾸지 않았습니다. 위 확인 상태와 `START_HERE_KO.html`을 함께 읽어 주세요.

## 설치 파일 무결성

```text
DomangaLauncher-RC2-Windows.zip
3,656,837 bytes
SHA-256: 088fc9dc5b9e9f561a7b3ec30f72541a913d2607b16fbf3050f62dc6f949b494
```

RC2 원본과 바이트가 동일합니다. ZIP 내부는 설치 목록 63개 파일과 목록 파일 2개를 합쳐 총 65개입니다. 파일별 해시는 릴리스의 `INSTALLER_FILE_LIST_SHA256.txt`에서 확인할 수 있습니다.

공식 런처의 계정 비밀번호·토큰은 운영자에게 보내지 마세요. 서명·해시 검증 오류가 발생하면 검사를 우회하거나 설치 기록을 직접 고치지 말고 오류 내용만 전달하세요.
