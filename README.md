# Wii 파티 U 한글 패치

일본판 Wii Party U(ANXJ01, 타이틀 ID `000500001011A800`)를 위한 비공식 팬 한글 패치입니다.

**최신 버전: 1.3.4** · [릴리스 다운로드](https://github.com/auseong325-design/wii-party-u-korean-patch/releases/latest)

| | |
|---|---|
| ![메인 메뉴](screenshots/game/02_main_menu.png) | ![다 함께 배틀](screenshots/game/11_all_battle_list.png) |
| ![추천](screenshots/game/13_recommend_players.png) | ![게임 설명](screenshots/game/12_twist_finger_detail.png) |

## 한글화 범위

- 게임 안의 문장 약 5,000개와 그림 속 일본어 글자(메뉴 제목, 버튼, 텔롭, 메뉴 미리보기 등)를 한국어로 바꿨습니다.
- 그대로 둔 것: 음성(일본어), 규칙 설명·게임 장면 스크린샷 그림 52종, 일본판의 영어 표기.
- 한국어 음성은 따로 배포하는 Cemu용 음성 팩으로 적용합니다.

## 다운로드

| 파일 | 내용 |
|---|---|
| `WiiPartyU_Korean_v1.3.4_WiiU.zip` | Wii U 본체용. 설치 앱, SDCafiine용 파일, PC FTP 설치 도구, 소스, 라이선스 |
| `WiiPartyU_Korean_v1.3.4_Cemu.zip` | Cemu 그래픽 팩 |

압축을 푼 뒤 안에 있는 `설치 안내.txt`를 따라 주세요. 게임 원본은 들어 있지 않습니다.

## Wii U 설치 방법

필요한 것: [Aroma](https://wiiu.hacks.guide/)가 설치된 Wii U, SD 카드(1.5GB 이상 여유).

| 방법 | 설명 |
|---|---|
| 1. 전용 설치 앱 | SD 카드에 `wiiu` 폴더를 복사하고 Wii U 메뉴의 「Wii Party U KR Patch」를 실행합니다. 원래 파일을 SD 카드에 백업한 뒤 본체의 게임 파일을 바꿉니다. 한 번 설치하면 SD 카드 없이도 한글로 나오고, 같은 앱에서 원래대로 되돌릴 수 있습니다. |
| 2. SDCafiine | 본체 파일을 바꾸지 않고 SD 카드의 한글 파일을 읽게 합니다. 디스크판은 이 방법만 쓸 수 있습니다. |
| 3. PC FTP 설치 도구 | Windows PC에서 FTPiiU 플러그인을 통해 설치합니다. 원래 파일은 PC에 백업합니다. |

### 이전 버전에서 업데이트

되돌리지 않고 그대로 업데이트할 수 있습니다. 새 패키지의 `wiiu` 폴더 **전체**를 SD 카드에 덮어쓴 뒤 설치 앱에서 「설치하기」를 고르면 바뀐 파일만 새 판으로 바꿉니다. 원래 파일 백업(`wiiu/kopatch/WiiPartyU/backup`)은 그대로 씁니다. 패치 파일만 바꾸고 설치 정보(`wiiu/kopatch`)를 예전 것으로 두면 설치 앱이 「SD 카드 데이터」를 빨간색으로 표시하고 멈춥니다.

### Tiramisu·구형 CFW

- 설치 앱(`.wuhb`), SDCafiine 플러그인, PC FTP 도구(FTPiiU 플러그인 전제)는 모두 **Aroma 전용**입니다. Tiramisu는 개발이 끝났고 Aroma로 넘어가는 것을 권장합니다.
- 이 패치는 게임 파일을 바꾸는 방식이라 설치가 끝난 뒤 게임을 실행할 때는 별도 구성 요소가 필요 없습니다. Aroma로 한 번 설치해 두면 됩니다.
- Tiramisu나 구형 CFW에서 FTP 프로그램으로 직접 파일을 옮기는 방법은 시험하지 않아 안내하지 않습니다.

## Cemu

`WiiPartyU_Korean` 폴더를 Cemu의 `graphicPacks`에 넣고 「Wii Party U > Mods > Korean Patch」를 켭니다. Cemu는 Wii U 메뉴 시작 화면을 보여 주지 않으므로 시작 화면 글자 패치는 Wii U용에만 있습니다.

## 스크린샷

<details>
<summary>게임 화면 16장 (Cemu)</summary>

| | |
|---|---|
| ![](screenshots/game/01_title.png) | ![](screenshots/game/02_main_menu.png) |
| ![](screenshots/game/03_tv_party.png) | ![](screenshots/game/04_living_party.png) |
| ![](screenshots/game/05_table_party.png) | ![](screenshots/game/06_mega_board_detail.png) |
| ![](screenshots/game/07_players.png) | ![](screenshots/game/08_minigame_menu.png) |
| ![](screenshots/game/09_free_play_detail.png) | ![](screenshots/game/10_rule_select.png) |
| ![](screenshots/game/11_all_battle_list.png) | ![](screenshots/game/12_twist_finger_detail.png) |
| ![](screenshots/game/13_recommend_players.png) | ![](screenshots/game/14_recommend_card.png) |
| ![](screenshots/game/15_data.png) | ![](screenshots/game/16_records.png) |

</details>

<details>
<summary>설치 앱 8장 (Cemu 모의 실행이라 「테스트 모드」 표시가 있습니다)</summary>

| | |
|---|---|
| ![](screenshots/installer/01_status.png) | ![](screenshots/installer/02_components.png) |
| ![](screenshots/installer/03_confirm_install.png) | ![](screenshots/installer/04_installing.png) |
| ![](screenshots/installer/05_install_done.png) | ![](screenshots/installer/06_status_installed.png) |
| ![](screenshots/installer/07_confirm_restore.png) | ![](screenshots/installer/08_restore_done.png) |

</details>

<details>
<summary>PC FTP 설치 도구</summary>

![](screenshots/ftp/01_menu.png)

</details>

## 주요 변경 (1.0.3 이후)

- **1.3.4**: 분홍 기울임 제목의 획 끝 모서리가 깎여 보이던 문제 수정.
- **1.3.3**: 일본판 제목의 입체감(글자 안쪽 밝은 테두리)을 재서 반영. 프리 플레이 제목 색, 모드 이름(TV 파티 등) 테두리를 일본판 구조로 수정.
- **1.3.2**: 화면 왼쪽 위 분홍 제목 50종을 하나의 스타일로 다시 그림. 「추천」 끝이 잘리던 문제 수정.
- **1.3.1**: 일본판에서 기울어진 그림 글자 20종의 기울임 반영.
- **1.3.0 / 1.2.0**: 그림 다시 그리기(화살표, 칸 이름, 텔롭 등), 투명 배경 복구, 문장 수정, Mii 포커 족보 이름 통일.
- **설치 앱 1.2.0**: 이전 판 위에 그대로 업데이트할 때 「이전 판 X 설치됨」「X에서 Y로 업데이트」로 표시.

## 구성과 출처

설치 앱, FTP 도구의 소스와 포함된 구성 요소의 라이선스 고지는 Wii U용 ZIP의 `source`, `licenses` 폴더에 있습니다. 비공식 팬 번역이며 Nintendo와 관계없습니다. 게임 원본과 업데이트는 직접 준비해야 합니다.
