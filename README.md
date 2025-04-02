# guri_highschool
##### 마크다운 방법
### 구리고등학교
## 1학년
# 키워드를 입력받고 관련 뉴스 출력하기 (간단한 예시)

keyword = input("검색할 키워드를 입력하세요: ")

news_data = [
    {"title": "정치 뉴스: 대선 후보들", "link": "http://news.com/politics"},
    {"title": "기후 변화의 중요성", "link": "http://news.com/climate"},
    {"title": "스포츠: 야구 경기 결과", "link": "http://news.com/sports"},
]

filtered_news = [news for news in news_data if keyword.lower() in news["title"].lower()]

if filtered_news:
    for news in filtered_news:
        print(f"제목: {news['title']}")
        print(f"링크: {news['link']}\n")
else:
    print("해당 키워드와 일치하는 뉴스가 없습니다.")
