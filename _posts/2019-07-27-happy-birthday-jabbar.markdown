---
layout: post
title:  "Happy birthday, Jabbar!"
date:   2019-07-27 10:01:54 +0800
categories: family
---

{% highlight typescript %}

const happyBirthday = (jabbar, date) => {
    return `${date.getDate()}/${date.getMonth() + 1}` === '27/7' 
        ? `Hello ${jabbar}, many happy returns` 
        : 'happy';
};

happyBirthday('Jabbar', new Date());

// prints 'Hello Jabbar, many happy return'
{% endhighlight %}

Happy birthday, Jabbar!!
`Many happy returns`
