# 마크다운 명령어

### 1. 글자 크기 조절


### 방법 1

Heading level 1
===  
```
Heading level 1
===
```

Heading level 2
---
```
Heading level 2
---
```


### 방법 2

# Heading level 1  
```
# Heading level 1
```
## Heading level 2  
```
## Heading level 2
```
### Heading level 3  
```
### Heading level 3
```
#### Heading level 4  
```
#### Heading level 4
```
##### Heading level 5  
```
##### Heading level 5
```
###### Heading level 6  
```
###### Heading level 6
```

<br/>

### 2. Bold  

I just love **bold text**.  
```
I just love **bold text**.  
```  

I just love __bold text__.
```
I just love __bold text__.
```

<br/>

### 3.Italic

I just love *italic text*.  
```
I just love *italic text*.  
```  

I just love italic text_.
```
I just love italic text_.
```

<br/>

### 4. Bold and Italic

I just love ***Bold and Italic text***.  
```
I just love ***Bold and Italic text***.  
```  

I just love Bold and ___Italic text___.
```
I just love Bold and ___Italic text___.
```

<br/>

### 5. 개행

### 방법 1 : 한 줄 띄우기

첫 번째 문장

두 번째 문장
```
첫 번째 문장
(한 줄 띄우기)
두 번째 문장
```

### 방법 2 : 스페이스 두 번

첫 번째 문장  
두 번째 문장
```
첫 번째 문장(스페이스)(스페이스)
두 번째 문장
```

<br/>

### 6. 인용
> 마크 다운은 존 그루버가 만들었다.
```
> 마크 다운은 존 그루버가 만들었다.
```

<br/>

> 마크 다운은 존 그루버가 만들었다.
>
> 텍스트 문서에 서식 요소를 추가해서 사용할 수 있다
```
> 마크 다운은 존 그루버가 만들었다.
>
> 텍스트 문서에 서식 요소를 추가해서 사용할 수 있다
```

<br/>

> 마크 다운은 존 그루버가 만들었다.
>
>> 텍스트 문서에 서식 요소를 추가해서 사용할 수 있다
```
> 마크 다운은 존 그루버가 만들었다.
>
>> 텍스트 문서에 서식 요소를 추가해서 사용할 수 있다
```

<br/>

> ### 마크 다운은 존 그루버가 만들었다.
>
>> 인용문 안에 다른 _마크다운도_ 사용할 수 있다
```
> ### 마크 다운은 존 그루버가 만들었다.
>
>> 인용문 안에 다른 _마크다운도_ 사용할 수 있다
```

<br/>

### 7. 목록

1. 첫번째
2. 두번째
3. 세번째
4. 네번째
    1. 네번째의 처음
    2. 네번쨰의 끝
```
1. 첫번째
2. 두번째
3. 세번째
4. 네번째
    1. 네번째의 처음
    2. 네번쨰의 끝
```

<br/>

* 목록1
* 목록2

- 아이템1
- 아이템2

+ 물건1
+ 물건2
    + 물건2의 1
    + 물건2의 2
```
* 목록1
* 목록2

- 아이템1
- 아이템2

+ 물건1
+ 물건2
    + 물건2의 1
    + 물건2의 2
```

<br/>

### 8. 코드 블럭
```swift
let name: String = "userName"
var age: int = 100
```

\```(프로그래밍 언어)  
let name: String = "userName"  
var age: int = 100  
\```


### 9. 링크  

[네이버](http://naver.com, "링크 설명")
```
[네이버](http://naver.com, "링크 설명")
```


[구글][googlelink]

[googlelink]: https://google.com "링크 설명"
```
[구글][googlelink]
(개행 필수)
[googlelink]: https://google.com "링크 설명"
```

빠른 링크  
<https://www.markdownguide.org>  
<fake@example.com>
```
<https://www.markdownguide.org>  
<fake@example.com>
```

<br/>

### 10.이미지 추가

![대체 텍스트](/assets/testImage.png "이미지 설명")

```
![대체 텍스트](/assets/testImage.png "이미지 설명")
```

### 11. 그 외

\* 한 줄 주석
```
\* 한 줄 주석
```

<br/>

```
문장 주석
```
\```  
\은 생략  
\```

<br/>

`포인트`