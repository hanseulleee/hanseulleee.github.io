---
layout: post
title: [JavaScript] ES6 Set 
subtitle: ES6 Set
tags: [JavaScript, Set, ES6]
comments: true
---

ES6에서는 'Set' 이라는 데이터 타입을 사용 할 수 있다.

Set은 중복된 값을 저장하지 않는 리스트이다.


Constructor

{% highlight javascript linenos %}
const testSet = new Set(); 
}

Set을 만들 때 중복되는 값을 가진 데이터를 넘기면,
Set이 알아서 중복되는 값을 제외하고 맨 처응 데이터만 남깁니다.

{% highlight javascript linenos %}
    const testSet = new Set([1, 2, 3, 1, 4, 2, 5]);
    console.log(testSet); // Set {1, 2, 3, 4, 5}
{% endhighlight %}


Method

add(value) : set에 데이터 추가

size: set의 데이터 갯수

has(value): set에 데이터 존재 여부

delete(value): set에 데이터 삭제

clear: set의 모든 데이터 삭제 !!!

