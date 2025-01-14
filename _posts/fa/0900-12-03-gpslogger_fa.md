---
layout: doc-rtl
title: نرم‌افزار آندروئید GPSLogger
permalink: /fa/mobile-mapping/gpslogger/
lang: fa
category: mobile-mapping
---

نرم‌افزار آندروئید GPSLogger
=====================


![GPSLogger] []

یک برنامه ساده، کم حجم و حداقلی برای ضبط مسیرهای GPS در پلتفرم Android است. رابط کاربری آسان که تنها با هدف ثبت و نگهداری GPS و آرام ماندن طراحی شده آنرا به برنامه ای با کارایی بسیار بالا برای ذخیره سازی باتری که می تواند مسیرهای GPS را در فرمتهای GPX ،KML ،NEMA یا فرمت فایل متنی ذخیره کند تبدیل کرده است. فایل های ثبت شده به طور خودکار می توانند به OpenStreetMap، سرور OpenGTS، دراپ باکس، سرور FTP و سرور HTTP آپلود شوند یا به آدرس ایمیل فرستاده شوند.  

<https://f-droid.org/en/packages/com.mendhak.gpslogger/>  

استفاده از GPSLogger برای آندروید رایگان است و فعالانه به صورت یک پروژه منبع باز نگهداری می شود. از کمک های مالی برای بهبود بیشتر برنامه استقبال می شود. اگر میخواهید مشارکت کنید (به عنوان مثال ارائه ترجمه به زبانهای دیگر، گزارش خطا یا ارسال درخواست ویژگی جدید)، از (https://github.com/mendhak/gpslogger)[مخزن] بازدید کنید.  

> OpenGTS اشاره به پروژه [Open GPS Tracking System] (http://opengts.sourceforge.net/) دارد  


ویژگیها
--------  

* مشخص کردن ثبت بر اساس فاصله زمانی یا مکانی  
* مشخص کردن تنظیمات صرفه جویی در باتری  
* فیلتر دقت GPS برای عدم ثبت نقطه های غیر قابل اعتماد  
* انتخاب وای فای، دکل مخابراتی تلفن همراه و/یا ماهواره های GPS به عنوان منبع اطلاعات مکان  
* ثبت به فرمتهای GPX، KML، CSV، TXT یا NMEA با پشتیبانی ZIP  
* واحد نمایش امپریال یا متریک  
* شروع خودکار پس از روشن شدن دستگاه  
* اجرا در پس زمینه  
* به خوبی با سایر برنامه های GPS در حال اجرا کار می کند  
* ارسال خودکار به ایمیل/FTP/DropBox/Google Docs/OpenStreetMap/OpenGTS در فواصل تعریف شده توسط کاربر  
* پیش تنظیم آسان فایلهای پیکربندی متنی برای توزیع به بسیاری از کاربران  


رابط کاربری
--------------------------

[Canvass1][]!

دکمه **Menu** گزینه های بیشتری را برای پیکربندی برنامه فراهم می کند.  
منوی کشویی **Views** به شما اجازه می دهد انتخاب کنید که چگونه اطلاعات روی صفحه نمایش داده شود.  
دکمه **Help** اطلاعات اضافی در مورد چگونگی استفاده از برنامه را فراهم می کند.  
دکمه **Annotate** به شما اجازه می دهد یک توضیح را به یک نقطه اضافه کنید.  
دکمه **ثبت یک نقطه** (Log one point) به شما اجازه می دهد تا به صورت دستی یک نقطه راه را وارد کنید.  
**آپلود** اجازه می دهد تا گزینه های مختلفی را برای آپلود فایل ثبتی انتخاب کنید. این موارد شامل گزینه ای برای ارسال خودکار به هر یک از موارد زیر است:  

- OpenStreetMap  
- گوگل درایو،  
- دراپ باکس،  
- یک سرور FTP  
- یک سرور OpenGTS یا  
- ارسال به آدرس ایمیل  

دکمه **اشتراک** به شما اجازه می دهد یک یا چند فایل ثبت شده را انتخاب کرده و با افراد دیگر از طریق بلوتوث یا پیامک به اشتراک بگذارید. بسته به برنامه های نصب شده بر روی دستگاه تان ممکن است گزینه های مختلفی برای شما در دسترس باشد.  


![Canvass2][]

دکمه **Start Logging** به رنگ آبی است. هنگامی که این دکمه را برای شروع ضبط بزنید، سبز رنگ میشود.  
**مختصات** آخرین نقطه GPS ثبت شده را نشان می دهد و وقتی یک مختصات جدید در دسترس قرار می گیرد، تازه سازی می شود.  
آیکن **ماهواره ها** تعدادماهواره های متصل شده را نشان می دهد.  
**ارتفاع** اطلاعات ارتفاع را نشان می دهد.  
**مدت** زمان کل زمان سپری شده از زمان فشار دادن دکمه شروع را نمایش میدهد.  
**مسافت** مسافت کل ضبط شده را نشان می دهد.  
**نوع فایل** نشان می دهد چه نوع ثبتی ایجاد شده و **مسیر فایل**می گوید که محل فایل روی دستگاه یا کارت حافظه است.  
نشانگر **وضعیت** در هنگام ضبط سبز رنگ است، زمانی که دستگاه در حال تلاش برای اتصال است یک چرخ دنده نشان داده میشود.  
**دقت** دقت داده های ضبط شده را نشان می دهد که در گیرنده های مختلف، موقعیت یا تعداد ماهواره های موجود، شرایط آب و هوایی یا موانع دید افق متفاوت است.  
**امتداد** جهت حرکت تان را به شما می گوید.  
**سرعت** اطلاعات تقریبی سرعت تان را نشان می دهد.  
**نقاط ثبت شده** تعداد کل نقطه های ثبت شده از زمان فشردن دکمه شروع را نشان می دهد.  


منوها
--------------------------

[Menus][]!

**گزینه های عمومی** جایی است که تنظیمات *شروع در هنگام روشن شدن*، *واحد اندازه گیری* (متریک یا امپریال)*، *فایل اشکالزدایی* و *اطلاعات نسخه* را پیدا میکنید.  

[Menus1][]!

**جزئیات ثبت ها** جایی است که تنظیمات *فرمت فایل* (همزمان از چند فرمت مختلف به طور همزمان پشتیبانی میشود)، *پوشه* مسیر ذخیره ثبت ها، قواعد *ایجاد فایل جدید* و *نام فایل سفارشی* را پیدا میکنید.  

[Menus2][]!

[Menus3][]!

قسمت **عملکرد** جایی است که تنظیمات *ارائه دهندگان مکان*، *زمان بندی*، *فیلتر* و * شنوندگان * یافت می شود. گزینه ارائه دهنده مکان به شما اجازه می دهد که منابع داده های مکان را تنظیم کنید: **GPS** - ماهواره های ناوبری؛ **شبکه** - دکلهای مخابراتی تلفن همراه؛ **Passive** - اجازه می دهد GPSLogger مختصات موقعیت مکانی را از برنامه دیگر "وام" بگیرد، تا در اثر عدم درخواست خود برنامه در مصرف باتری صرفه جویی شود.  

[Menus4][]!

[Menus5][]!

**ارسال خودکار، ایمیل و آپلود** جایی است که تنظیمات گزینه های آپلود مختلف مانند OpenStreetMap، گوگل درابو، FTP، دراپ باکس یافت می شود.  

[Menus6][]!

آپلود مسیرهای ردیابی شده GPS راه دیگری برای کمک به مشارکت داده در پروژه OpenStreetMap است. مسیر ردیابی شده یک ضبط موقعیت مکانی شما در فواصل زمانی یا مسافتی مختلف است که مختصات جغرافیایی (طول و عرض جغرافیایی و ارتفاع) ثبت می شود. از این مسیرها به عنوان لایه پس زمینه در هنگام ویرایش نقشه میتوان استفاده نمود و برای افزودن ویژگی های نقشه مانند تصاویر هوایی مفید هستند.  

#### گزینه های OpenStreetMap

[osm0][]!

تنظیمات **اجازه ارسال خودکار** تعیین می کند که آیا فایل های ثبتی به صورت خودکار آپلود شوند.  
**مجاز کردن برنامه** برای اعطای مجوز برنامه جهت آپلود مسیرهای ردیابی شده GPS به OSM، با استفاده از حساب OSM تان است.  
گزینه های **قابلیت مشاهده**، **توضیحات**، **برچسب ها** تا زمانی که شما برنامه را مجاز به آپلود مسیرهای GPS کنید، غیر فعال هستند. این تنظیمات برای مسیهای ردیابی شده GPS که به پایگاه داده OpenStreetMap آپلود می شوند استفاده می شوند.  
هنگام کلیک بر روی *مجاز کردن برنامه*، به مرورگر اینترنتی و وبسایت OpenStreetMap هدایت می شوید. اگر وارد سیستم نشده اید، از شما نام کاربری و رمزتان خواسته می شود.  

[osm2][]!

پس از ورود به سیستم، صفحه ای مانند زیر را که تأیید درخواست برنامه میکند و به طور اختصاصی اجازه *بارگذاری مسیر ردیابی شده GPS* را میخواهد مشاهده خواهید کرد. بر روی دکمه *ذخیره تغییرات* کلیک کنید تا برنامه را تأیید کنید.  

[osm3][]!

پس از بازگشت به برنامه GPSLogger، صفحه نمایش کمی متفاوت خواهد بود و با گزینه های بیشتری در دسترس است.

[osm1][]!

با کلیک بر روی گزینه **پاک کردن تأیید مجوز**، اجازه آپلود مسیر به سرور OSM را حذف خواهید کرد.  

گزینه های گوناگونی برای نمایش GPS وجود دارد. مسیرهای *خصوصی* (Private) به عنوان ناشناس، با نقاط غیرمرتب به اشتراک گذاشته می شوند. مسیرهای *عمومی* در لیست مسیرها  به صورت ناشناس، با نقاط غیرمرتب نشان داده میشوند. مسیرهای *قابل ردیابی* به عنوان ناشناس با نقاط مرتب دارای برچسب زمانی به اشتراک گذاشته می شوند. مسیرهای *قابل شناسایی* در لیست مسیرها نمایش داده میشوند در حابیکه نام کاربری شما همراه با برچسب های زمانی برای نقاز مرتب شده امتیازات سفارش شده باشد.  

توصیه می شود که وضعیت دیداری مسیرهای GPSتان را هنگام آپلود به صورت *قابل شناسایی* قرار دهید. داده ها و ابَرداده ها آن را برای نقشه کشهای دیگر مفیدتر می کند. اگر نگرانی در ارتباط با حریم شخصی و امنیت شخصی دارید، تنظیمات مناسب تری را انتخاب کنید یا اصلاً مسیرها را آپلود نکنید.  

مقداری *توضیحات* متنی به دیگران کمک می کند که بفهمند چگونه مسیر ردیابی شده ثبت شده است. مسیری که با پای پیاده ثبت می شود، شبیه مسیر ثبت شده توسط هواپیمای بدون سرنشین نیست.  

*تگ* کلمه کلیدی کوتاهی است که برای ارتباط دادن مسیر ردیابی شده با پروژه، مکان یا رویداد خاصی استفاده میشود.  


جمع آوری داده
---------------

### جمع آوری و آپلود خودکار مسیرهای GPS

در صورت پیکربندی صحیح، برنامه در پس زمینه اجرا شده و به صورت خودکار مسیرها را ضبط کرده و آنها را یک بار در روز به هر سرویس پیکربندی شده آپلود میکند. اینکار اجازه می دهد تا مجموعه ای از مسیرها به صورت خودکاردر هنگام  رانندگی روزانه ایجاد و به ایجاد مجموعه ای از اطلاعات جاده ای و زمان سفر برای نقشه کشی یا تجزیه و تحلیل بعدی کمک میکند. دارنده گوشی یا دستگاه اندرویدی به محض پیکربندی متوجه تاثیر بسیار کم برنامه روی مصرف باتری شده و نیاز به انجام هیچ کار دستی دیگری نیست. پیدا کردن تعادل مناسب استفاده باتری و وضوح مسیر GPS، با کمی تجربه به دست می آید.  

یک نمونه پیکربندی برای جمع آوری و آپلود خودکار روزانه به OpenStreetMap نیاز به وارد کردن این تنظیمات است:  

#### گزینه های عمومی  

* * شروع هنگام روشن شدن دستگاه** - روشن  

#### ثبت جزئیات  

* ** ثبت به GPX ** - روشن  
* **ایجاد فایل جدید** - یک بار در روز  

#### کارایی  

* **زمان قبل از ثبت** - 5  
* **روشن نگه داشتن GPS بین فیکسها** - روشن (خاموش کردن این مورد منجر به ایجاد "جهش" در مسیرهای GPS زمانی که دستگاه هر بار به ماهواره های GPS نیاز دارد.)  
* **عدم ثبت در صورت توقف** - روشن  

#### ارسال خودکار، ایمیل و آپلود  

* **اجازه ارسال خودکار** - روشن  
* **هر چند وقت یکبار** - برای یک بار در روز 1440 دقیقه را وارد کنید. این تنظیم در صورتی که در هنگام اجرای آن دسترسی به داده یا وای فای ندارید کمی قلق دارد. یا باید از زمان روشن شدن دستگاه شروع به شمارش کند و یا از زمان زدن دکمه "شروع ثبت"، بنابراین اگر در صبح شروع کنید، صبح روز بعد در همان زمان شروع به آپلود میکند.  
* **OpenStreetMap** - اجازه ارسال خودکار و تنظیمات دیگری را که می خواهید پیکربندی کنید میدهد، در صورتی که نگرانی های امنیتی مربوط به مسیرهای GPS دارید، به تنظیمات قابلیت دیده شدن توجه کنید.  


### ضبط دستی مسیرها

برای شروع ثبت ها (در نمای ساده)، به سادگی روی دکمه آبی کلیک کنید. یک چرخ دنده در نزدیکی گوشه سمت راست بالای صفحه ظاهر می شود تا تلاش برای دریافت سیگنالهای ماهواره ای را نشان دهد. یک دایره سبز در بالا سمت راست نشان داده می شود تا نشان دهد ثبت مسیر در حال انجام است.  

برای متوقف کردن ضبط داده ها در هر زمان، فقط دکمه سبز *توقف ثبت* را بزنید.  

#### یادداشت نویسی  

جهت اضافه کردن یادداشت یا توضیحات برای هر مسیر ثبت شده، روی آیکن *یادداشت* (مداد) کلیک کنید. این گزینه به شما اجازه می دهد متنی را جهت توصیف و یا یادداشتی از جزئیات مرتبط با هر نقطه را بنویسید.  

##### فراخوانی یادداشت نویسی از نوار اعلان  

همچنین این امکان وجود دارد که یاداشت نویسی را از نوار اعلان آندروئید فرا بخوانید. برنامه را از لیست اعلانها انتخاب کنید و روی دکمه *یادداشت* کلیک کنید.  

[annotate0][]!

اینکار یک کادر محاوره ای ورودی را نمایش می دهد که در آن می توانید جزئیات متن یادداشت را وارد کنید.

[annotate1][]!

#### فواصل ثبت

فواصل ثبت بر اساس زمان یا مسافت در منوی **کارایی** تعیین می شود.  

##### زمان

**زمان قبل از ثبت** به طور پیش فرض روی 60 ثانیه تنظیم شده است. هنگام پیاده روی آنرا می توانید به پنج یا ده ثانیه تغییر دهید. زمانی که در حال رانندگی با خودرو هستید، آنرا روی 1 ثانیه تنظیم کنید تا بتوانید مسیر بسیار دقیقی ایجاد کنید.  

##### مسافت

فیلتر **مسافت** به طور پیش فرض صفر است. می توانید آن را روی عدد دیگری تنظیم کنید، اگر می خواهید مختصات را برای هر X واحد طی شده از آخرین نقطه ضبط شده ثبت کنید.  


آپلود مسیرهای ردیابی شده
------------------

#### به OpenStreetMap

دکمه *آپلود* را بزنید و گزینه OpenStreetMap را انتخاب کنید. یک پنجره محاوره ای که در آن فایل ها برای انتخاب در دسترس قرار میگیرند نمایش داده می شود. هرکدام را که میخواهید آپلود کنید انتخاب کرده و دکمه Ok را فشار دهید.  

[upload0][]!

#### به گزینه های دیگر

گزینه های آپلود دیگری نیز وجود دارد که می توانید کشف کنید، اما خارج از حیطه این راهنما میباشند. برای اطلاعات بیشتر در مورد GPSLogger به وبسایت پروژه اندروید مراجعه کنید.  


به اشتراک گذاری مسیرهای ردیابی شده 
---------------

شما همچنین می توانید مسیرهای ضبط شده یا مکان فعلی خود را با افراد دیگر به اشتراک بگذارید. گزینه های اشتراک ممکن است از دستگاهی به دستگاه دیگر یا براساس برنامه های نصب شده بر روی دستگاه متفاوت باشند. مثال زیر نمونه ای از  صفحه به اشتراک گذاری می باشد:  

[share0][]!


خروجی مسیر ردیابی شده به یک ویرایشگر OpenStreetMap
--------------------------------------------

هنگامی که ضبط  مسیر انجام شد، میتوانید آن را به JOSM (یا یکی دیگر از ویرایشگرهای OpenStreetMap مانند iD) وارد کنید.  

دستگاه آندروئید خود را به رایانه متصل کنید (با استفاده از کابل، بلوتوث یا ارتباط اینترنت امکانپذیر است) و مسیرهای GPX (و شاید فایل های چندرسانه ای) را که گرفته اید منتقل کنید. در محل ذخیره دستگاه، مسیرهای GPX را در پوشه Android/data/com.mendhak.gpslogger/files/ جستجو کنید.  

استفاده از مسیرهای GPX با ویرایشگر JOSM و iD به آسانی کشیدن فایل و رها کردن آنها درون محیط نرم افزار (و یا برای iD زبانه مرورگر) است.  

برای جزئیات بیشتر برای کاربران iD، بخش [پیکربندی لایه پس زمینه(http://learnosm.org/en/beginner/id-editor/#configuring-the-background-layer) را ببینید.  

اگر از ویرایشگر JOSM استفاده می شود، می توانید دستورالعمل نحوه استفاده از مسیر GPX و فایل های چندرسانه ای در JOSM را در بخش [بازکردن در JOSM(http://learnosm.org/fa/mobile-mapping/using-gps/#open-in-josm) ببینید.  

برای دیگر ویرایشگرهای OpenStreetMap لطفاً به مستندات خود نرم افزار مراجعه کنید.  


گزینه های نمایش
-----------------

برنامه به ۳ روش مختلف نمایش داده میشود، هر کدام که برایتان مناسبتر است بکار ببرید:

#### نمای ساده

[view0][]!

#### نمای با جزئیات

[view1][]!

#### نمای بزرگ

[view2][]!


خلاصه
-------

بسیار عالی! نرم‌افزار بسیار سبک و کم مصرف به شما معرفی شد که می‌توانید در دستگاه آندروئیدتان داشته باشید تا مسیرها را ضبط کرده، به OSM آپلود کنید و یا در ویرایشگر OpenStreetMap دلخواه تان از آن استفاده کنید.  

GPSLogger آندروئید ابزار دیگری برای جمع‌آوری داده‌های میدانی بدون داشتن گیرنده GPS است. جمع‌آوری داده‌های میدانی معمول حتی بدون داشتن اتصال اینترنت فعال نیز امکانپذیر است.  

قبل از کار با داده‌های حقیقی، مفداری وقت گذاشته و با این نرم‌افزار تمرین کرده و آشنا شوید.  

این بخش ایده استفاده از GPSLogger برای آندروئید جهت جمع‌آوری GPS مسیرها، آپلود به OpenStreetMap و انتقال این موارد ثبت شده به رایانه شخصی را معرفی کرد.  


مستندات رسمی برنامه GPSLogger آندروئید
--------------------------------------------

این پروژه دارای یک صفحه [FAQ](http://code.mendhak.com/gpslogger/#faq) می‌باشد که حاوی سوالات رایج پرسیده شده درباره آن می‌باشد.

[GPSLogger]: /images/mobile-mapping/gpslogger_000.en.png
[Canvass1]: /images/mobile-mapping/gpslogger_001.en.png
[Canvass2]: /images/mobile-mapping/gpslogger_002.en.png
[Menus]: /images/mobile-mapping/gpslogger_003.en.png
[Menus1]: /images/mobile-mapping/gpslogger_003a.en.png
[Menus2]: /images/mobile-mapping/gpslogger_003b.en.png
[Menus3]: /images/mobile-mapping/gpslogger_003c.en.png
[Menus4]: /images/mobile-mapping/gpslogger_003d.en.png
[Menus5]: /images/mobile-mapping/gpslogger_003e.en.png
[Menus6]: /images/mobile-mapping/gpslogger_003f.en.png
[osm0]: /images/mobile-mapping/gpslogger_004.en.png
[osm1]: /images/mobile-mapping/gpslogger_004a.en.png
[osm2]: /images/mobile-mapping/gpslogger_004b.en.png
[osm3]: /images/mobile-mapping/gpslogger_004c.en.png
[upload0]: /images/mobile-mapping/gpslogger_005.en.png
[share0]: /images/mobile-mapping/gpslogger_006.en.png
[view0]: /images/mobile-mapping/gpslogger_007.en.png
[view1]: /images/mobile-mapping/gpslogger_007a.en.png
[view2]: /images/mobile-mapping/gpslogger_007b.en.png
[annotate0]: /images/mobile-mapping/gpslogger_008.en.png
[annotate1]: /images/mobile-mapping/gpslogger_008a.en.png