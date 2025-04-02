# 생성형 인공지능을 활용한 이미지 분류 프로젝트
##### 마크다운 방법
### 구리고등학교
## 1학년
![스크린샷 2025-04-02 155553](https://github.com/user-attachments/assets/19511a58-108a-4ff5-ac84-ade7dcf13f87)
https://www.youtube.com/watch?v=GQQqBru-Vko
```bash
https://www.youtube.com/watch?v=GQQqBru-Vko
```
**1, 구구단 만들기**
```bash
results = []
for i in range(2, 10):
    for j in range(1, 10):
        results.append(f"{i} x {j} = {i*j}")

print(results)
```
입력받아 구구단 표시하기
```bash
dan = int(input("원하는 단을 입력하세요 (2~9): "))

results = []

if 2 <= dan <= 9:
    for i in range(1, 10):
        results.append(f"{dan} x {i} = {dan * i}")

    print(results)
else:
    print("2에서 9 사이의 숫자를 입력해주세요.")
