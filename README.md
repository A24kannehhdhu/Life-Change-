<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ফ্রিল্যান্স ওয়েবসাইট</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background-color: #333; color: white; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .hero { background: #4caf50; color: white; padding: 100px 20px; text-align: center; }
    .section { padding: 50px 20px; }
    .services, .portfolio { display: flex; justify-content: space-around; flex-wrap: wrap; }
    .box { background: #f4f4f4; padding: 20px; margin: 10px; width: 250px; border-radius: 10px; }
    form { display: flex; flex-direction: column; width: 300px; margin: auto; }
    input, textarea { margin: 10px 0; padding: 10px; }
    footer { background: #222; color: white; text-align: center; padding: 20px; }
  </style>
</head>
<body>

  <header>
    <h1>ফ্রিল্যান্স সার্ভিস</h1>
    <nav>
      <a href="#services">সার্ভিস</a>
      <a href="#portfolio">পোর্টফোলিও</a>
      <a href="#contact">যোগাযোগ</a>
    </nav>
  </header>

  <div class="hero">
    <h2>আমি একজন পেশাদার ওয়েব ডেভেলপার</h2>
    <p>আমার সাথে যোগাযোগ করুন এবং আপনার ওয়েবসাইট বানিয়ে নিন!</p>
    <button onclick="document.getElementById('contact').scrollIntoView()">যোগাযোগ করুন</button>
  </div>

  <div class="section" id="services">
    <h2>আমার সার্ভিসসমূহ</h2>
    <div class="services">
      <div class="box">
        <h3>HTML ওয়েবসাইট</h3>
        <p>স্ট্যাটিক ওয়েবসাইট ডিজাইন ও ডেভেলপমেন্ট</p>
      </div>
      <div class="box">
        <h3>রেসপনসিভ ডিজাইন</h3>
        <p>সকল ডিভাইসে সুন্দরভাবে দেখানোর জন্য ওয়েবসাইট ডিজাইন</p>
      </div>
      <div class="box">
        <h3>SEO অপটিমাইজড</h3>
        <p>গুগল সার্চে র‍্যাংকিং উন্নত করার জন্য ওয়েবসাইট অপটিমাইজেশন</p>
      </div>
    </div>
  </div>

  <div class="section" id="portfolio">
    <
