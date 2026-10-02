[10/2/2026 3:26 AM] مــحــمد: <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>⚽ SPORT ELITE - أخبار الرياضة الحصرية</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            color: #333;
            line-height: 1.6;
        }

        /* Floating Ad */
        .floating-ad {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
            z-index: 500;
            min-width: 250px;
            animation: slideUp 0.5s ease;
        }

        .floating-ad-close {
            position: absolute;
            top: 5px;
            left: 5px;
            background: none;
            border: none;
            cursor: pointer;
            font-size: 20px;
        }

        /* Navigation */
        nav {
            background: rgba(0, 0, 0, 0.95);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .nav-container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .nav-logo {
            color: white;
            font-size: 1.8em;
            font-weight: bold;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-menu {
            display: flex;
            gap: 30px;
            list-style: none;
        }

        .nav-menu a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
            font-weight: 500;
        }

        .nav-menu a:hover {
            color: #667eea;
        }

        .search-box {
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.3);
            padding: 10px 15px;
            border-radius: 25px;
            color: white;
            width: 250px;
        }

        /* Hero */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px 0;
            text-align: center;
        }

        .hero h1 {
            font-size: 3.5em;
            margin-bottom: 10px;
            animation: slideDown 0.8s ease;
        }

        .hero p {
            font-size: 1.3em;
            opacity: 0.9;
            animation: slideUp 0.8s ease;
        }

        /* Pop-ups */
        .popup-overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            z-index: 999;
            animation: fadeIn 0.3s ease;
        }

        .popup-overlay.show {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .popup-content {
            background: white;
            border-radius: 20px;
            padding: 50px;
            max-width: 600px;
            width: 90%;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
            position: relative;
            animation: popUp 0.5s ease;
        }

        .popup-close {
            position: absolute;
            top: 20px;
            right: 20px;
            background: none;
            border: none;
            font-size: 32px;
            cursor: pointer;
            color: #999;
        }
[10/2/2026 3:26 AM] مــحــمد: .popup-content h2 {
            color: #667eea;
            margin-bottom: 15px;
            font-size: 2em;
        }

        .popup-buttons {
            display: flex;
            gap: 15px;
        }

        .popup-btn {
            flex: 1;
            padding: 15px;
            border: none;
            border-radius: 10px;
            font-size: 1em;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s;
        }

        .popup-btn-accept {
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
        }

        .popup-btn-accept:hover {
            transform: translateY(-3px);
        }

        .popup-btn-close {
            background: #f0f0f0;
            color: #333;
        }

        /* Ads Sections */
        .ads-section {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px;
            margin: 20px 0;
            border-radius: 12px;
            text-align: center;
            border: 2px solid #667eea;
            animation: slideDown 0.5s ease;
        }

        .ads-banner {
            background: linear-gradient(45deg, #667eea, #764ba2);
            color: white;
            padding: 25px;
            margin: 20px 0;
            border-radius: 12px;
            text-align: center;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.3s;
        }

        .ads-banner:hover {
            transform: scale(1.02);
        }

        /* Container */
        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Controls */
        .controls {
            display: flex;
< truncated lines 233-470 >
        </div>
    </div>

    <!-- Navigation -->
    <nav>
        <div class="nav-container">
            <div class="nav-logo">⚽ SPORT ELITE</div>
            <ul class="nav-menu">
                <li><a href="#home">الرئيسية</a></li>
                <li><a href="#news">الأخبار</a></li>
                <li><a href="#live">البث المباشر</a></li>
                <li><a href="#stats">الإحصائيات</a></li>
                <li><a href="#contact">اتصل بنا</a></li>
            </ul>
            <input type="text" class="search-box" placeholder="ابحث عن أخبار...">
        </div>
    </nav>

    <!-- Hero -->
    <section class="hero">
        <div style="padding: 20px; background: rgba(0,0,0,0.3); margin-bottom: 20px;">
            <p style="color: white; font-weight: bold;">⚡ إعلان: استمتع بدون حدود - اشترك الآن!</p>
        </div>
        <h1>⚽ SPORT ELITE</h1>
        <p>أحدث أخبار الرياضة العالمية بشكل حصري وفوري</p>
        <div style="padding: 20px; background: rgba(0,0,0,0.3); margin-top: 20px;">
            <p style="color: white; font-weight: bold;">🎯 إعلان: تابعنا على التواصل الاجتماعي!</p>
        </div>
    </section>

    <!-- Ads - Top -->
    <div class="container">
        <div class="ads-banner">
            🔥 إعلان: اشترك وكسب 1000$ - شروط بسيطة جداً!
        </div>
        <div class="ads-section">
            <p style="color: #667eea; font-weight: bold; margin-bottom: 10px;">📢 إعلان 1: منصة بث مباريات حية</p>
            <p style="font-size: 0.9em;">شاهد المباريات قبل الجميع بـ 4.99$ فقط!</p>
        </div>
        <div class="ads-section">
            <p style="color: #667eea; font-weight: bold; margin-bottom: 10px;">💳 إعلان 2: بطاقة رياضية ذهبية</p>
            <p style="font-size: 0.9em;">احصل على مميزات لا محدودة!</p>
        </div>
    </div>

    <!-- Stats with Ads -->
    <div class="container">
        <div class="stats">
            <div class="stat-card">
                <div class="stat-number">1.2M</div>
                <p style="color: #666; font-size: 0.9em;">القراء</p>
[10/2/2026 3:26 AM] مــحــمد: </div>
            <div class="stat-card">
                <div style="text-align: center; font-weight: bold; color: #667eea; font-size: 0.9em;">🎁 إعلان<br>استفد الآن!</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">500+</div>
                <p style="color: #666; font-size: 0.9em;">خبر يومي</p>
            </div>
            <div class="stat-card">
                <div style="text-align: center; font-weight: bold; color: #667eea; font-size: 0.9em;">💰 شارك<br>واكسب!</div>
            </div>
        </div>
    </div>

    <!-- Ads - Middle 1 -->
    <div class="container">
        <div class="ads-banner">
            🌟 إعلان حصري: تطبيق الأخبار الأول عربياً - نزله الآن!
        </div>
    </div>

    <!-- Controls -->
    <div class="container">
        <div class="controls">
            <div class="filter-buttons">
                <button class="filter-btn active" onclick="filterNews('all')">جميع الأخبار</button>
                <button class="filter-btn" onclick="filterNews('football')">⚽ كرة القدم</button>
                <button class="filter-btn" onclick="filterNews('basketball')">🏀 السلة</button>
                <button class="filter-btn" onclick="filterNews('tennis')">🎾 التنس</button>
            </div>
        </div>
    </div>

    <!-- News Grid with Interleaved Ads -->
    <div class="container" id="news">
        <div class="news-grid" id="newsGrid"></div>
    </div>

    <!-- Ads - Middle 2 -->
    <div class="container">
        <div class="ads-section">
            <p style="color: #667eea; font-weight: bold; margin-bottom: 10px;">🎮 إعلان 3: لعبة رياضية إلكترونية</p>
            <p style="font-size: 0.9em;">تنافس مع آلاف اللاعبين حول العالم!</p>
        </div>
        <div class="ads-banner">
            ⚡ إعلان عاجل: رابط تسجيل سريع - احصل على جائزة ترحيب 500$!
        </div>
    </div>

    <!-- More News Grid -->
    <div class="container">
        <div class="news-grid" id="newsGrid2"></div>
    </div>

    <!-- Ads - Bottom -->
    <div class="container">
        <div class="ads-section">
            <p style="color: #667eea; font-weight: bold; margin-bottom: 10px;">🏆 إعلان 4: بطولة رياضية افتراضية</p>
            <p style="font-size: 0.9em;">فرصتك للفوز بجوائز حقيقية!</p>
        </div>
        <div class="ads-banner">
            💎 إعلان نهائي: عضوية مدى الحياة بـ 99$ - عرض لا يتكرر!
        </div>
        <div class="ads-section">
            <p style="color: #667eea; font-weight: bold; margin-bottom: 10px;">🎁 إعلان 5: النشرة البريدية الحصرية</p>
            <p style="font-size: 0.9em;">احصل على أخبار قبل أي شخص آخر!</p>
            <input type="email" placeholder="بريدك الإلكتروني" style="width: 80%; padding: 8px; border-radius: 5px; border: none; margin-top: 10px;">
            <button style="padding: 8px 20px; background: #667eea; color: white; border: none; border-radius: 5px; cursor: pointer; margin-top: 10px; font-weight: bold;" onclick="clickAd()">اشترك</button>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>عن الموقع</h3>
                    <a href="#">من نحن</a>
                    <a href="#">الخصوصية</a>
                    <a href="#">الشروط</a>
                </div>
                <div class="footer-section">
                    <h3>📱 اتصل بنا</h3>
                    <a href="#">فيسبوك</a>
                    <a href="#">تويتر</a>
                    <a href="#">يوتيوب</a>
                </div>
                <div class="footer-section">
                    <h3>🎯 روابط سريعة</h3>
                    <a href="#">الأخبار</a>
                    <a href="#">البث المباشر</a>
[10/2/2026 3:26 AM] مــحــمد: <a href="#">الإحصائيات</a>
                </div>
            </div>
            <div style="padding: 20px; background: rgba(102,126,234,0.1); border-radius: 8px; margin-bottom: 20px;">
                <p style="text-align: center; color: #667eea; font-weight: bold;">⭐ إعلان: حمّل تطبيقنا الآن واستمتع برسائل إعلانية شخصية!</p>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2024 SPORT ELITE | جميع الحقوق محفوظة</p>
            </div>
        </div>
    </footer>

    <script>
        const newsData = [
            { id: 1, title: 'فوز تاريخي للفريق المحلي', category: 'football', emoji: '⚽', views: '125K', description: 'فاز الفريق بنتيجة تاريخية 3-1...' },
            { id: 2, title: 'نجم عالمي جديد ينضم للفريق', category: 'football', emoji: '⚽', views: '98K', description: 'أعلن الفريق عن توقيع نجم عالمي...' },
            { id: 3, title: 'بطل كرة السلة يحقق رقماً', category: 'basketball', emoji: '🏀', views: '156K', description: 'حقق لاعب النجم رقماً قياسياً جديداً...' },
            { id: 4, title: 'بطل التنس يحسم البطولة', category: 'tennis', emoji: '🎾', views: '89K', description: 'انتصر البطل على منافسه بقوة...' },
            { id: 5, title: 'سباح عربي يحطم رقماً', category: 'swimming', emoji: '🏊', views: '112K', description: 'حقق السباح رقماً قياسياً جديداً...' },
            { id: 6, title: 'فريق جديد يفاجئ الجميع', category: 'football', emoji: '⚽', views: '234K', description: 'فريق صاعد يثبت منافسته...' }
        ];

        function renderNews(filter = 'all') {
            const newsGrid = document.getElementById('newsGrid');
            newsGrid.innerHTML = '';

            let filtered = filter === 'all' ? newsData : newsData.filter(n => n.category === filter);

            filtered.forEach((news, index) => {
                const card = document.createElement('div');
                card.className = 'news-card';
                card.innerHTML = 
                    <div class="news-card-image">${news.emoji}</div>
                    <div class="news-card-content">
                        <span class="category-badge">أخبار</span>
                        <h2>${news.title}</h2>
                        <p>${news.description}</p>
                        <button class="read-more" onclick="clickAd()">اقرأ المزيد</button>
                    </div>
                ;
                newsGrid.appendChild(card);

                // إضافة إعلان بعد كل خبرين
                if ((index + 1) % 2 === 0) {
                    const adDiv = document.createElement('div');
                    adDiv.className = 'news-card';
                    adDiv.style.background = 'linear-gradient(45deg, #667eea, #764ba2)';
                    adDiv.innerHTML = 
                        <div style="padding: 30px; color: white; text-align: center;">
                            <p style="font-size: 1.2em; font-weight: bold; margin-bottom: 10px;">🎁 إعلان حصري!</p>
                            <p style="margin-bottom: 15px;">احصل على عضويتك الذهبية الآن</p>
                            <button style="width: 100%; padding: 12px; background: white; color: #667eea; border: none; border-radius: 8px; font-weight: bold; cursor: pointer;" onclick="clickAd()">اشترك الآن</button>
                        </div>
                    ;
                    newsGrid.appendChild(adDiv);
                }
            });
        }

        function filterNews(category) {
            document.querySelectorAll('.filter-btn').forEach(btn => btn.classList.remove('active'));
            event.target.classList.add('active');
            renderNews(category);
        }

        function closePopup(id) {
            document.getElementById(id).classList.remove('show');
        }

        function clickAd() {
            alert('شكراً! سيتم توجيهك للصفحة التالية...');
        }

        window.addEventListener('load', function() {
            // Pop-up 1
            setTimeout(() => {
                document.getElementById('popup1').classList.add('show');
            }, 500);
[10/2/2026 3:26 AM] مــحــمد: // Pop-up 2
            setTimeout(() => {
                document.getElementById('popup2').classList.add('show');
            }, 10000);

            renderNews();
        });
    </script>
</body>
</html>
