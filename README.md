### openSourceSW_03_20185032


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
