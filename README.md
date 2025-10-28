# Ch-n-g-
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chân Gà Sốt Thái</title>
  <!-- Font chữ kiểu Nhật -->
  <link href="https://fonts.googleapis.com/css2?family=Sawarabi+Gothic&display=swap" rel="stylesheet">
  <!-- Font Awesome cho icon -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Sawarabi Gothic', sans-serif;
      background-color: #E8F4FF; /* xanh nhạt */
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #0096FF; /* xanh đậm */
      color: white;
      text-align: center;
      padding: 20px 10px;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    main {
      padding: 20px;
      max-width: 800px;
      margin: auto;
      background-color: white; /* nội dung nền trắng */
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    img {
      max-width: 100%;
      border-radius: 10px;
      display: block;
      margin: 20px auto;
    }
    section {
      margin-bottom: 30px;
    }
    h2 {
      color: #0096FF;
      margin-bottom: 10px;
      border-bottom: 2px solid #0096FF;
      display: inline-block;
      padding-bottom: 5px;
    }
    ul {
      padding-left: 0;
      list-style: none;
    }
    li {
      margin-bottom: 10px;
      font-size: 1rem;
    }
    /* Icon trước mỗi mục */
    li::before {
      font-family: "Font Awesome 6 Free";
      font-weight: 900;
      color: #0096FF;
      display: inline-block;
      width: 25px;
    }
    /* Icon riêng cho nguyên liệu */
    #ingredients li::before {
      content: "\f372"; /* icon carrot */
    }
    /* Icon riêng cho cách làm */
    #recipe li::before {
      content: "\f2e7"; /* icon utensils */
    }
    footer {
      background-color: #0096FF;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
      border-radius: 0 0 10px 10px;
    }
    a {
      text-decoration: none;
    }
    /* Thông tin liên hệ màu đen */
    #contact a, #contact p {
      color: #000;
    }
    /* Thêm một chút hiệu ứng hover cho liên hệ */
    #contact a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Chân Gà Sốt Thái 🍗</h1>
  </header>

  <main>
    <!-- Hình ảnh minh họa -->
    <section id="image">
      <img src="https://i.imgur.com/7YVdF7Q.jpg" alt="Chân Gà Sốt Thái">
    </section>

    <!-- Giới thiệu -->
    <section id="intro">
      <h2>Giới thiệu 📝</h2>
      <p>Chân gà sốt Thái là món ăn vặt ngon miệng, kết hợp hương vị chua cay đặc trưng của Thái Lan với chân gà giòn sần sật. Món này phù hợp làm snack, nhậu hay ăn cùng cơm đều tuyệt vời.</p>
    </section>

    <!-- Hương vị -->
    <section id="taste">
      <h2>Hương vị 🌶️</h2>
      <p>Vị chua cay hòa quyện với vị ngọt thanh và thơm mùi tỏi, ớt, sả. Chân gà mềm nhưng vẫn giữ độ giòn, tạo cảm giác ngon miệng khó quên.</p>
    </section>

    <!-- Nguyên liệu -->
    <section id="ingredients">
      <h2>Nguyên liệu 🥕</h2>
      <ul>
        <li>Chân gà: 500g</li>
        <li>Tỏi băm: 2 tép</li>
        <li>Ớt băm: 1-2 quả</li>
        <li>Chanh: 1 quả</li>
        <li>Đường: 1 muỗng canh</li>
        <li>Nước mắm: 2 muỗng canh</li>
        <li>Hành lá, rau mùi</li>
      </ul>
    </section>

    <!-- Cách sơ chế -->
    <section id="preparation">
      <h2>Cách sơ chế 🔪</h2>
      <ul>
        <li>Rửa sạch chân gà, cắt bỏ móng.</li>
        <li>Luộc chân gà với nước sôi khoảng 10 phút cho chín mềm.</li>
        <li>Vớt ra, ngâm vào nước đá để chân gà săn và giòn.</li>
      </ul>
    </section>

    <!-- Cách làm -->
    <section id="recipe">
      <h2>Cách làm 🍴</h2>
      <ul>
        <li>Phi tỏi và ớt cho thơm, thêm nước mắm, đường, nước cốt chanh tạo nước sốt.</li>
        <li>Cho chân gà đã sơ chế vào trộn đều với nước sốt.</li>
        <li>Rắc hành lá và rau mùi lên trên, trộn nhẹ và thưởng thức.</li>
      </ul>
    </section>

    <!-- Thông tin liên hệ -->
    <section id="contact">
      <h2>Thông tin liên hệ 📞</h2>
      <p>Số điện thoại: <a href="tel:0329980234">0329980234</a></p>
      <p>Email: <a href="mailto:nguynphglinh16@gmail.com">nguynphglinh16@gmail.com</a></p>
    </section>

  </main>

  <footer>
    © 2025 Chân Gà Sốt Thái – Fanpage
  </footer>

</body>
</html>
