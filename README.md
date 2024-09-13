# news_summary
전 세계의 뉴스를 한국어로 요약해줍니다.

검색어 키워드를 입력할때 한국어로 입력할 때와 영어로 입력할 때가 다른 결과가 나옵니다.
미국 사이트에서 검색할때와 한국 사이트에서 검색할 때도 다르게 나옵니다.

이 사이트는 한국어로 검색어를 입력하면 전 세계의 뉴스 기사를 불러와 한국어로 요약해줍니다.
뉴스 내용이 더 궁금하다면 원문을 볼 수도 있습니다.

현재는 영어 뉴스만 포함됩니다. (업데이트 예정)
NewsAPI를 이용해 뉴스의 원문을 링크 형식으로 불러왔고 본문을 추출하고, 왓슨ai의 llama-3-70b-instruct 모델을 이용해 요약하고 번역합니다.
번역이 안된 본문은 mistralai/mistral-large모델을 이용해 추가 번역합니다.


![image](https://github.com/user-attachments/assets/9325968a-a735-404d-800d-642290f5ea7c)


![image](https://github.com/user-attachments/assets/9e215a1b-f424-42c5-865e-68134f9ff9d7)
