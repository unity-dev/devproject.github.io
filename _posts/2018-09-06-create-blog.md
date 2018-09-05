---
title: Jekyll과 minimal-mistakes 테마를 이용한 블로그 생성
categories:
  - Blogs
tags:
  - Blog
  - Jekyll
  - minimal-mistakes
---

# 발단
[GitBucket](https://github.com/gitbucket/gitbucket){:target="_blank"} 을 통하여 WIKI에 Unity 개발 팁을 작성 하였었는데,
Gitbucket을 Localhost 에서만 접속이 가능하게끔 구축해놓아서 , 외부에서 볼 수 없다는 단점으로 인하여 
Unity 를 공부할 수 있는기술적인 내용을 작성하자! 라는 마음에 `Github.io` 블로그를 구축하게 되었다.

# 테마 결정
구글링을 하다보니 Github의 Star가 많은 minimal-mistakes 로 우선 시작해보기로 했다.

# 테마 페이지 가져오기

> 이 내용은 [minimal-misatakes의 퀵가이드](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/){:target="_blank"} 에서 더 자세하게 볼 수 있다.

# MD 파일 타이틀 작성 방법 
(게시물제목,태그 등등)


```yaml
---
title: Jekyll과 minimal-mistakes 테마를 이용한 블로그 생성
categories:
  - Life
tags:
  - life
author: HyoJun
---
```

이런식으로 작성하면 된다.

author 은 _data/authors.yml 에서 추가 및 수정이 가능하다.