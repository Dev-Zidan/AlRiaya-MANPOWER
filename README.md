<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap" rel="stylesheet">

  <title>شركة الرعاية للعمالة</title>
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background-color: #ffffff;
      color: #000000;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #1c2541;
      padding: 20px;
      font-size: 1.8em;
      font-weight: bold;
      color: #ffffff;
    }
    section {
      padding: 40px 20px;
    }
    .intro {
      max-width: 600px;
      margin: 0 auto 30px;
      font-weight: normal;
      line-height: 1.8;
      font-size: 1.2em;
    }
    .paypal-box {
      background-color: #ffffff;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.4);
      padding: 25px;
      max-width: 400px;
      margin: 0 auto;
    }
    footer {
      background-color: #1c2541;
      padding: 15px;
      font-size: 0.9em;
      color: rgb(255, 255, 255);
        margin-top: 40px;
    }
  </style>
  <script 
    src="https://www.paypal.com/sdk/js?client-id=BAAB3CYBr-qgeFMQrXxtLrhGhF3ns-8O0HP7XpOrQpxrXovYi0nLK4xnvwPBE49J0vbOk-92jXOYvkPTII&components=hosted-buttons&disable-funding=venmo&currency=USD">
  </script>
</head>
<body>
  <header>شركة الرعاية للعمالة</header>

  <section>
    <div class="intro">
      <p>نحن شركة متخصصة في خدمات الاستقدام وتوفير العمالة المنزلية وفق أعلى معايير الجودة والالتزام، 
      نسعى لتقديم حلول موثوقة وسريعة لعملائنا في المملكة العربية السعودية.</p>
    </div>

    <div class="paypal-box">
      <h3 style="color: #000000;">إتمام الدفع الآمن عبر PayPal</h3>
      <div id="paypal-container-CVXYWJ3UQGQXE"></div>
      <script>
        paypal.HostedButtons({
          hostedButtonId: "CVXYWJ3UQGQXE",
        }).render("#paypal-container-CVXYWJ3UQGQXE")
      </script>
    </div>
  </section>

  <footer>© 2025 شركة الرعاية للعمالة - جميع الحقوق محفوظة</footer>
</body>
</html>
