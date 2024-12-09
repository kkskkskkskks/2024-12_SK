# MarkDown 문법정리

## MarkDown
> 일반 텍스트 형식 구문을 사용하는 마크업 언어의 일종 (쉽고, 빠르고, 간결)
> 모든 HTML을 대체하지는 않는다.
> 자유로운 포맷팅
 
## 1. Header (제목)
> 헤더는 제목을 표현할 때 사용한다.
> 단순히 글자 크기를 의미론적인 중요도를 갖는다.
> `<h1>`부터 `<h6>`까지 표현 가능
> `#`의 개수로 표현

## 2. List(목록)
> 목록을 나열할 때 사용한다.
> 순서가 필요한 목록과 순서가 필요없는 목록으로 구분된다.
* 순서가 없는 목록
  * `-`또는 `*`로 생성할 수 있다.
  * `tab`키를 눌러서 하위 항목으로 이동하고, `Shift` + `tab`을 눌러서 상위 항목으로 이동할 수 있다.
* 순서가 있는 목록
  * `1.`~`n.`으로 생성할 수 있다.
  * `tab`키를 눌러서 하위 항목으로 이동하고, `Shift` + `tab`을 눌러서 상위 항목으로 이동할 수 있다.

## 3. Code Block (코드 블록)
> 작성한 코드를 정하거나 강조하고 싶은 부분을 나타낼 때 사용한다.
> inline과 block으로 구분된다.
`git remote add https://github.com/USERNAME/REPOSITORYNAME`
```bash
    git add .
    git commit -m "커밋메시지"
    git push origin main
```
```python
    print('hello world')
```

## 4. Link (링크)
>특정 주소로 링크를 걸 때 사용한다.
[깃허브](https://github.com)
![](https://placeholder.com/200x200)

### 5. Table (표)
> `|`를 활용해 표를 작성할 수 있다.



### 6. ETC (기타)
> 인용문

수평선
---
***
___
*기울임체*
**볼드체**
***취소선***
