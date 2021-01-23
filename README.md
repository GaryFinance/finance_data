# 환경세팅 

### 	1. DATA 수집 및 분석을 위한 수업전 환경을 설정하고 필요한 프로그램을 설치

#### 			python 설치 

​					윈도우에서 파이썬 설치하기

**1)** 우선 파이썬 공식 홈페이지의 다운로드 페이지([http://www.python.org/downloads](http://www.python.org/downloads/))에서 윈도우용 파이썬 언어 패키지를 다운로드한다. 다음 화면에서 Python 3.x로 시작하는 버전 중 가장 최근의 윈도우 인스톨러를 다운로드하자(이 글을 작성하는 시점의 최신 버전은 3.7.3이다).

![image-20210123190506670](https://user-images.githubusercontent.com/25717861/105575292-efde9800-5dad-11eb-9b23-faccd20e6798.png)



![image-20210123190845399](https://user-images.githubusercontent.com/25717861/105575370-80b57380-5dae-11eb-893c-d2e5e1887466.png)

**2)인스톨러를 실행한 후에 "Install Now"를 선택하면 바로 설치가 진행된다.**

파이썬이 어느 곳에서든지 실행될 수 있도록 "Add Python3.8 to PATH" 옵션을 반드시 선택해야 한다.

![image-20210123191346607](https://user-images.githubusercontent.com/25717861/105575461-249f1f00-5daf-11eb-862d-584a84bea93e.png)

> ※ "Add Python 3.7 to PATH" 옵션을 누락하면 이후 실습할 때 오류가 발생할 수 있다. 만약 Python이 설치되는 경로와 PATH에 대한 사전 지식이 있는 사용자라면 이 옵션을 생략해도 된다.

##### 3)설치가 완료되면 [close]를 클릭하여 종료한다.

파이썬이 정상적으로 설치되었다면 다음 그림과 같이 프로그램 메뉴에서 확인할 수 있다.

**[시작 → 모든 프로그램 → Python 3.8]**



​				

####  		 jupyter notebook 설치

​			windows 10  기준으로 cmd 창을 열고 다음과 같은 명령어를 이용해서 설치

```cmd
pip install jupyter
```





####  		 jupyter notebook 실행

```cmd
C:\Users\user>cd 

C:\>cd apps

C:\apps>mkdir finace_data

C:\apps>cd finace_data

C:\apps\finace_data>jupyter notebook

```



![image-20210123192250643](https://user-images.githubusercontent.com/25717861/105575640-7a27fb80-5db0-11eb-9004-62d97901cb92.png)