멜론 플레이리스트 기반 음악 및 태그 추천
==========================
목표
--------------------
플레이리스트의 곡과 태그를 입력받아 연관성있는 음악, 태그 추천             
데이터 출처: 카카오 아레나 "Melon Playlist Continuation"      
                
개발환경: Python3.6, Jupyter          
                          
1. 데이터 탐색(EDA)
2. matplotlib, seaborn 시각화 라이브러리를 이용한 데이터 파악
3. 협업 필터링 방식을 이용한 음악 추천
4. 컨텐츠 기반 방식을 이용한 음악 추천
5. 신경망을 이용한 태그 추천
                       
프로젝트 진행 기간
--------------------
2020.10.19~2020.10.30

역할
--------------------
* EDA작업
* 컨텐츠 기반 음악 추천
* 신경망을 이용한 태그 추천

최종 결과물
--------------------
* 입력 곡과 유사한 Top-N개의 곡 추천           
* 입력 곡과 유사한 태그 추천           
* 신경망을 이용한 태그 추천 -> 실패 너무 낮은 정확도(0.06%)를 가짐

아쉬운 점
--------------------
* 다양한 파라미터를 비교해보며 학습을 진행하지 못한 점이 아쉽다.
* GPU를 사용하지 못해 신경망 학습의 결과를 보는데에 너무 오래 걸렸다.      
* 실시간으로 변화하는 온라인 환경에서 구동하기 위한 방법을 찾아봐야 할 것 같다.
* cosine유사도를 구하는 과정에서 Matrix가 너무 커서 오류가 발생했다.