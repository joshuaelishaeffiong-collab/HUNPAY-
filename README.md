<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HUNPAY Dashboard</title>

<style>
*{box-sizing:border-box}
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:#f4f7fb;
  color:#172033;
}
header{
  background:#111827;
  color:white;
  padding:20px;
}
header h1{margin:0;font-size:26px}
header p{margin:6px 0 0;color:#cbd5e1}

.container{
  max-width:700px;
  margin:auto;
  padding:20px;
}

.card{
  background:white;
  border-radius:16px;
  padding:20px;
  margin-bottom:16px;
  box-shadow:0 4px 15px rgba(0,0,0,.07);
}

.balance{
  background:#2563eb;
  color:white;
}
.balance h2{margin:0 0 8px}
.amount{
  font-size:34px;
  font-weight:bold;
}

.stats{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:14px;
}

.stat h3{
  margin:0;
  font-size:25px;
}
.stat p{
  margin:5px 0 0;
  color:#64748b;
}

button{
  width:100%;
  border:0;
  padding:14px;
  border-radius:10px;
  background:#2563eb;
  color:white;
  font-size:16px;
  font-weight:bold;
  margin-top:10px;
}

button.secondary{
  background:#e2e8f0;
  color:#172033;
}

.note{
  font-size:13px;
  color:#64748b;
  line-height:1.5;
}

footer{
  text-align:center;
  padding:20px;
  color:#64748b;
  font-size:13px;
}
</style>
</head>

<body>

<header>
  <h1>HUNPAY</h1>
  <p>Welcome to your dashboard</p>
</header>

<div class="container">

  <div class="card balance">
    <h2>Available Balance</h2>
    <div class="amount">₦0.00</div>
    <p>Demo balance</p>
  </div>

  <div class="stats">

    <div class="card stat">
      <h3>₦0.00</h3>
      <p>Total Earnings</p>
    </div>

    <div class="card stat">
      <h3>0</h3>
      <p>Referrals</p>
    </div>

    <div class="card stat">
      <h3>₦
