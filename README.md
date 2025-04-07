# lijon-topup
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>Lijon Top Up</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h2>Lijon Top Up</h2>
    <form id="topup-form">
      <label for="uid">Free Fire UID:</label>
      <input type="text" id="uid" name="uid" required>
      <label for="diamonds">ডায়মন্ড প্যাকেজ:</label>
      <select id="diamonds" name="diamonds" required>
        <option value="">একটা নির্বাচন করুন</option>
        <option value="100">100 Diamond</option>
        <option value="310">310 Diamond</option>
        <option value="520">520 Diamond</option>
        <option value="1060">1060 Diamond</option>
        <option value="2180">2180 Diamond</option>
      </select>
      <label for="payment">পেমেন্ট মেথড:</label>
      <select id="payment" name="payment" required>
        <option value="">একটা নির্বাচন করুন</option>
        <option value="bKash">bKash</option>
        <option value="Nagad">Nagad</option>
        <option value="Rocket">Rocket</option>
        <option value="Upay">Upay</option>
      </select>

 <label for="trxid">লেনদেন নম্বর (TrxID):</label>
      <input type="text" id="trxid" name="trxid" required>

  <button type="submit">Submit</button>
    </form>
    <p class="success" id="success-msg">সফলভাবে সাবমিট হয়েছে!</p>
  </div>

  <script src="script.js"></script>
</body>
</html>
