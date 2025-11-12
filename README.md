<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hồ sơ điện tử - Khánh</title>

  <!-- Font chữ -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0b0b0c;
      --card:#141416;
      --accent:#1ea7ff;
      --accent-strong:#0097ff;
      --text:#d6d6d6;
      --muted:#9aa3ad;
    }

    *{box-sizing:border-box}
    body{
      background:linear-gradient(180deg,#060607 0%, #0b0b0b 100%);
      font-family:'Poppins',sans-serif;
      color:var(--text);
      margin:0;
      padding:40px 0;
      display:flex;
      justify-content:center;
    }

    .card{
      display:flex;
      align-items:center;
      gap:30px;
      background:#141416;
      border-radius:20px;
      padding:40px;
      max-width:900px;
      box-shadow:0 0 25px rgba(0,140,255,0.1);
      transition:all 0.3s ease;
    }

    .card:hover{
      box-shadow:0 0 40px rgba(0,140,255,0.8);
      transform:translateY(-5px);
    }

    .card .info{
      flex:1;
    }

    .card h1{
      font-size:42px;
      color:var(--accent-strong);
      margin:0 0 10px;
    }

    .card h3{
      color:var(--accent);
      margin:0 0 20px;
    }

    .card p{
      color:var(--muted);
      line-height:1.7;
      margin-bottom:20px;
    }

    .card button{
      background:transparent;
      color:var(--accent);
      border:2px solid var(--accent);
      border-radius:10px;
      padding:10px 20px;
      font-weight:bold;
      cursor:pointer;
      transition:0.3s;
    }

    .card button:hover{
      background:var(--accent);
      color:black;
    }

    .avatar{
      width:220px;
      height:220px;
      border-radius:50%;
      border:4px solid #fff;
      box-shadow:0 0 30px rgba(30,167,255,0.5);
      background:url('avatar.jpg') center/cover no-repeat;
      transition:0.3s;
    }

    .card:hover .avatar{
      box-shadow:0 0 50px rgba(0,140,255,1);
      transform:scale(1.05);
    }

    .quote{
      margin-top:30px;
      max-width:800px;
      background-color:#1a1a1a;
      padding:20px;
      border-radius:10px;
      font-style:italic;
      color:#ccc;
      box-shadow:0 0 20px rgba(0,140,255,0.1);
      text-align:center;
    }

    .quote:hover{
      box-shadow:0 0 25px rgba(0,150,255,0.5);
    }

    @media (max-width:768px){
      .card{flex-direction:column;text-align:center}
    }
  </style>
</head>

<body>
  <div>
    <div class="card">
      <div class="info">
        <h1>Xin chào, tôi là Khánh</h1>
        <h3>Sinh viên năm hai - Ngành công nghệ thông tin</h3>
        <p>
          Tôi là sinh viên IT với ước mơ trở thành lập trình viên chuyên nghiệp.
          Đam mê lập trình và phát triển web, tôi luôn nỗ lực trau dồi kỹ năng mỗi ngày.
          Tôi tin rằng công nghệ không chỉ thay đổi cuộc sống mà còn mở ra cơ hội sáng tạo vô hạn!
        </p>
        <button>Giới thiệu về tôi</button>
      </div>

      <div class="avatar"></div>
    </div>

    <div class="quote">
      "Bạn ơi, trước khi bạn khám phá những thông tin thú vị khác về tôi, tôi xin gửi đến bạn lời cảm ơn chân thành nhất vì đã chọn xem hồ sơ của tôi 💙"
    </div>
  </div>
</body>
</html>
