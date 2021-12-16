---
title: "A"
date: 2021-12-16T15:21:21+08:00
draft: true
toc: false
images:
tags:
  - untagged
---

## 平台

- tetete

  ```sql
  use platform;
  select app_id,count(*),api_hash from billing_api_consumption group by app_id,api_hash
  ```

  接口和apihash的对应关系
