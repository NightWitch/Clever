
<h1><p align="center">سین آپ

<h3 align="right"> <strong> روش نصب سورس</strong> 🚀
</h3>
<hr>
<h4 dir="rtl">ابتدا آدرس گیتهاب <em>سین آپ</em> را کپی کرده و پکیج هارو  نصب کنید.</h4>
<h6>(موارد زیر را در ترمینال وارد کنید)</h6>
<pre>
<span>git clone https://github.com/Nightwitch/Clever.git</span>
<span>cd Clever</span>
<span>chmod +x bot</span>
<span>./bot install</span>
</pre>
<h4 dir="rtl"> برای ایجاد یک ربات سین آپ جدید دستور  <strong>bot create/.</strong> را وارد کنید.
</h4>
<pre>
<span>./bot create</span>
</pre>
<h4 dir="rtl">اکنون ربات خود را با عددی که داده شده راه اندازی کنید.
<br>مثال:./bot 1</h4>
<h6 dir="rtl"> برای شروع ردیس میتوانید از دستورات زیر استفاده کنید.</h6>
<pre>
<span> از دستور زیر برای تنظیم مجدد ردیس استفاده کنید    #</span>
<span>sudo service redis-server restart</span>
<span>  از دستور زیر برای راه اندازی ردیس استفاده کنید  #</span>
<span>sudo service redis-server start</span>
<span></span>
<span>./bot 1</span>
</pre>
<h5 dir="rtl"> پس از زدن دستور بالا از شما شناسه عددی ادمین ربات را میخواهد.
<h6 dir="rtl"> شما می توانید با استفاده از ربات <a href="https://telegram.me/userinfobot">@UserinfoBot</a> شناسه عددی خود را بدست آورید.</h6>
<h6 dir="rtl">از <a href="#help">راهنمای سین آپ</a> برای آشنا شدن با طرز کار رباتتان استفاده کنید.</h6>
<br>
<h3 align="right"><strong>جلوگیری از قطع شدن عملکرد سین آپ</strong>🛡
<hr
<h4 dir="rtl">یکی از مشکلات کار با SSH، قطع شدن آن در زمان قطع اتصال اینترنت است.<br>وقتی اتصال اینترنت قطع می‌شود اجرای تمامی برنامه‌ها و فرامینی که در حال استفاده از SSH بودند، متوقف می‌شود. فرمان screen این‌جا به‌کمک شما می‌آید. کافی است این دستور را قبل از دستورراه‌اندازی سین آپ قرار دهید.</h4>
<h6 dir="rtl">مثال:</h6>
<pre>
<span><strong>screen ./bot 1</strong></span>
</pre>
<h4 dir="rtl">برای خارج شدن از محیط screen کلید های ترکیبی Ctrl+A و سپس کلید D را بفشارید.<br>برای مشاهده فهرست screen های موجود میتوانید از دستور<strong>  screen -ls  </strong>  استفاده کنید.<br>این دستور فهرست تمامی screen های در حال اجرا را نمایش می دهد.<br>برای مشاهده screen اجرا شده، کافی است دستور زیر را وارد کنید:</h4>
<pre>
<span><strong>screen -r [screen name]</strong></span>
</pre>
 
 <a href="https://telegram.me/Mrjavi">ارتباط با پشتیبانی</a>
