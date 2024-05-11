# project

### 스도쿠 게임을 하는 프로그램입니다.
<img src="images/sudokuExample.png">

#### 스도쿠는 가로 9칸, 세로 9칸으로 이루어진 9x9 보드에서 빈 칸을 정해진 규칙에 맞도록 채우는 게임입니다.



## * 기능
### 1. 난이도 선택
#### Easy, Medium, Hard 중 선택할 수 있습니다.
### 2. 스도쿠 플레이
#### 스도쿠 문제가 주어지고 4가지 보기 중 선택하여 게임을 진행합니다.
#### - 숫자 입력(빈 칸의 숫자를 맞춥니다.)
#### - 힌트(빈 칸의 숫자가 무엇인지 알 수 있습니다.)
#### - 정답 공개(스도쿠의 정답을 공개합니다.)
#### - 게임 종료(프로그램을 종료합니다.)
### 3. 순위
#### play time에 걸린 시간을 기준으로 순위를 보여줍니다.
   


## * 코드
#### 코드는 모듈, 함수, 데이터, 메인(프로그램)으로 크게 4가지로 나누어 작성하였습니다.
<img src="images/code.png">

### 1. Modules
#### 프로그래밍에 필요한 모듈을 import합니다.
<img src="images/modules.png">

#### - random 모듈
####   스도쿠 문제를 생성할 때 사용합니다. (makeSudoku() 함수에 사용)
<img src="images/random.png">

#### - copy 모듈
####   스도쿠 보드(List)를 복제할 때 사용합니다. (makeSudoku() 함수에 사용)
<img src="images/cpoy.png">

#### - time 모듈
####   스도쿠 풀이 순위를 내기 위해 사용합니다. (program(main)에서 사용)
<img src="images/time.png">

### 2. Functions
#### main program에 필요한 함수를 작성하였습니다.
<img src="images/functions.png">

#### dddddddd

### 3. Data
#### 스도쿠 문제들(data)입니다.
<img src="images/dataSet.png">

#### 난이도 별로 문제(List)와 정답(List)을 가지고 있습니다.
#### Easy Data
<img src="images/dataEasy.png">
<img src="images/dataEasySol.png">

#### Medium Data
<img src="images/dataMedium.png">
<img src="images/dataMediumSol.png">

#### Hard Data
<img src="images/dataHard.png">
<img src="images/dataHardSol.png">

#### data source: Guru Puzzle Game

### 4. Program(Main)
#### 프로그램의 main 부분입니다. 데이터와 만든 함수로 스도쿠 게임을 프로그래밍하였습니다.
#### (주석 참조)
<img src="images/program.png">
   


## * 실행 결과
<img src="images/program.png">

### ddddddd
