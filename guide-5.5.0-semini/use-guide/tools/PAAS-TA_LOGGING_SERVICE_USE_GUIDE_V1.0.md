
# Table Of Contents

1. [문서 개요](#1)
	- [1.1. 목적](#1-1)
	- [1.2. 범위](#1-2)
2. [Logging 서비스 접속](#2)
	- [2.1. PaaS-TA 사용자 포탈 접속](#2-1)
	- [2.2. Logging 서비스 접속](#2-2)
3. [Logging 서비스 사용자 매뉴얼](#3)
	- [3.1. Logging 서비스 사용자 메뉴 구성](#3-1)
	- [3.2. Logging 서비스 사용자 메뉴 설명](#3-2)
	- [3.2.1. Discover](#3-2-1)
	- [3.2.1.1. 신규 검색](#3-2-1-1)
	- [3.2.1.2. 검색 저장](#3-2-1-2)
	- [3.2.1.3. 검색 열기](#3-2-1-3)
	- [3.2.1.4. 검색 공유](#3-2-1-4)
	- [3.2.1.5. 검색 조건 설정](#3-2-1-5)
	- [3.2.2. Visualize](#3-2-2)
	- [3.2.2.1. visualization 생성](#3-2-2-1)
	- [3.2.2.2. visualization 수정](#3-2-2-2)
	- [3.2.2.3. visualization 공유](#3-2-2-3)
	- [3.2.2.4. visualization 새로 고침](#3-2-2-4)
	- [3.2.2.5. visualization Time Range 설정](#3-2-2-5)
	- [3.2.2.6. visualization 삭제](#3-2-2-6)
	- [3.2.3. Dashboard](#3-2-3)
	- [3.2.3.1. Dashboard 생성](#3-2-3-1)
	- [3.2.3.2. Dashboard 수정](#3-2-3-2)
	- [3.2.3.3. Dashboard 공유](#3-2-3-3)
	- [3.2.3.4. Dashboard 옵션 및 Time Range](#3-2-3-4)
	- [3.2.3.5. Dashboard 삭제](#3-2-3-5)
	- [3.2.4. Management](#3-2-4)
	- [3.2.4.1. Saved Objects 조회](#3-2-4-1)
	- [3.2.4.2. Saved Objects 수정](#3-2-4-2)
	- [3.2.4.3. Saved Objects Export](#3-2-4-3)
	- [3.2.4.4. Saved Objects Import](#3-2-4-4)
	- [3.2.4.5. Saved Objects 삭제](#3-2-4-5)

---

# <div id='1'/> 1. 문서 개요
## <div id='1-1'/> 1.1 목적
본 문서는 Logging 서비스의 사용 방법에 대해 기술하였다.

## <div id='1-2'/> 1.2 범위
본 문서는 Windows 환경을 기준으로 Logging 서비스를 사용하는 방법에 대해 작성되었다.

# <div id='2'/> 2. Logging 서비스 접속

## <div id='2-1'/> 2.1 PaaS-TA 사용자 포탈 접속
- PaaS-TA 사용자 포탈에 접속하여 “로그인” 버튼을 클릭한다.

![001](../images/logging-service/image001.png)

- 사용자 계정과 비밀번호를 입력한 후 “SIGN IN” 버튼을 클릭하여 PaaS-TA 사용자 포탈에 로그인 한다.
![002](../images/logging-service/image002.png)

- 로그인 한 후 "애플리케이션명"을 클릭하여 애플리케이션 상세 페이지로 이동한다.
![003](../images/logging-service/image003.png)

## <div id='2-2'/> 2.2 Logging 서비스 접속

- PaaS-TA 포탈의 애플리케이션 상세 페이지로 이동하여 "로그" 메뉴를 선택한다.
![004](../images/logging-service/image004.png)

- 애플리케이션 로그 페이지의 "Log Service"를 클릭한다.
![005](../images/logging-service/image005.png)

- PaaS-TA Logging 서비스 접속을 확인한다.
![006](../images/logging-service/image006.png)

# <div id='3'/> 3. Logging 서비스 사용자 매뉴얼
본 장에서는 Logging 서비스의 메뉴 구성 및 화면 설명에 대해서 기술하였다.

## <div id='3-1'/> 3.1 Logging 서비스 사용자 메뉴 구성

Logging 서비스는 다음과 같은 메뉴로 구성되어 있다.

메뉴 | 설명
:--- | :---
Discover | 로그 데이터의 검색 및 필터링
Visulize | 로그 데이터의 시각화 구성 및 관리
Dashboard | 사용자가 배치하고 공유할 수 있는 시각화의 모음
Management | 저장된 객체 관리

## <div id='3-2'/> 3.2 Logging 서비스 사용자 메뉴 설명
본 장에서는 Logging 서비스의 4개 메뉴에 대한 설명을 기술한다.

### <div id='3-2-1'/> 3.2.1. Discover
본 장에서는 로그 데이터의 검색 및 필터링, 검색의 저장 및 공유에 대해 기술한다.

좌측의 "Discover" 메뉴를 클릭한다.
![007](../images/logging-service/image007.png)

#### <div id='3-2-1-1'/> 3.2.1.1. 신규 검색
"Discover"메뉴에서 상단의 "New"를 클릭한다.
![008](../images/logging-service/image008.png)

#### <div id='3-2-1-2'/> 3.2.1.2. 검색 저장
"Discover" 메뉴에서 상단의 "Save"를 클릭한다.
![009](../images/logging-service/image009.png)

검색 명을 입력한 후, "Save" 버튼을 클릭한다.
![010](../images/logging-service/image010.png)

#### <div id='3-2-1-3'/> 3.2.1.3. 검색 열기
"Discover" 메뉴에서 상단의 "Open"을 클릭한다.
![011](../images/logging-service/image011.png)

검색 목록에서 "검색 객체 명"을 클릭한다.
![012](../images/logging-service/image012.png)

#### <div id='3-2-1-4'/> 3.2.1.4. 검색 공유
"Discover" 메뉴에서 상단의 "Share"를 클릭한다.
![013](../images/logging-service/image013.png)

#### <div id='3-2-1-5'/> 3.2.1.5. 검색 조건 설정
- Time Range 설정
"Discover" 메뉴에서 상단의 ① 영역을 클릭하여, Time Range에서 원하는 조건을 선택한다.
![014](../images/logging-service/image014.png)

- query 설정
"Discover" 메뉴의 검색 query 영역(①)에 원하는 조건을 설정하고 데이터를 조회한다.
![015](../images/logging-service/image015.png)

- Fields 설정
"Discover" 메뉴의 ① 의 영역에서 Available Fields 목록의 Field를 선택(②)하여 조회 화면(③)에 표시되는 Field를 설정한다.
![016](../images/logging-service/image016.png)
![017](../images/logging-service/image017.png)

- Fields 설정 해제
"Discover" 메뉴의 ① 의 영역에서 Selected Fields 목록의 Field를 선택(②)하여 조회 설정을 해제 한다.
![018](../images/logging-service/image018.png)

### <div id='3-2-2'/> 3.2.2. Visualize
본 장에서는 로그 데이터의 시각화 구성 및 관리에 대해 기술한다.

#### <div id='3-2-2-1'/> 3.2.2.1. visualization 생성
좌측의 "Visualize" 메뉴를 클릭한다.
![019](../images/logging-service/image019.png)

"Visualize" 메뉴에서 "+" 또는 "+ Create a visualization" 버튼을 클릭한다.
![020](../images/logging-service/image020.png)

Select visualization type 목록에서 type을 클릭한다.
![021](../images/logging-service/image021.png)

색인 패턴을 클릭(①)하거나 저장된 검색 목록에서 "검색 명"을 클릭(②)한다.
![022](../images/logging-service/image022.png)

데이터 및 옵션(①)을 편집 하여 시각화를 구성한다.
![023](../images/logging-service/image023.png)

상단의 "Save"를 클릭한다.
![024](../images/logging-service/image024.png)

시각화 명을 입력한 후, "Save" 버튼을 클릭한다.
![025](../images/logging-service/image025.png)

#### <div id='3-2-2-2'/> 3.2.2.2. visualization 수정
좌측의 "Visualize" 메뉴를 클릭한다.
![026](../images/logging-service/image026.png)

시각화 목록에서 "시각화 객체 명"을 클릭한다.
![027](../images/logging-service/image027.png)

데이터 및 옵션(①)을 수정 후, "Save"를 클릭한다.
![028](../images/logging-service/image028.png)
![029](../images/logging-service/image029.png)

#### <div id='3-2-2-3'/> 3.2.2.3. visualization 공유
좌측의 "Visualize" 메뉴를 클릭한다.
![026](../images/logging-service/image026.png)

시각화 목록에서 "시각화 객체 명"을 클릭한다.
![027](../images/logging-service/image027.png)

상단의 "Share"를 클릭한다.
![030](../images/logging-service/image030.png)

#### <div id='3-2-2-4'/> 3.2.2.4. visualization 새로 고침
좌측의 "Visualize" 메뉴를 클릭한다.
![026](../images/logging-service/image026.png)

시각화 목록에서 "시각화 객체 명"을 클릭한다.
![027](../images/logging-service/image027.png)

상단의 "Refresh"를 클릭한다.
![031](../images/logging-service/image031.png)

#### <div id='3-2-2-5'/> 3.2.2.5. visualization Time Range 설정
좌측의 "Visualize" 메뉴를 클릭한다.
![026](../images/logging-service/image026.png)

시각화 목록에서 "시각화 객체 명"을 클릭한다.
![027](../images/logging-service/image027.png)

상단의 ① 영역을 클릭하여, Time Range에서 원하는 조건을 선택한다.
![032](../images/logging-service/image032.png)

#### <div id='3-2-2-6'/> 3.2.2.6. visualization 삭제
좌측의 "Visualize" 메뉴를 클릭한다.
![026](../images/logging-service/image026.png)

시각화 목록에서 시각화 객체를 선택(①)한 후, ② 아이콘을 클릭한다.
![033](../images/logging-service/image033.png)

### <div id='3-2-3'/> 3.2.3. Dashboard
본 장에서는 저장된 검색 객체와 저장된 시각화 객체를 이용한 대시보드의 구성 및 관리에 대해 기술한다.

#### <div id='3-2-3-1'/> 3.2.3.1. Dashboard 생성
좌측의 "Dashboard" 메뉴를 클릭한다.
![034](../images/logging-service/image034.png)

"+" 또는 "+ Create a dashboard" 버튼을 클릭한다.
![035](../images/logging-service/image035.png)

상단의 "Add"(①) 또는 "Add" 버튼(②)을 클릭한다.
![036](../images/logging-service/image036.png)

Add Panels의 "Visualization" / "Saved Search" 을 클릭하여 저장된 객체 목록을 조회한다.
![037](../images/logging-service/image037.png)

조회된 저장된 객체 목록에서 "객체 명"을 클릭(①)하여 대시보드를 구성한다.
![038](../images/logging-service/image038.png)

상단의 "Save"를 클릭한다.
![039](../images/logging-service/image039.png)

대시보드 명을 입력한 후, "Save" 버튼을 클릭한다.
![040](../images/logging-service/image040.png)

#### <div id='3-2-3-2'/> 3.2.3.2. Dashboard 수정
좌측의 "Dashboard" 메뉴를 클릭한다.
![041](../images/logging-service/image041.png)

대시보드 목록에서 "대시보드 명"을 클릭한다.
![042](../images/logging-service/image042.png)

대시보드를 수정 한 후 상단의 "Save"를 클릭한다.
![043](../images/logging-service/image043.png)

#### <div id='3-2-3-3'/> 3.2.3.3. Dashboard 공유
좌측의 "Dashboard" 메뉴를 클릭한다.
![041](../images/logging-service/image041.png)

대시보드 목록에서 "대시보드 명"을 클릭한다.
![042](../images/logging-service/image042.png)

상단의 "Share"를 클릭한다.
![044](../images/logging-service/image044.png)

#### <div id='3-2-3-4'/> 3.2.3.4. Dashboard 옵션 및 Time Range
좌측의 "Dashboard" 메뉴를 클릭한다.
![041](../images/logging-service/image041.png)

대시보드 목록에서 "대시보드 명"을 클릭한다.
![042](../images/logging-service/image042.png)

- 옵션 설정
상단의 "Options"를 클릭하고, "Use dark theme"를 선택(①)하여 테마 적용을 변경한다.
![045](../images/logging-service/image045.png)
![046](../images/logging-service/image046.png)

- Time Range 설정
상단의 ① 영역을 클릭하여, Time Range 영역에서 원하는 조건을 선택한다.
![047](../images/logging-service/image047.png)

#### <div id='3-2-3-5'/> 3.2.3.5. Dashboard 삭제
좌측의 "Dashboard" 메뉴를 클릭한다.
![041](../images/logging-service/image041.png)

대시보드 목록에서 대시보드 객체를 선택(①)한 후, ② 아이콘을 클릭한다.
![048](../images/logging-service/image048.png)

### <div id='3-2-4'/> 3.2.4. Management
본 장에서는 저장된 객체 관리에 대해 기술한다.

좌측의 "Management" 메뉴를 클릭하고, "Saved Objects"를 클릭한다.
![049](../images/logging-service/image049.png)
#### <div id='3-2-4-1'/> 3.2.4.1. Saved Objects 조회
"Dashboards" / "Searches" / "Visualization" 을 클릭하여 각 객체 목록을 조회한다.
![050](../images/logging-service/image050.png)

#### <div id='3-2-4-2'/> 3.2.4.2. Saved Objects 수정
"Dashboards" / "Searches" / "Visualization" 의 객체 목록에서 "객체 명"(①)을 클릭한다.
![051](../images/logging-service/image051.png)

객체 상세 페이지에서 내용을 수정한 후, 하단의 "Save dashboard Object" 버튼을 클릭한다.
![052](../images/logging-service/image052.png)

#### <div id='3-2-4-3'/> 3.2.4.3. Saved Objects Export
- 선택 Export
"Dashboards" / "Searches" / "Visualization" 의 객체 목록에서 객체를 선택(①)한 후, "Export" 버튼을 클릭한다.
![053](../images/logging-service/image053.png)

- 전체 Export
"Export Everything" 버튼을 클릭한다.
![054](../images/logging-service/image054.png)

#### <div id='3-2-4-4'/> 3.2.4.4. Saved Objects Import
"Import" 버튼을 클릭한다.
![055](../images/logging-service/image055.png)

디렉토리에서 객체 파일을 선택한 후, "열기" 버튼을 클릭한다.
![056](../images/logging-service/image056.png)

#### <div id='3-2-4-5'/> 3.2.4.5. Saved Objects 삭제
- 객체 목록에서 삭제
"Dashboards" / "Searches" / "Visualization" 의 객체 목록에서 객체를 선택(①)한 후, ② 아이콘을 클릭한다.
![057](../images/logging-service/image057.png)

- 객체 상세 페이지에서 삭제
"Dashboards" / "Searches" / "Visualization" 의 객체 목록에서 "객체 명"(①)을 클릭한다.
![058](../images/logging-service/image058.png)

객체 상세 페이지에서 상단의 "Delete dashboard/search/visualization" 버튼(①)을 클릭한다.
![059](../images/logging-service/image059.png)



[001]:/use-guide/images/logging-service/image001.png
[002]:/use-guide/images/logging-service/image002.png
[003]:/use-guide/images/logging-service/image003.png
[004]:/use-guide/images/logging-service/image004.png
[005]:/use-guide/images/logging-service/image005.png
[006]:/use-guide/images/logging-service/image006.png
[007]:/use-guide/images/logging-service/image007.png
[008]:/use-guide/images/logging-service/image008.png
[009]:/use-guide/images/logging-service/image009.png
[010]:/use-guide/images/logging-service/image010.png
[011]:/use-guide/images/logging-service/image011.png
[012]:/use-guide/images/logging-service/image012.png
[013]:/use-guide/images/logging-service/image013.png
[014]:/use-guide/images/logging-service/image014.png
[015]:/use-guide/images/logging-service/image015.png
[016]:/use-guide/images/logging-service/image016.png
[017]:/use-guide/images/logging-service/image017.png
[018]:/use-guide/images/logging-service/image018.png
[019]:/use-guide/images/logging-service/image019.png
[020]:/use-guide/images/logging-service/image020.png
[021]:/use-guide/images/logging-service/image021.png
[022]:/use-guide/images/logging-service/image022.png
[023]:/use-guide/images/logging-service/image023.png
[024]:/use-guide/images/logging-service/image024.png
[025]:/use-guide/images/logging-service/image025.png
[026]:/use-guide/images/logging-service/image026.png
[027]:/use-guide/images/logging-service/image027.png
[028]:/use-guide/images/logging-service/image028.png
[029]:/use-guide/images/logging-service/image029.png
[030]:/use-guide/images/logging-service/image030.png
[031]:/use-guide/images/logging-service/image031.png
[032]:/use-guide/images/logging-service/image032.png
[033]:/use-guide/images/logging-service/image033.png
[034]:/use-guide/images/logging-service/image034.png
[035]:/use-guide/images/logging-service/image035.png
[036]:/use-guide/images/logging-service/image036.png
[037]:/use-guide/images/logging-service/image037.png
[038]:/use-guide/images/logging-service/image038.png
[039]:/use-guide/images/logging-service/image039.png
[040]:/use-guide/images/logging-service/image040.png
[041]:/use-guide/images/logging-service/image041.png
[042]:/use-guide/images/logging-service/image042.png
[043]:/use-guide/images/logging-service/image043.png
[044]:/use-guide/images/logging-service/image044.png
[045]:/use-guide/images/logging-service/image045.png
[046]:/use-guide/images/logging-service/image046.png
[047]:/use-guide/images/logging-service/image047.png
[048]:/use-guide/images/logging-service/image048.png
[049]:/use-guide/images/logging-service/image049.png
[050]:/use-guide/images/logging-service/image050.png
[051]:/use-guide/images/logging-service/image051.png
[052]:/use-guide/images/logging-service/image052.png
[053]:/use-guide/images/logging-service/image053.png
[054]:/use-guide/images/logging-service/image054.png
[055]:/use-guide/images/logging-service/image055.png
[056]:/use-guide/images/logging-service/image056.png
[057]:/use-guide/images/logging-service/image057.png
[058]:/use-guide/images/logging-service/image058.png
[059]:/use-guide/images/logging-service/image059.png
