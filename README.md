<!DOCTYPE html>
<html lang = "en">
<head>
    <meta charset = "UTF-8">
    <meta name = "viewport" content = "width=device-width, initial-scale=1.0">
    <title>Job seek</title>
    <style>
        body {
            font-family: Arial, Sans-Serif;
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
        .nav {
            background: #ffe700;
            display: flex;
            justify-content: center;
            padding: 10px;
            gap: 15px
        }
        .nav div {
            color: #2f63ff;
            font-weight: bold;
            text-decoration: none;
            cursor: pointer;
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
    <div class="nav">
        <div onclick="location.href='cau5.html'">Trang chủ</div>
        <div onclick="location.href='cau1.html'">Giới thiệu</div>
        <div onclick="location.href='cau2.html'">Tuyển dụng</div>
        <div onclick="location.href='cau3.html'">Việc làm</div>
        <div onclick="location.href='cau4.html'">Đăng ký</div>
      </div>
    <header>
        <div class = "logo">
            <svg viewBox = "0 0 0 64" fill = "#ffffff">
                <circle cx = "32" cy = "32" r = "30" stroke = "ffe700" stroke-width = "4" fill = "#2fcbff"></circle>
                <text x = "32" y = "40" text-anchor = "middle" font-size = "20" fill = "#ffffff" font-family = "Arial">J</text>
            </svg>
        </div>
    </header>
    <section class = "article">
        <h2>Tuyen dung nhan vien</h2>
        <img src = "https://via.placeholder.com/400x200" alt = "Marketing Image">
        <p><strong>Vi tri:</strong>Nhan vien Marketing</p>
        <p><strong>Muc luong:</strong>10-15 trieu dong</p>
        <p><strong>Mo ta:</strong> Làm việc tại văn phòng Hà Nội, yêu cầu có kinh nghiệm từ 1 năm trở lên, có khả năng giao tiếp và sáng tạo nội dung tốt.</p>
    </section>
</body>
</html>

2
<!DOCTYPE html>
<html lang = "en">
<head>
    <meta charset = "UTF-8">
    <meta name = "viewport" content = "width=device-width,initial-scale=1.0">
    <title>Tuyen dung</title>
    <style>
        body {
            font-family: Arial, Sans-Serif;
            margin: 0;
            padding: 20px;
            background: #ffffff;
            text-align: center;
        }
        .nav {
            background: #ffe700;
            display: flex;
            justify-content: center;
            padding: 10px;
            gap: 15px;
        }
        .nav div {
            color: #2f63ff;
            font-weight: bold;
            text-decoration: none;
            cursor: pointer;
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
    </style>
</head>
<body>
    <div class="nav">
        <div onclick="location.href='cau5.html'">Trang chủ</div>
        <div onclick="location.href='cau1.html'">Giới thiệu</div>
        <div onclick="location.href='cau2.html'">Tuyển dụng</div>
        <div onclick="location.href='cau3.html'">Việc làm</div>
        <div onclick="location.href='cau4.html'">Đăng ký</div>
      </div>
    <div class = "item"> HTML co ban</div>
    <div class = "item">CSS nâng cao</div>
    <div class = "item">JS</div>
    <div class = "item">React JS</div>
    <div class = "advert">Quang cao hap dan!</div>    
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
    .nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    .nav div {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
    <div class="nav">
        <div onclick="location.href='cau5.html'">Trang chủ</div>
        <div onclick="location.href='cau1.html'">Giới thiệu</div>
        <div onclick="location.href='cau2.html'">Tuyển dụng</div>
        <div onclick="location.href='cau3.html'">Việc làm</div>
        <div onclick="location.href='cau4.html'">Đăng ký</div>
      </div>
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
    .nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    .nav div {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
    <div class="nav">
        <div onclick="location.href='cau5.html'">Trang chủ</div>
        <div onclick="location.href='cau1.html'">Giới thiệu</div>
        <div onclick="location.href='cau2.html'">Tuyển dụng</div>
        <div onclick="location.href='cau3.html'">Việc làm</div>
        <div onclick="location.href='cau4.html'">Đăng ký</div>
    </div>
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
    .nav {
      background: #ffe700;
      display: flex;
      justify-content: center;
      padding: 10px;
      gap: 15px;
    }
    .nav div {
      color: #2f63ff;
      font-weight: bold;
      text-decoration: none;
      cursor: pointer;
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

      <div class="nav">
        <div onclick="location.href='cau5.html'">Trang chủ</div>
        <div onclick="location.href='cau1.html'">Giới thiệu</div>
        <div onclick="location.href='cau2.html'">Tuyển dụng</div>
        <div onclick="location.href='cau3.html'">Việc làm</div>
        <div onclick="location.href='cau4.html'">Đăng ký</div>
      </div>
<p class="slogan">"Cơ hội nghề nghiệp rộng mở, chỉ cách bạn một cú click!"</p>

<div class="advert"> Khóa học miễn phí cho sinh viên mới tốt nghiệp</div>

<div class="course-container" id="courses"></div>

<script>
  const courses = [
    { ten: "Khóa học HTML" },
    { ten: "Khóa học CSS" },
    { ten: "Khóa học cơ bản" },
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

/*for*/
<style>
    .car {
      border: 1px solid #ccc;
      padding: 10px;
      margin: 15px auto;
      max-width: 400px;
      background-color: #eafff1;
      border-left: 5px solid #00b253;
    }
  </style>
</head>
<body>

<h2 style="text-align:center;">Danh sách xe cho thuê</h2>

<script>
  const cars = [
    { loai: "Xe 4 chỗ", soCho: 4, gia: "800.000đ/ngày"},
    { loai: "Xe 7 chỗ", soCho: 7, gia: "1.200.000đ/ngày"},
    { loai: "Xe 16 chỗ", soCho: 16, gia: "1.800.000đ/ngày"},
    { loai: "Xe Limousine", soCho: 9, gia: "2.500.000đ/ngày"},
    { loai: "Xe máy", soCho: 2, gia: "150.000đ/ngày"},
    { loai: "Xe tải", soCho: 3, gia: "1.000.000đ/ngày"}
  ];
  for (let i = 0; i < cars.length; i++) {
    document.write(`
      <div class="car">
        <strong>Loại xe:</strong> ${cars[i].loai}<br>
        <strong>Số chỗ:</strong> ${cars[i].soCho}<br>
        <strong>Giá thuê:</strong> ${cars[i].gia}
      </div>
    `);
  }
</script>

/*table8/
 table {
      border-collapse: collapse;
      width: 100%;
      margin-top: 10px;
    }

    table, th, td {
      border: 1px solid #434242;
    }

    th, td {
      padding: 8px;
      text-align: left;
    }
  </style>
</head>
<body>
  <header>
    <h1> Car Rental</h1>
    <nav>
      <ul>
        <li><a href="#">Trang chủ</a></li>
        <li><a href="#">Dịch vụ</a></li>
        <li><a href="#">Bảng giá</a></li>
        <li><a href="#">Liên hệ</a></li>
      </ul>
    </nav>
  </header>
  <section class="article">
    <h1> Xe Toyota Vios cho thuê</h1>
    <img src="https://via.placeholder.com/400x200" alt="Hình ảnh xe Toyota Vios">
    <p><strong>Loại xe:</strong> Sedan</p>
    <p><strong>Giá thuê:</strong> 800.000 VNĐ/ngày</p>

    <table>
      <tr>
        <th>Thông tin</th>
        <th>Chi tiết</th>
      </tr>
      <tr>
        <td>Số chỗ ngồi</td>
        <td>5</td>
      </tr>
      <tr>
        <td>Nhiên liệu</td>
        <td>Xăng</td>
      </tr>
      <tr>
        <td>Hộp số</td>
        <td>Tự động</td>
      </tr>
      <tr>
        <td>Điều hòa</td>
        <td>Có</td>
      </tr>
    </table>
  </section>


