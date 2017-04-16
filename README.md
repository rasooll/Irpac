# Irpac
<p align="right" dir="rtl"><strong>توضیحات:</strong><br />
شاید شما هم مثل من دوست داشته باشید بسته هایی که پکمن (مدیر یسته ی آرچ لینوکس) دانلود میکند از سرور های داخل کشور باشد .. به دلیل قیمت کمتر پهنای باند داخلی (البته در بعضی از ispها ) این برنامه مناسب شماست ....
</p>
<p dir="rtl" align="right"><strong>پیشنیاز ها:</strong><br />
<ul dir="rtl">
<li>دانلود منیجر Aria2.</li>
<li>سرور/ هاست با پشتیبانی از php.</li>
</ul>
</p>
<p dir="rtl" align="right"><strong>نحوه نصب:</strong><br />
ابتدا فایل pkg.php  را درون هاست خود آپلود کنید فرض می کنیم آدرس آن به صورت زیر است :
<br />
<code>http://example.ir/arch/pkg.php</code><br />
شما باید درون فایل های 
<code>irpac</code> و <code>irpac-upgrade</code>
مقدار status را برابر با 
<code dir="ltr">server="http://example.ir/arch/"</code>
قرار دهید
<br />
سپس برای نصب برنامه از دستورات زیر استفاده کنید:<br />
<div align=left><code dir="ltr">$ sudo mv irpac /usr/bin/irpac</code>
<code dir="ltr">$ sudo mv irpac-upgrad /usr/bin/irpac-upgrade</code>
</div>
<p dir="rtl" align="right"><strong>نحوه استفاده:</strong><br />
برای نصب بسته :
<code dir="ltr">$ irpac package-name</code>
<br />
برای آپگرید سیستم:
<code dir="ltr">$ irpac-upgrade</code>
</p>
