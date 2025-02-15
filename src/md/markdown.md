# 마크다운 문법

---

## 1. 제목(Header)

```markdown
# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6
```

**결과:**

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

---

## 2. 텍스트 스타일링 (굵게, 기울임, 취소선)

```markdown
**굵게**
_기울임_
~~취소선~~
```

**굵게**, _기울임_, ~~취소선~~

---

## 3. 목록 (List)

### ✔️ 순서 없는 목록

```markdown
- 항목 1
  - 하위 항목 1
  - 하위 항목 2
- 항목 2
```

**결과:**

- 항목 1
  - 하위 항목 1
  - 하위 항목 2
- 항목 2

### ✔️ 순서 있는 목록

```markdown
1. 첫 번째 항목
2. 두 번째 항목
   1. 하위 항목 1
   2. 하위 항목 2
```

**결과:**

1. 첫 번째 항목
2. 두 번째 항목
   1. 하위 항목 1
   2. 하위 항목 2

---

## 4. 코드 블록

```markdown
인라인 코드: `print('Hello, World!')`
```

인라인 코드: `print('Hello, World!')`

### ✔️ 여러 줄 코드 블록

````markdown
```python
print("Hello, Markdown!")
```
````

````

결과:
```python
print("Hello, Markdown!")
````

---

## 5. 인용문

```markdown
> 이것은 인용문입니다.
>
> > 중첩된 인용문입니다.
```

**결과:**

> 이것은 인용문입니다.
>
> > 중첩된 인용문입니다.

---

## 6. 링크 & 이미지

### ✔️ 링크 (Link)

```markdown
[Google](https://www.google.com)
```

[Google](https://www.google.com)

### ✔️ 이미지 (Image)

```markdown
![Alt 텍스트](이미지_URL)
```

예제:

```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

**결과:**
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### ✔️ 이미지 크기 조정

HTML 태그를 사용하여 크기 조정이 가능하다.

```markdown
<img src="이미지_URL" width="200" height="100">
```

예제:

```markdown
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="100" height="100">
```

---

## 7. 테이블 (Table)

```markdown
| 헤더 1 | 헤더 2 | 헤더 3 |
| ------ | ------ | ------ |
| 내용 1 | 내용 2 | 내용 3 |
| 내용 A | 내용 B | 내용 C |
```

**결과:**
| 헤더 1 | 헤더 2 | 헤더 3 |
|--------|--------|--------|
| 내용 1 | 내용 2 | 내용 3 |
| 내용 A | 내용 B | 내용 C |

---

## 8. 가로선 (Horizontal Rule)

```markdown
---
---
```

## 결과:

---

---

## 9. 체크리스트 (Task List)

```markdown
- [x] 완료된 항목
- [ ] 미완료된 항목
```

**결과:**

- [x] 완료된 항목
- [ ] 미완료된 항목

---

## 10. 이모지 (Emoji)

```markdown
:apple: 🍎 :banana: 🍌 :grapes: 🍇
```

## 🍎 🍌 🍇

## 11. 줄 바꿈 (Line Breaks)

```markdown
한 줄 작성 후  
두 번째 줄 (띄어쓰기 두 개 필요)
```

**결과:**
한 줄 작성 후  
두 번째 줄

---

## 12. HTML 태그 사용

```markdown
<u>밑줄</u>
<mark>형광펜</mark>

<details>
  <summary>클릭하면 열려용</summary>
  숨겨진 내용!
</details>
```

<u>밑줄</u> <mark>형광펜</mark>

<details>
  <summary>클릭하면 열려용</summary>
  숨겨진 내용!
</details>

---

## 13. 수식 표현 (LaTeX)

```markdown
$$E = mc^2$$
```

$$E = mc^2$$

---

## 14. 주석 (Comment)

```markdown
<!-- 이 부분은 보이지 않습니다 -->
```

---
