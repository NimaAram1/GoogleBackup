# Google Backup

In recent weeks (late March 2021 - early April 2021), some changes appear to have been made to the way Google detects its users' locations, as a result of which, one cannot access Google's services from inside Iran even using a VPN.

### What services have been affected?

- Youtube: Some Iranian youtubers have reported some viewership coming from Iran despite the fact that Youtube is blocked by Iranian authorities and Iranians have to use a VPN in order to watch Youtube videos.
- Developer Services: Some services related to Google-backed platforms like Android or programming languages like Go
- Youtube Premium
- Youtube Kids: Please note that this is a free service and has never been subject to sanctions.
- Spotify: Spotify is served by Google Cloud Platform (GCP).
- Google Cloud Platform (GCP)
- Google Analytics
- kaggle
- Google 2FA
- Google OAuth 2.0
- Google Prompt
- Last.fm

### FAQ

- Has Google suspended Gmail for Iranians due to sanctions? No.
- Has Google suspended Drive for Iranians due to sanctions? No.
- Has Google suspended any of its services for Iranians due to sanctions? No. There has been no indications of any changes in Google's policies.
- What is this repo about? The rest of this article is in Farsi and provides instructions for Iranians on how to export a copy of their contents in their Google account just in case.

<div dir='rtl'>
  

