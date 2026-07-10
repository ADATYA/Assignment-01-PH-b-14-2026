# The HTML file for AI Missing section and using this code for html.
<!-- AI Based missing section building section started  -->
  <!-- <section class="hackathon-section">
  <div class="hackathon-container">
     -->
    <!-- Section header -->
    <div class="hackathon-header">
      <span class="badge">DevConf 2026 Special</span>
      <h2>The Ultimate Hackathon Arena</h2>
      <p>Build the future in 48 hours. Compete with top minds, collaborate on cutting-edge tech, and win from our massive prize pool.</p>
      
      <!-- Prizepool hightlight box section -->
      <div class="prize-pool-box">
        <span class="prize-title">TOTAL PRIZE POOL</span>
        <h3 class="prize-amount">$10,000+</h3>
      </div>
    </div>

    <!-- Hackerthon Track  grid section -->
    <div class="hackathon-grid">
      
      <!--Track 1 -->
      <div class="track-card">
        <div class="track-icon">🤖</div>
        <h3>AI & Next-Gen Web App</h3>
        <p>Integrate Large Language Models (LLMs) into real-world SaaS applications. Build autonomous agents or next-gen dev tools.</p>
        <span class="track-prize">Prize: $5,000</span>
      </div>

      <!-- Track 2 -->
      <div class="track-card central-track">
        <div class="track-icon">🌐</div>
        <h3>Open Source & Core Dev</h3>
        <p>Contribute to critical web infrastructure or build tooling that optimizes developer workflows globally.</p>
        <span class="track-prize">Prize: $3,000</span>
      </div>

      <!-- Track 3 -->
      <div class="track-card">
        <div class="track-icon">🌱</div>
        <h3>Green Tech & Sustainability</h3>
        <p>Leverage software architecture and smart algorithms to measure, optimize, and reduce digital carbon footprints.</p>
        <span class="track-prize">Prize: $2,000</span>
      </div>

    </div>
<!-- call to action btn -->
  
    <div class="hackathon-action">
      <a href="#" class="btn-hackathon">Register for Hackathon</a>
    </div>

  <!-- </div>
</section> -->


# My CSS style and usign this code in AI generated missing section:

/* AI Missing link section started for css part */

/* hackerthoc section main section */
.hackathon-section {
  padding: 100px 20px;
  background-color: #f8fafc; 
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.hackathon-container {
  max-width: 1200px;
  margin: 0 auto; /* container section */
}

/* header desigh */
.hackathon-header {
  text-align: center;
  max-width: 700px;
  margin: 0 auto 60px auto;
}

.hackathon-header .badge {
  background-color: #e0e7ff;
  color: #e60fa2;
  padding: 6px 16px;
  font-size: 0.85rem;
  font-weight: 700;
  border-radius: 50px;
  letter-spacing: 0.5px;
  display: inline-block;
  margin-bottom: 15px;
}

.hackathon-header h2 {
  font-size: 2.8rem;
  font-weight: 800;
  color: #0f172a;
  margin-bottom: 15px;
  letter-spacing: -0.5px;
}

.hackathon-header p {
  color: #475569;
  font-size: 1.1rem;
  line-height: 1.6;
  margin-bottom: 30px;
}

/* Prize pool highligh */
.prize-pool-box {
  background: linear-gradient(135deg, #4f46e5, #ef0d91);
  color: white;
  display: inline-block;
  padding: 20px 40px;
  border-radius: 16px;
  box-shadow: 0 10px 25px -5px rgba(79, 70, 229, 0.4);
}

.prize-title {
  font-size: 0.8rem;
  font-weight: bold;
  letter-spacing: 1.5px;
  opacity: 0.9;
  display: block;
}

.prize-amount {
  font-size: 2.5rem;
  font-weight: 900;
  margin-top: 5px;
}

/* Teack gred leayout column 3 */
.hackathon-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
  margin-bottom: 50px;
}

/* simple card desigh section */
.track-card {
  background: #ffffff;
  border: 1px solid #e2e8f0;
  border-radius: 20px;
  padding: 40px 30px;
  text-align: center;
  transition: all 0.3s ease;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
}

/* pop up and highlight section */
.track-card.central-track {
  border: 2px solid #4f46e5;
  transform: scale(1.03);
}

.track-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
}

.track-icon {
  font-size: 3rem;
  margin-bottom: 20px;
}

.track-card h3 {
  font-size: 1.4rem;
  font-weight: 700;
  color: #1e293b;
  margin-bottom: 12px;
}

.track-card p {
  color: #64748b;
  font-size: 0.95rem;
  line-height: 1.6;
  margin-bottom: 25px;
}

.track-prize {
  display: inline-block;
  font-weight: 700;
  color: #d10591; /* prize tag */
  background-color: #ecfdf5;
  padding: 6px 14px;
  border-radius: 8px;
  font-size: 0.9rem;
}

/* action btn*/
.hackathon-action {
  text-align: center;
}

.btn-hackathon {
  display: inline-block;
  background-color: #ed1e7f; 
  color: white;
  padding: 16px 40px;
  font-size: 1.1rem;
  font-weight: bold;
  text-decoration: none;
  border-radius: 12px;
  transition: background 0.3s ease;
}

.btn-hackathon:hover {
  background-color: #1e293b;
}
