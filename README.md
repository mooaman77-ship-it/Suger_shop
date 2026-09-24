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

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sugar Shop</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&family=Pacifico&display=swap');
        
        body {
            font-family: 'Cairo', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fcf6f5;
            background-image: 
                url('https://www.transparenttextures.com/patterns/cupcake.png'),
                radial-gradient(circle at 10% 20%, rgba(255, 224, 230, 0.5) 0%, transparent 20%),
                radial-gradient(circle at 90% 80%, rgba(255, 200, 210, 0.5) 0%, transparent 20%);
        }

        header {
            background-color: #fff0f3;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid #ffccd5;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        .logo {
            font-family: 'Pacifico', cursive;
            font-size: 36px;
            color: #d1526d;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
            position: relative;
            transform: rotate(-3deg);
        }

        .logo::after {
            content: 'Premium Quality';
            font-family: 'Cairo', sans-serif;
            font-size: 12px;
            color: #888;
            position: absolute;
            bottom: -15px;
            right: 0;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .contact-info {
            font-size: 18px;
            font-weight: bold;
            color: #d1526d;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(rgba(255, 240, 243, 0.8), rgba(255, 240, 243, 0.8)), url('https://img.freepik.com/free-photo/assortment-delicious-macarons_23-2148767986.jpg?t=st=1715850937~exp=1715854537~hmac=8e5b4b1a7d6e5d9a9b1c2d3e4f5a6b7c8d9e0f1a2b3c4d5e6f7a8b9c0d1e2f3g') no-repeat center center/cover;
            border-radius: 0 0 50px 50px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }

        .hero h1 {
            color: #d1526d;
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            color: #555;
            font-size: 20px;
            margin-bottom: 40px;
        }

        .order-btn {
            background-color: #d1526d;
            color: white;
            padding: 15px 40px;
            border: none;
            border-radius: 30px;
            font-size: 20px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(209, 82, 109, 0.4);
        }

        .order-btn:hover {
            background-color: #b84059;
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(209, 82, 109, 0.6);
        }

        /* المودال الخاص بالطلب */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }

        .modal-content {
            background-color: white;
            padding: 40px;
            border-radius: 20px;
            width: 90%;
            max-width: 500px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            position: relative;
        }

        .modal-content h2 {
            color: #d1526d;
            margin-bottom: 20px;
            text-align: center;
        }

        .form-group {
            margin-bottom: 20px;
