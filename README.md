# nanri77.github.io

매주 배운 것을 정리하는 **Weekly I Learned** 블로그입니다.

- URL: https://nanri77.github.io
- 엔진: Jekyll + GitHub Pages (테마: `minima`)

## 새 글 작성

`_posts/YYYY-MM-DD-title.md` 파일을 만들고 아래 front matter로 시작합니다.

```yaml
---
layout: post
title: "글 제목"
date: 2026-05-16
categories: [wil]
tags: []
---
```

## 로컬 미리보기 (선택)

```bash
bundle install
bundle exec jekyll serve
```

푸시만 해도 GitHub Actions가 자동 빌드/배포합니다.
