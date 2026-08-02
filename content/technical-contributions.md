---
title: Technical Contributions
---

Selected articles I've written on production LLM systems and infrastructure.

<div class="contrib-cards">

<a href="https://rhesis.ai/post/migrating-to-kubernetes" class="contrib-card">
  <h3>Scoped Access, Managed Secrets, Self-Healing Deploys: Our Move to Kubernetes</h3>
  <p>A look at migrating infrastructure to Kubernetes, covering scoped access control, managed secrets, and self-healing deployment strategies.</p>
  <span class="read-more">Read article →</span>
</a>

<a href="https://rhesis.ai/post/deploying-custom-llm-in-production" class="contrib-card">
  <h3>Deploying a Custom LLM in Production: Four Architectures, Only One Works</h3>
  <p>A comparison of four architectures for deploying custom LLMs in production, examining why most approaches fall short and what actually works at scale.</p>
  <span class="read-more">Read article →</span>
</a>

<a href="https://rhesis.ai/post/self-hosting-llm-evaluation-framework" class="contrib-card">
  <h3>Self-Hosting Rhesis with Docker Compose</h3>
  <p>A guide to self-hosting the Rhesis LLM evaluation framework using Docker Compose.</p>
  <span class="read-more">Read article →</span>
</a>

</div>

<style>
.contrib-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.25em;
  margin-top: 1.5em;
}

.contrib-card {
  display: block;
  padding: 1.25em 1.5em;
  border: 1px solid #ddd;
  border-radius: 10px;
  text-decoration: none;
  color: inherit;
  transition: box-shadow 0.2s ease, transform 0.2s ease, border-color 0.2s ease;
}

.contrib-card:hover {
  box-shadow: 0 4px 14px rgba(0,0,0,0.08);
  transform: translateY(-2px);
  border-color: #999;
}

.contrib-card h3 {
  margin: 0 0 0.5em 0;
  font-size: 1.05em;
  line-height: 1.35;
  color: #1a0dab;
}

.contrib-card p {
  margin: 0 0 0.75em 0;
  font-size: 0.92em;
  line-height: 1.5;
  color: #444;
}

.contrib-card .read-more {
  font-size: 0.85em;
  font-weight: 600;
  color: #1a0dab;
}
</style>
