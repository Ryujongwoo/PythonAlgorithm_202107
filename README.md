# PythonAlgorithm_202107
2021년 7월 파이썬 Algorithm 수업 내용입니다.

## jupyter notebook 설치  
pip install jupyter notebook

## 자동 완성을 방해하는 라이브러리 제거
pip uninstall jedi

## jupyter notebook 화면 설정 방법  
C:\사용자\\<사용자ID>\\.jupyter 폴더에 쥬피터 노트북 설정이 있다.  
그 아래에 custom 이라는 이름의 폴더를 만들고, 그 아래에 custom.css 라는 파일을 복사해 넣는다.

.jupyter 폴더가 보이지 않으면 까만 화면에서 jupyter notebook --generate-config를 실행한다.

## 파이썬 소스코드 실행 사이트 
http://www.pythontutor.com/

# 크롤링시 406 에러가 발생될 경우
헤더 정보 사이트 => https://developers.whatismybrowser.com/useragents/explore/layout_engine_name/trident/  
header = {"User-agent": "Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko"}
