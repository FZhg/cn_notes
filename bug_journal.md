---
title: Bug贴
tags:
keywords:
last_updated: Demcember 9, 2019
summary: "我在学习的过程中遇到的Bug会在这里记录下来。"
sidebar: home_sidebar
permalink: bug_journal.html
search: exclude
---
| Bug Name        | Description           | Dates  | Counts|
|:-------------|:-------------|:----|:---|
| Private instance varibale is initialized with declaration.    | Since java will treate the newly declared variable as a new variable, the old private instance variable will be set to default. If the varibale is an istance of Object, it will be set to Null, which thorws out NullPointerException. It is really difficault to debug, because I had the expectation that the code will work. | 12-6-2019 | 1|
