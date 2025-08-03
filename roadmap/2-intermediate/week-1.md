<div dir="rtl" style="text-align: right;">
  <h2>🏗 هفته پنجم: آشنایی با معماری MVVM در اندروید</h2>
  <p>
    در این هفته وارد دنیای معماری نرم‌افزار در اندروید می‌شیم. یکی از پراستفاده‌ترین معماری‌ها، الگوی MVVM (Model-View-ViewModel) هست که به جداسازی منطق از رابط کاربری کمک می‌کنه و پروژه رو تست‌ پذیرتر و قابل نگهداری‌ تر می‌کنه.
  </p>

  <hr>

<h3>🎯 اهداف هفته:</h3>
  <ul>
    <li>درک مفهوم معماری MVVM و اجزای اصلی آن</li>
    <li>آشنایی با ViewModel و نقش آن در مدیریت داده‌ها</li>
    <li>استفاده از StateFlow برای ارتباط بین View و ViewModel</li>
    <li>ساخت پروژه ساده با استفاده از معماری MVVM</li>
    <li>ایجاد جداسازی مناسب بین لایه‌ها</li>
  </ul>

  <hr>

<h3>🧰 مراحل پیشنهادی:</h3>
  <ol>
    <li>
      <strong>🔍 معرفی معماری MVVM:</strong>
      <ul>
        <li>توضیح ساختار کلی MVVM (Model، View، ViewModel)</li>
        <li>تفاوت MVVM با معماری‌های دیگر (مثل MVC، MVP)</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>🧠 آشنایی با ViewModel:</strong>
      <ul>
        <li>ایجاد ViewModel</li>
        <li>ذخیره و مدیریت داده‌ها در ViewModel</li>
        <li>چرخه‌ حیات ViewModel و مزایای آن</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>🔄 ارتباط View با ViewModel:</strong>
      <ul>
        <li>آشنایی با <code>StateFlow</code> </li>
        <li>اتصال ViewModel به Composable یا Fragment/Activity</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>📦 ایجاد لایه Model:</strong>
      <ul>
        <li>تعریف دیتا کلاس های مورد نیاز</li>
        <li>ایجاد Repository برای منبع داده (مثلاً API یا دیتابیس)</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>🔗 اتصال همه اجزا:</strong>
      <ul>
        <li>ساخت پروژه ساده که از ViewModel، Repository و Model استفاده می‌کنه</li>
        <li>تفکیک کامل لایه‌ها و رعایت اصل Single Responsibility</li>
      </ul>
    </li>
  </ol>

  <hr>

<h3>❓ پرسش‌های تفکر‌برانگیز:</h3>
  <ul>
    <li>چرا باید بین UI و منطق برنامه جداسازی ایجاد کنیم؟</li>
    <li>چه زمانی استفاده از ViewModel الزامی یا مفید می‌شه؟</li>
    <li>آیا می‌شه بدون Repository هم MVVM پیاده‌سازی کرد؟</li>
  </ul>

  <hr>

<h3>✔ منابع پیشنهادی:</h3>
  <ul>
    <li><a href="https://developer.android.com/topic/architecture">راهنمای رسمی معماری اندروید</a></li>
  </ul>

  <hr>

<h3>🧪 تمرین‌های هفته:</h3>
  <p>
    ✅ <strong>تمرین ۱ (پایه):</strong> اپلیکیشنی بساز که یک متن رو از ViewModel دریافت کنه و با کلیک روی دکمه، متن تغییر کنه. از StateFlow برای این کار استفاده کن.
  </p>
  <p>
    🚀 <strong>تمرین ۲ (پیشرفته ‌تر):</strong> یک اپ لیست ساده بساز (مثلاً لیست وظایف یا محصولات) که داده‌ها از ViewModel تأمین بشن. داده‌ها رو داخل Repository شبیه‌سازی کن (مثل لیستی از داده‌های ثابت). اضافه کردن، حذف و فیلتر کردن آیتم‌ها رو هم پیاده‌سازی کن.
  </p>
</div>
