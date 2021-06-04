<div dir="rtl">
برخی از نتایج و کدهای مرتبط با مقاله‌ی ارسالی زیر:

## انتقال سبک با شبکه‌ی مولد رقابتی برای افزایش داده‌های آموزشی شبکه‌های پیچشی در شناسایی شعله‌ی آتش

چکیده:<br>
وجود داده‌های آموزشی کافی، امری اساسی در همه‌ی سیستم‌های یادگیری بانظارت و منجمله در حوزه‌ی یادگیری عمیق و بینایی ماشین است. یکی از روش‌های مورد استفاده برای افزایش تعداد نمونه‌های آموزشی در یادگیری عمیق، شیوه‌ی «داده افزایی» هست. این شیوه، متضمن  تبدیل‌های دوران، انتقال و برش بر روی تصاویر آموزشی است که منجر به افزایش تعداد نمونه‌های آموزشیِ نسبتاً متفاوت از داده‌های اولیه می‌گردد. در این نوشتار از الگوریتم «انتقال سَبْک» مبتنی بر شبکه‌های مولد رقابتی برای افزایش تعداد نمونه‌های آموزشی استفاده شده است. هدف در انتقال سبک، اِعمال ظاهر یا سبک بصری یک تصویر بر روی تصویری دیگر است که جنبه‌ی هنری آن  بیشتر دیده شده است. در این نوشتار از این شیوه‌ برای تولید نمونه‌های جدید آموزشی استفاده شده و به عنوان یک کاربرد، روش پیشنهادی بر روی مسأله‌ی شناسایی شعله‌ی آتش اعمال شده است. با این فرض که تصاویر آموزشی ثبت شده در طی شب، کمتر از نمونه‌های اخذ شده در روز هستند،  با اعمال یک روش انتقال سبک، تصاویر روز به تصاویر شب تبدیل شده و به عنوان داده‌ی آموزشی به مجموعه دادگان اضافه می‌شوند. نتایج آزمایشات انجام شده کارایی شیوه‌ی پیشنهادی را نشان داده است. به صورت میانگین، نرخ درست شناسایی ۴ درصد افزایش یافته است. مدل‌های یادگیری عمیق آموزش داده شده و مورد استفاده در آزمایشات، برای تست تصاویر جدید از گیت‌هاب نگارنده قابل دسترس هستند.

### اعمال انتقال سبک یک تصویر بر روی تصویر دیگر:
شکل ۲ مقاله:
<table  align="center" border="1">
<tr><td> <img src="images/fox.jpg" width="500"> </td><td> سطر اول: تصویر روباه، به عنوان تصویر محتوا. در سطرهای دوم تا سوم، ستون (الف) نتیجه اعمال 
<a href="https://github.com/sunshineatnoon/LinearStyleTransfer">
این شیوه‌ی انتقال سبک عصبی
</a>
 با تصویر روباه سطر اول به عنوان تصویر محتوا و تصویر سطر مربوطه در ستون (ب) به عنوان تصویر استایل است. 
نمونه‌هایی متاثر از استایل‌های دیگر را می‌توانید در 
<a href="https://github.com/mamintoosi/MMM-Artistic-photoes">
اینجـــــــا
</a>
 ملاحظه فرمایید.
 </td></tr>
</table>


### تبدیل تصاویر روز به تصاویر شب
نمونه تصاویری از صحنه‌های روز که به شب تبدیل شده‌اند:
<table  align="center" border="1">
<tr><td>تصــــویر حاصل از انتقــــال سبـــک </td><td> تصــــــــویــــــــــــر استــــــــــــایـــــل </td><td>تصــــــــــویـــــر محــــتـــوای ورودی</td></tr>
</table>
<table  align="center" border="1">
<tr><td> <img src="images/day2night/img (67).jpg" width="600"> </td></tr>
<tr><td> <img src="images/day2night/pic (110).jpg" width="600"> </td></tr>
</table>
سایر تصاویر  را می‌توانید در 
<a href="https://raw.githack.com/mamintoosi/ST-for-DA-in-FD/main/images/day2night.html">
اینجـــــــا
</a>
 ملاحظه فرمایید.



### بخشی از نتایج
<table  align="center" border="1">
<tr><td> روش پایه </td><td> روش پیشنهادی </td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/img (19).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/img (19).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/img (21).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/img (21).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/img (24).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/img (24).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/img (27).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/img (27).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/img (3).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/img (3).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/img (5).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/img (5).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/img (8).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/img (8).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/pic (10).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/pic (10).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/pic (13).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/pic (13).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/pic (16).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/pic (16).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/pic (19).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/pic (19).jpg" width="300"></td></tr>
<tr><td><img src= "./images/results_fire-dataset-outdoor/pic (21).jpg" width="300"></td><td><img src= "./images/results_fire-dataset-outdoor-d2n/pic (21).jpg" width="300"></td></tr>
</table>


## Start Using Google Colab:
<div dir="rtl">
برای اجرای برنامه در گوگل کولب از لینک زیر استفاده کنید.
به لحاظ ماهیت تصادفی مقداردهی اولیه‌ی وزنهای شبکه‌های عصبی، روال آموزش شبکه، خصوصیات سرور تخصیص داده شده و ... نتایج در اجراهای مختلف مقداری متفاوت خواهد بود. یک اجرای کامل برنامه حدود ۷۰ دقیقه طول کشیده و نزدیک به ۲ گیگابایت داده و مدل دانلود یا تولید خواهد شد. هیچ داده‌ای روی دستگاه شما ذخیره نخواهد شد و همه عملیات روی سرورهای گوگل انجام می‌شود.
</div>

https://colab.research.google.com/github/mamintoosi/Reg-OBD-for-VGG-Pruning-COVID19/blob/master/main_prune.ipynb

<div dir="rtl">
پس از آموزش یا هرس مدل، نتیجه‌ی اجرای آن روی داده‌های تست و صحت
(Accuracy) 
مدل نمایش داده شده است.
خروجی مدل روی ده تصویر تصادفی آزمون هم نشان داده شده است. تصاویر سطر اول، همه کووید۱۹ و تصاویر سطر دوم همه نرمال هستند. برچسب زیر هر تصویر، خروجی مدل را مشخص می‌کند. اگر خروجی مدل با مقدار درست مطابقت داشته باشد، برچسب با رنگ آبی و درغیر اینصورت با رنگ قرمز نمایش داده شده است. با توجه به اینکه ده تصویر از ۲۰۰ تصویر به صورت تصادفی انتخاب شده‌اند،‌ ممکن است نتیجه‌ی این ده تصویر با مقدار صحت نمایش داده شده -که بر روی ۲۰۰ تصویر بوده است- یکی نباشد.

در آخرین سلول مشخصات مدل ترکیبی پیشنهادی نمایش داده شده است، با اصلاح مقدار متغیر input_model می‌توان مشخصات سایر مدلها را نیز مشاهده کرد.
</div>