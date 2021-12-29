# 감성사전을 활용한 아이패드와 갤럭시 탭 감성분석


 본 연구에서는 ‘아이패드(iPad)’와 ‘갤럭시 탭(Galaxy Tab)’의 사용자 리뷰에 대한 속성기반 감성분석(AbSA, Aspect-Based Sentiment Analysis)을 진행하고, 이를 통해 제품의 소비자 선호도를 비교 및 분석하고자 하였다.

> 데이터 수집


![image](https://user-images.githubusercontent.com/89879599/147646135-9b60f0c6-34d6-4978-870c-77ba0641a005.png)


'Deco-R-Crawler'를 활용한 크롤링


아이패드 : ‘아이패드 에어 4세대’, ‘아이패드 9세대’, ‘아이패드 미니 6세대’, ‘아이패드 프로 5세대’, ‘아이패드 미니 5세대’, ‘아이패드 8세대’ 


갤럭시 탭 : ‘갤럭시 탭 S7 FE’, ‘갤럭시 탭 S7+’, ‘갤럭시 탭 S7’

 
> 전처리 

 
 ![image](https://user-images.githubusercontent.com/89879599/147645525-8de80eb9-5b97-4c16-998c-f8d9cc71decc.png)

 
수집된 데이터를 utf-8 txt로 변환 후 '전처리 문법 테이블' 적용

 
>토크나이징

 
>Seed 구축 및 Word2Vec 임베딩
 

 ![image](https://user-images.githubusercontent.com/89879599/147646639-0668eec7-daec-4d8b-a212-f4fca26b51af.png)

 
>Opinion Triple Word(OTW) 사전 구축

 
>주석데이터 생성

 
![image](https://user-images.githubusercontent.com/89879599/147648123-ad2ab284-9ef8-498a-86ca-472f20ec8dba.png)


>시각화

 
![image](https://user-images.githubusercontent.com/89879599/147648168-02b487ee-15b5-4014-b03f-87fec02b3325.png)

 
![image](https://user-images.githubusercontent.com/89879599/147648177-c3704b62-a1d9-48da-82f4-b26cceed034a.png)

 
