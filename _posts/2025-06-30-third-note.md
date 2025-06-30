---
layout: default
title: "|--EcHooo"
date: 2025-06-29
---

# 📘 Simple Privacy Tool: `goog`

A small shell script to perform **Google searches** using the **Lynx text browser**, helping to **reduce tracking** and improve **terminal-based privacy**.

## 🔧 Requirements

- `lynx` (text-based web browser)
- Unix-like environment (Linux, macOS, BSD ...)

## 🧪 Usage

```bash
./goog [search terms]
```
goog -- Performs a Google search using the lynx text browser in order to avoid tracking
#!/bin/sh
#Requires the lynx browser
#usage: ./goog [search terms]
lynx -image_links -accept_all_cookies -cookie_file=/dev/null "www.google.com/search?q=$*"
---
