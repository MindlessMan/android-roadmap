<div dir="rtl" style="text-align: right;"> 
  <h2>🎨 هفته سوم: آشنایی با Jetpack Compose برای طراحی UI اندروید</h2>
  <p>
    این هفته وارد دنیای طراحی رابط کاربری مدرن اندروید با Jetpack Compose می‌شیم؛ رویکرد جدید گوگل برای ساخت UI که مبتنی بر کدنویسی دکلرتیو هست.
    یادگیری Compose برای توسعه اپلیکیشن‌های سریع، قابل نگهداری و زیبا ضروریه.
  </p>

  <hr>

  <h3>🎯 اهداف هفته:</h3>
  <ul>
    <li>درک مفهوم UI دکلرتیو و مقایسه با XML سنتی</li>
    <li>آشنایی با ساختار پایه Jetpack Compose</li>
    <li>طراحی کامپوننت‌های ساده با Compose</li>
    <li>مدیریت حالت (State) در Compose</li>
    <li>آشنایی با لیست‌های کارا (Lazy Lists: <code>LazyColumn</code> / <code>LazyRow</code>)</li>
  </ul>

  <hr>

  <h3>🧰 مراحل پیشنهادی:</h3>
  <ol>
    <li>
      <strong>📦 مقدمه‌ای بر Jetpack Compose:</strong>
      <ul>
        <li>چرا Jetpack Compose؟ مزایا نسبت به XML</li>
        <li>راه‌اندازی پروژه با پشتیبانی از Compose در Android Studio</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>🖌 ساخت UI ساده:</strong>
      <ul>
        <li>ساخت اولین Composable با <code>@Composable</code></li>
        <li>نمایش متن با <code>Text</code></li>
        <li>اضافه کردن دکمه با <code>Button</code> و مدیریت رویداد کلیک</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>🔄 مدیریت حالت (State):</strong>
      <ul>
        <li>آشنایی با <code>remember</code> و <code>mutableStateOf</code></li>
        <li>به‌روزرسانی UI هنگام تغییر State</li>
        <li>مفهوم "State Hoisting" برای اشتراک‌گذاری State بین Composableها</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>🎨 Layout و Styling:</strong>
      <ul>
        <li>استفاده از <code>Column</code> و <code>Row</code></li>
        <li>تنظیم Padding، Margin و رنگ‌ها با Modifierها</li>
      </ul>
    </li>
    <br>
    <li>
      <strong>📜 Lazy Lists:</strong>
      <ul>
        <li>تفاوت <code>Column</code> با <code>LazyColumn</code> (Performance و Recomposition)</li>
        <li>استفاده از <code>items</code> و <code>item</code> در <code>LazyColumn</code></li>
        <li>اضافه کردن جداکننده (Divider) یا فاصله بین آیتم‌ها</li>
      </ul>
    </li>
  </ol>

  <hr>

  <h3>❓ پرسش‌های تفکر‌برانگیز:</h3>
  <ul>
    <li>چه تفاوتی بین رویکرد XML و Compose وجود داره؟</li>
    <li>چرا مدیریت State در UI دکلاراتیو اهمیت داره؟</li>
    <li>آیا می‌شه XML و Compose رو همزمان در یک پروژه استفاده کرد؟</li>
    <li>چه زمانی باید از <code>LazyColumn</code> به‌جای <code>Column</code> استفاده کرد؟</li>
  </ul>

  <hr>

  <h3>✔ منابع پیشنهادی:</h3>
  <ul>
    <li><a href="https://developer.android.com/jetpack/compose">مستندات رسمی Jetpack Compose</a></li>
  </ul>

  <hr>

  <h3>🧪 تمرین‌های هفته:</h3>
  <p>
    ✅ <strong>تمرین ۱ (پایه):</strong> یک صفحه ساده بساز که شامل یک متن و یک دکمه باشه. وقتی روی دکمه کلیک می‌شه، متن تغییر کنه. از State برای مدیریت این تغییر استفاده کن.
  </p>
  <p>
    🚀 <strong>تمرین ۲ (چالشی‌تر):</strong> یک لیست از آیتم‌ها (مثلاً نام درس‌ها یا وظایف روزانه) رو در <code>LazyColumn</code> نمایش بده. هر آیتم شامل متن و یک دکمه/چک‌باکس باشه. با کلیک، وضعیت آیتم (انجام‌شده/انجام‌نشده یا انتخاب‌شده) تغییر کنه و تعداد آیتم‌های انتخاب‌شده در بالای صفحه نمایش داده بشه. State رو در سطح والد نگه دار (State Hoisting) تا تمام لیست به‌درستی به‌روزرسانی بشه.
  </p>
</div>
