---
title: "Gọi API bằng Fetch trong JavaScript"
date: 2025-12-23
draft: false
categories: ["JavaScript"]
tags: ["JavaScript", "API"]
image: "j9.jpg"
imagePosition: "center 52%  "
---

## 1. API là gì?
API cho phép các hệ thống giao tiếp với nhau.

## 2. Fetch API
Fetch giúp lấy dữ liệu từ server dễ dàng.

## 3. Ví dụ
```javascript
fetch("https://api.example.com/data")
  .then(res => res.json())
  .then(data => console.log(data));
