---
layout: home
title: "Sustainable Funding for Academic Open Science"
---

<div class="hero-section">
  <div class="hero-content">
    <h1 class="hero-title">The OpenScience Collective</h1>
    <p class="hero-subtitle">Academic research depends on open-source tools, yet the sustainability of this critical infrastructure remains precarious.</p>
    <div class="hero-stats">
      <div class="stat-item">
        <span class="stat-number">Millions</span>
        <span class="stat-label">of researchers depend on open-source tools</span>
      </div>
      <div class="stat-item">
        <span class="stat-number">~0.1%</span>
        <span class="stat-label">of grant funding could solve the crisis</span>
      </div>
      <div class="stat-item">
        <span class="stat-number">1-2</span>
        <span class="stat-label">key maintainer losses could collapse entire ecosystems</span>
      </div>
    </div>
    <div class="hero-cta">
      <a href="/solution" class="btn btn-primary">Learn Our Solution</a>
      <a href="/get-involved" class="btn btn-secondary">Get Involved</a>
    </div>
  </div>
</div>

## The Crisis

**Research software is breaking.** Critical tools that millions of researchers depend on operate without sustainable funding. The loss of just 1-2 key maintainers could collapse entire research ecosystems.

<div class="problem-grid">
  <div class="problem-item">
    <h3>🔧 Maintenance Crisis</h3>
    <p>Essential research tools rely on volunteer labor and short-term grants</p>
  </div>
  <div class="problem-item">
    <h3>💸 Funding Mismatch</h3>
    <p>Grants fund new features but not the boring (yet critical) maintenance work</p>
  </div>
  <div class="problem-item">
    <h3>🚨 System Failure</h3>
    <p>When maintainers burn out, entire research workflows can break overnight</p>
  </div>
</div>

## Our Solution

**Just 0.1% of grant funding** can solve this crisis through systematic, sustainable funding:

### 💰 **Small Contribution, Big Impact**
Research grants contribute ~0.1% of direct costs to a shared sustainability fund

### 📊 **Smart Distribution**
Transparent metrics ensure funding reaches the tools researchers actually use

### 🔧 **Maintenance First**
Stable funding for the unglamorous but essential work of keeping software running

---

<div class="mission-statement">
  <blockquote>
    <p><strong>Our mission:</strong> Create sustainable funding for the research software that powers modern science.</p>
  </blockquote>
</div>

## Why This Matters

**Science builds on previous work.** When research software fails, it breaks the chain of knowledge that enables scientific progress. We're creating a systematic solution that ensures the digital tools of science remain reliable for future generations.

<div class="cta-section">
  <h3>Join the Movement</h3>
  <p>Whether you're a researcher, university administrator, or funding agency—help us fix research software sustainability.</p>
  <div class="cta-buttons">
    <a href="/get-involved" class="btn btn-primary">Get Involved</a>
    <a href="/solution" class="btn btn-outline">Learn More</a>
    <a href="https://github.com/OpenScience-Collective/osc" class="btn btn-outline">Read Full Concept</a>
  </div>
</div>

<style>
.hero-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 4rem 2rem;
  margin: 0 0 3rem 0;
  border-radius: 12px;
  text-align: center;
}

.hero-title {
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 1rem;
  line-height: 1.2;
}

.hero-subtitle {
  font-size: 1.25rem;
  margin-bottom: 2rem;
  opacity: 0.9;
  max-width: 600px;
  margin-left: auto;
  margin-right: auto;
}

.hero-stats {
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.stat-item {
  text-align: center;
}

.stat-number {
  display: block;
  font-size: 2rem;
  font-weight: 700;
  color: #ffd700;
}

.stat-label {
  display: block;
  font-size: 0.9rem;
  opacity: 0.8;
}

.hero-cta {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  padding: 12px 24px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
  display: inline-block;
}

.btn-primary {
  background-color: #ffd700;
  color: #333;
}

.btn-primary:hover {
  background-color: #ffed4e;
  transform: translateY(-2px);
}

.btn-secondary {
  background-color: rgba(255,255,255,0.2);
  color: white;
  border: 2px solid rgba(255,255,255,0.3);
}

.btn-secondary:hover {
  background-color: rgba(255,255,255,0.3);
  transform: translateY(-2px);
}

.btn-outline {
  background-color: transparent;
  color: #667eea;
  border: 2px solid #667eea;
}

.btn-outline:hover {
  background-color: #667eea;
  color: white;
  transform: translateY(-2px);
}

.problem-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.problem-item {
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 8px;
  border-left: 4px solid #667eea;
}

.problem-item h3 {
  margin-top: 0;
  color: #333;
}

.mission-statement {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  margin: 3rem 0;
  text-align: center;
}

.mission-statement blockquote {
  margin: 0;
  font-style: italic;
  font-size: 1.1rem;
}

.cta-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 3rem 2rem;
  border-radius: 12px;
  text-align: center;
  margin: 3rem 0;
}

.cta-section h3 {
  margin-top: 0;
  font-size: 2rem;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 1.5rem;
}

@media (max-width: 768px) {
  .hero-title {
    font-size: 2rem;
  }
  
  .hero-stats {
    gap: 1rem;
  }
  
  .problem-grid {
    grid-template-columns: 1fr;
  }
  
  .hero-cta, .cta-buttons {
    flex-direction: column;
    align-items: center;
  }
}
</style>