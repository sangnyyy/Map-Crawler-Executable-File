# Map-Crawler-Executable-File

## 실행파일을 저의 구글 드라이브에 업로드 하였습니다. 사용법은 아래를 참조하세요!
=> [링크](https://drive.google.com/open?id=1qM0IbWMzsQqGiIXNNW5Donblyj3jNH_s)

## Usage

```
1. SML-crawler 디렉토리를 다운로드 받으세요.

2. main.exe파일을 실행시키세요.

3. 상호명을 검색하시고, 디렉토리 내의 생성되는 csv파일을 확인하세요!
```

## Notice
* Mac/Linux 유저는 사용이 불가능합니다.

* 다음지도를 기반으로 크롤링을 진행합니다.

* (다음지도에 등록된) 정확한 상호명을 입력해야 합니다.

* Map-Crawler 레포지터리와는 다르게 레포지터리 안에 chrome driver(버전 2.38)이 포함되있습니다.

* 현재 서울특별시 종로구, 중구에 대하여 검색만을 진행합니다. 범위를 조정하고 싶은 경우,
cities.py의 코드를 수정해주세요.

* 새로 데이터를 검색하는 경우, 기존의 CSV파일에 덧붙혀집니다.

## Development Tools

* Pycharm

* Anaconda3

* Python(version = 3.6)

* Chrome driver

* Excel

## Made By

* PyInstaller ([https://www.pyinstaller.org](https://www.pyinstaller.org/))

```
$ pyinstaller --icon="icon.ico" main.py -F
```
