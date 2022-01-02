# scheduler_interpark

내 입맛에 맞는 스케줄 검색  
(모든 스케줄과 랭킹은 인터파크 기준임)  

inter_sch.exe - 실행 파일  

1. 실행 시 오늘 날짜 기준으로 뮤지컬, 연극 ranking top 20 의 goodsCode 출력  
   goodsCode? url에서 goods/ 뒷부분  
   ex) https://tickets.interpark.com/goods/21009146 -> goodsCode : 21009146  
2. goodsCode를 알고 있다면 입력, 또는 위의 list에서 goodsCode 찾아 입력  
3. 검색 시작 날짜와 끝 날짜 입력  
   입력하지 않고 enter 시 공연의 시작 날짜, 끝 날짜로 자동 입력됨  
4. In/Out에 포함/제외할 배우 입력  
   입력 rule) 'and' -> comma / 'or' -> space  
   In에 입력하지 않고 enter 시, 전부 포함  
   In : A,B     ---> A,B 모두 포함(스페이스 넣지 말 것)  
   In : A B     ---> A 또는 B 포함  
   In : A,B C,D ---> A,B 포함된 스케줄 + C,D 포함된 스케줄  
   Out : A B    ---> A, B 제외(스페이스로 구분할 것)  
5. 조건에 맞게 필터링 된 스케줄 출력  


ex)  
(예시는 예시일 뿐.. 악의XX)  
![예시1](https://user-images.githubusercontent.com/55429978/147873128-a46b93d2-83f9-4d14-aa67-abafaa0d8e55.PNG)
![예시2](https://user-images.githubusercontent.com/55429978/147873185-0393aa04-c4f7-4f5a-a844-dfe6e949cfc5.PNG)
![예시3](https://user-images.githubusercontent.com/55429978/147873295-846cab15-41e1-464a-82e7-1a5687cadf6a.PNG)
![예시4](https://user-images.githubusercontent.com/55429978/147873199-4042efaa-048c-4d84-9b4d-1e85a460847b.PNG)
![예시5](https://user-images.githubusercontent.com/55429978/147873205-f97ec1ed-acd3-4b03-99bb-905d7407a567.PNG)

