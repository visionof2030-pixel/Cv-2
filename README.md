<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الملف المهني | فهد الخالدي - معلم متخصص في اللغة الإنجليزية</title>
    <meta name="description" content="فهد الخالدي - معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة. اكتشف ملفي المهني وإنجازاتي التعليمية.">
    
    <!-- تحسينات SEO -->
    <meta property="og:title" content="فهد الخالدي - معلم متخصص في اللغة الإنجليزية">
    <meta property="og:description" content="معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة">
    <meta property="og:image" content="https://i.ibb.co/k66psVmZ/20220817-151032.jpg">
    <meta property="og:url" content="https://fahad-alkhaldi.com">
    <meta property="og:type" content="website">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="فهد الخالدي - معلم متخصص في اللغة الإنجليزية">
    <meta name="twitter:description" content="معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة">
    <meta name="twitter:image" content="https://i.ibb.co/k66psVmZ/20220817-151032.jpg">
    
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- PWA Manifest -->
    <link rel="manifest" href="manifest.json">
    <meta name="theme-color" content="#1A3A5F">
    
    <style>
        :root {
            /* الألوان المحدثة لتتناسب مع طقم النصر */
            --primary: #1A3A5F; /* أزرق كحلي بدلاً من الأزرق النصراوي */
            --primary-dark: #0F2A47;
            --primary-light: #2A4F7A;
            --accent: #F5D76E; /* أصفر باهت بدلاً من الأصفر النصراوي */
            --accent-dark: #E6C860;
            --accent-light: #FFE89D;
            --bg: #FFFFFF; /* خلفية بيضاء */
            --card-bg: #FFFFFF;
            --text: #1A1A1A;
            --light-text: #666666;
            --border: #E6E6E6;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            --shadow-hover: 0 10px 15px rgba(0, 0, 0, 0.1);
            /* تحديث التدرجات اللونية */
            --gradient: linear-gradient(135deg, #1A3A5F, #F5D76E);
            --gradient-dark: linear-gradient(135deg, #0F2A47, #E6C860);
            --gradient-light: linear-gradient(135deg, #2A4F7A, #FFE89D);
            --yellow-gradient: linear-gradient(135deg, #F5D76E, #FFE89D);
            --blue-gradient: linear-gradient(135deg, #1A3A5F, #2A4F7A);
        }

        /* أنماط الوضع الليلي */
        :root[data-theme="dark"] {
            --bg: #0A0A0A;
            --card-bg: #1A1A1A;
            --text: #F5F5F5;
            --light-text: #A0A0A0;
            --border: #333333;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            --shadow-hover: 0 10px 15px rgba(0, 0, 0, 0.4);
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
            padding-top: 87px;
            transition: background 0.3s ease, color 0.3s ease;
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
            height: 87px;
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
            height: 47px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
        }

        .logo-section {
            display: flex;
            align-items: center;
            gap: 15px;
            flex: 1;
            justify-content: center;
        }

        .title-section {
            text-align: center;
        }

        .title-section h1 {
            font-size: 1.5rem;
            font-weight: 800;
            margin: 0;
            background: var(--yellow-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        /* زر الترجمة والوضع الليلي في أقصى الزاوية اليمنى العلوية */
        .header-actions {
            position: absolute;
            right: 15px;
            top: 10px;
            display: flex;
            gap: 10px;
        }

        .lang-btn, .theme-btn {
            background: rgba(255, 255, 255, 0.15);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.2);
            padding: 5px 10px;
            border-radius: 6px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 6px;
            backdrop-filter: blur(10px);
            font-size: 0.75rem;
        }

        .lang-btn:hover, .theme-btn:hover {
            background: rgba(255, 255, 255, 0.25);
            transform: translateY(-2px);
        }

        /* ========== NAVIGATION BAR ========== */
        .nav-container {
            position: relative;
            overflow: hidden;
            background: linear-gradient(90deg, rgba(26, 58, 95, 0.9), rgba(42, 79, 122, 0.9));
            backdrop-filter: blur(10px);
            border-radius: 0 0 12px 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            height: 40px;
        }

        .nav-scroll {
            display: flex;
            gap: 0;
            padding: 0 15px;
            overflow-x: auto;
            scroll-behavior: smooth;
            -webkit-overflow-scrolling: touch;
            scrollbar-width: none;
            -ms-overflow-style: none;
            height: 100%;
        }

        .nav-scroll::-webkit-scrollbar {
            display: none;
        }

        .nav-item {
            flex: 0 0 auto;
            padding: 8px 12px;
            text-decoration: none;
            color: white;
            font-weight: 600;
            font-size: 0.65rem;
            transition: all 0.3s ease;
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 4px;
            min-width: 60px;
            border-left: 1px solid rgba(255, 255, 255, 0.15);
            border-radius: 8px 8px 0 0;
            margin: 0 2px;
            height: 100%;
            justify-content: center;
            background: rgba(255, 255, 255, 0.05);
        }

        .nav-item:first-child {
            border-radius: 0 8px 0 0;
        }

        .nav-item:last-child {
            border-radius: 8px 0 0 0;
            border-left: none;
        }

        .nav-item i {
            font-size: 0.7rem;
            transition: all 0.3s ease;
        }

        .nav-item:hover {
            background: rgba(255, 255, 255, 0.1);
            transform: translateY(-2px);
        }

        .nav-item:hover i {
            transform: translateY(-3px);
        }

        .nav-item.active {
            background: var(--yellow-gradient);
            color: var(--primary-dark);
            box-shadow: 0 -4px 8px rgba(245, 215, 110, 0.3);
            transform: translateY(-2px);
        }

        .nav-item.active::before {
            content: "";
            position: absolute;
            bottom: 0;
            right: 50%;
            transform: translateX(50%);
            width: 30px;
            height: 3px;
            background: var(--primary-dark);
            border-radius: 2px;
        }

        .nav-scroll-controls {
            position: absolute;
            top: 0;
            bottom: 0;
            width: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(5px);
            cursor: pointer;
            z-index: 2;
            transition: all 0.3s ease;
            opacity: 0;
            border-radius: 0 0 8px 8px;
        }

        .nav-scroll-controls:hover {
            background: rgba(255, 255, 255, 0.3);
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
            font-size: 1rem;
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
            padding: 30px;
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
            font-size: 2rem;
            font-weight: 800;
            margin-bottom: 12px;
            background: var(--yellow-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero-subtitle {
            font-size: 1rem;
            margin-bottom: 20px;
            opacity: 0.9;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .hero-actions {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 25px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 12px 25px;
            border-radius: 30px;
            font-weight: 700;
            text-decoration: none;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            font-size: 0.9rem;
        }

        .btn-primary {
            background: var(--yellow-gradient);
            color: var(--primary-dark);
            box-shadow: 0 4px 10px rgba(245, 215, 110, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(245, 215, 110, 0.4);
        }

        .btn-secondary {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.3);
            backdrop-filter: blur(10px);
        }

        .btn-secondary:hover {
            background: rgba(255, 255, 255, 0.3);
            transform: translateY(-3px);
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
            font-size: 1.6rem;
            font-weight: 800;
            display: block;
            background: var(--yellow-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .hero-stat .label {
            font-size: 0.8rem;
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
            font-size: 1.8rem;
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
            width: 70px;
            height: 3px;
            background: var(--yellow-gradient);
            border-radius: 2px;
        }

        /* تأثيرات الظهور عند التمرير */
        .fade-in-up {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.6s ease;
        }

        .fade-in-up.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Cards */
        .card {
            background: var(--card-bg);
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            border-right: 4px solid transparent;
            border: 1px solid var(--border);
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
            width: 130px;
            height: 130px;
            margin: 0 auto 15px;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid var(--accent);
            box-shadow: 0 6px 15px rgba(245, 215, 110, 0.3);
        }

        .profile-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .profile-info h2 {
            font-size: 1.3rem;
            color: var(--primary);
            margin-bottom: 5px;
        }

        .profile-info .title {
            font-size: 0.9rem;
            color: var(--accent-dark);
            font-weight: 700;
            margin-bottom: 12px;
        }

        .bio {
            text-align: justify;
            font-size: 0.9rem;
            line-height: 1.7;
            color: var(--text);
            margin: 15px 0;
        }

        .badge {
            display: inline-block;
            background: var(--yellow-gradient);
            color: var(--primary-dark);
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: 700;
            margin: 12px 0;
            box-shadow: 0 3px 8px rgba(245, 215, 110, 0.3);
            font-size: 0.85rem;
        }

        /* Stats Grid */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 15px;
            margin-top: 25px;
        }

        .stat-card {
            background: linear-gradient(135deg, var(--card-bg), var(--bg));
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            transition: all 0.3s ease;
            border-top: 3px solid var(--accent);
            border: 1px solid var(--border);
        }

        .stat-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .stat-number {
            font-size: 1.6rem;
            font-weight: 800;
            color: var(--primary);
            display: block;
            margin-bottom: 5px;
        }

        .stat-label {
            font-size: 0.8rem;
            color: var(--light-text);
            font-weight: 600;
        }

        /* Vision Section */
        .vision-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .vision-item {
            background: linear-gradient(135deg, var(--card-bg), var(--bg));
            padding: 25px;
            border-radius: 12px;
            text-align: center;
            border-top: 4px solid var(--accent);
            transition: all 0.3s ease;
            border: 1px solid var(--border);
        }

        .vision-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        }

        .vision-item i {
            font-size: 2.5rem;
            color: var(--accent);
            margin-bottom: 15px;
        }

        .vision-item h3 {
            color: var(--primary);
            margin-bottom: 12px;
            font-size: 1.2rem;
        }

        .vision-item p {
            color: var(--text);
            line-height: 1.6;
        }

        /* Timeline */
        .timeline {
            position: relative;
            padding-right: 25px;
        }

        .timeline::before {
            content: "";
            position: absolute;
            right: 12px;
            top: 0;
            bottom: 0;
            width: 2px;
            background: var(--yellow-gradient);
            border-radius: 2px;
        }

        .timeline-item {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            position: relative;
            box-shadow: var(--shadow);
            border-right: 2px solid var(--accent);
            border: 1px solid var(--border);
        }

        .timeline-item::before {
            content: "";
            position: absolute;
            right: -20px;
            top: 20px;
            width: 10px;
            height: 10px;
            background: var(--accent);
            border-radius: 50%;
            box-shadow: 0 0 0 3px rgba(245, 215, 110, 0.2);
        }

        .timeline-date {
            color: var(--accent-dark);
            font-weight: 700;
            font-size: 0.8rem;
            margin-bottom: 6px;
        }

        .timeline-content h3 {
            font-size: 0.9rem;
            color: var(--primary);
            margin-bottom: 5px;
        }

        .timeline-content p {
            color: var(--light-text);
            font-size: 0.8rem;
        }

        /* Skills */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
        }

        .skill-category {
            background: linear-gradient(135deg, var(--card-bg), var(--bg));
            padding: 20px;
            border-radius: 10px;
            border-top: 3px solid var(--accent);
            border: 1px solid var(--border);
        }

        .skill-category h3 {
            color: var(--primary);
            margin-bottom: 12px;
            font-size: 1.1rem;
        }

        .skill-list {
            list-style: none;
            padding: 0;
        }

        .skill-list li {
            padding: 6px 0;
            border-bottom: 1px solid var(--border);
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.85rem;
        }

        .skill-list li:last-child {
            border-bottom: none;
        }

        .skill-list li i {
            color: var(--accent);
            font-size: 0.8rem;
        }

        /* Achievements Section */
        .achievement-card {
            background: linear-gradient(135deg, var(--card-bg), var(--bg));
            border-right: 4px solid var(--accent);
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 20px;
            position: relative;
            overflow: hidden;
            box-shadow: var(--shadow);
            border: 1px solid var(--border);
        }

        .achievement-year {
            background: var(--accent);
            color: var(--primary-dark);
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: 700;
            display: inline-block;
            margin-bottom: 15px;
            font-size: 0.8rem;
            box-shadow: 0 3px 8px rgba(245, 215, 110, 0.3);
        }

        .achievement-content p {
            line-height: 1.8;
            text-align: justify;
            font-size: 0.9rem;
            color: var(--text);
            margin: 0;
        }

        /* Training Section */
        .training-card {
            background: linear-gradient(135deg, var(--card-bg), var(--bg));
            border-right: 4px solid var(--accent);
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 20px;
            box-shadow: var(--shadow);
            border: 1px solid var(--border);
        }

        .training-list {
            list-style: none;
            padding: 0;
        }

        .training-list li {
            padding: 8px 0;
            border-bottom: 1px solid var(--border);
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.85rem;
        }

        .training-list li:last-child {
            border-bottom: none;
        }

        .training-list li i {
            color: var(--accent);
            font-size: 0.8rem;
        }

        /* Tech Section */
        .tech-card {
            background: linear-gradient(135deg, var(--card-bg), var(--bg));
            border-right: 4px solid var(--accent);
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 20px;
            box-shadow: var(--shadow);
            border: 1px solid var(--border);
        }

        /* Portfolio Section */
        .portfolio-filters {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 25px;
            flex-wrap: wrap;
        }

        .filter-btn {
            background: var(--card-bg);
            border: 1px solid var(--border);
            padding: 8px 16px;
            border-radius: 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 600;
            font-size: 0.85rem;
        }

        .filter-btn:hover, .filter-btn.active {
            background: var(--yellow-gradient);
            color: var(--primary-dark);
            border-color: var(--accent);
        }

        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
        }

        .portfolio-item {
            background: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            border: 1px solid var(--border);
        }

        .portfolio-item:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
        }

        .portfolio-item img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .portfolio-item:hover img {
            transform: scale(1.05);
        }

        .portfolio-content {
            padding: 15px;
        }

        .portfolio-content h3 {
            color: var(--primary);
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        .portfolio-content p {
            color: var(--light-text);
            font-size: 0.9rem;
            line-height: 1.6;
            margin-bottom: 10px;
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

        .testimonial-slider {
            position: relative;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: var(--shadow);
        }

        .testimonial-slides {
            display: flex;
            transition: transform 0.5s ease;
        }

        .testimonial-slide {
            min-width: 100%;
            padding: 20px;
            background: linear-gradient(135deg, var(--card-bg), var(--bg));
            border-top: 3px solid var(--accent);
            box-shadow: var(--shadow);
            border-radius: 10px;
            border: 1px solid var(--border);
        }

        .testimonial-content {
            margin-bottom: 12px;
        }

        .testimonial-content p {
            font-style: italic;
            line-height: 1.6;
            color: var(--text);
            font-size: 0.9rem;
        }

        .testimonial-author {
            text-align: left;
        }

        .testimonial-author strong {
            display: block;
            color: var(--primary);
            font-size: 0.9rem;
        }

        .testimonial-author span {
            font-size: 0.8rem;
            color: var(--light-text);
        }

        .testimonial-controls {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 15px;
        }

        .testimonial-control {
            background: var(--card-bg);
            border: 1px solid var(--border);
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .testimonial-control:hover {
            background: var(--yellow-gradient);
            color: var(--primary-dark);
        }

        /* Contact Form */
        .form-group {
            margin-bottom: 20px;
        }

        .form-group input, .form-group textarea {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid var(--border);
            border-radius: 8px;
            background: var(--card-bg);
            color: var(--text);
            font-size: 0.9rem;
            transition: all 0.3s ease;
        }

        .form-group input:focus, .form-group textarea:focus {
            outline: none;
            border-color: var(--accent);
            box-shadow: 0 0 0 3px rgba(245, 215, 110, 0.2);
        }

        .form-group textarea {
            resize: vertical;
            min-height: 120px;
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
            display: none;
        }

        .copyright {
            margin-top: 15px;
            opacity: 0.8;
            font-size: 0.85rem;
        }

        /* أنماط إضافية للمعرض التفاعلي */
        .gallery-container {
            position: relative;
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
        }

        .gallery-scroll {
            display: flex;
            flex-direction: column;
            max-height: 500px;
            overflow-y: auto;
            scroll-behavior: smooth;
            padding: 10px;
            background: var(--card-bg);
            border-radius: 12px;
        }

        .gallery-scroll::-webkit-scrollbar {
            width: 8px;
        }

        .gallery-scroll::-webkit-scrollbar-track {
            background: var(--border);
            border-radius: 10px;
        }

        .gallery-scroll::-webkit-scrollbar-thumb {
            background: var(--accent);
            border-radius: 10px;
        }

        .gallery-scroll::-webkit-scrollbar-thumb:hover {
            background: var(--accent-dark);
        }

        .gallery-item {
            margin-bottom: 20px;
            text-align: center;
            background: var(--card-bg);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
            border: 1px solid var(--border);
        }

        .gallery-item:hover {
            transform: translateY(-5px);
        }

        .gallery-item img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .gallery-caption {
            margin-top: 10px;
            font-size: 0.9rem;
            color: var(--text);
            font-weight: 500;
        }

        .gallery-controls {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .gallery-btn {
            background: var(--yellow-gradient);
            color: var(--primary-dark);
            border: none;
            padding: 10px 20px;
            border-radius: 30px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 4px 8px rgba(245, 215, 110, 0.3);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .gallery-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(245, 215, 110, 0.4);
        }

        .gallery-btn:disabled {
            opacity: 0.5;
            cursor: not-allowed;
            transform: none;
        }

        .gallery-indicator {
            display: flex;
            justify-content: center;
            margin-top: 15px;
            gap: 8px;
        }

        .indicator-dot {
            width: 10px;
            height: 10px;
            border-radius: 50%;
            background: var(--border);
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .indicator-dot.active {
            background: var(--accent);
            transform: scale(1.2);
        }

        /* ========== التحسينات الجديدة ========== */
        
        /* زر العودة للأعلى */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            left: 30px;
            width: 50px;
            height: 50px;
            background: var(--yellow-gradient);
            color: var(--primary-dark);
            border: none;
            border-radius: 50%;
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
            z-index: 1000;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
        }

        .back-to-top.visible {
            opacity: 1;
            visibility: visible;
        }

        .back-to-top:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0,0,0,0.2);
        }

        /* مؤشر تقدم التمرير */
        .scroll-progress {
            position: fixed;
            top: 0;
            right: 0;
            width: 100%;
            height: 3px;
            background: transparent;
            z-index: 1001;
        }

        .scroll-progress-bar {
            height: 100%;
            width: 0%;
            background: var(--yellow-gradient);
            transition: width 0.1s ease;
        }

        /* تحسينات للصور (Lazy Loading) */
        img.lazy {
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        img.lazy.loaded {
            opacity: 1;
        }

        /* تحسينات للنموذج */
        .form-message {
            padding: 10px 15px;
            border-radius: 8px;
            margin-top: 15px;
            display: none;
        }

        .form-message.success {
            background: rgba(76, 175, 80, 0.1);
            border: 1px solid #4CAF50;
            color: #4CAF50;
            display: block;
        }

        .form-message.error {
            background: rgba(244, 67, 54, 0.1);
            border: 1px solid #F44336;
            color: #F44336;
            display: block;
        }

        .btn-loading {
            position: relative;
            pointer-events: none;
        }

        .btn-loading::after {
            content: "";
            position: absolute;
            width: 20px;
            height: 20px;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            margin: auto;
            border: 2px solid transparent;
            border-top-color: var(--primary-dark);
            border-radius: 50%;
            animation: button-loading-spinner 1s ease infinite;
        }

        @keyframes button-loading-spinner {
            from {
                transform: rotate(0turn);
            }
            to {
                transform: rotate(1turn);
            }
        }

        /* تحسينات للوضع الليلي - تحسين التباين */
        :root[data-theme="dark"] .card {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
        }

        :root[data-theme="dark"] .stat-card,
        :root[data-theme="dark"] .vision-item,
        :root[data-theme="dark"] .skill-category,
        :root[data-theme="dark"] .achievement-card,
        :root[data-theme="dark"] .training-card,
        :root[data-theme="dark"] .tech-card,
        :root[data-theme="dark"] .portfolio-item,
        :root[data-theme="dark"] .testimonial-slide,
        :root[data-theme="dark"] .gallery-item {
            background: linear-gradient(135deg, #1E1E1E, #2A2A2A);
        }

        /* ========== قسم الدورات التدريبية ========== */
        .certificates-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
        }

        .certificate-item {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            border: 1px solid var(--border);
            display: flex;
            flex-direction: column;
        }

        .certificate-item:hover {
            transform: translateY(-5px);
            box-shadow: var(--shadow-hover);
        }

        .certificate-img {
            height: 200px;
            overflow: hidden;
            position: relative;
        }

        .certificate-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .certificate-item:hover .certificate-img img {
            transform: scale(1.05);
        }

        .certificate-content {
            padding: 20px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
        }

        .certificate-content h3 {
            color: var(--primary);
            margin-bottom: 10px;
            font-size: 1.1rem;
        }

        .certificate-content p {
            color: var(--light-text);
            font-size: 0.9rem;
            line-height: 1.6;
            margin-bottom: 15px;
            flex-grow: 1;
        }

        .download-btn {
            margin-top: auto;
            text-align: center;
            padding: 10px 15px;
            font-size: 0.85rem;
        }

        /* معرض المشاركات */
        .participation-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .participation-img {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .participation-img img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.3s ease;
        }

        .participation-img:hover img {
            transform: scale(1.03);
        }

        /* تحسينات للتنقل على الجوال */
        @media (max-width: 768px) {
            body {
                padding-top: 82px;
            }
            
            .header-top {
                padding: 0 15px;
                height: 42px;
            }
            
            .title-section h1 {
                font-size: 1.3rem;
            }
            
            .nav-item {
                padding: 6px 10px;
                font-size: 0.55rem;
                min-width: 55px;
            }
            
            .nav-item i {
                font-size: 0.6rem;
            }
            
            .hero-section {
                padding: 20px 15px;
            }
            
            .hero-title {
                font-size: 1.5rem;
            }
            
            .hero-subtitle {
                font-size: 0.9rem;
            }
            
            .hero-actions {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 100%;
                max-width: 250px;
                justify-content: center;
            }
            
            .hero-stats {
                gap: 12px;
            }
            
            .hero-stat .number {
                font-size: 1.3rem;
            }
            
            .section-title {
                font-size: 1.4rem;
            }
            
            .card {
                padding: 15px;
            }
            
            .nav-scroll-controls {
                display: none;
            }
            
            .header-actions {
                right: 10px;
                top: 8px;
            }
            
            .gallery-container {
                max-height: 400px;
            }
            
            /* تحسينات إضافية للجوال */
            .back-to-top {
                bottom: 20px;
                left: 20px;
                width: 45px;
                height: 45px;
                font-size: 1rem;
            }
            
            .nav-scroll {
                padding: 0 10px;
            }
            
            .nav-item span {
                font-size: 0.5rem;
            }
            
            .certificates-grid {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            .header-top {
                flex-direction: row;
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
            
            .gallery-container {
                max-height: 350px;
            }
            
            .gallery-btn {
                padding: 8px 15px;
                font-size: 0.8rem;
            }
            
            .back-to-top {
                bottom: 15px;
                left: 15px;
                width: 40px;
                height: 40px;
            }
            
            .participation-gallery {
                grid-template-columns: 1fr;
            }
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

        /* تحسينات لقسم الدورات */
        .course-item {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: var(--shadow);
            border-right: 4px solid var(--accent);
            border: 1px solid var(--border);
            transition: all 0.3s ease;
        }

        .course-item:hover {
            transform: translateY(-3px);
            box-shadow: var(--shadow-hover);
        }

        .course-title {
            font-size: 1.1rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .course-emoji {
            font-size: 1.3rem;
        }

        .course-description {
            color: var(--text);
            line-height: 1.7;
            margin-bottom: 15px;
        }

        .course-impact {
            background: rgba(245, 215, 110, 0.1);
            border-right: 3px solid var(--accent);
            padding: 12px 15px;
            border-radius: 8px;
            font-style: italic;
            color: var(--light-text);
            line-height: 1.6;
        }

        .course-divider {
            height: 1px;
            background: linear-gradient(to right, transparent, var(--accent), transparent);
            margin: 25px 0;
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <div class="header-top">
                <!-- زر الترجمة والوضع الليلي في أقصى الزاوية اليمنى العلوية -->
                <div class="header-actions">
                    <button class="lang-btn" id="langBtn">
                        <i class="fas fa-language"></i>
                        <span id="langText">EN</span>
                    </button>
                    <button class="theme-btn" id="themeBtn">
                        <i class="fas fa-moon"></i>
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
                    <a href="#vision" class="nav-item" data-section="vision">
                        <i class="fas fa-eye"></i>
                        <span id="navVision">الرؤية التعليمية</span>
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
                    <a href="#certificates" class="nav-item" data-section="certificates">
                        <i class="fas fa-certificate"></i>
                        <span id="navCertificates">شهاداتي</span>
                    </a>
                    <a href="#tech" class="nav-item" data-section="tech">
                        <i class="fas fa-desktop"></i>
                        <span id="navTech">التقنية</span>
                    </a>
                    <a href="#portfolio" class="nav-item" data-section="portfolio">
                        <i class="fas fa-laptop-code"></i>
                        <span id="navPortfolio">معرض الأعمال</span>
                    </a>
                    <a href="#testimonials" class="nav-item" data-section="testimonials">
                        <i class="fas fa-comments"></i>
                        <span id="navTestimonials">التوصيات</span>
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

    <!-- مؤشر تقدم التمرير -->
    <div class="scroll-progress">
        <div class="scroll-progress-bar"></div>
    </div>

    <!-- باقي المحتوى -->
    <main>
        <!-- Hero Section -->
        <section class="hero-section">
            <div class="hero-content">
                <h1 class="hero-title" id="heroTitle">الملف المهني للمعلم فهد الخالدي</h1>
                <p class="hero-subtitle" id="heroSubtitle">معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة</p>
                
                <div class="hero-actions">
                    <a href="#portfolio" class="btn btn-primary">
                        <i class="fas fa-laptop-code"></i>
                        <span id="viewWorkBtn">استعرض أعمالي</span>
                    </a>
                    <a href="#contact" class="btn btn-secondary">
                        <i class="fas fa-envelope"></i>
                        <span id="contactBtn">تواصل معي</span>
                    </a>
                </div>
                
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
                        <span class="number">105+</span>
                        <span class="label" id="heroStat3">ساعات تطوع</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="active">
            <h2 class="section-title" id="aboutTitle">نبذة عني</h2>
            <div class="card fade-in-up">
                <div class="profile-header">
                    <div class="profile-img">
                        <img src="https://i.ibb.co/k66psVmZ/20220817-151032.jpg" alt="صورة فهد الخالدي" class="lazy" data-src="https://i.ibb.co/k66psVmZ/20220817-151032.jpg">
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
                        <span class="stat-number">105+</span>
                        <span class="stat-label" id="stat3">ساعات تطوع</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Vision Section -->
        <section id="vision">
            <h2 class="section-title" id="visionTitle">الرؤية التعليمية</h2>
            <div class="card fade-in-up">
                <div class="vision-content">
                    <div class="vision-item">
                        <i class="fas fa-lightbulb"></i>
                        <h3 id="visionItem1Title">التعليم المتمركز حول الطالب</h3>
                        <p id="visionItem1Desc">أؤمن بأن كل طالب فريد ويحتاج إلى أساليب تعلم مخصصة تناسب احتياجاته وقدراته.</p>
                    </div>
                    <div class="vision-item">
                        <i class="fas fa-handshake"></i>
                        <h3 id="visionItem2Title">الشراكة مع أولياء الأمور</h3>
                        <p id="visionItem2Desc">التعاون مع الأسر أساسي لتحقيق النجاح التعليمي المستدام.</p>
                    </div>
                    <div class="vision-item">
                        <i class="fas fa-chalkboard-teacher"></i>
                        <h3 id="visionItem3Title">التعليم القائم على المشاريع</h3>
                        <p id="visionItem3Desc">أدمج التعلم القائم على المشاريع لتعزيز التفكير النقدي وحل المشكلات.</p>
                    </div>
                    <div class="vision-item">
                        <i class="fas fa-graduation-cap"></i>
                        <h3 id="visionItem4Title">التعلم المستمر</h3>
                        <p id="visionItem4Desc">أؤمن بأن المعلم المتعلم باستمرار هو الأكثر قدرة على إلهام طلابه.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Experience Section -->
        <section id="experience">
            <h2 class="section-title" id="experienceTitle">الخبرات المهنية</h2>
            <div class="card fade-in-up">
                <div class="timeline">
                    <div class="timeline-item">
                        <div class="timeline-date">2017 - الآن</div>
                        <div class="timeline-content">
                            <h3 id="exp1Title">معلم لغة إنجليزية – سعيد بن العاص</h3>
                            <p id="exp1Location">مكة المكرمة</p>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-date">2015 - 2016</div>
                        <div class="timeline-content">
                            <h3 id="exp2Title">معلم لغة إنجليزية – ثانوية الأمير سعود بن عبدالمحسن</h3>
                            <p id="exp2Location">الليث</p>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-date">2012 - 2014</div>
                        <div class="timeline-content">
                            <h3 id="exp3Title">معلم لغة إنجليزية – سعيد بن زيد</h3>
                            <p id="exp3Location">عفيف</p>
                        </div>
                    </div>
                    <div class="timeline-item">
                        <div class="timeline-date">2011 - 2012</div>
                        <div class="timeline-content">
                            <h3 id="exp4Title">مترجم – وزارة الحج والعمرة</h3>
                            <p id="exp4Location">مكة المكرمة</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Achievements Section -->
        <section id="achievements">
            <h2 class="section-title" id="achievementsTitle">الإنجازات</h2>
            <div class="card fade-in-up">
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
            <div class="card fade-in-up">
                <div class="skills-container">
                    <div class="skill-category">
                        <h3 id="skillCat1">المهارات التعليمية</h3>
                        <ul class="skill-list">
                            <li><i class="fas fa-check"></i> <span id="skill1">إتقان اللغة الإنجليزية تحدثاً وكتابة</span></li>
                            <li><i class="fas fa-check"></i> <span id="skill2">تطوير خطط تدريس محفزة ومبتكرة</span></li>
                            <li><i class="fas fa-check"></i> <span id="skill3">إدارة الصفوف بفاعلية</span></li>
                            <li><i class="fas fa-check"></i> <span id="skill4">تشجيع التعلم الذاتي</span></li>
                        </ul>
                    </div>
                    <div class="skill-category">
                        <h3 id="skillCat2">المهارات التقنية</h3>
                        <ul class="skill-list">
                            <li><i class="fas fa-check"></i> <span id="skill5">استخدام أدوات القياس والتقويم الإلكترونية</span></li>
                            <li><i class="fas fa-check"></i> <span id="skill6">دمج التقنية في التعليم</span></li>
                            <li><i class="fas fa-check"></i> <span id="skill7">تصميم أنشطة تفاعلية</span></li>
                            <li><i class="fas fa-check"></i> <span id="skill8">تطوير اختبارات إلكترونية</span></li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Training Section -->
        <section id="training">
            <h2 class="section-title" id="trainingTitle">الدورات التالية</h2>
            <div class="card fade-in-up">
                <div class="training-card">
                    <!-- دورة 1 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">1️⃣</span>
                            <span>التفكير الناقد والإبداعي ودمجه في المواد الدراسية</span>
                        </div>
                        <div class="course-description">
                            دورة تهدف إلى تنمية مهارات التفكير العليا لدى المتعلمين من خلال توظيف استراتيجيات تعليمية قائمة على التحليل والاستنتاج والإبداع.
                        </div>
                        <div class="course-impact">
                            وقد أسهمت في تحويل الدروس إلى مواقف تعليمية نشطة قائمة على التفكير بدل التلقين، ورفعت مستوى التفاعل والفهم العميق لدى الطلاب.
                        </div>
                    </div>

                    <!-- دورة 2 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">2️⃣</span>
                            <span>القياس والتقويم التربوي</span>
                        </div>
                        <div class="course-description">
                            تركز على إكساب المعلم مهارات بناء أدوات التقويم وتحليل نتائج الطلاب وربطها بنواتج التعلم.
                        </div>
                        <div class="course-impact">
                            وقد انعكس أثرها في تحسين دقة التقييم، وتنويع أدوات التقويم، واتخاذ قرارات تعليمية أكثر دقة وموضوعية.
                        </div>
                    </div>

                    <!-- دورة 3 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">3️⃣</span>
                            <span>الاستراتيجيات الحديثة في تدريس أساسيات اللغة الإنجليزية</span>
                        </div>
                        <div class="course-description">
                            تهدف إلى تطوير أساليب تدريس المهارات الأساسية للغة باستخدام استراتيجيات حديثة قائمة على التفاعل والتعلم النشط.
                        </div>
                        <div class="course-impact">
                            وأسهمت في تبسيط المفاهيم اللغوية وزيادة مشاركة الطلاب وتحسن مستواهم التحصيلي.
                        </div>
                    </div>

                    <!-- دورة 4 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">4️⃣</span>
                            <span>البيئة الصفية الجاذبة</span>
                        </div>
                        <div class="course-description">
                            تعنى ببناء بيئة تعليمية محفزة وآمنة تعزز التعلم النشط والانضباط الإيجابي.
                        </div>
                        <div class="course-impact">
                            وقد أسهمت في تحسين إدارة الصف، وزيادة دافعية الطلاب، وانعكس ذلك على استقرار العملية التعليمية داخل الحجرة الدراسية.
                        </div>
                    </div>

                    <!-- دورة 5 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">5️⃣</span>
                            <span>تحليل أداء الطلاب وتقديم التغذية الراجعة</span>
                        </div>
                        <div class="course-description">
                            تستهدف استخدام البيانات التعليمية في تحليل مستويات الطلاب وتقديم تغذية راجعة بنّاءة.
                        </div>
                        <div class="course-impact">
                            وقد مكّنتني من تشخيص دقيق لجوانب القوة والضعف، وتحقيق تحسن ملموس في أداء الطلاب الأكاديمي.
                        </div>
                    </div>

                    <!-- دورة 6 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">6️⃣</span>
                            <span>أساسيات الترجمة</span>
                        </div>
                        <div class="course-description">
                            تهدف إلى تنمية المهارات الأساسية في الترجمة بين اللغتين العربية والإنجليزية مع مراعاة الدقة والسياق.
                        </div>
                        <div class="course-impact">
                            وقد عززت قدرتي على دعم الطلاب في فهم المعاني وتحسين مهاراتهم اللغوية بشكل أفضل.
                        </div>
                    </div>

                    <!-- دورة 7 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">7️⃣</span>
                            <span>مهارات التعامل مع أدوات القياس والتقويم الإلكترونية</span>
                        </div>
                        <div class="course-description">
                            تركز على بناء الاختبارات الإلكترونية وتحليل نتائجها باستخدام التقنيات الحديثة.
                        </div>
                        <div class="course-impact">
                            وقد أسهمت في تسريع عملية التقويم، ورفع دقة النتائج، وتقليل الجهد والوقت في متابعة تحصيل الطلاب.
                        </div>
                    </div>

                    <!-- دورة 8 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">8️⃣</span>
                            <span>التنمية المهنية لمعلمي اللغة الإنجليزية – المستوى الثالث</span>
                        </div>
                        <div class="course-description">
                            دورة متقدمة تهدف إلى رفع كفاءة المعلم المهنية وفق أحدث الاتجاهات التربوية.
                        </div>
                        <div class="course-impact">
                            وقد أسهمت في تطوير ممارساتي التدريسية وتحسين جودة التخطيط والتنفيذ داخل الصف.
                        </div>
                    </div>

                    <!-- دورة 9 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">9️⃣</span>
                            <span>العبقرية في العملية التعليمية</span>
                        </div>
                        <div class="course-description">
                            تركز على تنمية الإبداع والابتكار في التخطيط والتنفيذ والتحفيز.
                        </div>
                        <div class="course-impact">
                            وقد ساعدتني على تقديم الدروس بأساليب غير تقليدية، مما زاد من دافعية الطلاب ومتعتهم أثناء التعلم.
                        </div>
                    </div>

                    <!-- دورة 10 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">🔟</span>
                            <span>بناء الاختبار الجيد</span>
                        </div>
                        <div class="course-description">
                            تعنى بأسس إعداد الاختبارات التحصيلية وفق معايير علمية دقيقة.
                        </div>
                        <div class="course-impact">
                            وقد انعكس أثرها في إعداد اختبارات أكثر جودة وشمولية ودقة في قياس نواتج التعلم.
                        </div>
                    </div>

                    <!-- دورة 11 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">1️⃣1️⃣</span>
                            <span>توظيف استراتيجيات التعليم في البيئة التدريبية الجاذبة</span>
                        </div>
                        <div class="course-description">
                            تركز على تطبيق استراتيجيات التعلم النشط داخل البيئات التدريبية.
                        </div>
                        <div class="course-impact">
                            وقد أسهمت في تصميم أنشطة تدريبية تفاعلية تحقق الأهداف وترفع مستوى التفاعل والدافعية لدى المتدربين.
                        </div>
                    </div>

                    <!-- دورة 12 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">1️⃣2️⃣</span>
                            <span>تدريس مهارتي التحدث والاستماع</span>
                        </div>
                        <div class="course-description">
                            تعنى بتطوير أساليب تدريس مهارتي التحدث والاستماع في اللغة الإنجليزية باستخدام أنشطة تفاعلية.
                        </div>
                        <div class="course-impact">
                            وقد أسهمت في رفع الكفاءة التواصلية للطلاب وزيادة ثقتهم في استخدام اللغة داخل الصف.
                        </div>
                    </div>

                    <!-- دورة 13 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">1️⃣3️⃣</span>
                            <span>التوعية بقواعد السلوك والمواظبة المحدثة</span>
                        </div>
                        <div class="course-description">
                            تهدف إلى نشر ثقافة الانضباط المدرسي والالتزام بالأنظمة.
                        </div>
                        <div class="course-impact">
                            وقد ساعدتني على تعزيز السلوك الإيجابي لدى الطلاب، ورفع مستوى الانضباط والمواظبة المدرسية.
                        </div>
                    </div>

                    <!-- دورة 14 -->
                    <div class="course-item">
                        <div class="course-title">
                            <span class="course-emoji">1️⃣4️⃣</span>
                            <span>اللقاءات التخصصية لمادة اللغة الإنجليزية</span>
                        </div>
                        <div class="course-description">
                            لقاءات تهدف إلى تبادل الخبرات ومناقشة أفضل الممارسات في تدريس اللغة الإنجليزية.
                        </div>
                        <div class="course-impact">
                            وقد أسهمت في تطوير أسلوبي التدريسي وتحسين نواتج تعلم الطلاب.
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Certificates Section -->
        <section id="certificates">
            <h2 class="section-title" id="certificatesTitle">شهادات الدورات التدريبية</h2>
            <div class="card fade-in-up">
                <div class="portfolio-filters">
                    <button class="filter-btn active" data-filter="all" id="filterAllCert">الكل</button>
                    <button class="filter-btn" data-filter="teaching" id="filterTeaching">تعليمي</button>
                    <button class="filter-btn" data-filter="other" id="filterOther">أخرى</button>
                </div>
                
                <div class="certificates-grid">
                    <!-- شهادة 1 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/s9fcJcr7/1.jpg" alt="شهادة مهارات التفكير الناقد" class="lazy" data-src="https://i.ibb.co/s9fcJcr7/1.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>مهارات التفكير الناقد والإبداعي</h3>
                            <p>شهادة معتمدة في مهارات التفكير الناقد والإبداعي ودمجها في المواد الدراسية</p>
                            <a href="https://www.mediafire.com/file/1m5i9cwhiqz3dwl/%25E2%2580%258E%25E2%2581%25A8%25D8%25B4%25D9%2587%25D8%25A7%25D8%25AF%25D8%25A9_%25D9%2585%25D9%2587%25D8%25A7%25D8%25B1%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D9%2581%25D9%2583%25D9%258A%25D8%25B1_%25D8%25A7%25D9%2584%25D9%2586%25D8%25A7%25D9%2582%25D8%25AF_%25D9%2588%25D8%25A7%25D9%2584%25D8%25A7%25D8%25A8%25D8%25AF%25D8%25A7%25D8%25B9%25D9%258A_%25D9%2588%25D8%25AF%25D9%2585%25D8%25AC%25D9%2587%25D8%25A7_%25D9%2581%25D9%258A_%25D8%25A7%25D9%2584%25D9%2585%25D9%2588%25D8%25A7%25D8%25AF_%25D8%25A7%25D9%2584%25D8%25AF%25D8%25B1%25D8%25A7%25D8%25B3%25D9%258A%25D8%25A9%25E2%2581%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 2 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/6cHn5ny1/2.jpg" alt="شهادة القياس والتقويم التربوي" class="lazy" data-src="https://i.ibb.co/6cHn5ny1/2.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>القياس والتقويم التربوي</h3>
                            <p>شهادة معتمدة في القياس والتقويم التربوي وأساليب التقييم الحديثة</p>
                            <a href="https://www.mediafire.com/file/ylwfuhzhyt4m0x9/%25E2%2580%258E%25E2%2581%25A8%25D8%25B4%25D9%2587%25D8%25A7%25D8%25AF%25D8%25A9_%25D8%25A7%25D9%2584%25D9%2582%25D9%258A%25D8%25A7%25D8%25B3_%25D9%2588%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D9%2582%25D9%2588%25D9%258A%25D9%2585_%25D8%25A7%25D9%2584%25D8%25AA%25D8%25B1%25D8%25A8%25D9%2588%25D9%258A%25E2%2581%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 3 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/DfbgfFtL/3.jpg" alt="شهادة الاستراتيجيات الحديثة في تدريس اللغة الإنجليزية" class="lazy" data-src="https://i.ibb.co/DfbgfFtL/3.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>الاستراتيجيات الحديثة في تدريس اللغة الإنجليزية</h3>
                            <p>شهادة معتمدة في الاستراتيجيات الحديثة لتدريس أساسيات اللغة الإنجليزية</p>
                            <a href="https://www.mediafire.com/file/br7i8kkshy5qv6r/%25E2%2580%258E%25E2%2581%25A8%25D8%25B4%25D9%2587%25D8%25A7%25D8%25AF%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D8%25B3%25D8%25AA%25D8%25B1%25D8%25A7%25D8%25AA%25D9%258A%25D8%25AC%25D9%258A%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D8%25AD%25D8%25AF%25D9%258A%25D8%25AB%25D8%25A9_%25D9%2581%25D9%258A_%25D8%25A7%25D8%25B3%25D8%25A7%25D8%25B3%25D9%258A%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D9%2584%25D8%25BA%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2586%25D8%25AC%25D9%2584%25D9%258A%25D8%25B2%25D9%258A%25D8%25A9%25E2%2581%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 4 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/7JH4pjBT/4.jpg" alt="شهادة البيئة الصفية الجاذبة" class="lazy" data-src="https://i.ibb.co/7JH4pjBT/4.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>البيئة الصفية الجاذبة</h3>
                            <p>شهادة معتمدة في تصميم وإدارة البيئة الصفية الجاذبة والمحفزة للتعلم</p>
                            <a href="https://www.mediafire.com/file/5lpzoh55grwth8h/%25E2%2580%258E%25E2%2581%25A8%25D8%25B4%25D9%2587%25D8%25A7%25D8%25AF%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A8%25D9%258A%25D9%258A%25D9%2594%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25B5%25D9%2581%25D9%258A%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25AC%25D8%25A7%25D8%25B0%25D8%25A8%25D8%25A9%25E2%2581%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 5 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/99B2rcMN/5.jpg" alt="شهادة تحليل أداء الطلاب" class="lazy" data-src="https://i.ibb.co/99B2rcMN/5.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>تحليل أداء الطلاب وتقديم تغذية راجعة</h3>
                            <p>شهادة معتمدة في تحليل أداء الطلاب وتقديم التغذية الراجعة الفعالة</p>
                            <a href="https://www.mediafire.com/file/lcx20fw7uwvhtbm/%25E2%2580%258E%25E2%2581%25A8%25D8%25B4%25D9%2587%25D8%25A7%25D8%25AF%25D8%25A9_%25D8%25AA%25D8%25AD%25D9%2584%25D9%258A%25D9%2584_%25D8%25A7%25D9%2594%25D8%25AF%25D8%25A7%25D8%25A1_%25D8%25A7%25D9%2584%25D8%25B7%25D9%2584%25D8%25A7%25D8%25A8_%25D9%2588%25D8%25A7%25D8%25B3%25D8%25AA%25D8%25AE%25D8%25AF%25D8%25A7%25D9%2585_%25D8%25A7%25D9%2584%25D8%25AA%25D8%25BA%25D8%25B0%25D9%258A%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25B1%25D8%25A7%25D8%25AC%25D8%25B9%25D8%25A9%25E2%2581%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 6 -->
                    <div class="certificate-item" data-category="other">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/mV52L5Hf/6.jpg" alt="شهادة أساسيات الترجمة" class="lazy" data-src="https://i.ibb.co/mV52L5Hf/6.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>أساسيات الترجمة</h3>
                            <p>شهادة معتمدة في أساسيات ومبادئ الترجمة بين اللغتين العربية والإنجليزية</p>
                            <a href="https://www.mediafire.com/file/4by9vpzij9smpht/Certificate_for_%25D9%2581%25D9%2587%25D8%25AF_%25D9%2586%25D8%25BA%25D9%258A%25D9%2585%25D8%25B4_%25D8%25A7%25D9%2584%25D8%25AE%25D8%25A7%25D9%2584%25D8%25AF%25D9%258A_for_%25D8%25B4%25D9%2587%25D8%25A7%25D8%25AF%25D8%25A9_%25D8%25AF%25D9%2588%25D8%25B1%25D8%25A9_%25D8%25A3%25D8%25B3%25D8%25A7%25D8%25B3%25D9%258A%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25B1%25D8%25AC%25D9%2585%25D8%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 7 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/xShYN2g7/7.jpg" alt="شهادة التعامل مع أدوات القياس والتقويم الإلكترونية" class="lazy" data-src="https://i.ibb.co/xShYN2g7/7.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>مهارات التعامل مع أدوات القياس والتقويم الإلكترونية</h3>
                            <p>شهادة معتمدة في استخدام أدوات القياس والتقويم الإلكترونية في التعليم</p>
                            <a href="https://www.mediafire.com/file/33iz2k72lqr9r7n/%25D9%2585%25D9%2587%25D8%25A7%25D8%25B1%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25B9%25D8%25A7%25D9%2585%25D9%2584_%25D9%2585%25D8%25B9_%25D8%25A3%25D8%25AF%25D9%2588%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D9%2582%25D9%258A%25D8%25A7%25D8%25B3_%25D9%2588%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D9%2582%25D9%2588%25D9%258A%25D9%2585_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D9%2583%25D8%25AA%25D8%25B1%25D9%2588%25D9%2586%25D9%258A%25D8%25A9.php.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 8 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/BHj37qKz/8.jpg" alt="شهادة التنمية المهنية لمعلمي اللغة الإنجليزية" class="lazy" data-src="https://i.ibb.co/BHj37qKz/8.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>التنمية المهنية لمعلمي اللغة الإنجليزية</h3>
                            <p>شهادة معتمدة في التنمية المهنية لمعلمي اللغة الإنجليزية - المستوى الثالث</p>
                            <a href="https://www.mediafire.com/file/c9kpwvolamjgyfi/%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D9%2586%25D9%2585%25D9%258A%25D8%25A9_%25D8%25A7%25D9%2584%25D9%2585%25D9%2585%25D9%2587%25D9%2586%25D9%258A%25D8%25A9_%25D9%2584%25D9%2584%25D9%2585%25D8%25B9%25D9%2584%25D9%2585%25D9%258A%25D9%2586_%25D8%25A7%25D9%2584%25D9%2584%25D8%25BA%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2586%25D8%25AC%25D9%2584%25D9%258A%25D8%25B2%25D9%258A%25D8%25A9_%2528_%25D8%25A7%25D9%2584%25D9%2585%25D8%25B3%25D8%25AA%25D9%2588%25D9%2589_3%2529.php.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 9 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/x8KmXG0m/9.jpg" alt="شهادة العبقرية في العملية التدريبية" class="lazy" data-src="https://i.ibb.co/x8KmXG0m/9.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>العبقرية في العملية التدريبية</h3>
                            <p>شهادة معتمدة في العبقرية في العملية التدريبية (TOT)</p>
                            <a href="https://www.mediafire.com/file/lb129yr42malqhv/%25D8%25A7%25D9%2584%25D8%25B9%25D8%25A8%25D9%2582%25D8%25B1%25D9%258A%25D8%25A9_%25D9%2581%25D9%258A_%25D8%25A7%25D9%2584%25D8%25B9%25D9%2585%25D9%2584%25D9%258A%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25AF%25D8%25B1%25D9%258A%25D8%25A8%25D9%258A%25D8%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 10 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/MxJxBHsH/10.jpg" alt="شهادة بناء الاختبار الجيد" class="lazy" data-src="https://i.ibb.co/MxJxBHsH/10.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>بناء الاختبار الجيد</h3>
                            <p>شهادة معتمدة في بناء الاختبارات الجيدة والفعالة</p>
                            <a href="https://www.mediafire.com/file/uo2o7rqqv3j87g5/%25D8%25A8%25D9%2586%25D8%25A7%25D8%25A1_%25D8%25A7%25D9%2584%25D8%25A7%25D8%25AE%25D8%25AA%25D8%25A8%25D8%25A7%25D8%25B1_%25D8%25A7%25D9%2584%25D8%25AC%25D9%258A%25D8%25AF_%2528%25D8%25A7%25D9%2584%25D9%2581%25D8%25B5%25D9%2584_%25D8%25A7%25D9%2584%25D8%25AF%25D8%25B1%25D8%25A7%25D8%25B3%25D9%258A_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2588%25D9%2584%2529.php.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 11 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/60LbCHLy/11.jpg" alt="شهادة توظيف استراتيجيات التعليم" class="lazy" data-src="https://i.ibb.co/60LbCHLy/11.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>توظيف استراتيجيات التعليم في البيئة التدريبية الجاذبة</h3>
                            <p>شهادة معتمدة في توظيف استراتيجيات التعليم في البيئة التدريبية الجاذبة</p>
                            <a href="https://www.mediafire.com/file/jt7h17gdjl81gb3/%25D8%25AA%25D9%2588%25D8%25B8%25D9%258A%25D9%2581_%25D8%25A7%25D8%25B3%25D8%25AA%25D8%25B1%25D8%25A7%25D8%25AA%25D9%258A%25D8%25AC%25D9%258A%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25B9%25D9%2584%25D9%258A%25D9%2585_%25D9%2581%25D9%258A_%25D8%25A7%25D9%2584%25D8%25A8%25D9%258A%25D8%25A6%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25AF%25D8%25B1%25D9%258A%25D8%25A8%25D9%258A%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AC%25D8%25A7%25D8%25B0%25D8%25A8%25D8%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 12 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/Z6mRby92/12.jpg" alt="شهادة تدريس مهاراتي التحدث والاستماع" class="lazy" data-src="https://i.ibb.co/Z6mRby92/12.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>تدريس مهارتي التحدث والاستماع</h3>
                            <p>شهادة معتمدة في تدريس مهارات التحدث والاستماع في اللغة الإنجليزية</p>
                            <a href="https://www.mediafire.com/file/lnukcn37plu0bjt/%25D8%25AA%25D8%25AF%25D8%25B1%25D9%258A%25D8%25B3_%25D9%2585%25D9%2587%25D8%25A7%25D8%25B1%25D8%25A7%25D8%25AA%25D9%258A_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25AD%25D8%25AF%25D8%25AB_%25D9%2588%25D8%25A7%25D9%2584%25D8%25A5%25D8%25B3%25D8%25AA%25D9%2585%25D8%25A7%25D8%25B9.php.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 13 -->
                    <div class="certificate-item" data-category="teaching">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/rGVtkJN0/13.jpg" alt="شهادة اللقاءات التخصصية للغة الإنجليزية" class="lazy" data-src="https://i.ibb.co/rGVtkJN0/13.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>اللقاءات التخصصية للغة الإنجليزية</h3>
                            <p>شهادة معتمدة في اللقاءات التخصصية لمادة اللغة الإنجليزية</p>
                            <a href="https://www.mediafire.com/file/oybk1nug304u5cw/%25D8%25AF%25D9%2588%25D8%25B1%25D8%25A9_%25D8%25A7%25D9%2584%25D9%2584%25D9%2582%25D8%25A7%25D8%25A1%25D8%25A7%25D8%25AA_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25AE%25D8%25B5%25D8%25B5%25D9%258A%25D8%25A9_%25D9%2584%25D9%2584%25D8%25BA%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2586%25D8%25AC%25D9%2584%25D9%258A%25D8%25B2%25D9%258A%25D8%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                    
                    <!-- شهادة 14 -->
                    <div class="certificate-item" data-category="other">
                        <div class="certificate-img">
                            <img src="https://i.ibb.co/wZsxpBRX/14.jpg" alt="شهادة العمل التطوعي" class="lazy" data-src="https://i.ibb.co/wZsxpBRX/14.jpg">
                        </div>
                        <div class="certificate-content">
                            <h3>شهادة العمل التطوعي</h3>
                            <p>شهادة معتمدة في العمل التطوعي بمقدار 105 ساعة تطوعية</p>
                            <a href="https://www.mediafire.com/file/3msfzyf0afgm172/%25D8%25B4%25D9%2587%25D8%25A7%25D8%25AF%25D8%25A9_%25D8%25A7%25D9%2584%25D8%25A7%25D9%2584%25D8%25AA%25D8%25B7%25D9%2588%25D8%25B9_%25D9%25A1%25D9%25A0%25D9%25A5_%25D8%25B3%25D8%25A7%25D8%25B9%25D8%25A9.pdf/file" target="_blank" class="btn btn-primary download-btn">
                                <i class="fas fa-download"></i>
                                تحميل الشهادة
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Tech Section -->
        <section id="tech">
            <h2 class="section-title" id="techTitle">التقنية</h2>
            <div class="card fade-in-up">
                <div class="tech-card">
                    <p id="techText">
                        أتمتع بشغف كبير تجاه التقنية والتعليم الرقمي، وأواكب أحدث التطورات في مجال الذكاء الاصطناعي وتطبيقاته التعليمية. أمتلك خبرة عملية في تصميم وتطوير أنشطة تفاعلية واختبارات إلكترونية باستخدام HTML وCSS وJavaScript، مما يثري تجربة التعلم ويجعلها أكثر تفاعلية وجاذبية للطلاب. أستخدم أدوات الذكاء الاصطناعي في تحليل أداء الطلاب وتصميم خطط تعليمية مخصصة، كما أصمم محتوى رقميًا مبتكرًا يتناسب مع احتياجات التعلم الحديثة. أسعى دائمًا لدمج التقنية في العملية التعليمية بطرق إبداعية تواكب متطلبات العصر الرقمي وتخدم أهداف رؤية المملكة 2030.
                    </p>
                </div>
            </div>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio">
            <h2 class="section-title" id="portfolioTitle">معرض الأعمال</h2>
            <div class="card fade-in-up">
                <!-- أزرار التصفية -->
                <div class="portfolio-filters">
                    <button class="filter-btn active" data-filter="all" id="filterAll">الكل</button>
                    <button class="filter-btn" data-filter="interactive" id="filterInteractive">تفاعلية</button>
                    <button class="filter-btn" data-filter="strategies" id="filterStrategies">استراتيجيات</button>
                    <button class="filter-btn" data-filter="presentations" id="filterPresentations">عروض</button>
                    <button class="filter-btn" data-filter="participation" id="filterParticipation">مشاركات</button>
                </div>
                
                <div class="portfolio-grid">
                    <!-- مشروع اختبار الرخصة المهنية التفاعلي -->
                    <div class="portfolio-item" data-category="interactive">
                        <img src="https://i.ibb.co/h12KB7Gv/Professional-License-Exam.png" alt="اختبار الرخصة المهنية التفاعلي" class="lazy" data-src="https://i.ibb.co/h12KB7Gv/Professional-License-Exam.png">
                        <div class="portfolio-content">
                            <h3 id="project1Title">مشروع: اختبار الرخصة المهنية التفاعلي</h3>
                            <p id="project1Desc">مشروع تعليمي رقمي يهدف إلى محاكاة اختبار الرخصة المهنية للمعلمين، من خلال تقديم أسئلة تفاعلية مبنية على المعايير المعتمدة، مع تغذية راجعة فورية توضح السبب العلمي لكل إجابة صحيحة أو خاطئة، بما يسهم في رفع كفاءة المتدربين وتعزيز جاهزيتهم للاختبار الرسمي.</p>
                            <a href="https://visionof2030-pixel.github.io/Professional-License-Exam/" class="project-link" target="_blank"><span id="project1Link">عرض المشروع</span> <i class="fas fa-external-link-alt"></i></a>
                        </div>
                    </div>
                    
                    <!-- مشروع تطبيق الاستراتيجيات الحديثة في التعليم -->
                    <div class="portfolio-item" data-category="strategies">
                        <div class="portfolio-content">
                            <h3 id="project2Title">تطبيق الاستراتيجيات الحديثة في التعليم</h3>
                            <p id="project2Desc1" style="margin-bottom: 20px;">
                                تُعدّ الاستراتيجيات الحديثة عنصرًا محوريًا في تطوير العملية التعليمية وتعزيز فاعلية التعلم داخل الصف؛ إذ تسهم في رفع مستوى التفاعل، وتحفيز الدافعية، وتنمية مهارات التفكير والعمل لدى الطلاب. ومن هذا المنطلق أحرص على توظيف مجموعة متنوعة من الأساليب التدريسية التي تجمع بين المتعة والفائدة، وتعتمد على التفاعل الإيجابي والمشاركة الفعّالة.<br><br>

                                ويأتي التعلم القائم على التحفيز والتحدي كأحد الأساليب التي تسهم في ترسيخ المفاهيم بطريقة مشوقة، وتساعد الطلاب على التعلم بروح المنافسة الإيجابية. كما يمثل التعلم التعاوني ركيزة أساسية في بناء مهارات التواصل والعمل الجماعي، من خلال إتاحة الفرصة للطلاب لتبادل الآراء، ومناقشة الأفكار، وحل المشكلات بشكل جماعي. كذلك أحرص على توظيف التقنيات التعليمية الحديثة التي تسهم في عرض المحتوى بصورة جذابة، وتتيح تفاعل جميع الطلاب ومشاركتهم في تصحيح المفاهيم وبناء المعرفة بشكل مباشر.<br><br>

                                وتعد هذه الممارسات نماذج من جملة من الاستراتيجيات التي أعمل على تنويعها داخل الحصة بما يراعي الفروق الفردية، ويحقق الأهداف التعليمية، وتهيئ بيئة تعليمية نشطة ومحفزة تسهم في تحسين مستوى التحصيل الدراسي وتعزيز مهارات القرن الحادي والعشرين.
                            </p>
                            
                            <!-- معرض الصور التفاعلي -->
                            <div class="gallery-container">
                                <div class="gallery-scroll" id="galleryScroll">
                                    <!-- الصور الثلاثة الأولى مع عناوينها الحالية -->
                                    <div class="gallery-item">
                                        <img src="https://i.ibb.co/YrXjKC4/strategy7.jpg" alt="مهارات القرن الحادي والعشرين" class="lazy" data-src="https://i.ibb.co/YrXjKC4/strategy7.jpg">
                                        <div class="gallery-caption" id="galleryCaption1">تعزيز مهارات القرن الحادي والعشرين لدى الطلاب</div>
                                    </div>
                                    <div class="gallery-item">
                                        <img src="https://i.ibb.co/DPWWd5Z9/strategy4.jpg" alt="أنشطة تعليمية تفاعلية" class="lazy" data-src="https://i.ibb.co/DPWWd5Z9/strategy4.jpg">
                                        <div class="gallery-caption" id="galleryCaption2">أنشطة تعليمية تفاعلية لتحسين مستوى التحصيل الدراسي</div>
                                    </div>
                                    <div class="gallery-item">
                                        <img src="https://i.ibb.co/bR1Cn1WZ/strategy6.jpg" alt="بيئة تعليمية نشطة" class="lazy" data-src="https://i.ibb.co/bR1Cn1WZ/strategy6.jpg">
                                        <div class="gallery-caption" id="galleryCaption3">إعداد بيئة تعليمية نشطة ومحفزة للطلاب</div>
                                    </div>
                                    <!-- باقي الصور مع التعليق الجديد -->
                                    <div class="gallery-item">
                                        <img src="https://i.ibb.co/DyNDhNX/strategy1.jpg" alt="استراتيجية تعليمية تفاعلية" class="lazy" data-src="https://i.ibb.co/DyNDhNX/strategy1.jpg">
                                        <div class="gallery-caption">تطبيق استراتيجيات تعليمية حديثة لتعزيز التفاعل داخل الصف.</div>
                                    </div>
                                    <div class="gallery-item">
                                        <img src="https://i.ibb.co/BK6XTNG0/strategy2.jpg" alt="التعلم التعاوني" class="lazy" data-src="https://i.ibb.co/BK6XTNG0/strategy2.jpg">
                                        <div class="gallery-caption">تطبيق استراتيجيات تعليمية حديثة لتعزيز التفاعل داخل الصف.</div>
                                    </div>
                                    <div class="gallery-item">
                                        <img src="https://i.ibb.co/LzbN9WYb/strategy3.jpg" alt="تقنيات تعليمية حديثة" class="lazy" data-src="https://i.ibb.co/LzbN9WYb/strategy3.jpg">
                                        <div class="gallery-caption">تطبيق استراتيجيات تعليمية حديثة لتعزيز التفاعل داخل الصف.</div>
                                    </div>
                                    <div class="gallery-item">
                                        <img src="https://i.ibb.co/C3bhdCFt/strategy5.jpg" alt="مهارات التفكير والعمل" class="lazy" data-src="https://i.ibb.co/C3bhdCFt/strategy5.jpg">
                                        <div class="gallery-caption">تطبيق استراتيجيات تعليمية حديثة لتعزيز التفاعل داخل الصف.</div>
                                    </div>
                                </div>
                                
                                <div class="gallery-controls">
                                    <button class="gallery-btn" id="scrollUpBtn">
                                        <i class="fas fa-chevron-up"></i>
                                        <span id="scrollUpText">تمرير للأعلى</span>
                                    </button>
                                    <button class="gallery-btn" id="scrollDownBtn">
                                        <i class="fas fa-chevron-down"></i>
                                        <span id="scrollDownText">تمرير للأسفل</span>
                                    </button>
                                </div>
                                
                                <div class="gallery-indicator" id="galleryIndicator">
                                    <!-- سيتم إنشاء النقاط ديناميكيًا -->
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- مشروع عروض تقديمية -->
                    <div class="portfolio-item" data-category="presentations">
                        <img src="https://via.placeholder.com/300x180/1A3A5F/FFFFFF?text=عروض+تقديمية" alt="عروض تقديمية" class="lazy" data-src="https://via.placeholder.com/300x180/1A3A5F/FFFFFF?text=عروض+تقديمية">
                        <div class="portfolio-content">
                            <h3 id="project3Title">عروض تقديمية تفاعلية</h3>
                            <p id="project3Desc">تصميم عروض تفاعلية جذابة للطلاب باستخدام أحدث الأدوات والتقنيات التعليمية. تتضمن هذه العروض أنشطة تفاعلية، ومقاطع فيديو تعليمية، وأسئلة تقييم فورية لضمان مشاركة فعالة من الطلاب.</p>
                            <a href="https://visionof2030-pixel.github.io/English-quiz/" class="project-link" target="_blank"><span id="project3Link">عرض المشروع</span> <i class="fas fa-external-link-alt"></i></a>
                        </div>
                    </div>
                    
                    <!-- المشاركة الأولى -->
                    <div class="portfolio-item" data-category="participation">
                        <div class="portfolio-content">
                            <h3>عضوية لجنة التميز والتفاعل المهني</h3>
                            <p>جانب من مشاركتي بصفتي عضوًا في لجنة التميز المدرسية، دعمًا للتفاعل مع المجتمع المهني، وتعزيزًا للتعاون وتبادل الخبرات مع الزملاء، والمشاركة في المبادرات التعليمية التطويرية.</p>
                            
                            <div class="participation-gallery">
                                <div class="participation-img">
                                    <img src="https://i.ibb.co/N6zvYFTm/participation1-1.jpg" alt="عضوية لجنة التميز والتفاعل المهني 1" class="lazy" data-src="https://i.ibb.co/N6zvYFTm/participation1-1.jpg">
                                </div>
                                <div class="participation-img">
                                    <img src="https://i.ibb.co/93SBfMCM/participation1-2.jpg" alt="عضوية لجنة التميز والتفاعل المهني 2" class="lazy" data-src="https://i.ibb.co/93SBfMCM/participation1-2.jpg">
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- المشاركة الثانية -->
                    <div class="portfolio-item" data-category="participation">
                        <div class="portfolio-content">
                            <h3>تعزيز القيم الوطنية من خلال فعاليات اليوم الوطني</h3>
                            <p>مشاركتي في فعاليات اليوم الوطني، تجسيدًا لقيم الانتماء والولاء للوطن، وتعزيزًا لدور المدرسة في غرس القيم الوطنية لدى الطلاب.</p>
                            
                            <div class="participation-gallery">
                                <div class="participation-img">
                                    <img src="https://i.ibb.co/x855CYrT/participation2.jpg" alt="تعزيز القيم الوطنية من خلال فعاليات اليوم الوطني" class="lazy" data-src="https://i.ibb.co/x855CYrT/participation2.jpg">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials">
            <h2 class="section-title" id="testimonialsTitle">التوصيات</h2>
            <div class="card fade-in-up">
                <div class="testimonial-slider">
                    <div class="testimonial-slides" id="testimonialSlides">
                        <div class="testimonial-slide">
                            <div class="testimonial-content">
                                <p id="testimonial1Text">"المعلم فهد يتميز بالإبداع والابتكار في أساليب التدريس، وقد قدم إضافة حقيقية لفريق العمل"</p>
                            </div>
                            <div class="testimonial-author">
                                <strong id="testimonial1Author">مدير المدرسة</strong>
                                <span id="testimonial1Position">مدرسة سعيد بن العاص</span>
                            </div>
                        </div>
                        <div class="testimonial-slide">
                            <div class="testimonial-content">
                                <p id="testimonial2Text">"لقد أحدثت استراتيجياته التعليمية فرقاً ملحوظاً في أداء الطلاب وحبهم للغة الإنجليزية"</p>
                            </div>
                            <div class="testimonial-author">
                                <strong id="testimonial2Author">منسق اللغة الإنجليزية</strong>
                                <span id="testimonial2Position">إدارة التعليم</span>
                            </div>
                        </div>
                        <div class="testimonial-slide">
                            <div class="testimonial-content">
                                <p id="testimonial3Text">"تميزه في استخدام التقنية جعل عملية التعلم أكثر متعة وفعالية للطلاب"</p>
                            </div>
                            <div class="testimonial-author">
                                <strong id="testimonial3Author">زملاء العمل</strong>
                                <span id="testimonial3Position">فريق اللغة الإنجليزية</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="testimonial-controls">
                        <button class="testimonial-control" id="testimonialPrev">
                            <i class="fas fa-chevron-right"></i>
                        </button>
                        <button class="testimonial-control" id="testimonialNext">
                            <i class="fas fa-chevron-left"></i>
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2 class="section-title" id="contactTitle">تواصل معي</h2>
            <div class="card fade-in-up">
                <div style="text-align: center; padding: 25px;">
                    <h3 style="color: var(--primary); margin-bottom: 15px;" id="contactSubtitle">للتواصل</h3>
                    <div style="font-size: 1rem; line-height: 2; color: var(--text);">
                        <p><i class="fas fa-envelope" style="color: var(--accent);"></i> <span id="contactEmail">iFahadenglish@gmail.com</span></p>
                        <p><i class="fas fa-phone" style="color: var(--accent);"></i> <span id="contactPhone">+9665554449824</span></p>
                    </div>
                </div>
            </div>
            
            <!-- نموذج التواصل -->
            <div class="card fade-in-up">
                <form id="contactForm">
                    <div class="form-group">
                        <input type="text" id="contactName" placeholder="الاسم الكامل" required>
                    </div>
                    <div class="form-group">
                        <input type="email" id="contactEmailInput" placeholder="البريد الإلكتروني" required>
                    </div>
                    <div class="form-group">
                        <textarea id="contactMessage" placeholder="رسالتك..." rows="5" required></textarea>
                    </div>
                    <div class="form-message" id="formMessage"></div>
                    <button type="submit" class="btn btn-primary" style="width: 100%;" id="submitBtn">
                        <i class="fas fa-paper-plane"></i>
                        <span id="sendMessageBtn">إرسال الرسالة</span>
                    </button>
                </form>
            </div>
        </section>
    </main>

    <!-- زر العودة للأعلى -->
    <button class="back-to-top" id="backToTop">
        <i class="fas fa-chevron-up"></i>
    </button>

    <footer>
        <div class="footer-content">
            <h3 id="footerName">فهد الخالدي</h3>
            <p id="footerDesc">معلم متخصص في اللغة الإنجليزية - تطوير التعليم من خلال التقنية والابتكار</p>
            
            <div class="copyright" id="footerText">
                © 2024 جميع الحقوق محفوظة - فهد الخالدي
            </div>
        </div>
    </footer>

    <!-- بيانات Structured Data لتحسين SEO -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "Person",
        "name": "فهد الخالدي",
        "jobTitle": "معلم متقدم - تخصص اللغة الإنجليزية",
        "description": "معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة",
        "email": "iFahadenglish@gmail.com",
        "telephone": "+966554449824",
        "url": "https://example.com",
        "knowsAbout": ["التعليم", "اللغة الإنجليزية", "التقنية التعليمية", "التدريس التفاعلي"],
        "hasCredential": "معلم متقدم",
        "worksFor": {
            "@type": "Organization",
            "name": "وزارة التعليم السعودية"
        },
        "alumniOf": {
            "@type": "EducationalOrganization",
            "name": "جامعة أم القرى"
        }
    }
    </script>

    <!-- ملف Manifest لتطبيق PWA -->
    <script>
        // تسجيل Service Worker لتطبيق PWA
        if ('serviceWorker' in navigator) {
            window.addEventListener('load', function() {
                navigator.serviceWorker.register('/sw.js').then(function(registration) {
                    console.log('ServiceWorker registration successful with scope: ', registration.scope);
                }, function(err) {
                    console.log('ServiceWorker registration failed: ', err);
                });
            });
        }
    </script>

    <script>
        // بيانات الترجمة
        const translations = {
            ar: {
                pageTitle: "فهد الخالدي",
                heroTitle: "الملف المهني للمعلم فهد الخالدي",
                heroSubtitle: "معلم متخصص في اللغة الإنجليزية مع 14+ سنة خبرة في تطوير أساليب التعليم الحديثة",
                heroStat1: "سنوات خبرة",
                heroStat2: "ساعة تدريب",
                heroStat3: "ساعات تطوع",
                aboutTitle: "نبذة عني",
                visionTitle: "الرؤية التعليمية",
                experienceTitle: "الخبرات المهنية",
                achievementsTitle: "الإنجازات",
                skillsTitle: "المهارات والكفاءات",
                trainingTitle: "الدورات التالية",
                certificatesTitle: "شهادات الدورات التدريبية",
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
                stat3: "ساعات تطوع",
                visionItem1Title: "التعليم المتمركز حول الطالب",
                visionItem1Desc: "أؤمن بأن كل طالب فريد ويحتاج إلى أساليب تعلم مخصصة تناسب احتياجاته وقدراته.",
                visionItem2Title: "الشراكة مع أولياء الأمور",
                visionItem2Desc: "التعاون مع الأسر أساسي لتحقيق النجاح التعليمي المستدام.",
                visionItem3Title: "التعليم القائم على المشاريع",
                visionItem3Desc: "أدمج التعلم القائم على المشاريع لتعزيز التفكير النقدي وحل المشكلات.",
                visionItem4Title: "التعلم المستمر",
                visionItem4Desc: "أؤمن بأن المعلم المتعلم باستمرار هو الأكثر قدرة على إلهام طلابه.",
                achievementText: "في عام 2022 حصلتُ على ترقية إلى رتبة معلم متقدم بعد مسيرة مهنية امتدت لسنوات كمعلم ممارس، قدمت خلالها أداءً متميزًا أسهم في تطوير العملية التعليمية داخل المدرسة. جاءت هذه الترقية تقديرًا لجهودي في توظيف استراتيجيات تدريس حديثة تعزز مهارات التفكير النقدي والإبداعي لدى الطلاب، إضافة إلى قدرتي على تحليل نواتج التعلم وبناء خطط علاجية فردية أثمرت عن تحسين واضح في مستويات الطلاب.<br><br>وقد عكست هذه الترقية ثقة الجهة التعليمية بمهاراتي المهنية، خصوصًا في مجال تصميم أنشطة مبتكرة تُدمج مهارات الفهم العميق، والعمل التعاوني، والتعليم الذاتي داخل البيئة الصفية. كما كانت اعترافًا بدوري في تطوير البرامج التربوية والأنشطة التعليمية قبل عام 2022، ومساهمتي في بناء بيئة صفية محفزة يشعر فيها الطلاب بالأمان والرغبة في المشاركة والتعلم.<br><br>تعد هذه الترقية محطة مهمة في مسيرتي، لأنها لم تكن مجرد انتقال إلى مستوى وظيفي أعلى، بل كانت نتيجة تراكم خبرات وممارسات مهنية أثبتت أثرها على الطلاب وعلى منظومة التعليم داخل المدرسة. واليوم أواصل عملي كمعلم متقدم ملتزم بالتحسين المستمر، وتطبيق أفضل الممارسات التربوية، والمساهمة في رفع جودة التعليم وتحقيق نواتج تعلم أعلى.",
                techText: "أتمتع بشغف كبير تجاه التقنية والتعليم الرقمي، وأواكب أحدث التطورات في مجال الذكاء الاصطناعي وتطبيقاته التعليمية. أمتلك خبرة عملية في تصميم وتطوير أنشطة تفاعلية واختبارات إلكترونية باستخدام HTML وCSS وJavaScript، مما يثري تجربة التعلم ويجعلها أكثر تفاعلية وجاذبية للطلاب. أستخدم أدوات الذكاء الاصطناعي في تحليل أداء الطلاب وتصميم خطط تعليمية مخصصة، كما أصمم محتوى رقميًا مبتكرًا يتناسب مع احتياجات التعلم الحديثة. أسعى دائمًا لدمج التقنية في العملية التعليمية بطرق إبداعية تواكب متطلبات العصر الرقمي وتخدم أهداف رؤية المملكة 2030.",
                footerText: "© 2024 جميع الحقوق محفوظة - فهد الخالدي",
                // إضافة ترجمة نصوص الأيقونات
                navAbout: "نبذة عني",
                navVision: "الرؤية التعليمية",
                navExp: "الخبرات",
                navAchievements: "الإنجازات",
                navSkills: "المهارات",
                navTrain: "الدورات",
                navCertificates: "شهاداتي",
                navTech: "التقنية",
                navPortfolio: "معرض الأعمال",
                navTestimonials: "التوصيات",
                navContact: "بيانات التواصل",
                // ترجمة المهارات
                skillCat1: "المهارات التعليمية",
                skillCat2: "المهارات التقنية",
                skill1: "إتقان اللغة الإنجليزية تحدثاً وكتابة",
                skill2: "تطوير خطط تدريس محفزة ومبتكرة",
                skill3: "إدارة الصفوف بفاعلية",
                skill4: "تشجيع التعلم الذاتي",
                skill5: "استخدام أدوات القياس والتقويم الإلكترونية",
                skill6: "دمج التقنية في التعليم",
                skill7: "تصميم أنشطة تفاعلية",
                skill8: "تطوير اختبارات إلكترونية",
                // ترجمة الدورات
                course1: "التفكير الناقد والإبداعي ودمجه في المواد الدراسية",
                course2: "القياس والتقويم التربوي",
                course3: "الاستراتيجية الحديثة في تدريس أساسيات اللغة الإنجليزية",
                course4: "البيئة الصفية الجاذبة",
                course5: "تحليل أداء الطلاب وتقديم التغذية الراجعة",
                course6: "أساسيات الترجمة",
                course7: "مهارات التعامل مع أدوات القياس والتقويم الإلكترونية",
                course8: "التنمية المهنية لمعلمي اللغة الإنجليزية - المستوى الثالث",
                course9: "العبقرية في العملية التعليمية",
                course10: "بناء الاختيار الجيد",
                course11: "توظيف استراتيجيات التعليم في البيئة التدريبية الجاذبة",
                course12: "تدريس مهارتي التحدث والاستماع",
                course13: "التوعية بقواعد السلوك والمواظبة المحدثة",
                course14: "اللقاءات التخصصية لمادة اللغة الإنجليزية",
                // ترجمة المشاريع
                project1Title: "مشروع: اختبار الرخصة المهنية التفاعلي",
                project1Desc: "مشروع تعليمي رقمي يهدف إلى محاكاة اختبار الرخصة المهنية للمعلمين، من خلال تقديم أسئلة تفاعلية مبنية على المعايير المعتمدة، مع تغذية راجعة فورية توضح السبب العلمي لكل إجابة صحيحة أو خاطئة، بما يسهم في رفع كفاءة المتدربين وتعزيز جاهزيتهم للاختبار الرسمي.",
                project1Link: "عرض المشروع",
                project2Title: "تطبيق الاستراتيجيات الحديثة في التعليم",
                project2Desc1: "تُعدّ الاستراتيجيات الحديثة عنصرًا محوريًا في تطوير العملية التعليمية وتعزيز فاعلية التعلم داخل الصف؛ إذ تسهم في رفع مستوى التفاعل، وتحفيز الدافعية، وتنمية مهارات التفكير والعمل لدى الطلاب. ومن هذا المنطلق أحرص على توظيف مجموعة متنوعة من الأساليب التدريسية التي تجمع بين المتعة والفائدة، وتعتمد على التفاعل الإيجابي والمشاركة الفعّالة.<br><br>ويأتي التعلم القائم على التحفيز والتحدي كأحد الأساليب التي تسهم في ترسيخ المفاهيم بطريقة مشوقة، وتساعد الطلاب على التعلم بروح المنافسة الإيجابية. كما يمثل التعلم التعاوني ركيزة أساسية في بناء مهارات التواصل والعمل الجماعي، من خلال إتاحة الفرصة للطلاب لتبادل الآراء، ومناقشة الأفكار، وحل المشكلات بشكل جماعي. كذلك أحرص على توظيف التقنيات التعليمية الحديثة التي تسهم في عرض المحتوى بصورة جذابة، وتتيح تفاعل جميع الطلاب ومشاركتهم في تصحيح المفاهيم وبناء المعرفة بشكل مباشر.<br><br>وتعد هذه الممارسات نماذج من جملة من الاستراتيجيات التي أعمل على تنويعها داخل الحصة بما يراعي الفروق الفردية، ويحقق الأهداف التعليمية، ويهيئ بيئة تعليمية نشطة ومحفزة تسهم في تحسين مستوى التحصيل الدراسي وتعزيز مهارات القرن الحادي والعشرين.",
                project3Title: "عروض تقديمية تفاعلية",
                project3Desc: "تصميم عروض تفاعلية جذابة للطلاب باستخدام أحدث الأدوات والتقنيات التعليمية. تتضمن هذه العروض أنشطة تفاعلية، ومقاطع فيديو تعليمية، وأسئلة تقييم فورية لضمان مشاركة فعالة من الطلاب.",
                project3Link: "عرض المشروع",
                // ترجمة التوصيات
                testimonial1Text: "\"المعلم فهد يتميز بالإبداع والابتكار في أساليب التدريس، وقد قدم إضافة حقيقية لفريق العمل\"",
                testimonial1Author: "مدير المدرسة",
                testimonial1Position: "مدرسة سعيد بن العاص",
                testimonial2Text: "\"لقد أحدثت استراتيجياته التعليمية فرقاً ملحوظاً في أداء الطلاب وحبهم للغة الإنجليزية\"",
                testimonial2Author: "منسق اللغة الإنجليزية",
                testimonial2Position: "إدارة التعليم",
                testimonial3Text: "\"تميزه في استخدام التقنية جعل عملية التعلم أكثر متعة وفعالية للطلاب\"",
                testimonial3Author: "زملاء العمل",
                testimonial3Position: "فريق اللغة الإنجليزية",
                // ترجمة الاتصال
                contactSubtitle: "للتواصل",
                contactEmail: "iFahadenglish@gmail.com",
                contactPhone: "+966554449824",
                sendMessageBtn: "إرسال الرسالة",
                // ترجمة الفوتر
                footerName: "فهد الخالدي",
                footerDesc: "معلم متخصص في اللغة الإنجليزية - تطوير التعليم من خلال التقنية والابتكار",
                // ترجمة المعرض التفاعلي
                scrollUpText: "تمرير للأعلى",
                scrollDownText: "تمرير للأسفل",
                galleryCaption1: "تعزيز مهارات القرن الحادي والعشرين لدى الطلاب",
                galleryCaption2: "أنشطة تعليمية تفاعلية لتحسين مستوى التحصيل الدراسي",
                galleryCaption3: "إعداد بيئة تعليمية نشطة ومحفزة للطلاب",
                // ترجمة قسم الخبرات
                exp1Title: "معلم لغة إنجليزية – سعيد بن العاص",
                exp1Location: "مكة المكرمة",
                exp2Title: "معلم لغة إنجليزية – ثانوية الأمير سعود بن عبدالمحسن",
                exp2Location: "الليث",
                exp3Title: "معلم لغة إنجليزية – سعيد بن زيد",
                exp3Location: "عفيف",
                exp4Title: "مترجم – وزارة الحج والعمرة",
                exp4Location: "مكة المكرمة",
                // ترجمة أزرار التصفية
                filterAll: "الكل",
                filterInteractive: "تفاعلية",
                filterStrategies: "استراتيجيات",
                filterPresentations: "عروض",
                filterParticipation: "مشاركات",
                // ترجمة أزرار CTA
                viewWorkBtn: "استعرض أعمالي",
                contactBtn: "تواصل معي"
            },
            en: {
                pageTitle: "Fahad AlKhaldi",
                heroTitle: "Professional Portfolio - Fahad AlKhaldi",
                heroSubtitle: "English Language Specialist with 14+ Years Experience in Modern Teaching Methods",
                heroStat1: "Years Experience",
                heroStat2: "Training Hours",
                heroStat3: "Volunteer Hours",
                aboutTitle: "About Me",
                visionTitle: "Educational Vision",
                experienceTitle: "Professional Experience",
                achievementsTitle: "Achievements",
                skillsTitle: "Skills & Competencies",
                trainingTitle: "Training Courses",
                certificatesTitle: "Training Certificates",
                portfolioTitle: "Portfolio",
                testimonialsTitle: "Testimonials",
                techTitle: "Technology",
                contactTitle: "Contact Me",
                name: "Fahad Nughaimesh Humaid AlKhaldi",
                jobTitle: "Advanced English Teacher",
                bioText: "I believe that education is not merely about transferring knowledge, but a noble mission to make an impact and build individuals. I aspire to be an active part in developing education in the Kingdom by employing modern technologies, creating stimulating learning environments that enhance critical and creative thinking, and building student confidence. My future vision is based on continuous learning, developing professional skills, and keeping pace with digital transformations that serve educational outcomes and quality within the framework of Saudi Vision 2030.",
                badge: "🏆 Achieved a score of 95 in specialization",
                stat1: "Years of Experience",
                stat2: "Training Hours",
                stat3: "Volunteer Hours",
                visionItem1Title: "Student-Centered Education",
                visionItem1Desc: "I believe that every student is unique and needs customized learning methods that suit their needs and abilities.",
                visionItem2Title: "Partnership with Parents",
                visionItem2Desc: "Cooperation with families is essential to achieving sustainable educational success.",
                visionItem3Title: "Project-Based Learning",
                visionItem3Desc: "I integrate project-based learning to enhance critical thinking and problem-solving.",
                visionItem4Title: "Continuous Learning",
                visionItem4Desc: "I believe that a continuously learning teacher is the most capable of inspiring his students.",
                achievementText: "In 2022, I was promoted to the rank of Senior Teacher after a professional career spanning years as a practicing teacher, during which I provided outstanding performance that contributed to the development of the educational process within the school. This promotion came in recognition of my efforts in employing modern teaching strategies that enhance students' critical and creative thinking skills, in addition to my ability to analyze learning outcomes and build individual remedial plans that resulted in a clear improvement in student levels.<br><br>This promotion reflected the educational authority's confidence in my professional skills, especially in designing innovative activities that integrate deep understanding skills, collaborative work, and self-learning within the classroom environment. It was also an acknowledgment of my role in developing educational programs and activities before 2022, and my contribution to building a stimulating classroom environment where students feel safe and eager to participate and learn.<br><br>This promotion is an important milestone in my career, as it was not just a transition to a higher functional level, but rather the result of accumulated experiences and professional practices that proved their impact on students and the educational system within the school. Today, I continue my work as a senior teacher committed to continuous improvement, applying the best educational practices, and contributing to raising the quality of education and achieving higher learning outcomes.",
                techText: "I have a great passion for technology and digital education, and I keep up with the latest developments in the field of artificial intelligence and its educational applications. I have practical experience in designing and developing interactive activities and electronic tests using HTML, CSS, and JavaScript, which enriches the learning experience and makes it more interactive and attractive for students. I use AI tools to analyze student performance and design customized educational plans, and I also design innovative digital content that suits modern learning needs. I always strive to integrate technology into the educational process in creative ways that keep pace with the requirements of the digital age and serve the goals of Saudi Vision 2030.",
                footerText: "© 2024 All Rights Reserved - Fahad AlKhaldi",
                // إضافة ترجمة نصوص الأيقونات
                navAbout: "About Me",
                navVision: "Educational Vision",
                navExp: "Experience",
                navAchievements: "Achievements",
                navSkills: "Skills",
                navTrain: "Training",
                navCertificates: "My Certificates",
                navTech: "Technology",
                navPortfolio: "Portfolio",
                navTestimonials: "Testimonials",
                navContact: "Contact Info",
                // ترجمة المهارات
                skillCat1: "Teaching Skills",
                skillCat2: "Technical Skills",
                skill1: "Proficiency in spoken and written English",
                skill2: "Developing stimulating and innovative teaching plans",
                skill3: "Effective classroom management",
                skill4: "Encouraging self-learning",
                skill5: "Using electronic measurement and assessment tools",
                skill6: "Integrating technology into education",
                skill7: "Designing interactive activities",
                skill8: "Developing electronic tests",
                // ترجمة الدورات
                course1: "Critical and Creative Thinking and its Integration into Academic Subjects",
                course2: "Educational Measurement and Evaluation",
                course3: "Modern Strategy in Teaching English Language Basics",
                course4: "Attractive Classroom Environment",
                course5: "Analyzing Student Performance and Providing Feedback",
                course6: "Translation Fundamentals",
                course7: "Skills for Dealing with Electronic Measurement and Assessment Tools",
                course8: "Professional Development for English Teachers - Level Three",
                course9: "Genius in the Educational Process",
                course10: "Building Good Choices",
                course11: "Employing Teaching Strategies in an Attractive Training Environment",
                course12: "Teaching Speaking and Listening Skills",
                course13: "Awareness of Updated Behavior and Attendance Rules",
                course14: "Specialized Meetings for English Language Subject",
                // ترجمة المشاريع
                project1Title: "Project: Interactive Professional License Exam",
                project1Desc: "A digital educational project that aims to simulate the professional license exam for teachers, by providing interactive questions based on approved standards, with immediate feedback that explains the scientific reason for each correct or incorrect answer, which helps raise the efficiency of trainees and enhance their readiness for the official exam.",
                project1Link: "View Project",
                project2Title: "Applying Modern Strategies in Education",
                project2Desc1: "Modern strategies are a pivotal element in developing the educational process and enhancing the effectiveness of learning in the classroom. They contribute to raising the level of interaction, stimulating motivation, and developing thinking and working skills among students. From this standpoint, I am keen to employ a variety of teaching methods that combine fun and benefit, and rely on positive interaction and effective participation.<br><br>Challenge-based learning comes as one of the methods that helps consolidate concepts in an exciting way and helps students learn with a spirit of positive competition. Cooperative learning also represents a fundamental pillar in building communication and teamwork skills, by providing students with the opportunity to exchange opinions, discuss ideas, and solve problems collectively. I also strive to employ modern educational technologies that contribute to presenting content in an attractive way, and allow all students to interact and participate in correcting concepts and building knowledge directly.<br><br>These practices are examples of a range of strategies that I work to diversify within the class, taking into account individual differences, achieving educational goals, and preparing an active and stimulating educational environment that contributes to improving academic achievement and enhancing 21st century skills.",
                project3Title: "Interactive Presentations",
                project3Desc: "Designing interactive and engaging presentations for students using the latest educational tools and technologies. These presentations include interactive activities, educational videos, and instant assessment questions to ensure effective student participation.",
                project3Link: "View Project",
                // ترجمة التوصيات
                testimonial1Text: "\"Teacher Fahad is distinguished by creativity and innovation in teaching methods, and has made a real addition to the work team\"",
                testimonial1Author: "School Principal",
                testimonial1Position: "Saeed bin Al-Aas School",
                testimonial2Text: "\"His educational strategies have made a noticeable difference in students' performance and their love for the English language\"",
                testimonial2Author: "English Language Coordinator",
                testimonial2Position: "Education Department",
                testimonial3Text: "\"His excellence in using technology has made the learning process more enjoyable and effective for students\"",
                testimonial3Author: "Colleagues",
                testimonial3Position: "English Language Team",
                // ترجمة الاتصال
                contactSubtitle: "For Contact",
                contactEmail: "iFahadenglish@gmail.com",
                contactPhone: "+966554449824",
                sendMessageBtn: "Send Message",
                // ترجمة الفوتر
                footerName: "Fahad AlKhaldi",
                footerDesc: "English Language Specialist - Developing Education Through Technology and Innovation",
                // ترجمة المعرض التفاعلي
                scrollUpText: "Scroll Up",
                scrollDownText: "Scroll Down",
                galleryCaption1: "Enhancing 21st century skills among students",
                galleryCaption2: "Interactive educational activities to improve academic achievement",
                galleryCaption3: "Preparing an active and stimulating educational environment for students",
                // ترجمة قسم الخبرات
                exp1Title: "English Teacher – Saeed bin Al-Aas",
                exp1Location: "Makkah",
                exp2Title: "English Teacher – Prince Saud bin Abdulmohsen Secondary School",
                exp2Location: "Al-Lith",
                exp3Title: "English Teacher – Saeed bin Zaid",
                exp3Location: "Afif",
                exp4Title: "Translator – Ministry of Hajj and Umrah",
                exp4Location: "Makkah",
                // ترجمة أزرار التصفية
                filterAll: "All",
                filterInteractive: "Interactive",
                filterStrategies: "Strategies",
                filterPresentations: "Presentations",
                filterParticipation: "Participation",
                // ترجمة أزرار CTA
                viewWorkBtn: "View My Work",
                contactBtn: "Contact Me"
            }
        };

        let currentLang = 'ar';
        let currentTheme = localStorage.getItem('theme') || 'light';

        // تعيين الوضع الافتراضي
        document.documentElement.setAttribute('data-theme', currentTheme);

        // عناصر DOM
        const langBtn = document.getElementById('langBtn');
        const langText = document.getElementById('langText');
        const themeBtn = document.getElementById('themeBtn');
        const pageTitle = document.getElementById('pageTitle');
        const heroTitle = document.getElementById('heroTitle');
        const heroSubtitle = document.getElementById('heroSubtitle');
        const heroStat1 = document.getElementById('heroStat1');
        const heroStat2 = document.getElementById('heroStat2');
        const heroStat3 = document.getElementById('heroStat3');
        const aboutTitle = document.getElementById('aboutTitle');
        const visionTitle = document.getElementById('visionTitle');
        const experienceTitle = document.getElementById('experienceTitle');
        const achievementsTitle = document.getElementById('achievementsTitle');
        const skillsTitle = document.getElementById('skillsTitle');
        const trainingTitle = document.getElementById('trainingTitle');
        const certificatesTitle = document.getElementById('certificatesTitle');
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
        const visionItem1Title = document.getElementById('visionItem1Title');
        const visionItem1Desc = document.getElementById('visionItem1Desc');
        const visionItem2Title = document.getElementById('visionItem2Title');
        const visionItem2Desc = document.getElementById('visionItem2Desc');
        const visionItem3Title = document.getElementById('visionItem3Title');
        const visionItem3Desc = document.getElementById('visionItem3Desc');
        const visionItem4Title = document.getElementById('visionItem4Title');
        const visionItem4Desc = document.getElementById('visionItem4Desc');
        const achievementText = document.getElementById('achievementText');
        const techText = document.getElementById('techText');
        const footerText = document.getElementById('footerText');
        const navScroll = document.getElementById('navScroll');
        const navScrollPrev = document.querySelector('.nav-scroll-prev');
        const navScrollNext = document.querySelector('.nav-scroll-next');
        
        // عناصر نصوص الأيقونات
        const navAbout = document.getElementById('navAbout');
        const navVision = document.getElementById('navVision');
        const navExp = document.getElementById('navExp');
        const navAchievements = document.getElementById('navAchievements');
        const navSkills = document.getElementById('navSkills');
        const navTrain = document.getElementById('navTrain');
        const navCertificates = document.getElementById('navCertificates');
        const navTech = document.getElementById('navTech');
        const navPortfolio = document.getElementById('navPortfolio');
        const navTestimonials = document.getElementById('navTestimonials');
        const navContact = document.getElementById('navContact');

        // تحديث أيقونة الوضع الليلي
        function updateThemeIcon() {
            themeBtn.innerHTML = currentTheme === 'light' ? 
                '<i class="fas fa-moon"></i>' : 
                '<i class="fas fa-sun"></i>';
        }

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
            visionTitle.textContent = t.visionTitle;
            experienceTitle.textContent = t.experienceTitle;
            achievementsTitle.textContent = t.achievementsTitle;
            skillsTitle.textContent = t.skillsTitle;
            trainingTitle.textContent = t.trainingTitle;
            certificatesTitle.textContent = t.certificatesTitle;
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
            visionItem1Title.textContent = t.visionItem1Title;
            visionItem1Desc.textContent = t.visionItem1Desc;
            visionItem2Title.textContent = t.visionItem2Title;
            visionItem2Desc.textContent = t.visionItem2Desc;
            visionItem3Title.textContent = t.visionItem3Title;
            visionItem3Desc.textContent = t.visionItem3Desc;
            visionItem4Title.textContent = t.visionItem4Title;
            visionItem4Desc.textContent = t.visionItem4Desc;
            achievementText.innerHTML = t.achievementText;
            techText.textContent = t.techText;
            footerText.textContent = t.footerText;
            
            // تحديث نصوص الأيقونات
            navAbout.textContent = t.navAbout;
            navVision.textContent = t.navVision;
            navExp.textContent = t.navExp;
            navAchievements.textContent = t.navAchievements;
            navSkills.textContent = t.navSkills;
            navTrain.textContent = t.navTrain;
            navCertificates.textContent = t.navCertificates;
            navTech.textContent = t.navTech;
            navPortfolio.textContent = t.navPortfolio;
            navTestimonials.textContent = t.navTestimonials;
            navContact.textContent = t.navContact;
            
            // تحديث اتجاه النص
            document.documentElement.dir = lang === 'ar' ? 'rtl' : 'ltr';
            document.documentElement.lang = lang;
        }

        // حدث تبديل اللغة
        langBtn.addEventListener('click', () => {
            currentLang = currentLang === 'ar' ? 'en' : 'ar';
            loadLanguage(currentLang);
            langText.textContent = currentLang === 'ar' ? 'EN' : 'AR';
        });

        // حدث تبديل الوضع الليلي
        themeBtn.addEventListener('click', () => {
            currentTheme = currentTheme === 'light' ? 'dark' : 'light';
            document.documentElement.setAttribute('data-theme', currentTheme);
            updateThemeIcon();
            
            // تخزين التفضيل في localStorage
            localStorage.setItem('theme', currentTheme);
        });

        // تحديث أيقونة الوضع الليلي عند التحميل
        updateThemeIcon();

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

        // ========== التحسينات الجديدة ==========

        // زر العودة للأعلى
        const backToTopBtn = document.getElementById('backToTop');

        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopBtn.classList.add('visible');
            } else {
                backToTopBtn.classList.remove('visible');
            }
        });

        backToTopBtn.addEventListener('click', () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });

        // مؤشر تقدم التمرير
        const scrollProgressBar = document.querySelector('.scroll-progress-bar');

        window.addEventListener('scroll', () => {
            const windowHeight = document.documentElement.scrollHeight - document.documentElement.clientHeight;
            const scrolled = (window.scrollY / windowHeight) * 100;
            scrollProgressBar.style.width = scrolled + '%';
        });

        // Lazy Loading للصور
        function initLazyLoading() {
            const lazyImages = [].slice.call(document.querySelectorAll('img.lazy'));
            
            if ('IntersectionObserver' in window) {
                const lazyImageObserver = new IntersectionObserver(function(entries, observer) {
                    entries.forEach(function(entry) {
                        if (entry.isIntersecting) {
                            const lazyImage = entry.target;
                            lazyImage.src = lazyImage.dataset.src;
                            lazyImage.classList.remove('lazy');
                            lazyImage.classList.add('loaded');
                            lazyImageObserver.unobserve(lazyImage);
                        }
                    });
                });
                
                lazyImages.forEach(function(lazyImage) {
                    lazyImageObserver.observe(lazyImage);
                });
            } else {
                // Fallback للمتصفحات التي لا تدعم IntersectionObserver
                lazyImages.forEach(function(lazyImage) {
                    lazyImage.src = lazyImage.dataset.src;
                    lazyImage.classList.remove('lazy');
                    lazyImage.classList.add('loaded');
                });
            }
        }

        // تحسين نموذج التواصل
        function initContactForm() {
            const contactForm = document.getElementById('contactForm');
            const formMessage = document.getElementById('formMessage');
            const submitBtn = document.getElementById('submitBtn');
            const sendMessageBtnText = document.getElementById('sendMessageBtn');
            
            contactForm.addEventListener('submit', (e) => {
                e.preventDefault();
                
                const name = document.getElementById('contactName').value.trim();
                const email = document.getElementById('contactEmailInput').value.trim();
                const message = document.getElementById('contactMessage').value.trim();
                
                // التحقق من صحة البيانات
                if (!name || !email || !message) {
                    showFormMessage(
                        currentLang === 'ar' ? 
                            'يرجى ملء جميع الحقول المطلوبة.' : 
                            'Please fill in all required fields.',
                        'error'
                    );
                    return;
                }
                
                // التحقق من صحة البريد الإلكتروني
                const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
                if (!emailRegex.test(email)) {
                    showFormMessage(
                        currentLang === 'ar' ? 
                            'يرجى إدخال بريد إلكتروني صحيح.' : 
                            'Please enter a valid email address.',
                        'error'
                    );
                    return;
                }
                
                // إظهار حالة التحميل
                setButtonLoading(true);
                
                // محاكاة إرسال النموذج (يمكن استبدالها برمز إرسال حقيقي)
                setTimeout(() => {
                    const successMessage = currentLang === 'ar' ? 
                        `شكراً ${name}، تم استلام رسالتك بنجاح! سأتواصل معك قريباً.` : 
                        `Thank you ${name}, your message has been received! I will contact you soon.`;
                    
                    showFormMessage(successMessage, 'success');
                    contactForm.reset();
                    setButtonLoading(false);
                }, 2000);
            });
            
            function showFormMessage(message, type) {
                formMessage.textContent = message;
                formMessage.className = 'form-message ' + type;
                formMessage.style.display = 'block';
                
                // إخفاء الرسالة بعد 5 ثواني
                setTimeout(() => {
                    formMessage.style.display = 'none';
                }, 5000);
            }
            
            function setButtonLoading(loading) {
                if (loading) {
                    submitBtn.classList.add('btn-loading');
                    sendMessageBtnText.textContent = currentLang === 'ar' ? 'جاري الإرسال...' : 'Sending...';
                    submitBtn.disabled = true;
                } else {
                    submitBtn.classList.remove('btn-loading');
                    sendMessageBtnText.textContent = currentLang === 'ar' ? 'إرسال الرسالة' : 'Send Message';
                    submitBtn.disabled = false;
                }
            }
        }

        // وظيفة إدارة معرض الصور
        function initGallery() {
            const galleryScroll = document.getElementById('galleryScroll');
            const scrollUpBtn = document.getElementById('scrollUpBtn');
            const scrollDownBtn = document.getElementById('scrollDownBtn');
            const galleryIndicator = document.getElementById('galleryIndicator');
            
            // إنشاء نقاط المؤشر
            const galleryItems = galleryScroll.querySelectorAll('.gallery-item');
            galleryItems.forEach((_, index) => {
                const dot = document.createElement('div');
                dot.classList.add('indicator-dot');
                if (index === 0) dot.classList.add('active');
                dot.addEventListener('click', () => {
                    scrollToItem(index);
                });
                galleryIndicator.appendChild(dot);
            });
            
            const dots = galleryIndicator.querySelectorAll('.indicator-dot');
            
            // وظيفة التمرير إلى عنصر محدد
            function scrollToItem(index) {
                const item = galleryItems[index];
                galleryScroll.scrollTo({
                    top: item.offsetTop - galleryScroll.offsetTop,
                    behavior: 'smooth'
                });
                updateActiveDot(index);
            }
            
            // تحديث النقطة النشطة
            function updateActiveDot(index) {
                dots.forEach(dot => dot.classList.remove('active'));
                dots[index].classList.add('active');
            }
            
            // التمرير لأعلى
            scrollUpBtn.addEventListener('click', () => {
                const currentScroll = galleryScroll.scrollTop;
                const itemHeight = galleryItems[0].offsetHeight + 20; // الارتفاع + الهامش
                
                // البحث عن العنصر الحالي
                let currentIndex = 0;
                for (let i = 0; i < galleryItems.length; i++) {
                    if (galleryItems[i].offsetTop - galleryScroll.offsetTop >= currentScroll) {
                        currentIndex = i;
                        break;
                    }
                }
                
                // التمرير للعنصر السابق
                if (currentIndex > 0) {
                    scrollToItem(currentIndex - 1);
                }
            });
            
            // التمرير لأسفل
            scrollDownBtn.addEventListener('click', () => {
                const currentScroll = galleryScroll.scrollTop;
                const itemHeight = galleryItems[0].offsetHeight + 20; // الارتفاع + الهامش
                
                // البحث عن العنصر الحالي
                let currentIndex = 0;
                for (let i = 0; i < galleryItems.length; i++) {
                    if (galleryItems[i].offsetTop - galleryScroll.offsetTop >= currentScroll) {
                        currentIndex = i;
                        break;
                    }
                }
                
                // التمرير للعنصر التالي
                if (currentIndex < galleryItems.length - 1) {
                    scrollToItem(currentIndex + 1);
                }
            });
            
            // تحديث النقطة النشطة أثناء التمرير
            galleryScroll.addEventListener('scroll', () => {
                const scrollPosition = galleryScroll.scrollTop;
                
                for (let i = 0; i < galleryItems.length; i++) {
                    const item = galleryItems[i];
                    const itemTop = item.offsetTop - galleryScroll.offsetTop;
                    const itemBottom = itemTop + item.offsetHeight;
                    
                    if (scrollPosition >= itemTop && scrollPosition < itemBottom) {
                        updateActiveDot(i);
                        break;
                    }
                }
            });
        }

        // وظيفة تصفية المشاريع
        function initPortfolioFilter() {
            const filterBtns = document.querySelectorAll('.filter-btn');
            const portfolioItems = document.querySelectorAll('.portfolio-item');
            
            filterBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    // إزالة النشط من جميع الأزرار
                    filterBtns.forEach(b => b.classList.remove('active'));
                    // إضافة النشط للزر المحدد
                    btn.classList.add('active');
                    
                    const filterValue = btn.getAttribute('data-filter');
                    
                    portfolioItems.forEach(item => {
                        if (filterValue === 'all' || item.getAttribute('data-category') === filterValue) {
                            item.style.display = 'block';
                            setTimeout(() => {
                                item.style.opacity = '1';
                                item.style.transform = 'translateY(0)';
                            }, 100);
                        } else {
                            item.style.opacity = '0';
                            item.style.transform = 'translateY(20px)';
                            setTimeout(() => {
                                item.style.display = 'none';
                            }, 300);
                        }
                    });
                });
            });
        }

        // وظيفة تصفية الشهادات
        function initCertificatesFilter() {
            const filterBtns = document.querySelectorAll('#certificates .filter-btn');
            const certificateItems = document.querySelectorAll('.certificate-item');
            
            filterBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    // إزالة النشط من جميع الأزرار
                    filterBtns.forEach(b => b.classList.remove('active'));
                    // إضافة النشط للزر المحدد
                    btn.classList.add('active');
                    
                    const filterValue = btn.getAttribute('data-filter');
                    
                    certificateItems.forEach(item => {
                        if (filterValue === 'all' || item.getAttribute('data-category') === filterValue) {
                            item.style.display = 'flex';
                            setTimeout(() => {
                                item.style.opacity = '1';
                                item.style.transform = 'translateY(0)';
                            }, 100);
                        } else {
                            item.style.opacity = '0';
                            item.style.transform = 'translateY(20px)';
                            setTimeout(() => {
                                item.style.display = 'none';
                            }, 300);
                        }
                    });
                });
            });
        }

        // وظيفة شريط التوصيات
        function initTestimonialSlider() {
            const testimonialSlides = document.getElementById('testimonialSlides');
            const testimonialPrev = document.getElementById('testimonialPrev');
            const testimonialNext = document.getElementById('testimonialNext');
            let currentSlide = 0;
            const totalSlides = testimonialSlides.children.length;
            
            function updateSlider() {
                testimonialSlides.style.transform = `translateX(-${currentSlide * 100}%)`;
            }
            
            testimonialNext.addEventListener('click', () => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSlider();
            });
            
            testimonialPrev.addEventListener('click', () => {
                currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
                updateSlider();
            });
            
            // تبديل تلقائي كل 5 ثواني
            setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSlider();
            }, 5000);
        }

        // وظيفة تأثيرات الظهور عند التمرير
        function initScrollAnimations() {
            const fadeElements = document.querySelectorAll('.fade-in-up');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                    }
                });
            }, { threshold: 0.1 });
            
            fadeElements.forEach(el => observer.observe(el));
        }

        // التحميل الأولي
        loadLanguage(currentLang);
        
        // تهيئة جميع المكونات عند تحميل الصفحة
        document.addEventListener('DOMContentLoaded', () => {
            initLazyLoading();
            initGallery();
            initPortfolioFilter();
            initCertificatesFilter();
            initTestimonialSlider();
            initScrollAnimations();
            initContactForm();
        });
    </script>
</body>
</html>
