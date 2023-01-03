---
layout: post
title:  "첫 트레이딩 일기"
date:   2023-01-03 20:59:36 GMT+9
categories: System-Trading
---
트레이딩을 하며 처음 작성하는 글


아래 마크다운 예시처럼 앞으로 블로그 글을 작성할 때 사용하면 되겠다! 
이제 시스템 트레이딩 개발 일지를 앞으로 만들어나갈 것이다.

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
