---
layout: post
title:  "Contribuitor guide"
date:   2017-05-23 23:27:00 +0700
categories: misc
author: nobita-isc
---

### How to contribute
Dưới đây là trình tự để post 1 bài mới lên blog

- Fork repository dưới đây:

[https://github.com/nobita-isc/nobita-isc.github.io](https://github.com/nobita-isc/nobita-isc.github.io)

- Trên repo của mình, tạo nhánh mới với quy ước đặt tên là post-name-in-english. Sau đó tạo bài viết mới trong thư mục _post với quy ước đặt tên như sau:

yyyy-mm-dd-post-name-in-english.markdown

- Tạo PR trên repo [nobita-isc.github.io](https://github.com/nobita-isc/nobita-isc.github.io)

Sau khi được merge, nội dung bài viết sẽ được tự động đưa lên [blog SotaML](http://ml.sotatek.com).

### How to setup

Blog này sử dụng [jekyll](https://jekyllrb.com/) để compile static html file. Hãy tham khảo hướng dẫn cài đặt trên trang chủ của [jekyll](https://jekyllrb.com/).

Ruby cần phải được cài đặt trước khi thực hiện cài đặt jekyll.

### Frequently used command-line

Tạo một localhost web server để xem trước nội dung bài viết.
```
$ bundle exec jekyll serve
```