# 역사스페셜

현대 POSIX 준수 운영체제의 공통 조상인 UNIXv6을 x86 아키텍쳐상에서 재해석해보며 운영체제의 동작 방식에 대해 이해하고 학습합니다.

- [“UNIX V6로 배우는 커널의 원리와 구조”(아오야기 카타히로 저)](http://www.kyobobook.co.kr/product/detailViewKor.laf?barcode=9788968480966)의 내용을 바탕으로 매주 한 챕터씩 세미나, 코드 리뷰 등을 진행합니다. 
- 해당 챕터에서 본인이 탐구해보고자 하는 부분(보안, 알고리즘 등) 이 있는 경우 스스로 연구하여 발표해 볼 수 있도록 합니다.

### 모집대상 

운영체제에 대한 깊은 이해를 원하는 모든 분들


### 커밋 규칙

 - C 언어를 사용합니다. 다른 언어를 사용해도 무방하나, 되도록이면 통일되는 편이 좋습니다.
 - 탭은 4스페이스를 사용합니다. 다만 Make와 같이 tab(`\t`) 문자가 문법상 강제되는 경우에는 예외로 합니다.
 - 변수, 함수 등에는 snake notation을 사용합니다. e.g. `process_lock`, `user_update`
 - 프레젠테이션은 PDF 로 첨부하여야 합니다.
 - 작업이 길어질 소지가 있는 경우 브랜치를 따서 작업한 후 나중에 머지하는 것이 권장됩니다.
