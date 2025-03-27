<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ساعدوا أمير ليبدأ حياة جديدة</title>
    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #3498db;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Tajawal', sans-serif;
        }
        
        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 2rem 0;
            text-align: center;
            border-radius: 0 0 20px 20px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        .header-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .main-image {
            width: 100%;
            height: 400px;
            object-fit: cover;
            border-radius: 10px;
            margin: 2rem 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .story-section {
            background-color: white;
            padding: 2rem;
            border-radius: 10px;
            margin: 2rem 0;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .quote {
            font-style: italic;
            color: var(--secondary);
            border-right: 3px solid var(--accent);
            padding-right: 1rem;
            margin: 1.5rem 0;
        }
        
        .donation-section {
            background-color: var(--accent);
            color: white;
            padding: 2rem;
            border-radius: 10px;
            text-align: center;
            margin: 2rem 0;
        }
        
        .donation-options {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1rem;
            margin: 2rem 0;
        }
        
        .donation-amount {
            background-color: white;
            color: var(--dark);
            padding: 1rem 2rem;
            border-radius: 50px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            border: 2px solid transparent;
        }
        
        .donation-amount:hover {
            background-color: var(--secondary);
            color: white;
            transform: translateY(-3px);
        }
        
        .donation-amount.selected {
            background-color: var(--secondary);
            color: white;
            border-color: white;
        }
        
        .custom-amount {
            display: flex;
            justify-content: center;
            margin: 1rem 0;
        }
        
        .custom-amount input {
            padding: 0.8rem 1rem;
            border: 2px solid #ddd;
            border-radius: 50px 0 0 50px;
            width: 200px;
            font-size: 1rem;
        }
        
        .custom-amount button {
            background-color: var(--secondary);
            color: white;
            border: none;
            padding: 0 1.5rem;
            border-radius: 0 50px 50px 0;
            cursor: pointer;
            font-weight: bold;
        }
        
        .btn-donate {
            display: inline-block;
            background-color: white;
            color: var(--accent);
            padding: 1rem 3rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            margin-top: 1rem;
            transition: all 0.3s;
        }
        
        .btn-donate:hover {
            background-color: var(--dark);
            color: white;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .progress-container {
            background-color: #ddd;
            border-radius: 50px;
            height: 20px;
            margin: 2rem 0;
            overflow: hidden;
        }
        
        .progress-bar {
            background-color: var(--secondary);
            height: 100%;
            width: 35%;
            transition: width 0.5s ease;
        }
        
        .progress-text {
            display: flex;
            justify-content: space-between;
            margin-top: 0.5rem;
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }
        
        .contact-info {
            margin-top: 1rem;
        }
        
        .contact-info a {
            color: var(--secondary);
            text-decoration: none;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            .donation-options {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <h1>ساعدوا أمير ليبدأ حياة جديدة</h1>
            <p class="subtitle">حملة جمع تبرعات لمساعدة أمير كشيدي على تحقيق حلم الزواج</p>
        </div>
    </header>
    
    <div class="container">
        <img src="https://i.imgur.com/AEFOnKy.jpg" alt="أمير كشيدي" class="main-image">
      
        <div class="story-section">
            <h2>قصة أمير</h2>
            <p>أمير كشيدي، رجل مكافح يبلغ من العمر 35 سنة، يعمل طباخًا في مدرسة ابتدائية، حيث يُحضّر وجبات لذيذة للأطفال بكل حب وعناية. رغم بساطة حياته، يحمل في قلبه حلمًا كبيرًا: تأسيس أسرة وبناء بيت مليء بالحب والاستقرار.</p>
            
            <p class="quote">"كل يوم أرى الأطفال يبتسمون عندما يتذوقون الطعام الذي أعدّه، وأتمنى أن يكون لي طفلاً أرى ابتسامته كل صباح"</p>
            
            <p>لكن الظروف المادية تشكل عائقًا أمام زواجه، إذ أن دخله المتواضع لا يكفي لتغطية تكاليف الزواج الأساسية. اليوم، نفتح باب الخير أمام كل من يستطيع المساهمة في تحقيق حلمه، فربّ درهم يسير يُحدث فرقًا كبيرًا في حياة إنسان!</p>
        </div>
        
        <div class="donation-section">
            <h2>كن جزءًا من تغيير حياة أمير</h2>
            <p>هدفنا جمع 50 مليون دينار جزائري</p>
            
            <div class="progress-container">
                <div class="progress-bar" style="width: 35%;"></div>
            </div>
            
            <div class="progress-text">
                <span>17,500,000 دينار</span>
                <span>35% من الهدف</span>
                <span>50,000,000 دينار</span>
            </div>
            
            <h3>اختر مبلغ التبرع:</h3>
            <div class="donation-options">
                <div class="donation-amount">100 ألف</div>
                <div class="donation-amount">200 ألف</div>
                <div class="donation-amount selected">500 ألف</div>
                <div class="donation-amount">1 مليون</div>
            </div>
            
            <div class="custom-amount">
                <input type="number" placeholder="المبلغ المطلوب">
                <button>تأكيد</button>
            </div>
            
            <a href="#" class="btn-donate">تبرع الآن</a>
        </div>
        
        <div class="story-section">
            <h2>كيف ستساعد تبرعاتكم؟</h2>
            <ul style="list-style-type: none; padding-right: 0;">
                <li style="margin-bottom: 1rem;">✓ مساعدة أمير على دفع المهر</li>
                <li style="margin-bottom: 1rem;">✓ شراء أساسيات المنزل</li>
                <li style="margin-bottom: 1rem;">✓ تكاليف حفل الزفاف البسيط</li>
                <li style="margin-bottom: 1rem;">✓ بداية حياة كريمة للعروسين</li>
            </ul>
            
            <p>كل تبرع مهما كان بسيطًا، هو خطوة نحو سعادة أمير وحياة جديدة يستحقها. كن جزءًا من هذه الفرحة، وساهم في رسم الابتسامة على وجهه.</p>
        </div>
    </div>
    
    <footer>
        <div class="container">
            <h3>للتواصل والمساهمة:</h3>
            <div class="contact-info">
                <p>الهاتف: <a href="tel:+213772656837">0772656837</a></p>
                <p>البريد الإلكتروني: <a href="mailto:helpamir@example.com">helpamir@example.com</a></p>
                <p>حساب البنك: البنك الجزائري | رقم الحساب: 1234567890</p>
            </div>
            
            <a href="https://www.facebook.com/profile.php?id=100037011190718" target="_blank" style="color: white; display: block; margin-top: 1rem;">زوروا صفحتي على فيسبوك</a>
            <p style="margin-top: 2rem;">© 2023 حملة مساعدة أمير. كل الحقوق محفوظة.</p>
        </div>
    </footer>
    
    <script>
        // JavaScript لإدارة التبرعات
        document.querySelectorAll('.donation-amount').forEach(button => {
            button.addEventListener('click', function() {
                document.querySelectorAll('.donation-amount').forEach(btn => {
                    btn.classList.remove('selected');
                });
                this.classList.add('selected');
            });
        });

        // إضافة تفاعل زر التبرع
        document.querySelector('.btn-donate').addEventListener('click', function(e) {
            e.preventDefault();
            alert('شكرًا لك على تبرعك! سيتم توجيهك إلى صفحة الدفع.');
            // هنا يمكنك إضافة رابط الدفع الفعلي
        });
    </script>
</body>
</html>
