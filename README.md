# Suger_shop
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر سكر للحلويات</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #d2691e;
            color: white;
            text-align: center;
            padding: 1.5rem;
        }
        h1 {
            margin: 0;
        }
        .container {
            width: 90%;
            max-width: 1000px;
            margin: 2rem auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }
        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            overflow: hidden;
            text-align: center;
        }
        .card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }
        .card-body {
            padding: 1rem;
        }
        .card-title {
            font-size: 1.25rem;
            margin-bottom: 0.5rem;
            color: #d2691e;
        }
        .btn {
            display: inline-block;
            background-color: #d2691e;
            color: white;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 0.5rem;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #eee;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>سُكّر للحلويات</h1>
        <p>أطيب وألذ الحلويات والمخبوزات الطازجة</p>
    </header>

    <div class="container">
        <!-- المنتج الأول -->
        <div class="card">
            <img src="28538.jpg" alt="كيك الكراميل بالحليب">
            <div class="card-body">
                <div class="card-title">كيك الكراميل بالحليب (التريليتشا)</div>
                <p>كيكة هشة مشربة بالحليب ومغطاة بطبقة كراميل لذيذة[span_3](start_span)[span_3](end_span).</p>
                <a href="#" class="btn">طلب الآن</a>
            </div>
        </div>

        <!-- المنتج الثاني -->
        <div class="card">
            <img src="28539.jpg" alt="كرات الشوكولاتة بجوز الهند">
            <div class="card-body">
                <div class="card-title">كرات الشوكولاتة بجوز الهند</div>
                <p>كرات الشوكولاتة الغنية المغطاة ببرش جوز الهند الناعم[span_4](start_span)[span_4](end_span).</p>
                <a href="#" class="btn">طلب الآن</a>
            </div>
        </div>

        <!-- المنتج الثالث -->
        <div class="card">
            <img src="28540.jpg" alt="تيراميسو الكلاسيكي">
            <div class="card-body">
                <div class="card-title">تيراميسو الكلاسيكي</div>
                <p>طبقات القهوة مع كريمة الماسكاربوني ورشة الكاكاو[span_5](start_span)[span_5](end_span).</p>
                <a href="#" class="btn">طلب الآن</a>
            </div>
        </div>
    </div>

    <footer>
        <p>جميع الحقوق محفوظة © سُكّر للحلويات</p>
    </footer>

</body>
</html>
