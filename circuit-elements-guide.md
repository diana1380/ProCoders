---
layout: persian
classes: wide rtl-layout
dir: rtl
title: کتابچه المان‌های مدار برای دانش‌آموزان
permalink: /teaching/studenteffort/circuiteffort/circuit-elements-guide/
author_profile: true
header:
  overlay_image: /assets/images/background.jpg
  overlay_filter: 0.3
  overlay_color: "#5e616c"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---
1. 
# کتابچه المان های مدار


# فهرست مطالب

1. [ولتاژ](#voltage)
    - [1.1 تعریف ولتاژ](#voltage-definition)
    - [1.2 منبع ولتاژ چیست؟](#voltage-source)
    - [1.3 انواع منابع ولتاژ](#voltage-types)
    - [1.4 اهمیت منبع ولتاژ](#voltage-importance)
    - [1.5 نماد منبع ولتاژ در مدار](#voltage-symbol)

2. [جریان الکتریکی](#current)
    - [2.1 تعریف جریان الکتریکی](#current-definition)
    - [2.2 جهت جریان](#current-direction)
    - [2.3 منبع جریان چیست؟](#current-source)
    - [2.4 انواع منابع جریان](#current-types)
    - [2.5 نماد منبع جریان در مدار](#current-symbol)
    - [2.6 اهمیت منبع جریان](#current-importance)

3. [مقاومت (Resistor)](#resistor)
    - [3.1 مقاومت چیست؟](#what-is-resistor)
    - [3.2 چگونه جریان برق حرکت می‌کند؟](#how-electric-current-flows)
    - [3.3 مواد مختلف چه مقدار مقاومت دارند؟](#resistance-of-different-materials)
    - [3.4 کاربرد مقاومت در مدار چیست؟](#applications-of-resistor)
    - [3.5 چطور مقدار مقاومت را بفهمیم؟](#how-to-measure-resistance)
    - [3.6 مقاومت در مدار](#resistor-in-circuit)

4. [خازن (Capacitor)](#capacitor)
    - [4.1 خازن چیست؟](#capacitor)
    - [4.2 شارژ و تخلیه خازن](#charge-discharge)
    - [4.3 مثال ساده](#water-example)
    - [4.4 رفتار خازن](#behavior)
    - [4.5 اجزای اصلی خازن](#components)
    - [4.6 نحوه ساخت خازن](#construction)
    - [4.7 ظرفیت و ولتاژ خازن](#capacitance-voltage)
    - [4.8 کاربردهای خازن](#applications)

5. [سلف (Inductor)](#inductor)
    - [5.1 سلف چیست؟](#inductor)
    - [5.2 سلف و جریان برق](#inductor-and-electric-current)
    - [5.3 رفتار جادویی سیم‌پیچ](#magical-behavior-of-coil)
    - [5.4 چه چیزهایی روی قدرت سلف تأثیر دارند؟](#factors-affecting-inductance)
    - [5.5 کاربردهای سلف](#applications-of-inductor)
6. [نتیجه‌گیری](#conclusion)
7. [منابع](#references)
--- 

**نام:** زینب بادیانی  
**ایمیل:** raintdiana@gmail.com  
**وابستگی** : گروه مهندسی کامپیوتر، دانشگاه فردوسی مشهد

## 1. ولتاژ <a name="voltage"></a>

### 1.1 تعریف ولتاژ <a name="voltage-definition"></a>

ولتاژ چیست؟

تصور کنید یک رودخانه داریم که آب در آن جریان دارد. برای اینکه آب حرکت کند، باید نیرویی به آن وارد شود، مثلاً از یک ارتفاع به پایین بریزد. در مدارهای الکتریکی هم مشابه همین اتفاق می‌افتد، با این تفاوت که به جای آب، الکترون‌ها حرکت می‌کنند.

ولتاژ همان نیرویی است که باعث می‌شود الکترون‌ها در مدار حرکت کنند. به عبارت ساده، ولتاژ «فشار» الکترون‌ها در مدار است. واحد اندازه‌گیری ولتاژ، **ولت (V)** است.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Voltage.jpg" alt="فشار الکترون‌ها و ایجاد جریان" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱. فشار الکترون‌ها و ایجاد جریان
</div>

---

### 1.2 منبع ولتاژ چیست؟ <a name="voltage-source"></a>

حالا که فهمیدیم ولتاژ چیست، باید بدانیم که این فشار الکترون‌ها از کجا می‌آید. اینجا منبع ولتاژ وارد می‌شود.

منبع ولتاژ مانند یک پمپ است که ولتاژ را در مدار ایجاد می‌کند و باعث می‌شود الکترون‌ها حرکت کنند. مثلاً باتری‌ها و ژنراتورها منابع ولتاژ هستند.

---

### 1.3 انواع منابع ولتاژ <a name="voltage-types"></a>

1. **منبع ولتاژ ثابت (DC):** ولتاژی ثابت و یکنواخت تولید می‌کند. مثلاً باتری‌ها.  
2. **منبع ولتاژ متناوب (AC):** ولتاژی است که جهت آن با زمان تغییر می‌کند. مثلاً برق شهری.

---

### 1.4 اهمیت منبع ولتاژ <a name="voltage-importance"></a>

بدون منبع ولتاژ، هیچ‌چیز در مدار کار نمی‌کند. مثلاً در یک چراغ‌قوه، باتری منبع ولتاژ است که باعث می‌شود جریان برق به لامپ برسد و روشن شود.

---

### 1.4 نماد منبع ولتاژ در مدار <a name="voltage-symbol"></a>

در نقشه‌های مدار، منبع ولتاژ معمولاً با نماد خاصی نمایش داده می‌شود:

- برای منابع ولتاژ ثابت، نماد یک خط افقی با علامت مثبت (+) و منفی (-) است.  
- برای منابع ولتاژ متناوب، نماد یک خط افقی با موج سینوسی داخل آن است.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Voltage2.jpg" alt="نماد منبع ولتاژ" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲. نماد منبع ولتاژ
</div>

---

## 2. جریان الکتریکی <a name="current"></a>

### 2.1 تعریف جریان الکتریکی <a name="current-definition"></a>

اگر دوباره به مثال رودخانه برگردیم، جریان الکتریکی مثل حرکت آب در رودخانه است. وقتی ولتاژ (فشار الکترون‌ها) وجود داشته باشد، الکترون‌ها شروع به حرکت می‌کنند و این حرکت همان جریان برق است.

جریان میزان بار الکتریکی‌ای است که در یک زمان مشخص از یک نقطه مدار عبور می‌کند. واحد اندازه‌گیری جریان **آمپر (A)** است.

---

### 2.2 جهت جریان <a name="current-direction"></a>

جریان جهت دارد. به طور قراردادی، جریان مثبت در جهت حرکت بارهای مثبت است. در واقع، در سیم‌ها الکترون‌ها حرکت می‌کنند و جریان واقعی خلاف جهت جریان قراردادی است.

در نمودارهای مدار، معمولاً فلشی کنار نماد جریان قرار دارد تا جهت آن را نشان دهد.  
اگر مقدار جریان مثبت باشد، جریان در همان جهت فلش است؛ اگر منفی باشد، در خلاف جهت آن حرکت می‌کند.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Circuit.jpg" alt="جهت جریان و حرکت الکترون‌ها" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۳. جهت جریان و حرکت الکترون‌ها
</div>

---

### 2.3 منبع جریان چیست؟ <a name="current-source"></a>

منبع جریان یک عنصر مدار است که جریان مشخصی را به مدار می‌دهد، بدون توجه به مقاومت یا بار متصل به آن.  
می‌توان آن را مثل یک شیر آب تنظیم‌شده تصور کرد که همیشه مقدار مشخصی آب (جریان) را عبور می‌دهد، حتی اگر مسیر آب سخت‌تر یا آسان‌تر شود.

---

### 2.4 انواع منابع جریان <a name="current-types"></a>

1. **منبع جریان مستقل:** جریان ثابت و مشخصی تولید می‌کند، بدون توجه به شرایط مدار.  
2. **منبع جریان وابسته:** جریان آن به پارامترهای دیگر مدار وابسته است، مثل ولتاژ یا جریان در بخش‌های دیگر مدار.

---

### 2.4 نماد منبع جریان در مدار <a name="current-symbol"></a>

در نقشه‌های مدار، منبع جریان معمولاً با یک دایره و فلش داخل آن نمایش داده می‌شود که جهت جریان را مشخص می‌کند.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Current2.jpg" alt="نماد منبع جریان" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۴. نماد منبع جریان
</div>

---

### 2.5 اهمیت منبع جریان <a name="current-importance"></a>

در مدارهای الکترونیکی، بعضی وسایل مانند LEDها یا تقویت‌کننده‌ها نیاز به جریان ثابت دارند تا درست کار کنند.  
منبع جریان تضمین می‌کند که این جریان همیشه تأمین شود، حتی اگر مقاومت مدار تغییر کند.

---

## 3. مقاومت (Resistor) <a name="resistor"></a>

### 3.1 مقاومت چیست؟ <a name="what-is-resistor"></a>

مقاومت یکی از ساده‌ترین و مهم‌ترین قطعات در مدارهای الکتریکی است.  
اما واقعاً «مقاومت» یعنی چه؟   

برای درک بهتر، تصور کن **برق مثل آب داخل لوله‌ها جریان دارد.**  

حالا دو تا لوله داریم:  
- یکی دیواره‌های **صاف و صیقلی** دارد،  
- دیگری **زبر و خشن** است.  

به نظرت آب از کدام راحت‌تر عبور می‌کند؟  
درسته! از لولهٔ صاف  

پس لولهٔ زبر در برابر حرکت آب **مقاومت بیشتری** دارد.  
در مدار الکتریکی هم همین اتفاق می‌افتد.  

الکترون‌ها (ذرات کوچکی که جریان برق را می‌سازند)  
وقتی از یک سیم عبور می‌کنند، با مانعی روبه‌رو می‌شوند.  
به این مانع می‌گوییم **مقاومت الکتریکی**.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Image1.jpg" alt="تشبیه جریان برق با حرکت آب در لوله‌ها" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۵. تشبیه جریان برق با حرکت آب در لوله‌ها
</div>

---

### 3.2 چگونه جریان برق حرکت می‌کند؟ <a name="how-electric-current-flows"></a>

در مدار الکتریکی، چیزی به نام **ولتاژ (Voltage)** وجود دارد.  
ولتاژ مثل فشار آب است که باعث می‌شود الکترون‌ها حرکت کنند.  
وقتی الکترون‌ها حرکت می‌کنند، **جریان الکتریکی (Current)** به‌وجود می‌آید.  
پس ولتاژ، الکترون‌ها را هل می‌دهد و جریان ایجاد می‌شود.  

اما اگر مسیر باریک یا سخت باشد، حرکت کند می‌شود.  
این همان **مقاومت** است که جلوی حرکت زیاد جریان را می‌گیرد.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Image2.jpg" alt="رابطه بین ولتاژ، جریان و مقاومت" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۶. رابطه بین ولتاژ، جریان و مقاومت
</div>

---

### 3.3 مواد مختلف چه مقدار مقاومت دارند؟ <a name="resistance-of-different-materials"></a>

همه‌ی مواد مثل هم نیستند!  
بعضی مواد الکترون‌ها را راحت عبور می‌دهند،  
و بعضی دیگر تقریباً اجازه عبور نمی‌دهند.  

| نوع ماده | ویژگی | مثال |
|-----------|--------|------|
| **هادی (Conductor)** | جریان را راحت عبور می‌دهد | فلزات مثل مس و آلومینیوم |
| **عایق (Insulator)** | جلوی عبور جریان را می‌گیرد | پلاستیک، شیشه |
| **نیمه‌هادی (Semiconductor)** | بین این دو حالت است | سیلیکون |

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Image3.jpg" alt="مواد رسانا، عایق و نیمه‌هادی" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۷. مقایسه مواد رسانا، عایق و نیمه‌هادی
</div>

---

### 3.4 کاربرد مقاومت در مدار چیست؟ <a name="applications-of-resistor"></a>

در مدار، اگر جریان خیلی زیاد شود، ممکن است قطعات بسوزند.  
برای همین از **مقاومت‌ها (Resistors)** استفاده می‌کنیم.  

مقاومت‌ها مثل **شیر آب** هستند که مقدار عبور آب را کنترل می‌کنند.  
آن‌ها کمک می‌کنند جریان به اندازه‌ی مناسب از مدار عبور کند.  

---

### 3.5 چطور مقدار مقاومت را بفهمیم؟ <a name="how-to-measure-resistance"></a>

روی بیشتر مقاومت‌ها چند **نوار رنگی** وجود دارد.  
هر رنگ معنی خاصی دارد و مقدار مقاومت را مشخص می‌کند.  
آخرین نوار، **دقت** مقاومت را نشان می‌دهد (مثلاً ±۵٪).  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Image4.jpg" alt="مقاومت رنگی" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۸. مقاومت رنگی و نوارهای آن
</div>

---

### 3.6 مقاومت در مدار <a name="resistor-in-circuit"></a>

وقتی مقاومت را در **مدارهای الکتریکی** رسم می‌کنیم،  
از یک **نماد مخصوص** استفاده می‌شود تا شکل واقعی قطعه را ساده‌تر نمایش دهد.  

نماد مقاومت معمولاً به صورت یک **خط زیگزاگ** یا **مستطیل کوچک** کشیده می‌شود.  
در نقشه‌های مدار اروپایی معمولاً از مستطیل استفاده می‌کنند،  
اما در نقشه‌های آمریکایی از خط زیگزاگ.  

هر دو شکل درست هستند و فقط تفاوت در نوع استاندارد رسم است.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Image5.jpg" alt="نماد مقاومت در مدار" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۹. نماد مقاومت در مدار
</div>

واحد مقاومت **اهم (Ohm)** است که با نماد یونانی **Ω** (اُمگا) نشان داده می‌شود.  

اگر مقدار مقاومت زیاد باشد، برای راحتی از واحدهای بزرگ‌تر استفاده می‌کنیم:  

| واحد | نماد | مقدار |
|-------|------|--------|
| اهم | Ω | ۱ Ω |
| کیلو اهم | kΩ | ۱٬۰۰۰ Ω |
| مگا اهم | MΩ | ۱٬۰۰۰٬۰۰۰ Ω |

هرچه مقدار اهم بیشتر باشد، **عبور جریان سخت‌تر** می‌شود  
و هرچه کمتر باشد، **جریان راحت‌تر عبور می‌کند.**  

مثلاً مقاومت 100 Ω جریان بیشتری از 1 MΩ عبور می‌دهد.  

---

## 4. خازن (Capacitor) <a name="capacitor"></a>

### 4.1 خازن چیست؟ <a name="capacitor"></a>

خازن یکی از قطعات مهم در مدارهای الکتریکی است.  
کار اصلی آن **ذخیره و آزاد کردن انرژی الکتریکی برای مدت کوتاه** است.  

به زبان ساده، خازن مثل **یک ظرف کوچک برای نگه‌داشتن برق** است.  
وقتی به آن برق وصل می‌شود، پر از انرژی می‌شود (می‌گوییم شارژ شده است).  
وقتی مدار به انرژی نیاز دارد، خازن برق ذخیره‌شده را بیرون می‌دهد.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/1.jpg" alt="خازن و جریان شارژ/تخلیه" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۰. تصویر خازن و جریان شارژ/تخلیه
</div>

---

### 4.2 شارژ و تخلیه خازن <a name="charge-discharge"></a>

وقتی خازن را به باتری وصل می‌کنیم، مقداری از بارهای الکتریکی در یک طرف جمع می‌شوند و در طرف دیگر کمتر می‌شوند.  
در این حالت می‌گوییم خازن **شارژ شده** است.  

اگر مسیر جریان را باز کنیم، بارها دوباره برمی‌گردند و اختلاف بین دو طرف از بین می‌رود — یعنی **خازن تخلیه می‌شود**.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/2.jpg" alt="فرایند شارژ و تخلیه خازن" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۱. فرایند شارژ و تخلیه خازن
</div>

---

### 4.3 مثال ساده <a name="water-example"></a>

تصور کنید لوله‌ای دارید که وسط آن **تیغه‌ای نرم و انعطاف‌پذیر** قرار گرفته است.  
وقتی آب از یک طرف فشار می‌آورد، تیغه کشیده می‌شود و انرژی را در خودش نگه می‌دارد.  
وقتی فشار کم می‌شود، تیغه آب را به سمت دیگر برمی‌گرداند.  

خازن هم همین کار را با برق انجام می‌دهد:  
وقتی ولتاژ زیاد می‌شود، خازن انرژی را ذخیره می‌کند، و وقتی ولتاژ پایین می‌آید، انرژی را برمی‌گرداند.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/3.jpg" alt="مثال تیغه لاستیکی" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۲. مثال تیغه‌ی لاستیکی در لوله برای درک عملکرد خازن
</div>

---

### 4.4 رفتار خازن <a name="behavior"></a>

خازن‌ها در مدارها همیشه یک رفتار جالب دارند که بسته به نوع برق فرق می‌کند.  
در این بخش می‌خواهیم ببینیم وقتی برق مستقیم یا برق متناوب به خازن می‌دهیم، چه اتفاقی می‌افتد و چرا خازن در مدارها اینقدر مهم است.

#### 4.4.1 برق مستقیم (DC)
در این نوع برق، جریان همیشه در یک جهت حرکت می‌کند.  
خازن فقط در لحظه‌های اول که در حال شارژ است جریان را عبور می‌دهد.  
بعد از شارژ کامل، دیگر اجازه عبور نمی‌دهد.  
پس در برق مستقیم، خازن مثل **سد** عمل می‌کند.

#### 4.4.2 برق متناوب (AC)
در این نوع برق، جهت جریان مدام عوض می‌شود.  
به همین دلیل، خازن دائم در حال شارژ و تخلیه است و جریان می‌تواند از آن عبور کند.  
یعنی در برق متناوب، خازن مانند **دروازه‌ای نیمه‌باز** رفتار می‌کند.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/4.jpg" alt="رفتار خازن در جریان AC و DC" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۳. نمودار رفتار خازن در جریان AC و DC
</div>

---

### 4.5 اجزای اصلی خازن <a name="components"></a>

خازن از **سه بخش اصلی** تشکیل شده است:  

1. دو صفحه فلزی که بار الکتریکی را در خود نگه می‌دارند.  
2. یک لایهٔ نازک عایق (دی‌الکتریک) بین آن‌ها که اجازه عبور جریان نمی‌دهد.  
3. روکش خارجی که از آن محافظت می‌کند.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/5.jpg" alt="ساختار داخلی خازن" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۴. ساختار داخلی خازن
</div>

---

### 4.6 نحوه ساخت خازن <a name="construction"></a>

در بسیاری از خازن‌ها، دو ورق فلزی به‌همراه لایه‌ای از عایق به صورت **رول‌شده داخل یک استوانه** قرار می‌گیرند.  

اگر مادهٔ عایق نرم باشد → خازن می‌تواند برق بیشتری نگه دارد، اما ولتاژ زیادی را تحمل نمی‌کند.  
اگر مادهٔ عایق سخت باشد → ولتاژ بالا را تحمل می‌کند، ولی انرژی کمتری ذخیره می‌کند.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/6.jpg" alt="رول فلزی با دی‌الکتریک" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۵. رول فلزی با دی‌الکتریک
</div>

---

### 4.7 ظرفیت و ولتاژ خازن <a name="capacitance-voltage"></a>

**ظرفیت (Capacitance):**  
نشان می‌دهد خازن چقدر می‌تواند برق در خود نگه دارد.  
واحد آن «فاراد» (F) است، اما معمولاً از «میکروفاراد (µF)» یا «نانوفاراد (nF)» استفاده می‌شود.  

**ولتاژ کاری:**  
بیشترین مقدار ولتاژی است که خازن می‌تواند بدون آسیب‌دیدن تحمل کند.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/7.jpg" alt="ظرفیت و ولتاژ روی بدنه خازن" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۶. ظرفیت و ولتاژ روی بدنه خازن
</div>

---

### 4.8 کاربردهای خازن <a name="applications"></a>

خازن‌ها در مدارهای الکتریکی نقش‌های مختلف و مهمی دارند.  
در ادامه، به سه کاربرد اصلی آن‌ها می‌پردازیم:

#### 4.8.1 صاف کردن برق
وقتی برق از منبع وارد مدار می‌شود، ممکن است جریان یا ولتاژ کمی بالا و پایین برود.  
خازن مانند یک «بالشتک» عمل می‌کند:  

- وقتی برق زیاد شد، خازن آن را نگه می‌دارد.  
- وقتی برق کم شد، خازن انرژی ذخیره‌شده را آزاد می‌کند.  

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/8.1.jpg" alt="خازن به عنوان بالشتک" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۷. خازن به عنوان بالشتک برای یکنواخت کردن برق
</div>

#### 4.8.2 کاهش نویز
گاهی در مدار، برق همراه با لرزش یا نویزهای کوچک است که می‌تواند کارکرد قطعات را خراب کند.  
خازن می‌تواند این اختلال‌ها را کاهش دهد.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/8.2.jpg" alt="خازن مانند صافی برای کاهش نویز" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۸. خازن مانند صافی برای کاهش نویز
</div>

#### 4.8.3  عبور تغییرات برق
گاهی می‌خواهیم فقط **تغییرات سریعِ برق** (مثل صدا یا اطلاعات) از یک نقطه عبور کند و **برق ثابت** وارد آن نشود.  
خازن برق ثابت را مسدود می‌کند ولی تغییرات سریع را عبور می‌دهد.

---

## 5 سلف (Inductor) <a name="inductor"></a>

### 5.1 سلف چیست؟ <a name="inductor"></a>

سلف یکی از قطعات جالب در مدارهای الکتریکی است.  
کار اصلی آن مقاومت در برابر تغییر ناگهانی جریان برق است.  
برای درک بهتر، تصور کن یک **شلنگ آب بلند** داری که چند دور دور خودش پیچیده شده است.  
وقتی آب را باز می‌کنی، آب بلافاصله بیرون نمی‌آید، چون باید تمام شلنگ پر شود.  
اما وقتی آب در جریان می‌افتد و ناگهان شیر را می‌بندی، هنوز کمی آب از شلنگ بیرون می‌ریزد!

سلف هم دقیقاً همین‌طور رفتار می‌کند:  
وقتی جریان برق ناگهان زیاد یا کم شود، سلف نمی‌گذارد به سرعت تغییر کند.  
انگار جریان را **آرام و کنترل‌شده** می‌کند.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.1.jpg" alt="شلنگ پیچیده‌شده" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۱۹. تصویری از شلنگ پیچیده‌شده
</div>

---

### 5.2 سلف و جریان برق <a name="inductor-and-electric-current"></a>

سلف معمولاً از **سیمی که چندین بار به دور خودش پیچیده شده** ساخته می‌شود.  
به همین دلیل به آن **سیم‌پیچ (Coil)** هم می‌گویند.  

ویژگی جالب سلف این است که:
- جریان **مستقیم (DC)** را به راحتی عبور می‌دهد.  
- اما جلوی جریان **متناوب (AC)** را تا حدی می‌گیرد.

این ویژگی دقیقاً **برعکس خازن** است!  
خازن جلوی جریان مستقیم را می‌گیرد ولی جریان متناوب را عبور می‌دهد.  
به همین خاطر، سلف و خازن دو قطعه‌ی **مکمل** در مدار هستند.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.2.jpg" alt="عبور جریان DC و مقاومت در برابر AC" style="width: 50%; height: 50%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۰. عبور جریان DC و مقاومت در برابر جریان AC توسط سلف
</div>

---

### 5.3 رفتار جادویی سیم‌پیچ <a name="magical-behavior-of-coil"></a>

وقتی جریان برق از یک سیم عبور می‌کند، اطراف آن مقداری نیرو به‌وجود می‌آید که به آن **میدان مغناطیسی** می‌گویند.
این میدان مغناطیسی همان چیزی است که در آهن‌ربا هم وجود دارد.
حالا تصور کن این سیم را چند بار دور خودش بپیچی، مثل فنر.
در این حالت، میدان‌های مغناطیسیِ کوچکی که اطراف هر حلقه به‌وجود می‌آید، روی هم جمع می‌شوند و یک میدان قوی‌تر درست می‌کنند.
به همین دلیل سلف‌ها را به شکل سیم‌پیچ می‌سازند.

این میدان مغناطیسی مثل یک **باتری موقت** عمل می‌کند؛ یعنی می‌تواند برای مدت کوتاهی انرژی را در خودش نگه دارد.
وقتی جریان قطع می‌شود، سلف این انرژی مغناطیسی را دوباره به مدار برمی‌گرداند — مثل فنری که وقتی فشارش می‌دهی، انرژی ذخیره می‌کند و بعد رها می‌شود.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.3.jpg" alt="سیم‌پیچ با خطوط میدان مغناطیسی" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۱. سیم‌پیچ با خطوط میدان مغناطیسی اطراف آن
</div>

---

### 5.4 چه چیزهایی روی قدرت سلف تأثیر دارند؟ <a name="factors-affecting-inductance"></a>

سلف مثل **فنر جادویی مغناطیسی** است، اما قدرتش به چند عامل بستگی دارد:

#### 5.4.1 فاصله بین پیچ‌ها
اگر حلقه‌های سیم‌پیچ به هم نزدیک‌تر باشند، میدان‌های مغناطیسی با هم ترکیب می‌شوند و قوی‌تر می‌شوند.  
اما اگر فاصله زیاد باشد، میدان‌ها از هم جدا می‌مانند و سلف ضعیف‌تر می‌شود.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.4.jpg" alt="مقایسه دو سیم‌پیچ" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۲. مقایسه دو سیم‌پیچ
</div>

#### 5.4.2 قطر سیم‌پیچ
هرچه سیم‌پیچ بزرگ‌تر باشد، میدان مغناطیسی اطرافش گسترده‌تر می‌شود و انرژی بیشتری ذخیره می‌کند.  
پس هرچه قطر سیم‌پیچ بیشتر باشد، **سلف قوی‌تر** است.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.5.jpg" alt="سیم‌پیچ با قطرهای مختلف" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۳. سیم‌پیچ با قطرهای مختلف
</div>

#### 5.4.3 تعداد دورهای سیم‌پیچ
هرچه **تعداد حلقه‌ها بیشتر** باشد، میدان‌های بیشتری روی هم جمع می‌شوند و قدرت سلف افزایش پیدا می‌کند.  
در واقع با اضافه کردن دورهای بیشتر، سلف مثل فنری قوی‌تر می‌شود.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.6.jpg" alt="سیم‌پیچ با تعداد دور مختلف" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۴. سیم‌پیچ با تعداد دور مختلف
</div>

#### 5.4.4 جنس هسته (مغز سلف)
اگر در وسط سیم‌پیچ از **هسته‌ی آهنی یا مغناطیسی** استفاده شود، میدان قوی‌تر می‌شود و سلف انرژی بیشتری ذخیره می‌کند.  
اما اگر وسطش خالی یا غیرمغناطیسی باشد، میدان ضعیف‌تر خواهد بود.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.7.jpg" alt="سیم پیچ با هسته آهنی" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۵. سیم پیچ با هسته آهنی
</div>

---

### 5.5 کاربردهای سلف <a name="applications-of-inductor"></a>

#### 5.5.1 تنظیم و انتخاب فرکانس
در رادیوها و تلویزیون‌ها، سلف کمک می‌کند فقط «ایستگاه دلخواه» را دریافت کنیم.  
با تغییر مقدار سلف و خازن، مدار طوری تنظیم می‌شود که فقط همان فرکانس تقویت شود.

**مثال:**  
مثل وقتی بین ایستگاه‌های مختلف رادیو، فقط یکی را انتخاب می‌کنی تا صدایش واضح پخش شود.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.9.jpg" alt="تنظیم فرکانس" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۶. تنظیم فرکانس
</div>

#### 5.5.2 تشخیص اجسام فلزی
در دستگاه‌های فلزیاب یا گیت‌های فروشگاه، سلف میدان مغناطیسی ایجاد می‌کند.  
وقتی فلز به آن نزدیک شود، میدان تغییر می‌کند و مدار متوجه حضور فلز می‌شود — بدون تماس!

**مثال:**  
مثل زمانی که از گیت فروشگاه رد می‌شوی و دستگاه وجود تگ فلزی را تشخیص می‌دهد.

<div style="display: flex; justify-content: center; align-items: center; gap: 10px;">
  <img src="./assets/circuiteffort/Images/Self.8.jpg" alt="فلزیاب" style="width: 40%; height: 40%; object-fit: contain;">
</div>
<div class="caption" style="text-align: center; margin-top: 8px;">
شکل ۲۷. فلزیاب
</div>

#### 5.5.3 صاف‌کردن جریان برق
وقتی جریان برق ناگهان زیاد یا کم می‌شود، سلف مثل یک «ذخیره‌کننده مغناطیسی» عمل می‌کند.  
اگر جریان زیاد شود، انرژی را در خود نگه می‌دارد و اگر کم شود، آن را پس می‌دهد تا جریان ثابت‌تر شود.

**مثال:**  
مثل زمانی که موج دریا بالا و پایین می‌رود، سلف مثل یک سد کوچک جلوی موج‌ها را می‌گیرد تا حرکت آرام‌تر شود.

---
## 6. نتیجه‌گیری
<a name="conclusion"></a>


در این کتابچه، با **پنج المان اصلی مدارهای الکتریکی** آشنا شدیم که هر کدام نقش ویژه‌ای در دنیای الکترونیک دارند:

- **منبع ولتاژ و جریان**: موتور محرکه‌ی هر مدار؛ بدون آن‌ها هیچ الکترونی حرکت نمی‌کند.
- **مقاومت**: کنترل‌کننده‌ی جریان، مانند شیر آب که از سوختن قطعات جلوگیری می‌کند.
- **خازن**: نگهدارنده‌ی موقت انرژی، صاف‌کننده‌ی نوسانات، و فیلترکننده‌ی نویز.
- **سلف**: نگهبان تعادل جریان، مقاوم در برابر تغییرات ناگهانی، و تنظیم‌کننده‌ی فرکانس.

این المان‌ها مانند **قطعات یک پازل** هستند که با هم ترکیب می‌شوند تا دستگاه‌های پیچیده‌ای مثل تلفن همراه، کامپیوتر، رادیو و حتی خودروهای برقی ساخته شوند.  
درک رفتار هر کدام، کلید طراحی مدارهای ایمن، کارآمد و هوشمند است.

> **یادت باشد**:  
> هر چراغی که روشن می‌شود، هر صدایی که از اسپیکر می‌آید، و هر سیگنالی که در شبکه منتقل می‌شود،  
> نتیجه‌ی همکاری هماهنگ همین المان‌های ساده است!


---
## 7. منابع
 <a name="references"></a>


1. [Electronics Tutorials – What is a Capacitor?](https://www.electronics-tutorials.ws/capacitor/cap_1.html)
2. [All About Circuits – Capacitors](https://www.allaboutcircuits.com/textbook/direct-current/chpt-13/capacitors/)
3. Seymour, A. F. *Basic Electronic Components – Instruction Manual.*  
4. https://www.geeksforgeeks.org/physics/real-life-applications-of-inductor/
5. https://www.allaboutcircuits.com/textbook/direct-current/chpt-2/resistors/
6. https://www.geeksforgeeks.org/electrical-engineering/current-source/
## راه‌های ارتباطی

<p align="center">
  <a href="mailto:raintdiana@gmail.com">
    <img src="https://img.shields.io/badge/Email-raintdiana%40gmail.com-EA4335?logo=gmail&logoColor=white&style=flat-square" />
  </a>
</p>