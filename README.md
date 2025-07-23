<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <title>فرحمودة ❤️</title>
  <style>
    body {
      margin: 0;
      font-family: 'Cairo', sans-serif;
      background: linear-gradient(to top right, #fff0f5, #ffffff);
      color: #4d004d;
      overflow-x: hidden;
      text-align: center;
      direction: rtl;
    }
    .background-text {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 120px;
      color: rgba(255, 182, 193, 0.1);
      font-weight: bold;
      z-index: 0;
      pointer-events: none;
      user-select: none;
    }
    .welcome {
      padding: 100px 20px;
      position: relative;
      z-index: 1;
    }
    .welcome h1 {
      font-size: 36px;
      color: #cc0066;
      margin-bottom: 20px;
    }
    button {
      font-size: 20px;
      padding: 12px 30px;
      background-color: #ff66b2;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: background 0.3s;
      margin: 5px;
    }
    button:hover {
      background-color: #e60073;
    }
    .message {
      display: none;
      padding: 50px 30px;
      max-width: 800px;
      margin: auto;
      font-size: 20px;
      line-height: 2.2;
      position: relative;
      z-index: 1;
      text-align: right;
    }
    .heart-names {
      font-size: 24px;
      margin-top: 20px;
      color: #d4006b;
      font-weight: bold;
    }
    .hearts {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 0;
    }
    .heart {
      position: absolute;
      width: 20px;
      height: 20px;
      background: pink;
      transform: rotate(45deg);
      animation: float 6s infinite ease-in-out;
    }
    .heart::before,
    .heart::after {
      content: '';
      position: absolute;
      width: 20px;
      height: 20px;
      background: pink;
      border-radius: 50%;
    }
    .heart::before {
      top: -10px;
      left: 0;
    }
    .heart::after {
      left: -10px;
      top: 0;
    }
    @keyframes float {
      0% {
        transform: translateY(0) rotate(45deg);
        opacity: 1;
      }
      100% {
        transform: translateY(-800px) rotate(45deg);
        opacity: 0;
      }
    }

    /* الزر الخاص بالعبارات ومحتواها */
    .dropdown-container {
      margin: 40px auto;
      max-width: 800px;
      position: relative;
    }
    .main-dropdown-btn {
      background-color: #cc3399;
      width: 100%;
      font-size: 22px;
      font-weight: bold;
      border-radius: 12px;
    }
    .dropdown-content {
      display: none;
      margin-top: 15px;
      text-align: right;
      direction: rtl;
    }
    .dropdown-content button {
      background-color: #ff99cc;
      width: 100%;
      font-size: 18px;
      margin: 5px 0;
      border-radius: 10px;
      padding: 12px 20px;
    }
    .dropdown-content button:hover {
      background-color: #ff66b2;
    }
    .phrase-display {
      margin-top: 20px;
      background-color: #ffe6f2;
      padding: 20px;
      border-radius: 12px;
      min-height: 130px;
      font-size: 20px;
      color: #660033;
      white-space: pre-line; /* للحفاظ على تنسيق النصوص */
      text-align: right;
      direction: rtl;
    }
  </style>
</head>
<body>

  <div class="background-text">Farah</div>

  <div class="hearts">
    <div class="heart" style="left:5%; animation-delay: 0s;"></div>
    <div class="heart" style="left:20%; animation-delay: 1s;"></div>
    <div class="heart" style="left:40%; animation-delay: 2s;"></div>
    <div class="heart" style="left:60%; animation-delay: 3s;"></div>
    <div class="heart" style="left:80%; animation-delay: 4s;"></div>
    <div class="heart" style="left:90%; animation-delay: 5s;"></div>
  </div>

  <div class="welcome" id="welcome-screen">
    <h1>فراااحتي 💖💝</h1>
    <p>أدخلي قرأي كم صفة عنك يا حياتيي 😍💕</p>
    <button onclick="showMessage()">ادخلي يا عمري 💌😘</button>
  </div>

  <div class="message" id="message-box">
    <div class="heart-names">❤️ حمودي 💕 فروحة ❤️</div>
    <br /><br />
    <p>
      إلى من أهوى   إلى من أحب      إلى من أعشق ( من كل قلبي )     إلى صغريتي      إلى نبضُ قلبي     إلى بنوتةٍ عشِقتني     إلى أميرةٍ إختارتني أميراً لها     إلى تِلك التي هي قمرٌ يُضيءُ في سمائي     إلى تِلك التي هي جَمَلَتْ أيامي     إلى تِلك التي هو طيبٌ قلبها    إلى تلك التي هي عزيزةٌ على قلبي     إلى تلك التي تضيءُ في ظُلمةِ الحياة     إلى حبيبتي و حبيبةُ قلبي     إلى غاليتي و نور عيني     إلى جميلتي و وردة حياتي    إلى صغيرتي و نبض قلبي    إلى فَرحَةُ عُمري و أيامي       إلى بنوتتي الصغيرة
      إلى فروحتي الحبيبة    الغالية    الجميلة 
      أُحِبُكِ حُباً شديداً    و أحببتُ الحُبَ فيكِ
      حباً نابعاً من القلب نابعاً من الروح
      و أعشقُكِ عِشقاً كثيراً     بدايتاً دوون نِهاية
      و مُتعلِقاً بكِ تعلُقاً كبيراً    متيناً
      قلبي بقلبك و قلبكِ بقلبي   مُترابِطينَ معاً
      روحي أنت و أنت روحي    و أنا روحكِ أيضاً
      أنا انت و أنت أنا     لا فرق بيننا أبداً
      أُحِبُكِ و تُحبينني  أشتاقُ إليكِ و تشتاقينَ إلي
      أغارُ عليكِ و تغارينَ علي
      لست حاسداً يا فرحتي لكنني أحسُدُ و مِن كُلِ قلبي   من يُمكِنهُ التقربَ مِنكِ  بالوقت الذي يُريد و يَتحدثُ معكِ و يُكلِمكُ متى يشااء و يَنظرُ إلى وجهكِ و عينيكِ المُصنفتانِ عالمياً بالجمال  احسُدهم يا فرحتي    محرومٌ أنا من كُلِ ما ذكرت
      لكِنَ وجودَكِ معي يُعوضُني عن كُلِ شيء 
      كافي لأن ينسيني ما وُجِعتُ و ما فُجِعتُ و ما صُدِمت
      عن كُلِ شيءٍ يا فروحتي الغالية
      عن لحظاتِي التعيسة   التي لم أَراها مُنذُ عَشقِت
      أنتِ كُلُ شيءٍ جميلٍ بحياتي يا فرح
      أنتِ جمالُ حياتي و مُجمَلِها
      مُنذُ أن عرِفتُكِ    أحببتُ الحياةَ بكِ
      أنت الفرح و بكل معناً للفرح ♡
      يا دبدوبتي يا فرحة الفرافيح 🥲❤️ 

      — <strong>محبك إلى الأبد وحبيب قلبك  حمودي 💖</strong>

                 — <strong>بحببببك يا كتكوتة قلبيي 😍😘❤️</strong>
     
                 — <strong>فرحمودة  🩷🫂</strong>
    </p>

    <!-- زر ثالث صور + نص -->
    <div style="margin-top:40px; text-align: right; direction: rtl;">
      <h3>علاقتنا اللي دامت خمس سنين ❤️</h3>
      <button onclick="toggleImages()" style="background:#d6336c; padding: 12px 25px; border-radius: 12px;">من حمودتك يا فروحة  🥺🫂💖</button>
      <div id="image-gallery" style="display:none; margin-top: 20px;">
        <img src="https://i.pinimg.com/736x/d3/53/b3/d353b3d5c1fedef83069d09e304bfb18.jpg" alt="صورة 1" style="max-width: 100%; border-radius: 15px; margin-bottom: 15px;" />
        <img src="https://mr7bagulf.com/wp-content/uploads/2024/08/image002-149.png" alt="صورة 2" style="max-width: 100%; border-radius: 15px; margin-bottom: 15px;" />
        <p style="font-size: 18px; color: #800040; max-width: 800px; margin: auto; text-align: center;">
          خمس سنوات من الحب، الضحك، الدعم، والذكريات التي لا تُنسى. مع كل لحظة، يكبر حبنا ويزداد عمقًا. أنتِ دنيتي وحياتي وقلبي. 💖
        </p>
      </div>
    </div>

    <!-- زر رابع: عبارات مقربة من قلبك -->
    <div class="dropdown-container">
      <button class="main-dropdown-btn" onclick="toggleDropdown()">عبارات مقربة من قلبك 💬</button>
      <div class="dropdown-content" id="dropdown-content">
        <button onclick="showPhrase(0)">- مادُمت على قيد الحياة فاحلم ، وجاهِد لتصِل🤎!</button>
        <button onclick="showPhrase(1)">🌸</button>
        <button onclick="showPhrase(2)">*خلف الصبر أشياء جميلة تنتظر 🩵🖇️*</button>
        <button onclick="showPhrase(3)">🌸 ثُم تأتي مُعجزات الله .. 🤍 ...</button>
        <button onclick="showPhrase(4)">*أؤمن من أعماق قلبي بأن هنالك بداية جديدة لكل شيء ...*</button>
        <button onclick="showPhrase(5)">ولأنك وعدت أن السعي لا يضيع...</button>
      </div>
      <div class="phrase-display" id="phrase-display">
        اضغطي على شي زر يا كتكوتي من شان اعرض العبارة يلي بتحبيها    قصدي يلي سرقتهم من عندك 🥲🤗😘
      </div>
    </div>
  </div>

  <script>
    const phrases = [
      "-مادُمت على قيد الحياة فاحلم ، وجاهِد لتصِل🤎!",
      `🌸
ثُم تأتي مُعجزات الله .. 🤍
ويقلب الموازين لأجل دعوة كُنت تَلح بها في جوف الليل ، فيجبرك جبرًا يليق بعظمته ، لتنسى كُل كسر مررت به ، وكل حزن أصاب قلبك ، وكل هم أثقل كتفك ، وكل دمعة ذَرفت من عينيك
ولأنهُ الله سَيستجيب ، سَيجبرك ، سَيكرمك ، سَيُغنيك ، سَيكفيك
سَيُذيقك حَلاوة الجبر بعد مَرارة الكسر
اصبر إن بعد الصبر بُشرى ، فَصَبْرٌ جَمِيلٌ وَاللَّهُ الْمُسْتَعَانُ`,
      "*خلف الصبر أشياء جميلة تنتظر 🩵🖇️*\n𝒃𝒆𝒉𝒊𝒏𝒅 𝒑𝒂𝒕𝒊𝒆𝒏𝒄𝒆, 𝒃𝒆𝒂𝒖𝒕𝒊𝒇𝒖𝒍 𝒕𝒉𝒊𝒏𝒈𝒔 𝒂𝒘𝒂𝒊𝒕",
      `🌸
ثُم تأتي مُعجزات الله .. 🤍
ويقلب الموازين لأجل دعوة كُنت تَلح بها في جوف الليل ، فيجبرك جبرًا يليق بعظمته ، لتنسى كُل كسر مررت به ، وكل حزن أصاب قلبك ، وكل هم أثقل كتفك ، وكل دمعة ذَرفت من عينيك
ولأنهُ الله سَيستجيب ، سَيجبرك ، سَيكرمك ، سَيُغنيك ، سَيكفيك
سَيُذيقك حَلاوة الجبر بعد مَرارة الكسر
اصبر إن بعد الصبر بُشرى ، فَصَبْرٌ جَمِيلٌ وَاللَّهُ الْمُسْتَعَانُ`,
      `*أؤمن من أعماق قلبي بأن هنالك بداية جديدة لكل شيء وأن الحياة متجددة دائماً ولا تقتصر على حال واحدة💫🤎.*`,
      `ولأنك وعدت أن السعي لا يضيع،  
ها أنا يا الله أمضي بقلبي وعقلي،  
أرجو توفيقك مع كل خطوة،  
وأسألك أن تُتمّ نعمك عليّ بالرضا واليقين.  
اجعل جهدي خالصًا لك،  
واكتب لي الوصول الجميل،  
وامنحني لذّة الشكر قبل النهايات وبعدها،  
لأحكي عن كرمك ما حييت ✨🤍`
    ];

    function showMessage() {
      document.getElementById('welcome-screen').style.display = 'none';
      document.getElementById('message-box').style.display = 'block';
    }

    function toggleImages() {
      const gallery = document.getElementById('image-gallery');
      gallery.style.display = (gallery.style.display === 'none' || gallery.style.display === '') ? 'block' : 'none';
    }

    function toggleDropdown() {
      const dropdown = document.getElementById('dropdown-content');
      dropdown.style.display = (dropdown.style.display === 'block') ? 'none' : 'block';
    }

    function showPhrase(index) {
      const phraseDisplay = document.getElementById('phrase-display');
      phraseDisplay.textContent = phrases[index];
    }
  </script>
</body>
</html>
