# 개발자를 위한 파이썬

![개발자를 위한 파이썬 표지](cover.jpg)

이 책은 기존 개발자, 특히 다른 프로그래밍 언어를 배운 신입 1~3년 차 개발자를 주 대상으로 삼았다. 이들의 수준에 맞춰 파이썬의 핵심 문법을 속도감 있게 알려주고 실무에서 접할 확률이 높은 예제를 선택해서 실었다. 기존의 입문서는 지루하고, 두꺼운 책을 읽기에는 부담스럽다면 이 책으로 빠르게 파이썬을 배워보자.

# 요구사항

* [Python 3](https://www.python.org/downloads/)
  * [scrapy](https://scrapy.org/)
  * [flask](http://flask.pocoo.org/)
  * [slackbot](https://github.com/lins05/slackbot)
  * [rabbitmq](https://www.rabbitmq.com/)
  * [pika](https://pypi.python.org/pypi/pika)
  * [celery](http://www.celeryproject.org/)
  * [sqlalchemy](https://www.sqlalchemy.org/)
  * [pandas](http://pandas.pydata.org/)
  * [xlrd](https://pypi.python.org/pypi/xlrd)
  * [openpyxl](https://bitbucket.org/openpyxl/openpyxl/src)
  * [matplotlib](https://matplotlib.org/)
  * [네이버 개발자 센터](https://developers.naver.com/main/)
  * [Kakao Developers](https://developers.kakao.com/)
  * [The Movie Database API](https://developers.themoviedb.org/4/getting-started)

# 구매하기

[Yes24](http://goo.gl/NuzyEj) | [교보문고](https://goo.gl/DgFHDf) | [알라딘](https://goo.gl/tKawcG) | [인터파크](https://goo.gl/iUokXU) | [반디앤루니스](https://goo.gl/zankH4)

# 윈도우 환경에서의 트러블 슈팅 해결법

간혹 윈도우 환경에서 Jupyter Notebook이나 Scrapy 등 어떤 주요 패키지의 하위 패키지를 설치하던 중 'Running setup.py install for <패키지이름> ... error', 'UnicodeDecodeError: 'utf-8' codec can't decode byte 0x00 in position'이라는 에러 메시지와 함께 하위 패키지가 정상적으로 설치되지 않는 상황이 있습니다. 이런 경우에는 [Unofficial Windows Binaries for Python Extension Packages](https://www.lfd.uci.edu/~gohlke/pythonlibs/)에서 문제가 발생한 패키지 이름을 검색해서 최신 패키지를 프로젝트 디렉터리에 다운로드한 후 `pip install <패키지파일이름.확장자이름>`으로 직접 설치한 후 전체 패키지 설치를 다시 실행하면 문제가 해결될 때가 많습니다. 참고하기 바랍니다.

