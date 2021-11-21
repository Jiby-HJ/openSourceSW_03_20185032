### openSourceSW_03_20185032
--- 


- **getopt**
  - define :  \
    유닉스나 리눅스에서 프로그램 실행 시 '-a', '-l' 등 별도의 옵션을 줄 수 있다. \
    이러한 옵션(아규먼트)을 쉽게 처리하기 위해 만들어진 함수가 getopt이다. \
    유닉스는 unistd.h를 리눅스는 getopt.h 헤더파일을 include하면 사용 할 수 있다. \
    \
    `int main(int argc, char *argv[])` \
    \
    argc 파라미터는 커맨드 라인에서 넘어온 인수의 개수를 뜻하며, argv 파라미터는 C 문자열 벡터이다.  \
    argv 의 각 요소들은 공백으로 분리된 개별적인 커맨드 라인 인수 문자열이다.
  
- **getopts**




- **sed** 
  - define :  \
      sed(stream editor)는 유닉스에서 텍스트를 분해하거나 변환하기 위한 프로그램이다. \
      필터링과 텍스트를 변환하는 스트림 편집기이며 원본 변화없이 출력 결과를 변화시킨다.
      
  - syntex : \
      `sed 's/찾을텍스트/바꿀텍스트/' 파일명`
              
  
 

- **awk**
  - define : \
    AWK(오크;Aho Weinberger Kernighan)는 유닉스에서 처음 개발된 일반 스크립트 언어이다. \
    AWK의 기본 기능은 텍스트 형태로 되어있는 입력 데이터를 행과 단어 별로 처리해 출력하는 것이다. \
    AWK 프로그램은 기본적으로 패턴과 패턴을 처리하는 명령어 짝을 늘여놓은 구조로 이루어져 있다. \
    입력으로부터 한 줄씩을 읽어서 정규 표현식으로 조건이 맞는지를 검사하고 참으로 판명되면 \
    그 줄에 대해 명령어를 실행하는 형식이다.
