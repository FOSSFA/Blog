---
title: "آموزش نصب pkgsrc روی مک"
description: "آموزش نصب pkgsrc روی مک OSX"
image: "images/post/howtoinstallpkgsrcinmacosx.jpg"
date: 2021-03-14T16:43:08+04:30
author: "Gnkalk"
tags: ["NetBSD", "Pkgsrc"]
categories: ["BSD"]
draft: false
---

عده ای معتقد اند که مک نسخه اصلاح شده BSD هست که خب ما کاری بهش نداریم.. اما شما میتوانید پکیج منیجر نت BSD رو ، روی مک نصب کنید تا از شر پکیج منیجر هایی مثل « Homebrew » خلاص شید ;)

#### مراحل نصب

ابتدا pkgsrc را دانلود کنید :
‍
```‍‍‍
wget ftp://ftp.netbsd.org/pub/pkgsrc/current/pkgsrc.tar.xz
```

بعد توی usr/ استخراجش کنید :

```
tar -C /usr --xz -xf pkgsrc.tar.xz
```

تنظیم بوت استرپ :

```
cd /usr/pkgsrc/bootstrap
bootstrap --compiler=clang --abi=۶۴ --pkgdbdir=/usr/pkg/pkgdb --varbase /usr/pkg/var/.
```

خب حالا پچ pkgsrc رو اد میزنیم : 

```
export PATH=$PATH:~/pkg/bin:~/pkg/sbin
```

الان pkgsrc روی مک شما نصب شده و میتونید حالشو ببرید =)

استفاده از pkgsrc تو مک فرق خاصی با Homebrew نداره و راحته ، برای اطلاعات بیشتر در مورد این پروژه به [این صفحه](https://github.com/jdwhite/pkgsrc-darwin/tree/master) مراجعه کنید..