## چه اتفاقی افتاده است؟
در هفته‌های اخیر تغییراتی در شیوه شناسایی محل کاربران از سمت گوگل اتفاق افتاده که در نتیجه آن حتی اگر از VPN برای دسترسی به سرویس‌های گوگل استفاده کنید باز هم اینکه از ایران هستید را تشخیص داده و از استفاده از بعضی سرویس‌ها جلوگیری کند. بعضی این را مرتبط با [تغییرات در مالیات از درآمد یوتوب](https://support.google.com/youtube/answer/10391362?hl=en) می‌دانند که باعث شده گوگل مکانیزم شناسایی محل کاربران را بروز کند.

**چه سرویس‌هایی تا کنون از این تغییر تاثیر گرفته‌اند؟**

- Youtube: یوتبرهای ایرانی گزارش می‌کنند که بخشی از آمار بازدید آن‌ها از ایران تشخیص داده می‌شود. [منبع](https://twitter.com/amirabbas/status/1377186765358854144)
- Developer Services: بعضی از سرویس‌های مرتبط با برنامه‌نویسی مانند بخش توسعه‌دهندگان اندروید [منبع](https://twitter.com/ErFUN_KH/status/1378320906213339136) یا زبان Go [منبع](https://twitter.com/ans_ashkan/status/1378370073765756928) 
- Youtube Premium [منبع](https://twitter.com/AmirFouladvand/status/1378344635953713153)
- Youtube Kids: دقت کنید که این سرویس رایگان می‌باشد و از سوی گوگل تحریم نیست. [منبع](https://twitter.com/AmirFouladvand/status/1378344635953713153)
- Spotify: اسپاتیفای روی زیرساخت ابری گوگل (GCP) قرار دارد. [منبع](https://twitter.com/yashar_rashedi/status/1377947240078176259)
- GCP و برخی مشتریان آن به عنوان مثال tinypng.com و ifconfig.me [منبع](https://github.com/Hameds/GoogleBackup/issues/7)
- Google Analytics [منبع](https://twitter.com/AmirFouladvand/status/1378222387129368584)
- kaggle [منبع](https://twitter.com/MrAlihoseiny/status/1378383671133081606)
- Google 2FA [منبع](https://twitter.com/only_sadeghi/status/1378437673162043392)
- Google OAuth 2.0 [منبع](https://twitter.com/babakmhz/status/1378364207482212358)
- Google Prompt [منبع](https://github.com/Hameds/GoogleBackup/issues/13)
- Last.fm [منبع](https://twitter.com/don_wp/status/1378256122071687168)
- اگر سرویس دیگری می‌شناسید لطفاً در بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) اعلام کنید.

**چه خطایی دریافت می‌شود؟**

معمولاً خطای 403 گزارش شده است و در یک مورد خطای 404 [منبع](https://twitter.com/bkhezry/status/1377970749374365697). لطفاً اگر تجربه‌ای در این موارد داشته‌اید آن را در بخش  [Issues](https://github.com/Hameds/GoogleBackup/issues) یا با ویرایش این فایل در بخش «تجربه شما» به اشتراک بگذارید

## بکاپ به چه معناست و چه باید بکنم؟
نسخه پشتیبان یا Backup  به معنی یک نسخه از اطلاعات شماست که روی سرویس‌های گوگل قرار دارد مثلاً یک نسخه از تمام ایمیل‌های شما یا یک نسخه از تمام مخاطبین یا فایل‌های شما که روی Google Drive قرار دارد.

برای دریافت بکاپ به آدرس [Google Takeout](https://takeout.google.com) مراجعه کنید و سرویس‌هایی که می‌خواهید یک نسخه پشتیبان از اطلاعات آن‌ها دریافت کنید را مشخص کنید. در ادامه Export once را انتخاب و تایید کنید. بعد از مدتی یک ایمیل حاوی لینک دانلود اطلاعات برای شما ارسال می‌شود.

⚠️ نکته مهم: اگر کلمات عبور خود را روی مرورگر کروم ذخیره کردید به آدرس [Google Password Manager](https://password.google.com) رفته و یک نسخه پشتیبان تهیه کنید.

**رمزنگاری فایل‌های بکاپ**

بعد از دانلود فایل‌های بکاپ به روش اشاره شده در [این توییت](https://twitter.com/oraclenik/status/1378389345955155972) آن‌ها را رمزنگاری کنید.


## سوالات متداول

- آیا جیمیل ایران را تحریم کرده؟ خیر
- آیا گوگل درایو ایران را تحریم کرده؟ خیر
- آیا گوگل ایران را تحریم کرده؟ خیر. هیچ نشانه‌ای از تغییر سیاست‌های گوگل در این خصوص وجود ندارد و این بکاپ به منظور احتیاط گرفته می‌شود
- بعد از اقدام به بکاپ، به من می‌گوید چند ساعت یا چند روز طول می‌کشد بکاپ آماده شود. چه کنم؟ نگران نباشید، خیلی زود لینک دانلود بکاپ ایمیل خواهد شد.
- موقع دانلود فایل بکاپ با خطای 403 مواجه می‌شوم. چه کنم؟ از VPN استفاده کنید.
- با وجود استفاده از VPN باز هم با خطای 403 در موقع دانلود بکاپ مواجه می‌شوم. چه کنم؟ از VPN دیگری استفاده کنید و نگران نباشید
- اصلاً چرا باید بکاپ گرفت؟ صرفنظر از اینکه تحریم باشیم یا نباشیم، داشتن بکاپ از اطلاعات باعث آسودگی خاطر در زمان بحران‌های احتمالی است

## نشت‌های احتمالی
یکی از موارد مهمی که باعث مواجه شدن با خطای 403 می‌شود استفاده از VPNهای متفرقه با شیرینگ زیاد است. 
این VPNها باعث نشست‌های مختلف در سطوح مختلف می‌شوند و در نتیجه گوگل به مشخصات اصلی شما پی خواهد برد
#### برخی از این نشت‌ها (leaks)
##### IP and DNS leaks
این نشت زمانی اتفاق می‌افتد که VPN شما تنها برای گذر از فیلترینگ طراحی شده و توانایی رمزنگاری دیتا در سطح بالا را ندارد به همین دلیل آی‌پی اصلی شما مشخص خواهد شد

**تست و بررسی این نشست:**
https://browserleaks.com/ip

در صورتی که در بخش DNS Leak Test آی‌پی به غیر از آی‌پی VPN مشاهده می‌کنید به معنای مثبت بودن نشستی است

##### WebRTC leak:
نشست webRTC یکی از دیگر نشست‌هایی است که در سطح مرورگر باعث دسترسی به اطلاعات شما می‌شود و علیرغم استفاده از VPN با خطای 403 مواجه خواهید شد

برای بررسی این نشست نیز می‌توانید از سایت‌های زیر استفاده کنید:

- https://ip.voidsec.com/
- https://browserleaks.com/webrtc

رفع نشت webRTC با استفاده از پلاگین‌های نظیر WebRTC Leak Prevent یا استفاده از VPNهای معتبر قابل انجام است

### VPNهای تست شده
این VPNها طبق بررسی انجام شده دارای حداقل نشتی در اطلاعات هستند و در دیتاسنترهای معتبر میزبانی می‌شوند :

- NordVPN
- ExpressVPN
- Mullvad
- Windscribe [منبع](https://github.com/Hameds/GoogleBackup/issues/9)

## محتویات فایل‌ بک‌آپ
فایل بک‌آپ شامل تمام داده‌های سرویس‌های مختلف گوگل میباشد. مثلا:

- عکس‌هایی که توی گوگل‌فوتوز آپلود کردید +‌ فایل‌های متادیتاشون
- تمام ایمیل‌هاتون با فرمت Mbox موجوده که میتونید توی کلاینت‌های استاندارد ایمیل مشاهده کنیدشون
- کانال‌هایی که توی یوتیوب دنبال کردید یا پلی لیست‌ها یا حتی ویدیو‌هایی که لایک کردید و ... همگی به صورت json وجود داره
- تمام فایل‌های گوگل درایو
- لیست کانتکت‌هاتون با فرمت VCF
- چت‌های hangout و فایل‌هاش
- و ...

![Capture](https://user-images.githubusercontent.com/21690865/113487292-7d381a00-94cc-11eb-8db3-0747bd822b29.PNG)

<sub>تصویر پوشه‌های داخل فایل بک‌آپ</sub>

## تجربه شما

لطفاً اگر تجربه‌ای در این خصوص دارید، فایل `Readme.md` این مخزن را ویرایش کرده و `Pull Request`  ارسال کنید یا آن را از طریق بخش [Issues](https://github.com/Hameds/GoogleBackup/issues) به اشتراک بگذارید.


</div>
