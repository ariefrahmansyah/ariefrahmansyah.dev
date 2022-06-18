---
title: "Linux Tips"
date: 2022-06-18T09:00:00+07:00
description: 🐧
tags:
  - linux
  - tips
---

## Disable Keychron's Fn Keys

```
# To disable it
echo 0 | sudo tee /sys/module/hid_apple/parameters/fnmode

# To enable it
echo 1 | sudo tee /sys/module/hid_apple/parameters/fnmode
```

Source: https://www.reddit.com/r/MechanicalKeyboards/comments/d5io49/keychron_k2_f_keys_dont_work_w_linux_help/f0m2u14
