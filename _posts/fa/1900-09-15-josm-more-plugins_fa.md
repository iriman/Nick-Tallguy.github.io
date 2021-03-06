---
layout: doc-rtl
title: ابزارهای ساختمان JOSM و افزونه Utilsplugin2
permalink: /fa/josm/josm-more-plugins/
lang: fa
category: josm
---

ابزارهای ساختمان JOSM و افزونه Utilsplugin2
============

> تاریخ بازبینی ۱۳۹۵/۰۶/۲۲  

پلاگینهای **buildings_tools** و **utilsplugin2** قابلیتهای بسیار فراوانی به JOSM اضافه می‌کنند.در این بخش نگاه نزدیکتری به قابلیتهای اینها می‌اندازیم.  

پلاگین ابزار ساختمان
--------------------------

اگر قبلاً نصب نکرده‌اید، این پلاگین را به همراه دستورالعمل آن از [افزونه‌های JOSM](/fa/josm/josm-plugins) دانلود کنید.  

![Buildings tools plugin][]

پلاگین ابزار ساختمان برای دیجیتالی کردن ساختمانها بسیار مفید است. این پلاگین به شما اجازه ردیابی از یک طرف ساختمان مستطیل شکل و گسترش شکل آن را به راحتی  می‌دهد. اگر شما ساختمانهای زیادی را دیجیتالی می‌کنید، این افزونه به کاهش تعدادکلیک و به دنبال آن صرفه‌جویی در زمان را میدهد.  

به محض نصب پلاگین، دکمه جدیدی در سمت چپ JOSM می‌بینید که شبیه به این است: ![Buildings tools button][]{: height="29px"}

JOSM را راه‌اندازی کنید و ناحیه‌ای را که میخواهید ساختمانهای آنرا بکشید دانلود کنید.  

* ابزار ساختمان را انتخاب کنید و دوبار کلیک کنید تا یک خط روی نقشه بکشید.  

![Draw edge][]

* سپس ماوس را گسترش دهید و دوباره کلیک کنید تا یک مستطیل کشیده شود.  

![Extend building][]

* با این کار نه تنها مستطیل را تنها با سه کلیک ایجاد می‌کنید، بلکه به طور خودکار برچسب **building=yes** نیز به شکل اعمال می‌شود.  

### ساختمانهای پیچیده

همچنین می‌توانید ساختمانهایی که شکلی پیچیده دارند را ابتدا با کشیدن چند مستطیل که با هم همپوشانی دارند و سپس ادغام آنها با هم رسم کنید.  

* دو ساختمان که با هم همپوشانی داشته و شکل L مانند را می‌سازند بکشید.  
* هردو ساختمان را با انتخاب کنید (کلید SHIFT را نگه داشته و بیش از یک شی انتخاب کنید).  
* به Tools->Join overlapping Areas بروید و یا SHIFT+J را از صفحه کلید بزنید.  

![Merge buildings][]

### ویرایش تنظیمات

علاوه بر این، می‌توانید تنظیمات پیش‌فرض افزونه را تغییر دهید.  

* به Data->Set buildings size بروید. ![Set buildings size][]{: height="39px"}  

* چنانچه ساختمانهای زیادی با شکل و اندازه یکسان را ایجاد می‌کنید، می‌توانید طول و عرض ساختمانها را بطور پیش‌فرض تعیین کنید، مثلاً ۶ * ۱۰ متر (واحد به متر است).  

![Set buildings size dialog][]

* با تعیین کردن اندازه ساختمان، برای رسم آن تنها به دو کلیک نیاز دارید.  

در نهایت، اگر می‌خواهید یک سری تگ پیش‌فرض اضافه کنید که به طور خودکار برای هر ساختمان اعمال شود، می‌توانید روی دکمه 'پیشرفته' (Advanced) کلیک کنید. به عنوان مثال، اگر همه ساختمانهای که ترسیم می‌کنید در یک خیابان قرار دارند، شاید یک برچسب اضافه کنید که خیابان را مشخص کند و به صورت خودکار به همه ساختمانها اعمال شود.  

![Buildings advanced][]


Utilsplugin2
-------------

اگر قبلاً نصب نکرده‌اید، این پلاگین را به همراه دستورالعمل آن از [افزونه‌های JOSM](/fa/josm/josm-plugins) دانلود کنید.  

![Utilsplugin2 plugin][]

