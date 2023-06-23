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
<h3><li>Online :</h3>
 صرفا برای آشنایی با نحوه کارکرد و دیدکلی اولیه می توان از 
<a href="https://play.vuejs.org/#eNo9jcEKwjAMhl/lt5fpQYfXUQfefAMvvRQbddC1pUuHUPrudg4HIcmXjyRZXEM4zYlEJ+T0iEPgXjn6BB8Zhp46WUZWDjCa9f6w9kAkTtH9CRinV4fmRtZ63H20Ztesqiylphqy3R5UYBqD1UyVAPk+9zkvV1CKbCv9poMLiTEfR2/IXpSoXomqZLtti/IFwVtA9A==">playGround خود Vue</a>
استفاده کرد
</li>
<h3><li>با استفاده از node.js :</h3> برای این روش شما حداقل نیاز به ورژن ۱۶ یا بالاتر از node نیاز دارید.
ابتدا به محلی که می‌خواهید پروژه را ایجاد کنید بروید و کامند زیر را بزنید:
<br>
</li>
</div>
<br>
<div dir="ltr"><code>npm init vue@latest</code></div>
<div dir="rtl"><br>
با اینکار آخرین نسخه vue را دانلود و یک پروژه سمپل برای خود می‌سازید. احتمالا بعد از وارد کردن این کامند تعدادی اپشن به شکل زیر به شما نمایش داده می‌شود که برای شروع می‌توانید حالت پیشفرض هرکدام را بزنید و ادامه دهید.
</div>
<br>

```
✔ Project name: … <your-project-name>
✔ Add TypeScript? … No / Yes
✔ Add JSX Support? … No / Yes
✔ Add Vue Router for Single Page Application development? … No / Yes
✔ Add Pinia for state management? … No / Yes
✔ Add Vitest for Unit testing? … No / Yes
✔ Add an End-to-End Testing Solution? … No / Cypress / Playwright
✔ Add ESLint for code quality? … No / Yes
✔ Add Prettier for code formatting? … No / Yes

Scaffolding project in ./<your-project-name>... Done.
```
<br>
<div dir="rtl">در ادامه وارد پوشه پروژه ای که درمحل زدن کامند ساخته اید بشوید.
وسپس دستورات زیر را بزنید‌:
</div>
<br>
<div>

```
npm install
npm run dev
```
<br>
</div>
<div dir="rtl">
تبریک شما اولین پروژه Vue خود را ساختید. احتمالا در پایان این مرحله درکامند لاین برای شما یک پورت از لوکال هاست نمایش داده می‌شود که پروژه درآنجا بالا آمده. می‌توانید به مرورگر خود بروید و چک کنید.در ادامه هرتغییری که درپروژه می‌دهید نیازمند به ساخته شدن مجدد آن است که می‌توانید با کامند <code>npm run build</code>
آن را مجددا بسازید.</div>
<br>
<div dir = "rtl"> 
<h3><li>با استفاده از CDN </h3>
شما به سادگی می‌توانید در کد html خود تگ اسکریپت مربوط به کدهای ویو را ایمپورت کنید و از آنها استفاده کنید. مانند هرکد js دیگری که برای وب اپلیکیشن خود نوشته اید. برای اینکار باید تگ زیر در کد html شما موجود باشد:
</li></div>
<br>

```html
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
```
<div dir="rtl">
درادامه بیشتر از این مدل از Vue استفاده می‌کنیم و این روش واضح تر می‌شود.
نکته مثبت راجب این مدل استفاده از Vue این است که دیگر نیازی به بیلد کردن نداریم. درادامه به یک سری مفاهیم مهم در Vue می‌پردازیم و Hello World را در Vue پیاده‌سازی ‌می‌کنیم.
<br>
ابتدا یک Hello World ساده و استاتیک را نشان می‌دهیم.صرفا برای آشنایی با سینتکس Vue:<br>
</div>
<div>


    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Vue test</title>
        <script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
    </head>
    <body>
        <div id="app"></div>
        <script src="app.js"></script>
    </body></div>
<div dir="rtl">ابتدا CDN مربوطه را در اسکریپت نوشته و یک body برای فایل html خود می‌سازیم.
همچنین برای جلوگیری از شلوغی کدهای js را به یک فایل جدای app.js می‌بریم.محتوای فایل app.js نیز به شکل زیر است:</div>

```js
const app = Vue.createApp({
    template: '<h2>Hello World!</h2>'
})

app.mount('#app')
```
<div dir="rtl">همانطور که مشاهده می‌کنید Hello World درصفحه وب شما با اندازه h2 مشاهده می‌شود.
ما یک اپ Vue ساختیم و یک المان template به آن دادیم و دراینجا عینا سینتکس html را نوشته ایم و درنهایت با سینتکس app.mount
به اپی که ساخته ایم میگوییم کجای کد html ما سوار شود.(که دراینجا هرجایی که id ای برابر با app داشته باشد را شامل می‌شود.)</div>
<div dir="rtl">
در Vue دو مفهوم بسیار مهم و اساسی وجود دارد که اصلا دلیل به وجود آمدن آن نیز هست:<br>
<h3>Declarative Rendering</h3>
<h3>Reactivity</h3>
این مفاهیم را سعی می‌کنیم با مثال زیر توضیح دهیم:
<br>

<code>html</code>

```html
   <script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
    </head>
    <body>
        <h1>hi :)</h1>
        <div id="app">
            <button @click="increase">{{ count }}</button>
        </div>
        <script src="app.js"></script>
    </body>
```

<code>Vue</code>
```js
const app = Vue.createApp({
    data() {
        return {
            count: 0
        }
    },
    methods: {
        increase() {
            this.count++
        }
    }
})
app.mount('#app')
```
می‌توانید این کدرا کپی و امتحان کنید.در اینجا مابرای یک دکمه یک تابع تعریف کردیم (increase) که با هربار کلیک برروی آن متود increase از سمت Vue app کال می‌شود.
و همچنین یک متغیر count داریم که درسمت vue آن را درکد js خود تعریف کرده‌ایم.وبا هربار کلیک برروی دکمه یکی به مقدار آن افزوده می‌شود(مقدار اولیه آن را صفر درنظر گرفتیم)
حال به بررسی مفاهیم گفته شده می‌پردازیم:
<br>
<h3>Declarative Rendering:</h3>
 یک ویژگی مهم و فیچر اصلی در Vue این است که می‌تواند برروی کد html سوار شود و اصطلاحا آن را گسترش(extend) دهد.و DOM باتوجه به کد js ما دیتاهای اضافی ای را می‌گیرد مانند همین count که دراینجا با سینتکس مخصوص {{count}} نشان داده شده است.
<br>
<h3>Reactivity:</h3>
بدین معنی‌ست که تغییرات در JS توسط Vue به طور اتوماتیک همواره شناسایی شده و درکسری از ثانیه برروی DOM اعمال می‌شوند که سرعت بسیار بیشتری نسبت به ریلود کردن یک پیج دارد. مثلن درهمین مثال باهربار کلیک برروی دکمه یکی به عدد روی آن اضافه می‌شود ولی می بینیم که بدون هیچ وقفه ای این عدد در حال اپدیت شدن است. ویژگی Reactivity به ما قدرت مانور بسیاری می‌دهد.
</div>
