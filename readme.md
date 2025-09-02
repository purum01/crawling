# 학습 및 개발 자료
| 개발 환경 구축 | Front End 기본 기술 | 웹 접속 | Selenium | 파이썬 라이브러리 |
|---|---|---|---|---|
| [파이썬 공식 사이트](https://www.python.org/) | [파이썬 기본](https://www.w3schools.com/python/default.asp) | [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/index.html) | [Selenium with Python](https://selenium-python.readthedocs.io/) | [datetime 서식문자](https://docs.python.org/3/library/datetime.html#strftime-and-strptime-format-codes) |
| [아나콘다 사이트](https://anaconda.org/) | [HTML 기본](https://www.w3schools.com/html/) | [Beautiful Soup 한국어](https://www.crummy.com/software/BeautifulSoup/bs4/doc.ko/) | [Action Chains](https://selenium-python.readthedocs.io/api.html#module-selenium.webdriver.common.action_chains) | [pandas](https://pandas.pydata.org/pandas-docs/stable/) |
| [VSCode](https://code.visualstudio.com/) | [DOM 기본](https://www.w3schools.com/js/js_htmldom.asp) | [requests](https://2.python-requests.org//en/master/) | [Special Keys](https://selenium-python.readthedocs.io/api.html#module-selenium.webdriver.common.keys) | [Pandas 요약](https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf) |
| [패키지 저장소](https://pypi.org/) | [JavaScript 기본](https://www.w3schools.com/js/default.asp) | - | [셀레니엄 공식 문서](https://www.selenium.dev/documentation/) | - |


# 예제 사이트 
| 제목 | URL |
|------|-----|
| 네이버증권 | https://finance.naver.com/ |
| 멜론 TOP 100 차트 | https://www.melon.com/chart/index.htm |
| GET방식 테스트 | http://httpbin.org/get |
| POST방식 테스트 | http://httpbin.org/post |
| Naver 블로그 검색 | https://search.naver.com/search.naver?ssc=tab.blog.all&sm=tab_jum&query=korea |
| Open API 개발 사이트 | https://opendart.fss.or.kr/guide/detail.do?apiGrpCd=DS001&apiId=2019001 |
| 대한민국 구석구석 | https://korean.visitkorea.or.kr/ |
| 대한민국 구석구석 검색 | https://korean.visitkorea.or.kr/search/search_list.do?keyword=제주도 |
| 특정 게시글의 상세 정보 추출하기 | https://korean.visitkorea.or.kr/detail/rem_detail.html?cotid=be3db10c-b642-409c-81cc-c4cdecb5bd8b&temp= |
| KRX(한국증권거래소) 상장종목 주요기록 | http://data.krx.co.kr/contents/MDC/MDI/mdiLoader/index.cmd?menuId=MDC0301 |
| 댓글 수집 | https://news.naver.com/main/read.nhn?mode=LSD&mid=shm&sid1=102&oid=056&aid=0010661268 |
| IMDb Top 250 movies | https://www.imdb.com/chart/top/ |
| 아마존 닷컴 | https://www.amazon.com/bestsellers |
| 네이버 실시간 검색 | https://signal.bz/news |
| 네이트 | https://www.nate.com/ |
| zum | https://zum.com/ |


# 🌐 웹 크롤링 시 법적 주의사항 요약

## 1. 저작권 관련
- **콘텐츠 보호**: 텍스트, 이미지, 영상 등은 저작권법으로 보호될 수 있음  
- **합법적 활용 범위**: 공정 이용(Fair Use) 예외가 아니면 상업·비상업 목적 모두 주의 필요  

## 2. 이용 약관 준수
- **서비스 약관(TOS)**: 크롤링을 금지하거나 제한하는 경우가 많음  
- **robots.txt**: 법적 구속력은 없지만 통상적으로 준수해야 하는 규칙  

## 3. 개인정보보호
- **개인정보 수집 제한**: 이름, 이메일, 위치 등 동의 없는 수집은 위법 소지  
- **민감 정보**: 의료, 금융, 정치 성향 등 절대 수집 금지  

## 4. 부정경쟁방지법 및 형사적 책임
- **부정경쟁행위**: 대량 수집, 데이터베이스 무단 모방·판매는 불법 가능성  
- **정보통신망법**: 보안 장치 회피, 비인가 접근은 해킹 행위로 처벌 가능  

## 5. 크롤링 방식 리스크
- **공개 vs 비공개**: 로그인·CAPTCHA 우회는 불법 접근  
- **속도 조절**: 과도한 요청은 DoS 공격으로 간주될 수 있음  

## 6. 안전한 접근 방법
- **공식 API 활용**  
- **운영자 명시적 동의**  
- **데이터 비식별화 처리**  

---

# ✅ 합법적 웹 크롤링 체크리스트

## 1. 접근 권한 확인
- [ ] 사이트 **이용 약관(TOS)** 확인  
- [ ] `robots.txt` 규칙 확인  
- [ ] 로그인·보안장치 우회 금지  

## 2. 데이터 성격 점검
- [ ] **저작권 보호 대상** 여부 확인  
- [ ] **개인정보 포함 여부** 점검  
- [ ] **민감 정보** 수집 금지  

## 3. 수집 방식 안전성
- [ ] 요청 속도 조절 (서버 과부하 방지)  
- [ ] 필요 이상 반복 수집 금지  
- [ ] **내부 분석/연구 목적**으로만 활용  

## 4. 활용 및 보관
- [ ] 데이터 활용 목적이 합법적인가?  
- [ ] 개인정보는 **비식별화 처리** 했는가?  
- [ ] 저작권 자료는 **인용 규정** 준수  

## 5. 대안적 접근 방법
- [ ] 공식 **Open API** 먼저 확인  
- [ ] 필요 시 운영자에게 **사전 허락** 요청  

