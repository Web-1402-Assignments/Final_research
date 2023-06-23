<div dir="rtl">
<h1>VUE</h1>
<h2>نویسندگان</h2>
<li>مانا عباس‌زاده</li>
<li>محمدمهدی اکبر</li>
<li>دانیال غریب</li>
<hr></hr>
<h2>Vue چیست؟</h2>
Vue js یک framework برای ساختن user interface و همچنین single-page application(SPA) ها می‌باشد.(SPA درواقع به وب اپلیکیشن یا وب سایتی گفته می شود که با کاربر در یک صفحه واحد ارتباط دارد و داینامیک است. و نکته مهم در آن این است که با هر تغییر صفحه حال حاضر را اصطلاحا rewrite می کند به جای اینکه ریکوئست مجدد به سرور بدهد و دوباره صفحه رو لود کند. که این کار و تکنولوژی باعث سریعتر شدن و تجربه بهتری از وبسایت می‌شود)Vue یک فریمورک open-source است و کد مربوط به آن را از 
<a href="https://github.com/vuejs/core">اینجا</a>
می‌توانید ببینید و در آن مشارکت داشته باشید!
<br></br>
<h2>تاریخچه مختصر</h2>
Vue توسط آقای Evan You ساخته شد. که پیش از این برای گوگل کار می‌کرد و از 
<a href="https://angular.io/">Angular</a>
که خود یک فریمورک فرانت دیگر است در تعدادی پروژه استفاده کرده بود.در سال ۲۰۱۳ بر روی Vue کارش را آغاز کرد و در سال ۲۰۱۴ اولین نسخه از این فریمورک را release کرد.
<br></br>
<h2>راه اندازی و آغاز به کار</h2>
<li>پیش نیاز: طبیعتا شما نیاز به یک دانش اولیه و آشنایی با HTML, CSS و JavaScript خواهید داشت چرا که درگیر تگ های مختلف HTML , CSS و کدهای JS خواهید شد.</li>
<br></br>
می توان به ۳ روش زیر با Vue کار کرد:
<li>Online : صرفا برای آشنایی با نحوه کارکرد و دیدکلی اولیه می توان از 
<a href="https://play.vuejs.org/#eNo9jcEKwjAMhl/lt5fpQYfXUQfefAMvvRQbddC1pUuHUPrudg4HIcmXjyRZXEM4zYlEJ+T0iEPgXjn6BB8Zhp46WUZWDjCa9f6w9kAkTtH9CRinV4fmRtZ63H20Ztesqiylphqy3R5UYBqD1UyVAPk+9zkvV1CKbCv9poMLiTEfR2/IXpSoXomqZLtti/IFwVtA9A==">playGround خود Vue</a>
استفاده کرد
</li>
<li>با استفاده از node.js : برای این روش شما حداقل نیاز به ورژن ۱۶ یا بالاتر از node نیاز دارید.
ابتدا به محلی که می‌خواهید پروژه را ایجاد کنید بروید و کامند زیر را بزنید:
<br>
</li>
</div>
<br>
<div dir="ltr"><code>npm init vue@latest</code></div>
<div dir="rtl">
با اینکار آخرین نسخه vue را دانلود و یک پروژه سمپل برای خود می‌سازید. احتمالا بعد از وارد کردن این کامند تعدادی اپشن به شکل زیر به شما نمایش داده می‌شود که برای شروع می‌توانید حالت پیشفرض هرکدام را بزنید و ادامه دهید.
</div>
<div><code>✔ Project name: … <your-project-name>
✔ Add TypeScript? … No / Yes<br>
✔ Add JSX Support? … No / Yes<br>
✔ Add Vue Router for Single Page Application development? … No / Yes<br>
✔ Add Pinia for state management? … No / Yes<br>
✔ Add Vitest for Unit testing? … No / Yes<br>
✔ Add an End-to-End Testing Solution? … No / Cypress / Playwright<br>
✔ Add ESLint for code quality? … No / Yes<br>
✔ Add Prettier for code formatting? … No / Yes<br>

Scaffolding project in ./<your-project-name>...
Done.</code></div>
<div dir="rtl">
![Getting Started](Screenshot%20from%202023-06-22%2023-44-35.png)</div>