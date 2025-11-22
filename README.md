<!doctype html>
<html lang="ar" dir="rtl">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>روعة الطبيعة في روسيا</title>
  <script src="/_sdk/element_sdk.js"></script>
  <style>
    body {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      height: 100%;
      overflow: hidden;
    }
    
    html {
      height: 100%;
    }
    
    .presentation-container {
      width: 100%;
      height: 100%;
      position: relative;
      background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
    }
    
    .slide {
      width: 100%;
      height: 100%;
      position: absolute;
      top: 0;
      left: 0;
      display: none;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 60px;
      opacity: 0;
      transition: opacity 0.6s ease;
    }
    
    .slide.active {
      display: flex;
      opacity: 1;
    }
    
    .slide-content {
      max-width: 900px;
      text-align: center;
      background: rgba(255, 255, 255, 0.95);
      padding: 50px;
      border-radius: 20px;
      box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
    }
    
    .slide-title {
      font-size: 48px;
      font-weight: bold;
      color: #1e3c72;
      margin-bottom: 20px;
      line-height: 1.3;
    }
    
    .slide-text {
      font-size: 24px;
      color: #333;
      line-height: 1.8;
      margin-bottom: 30px;
    }
    
    .icon-container {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
      flex-wrap: wrap;
    }
    
    .icon-item {
      text-align: center;
    }
    
    .icon {
      font-size: 64px;
      margin-bottom: 10px;
    }
    
    .icon-label {
      font-size: 18px;
      color: #555;
      font-weight: 600;
    }
    
    .navigation {
      position: absolute;
      bottom: 40px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 20px;
      align-items: center;
    }
    
    .nav-button {
      background: rgba(255, 255, 255, 0.9);
      border: none;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      font-size: 24px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: all 0.3s ease;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }
    
    .nav-button:hover {
      background: #ffffff;
      transform: scale(1.1);
    }
    
    .nav-button:active {
      transform: scale(0.95);
    }
    
    .slide-indicator {
      display: flex;
      gap: 10px;
    }
    
    .indicator-dot {
      width: 12px;
      height: 12px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.5);
      cursor: pointer;
      transition: all 0.3s ease;
    }
    
    .indicator-dot.active {
      background: #ffffff;
      transform: scale(1.3);
    }
    
    .intro-slide .slide-content {
      background: linear-gradient(135deg, rgba(255, 255, 255, 0.95) 0%, rgba(240, 248, 255, 0.95) 100%);
    }
    
    .intro-title {
      font-size: 64px;
      color: #1e3c72;
      margin-bottom: 20px;
      font-weight: bold;
    }
    
    .intro-subtitle {
      font-size: 32px;
      color: #2a5298;
      margin-bottom: 40px;
    }
    
    .decorative-line {
      width: 200px;
      height: 4px;
      background: linear-gradient(90deg, transparent, #2a5298, transparent);
      margin: 30px auto;
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body>
  <div class="presentation-container"><!-- Slide 1: Intro -->
   <div class="slide active intro-slide" data-slide="0">
    <div class="slide-content">
     <div class="intro-title" id="main-title">
      روعة الطبيعة في روسيا
     </div>
     <div class="decorative-line"></div>
     <div class="intro-subtitle" id="subtitle">
      رحلة عبر المناظر الطبيعية الخلابة
     </div>
     <div class="icon-container">
      <div class="icon-item">
       <div class="icon">
        🏔️
       </div>
       <div class="icon-label">
        جبال شاهقة
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        🌲
       </div>
       <div class="icon-label">
        غابات كثيفة
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        ❄️
       </div>
       <div class="icon-label">
        ثلوج ساحرة
       </div>
      </div>
     </div>
    </div>
   </div><!-- Slide 2: Mountains -->
   <div class="slide" data-slide="1">
    <div class="slide-content">
     <div class="slide-title" id="slide1-title">
      جبال القوقاز الشامخة
     </div>
     <div class="decorative-line"></div>
     <div class="slide-text" id="slide1-text">
      تمتد سلسلة جبال القوقاز بين البحر الأسود وبحر قزوين، وتضم قمة إلبروس أعلى قمة في أوروبا. المناظر الخلابة والقمم المغطاة بالثلوج تجذب المتسلقين من جميع أنحاء العالم.
     </div>
     <div class="icon-container">
      <div class="icon-item">
       <div class="icon">
        🏔️
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        ⛷️
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        🌄
       </div>
      </div>
     </div>
    </div>
   </div><!-- Slide 3: Forests -->
   <div class="slide" data-slide="2">
    <div class="slide-content">
     <div class="slide-title" id="slide2-title">
      غابات التايغا الكثيفة
     </div>
     <div class="decorative-line"></div>
     <div class="slide-text" id="slide2-text">
      التايغا الروسية هي أكبر غابة في العالم، تمتد عبر سيبيريا بأشجارها الصنوبرية الشاهقة. هذه الغابات موطن لحيوانات نادرة مثل الدب البني والوشق السيبيري.
     </div>
     <div class="icon-container">
      <div class="icon-item">
       <div class="icon">
        🌲
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        🐻
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        🦌
       </div>
      </div>
     </div>
    </div>
   </div><!-- Slide 4: Lake Baikal -->
   <div class="slide" data-slide="3">
    <div class="slide-content">
     <div class="slide-title" id="slide3-title">
      بحيرة بايكال الساحرة
     </div>
     <div class="decorative-line"></div>
     <div class="slide-text" id="slide3-text">
      بحيرة بايكال هي أعمق وأقدم بحيرة للمياه العذبة في العالم، وتحتوي على 20% من المياه العذبة على سطح الأرض. مياهها الصافية والجليد الأزرق في الشتاء يخلقان مشهداً أسطورياً.
     </div>
     <div class="icon-container">
      <div class="icon-item">
       <div class="icon">
        🌊
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        🧊
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        🐟
       </div>
      </div>
     </div>
    </div>
   </div><!-- Slide 5: Northern Lights -->
   <div class="slide" data-slide="4">
    <div class="slide-content">
     <div class="slide-title" id="slide4-title">
      الشفق القطبي الساحر
     </div>
     <div class="decorative-line"></div>
     <div class="slide-text" id="slide4-text">
      في شمال روسيا، يمكن مشاهدة الأضواء الشمالية الخلابة ترقص في السماء. هذه الظاهرة الطبيعية المذهلة تضيء السماء بألوان خضراء وبنفسجية ساحرة، خاصة في منطقة مورمانسك.
     </div>
     <div class="icon-container">
      <div class="icon-item">
       <div class="icon">
        ✨
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        🌌
       </div>
      </div>
      <div class="icon-item">
       <div class="icon">
        ❄️
       </div>
      </div>
     </div>
    </div>
   </div><!-- Navigation -->
   <div class="navigation"><button class="nav-button" id="prev-btn" aria-label="السابق">◄</button>
    <div class="slide-indicator">
     <div class="indicator-dot active" data-slide="0"></div>
     <div class="indicator-dot" data-slide="1"></div>
     <div class="indicator-dot" data-slide="2"></div>
     <div class="indicator-dot" data-slide="3"></div>
     <div class="indicator-dot" data-slide="4"></div>
    </div><button class="nav-button" id="next-btn" aria-label="التالي">►</button>
   </div>
  </div>
  <script>
    const defaultConfig = {
      main_title: "روعة الطبيعة في روسيا",
      subtitle: "رحلة عبر المناظر الطبيعية الخلابة",
      slide1_title: "جبال القوقاز الشامخة",
      slide1_text: "تمتد سلسلة جبال القوقاز بين البحر الأسود وبحر قزوين، وتضم قمة إلبروس أعلى قمة في أوروبا. المناظر الخلابة والقمم المغطاة بالثلوج تجذب المتسلقين من جميع أنحاء العالم.",
      slide2_title: "غابات التايغا الكثيفة",
      slide2_text: "التايغا الروسية هي أكبر غابة في العالم، تمتد عبر سيبيريا بأشجارها الصنوبرية الشاهقة. هذه الغابات موطن لحيوانات نادرة مثل الدب البني والوشق السيبيري.",
      slide3_title: "بحيرة بايكال الساحرة",
      slide3_text: "بحيرة بايكال هي أعمق وأقدم بحيرة للمياه العذبة في العالم، وتحتوي على 20% من المياه العذبة على سطح الأرض. مياهها الصافية والجليد الأزرق في الشتاء يخلقان مشهداً أسطورياً.",
      slide4_title: "الشفق القطبي الساحر",
      slide4_text: "في شمال روسيا، يمكن مشاهدة الأضواء الشمالية الخلابة ترقص في السماء. هذه الظاهرة الطبيعية المذهلة تضيء السماء بألوان خضراء وبنفسجية ساحرة، خاصة في منطقة مورمانسك.",
      primary_color: "#1e3c72",
      secondary_color: "#2a5298",
      text_color: "#333333",
      background_color: "#ffffff",
      font_family: "Segoe UI",
      font_size: 16
    };

    let currentSlide = 0;
    const totalSlides = 5;

    async function onConfigChange(config) {
      const mainTitle = config.main_title || defaultConfig.main_title;
      const subtitle = config.subtitle || defaultConfig.subtitle;
      const slide1Title = config.slide1_title || defaultConfig.slide1_title;
      const slide1Text = config.slide1_text || defaultConfig.slide1_text;
      const slide2Title = config.slide2_title || defaultConfig.slide2_title;
      const slide2Text = config.slide2_text || defaultConfig.slide2_text;
      const slide3Title = config.slide3_title || defaultConfig.slide3_title;
      const slide3Text = config.slide3_text || defaultConfig.slide3_text;
      const slide4Title = config.slide4_title || defaultConfig.slide4_title;
      const slide4Text = config.slide4_text || defaultConfig.slide4_text;
      
      const primaryColor = config.primary_color || defaultConfig.primary_color;
      const secondaryColor = config.secondary_color || defaultConfig.secondary_color;
      const textColor = config.text_color || defaultConfig.text_color;
      const backgroundColor = config.background_color || defaultConfig.background_color;
      const fontFamily = config.font_family || defaultConfig.font_family;
      const fontSize = config.font_size || defaultConfig.font_size;

      document.getElementById('main-title').textContent = mainTitle;
      document.getElementById('subtitle').textContent = subtitle;
      document.getElementById('slide1-title').textContent = slide1Title;
      document.getElementById('slide1-text').textContent = slide1Text;
      document.getElementById('slide2-title').textContent = slide2Title;
      document.getElementById('slide2-text').textContent = slide2Text;
      document.getElementById('slide3-title').textContent = slide3Title;
      document.getElementById('slide3-text').textContent = slide3Text;
      document.getElementById('slide4-title').textContent = slide4Title;
      document.getElementById('slide4-text').textContent = slide4Text;

      document.querySelector('.presentation-container').style.background = `linear-gradient(135deg, ${primaryColor} 0%, ${secondaryColor} 100%)`;
      
      const allTitles = document.querySelectorAll('.slide-title, .intro-title');
      allTitles.forEach(title => {
        title.style.color = primaryColor;
        title.style.fontFamily = `${fontFamily}, 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`;
      });

      document.querySelector('.intro-subtitle').style.color = secondaryColor;
      document.querySelector('.intro-subtitle').style.fontFamily = `${fontFamily}, 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`;

      const allTexts = document.querySelectorAll('.slide-text, .icon-label');
      allTexts.forEach(text => {
        text.style.color = textColor;
        text.style.fontFamily = `${fontFamily}, 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`;
      });

      const allContents = document.querySelectorAll('.slide-content');
      allContents.forEach(content => {
        content.style.background = `rgba(255, 255, 255, 0.95)`;
      });

      document.querySelector('.intro-title').style.fontSize = `${fontSize * 4}px`;
      document.querySelector('.intro-subtitle').style.fontSize = `${fontSize * 2}px`;
      allTitles.forEach(title => {
        if (!title.classList.contains('intro-title')) {
          title.style.fontSize = `${fontSize * 3}px`;
        }
      });
      allTexts.forEach(text => {
        if (text.classList.contains('slide-text')) {
          text.style.fontSize = `${fontSize * 1.5}px`;
        } else {
          text.style.fontSize = `${fontSize * 1.125}px`;
        }
      });
    }

    function showSlide(index) {
      const slides = document.querySelectorAll('.slide');
      const dots = document.querySelectorAll('.indicator-dot');
      
      slides.forEach(slide => {
        slide.classList.remove('active');
      });
      
      dots.forEach(dot => {
        dot.classList.remove('active');
      });
      
      slides[index].classList.add('active');
      dots[index].classList.add('active');
      currentSlide = index;
    }

    document.getElementById('next-btn').addEventListener('click', () => {
      const nextSlide = (currentSlide + 1) % totalSlides;
      showSlide(nextSlide);
    });

    document.getElementById('prev-btn').addEventListener('click', () => {
      const prevSlide = (currentSlide - 1 + totalSlides) % totalSlides;
      showSlide(prevSlide);
    });

    document.querySelectorAll('.indicator-dot').forEach((dot, index) => {
      dot.addEventListener('click', () => {
        showSlide(index);
      });
    });

    document.addEventListener('keydown', (e) => {
      if (e.key === 'ArrowRight' || e.key === 'ArrowLeft') {
        if (e.key === 'ArrowRight') {
          const prevSlide = (currentSlide - 1 + totalSlides) % totalSlides;
          showSlide(prevSlide);
        } else {
          const nextSlide = (currentSlide + 1) % totalSlides;
          showSlide(nextSlide);
        }
      }
    });

    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange,
        mapToCapabilities: (config) => ({
          recolorables: [
            {
              get: () => config.primary_color || defaultConfig.primary_color,
              set: (value) => {
                config.primary_color = value;
                window.elementSdk.setConfig({ primary_color: value });
              }
            },
            {
              get: () => config.secondary_color || defaultConfig.secondary_color,
              set: (value) => {
                config.secondary_color = value;
                window.elementSdk.setConfig({ secondary_color: value });
              }
            },
            {
              get: () => config.text_color || defaultConfig.text_color,
              set: (value) => {
                config.text_color = value;
                window.elementSdk.setConfig({ text_color: value });
              }
            },
            {
              get: () => config.background_color || defaultConfig.background_color,
              set: (value) => {
                config.background_color = value;
                window.elementSdk.setConfig({ background_color: value });
              }
            }
          ],
          borderables: [],
          fontEditable: {
            get: () => config.font_family || defaultConfig.font_family,
            set: (value) => {
              config.font_family = value;
              window.elementSdk.setConfig({ font_family: value });
            }
          },
          fontSizeable: {
            get: () => config.font_size || defaultConfig.font_size,
            set: (value) => {
              config.font_size = value;
              window.elementSdk.setConfig({ font_size: value });
            }
          }
        }),
        mapToEditPanelValues: (config) => new Map([
          ["main_title", config.main_title || defaultConfig.main_title],
          ["subtitle", config.subtitle || defaultConfig.subtitle],
          ["slide1_title", config.slide1_title || defaultConfig.slide1_title],
          ["slide1_text", config.slide1_text || defaultConfig.slide1_text],
          ["slide2_title", config.slide2_title || defaultConfig.slide2_title],
          ["slide2_text", config.slide2_text || defaultConfig.slide2_text],
          ["slide3_title", config.slide3_title || defaultConfig.slide3_title],
          ["slide3_text", config.slide3_text || defaultConfig.slide3_text],
          ["slide4_title", config.slide4_title || defaultConfig.slide4_title],
          ["slide4_text", config.slide4_text || defaultConfig.slide4_text]
        ])
      });
    }
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9a2b62a7975ce201',t:'MTc2Mzg0NTUzMC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
