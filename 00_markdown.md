# 마크다운(Markdown)

> 일반 텍스트 형식 구문을 사용하는 마크업 언어의 일종으로 사용법이 쉽고 간결하여 빠르게 문서 정리를 할 수 있습니다. 단, 모든 HTML 마크업을 대체하지는 않습니다.



## 1. 문법

### 1.1 Header

> 헤더는 제목을 표현할 때 사용합니다. 단순히 글자의 크기를 표현하는 것이 아닌 의미론적인 중요도를 나타냅니다.

* `<h1>`부터 `<h6>`까지 표현 가능합니다.
* `#`의 개수로 표현하거나 `<h1></h1>`의 형태로 표현 가능합니다.



# h1 태그입니다.

## h2 태그입니다.

### h3 태그입니다.

#### h4 태그입니다.

##### h5 태그입니다.

###### h6 태그입니다.

### 1.2 List

> 목록을 나열할 때 사용합니다. 순서가 필요한 항목과 그렇지 않은 항목으로 구분할 수 있습니다. 순서가 있는 항
> 목 아래 순서가 없는 항목을 지정할 수 있으며 그 반대도 가능합니다.

* 순서가 없는 목록

  * `1.` 을 누르고 스페이스바를 누르면 생성할 수 있습니다.
  * `tab` 키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위 항목으로 이동 할 수 있
    습니다.

* 순서가 있는 목록

  * `-`(하이픈)을 쓰고 스페이스바를 누르면 생성할 수 있습니다
    `tab` 키를 눌러서 하위 항목을 생성할 수 있고 `shift + tab` 키를 눌러서 상위 항목으로 이동 할 수 있

  습니다.

1. 순서가 있는 항목
2. 순서가 있는 항목
   1. 순서가 있는 하위 항목
   2. 순서가 있는 하위 항목



* 순서가 없는 항목
* 순서가 없는 항목
  * 순서가 없는 하위 항목
  * 순서가 없느 하위 항목



### 1.3 Code Block

> 코드 블럭은 작성한 코드를 정리하거나 강조하고 싶은 부분을 나타낼 때 사용합니다. 인라인과 블럭 단위로 구분
> 할 수 있습니다.



* Inline
  * 인라인 블럭으로 처리하고 싶은 부분을 `(백틱)으로 감싸줍니다.
* Block
  * \`(백틱)을 3번 입력하고 `Enter`를 눌러 생성합니다. 
  * 백틱 3번에 언어 하고 enter 누르면 해당 언어로 코드블럭이 생성된다.



`add`한 요소를 remote 저장소에 올리려면 `$ git push origin master`를 터미널에 입력합니다. (language shell)

```shell
$ git add .
$ git commit -m "first commit"
$ git push origin master
```



### 1.4 Image

> 로컬에 있는 이미지를 삽입하거나 이미지 링크를 활용하여 이미지를 나타낼 때 사용합니다.

* `![]()` 을 작성하고 `()` 안에 이미지 주소를 입력합니다. `[]` 안에는 이미지 파일의 이름을 작성합니다.

* 로컬에 이미지 파일을 저장한 경우 절대 경로가 아닌 상대 경로를 사용하여 이미지를 저장합니다.

  



<img src ="data:image/png;base64,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" width="200" height="100" align="left" >

<img src="data:image/png;base64,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" width="200" height="100" align="right">

### 1.5 Link

> 특정 주소로 링크를 걸 때 사용합니다.

* `[] ()` 을 작성하고 `()` 안에 링크 주소를 작성하고 `[]`안에 어떤 링크주소인지 작성합니다

[git 공식문서](https://git-scm.com/)

[github 공식문서](https://github.com/)



### 1.6 Table

> 표를 작성하여 요소를 구분할 수 있습니다.

* `|`(파이프) 사이에 컬럼을 작성하고 `enter`를 입력합니다.
* 마지막 컬럼을 작성하고 뒤에 `|`를 붙여줍니다.

| **working directory** | **statging area** | **remoe repo** |
| --------------------- | ----------------- | -------------- |
| working tree          | index             | history        |
| working copy          | cache             | tree           |



### 1.7 기타

**인용문**

* `>`을 입력하고`enter`키를 누룹니다.

> git은 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산
> 버전 관리 시스템이다.

* 인용문 안에 인용문을 작성하면 중첩해서 사용할 수 있습니다.

> $ git add.
>
> > $ git commit -m "first commit"
> >
> > > $ git push origin master



**수평선**

* `---`,`***`,`___`을 입력하여 작성합니다.



Working Directory

Working Directory

---

Staging Area

***

Remote Repository

___



**강조**

* 이탤릭체는 해당 부분을 * 혹은 _ (언더바) 로 감싸줍니다.
* 보드체는 해당 부분을 ** 혹은 __ (언더바 2개)로 감싸줍니다.
* 취소선은 ~~ 표시를 사용합니다.

이것은 *이탤릭체*입니다.

이것은 **보드체**입니다.

이것은 ~~취소선~~입니다.



### 2. 과제

> 현재의 pdf 문서를 마크다운 문법을 활용하여 00_markdown_basic.md 로 만들어 보세요.