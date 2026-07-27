---
title: 'OpenSSH 升級與實務踩坑紀錄'
description: '紀錄伺服器 OpenSSH 升級流程，確保連線安全與憑證設定正確。'
date: 2026-07-27
slug: 'openssh-upgrade-note'
categories:
  - Linux 維運
tags:
  - OpenSSH
  - Security
  - CentOS
  - Rocky Linux
draft: false
---

這是一篇模擬測試文章。

在機房維運的過程中，確保伺服器的 SSH 連線安全是非常重要的一環。本篇紀錄了將舊版 OpenSSH 進行升級的具體流程，並整理了升級過程可能導致金鑰與設定檔失效的踩坑經驗。