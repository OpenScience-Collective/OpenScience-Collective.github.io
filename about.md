---
layout: page
title: "The Problem"
permalink: /about/
---

# The Sustainability Crisis in Academic Open Source

Academic research increasingly depends on open-source tools, yet the sustainability of this critical infrastructure remains precarious. **This is not just a technical problem—it's a crisis that threatens the foundation of modern scientific research.**

## The Scale of the Problem

<div class="stats-container">
  <div class="stat-box">
    <h3>Critical Dependencies</h3>
    <p>Major research domains rely on a handful of essential tools:</p>
    <ul>
      <li><strong>Neuroscience:</strong> EEGLAB, FieldTrip, BrainStorm, MNE-Python, SPM</li>
      <li><strong>Bioinformatics:</strong> BioConductor, Galaxy, GATK</li>
      <li><strong>Physics:</strong> ROOT, Geant4, NumPy, SciPy</li>
      <li><strong>Climate Science:</strong> xarray, Dask, Matplotlib</li>
    </ul>
  </div>
  
  <div class="stat-box">
    <h3>Vulnerability Assessment</h3>
    <p>Recent analysis reveals alarming fragility:</p>
    <ul>
      <li>Loss of <strong>1-2 key maintainers</strong> could collapse entire ecosystems</li>
      <li>Most projects operate with <strong>insufficient funding</strong> for basic maintenance</li>
      <li>Critical infrastructure relies on <strong>volunteer labor</strong></li>
      <li>No systematic approach to <strong>succession planning</strong></li>
    </ul>
  </div>
</div>

## Why Traditional Funding Fails

### 🎯 **Grant Cycle Mismatch**
Traditional research grants typically last 2-5 years and focus on novel development. Software maintenance, however, requires **continuous, long-term support**. The mismatch creates dangerous gaps where established tools lose funding just as they become most valuable to the research community.

### 💡 **Innovation Bias**
Funding agencies naturally prioritize innovative, cutting-edge research. This creates a systematic bias against the "boring" but essential work of maintaining, documenting, and securing existing tools. The result: a graveyard of abandoned software and researchers constantly reinventing the wheel.

### 🏢 **Institutional Misalignment**
Universities reward faculty for publications and novel research, not for maintaining software. Research software engineers often lack clear career paths, leading to brain drain and loss of institutional knowledge. The very people best qualified to maintain research infrastructure are incentivized to move on.

### 📊 **Invisible Impact**
The impact of software maintenance is often invisible until something breaks. Unlike publications or patents, keeping software running doesn't generate measurable outputs that traditional evaluation systems recognize. This "success invisibility" perpetuates the underfunding cycle.

## Real-World Consequences

<div class="consequence-grid">
  <div class="consequence-item crisis">
    <h4>🚨 Critical Failures</h4>
    <p>When maintainers burn out or move on, essential tools become security risks, incompatible with new systems, or simply stop working. Entire research programs can grind to a halt.</p>
  </div>
  
  <div class="consequence-item waste">
    <h4>💸 Resource Waste</h4>
    <p>Researchers spend enormous time troubleshooting broken tools, working around bugs, or switching between incompatible software versions instead of focusing on science.</p>
  </div>
  
  <div class="consequence-item barrier">
    <h4>🚧 Entry Barriers</h4>
    <p>Poor documentation and user experience in underfunded tools create barriers for new researchers, particularly those from underrepresented groups or resource-constrained institutions.</p>
  </div>
  
  <div class="consequence-item reproducibility">
    <h4>🔄 Reproducibility Crisis</h4>
    <p>Broken or abandoned software makes reproducing scientific results difficult or impossible, undermining the reliability of scientific knowledge.</p>
  </div>
</div>

## The Network Effect Problem

Research software exists in complex dependency networks. A tool might seem stable because it's actively maintained, but it could depend on dozens of other packages, any of which could fail. This creates a **cascade vulnerability** where the failure of one small component can bring down entire research workflows.

### Example: The NumPy Foundation
NumPy, fundamental to scientific computing in Python, supports millions of researchers worldwide. Despite its critical importance, it operated for years without dedicated funding. Only recently, through heroic volunteer efforts and targeted foundation support, has it achieved some stability. But NumPy is the exception—most research software lacks such visibility and community support.

## Why This Matters for Science

**Science builds on previous work.** When research infrastructure fails, it doesn't just inconvenience current researchers—it breaks the chain of knowledge transfer that enables scientific progress. Future researchers lose access to tools and methods that embody decades of accumulated expertise.

The sustainability crisis in research software is, fundamentally, **a threat to the continuity of scientific knowledge itself.**

---

<div class="solution-preview">
  <h2>The Path Forward</h2>
  <p>The OpenScience Collective proposes a systematic solution that addresses these root causes through sustainable funding, professional career paths, and shared infrastructure. Learn how we can transform this crisis into an opportunity.</p>
  <div class="solution-cta">
    <a href="/solution" class="btn btn-primary">Explore Our Solution</a>
    <a href="/get-involved" class="btn btn-secondary">Join the Movement</a>
  </div>
</div>

<style>
.stats-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.stat-box {
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 8px;
  border-top: 4px solid #dc3545;
}

.stat-box h3 {
  color: #dc3545;
  margin-top: 0;
}

.stat-box ul {
  margin: 0;
  padding-left: 1.2rem;
}

.stat-box li {
  margin-bottom: 0.5rem;
}

.consequence-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.consequence-item {
  padding: 1.5rem;
  border-radius: 8px;
  border-left: 4px solid;
}

.consequence-item h4 {
  margin-top: 0;
  margin-bottom: 0.5rem;
}

.crisis {
  background-color: #fff5f5;
  border-color: #dc3545;
}

.waste {
  background-color: #fff8e1;
  border-color: #ff9800;
}

.barrier {
  background-color: #f3e5f5;
  border-color: #9c27b0;
}

.reproducibility {
  background-color: #e8f4fd;
  border-color: #2196f3;
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
  .stats-container {
    grid-template-columns: 1fr;
  }
  
  .consequence-grid {
    grid-template-columns: 1fr;
  }
  
  .solution-cta {
    flex-direction: column;
    align-items: center;
  }
}
</style>