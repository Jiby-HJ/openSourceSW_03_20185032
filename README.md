### openSourceSW_03_20185032


- **getopt**
- 
  유닉스나 리눅스에서 프로그램 실행 시 '-a', '-l' 등 별도의 옵션을 줄 수 있다. 
  
  이러한 옵션(아규먼트)을 쉽게 처리하기 위해 만들어진 함수가 getopt이다. 
  
  유닉스는 unistd.h를 리눅스는 getopt.h 헤더파일을 include하면 사용 할 수 있다. 
  
  그리고 이 함수는 main함수에서 많이 사용되고 있다.
  
  모든 C(C++)로 된 프로그램은 보통 main 함수를 정의할 때 아래와 같이 두 개의 파라미터를 가진다. 
  
  프로그램이 커맨드 라인에서 인수를 받는 방법은 main 함수를 통해서만 가능하다.
  
  ` int main(int argc, char *argv[])`
  
  argc 파라미터는 커맨드 라인에서 넘어온 인수의 개수를 뜻하며, argv 파라미터는 C 문자열 벡터이다.
  
  argv 의 각 요소들은 공백으로 분리된 개별적인 커맨드 라인 인수 문자열이다.

  
  
- **getopts**






- **sed**

  sed(stream editor)는 유닉스에서 텍스트를 분해하거나 변환하기 위한 프로그램이다.
 

- **awk**
