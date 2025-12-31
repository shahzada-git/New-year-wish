# New-year-wish
This is for you 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy New Year</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <audio autoplay loop>
    <source src="music.mp3" type="audio/mpeg">
  </audio>

  <div class="page center fade-in">
    <h1>🎉 Happy New Year 🎉</h1>
    <p>Ek naya saal, nayi umeedein, aur nayi muskaan ke saath</p>
    <a href="page2.html" class="btn">Aage Badho ➜</a>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>New Beginnings</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <audio autoplay loop>
    <source src="music.mp3" type="audio/mpeg">
  </audio>

  <div class="page center slide-up">
    <h2>✨ Nayi Shuruaat ✨</h2>
    <p>
      Is saal ke har din me khushi mile,  
      har raat sukoon de,  
      aur har sapna haqeeqat ke kareeb ho.
    </p>
    <a href="page3.html" class="btn">Aur Padho ➜</a>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>From Heart</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <audio autoplay loop>
    <source src="music.mp3" type="audio/mpeg">
  </audio>

  <div class="page center zoom-in">
    <h2>❤️ Dil Se Dua ❤️</h2>
    <p>
      Jo chala gaya, usse seekh lo.  
      Jo hai, usse sambhaal lo.  
      Jo aane wala hai, usse khule dil se apna lo.
    </p>
    <a href="page4.html" class="btn">Last Page ➜</a>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Best Wishes</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <audio autoplay loop>
    <source src="music.mp3" type="audio/mpeg">
  </audio>

  <div class="page center fade-in">
    <h2>🌟 Best Wishes 🌟</h2>
    <p>
      Aapki zindagi roshni se bhari rahe,  
      muskaan kabhi kam na ho,  
      aur ye naya saal aapko woh sab de  
      jo aap dil se chahte ho.
    </p>
    <h3>💫 Happy New Year 💫</h3>
  </div>
</body>
</html>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(120deg, #0f2027, #203a43, #2c5364);
  color: white;
  height: 100vh;
}

.page {
  height: 100vh;
  padding: 20px;
}

.center {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

h1, h2, h3 {
  margin-bottom: 15px;
}

p {
  max-width: 600px;
  font-size: 18px;
  line-height: 1.6;
}

.btn {
  margin-top: 30px;
  padding: 12px 25px;
  background: #ffcc70;
  color: #000;
  text-decoration: none;
  border-radius: 30px;
  font-weight: bold;
}

.btn:hover {
  background: #ffd98e;
}

/* Animations */
.fade-in {
  animation: fadeIn 2s ease;
}

.slide-up {
  animation: slideUp 1.5s ease;
}

.zoom-in {
  animation: zoomIn 1.5s ease;
}

@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes slideUp {
  from { transform: translateY(40px); opacity: 0; }
  to { transform: translateY(0); opacity: 1; }
}

@keyframes zoomIn {
  from { transform: scale(0.8); opacity: 0; }
  to { transform: scale(1); opacity: 1; }
}
