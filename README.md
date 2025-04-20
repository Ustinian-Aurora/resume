<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>邓颖昊的个人简历</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;700&family=Roboto:wght@300;400;500&display=swap">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <style>
        :root {
            --primary: #3498db;
            --secondary: #2ecc71;
            --dark: #2c3e50;
            --light: #ecf0f1;
            --accent: #f1c40f;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Roboto', 'Microsoft YaHei', sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: var(--dark);
            line-height: 1.6;
            min-height: 100vh;
            padding: 40px 20px;
        }
        
        .resume-container {
            max-width: 1000px;
            margin: 0 auto;
            background-color: white;
            border-radius: 15px;
            box-shadow: var(--shadow);
            overflow: hidden;
            position: relative;
        }
        
        .resume-header {
            padding: 40px;
            text-align: center;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            position: relative;
            overflow: hidden;
        }
        
        .resume-header::before {
            content: "";
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,255,255,0.1) 0%, transparent 70%);
            transform: rotate(30deg);
        }
        
        .resume-title {
            font-family: 'Noto Serif SC', serif;
            font-size: 2.8rem;
            margin-bottom: 15px;
            letter-spacing: 2px;
            position: relative;
            text-shadow: 0 2px 4px rgba(0,0,0,0.2);
        }
        
        .resume-subtitle {
            font-weight: 300;
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 30px;
        }
        
        .resume-photo-container {
            width: 180px;
            height: 180px;
            margin: 0 auto 20px;
            border-radius: 50%;
            border: 5px solid rgba(255,255,255,0.3);
            padding: 5px;
            background: linear-gradient(135deg, var(--accent) 0%, var(--secondary) 100%);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: var(--transition);
            position: relative;
            overflow: hidden;
        }
        
        .resume-photo {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover;
            display: block;
            transition: var(--transition);
        }
        
        .resume-photo-container:hover {
            transform: scale(1.05) rotate(5deg);
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
        }
        
        .resume-photo-container:hover .resume-photo {
            transform: scale(0.95);
        }
        
        .resume-body {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 30px;
            padding: 40px;
        }
        
        .sidebar {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }
        
        .main-content {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }
        
        .card {
            background: white;
            border-radius: 10px;
            padding: 25px;
            box-shadow: var(--shadow);
            transition: var(--transition);
            position: relative;
            overflow: hidden;
        }
        
        .card::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 4px;
            height: 100%;
            background: linear-gradient(to bottom, var(--primary), var(--secondary));
            transition: var(--transition);
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .card:hover::after {
            width: 6px;
        }
        
        .section-title {
            font-family: 'Noto Serif SC', serif;
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: var(--dark);
            position: relative;
            display: flex;
            align-items: center;
        }
        
        .section-title::after {
            content: "";
            flex: 1;
            height: 1px;
            background: linear-gradient(to right, var(--primary), transparent);
            margin-left: 15px;
        }
        
        .section-title i {
            margin-right: 10px;
            color: var(--primary);
        }
        
        .info-item {
            margin-bottom: 15px;
            display: flex;
            align-items: flex-start;
        }
        
        .info-item:last-child {
            margin-bottom: 0;
        }
        
        .info-icon {
            width: 30px;
            height: 30px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            flex-shrink: 0;
            box-shadow: 0 3px 6px rgba(0,0,0,0.1);
        }
        
        .info-content {
            flex: 1;
        }
        
        .info-label {
            font-weight: 500;
            color: var(--dark);
            margin-bottom: 3px;
        }
        
        .info-text {
            color: #666;
            font-size: 0.95rem;
        }
        
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill-tag {
            background: linear-gradient(135deg, var(--light) 0%, #dfe6e9 100%);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            color: var(--dark);
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            transition: var(--transition);
        }
        
        .skill-tag:hover {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            transform: translateY(-2px);
        }
        
        .timeline {
            position: relative;
            padding-left: 30px;
        }
        
        .timeline::before {
            content: "";
            position: absolute;
            left: 10px;
            top: 5px;
            height: calc(100% - 10px);
            width: 2px;
            background: linear-gradient(to bottom, var(--primary), var(--secondary));
        }
        
        .timeline-item {
            position: relative;
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px dashed #eee;
        }
        
        .timeline-item:last-child {
            margin-bottom: 0;
            padding-bottom: 0;
            border-bottom: none;
        }
        
        .timeline-dot {
            position: absolute;
            left: -30px;
            top: 5px;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.2);
        }
        
        .timeline-date {
            font-size: 0.85rem;
            color: var(--primary);
            margin-bottom: 5px;
            font-weight: 500;
        }
        
        .timeline-title {
            font-weight: 500;
            margin-bottom: 5px;
            color: var(--dark);
        }
        
        .timeline-desc {
            font-size: 0.9rem;
            color: #666;
        }
        
        .about-text {
            color: #666;
            line-height: 1.8;
            text-align: justify;
        }
        
        .about-text p {
            margin-bottom: 15px;
        }
        
        .about-text p:last-child {
            margin-bottom: 0;
        }
        
        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-link {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--light) 0%, #dfe6e9 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--dark);
            transition: var(--transition);
            box-shadow: 0 3px 6px rgba(0,0,0,0.1);
        }
        
        .social-link:hover {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            transform: translateY(-3px);
        }
        
        @media (max-width: 768px) {
            .resume-body {
                grid-template-columns: 1fr;
                padding: 30px 20px;
            }
            
            .resume-header {
                padding: 30px 20px;
            }
            
            .resume-title {
                font-size: 2rem;
            }
            
            .resume-photo-container {
                width: 150px;
                height: 150px;
            }
        }
    </style>
