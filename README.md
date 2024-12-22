# 👨‍💻 Tran Minh Thuong (MinhThuongTMT)

🌟 **Welcome to my GitHub Profile!**  
🚀 Passionate about **IoT Embedded Programming**, **Web Development**, and **AI Solutions**.  
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dynamic Tagline</title>
  <style>
    /* Reset mặc định */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    /* Toàn bộ trang */
    body {
      font-family: 'Arial', sans-serif;
      background-color: #0d1117; /* Màu nền tối */
      color: #c9d1d9; /* Màu chữ sáng */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    /* Hiển thị câu tagline */
    .tagline {
      font-size: 2rem;
      font-weight: bold;
      text-align: center;
      line-height: 1.5;
    }

    /* Chữ thay đổi */
    .changing-text {
      color: #39d353; /* Màu xanh nổi bật */
      display: inline-block;
      animation: fadeInOut 5s infinite;
    }

    /* Hiệu ứng động fade-in, fade-out */
    @keyframes fadeInOut {
      0%, 100% {
        opacity: 0;
        transform: translateY(-10px);
      }
      10%, 90% {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="tagline">
    🌍 Turning <span class="changing-text"></span> into reality, one line of code at a time.
  </div>

  <script>
    // Mảng chứa các từ sẽ thay đổi
    const words = ["ideas", "dreams", "innovation", "concepts", "visions"];
    let wordIndex = 0; // Vị trí từ hiện tại
    const changingTextElement = document.querySelector('.changing-text');

    // Hàm để thay đổi từ
    function updateWord() {
      changingTextElement.textContent = words[wordIndex];
      wordIndex = (wordIndex + 1) % words.length; // Lặp lại danh sách từ
    }

    // Cập nhật từ đầu tiên và thiết lập khoảng thời gian thay đổi
    updateWord();
    setInterval(updateWord, 5000); // Thay đổi mỗi 5 giây
  </script>
</body>
</html>


---

## 🛠 Skills & Technologies

### 🔥 Programming Languages:
![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white&style=for-the-badge)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![HTML](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge)
![Dart](https://img.shields.io/badge/-Dart-0175C2?logo=dart&logoColor=white&style=for-the-badge)

### 🧰 Tools & Frameworks:
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=for-the-badge)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=for-the-badge)
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?logo=firebase&logoColor=black&style=for-the-badge)

### 📱 IoT & Embedded:
![Arduino](https://img.shields.io/badge/-Arduino-00979D?logo=arduino&logoColor=white&style=for-the-badge)
![ESP8266](https://img.shields.io/badge/-ESP8266-006FBA?style=for-the-badge)
![ESP32](https://img.shields.io/badge/-ESP32-003B57?style=for-the-badge)

---

## 🌟 Featured Projects

### 🎄 Festive Projects:
- 🎅 [Merry_Christmas](https://github.com/MinhThuongTMT/Merry_Christmas): CSS-based Christmas-themed project.
- 🎆 [HappyNewYear_2025](https://github.com/MinhThuongTMT/HappyNewYear_2025): JavaScript-powered New Year celebration project.
- 🌲 [CayThongNoel](https://github.com/MinhThuongTMT/caythongnoel): Full code for a Christmas tree (2024).

### 🕹️ Games & Fun:
- 🐍 [Snake_game](https://github.com/MinhThuongTMT/Snake_game): Python implementation of the classic snake game.

### 🧮 Tools & Utilities:
- 🖩 [Casio_calculator](https://github.com/MinhThuongTMT/Casio_calculator): A Python-based calculator.
- ✋ [OpenCv_Finger](https://github.com/MinhThuongTMT/OpenCv_Finger): Hand gesture recognition using OpenCV.

### 🌐 Web Development:
- 🌟 [MyWeb](https://github.com/MinhThuongTMT/MyWeb): HTML project showcasing web design skills.
- 🔐 [web_login_signup](https://github.com/MinhThuongTMT/web_login_signup): User authentication system.
- 🎨 [Website_Profile](https://github.com/MinhThuongTMT/Website_Profile): Personal profile website using CSS.
- 🎥 [Slide_picture](https://github.com/MinhThuongTMT/Slide_picture): Image slider for websites.
- 🔦 [Web_dark-mode](https://github.com/MinhThuongTMT/Web_dark-mode): Toggleable dark mode project.
- 🇻🇳🇺🇸 [Web_VN-EN](https://github.com/MinhThuongTMT/Web_VN-EN): Multi-language website.

### 🧑‍🔬 Research & IoT:
- 🌾 [Project_SmartFarm](https://github.com/MinhThuongTMT/Project_SmartFarm): IoT smart farm project.
- 📱 [App_Healthy](https://github.com/MinhThuongTMT/App_Healthy): Flutter app for health monitoring.
- ⚙️ [All_CodeProject](https://github.com/MinhThuongTMT/All_CodeProject): Research and development of health monitoring devices.
- 🌱 [smart_farm](https://github.com/MinhThuongTMT/smart_farm): Smart farm UI using CSS.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MinhThuongTMT&show_icons=true&theme=radical" alt="MinhThuongTMT's GitHub Stats" height="180px"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MinhThuongTMT&theme=radical" alt="GitHub Streak" height="180px"/>
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MinhThuongTMT&layout=compact&theme=radical" alt="Top Languages" height="180px"/>
</p>

---

## 🤝 Connect with Me

- 🌐 **Portfolio Website:[TranMinhThuong.com](https://myweb-tmt.vercel.app/)
- 💼 **LinkedIn:** [Tran Minh Thuong](https://www.linkedin.com)
- 📧 **Email:** tranminhthuong08082003@gmail.com
- 🌍 **Facebook:** [Facebook Profile](https://www.facebook.com/trannminh.thuongg)

---

## ✨ Fun Fact
Coding feels like magic until it becomes debugging... then it’s just a puzzle! 🔍