پس از نصب افزونه و راه‌اندازی مجدد JOSM، در بالا یک منوی جدید به نام «ابزارهای بیشتر» (More Tools) خواهید داشت.  

![More tools menu][]

یک لایه جدید ایجاد کنید و برخی از ابزارهای جدید را آزمایش کنید. در اینجا ما برخی از مفیدترین ابزارهای جدید را شرح میدهیم:  

1. **اضافه کردن گره در تقاطع:** این ابزار برای اضافه کردن گره‌های فراموش شده در تقاطع راه‌های انتخاب شده بسیار مفید است. جاده‌ها همیشه باید در جایی که هم را قطع میکنند یک گره مشترک داشته باشند.  

    ![Nodes interesection][]

2. **کپی کردن برچسب‌ها از انتخاب قبلی:** این عملکرد باعث می‌شود که تگ‌ها را راحت‌تر کپی کنید. اگر می‌خواهید اشیاء زیادی را با تگ‌های مشابه ایجاد کنید، ابتدا اشیا را رسم کنید. سپس برچسب‌ها را به یک شی اضافه کنید. روی شی دیگری کلیک کنید و Shift+R را برای کپی کردن برچسب‌ها از شی قبلی بزنید. می‌توانید این کار را برای تمام اشیائی که می‌خواهید برچسب‌گذاری کنید انجام دهید. به یاد داشته باشید که برچسب‌ها از شی انتخاب شده قبلی کپی می‌شوند، بنابراین اگر روی یک شیء بدون برچسب کلیک کنید و سپس روی یک شیء بدون برچسب دیگر کلیک کنید، نمی‌توانید هیچ تگی را کپی کنید.  

    ![Copy tags][]

3. ** اضافه کردن تگ منبع:** این ابزار افزودن تگ منبع را ساده می‌کند. این عملکرد منبع نقشه‌ای را که آخرین بار اختصاص داده شده به خاطر سپرده و آن را به اشیاء اضافه می‌کند. شما می‌توانید منبع را تنها با یک کلیک وارد کنید.  

4. **جایگزینی هندسه:** (Replace Geometry) این ابزار اگر می‌خواهید یک شیء بدشکل را دوباره بکشید، اما می‌خواهید تاریخ، ویژگی‌ها و شماره شناسه آن شیء را نگه دارید فوق‌العاده است. به عنوان مثال، در یک ساختمان پیچیده که کامل رسم نشده به جای اینکه یکی یکی هر نقطه از ساختمان را به سختی جابجا کنید، می‌توانید بطور کامل دوباره از اول شی را ترسیم کنید، اشیاء قدیمی و جدید را انتخاب کنید و ¨جایگزینی هندسه¨ را برای انتقال همه اطلاعات قبلی بزنید.  

    ![Replace geometry][]


### ابزارهای انتخاب بیشتر

**Utilsplugin2** ابزارهای بیشتری را در منوی "انتخاب" (Selection) ارائه می‌کند. سعی کنید با آنها کار کنید.  

![Selection menu][]

یکی از ابزارهای انتخاب مورد علاقه ما **Unselect Nodes:** این ابزار تمام گره‌ها را ار انتخاب پاک می‌کند. این عملکرد می‌تواند مفید باشد اگر شما کادری را برای انتخاب چندین شی میکشید اما شما نمی خواهید نقطه‌ها موجود در تمام خطوط و اشکال را انتخاب کنید.  

![Unselect nodes][]

موفق باشید!  


[Buildings tools plugin]: /images/josm/buildings_tools-plugin.png
[Buildings tools button]: /images/josm/buildings_tools-button.png
[Draw edge]: /images/josm/draw-edge.png
[Extend building]: /images/josm/extend-building.png
[Merge buildings]: /images/josm/merge-buildings.png
[Set buildings size]: /images/josm/set-buildings-size.png
[Set buildings size dialog]: /images/josm/set-buildings-size-dialog.png
[Buildings advanced]: /images/josm/buildings-advanced.png
[Utilsplugin2 plugin]: /images/josm/utilsplugin2-plugin.png
[More tools menu]: /images/josm/more-tools-menu.png
[Nodes interesection]: /images/josm/utilsplugin2-nodes-intersection.png
[Copy tags]: /images/josm/utilsplugin2-copy-tags.png
[Replace geometry]: /images/josm/utilsplugin2-replace-geometry.png
[Selection menu]: /images/josm/selection-menu.png
[Unselect nodes]: /images/josm/utilsplugin2-unselect-nodes.png

