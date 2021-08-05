---
title: "شخصی سازی میزکار kde - شبیه سازی ویندوز 10 (قسمت2)"
description: "آموزش شخصی سازی میزکار kde به شکل ویندوز 10"
image: "images/post/KDECustomize2.png"
date: 2021-03-03T16:43:08+04:30
author: "Gnkalk"
tags: ["KDE", "customize", "kde-customize"]
categories: ["Linux", "BSD"]
draft: false
---

خیلی وقت بود دنبال آموزش شخصی سازی میزکار KDE بودم . ولی متاسفانه در سطح وب آموزشی (فارسی) پیدا نکردم پس خودم دست به کار شدم و کوبونتو رو دانلود و نصب کردم .سپس شروع به دستکاریش کردم تا محیط های مختلف رو در آن بسازم و اینجوری یادگرفتم چجوری KDE رو شخصی سازی کنم.
در این سری آموزش ها ساخت محیط هایی شبیه به مکینتاش ، ویندوز 10 و DDE رو داریم.

### مرحله اول

نصب ویجت های
- Win10 Indicator
- MenuX
- MenuZ
- Digital Clock WL
- Netspeed Widget

برای نصب ابتدا بر روی دسکتاپ راست کلیک کرده و گزینه add widgetsرا انتخاب کرده
در پنل باز شده بر بروی گزینه get new  widgetsکلیک کرده و گزینه download new plasma widgetsرا انتخاب کنید.
در صفحه باز شده سمت راست در کادر جست و جو نام ویجت ها را نوشته و سپس آن ها را نصب کنید.

### مرحله دوم

نصب ابزار مورد نیاز(پیشنهاد میشه ولی ضروری نیست)حالا ابزار latte Dockرا نصب کنید برای نصب این ابزار (داک)ترمینال را باز کرده و سپس دستور زیر را وارد کنید

```
[ubuntu@fossfa ~] sudo apt install latte-dock
[arch@fossfa ~] sudo pacman -S latte-dock
[suse@fossfa ~] sudo zypper install latte-dock
[fedora@fossfa ~] sudo yum install latte-dock
```

### مرحله سوم

#### روش اول

فایل .latte را دانلود کنید برای این کار به [این](https://store.kde.org/p/1377447/) صفحه بروید و آن را دانلود کنید

سپس اپلیکیشن latte را باز کنید.بعد بر روی داک راست کلیک کرده و گزینه Layouts و در منو باز شده گزینه Manage Layoutsویا آخرین گزینه را انتخاب کنید.
در صفحه باز شده بر روی گزینه Importکلیک کرده و سپس فایل های دانلود شده(  Windows 10یا چیزی شبیه به  Windows 10) را انتخاب کنید.
سپس آن پنجره را ببندید دوباره بر روی داک راست کلیک کرده و گزینه Layouts و منو باز شده گزینه  Windows 10(یا چیزی شبیه به  Windows 10)را انتخاب کنید.

![](/images/post/kdecustomize/windows.png)

خب کسانی که از این روش استفاده کردند کارشون تمومه حالا از دسکتاپتان لذت ببرید

فقط قبلش پنل اصلی kdeرو حذف کنن برای این کار برروی پنل راست کلیک کرده و گزینه edit را انتخاب کنید سپس گزینه removeرا انتخاب کنید . دیگه کار تمومه

خسته نباشید =)

کسانی که استفاده نکردند میتونن از روش دوم که پیشنهاد منه استفاده کنن

#### روش دوم

بر روی پنل پایینی راست کلیک کرده و گزینه edit(ویرایش)را انتخاب کنید.

سپس به صورت زیر تمام ویجت های پنل را حذف کنید.

![](/images/post/kdecustomize/removewighet.png)

**نکته** برای خارج شدن از حالت ادیت بر روی دکمه خروج همانند تصویر زیر کلیک کنید
![](/images/post/kdecustomize/exiteditmode.png)

سپس گزینه Add widget را انتخاب کنید حالا ویجت هارا به سمت پنل کشیده

![](/images/post/kdecustomize/addwighet.png)

خب دیگه آخرشه
از سمت راست به ترتیب این ویجت هارا در پنل قرار دهید
- Notifications
- Digital Clock WL
- System Tray
- Netspeed Widget
- icon-only Task Manager
- MenuZ
- MenuX

![](/images/post/kdecustomize/windows2.png)

برای شبیه تر شدن ، گلوبال تم ویندوز 10 را نصب و از آیکون های مک استفاده کنید.

گلوبال تم https://github.com/yeyushengfan258/We10XOS-kde

آیکون را از طریق تنظیمات نصب کنید.

![](/images/post/kdecustomize/installicon.png)

کار تمومه از دسکتاپتون لذت ببرید :)