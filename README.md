<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="device-width, initial-scale=1.0">
  <title>Job seek - Website học tiếng Anh</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #2f63ff;
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .logo {
      display: flex;
      align-items: center;
    }
    .logo svg {
      width: 40px;
      height: 40px;
      margin-right: 10px;
    }
    nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    nav a {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
    }
    .article {
      padding: 20px;
    }
    .article img {
      width: 100%;
      max-width: 400px;
      height: auto;
      display: block;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
    <nav>
        <a href="5.html">Trang chủ</a>
        <a href="1.html">Giới thiệu</a>
        <a href="2.html">Tuyển dụng</a>
        <a href="3.html">Việc làm</a>
        <a href="4.html">Đăng ký</a>
      </nav>
<header>
  <div class="logo">
    <!-- SVG logo -->
    <svg viewBox="0 0 64 64" fill="#ffffff" xmlns="http://www.w3.org/2000/svg">
      <circle cx="32" cy="32" r="30" stroke="#ffe700" stroke-width="4" fill="#2fcbff"></circle>
      <text x="32" y="40" text-anchor="middle" font-size="20" fill="#ffffff" font-family="Arial">J</text>
    </svg>
    <h1>Job seek</h1>
  </div>
</header>

<section class="article">
  <h2>🌟 Tuyển dụng Nhân viên Marketing</h2>
  <img src="https://via.placeholder.com/400x200" alt="Marketing Image">
  <p><strong>Vị trí:</strong> Nhân viên Marketing</p>
  <p><strong>Mức lương:</strong> 10 - 15 triệu VNĐ</p>
  <p><strong>Mô tả:</strong> Làm việc tại văn phòng Hà Nội, yêu cầu có kinh nghiệm từ 1 năm trở lên, có khả năng giao tiếp và sáng tạo nội dung tốt.</p>
</section>

</body>
</html>

2
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="device-width, initial-scale=1.0">
  <title>Câu 2</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background: #ffffff;
      text-align: center;
    }
    .item {
      width: 150px;
      height: 100px;
      background-color: #00b253;
      display: inline-block;
      margin: 10px;
      border-radius: 8px;
      box-shadow: 0 2px 5px #000;
    }
    .advert {
      width: 100%;
      max-width: 600px;
      height: 200px;
      margin: 30px auto;
      border: 2px solid #2f63ff;
      background-color: #2fcbff;
      line-height: 200px;
      font-weight: bold;
      color: #000;
      border-radius: 10px;
      box-shadow: 0 2px 8px #999999;
    }
    nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    nav a {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
    }
  </style>
</head>
<body>
    <nav>
        <a href="5.html">Trang chủ</a>
        <a href="1.html">Giới thiệu</a>
        <a href="2.html">Tuyển dụng</a>
        <a href="3.html">Việc làm</a>
        <a href="4.html">Đăng ký</a>
      </nav>
<div class="item">HTML cơ bản</div>
<div class="item">CSS nâng cao</div>
<div class="item">JS</div>
<div class="item">React JS</div>

<div class="advert">Quảng cáo khóa học hấp dẫn!</div>

</body>
</html>

3
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="device-width, initial-scale=1.0">
  <title>Câu 3</title>
  <style>
    .job {
      border: 1px solid #ccc;
      padding: 10px;
      margin: 10px auto;
      width: 90%;
      max-width: 400px;
      background-color: #e8faff;
      border-left: 5px solid #00b253;
    }
    nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    nav a {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
    }
  </style>
</head>
<body>
    <nav>
        <a href="5.html">Trang chủ</a>
        <a href="1.html">Giới thiệu</a>
        <a href="2.html">Tuyển dụng</a>
        <a href="3.html">Việc làm</a>
        <a href="4.html">Đăng ký</a>
      </nav>
<h2 style="text-align:center;">Danh sách việc làm</h2>

<script>
  const jobs = [
    { vitri: "Kế toán", luong: "10 triệu" },
    { vitri: "Nhân sự", luong: "9 triệu" },
    { vitri: "Kỹ thuật viên", luong: "11 triệu" },
    { vitri: "Kinh doanh", luong: "12 triệu + hoa hồng" },
    { vitri: "Marketing", luong: "10-15 triệu" },
    { vitri: "Lập trình viên", luong: "15-20 triệu" }
  ];

  let i = 0;
  while (i < jobs.length) {
    document.write(
      `<div class="job">
        <strong>Vị trí:</strong> ${jobs[i].vitri}<br>
        <strong>Lương:</strong> ${jobs[i].luong}
      </div>`
    );
    i++;
  }
</script>

</body>
</html>

