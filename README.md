### Myongji University Project
### OpenSW_modify
-----------------------------------
#### 요약문
>  본 프로젝트에서는 공개 SW 활용 및 파이썬 프로그래밍 역량 향상을 위해 파이썬, 공개SW, 개발도구 등 기초 기술을 공부하며 파이썬을 이용한 공개SW 프로젝트 활동을 수행한다.
공개SW는 GitHub커뮤니티의 ‘2048-python (개발자 yangshun)'의 SW를 참고하며, 개발에 사용된 코드와 로직 등을 분석하고 보완한다.
 프로젝트를 진행하는 동안 소스코드를 분석해보며 부족한 점을 찾아서 코드를 보완하고, 사용자들의 편의를 증가시킬 수 있다. 이러한 과정에서 파이썬 프로그래밍 능력을 향상시킬 수 있으며 팀원들과의 협동심을 기를 수 있다.
 본 게임의 목적은 격자 위에 있는 수많은 타일들을 사용자의 키보드 입력을 받아 움직여서 병합한 
음, 2048이라는 숫자의 타일을 하나 만들어 내는 것이다. python 언어로 개발되었으며, 350줄 가량의 소스라인과 3개의 파이썬 파일로 작성되었다. 어렵지 않은 게임방법과 낮은 진입 장벽으로 남녀노소 누구나 플레이할 수 있으며 접근성이 좋으며, 2의 배수를 이용해 2048이라는 수를 만드는 과정에서 뇌를 활발하게 할 수 있다.

>프로젝트에 선정한 공개SW의 전체적인 프로그램 작동방식과 세부적인 기능들에 대하여 알아보았으며, 이에 사용된 자료구조 및 함수와 클래스들을 분석해보았다. 이 과정에서 프로그램의 문제점들이 여럿 확인되었고, 분석한 결과물들을 참고하여 추후 개선방안들을 모색하였다. 팀원들은 계획한 프로젝트의 일정에 따라, 앞서 모색한 개선방안들을 실행해나갈 것이다.

>확인된 프로그램의 여러 문제점들을 팀원들이 모색한 개성방안들에 따라 보완해나간 결과, 성공적인 결과를 거두었다. 팀원들이 개선하고자 했던 프로그램의 모든 문제점들을 개선방안에 따라 완벽하게 이루어나간 것이다. 계획했던 사항들을 성공적으로 마무리한 팀원들은, 자기평가와 향후 계획을 세운 뒤 프로젝트를 종료한다.
-----------------------------------
#### 2020.11.16 - 1차 업뎃
##### -게임 실행 전 설정화면 생성 완료-
>신규UI를 추가하여 컴파일시 바로 게임이 시작되던 방식을 개선했습니다.
>4x4의 크기로만 진행이 되던 게임을 5x5, 6x6까지 확장하였으며 신규UI를 통해 사용자가 크기를 선택할 수 있도록 하였습니다.

#### 2020.11.17 - 2차 업뎃
##### -도움말 기능 추가-
>처음 접하는 사용자가 어려움을 겪지 않도록 게임의 진행방식과 조작법, 승패조건에 대해 안내를 해주는 도움말 버튼을 추가했습니다.

#### 2020.11.17 - 3차 업뎃
##### -사운드 기능 추가-
>게임의 재미 향상을 위해 사운드를 여럿 추가했습니다.

#### 2020.11.17 - 4차 업뎃
##### -logic.py - 생성숫자 4추가-
>타일이 생성될 시 2뿐만 아니라 2와 4 둘 중 하나가 랜덤으로 생성되도록 수정했습니다.

#### 2020.11.17 - 5차 업뎃
##### -사운드 관련 수정-
>사운드 관련 코드들을 일부 수정했습니다.

#### 2020.11.17 - 6차 업뎃
##### -게임 종료 후 다시시작 기능 생성-
>게임이 종료된 후 점수를 표기해주는 UI를 추가하였으며,
>게임을 재시작 할 수 있는 버튼을 추가했습니다.

#### 2020.11.21 - 최종 업뎃
##### -되돌리기 기능 오류 수정, 자료구조 수정-
>되돌리기 키를 눌렀을 때 첫 입력이 누락되는 오류를 수정했습니다.
>기존에 선형탐색을 사용하던 자료구조를 이진탐색으로 변경했습니다.

개선 사항들의 최종 테스트를 마쳤습니다.
-------------------------------------------
