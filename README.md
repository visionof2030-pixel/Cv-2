<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الملف المهني | فهد الخالدي</title>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #1a365d;
            --primary-dark: #0f1f3d;
            --primary-light: #2d4a7f;
            --accent: #d4af37;
            --accent-dark: #b8941f;
            --accent-light: #e6c967;
            --bg: #f8f9fa;
            --card-bg: #ffffff;
            --text: #2d3748;
            --light-text: #718096;
            --border: #e2e8f0;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            --shadow-hover: 0 10px 15px rgba(0, 0, 0, 0.1);
            --gold-gradient: linear-gradient(135deg, #d4af37, #f7ef8a);
            --blue-gradient: linear-gradient(135deg, #1a365d, #2d4a7f);
        }

        * {
            box-sizing: border-box;
            font-family: 'Tajawal', Tahoma, Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        body {
            background: var(--bg);
            color: var(--text);
            line-height: 1.7;
            overflow-x: hidden;
            padding-top: 60px; /* مساحة أقل للهيدر المصغر */
        }

        /* ========== HEADER REDESIGN ========== */
        header {
            background: var(--blue-gradient);
            color: white;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            box-shadow: 0 2px 20px rgba(0, 0, 0, 0.15);
            border-bottom: 3px solid var(--accent);
            height: 87px; /* تصغير ارتفاع الهيدر */
        }

        .header-container {
            max-width: 100%;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            padding: 0;
            height: 100%;
        }

        .header-top {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            height: 60px; /* تصغير ارتفاع القسم العلوي */
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
        }

        .logo-section {
            display: flex;
            align-items: center;
            gap: 15px;
            flex: 1;
            justify-content: center; /* توسيط العنوان */
        }

        .title-section {
            text-align: center;
        }

        .title-section h1 {
            font-size: 1.3rem; /* تصغير حجم الخط */
            font-weight: 800;
            margin: 0;
            background: var(--gold-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        /* زر الترجمة في أقصى الزاوية اليسرى العلوية */
        .header-actions {
            position: absolute;
            left: 15px; /* نقل إلى أقصى الزاوية اليسرى */
            top: 10px; /* نقل إلى أعلى الزاوية */
        }

        .lang-btn {
            background: rgba(255, 255, 255, 0.15);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.2);
            padding: 5px 10px; /* تصغير الزر أكثر */
            border-radius: 6px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 6px;
            backdrop-filter: blur(10px);
            font-size: 0.75rem; /* تصغير حجم الخط */
        }

        .lang-btn:hover {
            background: rgba(255, 255, 255, 0.25);
            transform: translateY(-2px);
        }

        /* ========== NAVIGATION BAR ========== */
        .nav-container {
            position: relative;
            overflow: hidden;
            background: rgba(0, 0, 0, 0.1);
            height: 40px; /* تصغير ارتفاع شريط التنقل */
        }

        .nav-scroll {
            display: flex;
            gap: 0;
            padding: 0 10px;
            overflow-x: auto;
            scroll-behavior: smooth;
            -webkit-overflow-scrolling: touch;
            scrollbar-width: none; /* Firefox */
            -ms-overflow-style: none; /* IE and Edge */
            height: 100%;
        }

        .nav-scroll::-webkit-scrollbar {
            display: none; /* Chrome, Safari and Opera */
        }

        .nav-item {
            flex: 0 0 auto;
            padding: 8px 12px; /* تصغير الحشوة */
            text-decoration: none;
            color: white;
            font-weight: 600;
            font-size: 0.65rem; /* تصغير حجم الخط */
            transition: all 0.3s ease;
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 4px; /* تقليل المسافة بين الأيقونة والنص */
            min-width: 60px; /* تصغير العرض الأدنى */
            border-left: 1px solid rgba(255, 255, 255, 0.1);
            height: 100%;
            justify-content: center;
        }

        .nav-item:last-child {
            border-left: none;
        }

        .nav-item i {
            font-size: 0.7rem; /* تصغير حجم الأيقونات */
            transition: all 0.3s ease;
        }

        .nav-item:hover {
            background: rgba(255, 255, 255, 0.1);
        }

        .nav-item:hover i {
            transform: translateY(-3px);
        }

        .nav-item.active {
            background: var(--gold-gradient);
            color: var(--primary-dark);
            box-shadow: 0 -3px 10px rgba(212, 175, 55, 0.3);
        }

        .nav-item.active::before {
            content: "";
            position: absolute;
            bottom: 0;
            right: 50%;
            transform: translateX(50%);
            width: 25px; /* تصغير العرض */
            height: 2px; /* تصغير الارتفاع */
            background: var(--accent-dark);
            border-radius: 2px;
        }

        .nav-scroll-controls {
            position: absolute;
            top: 0;
            bottom: 0;
            width: 30px; /* تصغير عرض عناصر التحكم */
            display: flex;
            align-items: center;
            justify-content: center;
            background: rgba(0, 0, 0, 0.3);
            cursor: pointer;
            z-index: 2;
            transition: all 0.3s ease;
            opacity: 0;
        }

        .nav-scroll-controls:hover {
            background: rgba(0, 0, 0, 0.5);
        }

        .nav-container:hover .nav-scroll-controls {
            opacity: 1;
        }

        .nav-scroll-prev {
            right: 0;
        }

        .nav-scroll-next {
            left: 0;
        }

        .nav-scroll-controls i {
            color: white;
            font-size: 1rem; /* تصغير حجم الأيقونات */
        }

        /* ========== MAIN CONTENT ========== */
        main {
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
        }

        .hero-section {
            background: var(--blue-gradient);
            color: white;
            border-radius: 20px;
            padding: 30px; /* تقليل الحشوة */
            margin-bottom: 30px;
            text-align: center;
            position: relative;
            overflow: hidden;
            box-shadow: var(--shadow-hover);
        }

        .hero-section::before {
            content: "";
            position: absolute;
            top: 0;
            right: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 L100,0 L100,100 Z" fill="rgba(255,255,255,0.05)"/></svg>');
            background-size: cover;
        }

        .hero-content {
            position: relative;
            z-index: 1;
        }

        .hero-title {
            font-size: 2rem; /* تصغير حجم الخط */
            font-weight: 800;
            margin-bottom: 12px;
            background: var(--gold-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero-subtitle {
            font-size: 1rem; /* تصغير حجم الخط */
            margin-bottom: 20px;
            opacity: 0.9;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .hero-stats {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 25px;
        }

        .hero-stat {
            text-align: center;
        }

        .hero-stat .number {
            font-size: 1.6rem; /* تصغير حجم الخط */
            font-weight: 800;
            display: block;
            background: var(--gold-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero-stat .label {
            font-size: 0.8rem; /* تصغير حجم الخط */
            opacity: 0.8;
        }

        /* Sections */
        section {
            display: none;
            animation: fadeInUp 0.6s ease;
        }

        section.active {
            display: block;
        }

        .section-title {
            text-align: center;
            color: var(--primary);
            margin-bottom: 25px;
            font-size: 1.8rem; /* تصغير حجم الخط */
            font-weight: 800;
            position: relative;
            padding-bottom: 12px;
        }

        .section-title::after {
            content: "";
            position: absolute;
            bottom: 0;
            right: 50%;
            transform: translateX(50%);
            width: 70px; /* تصغير العرض */
            height: 3px; /* تصغير الارتفاع */
            background: var(--gold-gradient);
            border-radius: 2px;
        }

        /* Cards */
        .card {
            background: var(--card-bg);
            border-radius: 15px;
            padding: 25px; /* تقليل الحشوة */
            margin-bottom: 25px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            border-right: 4px solid transparent;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
            border-right-color: var(--accent);
        }

        /* Profile Section */
        .profile-header {
            text-align: center;
            margin-bottom: 25px;
        }

        .profile-img {
            width: 130px; /* تصغير حجم الصورة */
            height: 130px; /* تصغير حجم الصورة */
            margin: 0 auto 15px;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid var(--accent); /* تصغير الحدود */
            box-shadow: 0 6px 15px rgba(212, 175, 55, 0.3);
        }

        .profile-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .profile-info h2 {
            font-size: 1.3rem; /* تصغير حجم الخط */
            color: var(--primary);
            margin-bottom: 5px;
        }

        .profile-info .title {
            font-size: 0.9rem; /* تصغير حجم الخط */
            color: var(--accent-dark);
            font-weight: 700;
            margin-bottom: 12px;
        }

        .bio {
            text-align: justify;
            font-size: 0.9rem; /* تصغير حجم الخط */
            line-height: 1.7;
            color: var(--text);
            margin: 15px 0;
        }

        .badge {
            display: inline-block;
            background: var(--gold-gradient);
            color: var(--primary-dark);
            padding: 8px 16px; /* تصغير الحشوة */
            border-radius: 20px;
            font-weight: 700;
            margin: 12px 0;
            box-shadow: 0 3px 8px rgba(212, 175, 55, 0.3);
            font-size: 0.85rem; /* تصغير حجم الخط */
        }

        /* Stats Grid */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 15px;
            margin-top: 25px;
        }

        .stat-card {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 15px; /* تقليل الحشوة */
            border-radius: 10px;
            text-align: center;
            transition: all 0.3s ease;
            border-top: 3px solid var(--accent); /* تصغير الحدود */
        }

        .stat-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .stat-number {
            font-size: 1.6rem; /* تصغير حجم الخط */
            font-weight: 800;
            color: var(--primary);
            display: block;
            margin-bottom: 5px;
        }

        .stat-label {
            font-size: 0.8rem; /* تصغير حجم الخط */
            color: var(--light-text);
            font-weight: 600;
        }

        /* Timeline */
        .timeline {
            position: relative;
            padding-right: 25px; /* تقليل الحشوة */
        }

        .timeline::before {
            content: "";
            position: absolute;
            right: 12px; /* تقليل المسافة */
            top: 0;
            bottom: 0;
            width: 2px; /* تصغير العرض */
            background: var(--gold-gradient);
            border-radius: 2px;
        }

        .timeline-item {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 15px; /* تقليل الحشوة */
            margin-bottom: 15px;
            position: relative;
            box-shadow: var(--shadow);
            border-right: 2px solid var(--accent); /* تصغير الحدود */
        }

        .timeline-item::before {
            content: "";
            position: absolute;
            right: -20px; /* تعديل المسافة */
            top: 20px;
            width: 10px; /* تصغير الحجم */
            height: 10px; /* تصغير الحجم */
            background: var(--accent);
            border-radius: 50%;
            box-shadow: 0 0 0 3px rgba(212, 175, 55, 0.2); /* تصغير الظل */
        }

        .timeline-date {
            color: var(--accent-dark);
            font-weight: 700;
            font-size: 0.8rem; /* تصغير حجم الخط */
            margin-bottom: 6px;
        }

        .timeline-content h3 {
            font-size: 0.9rem; /* تصغير حجم الخط */
            color: var(--primary);
            margin-bottom: 5px;
        }

        .timeline-content p {
            color: var(--light-text);
            font-size: 0.8rem; /* تصغير حجم الخط */
        }

        /* Skills */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
        }

        .skill-category {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 20px; /* تقليل الحشوة */
            border-radius: 10px;
            border-top: 3px solid var(--accent); /* تصغير الحدود */
        }

        .skill-category h3 {
            color: var(--primary);
            margin-bottom: 12px;
            font-size: 1.1rem; /* تصغير حجم الخط */
        }

        .skill-list {
            list-style: none;
            padding: 0;
        }

        .skill-list li {
            padding: 6px 0; /* تقليل الحشوة */
            border-bottom: 1px solid var(--border);
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.85rem; /* تصغير حجم الخط */
        }

        .skill-list li:last-child {
            border-bottom: none;
        }

        .skill-list li i {
            color: var(--accent);
            font-size: 0.8rem; /* تصغير حجم الأيقونة */
        }

        /* Achievements Section */
        .achievement-card {
            background: linear-gradient(135deg, #f0f9ff, #e0f2fe);
            border-right: 4px solid var(--accent); /* تصغير الحدود */
            padding: 25px; /* تقليل الحشوة */
            border-radius: 12px;
            margin-bottom: 20px;
            position: relative;
            overflow: hidden;
            box-shadow: var(--shadow);
        }

        .achievement-year {
            background: var(--accent);
            color: white;
            padding: 8px 16px; /* تصغير الحشوة */
            border-radius: 20px;
            font-weight: 700;
            display: inline-block;
            margin-bottom: 15px;
            font-size: 0.8rem; /* تصغير حجم الخط */
            box-shadow: 0 3px 8px rgba(212, 175, 55, 0.3);
        }

        .achievement-content p {
            line-height: 1.8;
            text-align: justify;
            font-size: 0.9rem; /* تصغير حجم الخط */
            color: var(--text);
            margin: 0;
        }

        /* Training Section */
        .training-card {
            background: linear-gradient(135deg, #f0f9ff, #e0f2fe);
            border-right: 4px solid var(--accent); /* تصغير الحدود */
            padding: 25px; /* تقليل الحشوة */
            border-radius: 12px;
            margin-bottom: 20px;
            box-shadow: var(--shadow);
        }

        .training-list {
            list-style: none;
            padding: 0;
        }

        .training-list li {
            padding: 8px 0; /* تقليل الحشوة */
            border-bottom: 1px solid var(--border);
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.85rem; /* تصغير حجم الخط */
        }

        .training-list li:last-child {
            border-bottom: none;
        }

        .training-list li i {
            color: var(--accent);
            font-size: 0.8rem; /* تصغير حجم الأيقونة */
        }

        /* Tech Section */
        .tech-card {
            background: linear-gradient(135deg, #f0f9ff, #e0f2fe);
            border-right: 4px solid var(--accent); /* تصغير الحدود */
            padding: 25px; /* تقليل الحشوة */
            border-radius: 12px;
            margin-bottom: 20px;
            box-shadow: var(--shadow);
        }

        /* Portfolio Section */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
        }

        .portfolio-item {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
        }

        .portfolio-item:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
        }

        .portfolio-item img {
            width: 100%;
            height: 160px; /* تصغير الارتفاع */
            object-fit: cover;
        }

        .portfolio-content {
            padding: 12px; /* تقليل الحشوة */
        }

        .portfolio-content h3 {
            color: var(--primary);
            margin-bottom: 6px;
            font-size: 1rem; /* تصغير حجم الخط */
        }

        .portfolio-content p {
            color: var(--light-text);
            font-size: 0.8rem; /* تصغير حجم الخط */
        }

        .project-link {
            display: inline-block;
            margin-top: 10px;
            color: var(--accent);
            text-decoration: none;
            font-weight: 600;
            font-size: 0.85rem;
            transition: all 0.3s ease;
        }

        .project-link:hover {
            color: var(--accent-dark);
            text-decoration: underline;
        }

        /* Testimonials Section */
        .testimonials-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
        }

        .testimonial-item {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 20px; /* تقليل الحشوة */
            border-radius: 10px;
            border-top: 3px solid var(--accent); /* تصغير الحدود */
            box-shadow: var(--shadow);
        }

        .testimonial-content {
            margin-bottom: 12px;
        }

        .testimonial-content p {
            font-style: italic;
            line-height: 1.6;
            color: var(--text);
            font-size: 0.9rem; /* تصغير حجم الخط */
        }

        .testimonial-author {
            text-align: left;
        }

        .testimonial-author strong {
            display: block;
            color: var(--primary);
            font-size: 0.9rem; /* تصغير حجم الخط */
        }

        .testimonial-author span {
            font-size: 0.8rem; /* تصغير حجم الخط */
            color: var(--light-text);
        }

        /* Footer */
        footer {
            background: var(--blue-gradient);
            color: white;
            text-align: center;
            padding: 25px 20px;
            margin-top: 40px;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
        }

        .footer-links {
            display: none; /* إخفاء روابط الفوتر */
        }

        .copyright {
            margin-top: 15px;
            opacity: 0.8;
            font-size: 0.85rem; /* تصغير حجم الخط */
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            body {
                padding-top: 55px; /* تقليل المسافة للهيدر المصغر */
            }
            
            .header-top {
                padding: 0 15px;
                height: 55px; /* تصغير أكثر للجوال */
            }
            
            .title-section h1 {
                font-size: 1.1rem; /* تصغير حجم الخط للجوال */
            }
            
            .nav-item {
                padding: 6px 10px; /* تصغير الحشوة للجوال */
                font-size: 0.55rem; /* تصغير حجم الخط للجوال */
                min-width: 55px; /* تصغير العرض الأدنى للجوال */
            }
            
            .nav-item i {
                font-size: 0.6rem; /* تصغير حجم الأيقونات للجوال */
            }
            
            .hero-section {
                padding: 20px 15px; /* تقليل الحشوة للجوال */
            }
            
            .hero-title {
                font-size: 1.5rem; /* تصغير حجم الخط للجوال */
            }
            
            .hero-subtitle {
                font-size: 0.9rem; /* تصغير حجم الخط للجوال */
            }
            
            .hero-stats {
                gap: 12px;
            }
            
            .hero-stat .number {
                font-size: 1.3rem; /* تصغير حجم الخط للجوال */
            }
            
            .section-title {
                font-size: 1.4rem; /* تصغير حجم الخط للجوال */
            }
            
            .card {
                padding: 15px; /* تقليل الحشوة للجوال */
            }
            
            .nav-scroll-controls {
                display: none; /* إخفاء عناصر التحكم على الجوال */
            }
            
            .header-actions {
                left: 10px; /* تعديل المسافة للجوال */
                top: 8px; /* تعديل المسافة للجوال */
            }
        }

        @media (max-width: 480px) {
            .header-top {
                flex-direction: row; /* الحفاظ على الاتجاه الأفقي */
                height: auto;
                padding: 8px 15px;
                gap: 10px;
            }
            
            .logo-section {
                margin-bottom: 0;
            }
            
            .hero-stats {
                flex-direction: column;
                gap: 12px;
            }
            
            .nav-item {
                min-width: 50px;
                padding: 5px 8px;
            }
            
            .nav-item span {
                font-size: 0.5rem;
            }
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <div class="header-top">
                <!-- زر الترجمة في أقصى الزاوية اليسرى العلوية -->
                <div class="header-actions">
                    <button class="lang-btn" id="langBtn">
                        <i class="fas fa-language"></i>
                        <span>EN</span>
                    </button>
                </div>
                
                <!-- العنوان الرئيسي فقط -->
                <div class="logo-section">
                    <div class="title-section">
                        <h1 id="pageTitle">فهد الخالدي</h1>
                    </div>
                </div>
            </div>
            
            <!-- شريط الأيقونات للتنقل -->
            <div class="nav-container">
                <div class="nav-scroll-controls nav-scroll-prev">
                    <i class="fas fa-chevron-right"></i>
                </div>
                
                <div class="nav-scroll" id="navScroll">
                    <a href="#about" class="nav-item active" data-section="about">
                        <i class="fas fa-user"></i>
                        <span id="navAbout">نبذة عني</span>
                    </a>
                    <a href="#experience" class="nav-item" data-section="experience">
                        <i class="fas fa-briefcase"></i>
                        <span id="navExp">الخبرات</span>
                    </a>
                    <a href="#achievements" class="nav-item" data-section="achievements">
                        <i class="fas fa-trophy"></i>
                        <span id="navAchievements">الإنجازات</span>
                    </a>
                    <a href="#skills" class="nav-item" data-section="skills">
                        <i class="fas fa-star"></i>
                        <span id="navSkills">المهارات</span>
                    </a>
                    <a href="#training" class="nav-item" data-section="training">
                        <i class="fas fa-graduation-cap"></i>
                        <span id="navTrain">الدورات</span>
                    </a>
                    <a href="#tech" class="nav-item" data-section="tech">
                        <i class="fas fa-code"></i>
                        <span id="navTech">التقنية</span>
                    </a>
                    <a href="#portfolio" class="nav-item" data-section="portfolio">
                        <i class="fas fa-laptop-code"></i>
                        <span id="navPortfolio">معرض الأعمال</span>
                    </a>
                    <a href="#contact" class="nav-item" data-section="contact">
                        <i class="fas fa-envelope"></i>
                        <span id="navContact">بيانات التواصل</span>
                    </a>
                </div>
                
                <div class="nav-scroll-controls nav-scroll-next">
                    <i class="fas fa-chevron-left"></i>
                </div>
            </div>
        </div>
    </header>

    <!-- باقي المحتوى يبقى كما هو -->
    <main>
        <!-- Hero Section -->
        <section class="hero-section">
            <div class="hero-content">
                <h1 class="hero-title" id="heroTitle">الملف المهني للمعلم فهد الخالدي</h1>
                <p class="hero-subtitle" id="heroSubtitle">معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة</p>
                
                <div class="hero-stats">
                    <div class="hero-stat">
                        <span class="number">14+</span>
                        <span class="label" id="heroStat1">سنوات خبرة</span>
                    </div>
                    <div class="hero-stat">
                        <span class="number">130+</span>
                        <span class="label" id="heroStat2">ساعة تدريب</span>
                    </div>
                    <div class="hero-stat">
                        <span class="number">3</span>
                        <span class="label" id="heroStat3">مدن تعليمية</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="active">
            <h2 class="section-title" id="aboutTitle">نبذة عني</h2>
            <div class="card">
                <div class="profile-header">
                    <div class="profile-img">
                        <img src="https://i.ibb.co/k66psVmZ/20220817-151032.jpg" alt="صورة فهد الخالدي">
                    </div>
                    <div class="profile-info">
                        <h2 id="name">فهد نغيمش حميد الخالدي</h2>
                        <div class="title" id="jobTitle">معلم متقدم – تخصص اللغة الإنجليزية</div>
                    </div>
                </div>

                <p class="bio" id="bioText">
                    أؤمن أن التعليم ليس مجرد نقل معرفة، بل رسالة سامية لصناعة الأثر وبناء الإنسان. أطمح إلى أن أكون جزءًا فاعلًا في تطوير التعليم بالمملكة من خلال توظيف التقنيات الحديثة، وصناعة بيئات تعلم محفزة، تعزز التفكير النقدي والإبداعي، وتبني الثقة لدى الطالب. نظرتي المستقبلية تقوم على التعلم المستمر، وتطوير المهارات المهنية، ومواكبة التحولات الرقمية بما يخدم مخرجات التعليم وجودته في إطار رؤية المملكة 2030.
                </p>

                <div class="badge" id="badge">🏆 حاصل على درجة 95 في التخصص</div>

                <div class="stats-grid">
                    <div class="stat-card">
                        <span class="stat-number">14+</span>
                        <span class="stat-label" id="stat1">سنوات خبرة</span>
                    </div>
                    <div class="stat-card">
                        <span class="stat-number">130+</span>
                        <span class="stat-label" id="stat2">ساعات تدريبية</span>
                    </div>
                    <div class="stat-card">
                        <span class="stat-number">3</span>
                        <span class="stat-label" id="stat3">مدن تعليمية</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Experience Section -->
        <section id="experience">
            <h2 class="section-title" id="experienceTitle">الخبرات المهنية</h2>
            <div class="card">
                <div class="timeline">
                    <div class="timeline-item">
                        <div class="timeline-date">2017 - الآن</div>
                        <div class="timeline-content">
                            <h3>معلم لغة إنجليزية – سعيد بن العاص</h3>
                            <p>مكة المكرمة</p>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-date">2015 - 2016</div>
                        <div class="timeline-content">
                            <h3>معلم لغة إنجليزية – ثانوية الأمير سعود بن عبدالمحسن</h3>
                            <p>الليث</p>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-date">2012 - 2014</div>
                        <div class="timeline-content">
                            <h3>معلم لغة إنجليزية – سعيد بن زيد</h3>
                            <p>عفيف</p>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-date">2011 - 2012</div>
                        <div class="timeline-content">
                            <h3>مترجم – وزارة الحج والعمرة</h3>
                            <p>مكة المكرمة</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Achievements Section -->
        <section id="achievements">
            <h2 class="section-title" id="achievementsTitle">الإنجازات</h2>
            <div class="card">
                <div class="achievement-card">
                    <div class="achievement-year">2022</div>
                    <div class="achievement-content">
                        <p id="achievementText">
                            في عام 2022 حصلتُ على ترقية إلى رتبة معلم متقدم بعد مسيرة مهنية امتدت لسنوات كمعلم ممارس، قدمت خلالها أداءً متميزًا أسهم في تطوير العملية التعليمية داخل المدرسة. جاءت هذه الترقية تقديرًا لجهودي في توظيف استراتيجيات تدريس حديثة تعزز مهارات التفكير النقدي والإبداعي لدى الطلاب، إضافة إلى قدرتي على تحليل نواتج التعلم وبناء خطط علاجية فردية أثمرت عن تحسين واضح في مستويات الطلاب.<br><br>

                            وقد عكست هذه الترقية ثقة الجهة التعليمية بمهاراتي المهنية، خصوصًا في مجال تصميم أنشطة مبتكرة تُدمج مهارات الفهم العميق، والعمل التعاوني، والتعليم الذاتي داخل البيئة الصفية. كما كانت اعترافًا بدوري في تطوير البرامج التربوية والأنشطة التعليمية قبل عام 2022، ومساهمتي في بناء بيئة صفية محفزة يشعر فيها الطلاب بالأمان والرغبة في المشاركة والتعلم.<br><br>

                            تعد هذه الترقية محطة مهمة في مسيرتي، لأنها لم تكن مجرد انتقال إلى مستوى وظيفي أعلى، بل كانت نتيجة تراكم خبرات وممارسات مهنية أثبتت أثرها على الطلاب وعلى منظومة التعليم داخل المدرسة. واليوم أواصل عملي كمعلم متقدم ملتزم بالتحسين المستمر، وتطبيق أفضل الممارسات التربوية، والمساهمة في رفع جودة التعليم وتحقيق نواتج تعلم أعلى.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2 class="section-title" id="skillsTitle">المهارات والكفاءات</h2>
            <div class="card">
                <div class="skills-container">
                    <div class="skill-category">
                        <h3>المهارات التعليمية</h3>
                        <ul class="skill-list">
                            <li><i class="fas fa-check"></i> إتقان اللغة الإنجليزية تحدثاً وكتابة</li>
                            <li><i class="fas fa-check"></i> تطوير خطط تدريس محفزة ومبتكرة</li>
                            <li><i class="fas fa-check"></i> إدارة الصفوف بفاعلية</li>
                            <li><i class="fas fa-check"></i> تشجيع التعلم الذاتي</li>
                        </ul>
                    </div>
                    <div class="skill-category">
                        <h3>المهارات التقنية</h3>
                        <ul class="skill-list">
                            <li><i class="fas fa-check"></i> استخدام أدوات القياس والتقويم الإلكترونية</li>
                            <li><i class="fas fa-check"></i> دمج التقنية في التعليم</li>
                            <li><i class="fas fa-check"></i> تصميم أنشطة تفاعلية</li>
                            <li><i class="fas fa-check"></i> تطوير اختبارات إلكترونية</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Training Section -->
        <section id="training">
            <h2 class="section-title" id="trainingTitle">الدورات التدريبية</h2>
            <div class="card">
                <div class="training-card">
                    <ul class="training-list" id="trainingList">
                        <li><i class="fas fa-certificate"></i> التفكير الناقد والإبداعي ودمجه في المواد الدراسية</li>
                        <li><i class="fas fa-certificate"></i> القياس والتقويم التربوي</li>
                        <li><i class="fas fa-certificate"></i> الاستراتيجية الحديثة في تدريس أساسيات اللغة الإنجليزية</li>
                        <li><i class="fas fa-certificate"></i> البيئة الصفية الجاذبة</li>
                        <li><i class="fas fa-certificate"></i> تحليل أداء الطلاب وتقديم التغذية الراجعة</li>
                        <li><i class="fas fa-certificate"></i> أساسيات الترجمة</li>
                        <li><i class="fas fa-certificate"></i> مهارات التعامل مع أدوات القياس والتقويم الإلكترونية</li>
                        <li><i class="fas fa-certificate"></i> التنمية المهنية لمعلمي اللغة الإنجليزية - المستوى الثالث</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio">
            <h2 class="section-title" id="portfolioTitle">معرض الأعمال</h2>
            <div class="card">
                <div class="portfolio-grid">
                    <!-- مشروع اختبار الرخصة المهنية التفاعلي -->
                    <div class="portfolio-item">
                        <img src="https://via.placeholder.com/300x180/3B82F6/FFFFFF?text=اختبار+الرخصة+المهنية" alt="اختبار الرخصة المهنية التفاعلي">
                        <div class="portfolio-content">
                            <h3>مشروع: اختبار الرخصة المهنية التفاعلي</h3>
                            <p>مشروع تعليمي رقمي يهدف إلى محاكاة اختبار الرخصة المهنية للمعلمين، من خلال تقديم أسئلة تفاعلية مبنية على المعايير المعتمدة، مع تغذية راجعة فورية توضح السبب العلمي لكل إجابة صحيحة أو خاطئة، بما يسهم في رفع كفاءة المتدربين وتعزيز جاهزيتهم للاختبار الرسمي.</p>
                            <a href="https://visionof2030-pixel.github.io/Professional-License-Exam/" class="project-link" target="_blank">عرض المشروع <i class="fas fa-external-link-alt"></i></a>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <img src="https://via.placeholder.com/300x180/10B981/FFFFFF?text=مواد+تعليمية" alt="مواد تعليمية">
                        <div class="portfolio-content">
                            <h3>مواد تعليمية</h3>
                            <p>تطوير محتوى تعليمي متميز ومتوافق مع المناهج</p>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <img src="https://via.placeholder.com/300x180/8B5CF6/FFFFFF?text=عروض+تقديمية" alt="عروض تقديمية">
                        <div class="portfolio-content">
                            <h3>عروض تقديمية</h3>
                            <p>تصميم عروض تفاعلية جذابة للطلاب</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials">
            <h2 class="section-title" id="testimonialsTitle">التوصيات</h2>
            <div class="card">
                <div class="testimonials-container">
                    <div class="testimonial-item">
                        <div class="testimonial-content">
                            <p>"المعلم فهد يتميز بالإبداع والابتكار في أساليب التدريس، وقد قدم إضافة حقيقية لفريق العمل"</p>
                        </div>
                        <div class="testimonial-author">
                            <strong>مدير المدرسة</strong>
                            <span>مدرسة سعيد بن العاص</span>
                        </div>
                    </div>
                    <div class="testimonial-item">
                        <div class="testimonial-content">
                            <p>"لقد أحدثت استراتيجياته التعليمية فرقاً ملحوظاً في أداء الطلاب وحبهم للغة الإنجليزية"</p>
                        </div>
                        <div class="testimonial-author">
                            <strong>منسق اللغة الإنجليزية</strong>
                            <span>إدارة التعليم</span>
                        </div>
                    </div>
                    <div class="testimonial-item">
                        <div class="testimonial-content">
                            <p>"تميزه في استخدام التقنية جعل عملية التعلم أكثر متعة وفعالية للطلاب"</p>
                        </div>
                        <div class="testimonial-author">
                            <strong>زملاء العمل</strong>
                            <span>فريق اللغة الإنجليزية</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Tech Section -->
        <section id="tech">
            <h2 class="section-title" id="techTitle">التقنية</h2>
            <div class="card">
                <div class="tech-card">
                    <p id="techText">
                        أتمتع بشغف كبير تجاه التقنية والتعليم الرقمي، وأواكب أحدث التطورات في مجال الذكاء الاصطناعي وتطبيقاته التعليمية. أمتلك خبرة عملية في تصميم وتطوير أنشطة تفاعلية واختبارات إلكترونية باستخدام HTML وCSS وJavaScript، مما يثري تجربة التعلم ويجعلها أكثر تفاعلية وجاذبية للطلاب. أستخدم أدوات الذكاء الاصطناعي في تحليل أداء الطلاب وتصميم خطط تعليمية مخصصة، كما أصمم محتوى رقميًا مبتكرًا يتناسب مع احتياجات التعلم الحديثة. أسعى دائمًا لدمج التقنية في العملية التعليمية بطرق إبداعية تواكب متطلبات العصر الرقمي وتخدم أهداف رؤية المملكة 2030.
                    </p>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2 class="section-title" id="contactTitle">تواصل معي</h2>
            <div class="card">
                <div style="text-align: center; padding: 25px;">
                    <h3 style="color: var(--primary); margin-bottom: 15px;">للتواصل</h3>
                    <div style="font-size: 1rem; line-height: 2; color: var(--text);">
                        <p><i class="fas fa-envelope" style="color: var(--accent);"></i> iFahadenglish@gmail.com</p>
                        <p><i class="fas fa-phone" style="color: var(--accent);"></i> +9665554449824</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-content">
            <h3>فهد الخالدي</h3>
            <p>معلم متخصص في اللغة الإنجليزية - تطوير التعليم من خلال التقنية والابتكار</p>
            
            <!-- تم إزالة روابط الفوتر -->
            
            <div class="copyright" id="footerText">
                © 2024 جميع الحقوق محفوظة - فهد الخالدي
            </div>
        </div>
    </footer>

    <script>
        // بيانات الترجمة
        const translations = {
            ar: {
                pageTitle: "فهد الخالدي",
                heroTitle: "الملف المهني للمعلم فهد الخالدي",
                heroSubtitle: "معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة",
                heroStat1: "سنوات خبرة",
                heroStat2: "ساعة تدريب",
                heroStat3: "مدن تعليمية",
                aboutTitle: "نبذة عني",
                experienceTitle: "الخبرات المهنية",
                achievementsTitle: "الإنجازات",
                skillsTitle: "المهارات والكفاءات",
                trainingTitle: "الدورات التدريبية",
                portfolioTitle: "معرض الأعمال",
                testimonialsTitle: "التوصيات",
                techTitle: "التقنية",
                contactTitle: "تواصل معي",
                name: "فهد نغيمش حميد الخالدي",
                jobTitle: "معلم متقدم – تخصص اللغة الإنجليزية",
                bioText: "أؤمن أن التعليم ليس مجرد نقل معرفة، بل رسالة سامية لصناعة الأثر وبناء الإنسان. أطمح إلى أن أكون جزءًا فاعلًا في تطوير التعليم بالمملكة من خلال توظيف التقنيات الحديثة، وصناعة بيئات تعلم محفزة، تعزز التفكير النقدي والإبداعي، وتبني الثقة لدى الطالب. نظرتي المستقبلية تقوم على التعلم المستمر، وتطوير المهارات المهنية، ومواكبة التحولات الرقمية بما يخدم مخرجات التعليم وجودته في إطار رؤية المملكة 2030.",
                badge: "🏆 حاصل على درجة 95 في التخصص",
                stat1: "سنوات خبرة",
                stat2: "ساعات تدريبية",
                stat3: "مدن تعليمية",
                achievementText: "في عام 2022 حصلتُ على ترقية إلى رتبة معلم متقدم بعد مسيرة مهنية امتدت لسنوات كمعلم ممارس، قدمت خلالها أداءً متميزًا أسهم في تطوير العملية التعليمية داخل المدرسة. جاءت هذه الترقية تقديرًا لجهودي في توظيف استراتيجيات تدريس حديثة تعزز مهارات التفكير النقدي والإبداعي لدى الطلاب، إضافة إلى قدرتي على تحليل نواتج التعلم وبناء خطط علاجية فردية أثمرت عن تحسين واضح في مستويات الطلاب.<br><br>وقد عكست هذه الترقية ثقة الجهة التعليمية بمهاراتي المهنية، خصوصًا في مجال تصميم أنشطة مبتكرة تُدمج مهارات الفهم العميق، والعمل التعاوني، والتعليم الذاتي داخل البيئة الصفية. كما كانت اعترافًا بدوري في تطوير البرامج التربوية والأنشطة التعليمية قبل عام 2022، ومساهمتي في بناء بيئة صفية محفزة يشعر فيها الطلاب بالأمان والرغبة في المشاركة والتعلم.<br><br>تعد هذه الترقية محطة مهمة في مسيرتي، لأنها لم تكن مجرد انتقال إلى مستوى وظيفي أعلى، بل كانت نتيجة تراكم خبرات وممارسات مهنية أثبتت أثرها على الطلاب وعلى منظومة التعليم داخل المدرسة. واليوم أواصل عملي كمعلم متقدم ملتزم بالتحسين المستمر، وتطبيق أفضل الممارسات التربوية، والمساهمة في رفع جودة التعليم وتحقيق نواتج تعلم أعلى.",
                techText: "أتمتع بشغف كبير تجاه التقنية والتعليم الرقمي، وأواكب أحدث التطورات في مجال الذكاء الاصطناعي وتطبيقاته التعليمية. أمتلك خبرة عملية في تصميم وتطوير أنشطة تفاعلية واختبارات إلكترونية باستخدام HTML وCSS وJavaScript، مما يثري تجربة التعلم ويجعلها أكثر تفاعلية وجاذبية للطلاب. أستخدم أدوات الذكاء الاصطناعي في تحليل أداء الطلاب وتصميم خطط تعليمية مخصصة، كما أصمم محتوى رقميًا مبتكرًا يتناسب مع احتياجات التعلم الحديثة. أسعى دائمًا لدمج التقنية في العملية التعليمية بطرق إبداعية تواكب متطلبات العصر الرقمي وتخدم أهداف رؤية المملكة 2030.",
                footerText: "© 2024 جميع الحقوق محفوظة - فهد الخالدي",
                // إضافة ترجمة نصوص الأيقونات
                navAbout: "نبذة عني",
                navExp: "الخبرات",
                navAchievements: "الإنجازات",
                navSkills: "المهارات",
                navTrain: "الدورات",
                navTech: "التقنية",
                navPortfolio: "معرض الأعمال",
                navContact: "بيانات التواصل"
            },
            en: {
                pageTitle: "Fahad AlKhaldi",
                heroTitle: "Professional Portfolio - Fahad AlKhaldi",
                heroSubtitle: "English Language Specialist with 14+ Years Experience in Modern Teaching Methods",
                heroStat1: "Years Experience",
                heroStat2: "Training Hours",
                heroStat3: "Education Cities",
                aboutTitle: "About Me",
                experienceTitle: "Professional Experience",
                achievementsTitle: "Achievements",
                skillsTitle: "Skills & Competencies",
                trainingTitle: "Training Courses",
                portfolioTitle: "Portfolio",
                testimonialsTitle: "Testimonials",
                techTitle: "Technology",
                contactTitle: "Contact Me",
                name: "Fahad Naghimish Humaid AlKhaldi",
                jobTitle: "Senior English Teacher",
                bioText: "I believe that education is not merely about transferring knowledge, but a noble mission to make an impact and build individuals. I aspire to be an active part in developing education in the Kingdom by employing modern technologies, creating stimulating learning environments that enhance critical and creative thinking, and building student confidence. My future vision is based on continuous learning, developing professional skills, and keeping pace with digital transformations that serve educational outcomes and quality within the framework of Saudi Vision 2030.",
                badge: "🏆 Achieved a score of 95 in specialization",
                stat1: "Years of Experience",
                stat2: "Training Hours",
                stat3: "Education Cities",
                achievementText: "In 2022, I was promoted to the rank of Senior Teacher after a professional career spanning years as a practicing teacher, during which I provided outstanding performance that contributed to the development of the educational process within the school. This promotion came in recognition of my efforts in employing modern teaching strategies that enhance students' critical and creative thinking skills, in addition to my ability to analyze learning outcomes and build individual remedial plans that resulted in a clear improvement in student levels.<br><br>This promotion reflected the educational authority's confidence in my professional skills, especially in designing innovative activities that integrate deep understanding skills, collaborative work, and self-learning within the classroom environment. It was also an acknowledgment of my role in developing educational programs and activities before 2022, and my contribution to building a stimulating classroom environment where students feel safe and eager to participate and learn.<br><br>This promotion is an important milestone in my career, as it was not just a transition to a higher functional level, but rather the result of accumulated experiences and professional practices that proved their impact on students and the educational system within the school. Today, I continue my work as a senior teacher committed to continuous improvement, applying the best educational practices, and contributing to raising the quality of education and achieving higher learning outcomes.",
                techText: "I have a great passion for technology and digital education, and I keep up with the latest developments in the field of artificial intelligence and its educational applications. I have practical experience in designing and developing interactive activities and electronic tests using HTML, CSS, and JavaScript, which enriches the learning experience and makes it more interactive and attractive for students. I use AI tools to analyze student performance and design customized educational plans, and I also design innovative digital content that suits modern learning needs. I always strive to integrate technology into the educational process in creative ways that keep pace with the requirements of the digital age and serve the goals of Saudi Vision 2030.",
                footerText: "© 2024 All Rights Reserved - Fahad AlKhaldi",
                // إضافة ترجمة نصوص الأيقونات
                navAbout: "About Me",
                navExp: "Experience",
                navAchievements: "Achievements",
                navSkills: "Skills",
                navTrain: "Training",
                navTech: "Technology",
                navPortfolio: "Portfolio",
                navContact: "Contact Info"
            }
        };

        let currentLang = 'ar';

        // عناصر DOM
        const langBtn = document.getElementById('langBtn');
        const pageTitle = document.getElementById('pageTitle');
        const heroTitle = document.getElementById('heroTitle');
        const heroSubtitle = document.getElementById('heroSubtitle');
        const heroStat1 = document.getElementById('heroStat1');
        const heroStat2 = document.getElementById('heroStat2');
        const heroStat3 = document.getElementById('heroStat3');
        const aboutTitle = document.getElementById('aboutTitle');
        const experienceTitle = document.getElementById('experienceTitle');
        const achievementsTitle = document.getElementById('achievementsTitle');
        const skillsTitle = document.getElementById('skillsTitle');
        const trainingTitle = document.getElementById('trainingTitle');
        const portfolioTitle = document.getElementById('portfolioTitle');
        const testimonialsTitle = document.getElementById('testimonialsTitle');
        const techTitle = document.getElementById('techTitle');
        const contactTitle = document.getElementById('contactTitle');
        const nameEl = document.getElementById('name');
        const jobTitle = document.getElementById('jobTitle');
        const bioText = document.getElementById('bioText');
        const badge = document.getElementById('badge');
        const stat1 = document.getElementById('stat1');
        const stat2 = document.getElementById('stat2');
        const stat3 = document.getElementById('stat3');
        const achievementText = document.getElementById('achievementText');
        const techText = document.getElementById('techText');
        const footerText = document.getElementById('footerText');
        const navScroll = document.getElementById('navScroll');
        const navScrollPrev = document.querySelector('.nav-scroll-prev');
        const navScrollNext = document.querySelector('.nav-scroll-next');
        
        // عناصر نصوص الأيقونات
        const navAbout = document.getElementById('navAbout');
        const navExp = document.getElementById('navExp');
        const navAchievements = document.getElementById('navAchievements');
        const navSkills = document.getElementById('navSkills');
        const navTrain = document.getElementById('navTrain');
        const navTech = document.getElementById('navTech');
        const navPortfolio = document.getElementById('navPortfolio');
        const navContact = document.getElementById('navContact');

        // وظيفة لتحميل اللغة
        function loadLanguage(lang) {
            const t = translations[lang];
            
            // تحديث النصوص الأساسية
            pageTitle.textContent = t.pageTitle;
            heroTitle.textContent = t.heroTitle;
            heroSubtitle.textContent = t.heroSubtitle;
            heroStat1.textContent = t.heroStat1;
            heroStat2.textContent = t.heroStat2;
            heroStat3.textContent = t.heroStat3;
            aboutTitle.textContent = t.aboutTitle;
            experienceTitle.textContent = t.experienceTitle;
            achievementsTitle.textContent = t.achievementsTitle;
            skillsTitle.textContent = t.skillsTitle;
            trainingTitle.textContent = t.trainingTitle;
            portfolioTitle.textContent = t.portfolioTitle;
            testimonialsTitle.textContent = t.testimonialsTitle;
            techTitle.textContent = t.techTitle;
            contactTitle.textContent = t.contactTitle;
            nameEl.textContent = t.name;
            jobTitle.textContent = t.jobTitle;
            bioText.textContent = t.bioText;
            badge.textContent = t.badge;
            stat1.textContent = t.stat1;
            stat2.textContent = t.stat2;
            stat3.textContent = t.stat3;
            achievementText.innerHTML = t.achievementText;
            techText.textContent = t.techText;
            footerText.textContent = t.footerText;
            
            // تحديث نصوص الأيقونات
            navAbout.textContent = t.navAbout;
            navExp.textContent = t.navExp;
            navAchievements.textContent = t.navAchievements;
            navSkills.textContent = t.navSkills;
            navTrain.textContent = t.navTrain;
            navTech.textContent = t.navTech;
            navPortfolio.textContent = t.navPortfolio;
            navContact.textContent = t.navContact;
            
            // تحديث اتجاه النص
            document.documentElement.dir = lang === 'ar' ? 'rtl' : 'ltr';
            document.documentElement.lang = lang;
        }

        // حدث تبديل اللغة
        langBtn.addEventListener('click', () => {
            currentLang = currentLang === 'ar' ? 'en' : 'ar';
            loadLanguage(currentLang);
            langBtn.innerHTML = currentLang === 'ar' ? 
                '<i class="fas fa-language"></i><span>EN</span>' : 
                '<i class="fas fa-language"></i><span>AR</span>';
        });

        // التنقل بين الأقسام
        document.querySelectorAll(".nav-item").forEach(link => {
            link.addEventListener('click', (e) => {
                e.preventDefault();
                
                // إزالة النشط من جميع الروابط
                document.querySelectorAll(".nav-item").forEach(n => n.classList.remove("active"));
                
                // إضافة النشط للرابط المحدد
                link.classList.add("active");
                
                // إخفاء جميع الأقسام
                document.querySelectorAll("section").forEach(s => s.classList.remove("active"));
                
                // إظهار القسم المحدد
                const targetSection = link.getAttribute('data-section');
                document.getElementById(targetSection).classList.add("active");
                
                // إضافة تأثير التمرير السلس
                window.scrollTo({ top: 0, behavior: 'smooth' });
            });
        });

        // التحكم في شريط التنقل
        navScrollPrev.addEventListener('click', () => {
            navScroll.scrollBy({ left: 200, behavior: 'smooth' });
        });

        navScrollNext.addEventListener('click', () => {
            navScroll.scrollBy({ left: -200, behavior: 'smooth' });
        });

        // التحميل الأولي
        loadLanguage(currentLang);
    </script>
</body>
</html>
