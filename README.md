index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kenya Jobs - Join Today | M-Pesa Payment</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Arial, sans-serif; }
  body { background: #f4f7fb; color: #222; line-height: 1.6; }

  header {
    background: linear-gradient(135deg, #0066cc, #00b4d8);
    color: white; padding: 40px 20px; text-align: center;
  }
  header h1 { font-size: 2.2rem; margin-bottom: 10px; }
  header p { font-size: 1.1rem; opacity: 0.95; }

  .container { max-width: 1100px; margin: 30px auto; padding: 0 20px; }

  .section-title {
    text-align: center; color: #0066cc; font-size: 1.8rem;
    margin: 30px 0 20px; 
  }

  .jobs-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
  }

  .job-card {
    background: white; border-radius: 12px; padding: 22px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    border-top: 5px solid #0066cc;
    transition: transform 0.2s, box-shadow 0.2s;
    display: flex; flex-direction: column;
  }
  .job-card:hover { transform: translateY(-4px); box-shadow: 0 8px 25px rgba(0,0,0,0.15); }

  .job-icon { font-size: 2.2rem; margin-bottom: 8px; }
  .job-card h3 { color: #0066cc; font-size: 1.2rem; margin-bottom: 8px; }
  .job-card p { font-size: 0.95rem; color: #444; margin-bottom: 12px; flex-grow: 1; }

  .job-meta {
    display: flex; justify-content: space-between;
    font-size: 0.85rem; color: #666; margin: 8px 0;
    padding-top: 8px; border-top: 1px dashed #ddd;
  }

  .price-tag {
    background: #28a745; color: white; padding: 6px 12px;
    border-radius: 20px; font-weight: bold; font-size: 0.9rem;
    display: inline-block; margin-top: 10px;
  }
  .price-tag.medium { background: #ff9800; }
  .price-tag.high { background: #dc3545; }

  .pay-btn {
    display: block; text-align: center; background: #0066cc; color: white;
    padding: 10px; border-radius: 8px; text-decoration: none;
    font-weight: bold; margin-top: 12px; transition: 0.3s;
  }
  .pay-btn:hover { background: #004a99; }

  /* Payment section */
  .payment-section {
    background: linear-gradient(135deg, #fff8e1, #ffeec2);
    border: 2px dashed #ffb703;
    border-radius: 12px; padding: 30px; text-align: center;
    margin: 40px 0 20px;
  }
  .payment-section h2 { color: #d97706; margin-bottom: 12px; }
  .mpesa-number {
    font-size: 2.5rem; font-weight: bold; color: #0066cc;
    letter-spacing: 3px; margin: 12px 0;
    background: white; padding: 15px; border-radius: 10px;
    display: inline-block; box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }

  .steps {
    text-align: left; max-width: 500px; margin: 20px auto;
    background: white; padding: 20px; border-radius: 10px;
  }
  .steps h3 { color: #0066cc; margin-bottom: 10px; }
  .steps ol { padding-left: 22px; }
  .steps li { margin-bottom: 6px; }

  .btn-whatsapp {
    display: inline-block; background: #25D366; color: white;
    padding: 14px 28px; border-radius: 8px; text-decoration: none;
    font-weight: bold; font-size: 1.05rem; margin-top: 15px;
  }
  .btn-whatsapp:hover { background: #1da851; }

  .warning {
    background: #ffe5e5; border-left: 4px solid #dc3545;
    padding: 12px; border-radius: 6px; margin-top: 20px;
    font-size: 0.9rem; text-align: left; max-width: 600px; margin-left: auto; margin-right: auto;
  }

  footer { text-align: center; padding: 30px 20px; color: #666; font-size: 0.9rem; }

  @media (max-width: 600px) {
    header h1 { font-size: 1.6rem; }
    .mpesa-number { font-size: 1.8rem; letter-spacing: 2px; }
  }
</style>
</head>
<body>

<header>
  <h1>🇰🇪 Kenya Jobs Portal</h1>
  <p>All types of jobs available — Local workers wanted across Kenya</p>
</header>

<div class="container">

  <!-- Jobs Grid -->
  <h2 class="section-title">💼 Available Jobs</h2>

  <div class="jobs-grid">

    <!-- 1. Car Wash -->
    <div class="job-card">
      <div class="job-icon">🚗</div>
      <h3>Car Wash Attendant</h3>
      <p>Wash cars and earn per vehicle. No experience needed. Local workers only.</p>
      <div class="job-meta"><span>📍 Local Area</span><span>⏰ Flexible</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 2. House Help -->
    <div class="job-card">
      <div class="job-icon">🏠</div>
      <h3>House Help / Cleaner</h3>
      <p>House cleaning, laundry, and general home help. Daily or live-in.</p>
      <div class="job-meta"><span>📍 Nairobi & Environs</span><span>⏰ Daily</span></div>
      <span class="price-tag">Join Fee: KSh 100</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 3. Security Guard -->
    <div class="job-card">
      <div class="job-icon">🛡️</div>
      <h3>Security Guard</h3>
      <p>Night & day guard positions. Must be reliable and alert.</p>
      <div class="job-meta"><span>📍 Various</span><span>⏰ Shifts</span></div>
      <span class="price-tag medium">Join Fee: KSh 100</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 4. Delivery Rider -->
    <div class="job-card">
      <div class="job-icon">🛵</div>
      <h3>Delivery Rider</h3>
      <p>Deliver packages using motorbike or bicycle. Own bike preferred.</p>
      <div class="job-meta"><span>📍 Town</span><span>⏰ Full-time</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 5. Waiter / Waitress -->
    <div class="job-card">
      <div class="job-icon">🍽️</div>
      <h3>Waiter / Waitress</h3>
      <p>Serve customers in restaurants and hotels. Good communication needed.</p>
      <div class="job-meta"><span>📍 City Hotels</span><span>⏰ Shifts</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 6. Shop Assistant -->
    <div class="job-card">
      <div class="job-icon">🏪</div>
      <h3>Shop Assistant</h3>
      <p>Attend to customers, arrange stock, and handle simple sales.</p>
      <div class="job-meta"><span>📍 Local Shops</span><span>⏰ Daily</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 7. Garden Boy / Landscaper -->
    <div class="job-card">
      <div class="job-icon">🌿</div>
      <h3>Gardener / Landscaper</h3>
      <p>Maintain gardens, trim hedges, and plant flowers. Tools provided.</p>
      <div class="job-meta"><span>📍 Residential</span><span>⏰ Weekly</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 8. Cook -->
    <div class="job-card">
      <div class="job-icon">👨‍🍳</div>
      <h3>Cook / Chef</h3>
      <p>Prepare meals for families or small hotels. Experience a plus.</p>
      <div class="job-meta"><span>📍 Homes & Hotels</span><span>⏰ Daily</span></div>
      <span class="price-tag medium">Join Fee: KSh 100</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 9. Driver -->
    <div class="job-card">
      <div class="job-icon">🚕</div>
      <h3>Driver (Taxi / Personal)</h3>
      <p>Valid driving license required. Drive for hire or personal errands.</p>
      <div class="job-meta"><span>📍 Town</span><span>⏰ Full-time</span></div>
      <span class="price-tag medium">Join Fee: KSh 100</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 10. Salon / Barber -->
    <div class="job-card">
      <div class="job-icon">💇</div>
      <h3>Salon / Barber Assistant</h3>
      <p>Assist in hairdressing, braiding, and barbering. Training provided.</p>
      <div class="job-meta"><span>📍 Local Salons</span><span>⏰ Daily</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 11. Sales Person -->
    <div class="job-card">
      <div class="job-icon">📞</div>
      <h3>Sales Person</h3>
      <p>Sell products and promote brands. Commission-based earning.</p>
      <div class="job-meta"><span>📍 Town</span><span>⏰ Flexible</span></div>
      <span class="price-tag high">Join Fee: KSh 100</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 12. Mjengo / Construction -->
    <div class="job-card">
      <div class="job-icon">🔨</div>
      <h3>Construction (Mjengo)</h3>
      <p>General labour on construction sites. Physical work, daily pay.</p>
      <div class="job-meta"><span>📍 Site</span><span>⏰ Daily</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 13. Farm Worker -->
    <div class="job-card">
      <div class="job-icon">🌾</div>
      <h3>Farm Worker</h3>
      <p>Planting, weeding, harvesting and livestock care.</p>
      <div class="job-meta"><span>📍 Rural</span><span>⏰ Seasonal</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 14. Receptionist -->
    <div class="job-card">
      <div class="job-icon">💻</div>
      <h3>Receptionist / Office Assistant</h3>
      <p>Answer calls, greet clients, and basic office duties.</p>
      <div class="job-meta"><span>📍 Offices</span><span>⏰ Full-time</span></div>
      <span class="price-tag high">Join Fee: KSh 100</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 15. Boda Boda -->
    <div class="job-card">
      <div class="job-icon">🏍️</div>
      <h3>Boda Boda Rider</h3>
      <p>Carry passengers and goods. Valid license required.</p>
      <div class="job-meta"><span>📍 Town</span><span>⏰ Daily</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

    <!-- 16. House Watchman -->
    <div class="job-card">
      <div class="job-icon">🔑</div>
      <h3>Watchman (Night)</h3>
      <p>Guard residential homes or shops at night. Reliable only.</p>
      <div class="job-meta"><span>📍 Residential</span><span>⏰ Night</span></div>
      <span class="price-tag">Join Fee: KSh 50</span>
      <a href="#payment" class="pay-btn">Apply Now</a>
    </div>

  </div>

  <!-- Payment Section -->
  <div class="payment-section" id="payment">
    <h2>📲 How to Apply — Pay Joining Fee</h2>
    <p>To apply for any job, pay the joining fee (KSh 50 or 100) via M-Pesa:</p>

    <div class="mpesa-number">0702 844 866</div>
    <p><strong>Account Name:</strong> Kenya Jobs Portal</p>

    <div class="steps">
      <h3>Payment Steps (M-Pesa):</h3>
      <ol>
        <li>Open M-Pesa menu on your phone</li>
        <li>Select <strong>Send Money</strong> or <strong>Lipa na M-Pesa</strong></li>
        <li>Enter number: <strong>0702844866</strong></li>
        <li>Amount: <strong>KSh 50</strong> or <strong>KSh 100</strong> (depends on job)</li>
        <li>Enter your M-Pesa PIN and confirm</li>
        <li>Send the confirmation SMS + job title on WhatsApp</li>
      </ol>
    </div>

    <a href="https://wa.me/254702844866?text=Hi%2C%20I%20have%20paid%20the%20joining%20fee.%20My%20M-Pesa%20code%3A%20%0AJob%20applied%20for%3A%20" 
       class="btn-whatsapp" target="_blank">
      📩 Send Payment Confirmation on WhatsApp
    </a>

    <div class="warning">
      ⚠️ <strong>Security Notice:</strong> Only send money to <strong>0702844866</strong>. Do not pay anyone else claiming to represent Kenya Jobs Portal. Keep your M-Pesa confirmation SMS as proof.
    </div>
  </div>

</div>

<footer>
  © 2025 Kenya Jobs Portal | M-Pesa: 0702844866 <br>
  Empowering local workers across Kenya 🇰🇪
</footer>

</body>
</html>