</head>
<body>
    <div class="resume-container">
        <div class="resume-header">
            <div class="resume-photo-container">
                <img src="2.jpg" alt="邓颖昊" class="resume-photo">
            </div>
            <h1 class="resume-title">邓颖昊</h1>
            <p class="resume-subtitle">软件工程 | 烟台理工学院</p>
        </div>
        
        <div class="resume-body">
            <div class="sidebar">
                <div class="card">
                    <h2 class="section-title"><i class="fas fa-user"></i>基本信息</h2>
                    <div class="info-item">
                        <div class="info-icon"><i class="fas fa-venus-mars"></i></div>
                        <div class="info-content">
                            <div class="info-label">性别</div>
                            <div class="info-text">男</div>
                        </div>
                    </div>
                    <div class="info-item">
                        <div class="info-icon"><i class="fas fa-birthday-cake"></i></div>
                        <div class="info-content">
                            <div class="info-label">年龄</div>
                            <div class="info-text">20岁</div>
                        </div>
                    </div>
                    <div class="info-item">
                        <div class="info-icon"><i class="fas fa-map-marker-alt"></i></div>
                        <div class="info-content">
                            <div class="info-label">籍贯</div>
                            <div class="info-text">山东青岛</div>
                        </div>
                    </div>
                    <div class="info-item">
                        <div class="info-icon"><i class="fas fa-graduation-cap"></i></div>
                        <div class="info-content">
                            <div class="info-label">学历</div>
                            <div class="info-text">本科</div>
                        </div>
                    </div>
                </div>
                
                <div class="card">
                    <h2 class="section-title"><i class="fas fa-phone-alt"></i>联系方式</h2>
                    <div class="info-item">
                        <div class="info-icon"><i class="fas fa-mobile-alt"></i></div>
                        <div class="info-content">
                            <div class="info-label">电话</div>
                            <div class="info-text">17616059637</div>
                        </div>
                    </div>
                    <div class="info-item">
                        <div class="info-icon"><i class="fas fa-envelope"></i></div>
                        <div class="info-content">
                            <div class="info-label">邮箱</div>
                            <div class="info-text">387930179@qq.com</div>
                        </div>
                    </div>
                    <div class="social-links">
                        <a href="#" class="social-link"><i class="fab fa-weixin"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-qq"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-github"></i></a>
                        <a href="#" class="social-link"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                
                <div class="card">
                    <h2 class="section-title"><i class="fas fa-star"></i>技能证书</h2>
                    <div class="skills-list">
                        <div class="skill-tag">平面设计师</div>
                        <div class="skill-tag">软件系统设计师</div>
                    </div>
                </div>
                
                <div class="card">
                    <h2 class="section-title"><i class="fas fa-heart"></i>兴趣爱好</h2>
                    <div class="skills-list">
                        <div class="skill-tag">唱</div>
                        <div class="skill-tag">跳</div>
                        <div class="skill-tag">Rap</div>
                        <div class="skill-tag">篮球</div>
                    </div>
                </div>
            </div>
            
            <div class="main-content">
                <div class="card">
                    <h2 class="section-title"><i class="fas fa-user-tie"></i>个人简介</h2>
                    <div class="about-text">
                        <p>您好，我是邓颖昊，烟台理工学院软件工程专业的本科生。我是一位怀揣着诗意与远方，在时光长河中悠然漫步的追梦者。于我而言，书是一座静谧的港湾，我常在其中探寻未知的宝藏，在文字的花园里尽情采撷芬芳。</p>
                        <p>作为一名软件工程专业的学生，我不仅注重技术能力的提升，也重视人文素养的培养。每一个午后，沏上一杯香茗，翻开一本好书，我便能沉浸其中，忘却周遭的喧嚣。</p>
                        <p>生活里，我崇尚简单与自然，像一只闲云野鹤，享受每一个宁静的瞬间。我深信世间的美好都藏在不经意间，宛如一场突如其来的邂逅，总能给人带来无尽的惊喜。</p>
                    </div>
                </div>
                
                <div class="card">
                    <h2 class="section-title"><i class="fas fa-briefcase"></i>教育背景</h2>
                    <div class="timeline">
                        <div class="timeline-item">
                            <div class="timeline-dot"></div>
                            <div class="timeline-date">2023 - 2027</div>
                            <h3 class="timeline-title">烟台理工学院</h3>
                            <p class="timeline-desc">软件工程专业 | 本科</p>
                        </div>
                        <div class="timeline-item">
                            <div class="timeline-dot"></div>
                            <div class="timeline-date">2020 - 2023</div>
                            <h3 class="timeline-title">青岛西海岸新区职业中等专业学校</h3>
                            <p class="timeline-desc">计算机应用 | 中专</p>
                        </div>
                    </div>
                </div>
                
                <div class="card">
                    <h2 class="section-title"><i class="fas fa-project-diagram"></i>求职意向</h2>
                    <div class="timeline">
                        <div class="timeline-item">
                            <div class="timeline-dot"></div>
                            <h3 class="timeline-title">技术开发岗</h3>
                            <p class="timeline-desc">前端/后端开发/测试/运维</p>
                        </div>
                        <div class="timeline-item">
                            <div class="timeline-dot"></div>
                            <h3 class="timeline-title">算法与数据岗</h3>
                            <p class="timeline-desc">AI算法工程师/大数据开发/网络安全</p>
                        </div>
                    </div>
                </div>
          
        
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
