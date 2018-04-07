save_as: reports/session-108/index.html
url: reports/session-108
title: گزارش جلسه‌ی ۱۰۸م
layout: page
author: tuxitop
date: 2012-07-11 00:19:00
meta: date by tuxitop on Wed, 07/11/2012 - 00:19
category: reports

جلسه ۱۰۸م گروه کاربران لینوکس در ساعت ۱۷ روز شنبه ۱۷ تیر ماه ۱۳۹۱، در محل شرکت
معیار گستر توس با حضور تعدادی از اعضای آن برگزار شد.


<!--more-->


موضوعاتی که در این جلسه به آن‌ها پرداخته شد عبارتند از:

## بررسی اخبار دنیای متن باز *آرش موسوی*
## معرفی مدیرپنجره‌ی آسام *علی موسوی*
[مشاهده در ویکی‌پدیا](http://fa.wikipedia.org/wiki/%D8%A2%D8%B3%D8%A7%D9%85_%28%D9%85%D8%AF%DB%8C%D8%B1_%D9%BE%D9%86%D8%AC%D8%B1%D9%87%29)
## «اصول طراحی وب، فونت‌ها» *بیژن ابراهیمی*

```

خلاصه ارائه آشنایی با تکنیک‌های طراحی وب، اندازه فونت‌ها
توسط بیژن ابراهیمی
۱۷ تیرماه ۹۱، گروه کاربران لینوکس مشهد


واحد‌های مقداردهی اندازه فونت
	۱. کلیدواژه ها ( XX-Small, X-Small, Small, Medium, Large, X-Large, XX-Large, Smaller, Larger )

		۱.۱ مزایا
			۱.۱.۱ نمایش یکسان در مرورگر‌های متفاوت
			به جز جائی که خط شکسته می‌شود و ارتفاع پاراگراف

			۱.۱.۲ آبشاری، (المان‌های فرزند تحت تاثیر مقادیر المان والد قرار می‌گیرند)
			مثال:
			‮‬‪p{ font-size:medium; }
			‮‬‪p em{ font-size:smaler; }
			۱.۱.۳ مناسب برای استفاده به عنوان روشی برای تغییر اندازه فونت 
			به کمک جاوا اسکریپت

		۱.۲ معایب
		۱.۲.۱ عدم کنترل کافی بر دقت اندازه فونت‌ها

	۲. پیکسل
		۲.۱ مزایا
			۲.۲ دقیق‌ترین روش برای اندازه‌دهی به فونت‌ها
			البته تغییراتی اندک در نمایش مرورگرهای مختلف وجود دارد
		۲.۲ معایب
			۲.۲.۱ عدم تاثیر آبشاری 
			البته قابل رفع با کمک از روش‌های ترکیبی. مثال:
‬‮‬‫‪			body{ font-size:16px; }
			‮‬‪p{ font-size:larger; } 
			اندازه فونت پاراگراف به ۲۰ پیکسل (۲۵ درصد) افزایش می‌یابد

			۲.۲.۲ عدم پشتیبانی مرورگر‌های اینترنت‌اکسپلورر از تغییر اندازه فونت (font enlarging)

‫	۳. emها
	یک em برابر با اندازه فونت پیش‌فرض المان می‌باشد. این مقدار به صورت پیش‌فرض در اکثر مرورگرها
	برابر ۱۶ پیکسل می‌باشد
		۳.۱ مزایا
			۳.۱.۱ آبشاری
‮‭				body{ font-size:20px }
‮				‪‭p{ font-size:1em }‮
‮				‬‫‪h1{ font-size:2em }
			در این مثال اندازه فونت پاراگراف برابر با ۲۰ پیکسل و اندازه فونت هدر برابر
			با ۴۰ پیکسل می‌باشد
			
			۳.۱.۲ پشتیبانی مرورگر اینترنت اکسپلورر (۶ و ۷) از تغییر اندازه فونت
			۳.۱.۳ قابلیت اندازه‌دهی نسبی با المان‌های دیگر (طولی)
			۳.۱.۴ قابل استفاده برای دیگر المان‌های موجود (نه‌تنها فونت‌ها)
			      مثال:
‮‬‪				.box{ height:10em; }
‮‬‪				.box p{ font-size:1em; }
				در این مثال اندازه فونت پاراگراف داخل جعبه همیشه یک‌دهم ارتفاع جعبه
				خواهد بود
			۳.۱.۵ ابزاری عالی برای طراحی‌وب
		۳.۲ معایب
			۳.۲.۱ پیچیدگی زیاد

	۴. درصد 
	نحوه کاربرد آن مشخص است. مثال:
	‮‬‪	body{ font-size:20px; }
‮‬‪		p{ font-size:50%; }
	در اینجا پاراگراف فونتی برابر با ۱۰ پیکسل خواهد داشت.

		۴.۱ مزایا
			۴.۱.۱ وجود رابطه نسبی با المان‌های والد
			۴.۱.۲ ابشاری
			۴.۱.۳ قابل استفاده در تکنیک‌های تغییر اندازه فونت

	۵. نقطه‌ها (Points)
	    کاربرد این واحد تنها در نسخه‌های چاپی (پرینت) صفحات می‌باشد
	    هر ۷۲ نقطه برابر با یک اینچ در دنیای واقعی می‌باشد (یک اینچ در مانیتور نسبی و وابسته 
	    به رزولوشن مانیتور می‌باشد، پس اشتباه گرفته نشود)

		۵.۱ مزایا
			۵.۱.۱ دقت بسیار بالا بر روی نسخه‌های چاپی (معادل دقت پیکسل در خروجی مانیتور)
		
		۵.۲ معایب
			۵.۲.۱ غیرقابل استفاده در خروجی‌هایی بجز خروجی چاپی
```

## نکته‌ی خط فرمان *بیژن ابراهیمی*
## بررسی فعالیت هفته‌ی نهم پروژه‌ی ویکی‌پدیای فارسی *حامد رمضانیان*

بررسی فعالیت هفته‌ی نهم پروژه‌ی ویکی‌پدیای فارسی با موضوعات [گواهینامه
مؤسسه تخصصی لینوکس](http://fa.wikipedia.org/wiki/%DA%AF%D9%88%D8%A7%D9%87%DB%8C%D9%86%D8%A7%D9%85%D9%87_%D9%85%D9%88%D8%B3%D8%B3%D9%87_%D8%AA%D8%AE%D8%B5%D8%B5%DB%8C_%D9%84%DB%8C%D9%86%D9%88%DA%A9%D8%B3)، [زول](http://fa.wikipedia.org/w/index.php?title=%D8%B2%D9%88%D9%84_%28%D8%B2%D8%A8%D8%A7%D9%86_%D8%A8%D8%B1%D9%86%D8%A7%D9%85%D9%87%E2%80%8C%D9%86%D9%88%DB%8C%D8%B3%DB%8C%29&action=edit
&redlink=1)، [کامپیز](http://fa.wikipedia.org/w/index.php?title=%DA%A9%D8%A7%D9%85%D9%BE%DB%8C%D8%B2&action=edit&redlink=1)
## بحث آزاد

