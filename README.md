# WONDER-LAND<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WONDERLAND | Winning Color</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- 헤더 -->
  <header class="header">
    <img src="assets/logo.svg" alt="WONDERLAND 로고" class="logo" />
    <nav class="nav">
      <a href="#">About</a>
      <a href="#">Colors</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <!-- 메인 히어로 섹션 -->
  <section class="hero">
    <div class="hero-content">
      <h1>Discover Your <span>Winning Color</span></h1>
      <p>당신만의 색을 찾아드리는 컬러 브랜드, WONDERLAND.</p>
      <a href="#" class="btn">Explore Colors</a>
    </div>
  </section>

  <!-- 컬러 소개 섹션 -->
  <section class="colors">
    <div class="color-card">
      <img src="assets/color-1.jpg" alt="컬러 1" />
      <h3>Serene Blue</h3>
      <p>잔잔하지만 강한 인상을 주는 블루.</p>
    </div>
    <div class="color-card">
      <img src="assets/color-2.jpg" alt="컬러 2" />
      <h3>Golden Glow</h3>
      <p>자신감과 따뜻함이 느껴지는 골드 톤.</p>
    </div>
    <div class="color-card">
      <img src="assets/color-3.jpg" alt="컬러 3" />
      <h3>Pure White</h3>
      <p>모든 색의 시작, 완전한 여백의 미.</p>
    </div>
  </section>

  <!-- 푸터 -->
  <footer class="footer">
    <p>© 2025 WONDERLAND | Designed with Minimal Passion</p>
  </footer>
</body>
</html>

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Helvetica Neue', Arial, sans-serif;
}

/* Body */
body {
  background-color: #fff;
  color: #111;
  line-height: 1.6;
}

/* Header */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem 5%;
  position: fixed;
  width: 100%;
  background-color: rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(10px);
  z-index: 100;
  border-bottom: 1px solid #eee;
}

.logo {
  width: 140px;
  height: auto;
}

.nav a {
  margin-left: 2rem;
  text-decoration: none;
  color: #111;
  font-size: 0.95rem;
  transition: color 0.3s ease;
}

.nav a:hover {
  color: #777;
}

/* Hero */
.hero {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  background-color: #f5f5f5;
}

.hero-content {
  max-width: 700px;
}

.hero h1 {
  font-size: 3rem;
  font-weight: 600;
  letter-spacing: -1px;
}

.hero h1 span {
  color: #d2a679;
}

.hero p {
  margin-top: 1rem;
  color: #555;
}

.btn {
  display: inline-block;
  margin-top: 2rem;
  padding: 0.8rem 1.6rem;
  background-color: #111;
  color: #fff;
  text-decoration: none;
  border-radius: 25px;
  font-size: 0.9rem;
  transition: all 0.3s ease;
}

.btn:hover {
  background-color: #d2a679;
  color: #fff;
}

/* Colors section */
.colors {
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding: 6rem 5%;
  background-color: #fff;
}

.color-card {
  width: 280px;
  text-align: center;
}

.color-card img {
  width: 100%;
  border-radius: 20px;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
}

.color-card h3 {
  margin-top: 1.2rem;
  font-size: 1.2rem;
}

.color-card p {
  color: #666;
  font-size: 0.9rem;
  margin-top: 0.5rem;
}

/* Footer */
.footer {
  text-align: center;
  padding: 3rem 0;
  background-color: #f5f5f5;
  font-size: 0.8rem;
  color: #777;
}