4
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="device-width, initial-scale=1.0">
  <title>Câu 4 - Đăng ký việc làm</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background: #f4f4f4;
    }
    form {
      background: white;
      max-width: 500px;
      margin: auto;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #999999;
    }
    input {
      width: 96%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #999999;
      border-radius: 5px;
    }
    button {
      padding: 10px 20px;
      background: #00b253;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    /* Responsive thiết bị */
    @media (max-width: 414px) {
      form { width: 90%; }
    }
    @media (min-width: 415px) and (max-width: 1024px) {
      form { width: 80%; }
    }
    @media (min-width: 1025px) {
      form { width: 50%; }
    }
    nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    nav a {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
    }
  </style>
</head>
<body>
    <nav>
        <a href="5.html">Trang chủ</a>
        <a href="1.html">Giới thiệu</a>
        <a href="2.html">Tuyển dụng</a>
        <a href="3.html">Việc làm</a>
        <a href="4.html">Đăng ký</a>
      </nav>
<form onsubmit="return validateForm()">
  <h2>Đăng ký việc làm</h2>
  <input type="text" id="name" placeholder="Họ và tên" required>
  <input type="email" id="email" placeholder="Địa chỉ email" required>
  <input type="tel" id="phone" placeholder="Số điện thoại" required>
  <input type="text" id="job" placeholder="Công việc mong muốn" required>
  <input type="number" id="salary" placeholder="Mức lương mong muốn" required>
  <button type="submit">Gửi đăng ký</button>
</form>

<script>
  function validateForm() {
    const phone = document.getElementById("phone").value;
    const salary = document.getElementById("salary").value;

    if (!/^\d{10}$/.test(phone)) {
      alert("Số điện thoại phải gồm đúng 10 chữ số!");
      return false;
    }

    if (salary <= 0) {
      alert("Mức lương phải lớn hơn 0");
      return false;
    }

    return true;
  }
</script>

</body>
</html>

5
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Câu 5 - Website hoàn chỉnh</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #ffffff; }
    header {
      background-color: #2f63ff;
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .logo {
      display: flex;
      align-items: center;
    }
    .logo svg {
      width: 40px;
      height: 40px;
      margin-right: 10px;
    }
    nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    nav a {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
    }
    .slogan {
      text-align: center;
      font-style: italic;
      margin-top: 10px;
      color: #000;
    }
    .advert {
      width: 100%;
      max-width: 600px;
      height: 200px;
      margin: 30px auto;
      border: 2px solid #2f63ff;
      background-color: #2fcbff;
      line-height: 200px;
      text-align: center;
      font-weight: bold;
      transition: 0.3s;
      border-radius: 10px;
      box-shadow: 0 2px 8px #999999;
    }
    .advert:hover {
      background-color: #00e56b;
      border-color: #00b253;
      font-style: italic;
    }
    .course-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      margin: 20px;
    }
    .item {
      width: 150px;
      height: 100px;
      background-color: #00b253;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      margin: 10px;
      box-shadow: 0 2px 5px #000;
    }
    form {
      background: white;
      max-width: 500px;
      margin: auto;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #999999;
    }
    input {
      width: 96%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #999999;
      border-radius: 5px;
    }
    button {
      padding: 10px 20px;
      background: #00b253;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #2f63ff;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

    <header>
        <div class="logo">
          <!-- SVG logo -->
          <svg viewBox="0 0 64 64" fill="#ffffff" xmlns="http://www.w3.org/2000/svg">
            <circle cx="32" cy="32" r="30" stroke="#ffe700" stroke-width="4" fill="#2fcbff"></circle>
            <text x="32" y="40" text-anchor="middle" font-size="20" fill="#ffffff" font-family="Arial">J</text>
          </svg>
          <h1>Job seek</h1>
        </div>
      </header>

<nav>
  <a href="5.html">Trang chủ</a>
  <a href="1.html">Giới thiệu</a>
  <a href="2.html">Tuyển dụng</a>
  <a href="3.html">Việc làm</a>
  <a href="4.html">Đăng ký</a>
</nav>

<p class="slogan">"Cơ hội nghề nghiệp rộng mở, chỉ cách bạn một cú click!"</p>

<div class="advert">🔔 Khóa học miễn phí cho sinh viên mới tốt nghiệp</div>

<div class="course-container" id="courses"></div>

<script>
  const courses = [
    { ten: "Khóa học HTML" },
    { ten: "Khóa học CSS" },
    { ten: "Khóa học JS cơ bản" },
    { ten: "Khóa học ReactJS" }
  ];

  const container = document.getElementById("courses");
  for (let i = 0; i < courses.length; i++) {
    const div = document.createElement("div");
    div.className = "item";
    div.textContent = courses[i].ten;
    container.appendChild(div);
  }
</script>

<form onsubmit="return validateForm()">
    <h2>Đăng ký việc làm</h2>
    <input type="text" id="name" placeholder="Họ và tên" required>
    <input type="email" id="email" placeholder="Địa chỉ email" required>
    <input type="tel" id="phone" placeholder="Số điện thoại" required>
    <input type="text" id="job" placeholder="Công việc mong muốn" required>
    <input type="number" id="salary" placeholder="Mức lương mong muốn" required>
    <button type="submit">Gửi đăng ký</button>
  </form>
  
  <script>
    function validateForm() {
      const phone = document.getElementById("phone").value;
      const salary = document.getElementById("salary").value;
  
      if (!/^\d{10}$/.test(phone)) {
        alert("Số điện thoại phải gồm đúng 10 chữ số!");
        return false;
      }
  
      if (salary <= 0) {
        alert("Mức lương phải lớn hơn 0");
        return false;
      }
  
      return true;
    }
  </script>

<footer>
  Họ tên: Phạm Văn Khánh Phong - Lớp: CNTT & Chuyển đổi số CLC K65 - MSSV: 11236556
</footer>

</body>
</html>


