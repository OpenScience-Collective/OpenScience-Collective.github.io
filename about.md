---
layout: page
title: "The Problem"
permalink: /about/
---

# Research Software is Failing

**The digital infrastructure that powers modern science is dangerously fragile.** Critical research tools operate without sustainable funding, relying on volunteers and short-term grants. This isn't just inconvenient—it's a systemic threat to scientific progress.

## The Scale of the Crisis

<div class="crisis-stats">
  <div class="stat-item">
    <h3>🔬 Dependency Crisis</h3>
    <p>Essential tools across every research domain—from EEGLAB in neuroscience to NumPy in data science—operate without guaranteed funding.</p>
  </div>
  
  <div class="stat-item">
    <h3>⚠️ Critical Fragility</h3>
    <p>The loss of just 1-2 key maintainers could collapse entire research ecosystems that millions depend on.</p>
  </div>
  
  <div class="stat-item">
    <h3>💔 Maintainer Burnout</h3>
    <p>Volunteer maintainers burn out from unglamorous but essential work that receives no institutional recognition.</p>
  </div>
</div>

## Why Traditional Funding Fails

### 🎯 **The Innovation Bias**
Funding agencies reward shiny new projects, not boring maintenance. But keeping software running is just as critical as building it.

### ⏰ **Grant Cycle Mismatch** 
Research grants last 2-5 years. Software maintenance is forever. When grants end, maintenance stops—and software breaks.

### 🏢 **Career Disincentives**
Universities reward faculty for publications, not software upkeep. Research software engineers have no clear career path for maintenance work.

## Real Consequences

<div class="consequence-grid">
  <div class="consequence-item">
    <h4>🚨 Research Disruption</h4>
    <p>When critical tools fail, entire research programs grind to a halt while researchers scramble for alternatives.</p>
  </div>
  
  <div class="consequence-item">
    <h4>💸 Wasted Resources</h4>
    <p>Researchers spend months troubleshooting broken software instead of doing science.</p>
  </div>
  
  <div class="consequence-item">
    <h4>🔄 Reproducibility Crisis</h4>
    <p>Broken or abandoned software makes reproducing scientific results impossible.</p>
  </div>
  
  <div class="consequence-item">
    <h4>🚧 Barriers to Entry</h4>
    <p>Poor documentation and unstable tools exclude newcomers and underrepresented groups.</p>
  </div>
</div>

## The Network Effect Problem

Research software doesn't exist in isolation. Tools depend on dozens of other packages. When one component fails, it can cascade through the entire ecosystem. **A single point of failure can break thousands of research workflows.**

### Example: The NumPy Near-Miss
NumPy—fundamental to scientific computing in Python—operated for years without dedicated funding despite supporting millions of researchers. Only heroic volunteer efforts and recent foundation support have stabilized it. **NumPy is the exception. Most research software lacks such visibility and support.**

## Why This Threatens Science Itself

**Science builds on previous work.** When research software fails, it doesn't just inconvenience current researchers—it breaks the chain of knowledge transfer that enables scientific progress.

**The sustainability crisis in research software is a threat to the continuity of scientific knowledge.**

---

<div class="solution-preview">
  <h2>There Is a Solution</h2>
  <p>The math is simple: just 0.1% of grant funding could solve this crisis completely. We know how to fix this—we just need to act.</p>
  <div class="solution-cta">
    <a href="/solution" class="btn btn-primary">See Our Solution</a>
    <a href="/get-involved" class="btn btn-secondary">Join the Movement</a>
  </div>
</div>

<style>
.crisis-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.stat-item {
  background: #fff5f5;
  padding: 1.5rem;
  border-radius: 8px;
  border-left: 4px solid #dc3545;
}

.stat-item h3 {
  color: #dc3545;
  margin-top: 0;
  margin-bottom: 1rem;
}

.consequence-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minMax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.consequence-item {
  padding: 1.5rem;
  border-radius: 8px;
  background: #f8f9fa;
  border-left: 4px solid #ff9800;
}

.consequence-item h4 {
  margin-top: 0;
  color: #ff9800;
  margin-bottom: 0.5rem;
}

.solution-preview {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 3rem 2rem;
  border-radius: 12px;
  text-align: center;
  margin: 3rem 0;
}

.solution-preview h2 {
  margin-top: 0;
  font-size: 2rem;
}

.solution-cta {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 1.5rem;
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

@media (max-width: 768px) {
  .crisis-stats,
  .consequence-grid {
    grid-template-columns: 1fr;
  }
  
  .solution-cta {
    flex-direction: column;
    align-items: center;
  }
}
</style>