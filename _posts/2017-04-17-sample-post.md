---
layout: post
title: 마크다운으로 글쓰기
excerpt: "이곳에는 인용 문구를 넣어서 멋진 척을 할 수 있습니다."
categories:
comments: true
image:
  feature: https://cdn.pixabay.com/photo/2014/12/03/21/20/kittens-555822_960_720.jpg
  credit: 전국애묘협회
  creditlink: https://pixabay.com/
---

마크다운을 이용해 아래와 같이 표현 할 수 있습니다.

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

### 본문 작성에 대해 알아봅시다.

마크다운에서 "** **" 을 사용하면 **이렇게 강조를 할 수 있습니다.**. 정말 쉽고 멋지죠! 사실 저는 ctrl+b가 더 편한데.. 뭐 지원을 안하니..

이미지를 넣고 싶다면 !와 [Smithsonian Image]를 이용해 넣을 수 있습니다. 이 뒤에 이미지 경로를 붙이면 됩니다.

일단 **고양이 사진**을 보고 가시죠.

![Smithsonian Image](https://cdn.pixabay.com/photo/2014/06/03/01/31/cat-360807_960_720.jpg)

이텔릭체로 글을 쓰고 싶으시다구요?
뭐, 가끔 그렇게 비스듬히 글을 쓰고 싶을 때가 있습니다.
그럴땐 "* *"를 사용해보세요.
*이렇게 말이죠*.
참 쉽죠?


### 멋진 인용문을 쓸때

내가 한 말을 아니지만 가지고 오고 싶은 말이 가끔 있습니다.
그럴 땐 인용 표시를 해줍시다. 사실 그냥 블록 하나 추가하는 거에요.
" > " 를 사용하면 쉽게 할 수 있습니다.

> 치킨은 인 당 한 마리씩 시켜야 다툼이 없다.

이렇게 말이죠.

## 목차를 만들고 싶다구요?

그런 번거로운 것을..! 아닙니다. 때론 필요합니다.

### 목차  <- 요건 제목처럼 해주세요.

1. 번호를 붙이고 Enter를 치면
   1. 이렇게
   2. 목차 형태로
   3. 보여집니다.
      물론 이렇게 본문도 쓸 수 있구요.
      
2. 구조적/형식적인 글을 쓸 때 유용하겠군요!

### 번호가 싫으시다면

* 이렇게 점으로 하는 방법도 있습니다.
* "*"을 붙이고 글을 쓰면 앞에 이렇게 점이 생겨요.
* PPT 같은 곳에서 많이 보던 스타일이죠.
* 저는 번호보다 이게 더 좋네요.

## 표를 만들고 싶다니..?

마크다운에서 표를 만드는 것 아주 귀찮습니다.

| Header 1 | Header 2 | Header 3 |
|:--------|:-------:|--------:|
| cell 1   | cell 2   | cell 3   |
| cell 4   | cell 5   | cell 6   |
|----
| cell 1   | cell 2   | cell 3   |
| cell 4   | cell 5   | cell 6   |
|=====
| Foot 1   | Foot 2   | Foot 3   |

이렇게 만들 수 있지만 그냥 엑셀을 쓰는게 234623528배 정도 편합니다.
엑셀을 쓰세요.

## 코드를 멋드러지게 문법을 적용하고 싶을땐 이렇게 해봅시다.

highlight와 코드명을 입력하고 아래와 같이 치면 됩니다.

{% highlight python %}
print "hello world"
{% endhighlight %}

하긴.. 누가 신경 쓰겠어요.

## 이쁜 버튼을 달고 싶다면

저는 잘 쓰지 않지만 버튼도 이렇게 만들수 있죠`.btn` 클래스를 이용해서요.
사실 위의 highlight를 html로 나타낸거랍니다. 정말 귀찮군요!

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">시작 버튼</a></div>
<div markdown="0"><a href="#" class="btn btn-success">성공 버튼</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">주의 버튼</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">위험 버튼</a></div>
<br>
<div markdown="0"><a href="#" class="btn btn-info">이걸 왜 하고 있죠?</a></div>
