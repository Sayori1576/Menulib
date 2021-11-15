# Menulib
간단한 콘솔 라이브러리
# How to use
Menulib.h를 다운로드 받아 include하면 사용 가능합니다.
# Example
  ```#include "Menulib.h"
  void printh()
  {
    cout << "ㅎㅇㅇ" << endl;
  }
  void printn()
  {
    cout << "1234" << endl;
  }
  int main()
  {
    Menu M({ {"숫자 출력",printn},{"문자 출력",printh} });
    M.run();
  }
