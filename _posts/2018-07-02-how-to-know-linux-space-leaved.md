---
layout: post
title: "용량확인하는 방법"
date: 2018-07-02 12:28:08
image: 'https://github.com/jooyounghun/jooyounghun.github.io/blob/master/imagesource/linuximage.png'
description:
category: ''
tags:
twitter_text:
introduction:
---

df : show the rest of disk

df -k : by kilobyte
df -m : by megabyte
df -h : show easily
df. : show rest of partition including current directory

du : show current dir & sub dir space leaved.
du -a : print file unit on  directory using ratio
du -s : confirm total using ratio
du -h : show easily
du -sh * : show rest of space based on 1 step sub directory
