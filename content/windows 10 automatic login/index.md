---
title: Windows 10 Automatic Login
slug: windows-10-automatic-login
description: null
author: null
date: '2021-12-23T15:50:00.975Z'
lastmod: '2021-12-23T15:50:00.975Z'
draft: false
tags: []
categories: []
type: post
comments: true
---

Run `netplwiz`, and uncheck 'Users must enter a user name and password', enter your login credentials, press 'OK', and reboot.

Of course, the checkbox most likely isn't present, and you need to open the Command Prompt as an administrator and run the following command:

`reg ADD "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\PasswordLess\Device" /v DevicePasswordLessBuildVersion /t REG_DWORD /d 0 /f`
