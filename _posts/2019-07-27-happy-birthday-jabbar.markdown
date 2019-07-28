---
layout: post
title:  "Happy birthday, Jabbar!"
date:   2019-07-27 10:01:54 +0800
categories: family
---

{% highlight typescript %}

const BIRTH_DATE = '27/7'; // 27 July;
const happyBirthday = (jabbar, date) => {
    return `${date.getDate()}/${date.getMonth() + 1}` === BIRTH_DATE 
        ? `Happy birthday ${jabbar}, many happy returns` 
        : 'happy';
};

happyBirthday('Jabbar', new Date());

// prints 'Happy birthday Jabbar, many happy returns'
{% endhighlight %}

Happy birthday, Jabbar!!
`Many happy returns`
