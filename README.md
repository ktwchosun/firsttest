### first_homework_20184412

first homework

1. getopt

* 용도: 명령형 플래그와 매개변수를 구문 분석하기 위해 사용된다.

* 설명: getopt 명령은 예상되는 플래그와 인수를 지정하는 형식을 사용하여 토큰 리스트를 구문 분석합니다. 
플래그는 단일 ASCII 문자이며 뒤에 :(콜론)이 올 경우 하나 이상의 탭 또는 공백으로 분리하거나 분리할 수 없는 인수가 있어야 합니다.
인수에는 복수 바이트를 포함시킬 수 있지만 플래그 문자로는 포함시킬 수 없습니다.

* 예시:

2. getopts

* 용도: 


3. sed

* 용도: 파일을 편집할 때 사용된다.

* 설명: stream editor의 약자로, sed 명령은 입력 선을 패턴 공간으로 읽고 주소가 해당 줄을 선택하는 순서대로 모든 sed 하위 명령을 적용하고 패턴 공간을 표준 출력에 작성하여 각 입력 파일 매개 변수를 처리합니다.

    그런 다음 패턴 공간을 지우고 입력 파일 매개 변수에 지정된 각 줄에 대해 이 프로세스를 반복합니다.
 sed는 출력된 결과가 명령과 다르더라도 원본에 손해가 없습니다.

* 예시

|옵션|사용방식|설명|
|------|---|---|
|-n|sed-n'3p'(파일명)|3번째 라인을 출력|
||sed-n'1,3p'(파일명)|1~3번쟤 라인을 출력|
||sed-n'4,$p'(파일명)|4~끝라인까지 출력|
|-e|sed-n-e'1p'-e'3p'(파일명)|-e:여러개의 편집명령을 수행|

4. awk

* 용도: 패턴과 일치하는 파일의 줄을 찾아 해당 줄에서 지정된 작업을 수행할 때 사용된다.

* 설명: awk 명령은 사용자가 제공한 지침 집합을 사용하여 한 번에 한 줄씩 한 줄씩 사용자가 제공하는 일반 식에 대해 비교합니다. 
그런 다음 확장된 정규 식과 일치하는 모든 줄에서 작업이 수행됩니다.
 awk 명령 프로그래밍 언어에는 컴파일이 필요하지 않으며 사용자가 변수, 숫자 함수, 문자열 함수 및 논리 연산자를 사용할 수 있습니다.

* 예시

|사용방식|설명|
|------|---|
|awk'
